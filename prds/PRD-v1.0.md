# PRD — automations.life Landing Page
**Versión:** 1.0  
**Fecha:** 2026-06-10  
**Estado:** Activo

---

## 1. Objetivo

Generar contactos calificados (leads) de empresas latinoamericanas que quieran automatizar sus procesos críticos usando agentes de IA conversacional. La conversión principal es que el visitante haga clic en "Hablar con un asesor" y contacte por WhatsApp.

---

## 2. Audiencia objetivo

- **Perfil:** Dueños o gerentes de PYMES en Latinoamérica
- **Sectores principales:** Salud (consultorios, centros de imágenes), ventas B2C/B2B, empresas con cartera vencida
- **Idiomas:** Español (primario), Inglés (secundario)

---

## 3. Estructura de la página

La página es un **single-page** con navegación por anclas. Secciones en orden:

| # | Sección | ID | Descripción |
|---|---------|-----|-------------|
| 1 | Nav | — | Logo, links de navegación, toggle de idioma, CTA |
| 2 | Hero | — | Headline, subtítulo, botón principal, stats |
| 3 | Cómo empezar | `#como-funciona` | 3 pasos para iniciar |
| 4 | Agentes | `#soluciones` | 3 cards de soluciones |
| 5 | Precios | `#precios` | Precio base y CTA a asesor |
| 6 | Contacto | `#contacto` | CTA final de conversión |
| 7 | Footer | — | Logo, links legales, copyright |

---

## 4. Navegación

| Botón | Destino |
|-------|---------|
| Inicio | Top de página (`#`) |
| Cómo empezar | `#como-funciona` |
| Agentes | `#soluciones` |
| Precios | `#precios` |
| Hablar con un asesor | WhatsApp `https://wa.me/573204701302` |

---

## 5. Contenido por sección

### 5.1 Hero
- **Headline:** "Nunca pierdas una cita, una venta o un cobro."
- **Subtítulo:** "Automatizamos con AI para reducir tus costos y aumentar tus ganancias."
- **CTA:** "Hablar con un asesor" → WhatsApp
- **Stats:**
  - +40% más citas agendadas
  - 3x más seguimiento comercial
  - -60% en cartera vencida

### 5.2 Cómo empezar
- **Tag:** Cómo empezar
- **Título:** Empieza en 3 pasos
- **Subtítulo:** "Sin meses de implementación. Sin equipos técnicos. Tu agente operando en días."
- **Pasos:**
  1. Nos cuentas tu proceso — llamada de 30 min
  2. Configuramos tu agente — tono, horarios, guiones
  3. Tu agente empieza a trabajar — 24/7

### 5.3 Agentes
- **Tag:** Nuestras soluciones
- **Título:** Un agente para cada proceso crítico
- **Cards:**
  1. **Agente de Agendamiento** — Consultorios médicos · Centros de imágenes
  2. **Ejecutivo Comercial AI** — Cualquier negocio con proceso de ventas
  3. **Agente de Cobro de Cartera** — Empresas con cartera vencida

### 5.4 Precios
- **Tag:** Precios
- **Título:** Desde 150 USD
- **Subtítulo:** "Habla con un asesor y te armamos un plan según tu operación."

### 5.5 CTA de contacto
- **Tag:** Empieza hoy
- **Título:** "¿Cuánto está perdiendo tu negocio hoy?"
- **Subtítulo:** "Cada cita no agendada, cada lead sin respuesta y cada cobro sin gestionar es dinero que se va. Hablemos."
- **CTA:** "Hablar con un asesor" → WhatsApp

### 5.6 Footer
- Links: Privacidad · Términos de uso · Contacto
- Copyright: © 2026 automations.life

---

## 6. Funcionalidades

| Feature | Estado |
|---------|--------|
| Cambio de idioma ES / EN | ✅ Implementado |
| Navegación por anclas (scroll suave) | ✅ Implementado |
| Nav fijo con blur | ✅ Implementado |
| Favicon SVG | ✅ Implementado |
| Meta description bilingüe | ✅ Implementado |
| Title bilingüe | ✅ Implementado |
| Responsive (mobile first) | ✅ Implementado |
| Testimonios / prueba social | ❌ Pendiente |
| Sección FAQ | ❌ Pendiente |
| Detalle de planes de precios | ❌ Pendiente |

---

## 7. Técnico

- **Stack:** HTML + CSS + JS vanilla (sin dependencias externas)
- **Archivo principal:** `index.html`
- **Favicon:** `favicon.svg`
- **Fuente:** Segoe UI / system-ui
- **Colores principales:**
  - Fondo: `#080C14`
  - Acento: `#00D4FF`
  - Texto: `#F0F4FF`

---

## 8. Pendientes identificados

1. **Prueba social** — Agregar testimonios o logos de clientes
2. **FAQ** — Preguntas frecuentes para reducir fricción
3. **Precios detallados** — Expandir sección con qué incluye cada plan
4. **Políticas** — Páginas de Privacidad y Términos de uso
5. **Analytics** — Integrar Google Analytics o similar

---

## Historial de versiones

| Versión | Fecha | Cambios |
|---------|-------|---------|
| 1.0 | 2026-06-10 | Versión inicial — estructura completa de la landing |

# JOTA — Web Engineering, WhatsApp E-Commerce & AI Automation Studio

Plataforma oficial de **JOTA** (Venezuela & Global), diseñada bajo la estética **Dark Kinetic Cyber-Organic** (`#060609` obsidiana, `#0D0E12` cristal, `#D9F99D` acid lime, `#10B981` esmeralda, `#F4F4F0` blanco hueso).

---

## 🏛️ Estructura & Secciones de la Landing Page

### 1. Top Fold (Hero Section con 3D Spline)
- **Floating Glass Pill Navbar:** Logotipo de JOTA, accesos directos a `[ Comparativa ]`, `[ Catálogo & Precios ]`, `[ Sistemas IA ]` y botón CTA de alto contraste.
- **Hero Grid (7 / 5 Columnas):**
  - **Columna Izquierda (7 cols):** Badge técnico `[ ● JOTA STUDIO // WEB & AI ENGINEERING ]`, titular H1 fluido con tipografía mixta (*'Syne'* 800 + *'Instrument Serif'* italic), propuesta de valor sin mensualidades y doble llamada a la acción.
  - **Columna Derecha (5 cols):** Canvas 3D de Spline (`@splinetool/viewer` async) con máscara de viñeta radial difuminada a `#060609` y un `IntersectionObserver` que apaga el renderizado al salir del viewport para mantener 60fps en smartphones.

### 2. Módulo Bento Comparativo: "Stop Renting" (`#comparativa`)
Contrasta de forma directa y contundente:
1. **Plataformas de Suscripción Genéricas:** $35 a $200/mes ($420 a $2,400 al año en rentas), comisiones por orden del 1.5% al 3%, si dejas de pagar te apagan la tienda.
2. **Agencias Tradicionales Locales:** $700 a $1,100 por sitios lentos en WordPress con plugins pesados, 3 a 6 semanas de entrega y cero agentes de IA.
3. **Ecosistema Propio JOTA:** Pago único por tu infraestructura propia (desde $120), cero comisiones por venta, velocidad de carga en <0.4s, sincronización automática de **Tasa Oficial BCV** y agentes de IA 24/7.

### 3. Creaciones & Portafolio en Vivo (`#creaciones`)
Muestra interactiva de proyectos reales en producción para generar confianza inmediata con clientes potenciales:
- **Once Sports (Valencia, Carabobo):** Catálogo e-commerce en vivo (`https://jotawebs.github.io/oncesports/`) con carrito flotante, checkout directo a WhatsApp, tasa oficial BCV automática, diseño oscuro athletic tech y velocidad de carga <0.4s.
- **Slot para Nuevos Despliegues:** Tarjeta de llamado a la acción para clientes que desean un nuevo proyecto en 48-72h.
- **Estructura Modular:** Diseñado con código limpio y comentado para que puedas añadir fácilmente nuevas creaciones duplicando la tarjeta de Once Sports.

### 4. Catálogo Interactivo de Servicios (`#catalogo`)
Pestañas dinámicas para alternar entre categorías y botón **"Agregar a mi cotización"** interactivo en cada producto:

#### Pestaña 1: Webs & Catálogos WhatsApp
- **Jota Launch (Landing / Catálogo Express):** **$120 Pago Único** (`$0/mes hosting base`). Carga en 0.4s, hasta 15 productos, checkout directo a WhatsApp. *Add-on seleccionable: + Dominio .com propio por $30*.
- **Jota Catálogo Pro (Full WhatsApp E-Commerce):** **$240 Pago Único** *(Soporte opcional: $25/mes)*. **[MÁS VENDIDO vs APPS DE $35-$100/MES]**. Dominio `.com` incluido, carrito avanzado, cálculo automático en Dólares y Bolívares con **Tasa Oficial BCV Automática**, reporte de Pago Móvil / Zelle / Binance, panel autogestionable o versión *Igniter* con pantalla de cocina.
- **Jota Corporate (Web Profesional de Alto Impacto):** **$490 (Español) / $750 (Bilingüe EN-ES)**. **[AHORRA +$350 VS AGENCIAS]**. Multipágina a 60fps, objeto 3D interactivo, SEO Google, correos corporativos y **Bono incluido: Video Motion Graphics IA (Hyperframes)**.

#### Pestaña 2: Automatización & Sistemas IA (`#ia`)
- **Jota AI Setter (Central Omnicanal Chatwoot + Agente IA):** **$380 Instalación + $55/mes**. Unifica WhatsApp, Instagram y Facebook en un solo CRM. Agente de IA entrenado que responde dudas, envía catálogo y califica leads 24/7 sin comisiones por mensaje.
- **Jota Custom Elite (Ecosistema Full Stack + IA / ERP / Visión):** **$890 a $1,200 Instalación + $80/mes**. Web Corporativa o E-Commerce + Agente IA 24/7 + Automatización avanzada a elección: Sistema de Inventario/Stock (**Carbon ERP**), Agendamiento Automático de Citas, o Cámaras con Detección IA Local (**Frigate Local**).

### 5. Barra Flotante & Checkout a WhatsApp
- Una barra dock inferior fija (`#cotizadorBar`) calcula en tiempo real la **Inversión Inicial Total** y el **Mantenimiento Mensual (si aplica)**.
- Botón **"Enviar Solicitud a WhatsApp ↗"** que compila la orden seleccionada con todos los detalles y abre el chat de WhatsApp con el mensaje pre-estructurado.

---

## 🛠️ Personalización del Número de WhatsApp

En la esquina inferior izquierda se encuentra el botón flotante **"⚙️ Vincular tu WhatsApp"**:
- Puedes ingresar tu número personal o de empresa con código de país (ej: `584120000000` o `13050000000`).
- Se guarda de forma persistente en el navegador (`localStorage`) y enlaza todas las cotizaciones a tu chat.

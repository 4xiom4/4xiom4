# Renato Miranda (Axioma) 👋

Desarrollador enfocado en el ecosistema **TypeScript**, **Next.js**, bases de datos relacionales y entornos **Linux**. Me interesa el desarrollo web moderno, las herramientas bien diseñadas y entender cómo funcionan las cosas por debajo: desde la contenerización con Docker y el rendimiento en el servidor, hasta la experiencia de usuario y la seguridad de los datos.

Santiago, Chile • [Email](mailto:rimadev@tuta.io) • [Mastodon](https://mastodon.social/@axioma1337) • [Buy Me a Coffee](https://buymeacoffee.com/axioma1337)

---

### 🛠️ Lo que suelo usar

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,nextjs,astro,tailwind,nodejs,postgres,redis,docker,linux,git,python" alt="Habilidades" />
  </a>
</p>

* **Frontend:** TypeScript, Next.js (App Router), React, Astro, Tailwind CSS, Framer Motion.
* **Backend & Persistencia:** Node.js, PostgreSQL (RLS), Drizzle ORM, Better-Auth, Redis / Valkey.
* **Infraestructura & Herramientas:** Docker, Docker Compose, Linux (CachyOS/Arch), Git, Turborepo, Biome.
* **Explorando:** WebSockets y eventos en tiempo real (Centrifugo), CMS Headless (Payload 3, Sanity).

---

### 🚀 Proyectos & Exploraciones

Gran parte de mi código está en repositorios privados (clientes y proyectos en desarrollo continuo). Aquí un resumen de lo que he estado construyendo y la arquitectura detrás:

#### ⚡ [0x1] — Plataforma FOSS de Soporte, Gestión & E-Commerce
> Monorepo auto-alojado que centraliza soporte técnico por tickets, seguimiento de proyectos, garantías y catálogo comercial.
* **Stack:** Next.js 15, Medusa v2, PostgreSQL 16 (RLS multi-tenant), Drizzle ORM, Better-Auth, Centrifugo v6, Valkey 8, Docker Compose.
* **Retos y arquitectura:**
  * **Migración arquitectónica:** Transición desde un stack SaaS dependiente (Supabase / Render / Upstash) hacia una arquitectura FOSS auto-alojada y contenerizada sobre VPS, con importación de usuarios con hash bcrypt sin forzar reseteos.
  * **Seguridad & Aislamiento:** Políticas estrictas de Row-Level Security (RLS) multi-tenant validadas mediante suites de tests automatizados para prevención de IDOR entre clientes y operadores.
  * **Tiempo Real:** Sistema de chat por ticket mediante WebSockets con Centrifugo v6 y tokens JWT efímeros por canal, respaldado por Valkey para sesiones y caché.
  * **Comercio desacoplado:** Integración con Medusa v2 headless y checkout local con MercadoPago.

#### 🏛️ [Athanor Platform]
> Sistema de gestión y catálogo multi-inquilino con enfoque Headless.
* **Stack:** Next.js, Payload CMS 3, PostgreSQL, Drizzle ORM, AWS S3, Upstash QStash, Cal.com.
* **Foco:** Arquitectura desacoplada, almacenamiento seguro de archivos con URLs prefirmadas en S3, y tareas en segundo plano mediante colas serverless con QStash.

#### 🏎️ [Swincar Detailing]
> Sitio web comercial para un negocio de detallado automotriz.
* **Stack:** Next.js, React, Tailwind CSS, Framer Motion.
* **Foco:** Experiencia de usuario interactiva y fluida con comparador visual de imágenes antes/después y flujo rápido de cotización y reservas.

#### 🌌 [Pleroma Monorepo]
> Monorepo que combina portal web y automatizaciones con bots.
* **Stack:** Turborepo, Astro, React, Sanity CMS, Discord.js, Tesseract.js (OCR), Zod.
* **Foco:** Arquitectura modular con paquetes compartidos de tipos y lógica (`@pleroma/shared`), renderizado de contenido dinámico y extracción de texto en imágenes vía OCR.

---

### 📊 Actividad

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=4xiom4&show_icons=true&count_private=true&theme=tokyonight&hide_border=true" height="145" alt="Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=4xiom4&layout=compact&theme=tokyonight&hide_border=true" height="145" alt="Top Langs" />
</p>

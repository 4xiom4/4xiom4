<div align="center">

# ¡Hola, soy Renato (Axioma)! 👋

**Analista Programador & Ingeniero en Computación**  
*Construyendo software web moderno, arquitecturas FOSS auto-alojadas y trasteando con Linux.*

[![Email](https://img.shields.io/badge/Email-rimadev%40tuta.io-2563EB?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:rimadev@tuta.io)
[![Mastodon](https://img.shields.io/badge/Mastodon-@axioma1337-6366F1?style=for-the-badge&logo=mastodon&logoColor=white)](https://mastodon.social/@axioma1337)
[![CachyOS](https://img.shields.io/badge/OS-CachyOS_(Arch)-00adff?style=for-the-badge&logo=archlinux&logoColor=white)](https://cachyos.org)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/axioma1337)

</div>

---

### 💡 Sobre mi enfoque

Me apasiona entender el software desde el kernel hasta la interfaz. Disfruto diseñar herramientas ágiles, desacopladas y con soberanía de datos: cambiar dependencias de cajas negras SaaS por stacks FOSS auto-alojados en Docker, cuidar el modelado relacional con seguridad a nivel de filas (RLS), y crear experiencias web fluidas y con identidad propia.

---

### 🛠️ Tech Stack en Acción

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,nextjs,astro,tailwind,nodejs,postgres,redis,docker,linux,python,git" alt="Habilidades" />
  </a>
</p>
┌─────────────────┬──────────────────────────────────────────────────────────────┐ │ Capa │ Herramientas & Tecnologías │ ├─────────────────┼──────────────────────────────────────────────────────────────┤ │ 🌐 Frontend │ TypeScript, Next.js 15 (App Router), React, Astro, Tailwind, │ │ │ Framer Motion, Base UI │ │ ⚙️ Backend │ Node.js, Better-Auth, Drizzle ORM, Payload CMS v3 (Code-first)│ │ 🗄️ Datos & Caché│ PostgreSQL 16 (RLS multi-tenant), Valkey 8 / Redis, R2 / S3 │ │ ⚡ Real-Time/Ops│ Centrifugo v6 (WebSockets), Upstash QStash, Docker Compose │ │ 🐧 Ecosistema │ CachyOS / Arch Linux, PipeWire Audio, Turborepo, Biome, Python│ └─────────────────┴──────────────────────────────────────────────────────────────┘


---

### 🚀 Proyectos Destacados (Fórmula X-Y-Z)

> Gran parte de mi trabajo activo reside en repositorios privados (clientes y plataformas propias). Aplico la metodología de **Logro [X] + Medición/Impacto [Y] + Cómo técnico [Z]** para mostrar la ingeniería detrás de cada uno:

#### ⚡ **0x1 — Plataforma FOSS de Soporte & Gestión en Tiempo Real**
* **[X] Logro:** Diseñé y migré la plataforma integral de tickets, garantías y seguimiento técnico desde un ecosistema SaaS fragmentado hacia un monolito contenerizado 100% FOSS auto-alojado.
* **[Y] Impacto:** Eliminé el 100% de costos de suscripción a terceros (Supabase/Upstash/Render), aseguré 0 fugas de aislamiento de datos en **22 tests automáticos de seguridad RLS**, e importé usuarios con sus contraseñas en hash bcrypt sin obligar a ningún usuario a resetear su clave.
* **[Z] Cómo técnico:** Orquesté un stack local con **Docker Compose** unificando **Next.js 15**, **PostgreSQL 16** con Row-Level Security estricto, sesiones ultrarrápidas con **Valkey 8**, y canales de chat por ticket mediante WebSockets autorizados por JWT con **Centrifugo v6**.

---

#### 🏛️ **ATHANOR — Motor White-Label & CMS Multi-Tenant**
* **[X] Logro:** Desarrollé una plataforma modular de gestión y presencia web orientada a negocios de estética y servicios (Cliente 0: *Swingcar Detailing*).
* **[Y] Impacto:** Reduje al 0% la carga de ancho de banda del servidor de aplicaciones al gestionar almacenamiento multimedia mediante subidas directas y URLs prefirmadas a buckets Cloudflare R2 / AWS S3, desacoplando tareas asíncronas de fondo.
* **[Z] Cómo técnico:** Implementé una arquitectura *code-first* con **Payload CMS v3** montado sobre **Next.js 15 (App Router)** y **PostgreSQL**, con orquestación de colas y cron serverless mediante **Upstash QStash**, agendas dinámicas con **Cal.com** e interfaces con **Tailwind + Framer Motion**.

---

#### 🏎️ **Swingcar Detailing — Web Comercial de Alta Conversión**
* **[X] Logro:** Construí la presencia digital comercial para un centro automotriz premium en La Serena, enfocado en mostrar el valor del trabajo artesanal y cerrar cotizaciones directas.
* **[Y] Impacto:** Maximizé la retención y conversión de visitantes sustituyendo galerías estáticas tradicionales por una experiencia visual interactiva de antes/después con soporte táctil total.
* **[Z] Cómo técnico:** Desarrollé una SPA de alto rendimiento con **Next.js**, **React**, tipado estricto en **TypeScript**, animaciones fluidas con **Framer Motion**, sliders interactivos de comparación y pipeline de cotización rápida.

---

#### 🌌 **Pleroma Monorepo — Ecosistema Web & Automatización con OCR**
* **[X] Logro:** Construí un monorepo que sincroniza el portal web informativo de la comunidad con un bot autónomo para validación de miembros.
* **[Y] Impacto:** Ahorré horas de moderación manual automatizando la verificación de capturas de pantalla de usuarios mediante lectura óptica de caracteres (OCR) y validación de esquemas en tiempo real.
* **[Z] Cómo técnico:** Estructuré un monorepo con **Turborepo** y **Biome**, enlazando una web ultra-ligera en **Astro + Sanity CMS** con un bot en **Node.js (Discord.js)** que procesa imágenes con **Tesseract.js** y valida datos compartidos con **Zod**.

---

#### 🎧 **PipeWire Audio Streamer — Automatización de Audio en Linux**
* **[X] Logro:** Creé una utilidad de escritorio para CachyOS / Arch Linux que enruta dinámicamente audio de cualquier aplicación hacia un bot de Discord con cero latencia añadida.
* **[Y] Impacto:** Resolvió las limitaciones de captura de audio en servidores de sonido modernos en Linux, permitiendo rutear flujos de audio independientes de videojuegos o reproductores sin mezclar el micrófono personal.
* **[Z] Cómo técnico:** Construido en **Python** con interfaz moderna en **CustomTkinter**, gestionando sinks virtuales (*null-sinks*) de **PipeWire / PulseAudio** en tiempo de ejecución mediante llamadas nativas a `pactl`.

---

### 📊 Actividad & Rendimiento

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=4xiom4&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0d1117" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=4xiom4&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" height="150" alt="Top Languages" />
</div>

<br />

<div align="center">
  <sub>Diseñado con cariño desde la terminal • CachyOS Linux • <i>"FOSS first, always curious."</i></sub>
</div>

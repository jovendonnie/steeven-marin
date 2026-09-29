# Steeven — Full-Stack Developer (React · Node.js)

Desarrollador Full-Stack basado en Medellín, Colombia, enfocado en construir productos completos de punta a punta — desde la arquitectura y el desarrollo hasta la documentación técnica y el despliegue en producción. Trabajo principalmente con React, Node.js y TypeScript, con experiencia adicional en React Native.

Mis repositorios de producto propio y de proyectos de cliente son privados, así que aquí abajo tienes contexto real de lo que he construido, con demos en vivo.

## Proyectos destacados

### Sendix — Capa de orquestación de email
**[sendix.lat](https://www.sendix.lat/)**

Sendix es un producto propio. Nació como un envío masivo de correos ("bulk email sender") y evolucionó hacia algo más específico y con más valor: una **capa de orquestación de email** que se sienta sobre proveedores como Resend o SendGrid, resolviendo un problema real de ese tipo de servicios — qué pasa cuando un proveedor falla o se degrada a mitad de un envío. Sendix agrega fallback automático entre proveedores, reintentos inteligentes y observabilidad de entregas vía webhooks, en la misma línea de productos como Courier.com o Knock.app.

Lo construí de punta a punta: producto, arquitectura, desarrollo e infraestructura.

- **Stack:** Node.js, TypeScript, PostgreSQL (Neon), Clerk (autenticación), AWS SES (verificación de dominio, configuración de SPF/DMARC/DKIM), desplegado en DigitalOcean.
- **Más allá del código:** desarrollé una suite completa de documentación técnica en formato APA 7ª edición — alcance, requisitos funcionales y no funcionales, casos de uso, historias de usuario, arquitectura de software, diagramas UML, modelo entidad-relación, una presentación y wireframes/prototipos de 5 pantallas — generada con tooling propio en Node.js (ReportLab, la librería docx, Playwright).
- **Estado actual:** en fase de relanzamiento, trabajando en escalarlo como producto real.

### Bancarrota — Plataforma de precalificación legal (Hispacontact)
**[Demo en vivo](https://proyecto-elegibilad-bancarota-front.vercel.app/)**

Plataforma web desarrollada para Hispacontact, un bufete legal que atiende a la comunidad hispana en Florida (EE. UU.), para digitalizar su proceso de precalificación de casos de bancarrota — antes completamente manual.

Construí una landing page, un wizard de precalificación multi-paso para que el usuario evalúe si califica, y un panel administrativo donde el abogado revisa cada solicitud y emite una decisión (aprobada o rechazada), con notificaciones automáticas por correo tanto al bufete como al usuario sobre el resultado.

- **Stack:** React, Vite, Tailwind CSS, Node.js, Express, MongoDB Atlas · desplegado en Firebase Hosting (frontend) y Google Cloud Run (backend) · Nodemailer + Gmail para notificaciones.
- **Decisión técnica relevante:** migré la arquitectura de un monorepo (monolito modular) a repositorios separados de backend y frontend, tras identificar a tiempo un problema de escalabilidad.
- **Estado actual:** la Fase 1 (landing + wizard + panel admin con flujo de decisión del abogado) está completa y en producción. Actualmente en desarrollo activo la Fase 2 — un Portal del Cliente de 8 etapas, construido primero como prototipo con integraciones externas simuladas para validar el flujo completo antes de conectarlas de verdad.

## Stack y herramientas

**Frontend:** React · React Native · TypeScript · JavaScript · Tailwind CSS · Vite
**Backend:** Node.js · Express · REST APIs
**Bases de datos:** PostgreSQL · MongoDB · Neon
**Infraestructura:** Docker · DigitalOcean · Firebase Hosting · Google Cloud Run · AWS SES
**Otros:** Clerk · Stripe · Nodemailer · Git

## Contacto

- Email: marinstvvnn@gmail.com
- LinkedIn: *(agrega aquí tu URL)*
- Portafolio: *(agrega aquí cuando esté publicado)*
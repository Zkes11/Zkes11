<div align="center">

# Santiago Rodríguez Rojas
**Backend Engineer · Microservicios · IA aplicada a producción**

Colombia 🇨🇴 · santiago11ro11@gmail.com

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:santiago11ro11@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Zkes11-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Zkes11)

</div>

---

## 👋 Sobre mí

Backend developer enfocado en **sistemas distribuidos**, **seguridad** e **integración de IA en producción**. Estudiante de Ingeniería de Software.

Disfruto más el lado duro del backend: arquitectura de microservicios, observabilidad, RAG con LLMs y el **code review exigente** que levanta la calidad de todo el equipo. Cuando algo se rompe en producción, soy de los que prefiere leer logs hasta encontrar la causa raíz en vez de reiniciar y rezar.

---

## 🧭 Stack por nivel de manejo

### 🏗️ Avanzado — lo uso en producción y tomo decisiones de arquitectura
- **NestJS + TypeScript** — microservicios con API Gateway, JWT fail-fast, validación de secretos por entropía (Shannon), guards internos con `x-internal-service-token`
- **Node.js (Express / Fastify)** — BFF, proxies, middlewares de seguridad (CORS fail-closed, Helmet)
- **PostgreSQL + Prisma** — modelado, migraciones, RLS multi-tenant
- **MySQL** — replicación lectura/escritura contra monolitos legacy
- **Docker + docker-compose** — multi-stage builds, optimización del runtime, aislamiento por servicio
- **Railway** — deploy de microservicios, debugging de crashes en vivo
- **React + Vite + Redux Toolkit** — feature-sliced, slices puras testeables, design tokens compartidos vía npm workspaces

### 🤖 IA — integración real en producción
- **LLM (OpenAI-compatible, Claude, Gemini)** — prompts clínicos, guardrails anti-inyección
- **RAG** — pipeline completo: chunking, embeddings, pgvector, retrieval por scope
- **Triage clínico asistido por IA** — catálogos versionados validados con Zod, reglas duras deterministas, safety policy fail-closed

### ⚙️ Intermedio — lo construí y lo mantengo con bases sólidas
- **Go** — microservicios con gRPC y Clean Architecture *(experiencia previa, ver Sistema de Campañas IA abajo)*
- **Python (FastAPI, scripting, Pygame)** — integraciones, herramientas CLI, juegos educativos
- **Flutter / Dart** — apps multiplataforma con arquitectura limpia
- **Redis** — caching de embeddings y rate limiting
- **GitHub Actions** — CI con typecheck / lint / build / test / validadores custom
- **Vitest + Playwright** — unit + E2E
- **Traefik** — API Gateway con load balancing

### 🧪 Roles que hago más allá de codear
- **Code review senior estricto** — severidad BLOCKER / MAJOR / MINOR, incluso en superficies safety-críticas (crisis, salud mental)
- **Security audits** — estilo OWASP, threat modeling sobre PRs
- **Debugging de producción** — diagnóstico root-cause desde logs + hotfixes limpios y.chicos
- **Arquitectura** — diseño de servicios, contratos entre equipos, planes de migración

### 🔭 Explorando
- **Go para alto throughput** (más allá del proyecto que ya entregué)
- **PyTorch / LSTM** para predicción de series temporales
- **Kubernetes** avanzado (más allá del docker-compose)

---

## 🚀 Proyectos destacados

### 🧠 App_Psicologia — Plataforma clínica con IA *(activo)*
Sistema de salud mental multi-rol (paciente, practitioner, admin) con detección de crisis en tiempo real.
- **10 microservicios NestJS** detrás de un API Gateway (Auth, Accounts, Case, Activity, Admin, Crisis, Notification, AI Orchestrator…)
- **AI Orchestrator con RAG** sobre DSM-5 / CIE-11 / catálogo de triaje, con safety policy fail-closed y regla de oro determinista para riesgo crítico
- **3 frontends React+Vite** (Patient, Admin, Practitioner) con paleta compartida vía npm workspace
- **Deploy en Railway** + Docker + GitHub Actions
- **Mi rol**: arquitecto del AI Orchestrator y reviewer senior de los PRs del equipo

### 🟦 Sistema de Campañas IA — Plataforma multi-tenant en Go *(entregado, inactivo)*
Plataforma enterprise para automatización de campañas publicitarias con IA (Meta Ads API). Lo construí en **dos versiones funcionales (v1 y v2)** que quedaron productivas; hoy ya no trabajo en el proyecto.
- **6 microservicios en Go** (auth, content, campaign-analyzer, campaign-template, meta-ads, mcp-search) + Python para IA
- **gRPC** entre servicios + **Traefik** como API Gateway
- **PostgreSQL multi-tenant** con Row Level Security, RBAC con 6 roles / 25 permisos, JWT con token blacklist
- **Integración Meta Ads API** (Facebook/Instagram), generación de copys e imágenes con LLM
- ~350 archivos Go, evolución de monolito legacy → arquitectura de microservicios

### 🏍️ MOTORS — E-commerce premium de motos
Monorepo (npm workspaces + Turborepo) con frontend React+Vite, BFF Gateway en Fastify y microservicios hexagonales. Checkout robusto con manejo de fallos parciales, carrito persistente, tests E2E con Playwright.

### 🎮 PythonEscape — Aprende Python jugando
Juego educativo en Pygame con arquitectura por capas (SOLID), 7 escenarios interconectados, sistema de niveles progresivos y tests con pytest.

---

## 📫 Contacto

✉️ **santiago11ro11@gmail.com** · 🐙 **[@Zkes11](https://github.com/Zkes11)**

---

<div align="center">

*"La disciplina y la consistencia construyen desarrolladores excepcionales"*

</div>

### Hi, I'm Eze 

Full stack developer based in Buenos Aires. I work with TypeScript, React, Next.js, and Node.js, using Python for automation and scripting. English C2.

Looking for full stack or frontend roles in Buenos Aires or remote. The three projects below are live and tested, and I also fix bugs in the open source tools I depend on.

### Open Source Contributions

Three bug fixes merged into open source tools and libraries:

- **[vitest](https://github.com/vitest-dev/vitest/pull/11360)** (17.2k ★): fixed an issue where `vm` pools executed Vite's dependency optimizer over `index.html`, causing unbundlable dependencies to crash the run with `exit 1` while every test passed. Traced it back to the commit that introduced it; its author later approved the fix.
- **[vitest](https://github.com/vitest-dev/vitest/pull/11781)** (second fix there): the module cache killed the whole run when its directory could not be created, with an error unrelated to the test. The maintainer asked to disable the cache up front instead of catching the error late, and the final design came out smaller than my first version.
- **[@fastify/cookie](https://github.com/fastify/fastify-cookie/pull/377)**: `reply.setCookie()` accepted an `encode` option and silently ignored it, so there was no way to customize how the value is encoded. Merged with two maintainer approvals and released in `v11.1.5`.

### Projects

**[Relevy](https://github.com/ezefernandezyf/relevy)** · [relevy.app](https://relevy.app)
GEO/SEO auditing platform in production. 46,000 lines across 21 sprints, **1,119 tests**, and 4 CI jobs. Built end-to-end: React 19, Next.js 15, Node.js, PostgreSQL.

**[EchoLog](https://github.com/ezefernandezyf/echolog)** · [live demo](https://echolog-web.vercel.app)
Multi-tenant feedback SaaS built across 18 development phases and ~45 reviewed PRs. React 19, Express, Prisma, PostgreSQL. Tests in three layers, running in CI.

**[Nexus Talent](https://github.com/ezefernandezyf/nexus-talent)** · [live demo](https://nexustalent.vercel.app)
AI-powered recruiting platform. The model runs server-side and its output is validated with Zod before it reaches the UI, with 502 handling and automatic fallback between Groq and Google. React 19, Express, Prisma. **542 tests.**

**More:** [geo-seo-opencode](https://github.com/ezefernandezyf/geo-seo-opencode) (CLI for AI search engine optimization in Python/Bash) · [egg-ai-readiness-diagnostic](https://github.com/ezefernandezyf/egg-ai-readiness-diagnostic) (AI maturity diagnostic for Egg.live) · [ia-recipe-generator](https://github.com/ezefernandezyf/ia-recipe-generator) · [cinelab-react](https://github.com/ezefernandezyf/cinelab-react).

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

*Also:* Express, Zod, Tailwind CSS, Docker, GitHub Actions, Git (Feature Branching, PR Code Reviews).

### Links

[![Portfolio](https://img.shields.io/badge/Portfolio-ezefernandez.com-8B5CF6?style=flat-square&logo=googlechrome&logoColor=white)](https://ezefernandez.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ezequiel-fernandez-59a21a387/)

---

### Hola, soy Eze 

Desarrollador full stack en Buenos Aires. Trabajo con TypeScript, React, Next.js y Node.js, y Python para automatización. Inglés C2.

Busco un rol full stack o frontend, en Buenos Aires o remoto. Los tres proyectos de abajo están desplegados y con tests, y también arreglo bugs en las herramientas open source que uso.

**Contribuciones:** tres arreglos de bugs mergeados, dos en [vitest](https://github.com/vitest-dev/vitest/pull/11360) (17.2k ★: el optimizador de dependencias, rastreado hasta el commit que lo introdujo, y el cache de módulos) y uno en [@fastify/cookie](https://github.com/fastify/fastify-cookie/pull/377) (publicado en v11.1.5).

**Proyectos:** [Relevy](https://relevy.app) (auditoría GEO/SEO con 1.119 tests) · [Nexus Talent](https://nexustalent.vercel.app) (reclutamiento con IA y 542 tests) · [EchoLog](https://echolog-web.vercel.app) (SaaS multi-tenant con CI/CD y 3 capas de testing).

[Portfolio](https://ezefernandez.com) · [LinkedIn](https://www.linkedin.com/in/ezequiel-fernandez-59a21a387/)

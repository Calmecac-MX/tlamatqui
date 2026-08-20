# Changelog - Tlamatqui

Todos los cambios notables en este proyecto son documentados automáticamente de acuerdo con **Conventional Commits** y **Release Please**.

---

## [2.6.0](https://github.com/Calmecac-MX/tlamatqui/compare/tlamatqui-v2.5.0...tlamatqui-v2.6.0) (2026-08-20)


### 🚀 Features & Nuevas Funcionalidades

* **admin:** actualizar etiqueta a Configuración de Branding y remover campo de archivo/URL de logo ([5a77c92](https://github.com/Calmecac-MX/tlamatqui/commit/5a77c924be692ac946c8caff65e800762391d5a2))
* **auth:** rediseñar LoginPage para Auth0 Universal Login exclusivo con logo de instancia v2.5.25 ([535cebf](https://github.com/Calmecac-MX/tlamatqui/commit/535cebf95d9528fea0fcd09a2acde37ce1eef8e4))
* **changelog:** agregar soporte de archivos por versión en changelog/ y regla obligatoria de commits ([9c1618d](https://github.com/Calmecac-MX/tlamatqui/commit/9c1618df88dfe389fc75f6def1b25f4830f6844f))
* **config:** agregar campos para logos 2 y 3 en configuración global ([50d9942](https://github.com/Calmecac-MX/tlamatqui/commit/50d9942ca5345a909293e0cb5a53372f5d4674d0))
* **config:** agregar compartir reportes en dominio personalizado con verificacion TXT (Frontend v2.5.20 / Backend v2.5.10) ([b59d9b4](https://github.com/Calmecac-MX/tlamatqui/commit/b59d9b4ea65512d4409b0d98dda3ce3a026a002e))
* **dns:** auto-registrar dominio automaticamente en Vercel API al guardar o consultar (Frontend v2.5.22 / Backend v2.5.12) ([b9d2695](https://github.com/Calmecac-MX/tlamatqui/commit/b9d269535375b30d31f31b51b9c9894e9593048c))
* **dns:** integrar API de Vercel para auto-aprovisionamiento y diagnostico en vivo 4-checkpoints (Frontend v2.5.21 / Backend v2.5.11) ([4960fe7](https://github.com/Calmecac-MX/tlamatqui/commit/4960fe72527330e8cda41f21b424f3bc11513b46))
* **env:** configurar variables de entorno y soporte CORS para ejecucion desacoplada ([7483b73](https://github.com/Calmecac-MX/tlamatqui/commit/7483b730bbc7653b0ca2bcfa00fb774c50514769))
* **prisma:** actualizar paquete y cliente a Prisma 7.9.1 con soporte para prisma.config.ts (v2.5.27 / v2.5.18) ([5a43e5e](https://github.com/Calmecac-MX/tlamatqui/commit/5a43e5eb6afac6382859e1f11556212c436ad310))
* **rules:** crear regla dedicada para el ecosistema Caveman en .agents/rules/caveman-rules.md ([c411890](https://github.com/Calmecac-MX/tlamatqui/commit/c411890ec346d3d23984fcf83e0df47c7917e618))
* **rules:** crear sistema modular de reglas de IA en .agents/rules/ ([1023197](https://github.com/Calmecac-MX/tlamatqui/commit/1023197a230480a18ec66223f7ceb563cc864211))
* **security:** aplicar cifrado transparente de datos sensibles en reposo mediante ENCRYPTION_KEY en la capa de persistencia (v2.5.26 / v2.5.17) ([e0319fa](https://github.com/Calmecac-MX/tlamatqui/commit/e0319fa78aaf8bd88274f62b1291fe3ca7e9abed))
* **security:** implementar token secreto x-api-secret para comunicacion cliente-servidor (v2.5.26 / v2.5.15) ([b55abeb](https://github.com/Calmecac-MX/tlamatqui/commit/b55abeb91394a9e8238c1059ad0e9a72826af4b2))
* **security:** integrar servicio de encriptacion AES-256-GCM y firmas HMAC utilizando ENCRYPTION_KEY (v2.5.26 / v2.5.16) ([94151da](https://github.com/Calmecac-MX/tlamatqui/commit/94151da430e87ac851663b3317a8576e88ce4041))
* **smtp:** implementar servicio de envio de reportes por correo electronico via SMTP ([d7b5ff8](https://github.com/Calmecac-MX/tlamatqui/commit/d7b5ff87e399798308c8ceb44ee6c7d8b2bdbb5f))
* **teams:** permitir invitar miembros a un equipo a traves de un enlace corto (Frontend v2.5.23 / Backend v2.5.13) ([4cbf1e9](https://github.com/Calmecac-MX/tlamatqui/commit/4cbf1e9af1eba5bfb5ffec5aae9e13bee6aa0130))
* **ui:** actualizar el titulo de la pestana a Tlamatqui ([c8b91a4](https://github.com/Calmecac-MX/tlamatqui/commit/c8b91a4ad6091c0669bcc6f9de7e48a909a4069d))
* **ui:** establecer titulo dinamico del reporte web como Reporte de {{marca}} | Tlamatqui ([94939d0](https://github.com/Calmecac-MX/tlamatqui/commit/94939d0758d569e0c44489ad502eaad780ed1af2))


### 🐛 Corregido & Bug Fixes

* **ci:** corregir sintaxis YAML de comillas en titulo de docker-publish workflow ([bd08b33](https://github.com/Calmecac-MX/tlamatqui/commit/bd08b332e5ca1e63374abbc8dd711488eee71644))


### ⚡ Optimización y Rendimiento

* **changelog:** optimizar generación de changelogs y reducir peso del repositorio v2.5.25 ([d930dc4](https://github.com/Calmecac-MX/tlamatqui/commit/d930dc4724e94ccd0e272263d14d7ca32f3186e5))


### ♻️ Refactorización de Código

* **admin:** renombrar panel de administracion a Tlachiālōyan y establecer slug /tlachialoyan ([b8d3612](https://github.com/Calmecac-MX/tlamatqui/commit/b8d3612a7c9f56d89d4f30693fd902ccbec76fc3))


### 📚 Documentación

* **changelog:** actualizar changelog con cambios de Configuración de Branding ([ef436d7](https://github.com/Calmecac-MX/tlamatqui/commit/ef436d795bcf408c5f9cccd1ef7c88819838b5d0))
* **changelog:** actualizar changelog con el titulo Tlamatqui ([6e03064](https://github.com/Calmecac-MX/tlamatqui/commit/6e030643f316cec533eec4c856d6f7b375dbb9d6))
* **changelog:** actualizar changelog con la creación del sistema modular de reglas ([50d1ab7](https://github.com/Calmecac-MX/tlamatqui/commit/50d1ab7a78939170c66fdcac6026e7a91fd3d5bd))
* **changelog:** actualizar changelog con la funcionalidad SMTP ([1b1490b](https://github.com/Calmecac-MX/tlamatqui/commit/1b1490b2777175d0b2018f425054d002c7e0d338))
* **changelog:** actualizar changelog con registro de cerebros y datos ([7bbfff4](https://github.com/Calmecac-MX/tlamatqui/commit/7bbfff4414a5e84aa4702db272b6f31cb754d5de))
* **changelog:** actualizar changelog con registro de Licencia AGPL-3.0 ([a8a6db3](https://github.com/Calmecac-MX/tlamatqui/commit/a8a6db3c073b4f317f8afd045ac02c8de06f00d3))
* **changelog:** actualizar changelog con regla de Caveman Mode ([a0b0910](https://github.com/Calmecac-MX/tlamatqui/commit/a0b091095dbb9155a591b515a342b949d976cf9c))
* **changelog:** actualizar changelog con renombrado Tlachiālōyan y slug /tlachialoyan ([14064e3](https://github.com/Calmecac-MX/tlamatqui/commit/14064e3b5fe62e4a2af0bd5d9d45ac6fd624321c))
* **changelog:** actualizar changelog con titulo dinamico de reporte por marca ([4e990c3](https://github.com/Calmecac-MX/tlamatqui/commit/4e990c31a2a74fe425e21e831d2a7dbd7ed89653))
* **changelog:** actualizar changelog raíz y archivos por versión con último commit ([50cc9ce](https://github.com/Calmecac-MX/tlamatqui/commit/50cc9ce3143a5f9348bafd5fec7d27c6d3bb7b1f))
* **changelog:** actualizar changelog tras establecer directiva de cerebros ([d501d0f](https://github.com/Calmecac-MX/tlamatqui/commit/d501d0f5bb4fcbf5c6a7c52cb59779d72dc6f618))
* **changelog:** actualizar changelog tras revision de .gitignore ([5aca9ed](https://github.com/Calmecac-MX/tlamatqui/commit/5aca9edad39a4317674838e5b96a654b87ad1aa5))
* **changelog:** actualizar CHANGELOG.md y extractos por version ([367af3b](https://github.com/Calmecac-MX/tlamatqui/commit/367af3b26d8c711d9303cb812c1eb26fa3989eb5))
* **changelog:** registrar cambios de versión v2.5.5 en changelogs ([ece4511](https://github.com/Calmecac-MX/tlamatqui/commit/ece4511036bd033de2136a8d90124fba21018b4f))
* **changelog:** sincronizar registro de changelog con ultimo commit ([23b0d7c](https://github.com/Calmecac-MX/tlamatqui/commit/23b0d7c45782db2bc6a29ad55a1b7cc0eeed15c8))
* **ci:** actualizar documentacion de cerebros con permisos de docker-publish workflow ([34aaf4b](https://github.com/Calmecac-MX/tlamatqui/commit/34aaf4b45a40e81ccaafed5213e9163b321390a1))
* **context:** actualizar el contexto de los cerebros y datos del proyecto ([d720ce3](https://github.com/Calmecac-MX/tlamatqui/commit/d720ce379912c1aaa5f3b9b4e38076ad1d6fa704))
* **release:** actualizar cabeceras de version de cerebros a v2.5.28 / v2.5.19 ([858df79](https://github.com/Calmecac-MX/tlamatqui/commit/858df7998c9dcb9ad87398f37b942f7674f6bc89))
* **rules:** actualizar nombre del proyecto a Tlamatqui en la ruta de la IA y documentación ([4248b88](https://github.com/Calmecac-MX/tlamatqui/commit/4248b88c1f060ea06fa54e22d383f4bc7feef2f1))
* **rules:** añadir regla obligatoria de envio de cambios via PR con aprobacion explicita ([1a35785](https://github.com/Calmecac-MX/tlamatqui/commit/1a357859b8ed0bb61b5a3fcdbb254403a5473058))
* **rules:** establecer directiva obligatoria de registro en cerebros y documentacion IA ([c3d1797](https://github.com/Calmecac-MX/tlamatqui/commit/c3d1797100df2ffb4242e8962f228b5a96570ea5))


### 🔧 Tareas Operativas y Mantenimiento

* **git:** actualizar .gitignore con reglas de ignorado estructuradas ([dad0315](https://github.com/Calmecac-MX/tlamatqui/commit/dad031549b12869a5d9f2107a3d80b47f5ce2c98))
* **license:** añadir licencia GNU Affero General Public License v3.0 (AGPL-3.0) ([d216ee0](https://github.com/Calmecac-MX/tlamatqui/commit/d216ee097c5bc39be706fd1cb537776fe229f61b))
* **prisma:** crear archivo de configuracion prisma.config.ts para soporte oficial de Prisma CLI y Language Server ([562e5f5](https://github.com/Calmecac-MX/tlamatqui/commit/562e5f5a5604b86dfdfe48430cf2975b3ca91cab))
* **release:** v2.5.28 (Frontend) / v2.5.19 (Backend) ([6d02bfd](https://github.com/Calmecac-MX/tlamatqui/commit/6d02bfd3804698a4220a324f4d8bd1556858b3bb))
* remove legacy project documentation and architecture proposal files ([3f5bc24](https://github.com/Calmecac-MX/tlamatqui/commit/3f5bc241d1c94150424f42f9286b116628399e65))

## [v2.5.28 (Frontend) / v2.5.19 (Backend)] - 2026-08-20

### 🚀 Features & Nuevas Funcionalidades
- **prisma:** actualizar paquete y cliente a Prisma 7.9.1 con soporte para prisma.config.ts (v2.5.27 / v2.5.18) (`5a43e5e`)

### 🐛 Corregido & Bug Fixes
- **ci:** corregir sintaxis YAML de comillas en titulo de docker-publish workflow (`bd08b33`)

### 📚 Documentación
- **rules:** añadir regla obligatoria de envio de cambios via PR con aprobacion explicita (`1a35785`)
- **ci:** actualizar documentacion de cerebros con permisos de docker-publish workflow (`34aaf4b`)

## [v2.5.27 (Frontend) / v2.5.18 (Backend)] - 2026-08-20

*Actualización de estabilidad, sincronización de versiones y optimización de componentes.*

## [v2.5.26 (Frontend) / v2.5.18 (Backend)] - 2026-08-20

### 🚀 Features & Nuevas Funcionalidades
- **security:** aplicar cifrado transparente de datos sensibles en reposo mediante ENCRYPTION_KEY en la capa de persistencia (v2.5.26 / v2.5.17) (`e0319fa`)

### 🔧 Tareas Operativas y Mantenimiento
- **prisma:** crear archivo de configuracion prisma.config.ts para soporte oficial de Prisma CLI y Language Server (`562e5f5`)

## [v2.5.26 (Frontend) / v2.5.17 (Backend)] - 2026-08-19

### 🚀 Features & Nuevas Funcionalidades
- **security:** integrar servicio de encriptacion AES-256-GCM y firmas HMAC utilizando ENCRYPTION_KEY (v2.5.26 / v2.5.16) (`94151da`)

## [v2.5.26 (Frontend) / v2.5.16 (Backend)] - 2026-08-19

### 🚀 Features & Nuevas Funcionalidades
- **security:** implementar token secreto x-api-secret para comunicacion cliente-servidor (v2.5.26 / v2.5.15) (`b55abeb`)

## [v2.5.26 (Frontend) / v2.5.15 (Backend)] - 2026-08-19

### 🚀 Features & Nuevas Funcionalidades
- **changelog:** agregar soporte de archivos por versión en changelog/ y regla obligatoria de commits (`9c1618d`)

### ⚡ Optimización y Rendimiento
- **changelog:** optimizar generación de changelogs y reducir peso del repositorio v2.5.25 (`d930dc4`)

### 📚 Documentación
- **changelog:** actualizar changelog con registro de Licencia AGPL-3.0 (`a8a6db3`)
- **changelog:** actualizar changelog con cambios de Configuración de Branding (`ef436d7`)
- **changelog:** actualizar changelog tras establecer directiva de cerebros (`d501d0f`)
- **changelog:** actualizar changelog con registro de cerebros y datos (`7bbfff4`)
- **changelog:** actualizar changelog con el titulo Tlamatqui (`6e03064`)
- **changelog:** actualizar changelog tras revision de .gitignore (`5aca9ed`)
- **changelog:** sincronizar registro de changelog con ultimo commit (`23b0d7c`)
- **changelog:** actualizar CHANGELOG.md y extractos por version (`367af3b`)
- **changelog:** actualizar changelog con regla de Caveman Mode (`a0b0910`)
- **changelog:** actualizar changelog con la creación del sistema modular de reglas (`50d1ab7`)
- **changelog:** registrar cambios de versión v2.5.5 en changelogs (`ece4511`)
- **rules:** actualizar nombre del proyecto a Tlamatqui en la ruta de la IA y documentación (`4248b88`)
- **changelog:** actualizar changelog raíz y archivos por versión con último commit (`50cc9ce`)

### 🔧 Tareas Operativas y Mantenimiento
- remove legacy project documentation and architecture proposal files (`3f5bc24`)

## [v2.5.25 (Frontend) / v2.5.14 (Backend)] - 2026-08-19

### 🚀 Features & Nuevas Funcionalidades
- **auth:** rediseñar LoginPage para Auth0 Universal Login exclusivo con logo de instancia (`535cebf`)
- **config:** agregar campos para logos 2 y 3 en configuración global (`50d9942`)
- **teams:** permitir invitar miembros a un equipo a traves de un enlace corto (`4cbf1e9`)
- **dns:** auto-registrar dominio automaticamente en Vercel API al guardar o consultar (`b9d2695`)
- **dns:** integrar API de Vercel para auto-aprovisionamiento y diagnostico en vivo 4-checkpoints (`4960fe7`)
- **config:** agregar compartir reportes en dominio personalizado con verificacion TXT (`b59d9b4`)
- **ui:** establecer titulo dinamico del reporte web como Reporte de {{marca}} | Tlamatqui (`94939d0`)
- **smtp:** implementar servicio de envio de reportes por correo electronico via SMTP (`d7b5ff8`)
- **admin:** actualizar etiqueta a Configuración de Branding y remover campo de archivo/URL de logo (`5a77c92`)
- **ui:** actualizar el titulo de la pestana a Tlamatqui (`c8b91a4`)
- **env:** configurar variables de entorno y soporte CORS para ejecucion desacoplada (`7483b73`)
- **rules:** crear regla dedicada para el ecosistema Caveman en .agents/rules/caveman-rules.md (`c411890`)
- **rules:** crear sistema modular de reglas de IA en .agents/rules/ (`1023197`)

### ♻️ Refactorización de Código
- **admin:** renombrar panel de administracion a Tlachiālōyan y establecer slug /tlachialoyan (`b8d3612`)

### 📚 Documentación & Reglas
- **changelog:** actualizar changelog con renombrado Tlachiālōyan y slug /tlachialoyan (`14064e3`)
- **changelog:** actualizar changelog con titulo dinamico de reporte por marca (`4e990c3`)
- **changelog:** actualizar changelog con la funcionalidad SMTP (`1b1490b`)
- **rules:** establecer directiva obligatoria de registro en cerebros y documentacion IA (`c3d1797`)
- **context:** actualizar el contexto de los cerebros y datos del proyecto (`d720ce3`)

### 🔧 Tareas Operativas y Mantenimiento
- **license:** añadir licencia GNU Affero General Public License v3.0 (AGPL-3.0) (`d216ee0`)
- **git:** actualizar .gitignore con reglas de ignorado estructuradas (`dad0315`)

## [v2.5.0 (Frontend) / v2.5.0 (Backend)] - 2026-08-16

*Versión inicial de la plataforma Tlamatqui con arquitectura desacoplada React 19/Vite 6 y Express/Prisma ORM.*

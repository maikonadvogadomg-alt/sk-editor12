# PLANO DO PROJETO: HTML/CSS/JS

> Gerado automaticamente pelo SK Code Editor em 23/10/2026, 04:38:30
> **380 arquivo(s)** | **~43.240 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React, TypeScript
- **Versao:** 1.0.4
- **Descricao:** codelens-local — App desktop (Windows, Mac, Linux)

**Para rodar o projeto:**
```bash
npm install && npm start
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS/
├── .github/
│   └── workflows/
│       ├── apk-capacitor.yml
│       ├── apk.yml
│       ├── build-desktop.yml
│       └── desktop-exe.yml
├── .sk/
│   ├── hub.json
│   └── memoria.json
├── android/
│   ├── app/
│   │   ├── src/
│   │   │   └── main/
│   │   │       ├── assets/
│   │   │       │   └── __ponte.js
│   │   │       ├── java/
│   │   │       │   └── app/
│   │   │       │       └── minisk/
│   │   │       │           └── shell/
│   │   │       │               └── MainActivity.java
│   │   │       ├── res/
│   │   │       │   └── xml/
│   │   │       │       └── rede.xml
│   │   │       └── AndroidManifest.xml
│   │   └── build.gradle
│   ├── build.gradle
│   ├── gradle.properties
│   └── settings.gradle
├── electron/
│   ├── main.cjs
│   └── preload.cjs
├── icons/
│   ├── icon.svg
│   └── maskable.svg
├── www/
│   ├── .github/
│   │   └── workflows/
│   │       ├── apk-capacitor.yml
│   │       ├── apk.yml
│   │       ├── desktop-exe.yml
│   │       ├── teste.yml
│   │       └── windows.yml
│   ├── .sk/
│   │   └── plano.md
│   ├── android/
│   │   ├── app/
│   │   │   ├── src/
│   │   │   │   └── main/
│   │   │   │       ├── assets/
│   │   │   │       │   ├── public/
│   │   │   │       │   │   ├── assets/
│   │   │   │       │   │   │   ├── icon-CTxW8nPR.svg
│   │   │   │       │   │   │   ├── index-YmvJSp3J.css
│   │   │   │       │   │   │   └── manifest-alaULjTv.json
│   │   │   │       │   │   ├── cordova_plugins.js
│   │   │   │       │   │   ├── cordova.js
│   │   │   │       │   │   ├── favicon.svg
│   │   │   │       │   │   ├── index.html
│   │   │   │       │   │   ├── manifest.json
│   │   │   │       │   │   └── sw.js
│   │   │   │       │   ├── __ponte.js
│   │   │   │       │   ├── capacitor.config.json
│   │   │   │       │   └── capacitor.plugins.json
│   │   │   │       ├── java/
│   │   │   │       │   └── app/
│   │   │   │       │       └── minisk/
│   │   │   │       │           └── shell/
│   │   │   │       │               └── MainActivity.java
│   │   │   │       ├── res/
│   │   │   │       │   └── xml/
│   │   │   │       │       ├── config.xml
│   │   │   │       │       └── rede.xml
│   │   │   │       └── AndroidManifest.xml
│   │   │   ├── build.gradle
│   │   │   └── capacitor.build.gradle
│   │   ├── capacitor-cordova-android-plugins/
│   │   │   ├── src/
│   │   │   │   └── main/
│   │   │   │       └── AndroidManifest.xml
│   │   │   ├── build.gradle
│   │   │   └── cordova.variables.gradle
│   │   ├── build.gradle
│   │   ├── capacitor.settings.gradle
│   │   ├── gradle.properties
│   │   └── settings.gradle
│   ├── dados/
│   │   └── banco/
│   │       ├── base/
│   │       │   ├── 1/
│   │       │   │   ├── 12599
│   │       │   │   ├── 12604
│   │       │   │   ├── 12609
│   │       │   │   ├── 12614
│   │       │   │   ├── 1417
│   │       │   │   ├── 1418
│   │       │   │   ├── 16385
│   │       │   │   ├── 16392
│   │       │   │   ├── 16397
│   │       │   │   ├── 16402
│   │       │   │   ├── 16413
│   │       │   │   ├── 16418
│   │       │   │   ├── 16423
│   │       │   │   ├── 16433
│   │       │   │   ├── 2328
│   │       │   │   ├── 2336
│   │       │   │   ├── 2611
│   │       │   │   ├── 2613
│   │       │   │   ├── 2830
│   │       │   │   ├── 2832
│   │       │   │   ├── 2834
│   │       │   │   ├── 2995
│   │       │   │   ├── 3118
│   │       │   │   ├── 3256
│   │       │   │   ├── 3350
│   │       │   │   ├── 3381
│   │       │   │   ├── 3429
│   │       │   │   ├── 3430
│   │       │   │   ├── 3439
│   │       │   │   ├── 3466
│   │       │   │   ├── 3501
│   │       │   │   ├── 3576
│   │       │   │   ├── 3596
│   │       │   │   ├── 3598
│   │       │   │   ├── 4143
│   │       │   │   ├── 4145
│   │       │   │   ├── 4147
│   │       │   │   ├── 4149
│   │       │   │   ├── 4151
│   │       │   │   ├── 4153
│   │       │   │   ├── 4155
│   │       │   │   ├── 4157
│   │       │   │   ├── 4159
│   │       │   │   ├── 4163
│   │       │   │   ├── 4165
│   │       │   │   ├── 4167
│   │       │   │   ├── 4169
│   │       │   │   ├── 4171
│   │       │   │   ├── 4173
│   │       │   │   ├── 6102
│   │       │   │   ├── 6104
│   │       │   │   ├── 6106
│   │       │   │   ├── 6175
│   │       │   │   ├── 6228
│   │       │   │   ├── 6237
│   │       │   │   ├── 826
│   │       │   │   └── PG_VERSION
│   │       │   ├── 4/
│   │       │   │   ├── 12599
│   │       │   │   ├── 12604
│   │       │   │   ├── 12609
│   │       │   │   ├── 12614
│   │       │   │   ├── 1417
│   │       │   │   ├── 1418
│   │       │   │   ├── 2224
│   │       │   │   ├── 2328
│   │       │   │   ├── 2336
│   │       │   │   ├── 2604
│   │       │   │   ├── 2611
│   │       │   │   ├── 2613
│   │       │   │   ├── 2620
│   │       │   │   ├── 2830
│   │       │   │   ├── 2832
│   │       │   │   ├── 2834
│   │       │   │   ├── 2995
│   │       │   │   ├── 3118
│   │       │   │   ├── 3256
│   │       │   │   ├── 3350
│   │       │   │   ├── 3381
│   │       │   │   ├── 3429
│   │       │   │   ├── 3430
│   │       │   │   ├── 3439
│   │       │   │   ├── 3466
│   │       │   │   ├── 3501
│   │       │   │   ├── 3576
│   │       │   │   ├── 3596
│   │       │   │   ├── 3598
│   │       │   │   ├── 4143
│   │       │   │   ├── 4145
│   │       │   │   ├── 4147
│   │       │   │   ├── 4149
│   │       │   │   ├── 4151
│   │       │   │   ├── 4153
│   │       │   │   ├── 4155
│   │       │   │   ├── 4157
│   │       │   │   ├── 4159
│   │       │   │   ├── 4163
│   │       │   │   ├── 4165
│   │       │   │   ├── 4167
│   │       │   │   ├── 4169
│   │       │   │   ├── 4171
│   │       │   │   ├── 4173
│   │       │   │   ├── 6102
│   │       │   │   ├── 6104
│   │       │   │   ├── 6106
│   │       │   │   ├── 6175
│   │       │   │   ├── 6228
│   │       │   │   ├── 6237
│   │       │   │   ├── 826
│   │       │   │   └── PG_VERSION
│   │       │   └── 5/
│   │       │       ├── 12599
│   │       │       ├── 12604
│   │       │       ├── 12609
│   │       │       ├── 12614
│   │       │       ├── 1417
│   │       │       ├── 1418
│   │       │       ├── 2224
│   │       │       ├── 2328
│   │       │       ├── 2336
│   │       │       ├── 2604
│   │       │       ├── 2611
│   │       │       ├── 2613
│   │       │       ├── 2620
│   │       │       ├── 2830
│   │       │       ├── 2832
│   │       │       ├── 2834
│   │       │       ├── 2995
│   │       │       ├── 3118
│   │       │       ├── 3256
│   │       │       ├── 3350
│   │       │       ├── 3381
│   │       │       ├── 3429
│   │       │       ├── 3430
│   │       │       ├── 3439
│   │       │       ├── 3466
│   │       │       ├── 3501
│   │       │       ├── 3576
│   │       │       ├── 3596
│   │       │       ├── 3598
│   │       │       ├── 4143
│   │       │       ├── 4145
│   │       │       ├── 4147
│   │       │       ├── 4149
│   │       │       ├── 4151
│   │       │       ├── 4153
│   │       │       ├── 4155
│   │       │       ├── 4157
│   │       │       ├── 4159
│   │       │       ├── 4163
│   │       │       ├── 4165
│   │       │       ├── 4167
│   │       │       ├── 4169
│   │       │       ├── 4171
│   │       │       ├── 4173
│   │       │       ├── 6102
│   │       │       ├── 6104
│   │       │       ├── 6106
│   │       │       ├── 6175
│   │       │       ├── 6228
│   │       │       ├── 6237
│   │       │       ├── 826
│   │       │       └── PG_VERSION
│   │       ├── global/
│   │       │   ├── 1214
│   │       │   ├── 2846
│   │       │   ├── 2964
│   │       │   ├── 2966
│   │       │   ├── 3592
│   │       │   ├── 4060
│   │       │   ├── 4175
│   │       │   ├── 4177
│   │       │   ├── 4181
│   │       │   ├── 4183
│   │       │   ├── 4185
│   │       │   ├── 6000
│   │       │   ├── 6100
│   │       │   ├── 6243
│   │       │   └── 6244
│   │       ├── pg_hba.conf
│   │       ├── pg_ident.conf
│   │       ├── PG_VERSION
│   │       ├── postgresql.auto.conf
│   │       ├── postgresql.conf
│   │       └── postmaster.pid
│   ├── electron/
│   │   ├── main.cjs
│   │   └── preload.cjs
│   ├── icons/
│   │   ├── icon.svg
│   │   └── maskable.svg
│   ├── lib/
│   │   ├── api-client-react/
│   │   │   └── index.ts
│   │   ├── api-zod/
│   │   │   └── index.ts
│   │   └── db/
│   │       └── index.ts
│   ├── public/
│   │   ├── favicon.svg
│   │   ├── manifest.json
│   │   └── sw.js
│   ├── scripts/
│   │   ├── abrir-pronto.mjs
│   │   └── iniciar.mjs
│   ├── server/
│   │   ├── lib/
│   │   │   ├── devServerRegistry.ts
│   │   │   ├── gemini-ponte.ts
│   │   │   ├── logger.ts
│   │   │   ├── persistFiles.ts
│   │   │   ├── shell.ts
│   │   │   ├── storage.ts
│   │   │   ├── tar.ts
│   │   │   └── tts.ts
│   │   ├── routes/
│   │   │   ├── ai.ts
│   │   │   ├── code-assistant.ts
│   │   │   ├── code-run.ts
│   │   │   ├── dev-server.ts
│   │   │   ├── exec.ts
│   │   │   ├── files.ts
│   │   │   ├── git.ts
│   │   │   ├── github.ts
│   │   │   ├── health.ts
│   │   │   ├── import-github.ts
│   │   │   ├── index.ts
│   │   │   ├── preview.ts
│   │   │   ├── projects.ts
│   │   │   ├── settings.ts
│   │   │   └── snippets.ts
│   │   ├── app.ts
│   │   └── index.ts
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button-group.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── empty.tsx
│   │   │   │   ├── field.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-group.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── item.tsx
│   │   │   │   ├── kbd.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── sonner.tsx
│   │   │   │   ├── spinner.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── ai-panel.tsx
│   │   │   ├── code-editor.tsx
│   │   │   ├── code-viewer.tsx
│   │   │   ├── error-boundary.tsx
│   │   │   ├── file-tree.tsx
│   │   │   ├── git-history-modal.tsx
│   │   │   ├── github-conta.tsx
│   │   │   ├── github-deploy-modal.tsx
│   │   │   ├── layout.tsx
│   │   │   ├── packages-panel.tsx
│   │   │   ├── preview-panel.tsx
│   │   │   ├── terminal-panel.tsx
│   │   │   └── theme-provider.tsx
│   │   ├── hooks/
│   │   │   ├── use-file-ops.ts
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   └── utils.ts
│   │   ├── pages/
│   │   │   ├── assistant.tsx
│   │   │   ├── home.tsx
│   │   │   ├── not-found.tsx
│   │   │   ├── playground.tsx
│   │   │   ├── project-explorer.tsx
│   │   │   └── settings.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   ├── windows/
│   │   └── Abrir-CodeLens.bat
│   ├── .gitignore
│   ├── .npmrc
│   ├── 404.html
│   ├── apk.config.json
│   ├── capacitor.config.json
│   ├── index.html
│   ├── iniciar.bat
│   ├── iniciar.sh
│   ├── LEIA-ME.md
│   ├── manifest.json
│   ├── package.json
│   ├── PLANO.md
│   ├── service-worker.js
│   ├── termux-atalho.sh
│   ├── tsconfig.json
│   └── vite.config.ts
├── .gitignore
├── .npmrc
├── 1.md
├── apk.config.json
├── capacitor.config.json
├── index.html
├── main.js
├── manifest.json
├── package.json
├── PLANO.md
├── preload.js
├── README.md
├── service-worker.js
└── SISTEMA.md
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React, TypeScript
- **Todos os pacotes (5):** @capacitor/core, @capacitor/android, electron, electron-builder, @capacitor/cli

---

## ROTAS DA API (endpoints detectados automaticamente)

```
USE    /api  (em www/server/app.ts)
USE    /api  (em www/server/app.ts)
POST   /ai/chat  (em www/server/routes/ai.ts)
POST   /ai/analyze-file  (em www/server/routes/ai.ts)
POST   /ai/analyze-folder  (em www/server/routes/ai.ts)
POST   /ai/tts  (em www/server/routes/ai.ts)
POST   /code-assistant  (em www/server/routes/code-assistant.ts)
POST   /code/run  (em www/server/routes/code-run.ts)
POST   /projects/:projectId/dev-server/start  (em www/server/routes/dev-server.ts)
DELETE /projects/:projectId/dev-server/stop  (em www/server/routes/dev-server.ts)
GET    /projects/:projectId/dev-server/status  (em www/server/routes/dev-server.ts)
POST   /projects/:projectId/exec-stream  (em www/server/routes/exec.ts)
POST   /projects/:projectId/exec  (em www/server/routes/exec.ts)
GET    /projects/:projectId/files  (em www/server/routes/files.ts)
PUT    /projects/:projectId/files  (em www/server/routes/files.ts)
DELETE /projects/:projectId/files  (em www/server/routes/files.ts)
POST   /projects/:projectId/files/mkdir  (em www/server/routes/files.ts)
PATCH  /projects/:projectId/files  (em www/server/routes/files.ts)
POST   /projects/:projectId/files/copy  (em www/server/routes/files.ts)
GET    /projects/:projectId/git/info  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/log  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/procurar  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/mudancas  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/arquivos  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/ver  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/diferencas  (em www/server/routes/git.ts)
POST   /projects/:projectId/git/restaurar  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/zip  (em www/server/routes/git.ts)
GET    /projects/:projectId/git/relatorio  (em www/server/routes/git.ts)
POST   /projects/:projectId/git/importar-bundle  (em www/server/routes/git.ts)
POST   /github/create-repo  (em www/server/routes/github.ts)
GET    /github/conta  (em www/server/routes/github.ts)
POST   /github/token  (em www/server/routes/github.ts)
DELETE /github/token  (em www/server/routes/github.ts)
GET    /github/repos  (em www/server/routes/github.ts)
POST   /github/enviar  (em www/server/routes/github.ts)
GET    /healthz  (em www/server/routes/health.ts)
POST   /projects/import-github  (em www/server/routes/import-github.ts)
GET    /projects/:projectId/preview/status  (em www/server/routes/preview.ts)
GET    /projects/:projectId/preview{/*path}  (em www/server/routes/preview.ts)
GET    /projects  (em www/server/routes/projects.ts)
POST   /projects  (em www/server/routes/projects.ts)
GET    /api/hello  (em www/server/routes/projects.ts)
POST   /projects/blank  (em www/server/routes/projects.ts)
GET    /projects/:projectId  (em www/server/routes/projects.ts)
GET    /projects/:projectId/download  (em www/server/routes/projects.ts)
DELETE /projects/:projectId  (em www/server/routes/projects.ts)
GET    /settings  (em www/server/routes/settings.ts)
PUT    /settings  (em www/server/routes/settings.ts)
GET    /snippets  (em www/server/routes/snippets.ts)
POST   /snippets  (em www/server/routes/snippets.ts)
PATCH  /snippets/:id  (em www/server/routes/snippets.ts)
DELETE /snippets/:id  (em www/server/routes/snippets.ts)
```

---

## SCRIPTS DISPONIVEIS (package.json)

```bash
npm run desktop       # electron .
npm run exe           # electron-builder --win portable --publish never
npm run start         # electron .
npm run build         # electron-builder --publish=never
npm run build:win     # electron-builder --win --x64 --publish=never
npm run build:mac     # electron-builder --mac --x64 --arm64 --publish=never
npm run build:linux   # electron-builder --linux --x64 --publish=never
```

---

## VARIAVEIS DE AMBIENTE NECESSARIAS

Crie um arquivo `.env` na raiz com estas variaveis:

```env
DATA_DIR=seu_valor_aqui
STORAGE_PATH=seu_valor_aqui
LOG_LEVEL=seu_valor_aqui
C=seu_valor_aqui
TTS_VOZ=seu_valor_aqui
TTS_VELOCIDADE=seu_valor_aqui
TTS_TOM=seu_valor_aqui
AI_INTEGRATIONS_GEMINI_BASE_URL=seu_valor_aqui
AI_INTEGRATIONS_GEMINI_API_KEY=seu_valor_aqui
PATH=seu_valor_aqui
PORT=seu_valor_aqui
```

---

## ARQUIVOS PRINCIPAIS

- `index.html` — Pagina HTML principal
- `www/android/app/src/main/assets/public/index.html` — Arquivo principal
- `www/index.html` — Arquivo principal
- `www/lib/api-client-react/index.ts` — Arquivo principal
- `www/lib/api-zod/index.ts` — Arquivo principal
- `www/lib/db/index.ts` — Arquivo principal
- `www/server/app.ts` — Ponto de entrada do backend
- `www/server/index.ts` — Ponto de entrada do backend
- `www/server/routes/index.ts` — Ponto de entrada do backend
- `www/src/App.tsx` — Componente raiz do frontend

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`.gitignore`** _(5 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`.npmrc`** _(5 linhas)_
Arquivo NPMRC — parte do projeto.

**`1.md`** _(14441 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`PLANO.md`** _(2348 linhas)_
Este documento! Gerado automaticamente pelo SK Code Editor com toda a estrutura do projeto.

**`README.md`** _(66 linhas)_
Documentacao principal do projeto. Explica o que o projeto faz e como rodar.

**`SISTEMA.md`** _(98 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`apk.config.json`** _(11 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`capacitor.config.json`** _(9 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(99 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`main.js`** _(46 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`manifest.json`** _(109 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`package.json`** _(94 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`preload.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`service-worker.js`** _(1288 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `.sk/`
> Pasta '.sk' — agrupamento de arquivos relacionados.

**`hub.json`** _(31 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`memoria.json`** _(1 linha)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

---

### 📁 `android/`
> Pasta 'android' — agrupamento de arquivos relacionados.

**`build.gradle`** _(4 linhas)_
Arquivo GRADLE — parte do projeto.

**`gradle.properties`** _(4 linhas)_
Arquivo PROPERTIES — parte do projeto.

**`settings.gradle`** _(10 linhas)_
Arquivo GRADLE — parte do projeto.

---

### 📁 `electron/`
> Pasta 'electron' — agrupamento de arquivos relacionados.

**`main.cjs`** _(38 linhas)_
Arquivo CJS — parte do projeto.

**`preload.cjs`** _(4 linhas)_
Arquivo CJS — parte do projeto.

---

### 📁 `icons/`
> Icones do projeto.

**`icon.svg`** _(2 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`maskable.svg`** _(2 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

---

### 📁 `www/`
> Pasta 'www' — agrupamento de arquivos relacionados.

**`.gitignore`** _(8 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`.npmrc`** _(4 linhas)_
Arquivo NPMRC — parte do projeto.

**`404.html`** _(29 linhas)_
Arquivo HTML — parte do projeto.

**`LEIA-ME.md`** _(115 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`PLANO.md`** _(453 linhas)_
Este documento! Gerado automaticamente pelo SK Code Editor com toda a estrutura do projeto.

**`apk.config.json`** _(11 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`capacitor.config.json`** _(9 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(29 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`iniciar.bat`** _(31 linhas)_
Arquivo BAT — parte do projeto.

**`iniciar.sh`** _(11 linhas)_
Arquivo SH — parte do projeto.

**`manifest.json`** _(95 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`package.json`** _(140 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`service-worker.js`** _(183 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`termux-atalho.sh`** _(15 linhas)_
Arquivo SH — parte do projeto.

**`tsconfig.json`** _(26 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.ts`** _(27 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `.github/workflows/`
> Pasta 'workflows' — agrupamento de arquivos relacionados.

**`apk-capacitor.yml`** _(45 linhas)_
Arquivo YML — parte do projeto.

**`apk.yml`** _(82 linhas)_
Arquivo YML — parte do projeto.

**`build-desktop.yml`** _(177 linhas)_
Arquivo YML — parte do projeto.

**`desktop-exe.yml`** _(26 linhas)_
Arquivo YML — parte do projeto.

---

### 📁 `android/app/`
> Pasta 'app' — agrupamento de arquivos relacionados.

**`build.gradle`** _(47 linhas)_
Arquivo GRADLE — parte do projeto.

---

### 📁 `www/.sk/`
> Pasta '.sk' — agrupamento de arquivos relacionados.

**`plano.md`** _(323 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

---

### 📁 `www/android/`
> Pasta 'android' — agrupamento de arquivos relacionados.

**`build.gradle`** _(4 linhas)_
Arquivo GRADLE — parte do projeto.

**`capacitor.settings.gradle`** _(4 linhas)_
Arquivo GRADLE — parte do projeto.

**`gradle.properties`** _(4 linhas)_
Arquivo PROPERTIES — parte do projeto.

**`settings.gradle`** _(10 linhas)_
Arquivo GRADLE — parte do projeto.

---

### 📁 `www/electron/`
> Pasta 'electron' — agrupamento de arquivos relacionados.

**`main.cjs`** _(38 linhas)_
Arquivo CJS — parte do projeto.

**`preload.cjs`** _(4 linhas)_
Arquivo CJS — parte do projeto.

---

### 📁 `www/icons/`
> Icones do projeto.

**`icon.svg`** _(2 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`maskable.svg`** _(2 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

---

### 📁 `www/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`manifest.json`** _(27 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(34 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `www/scripts/`
> Pasta 'scripts' — agrupamento de arquivos relacionados.

**`abrir-pronto.mjs`** _(32 linhas)_
Arquivo MJS — parte do projeto.

**`iniciar.mjs`** _(123 linhas)_
Arquivo MJS — parte do projeto.

---

### 📁 `www/server/`
> Pasta 'server' — agrupamento de arquivos relacionados.

**`app.ts`** _(61 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index.ts`** _(27 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

---

### 📁 `www/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(43 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(386 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(12 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `www/windows/`
> Pasta 'windows' — agrupamento de arquivos relacionados.

**`Abrir-CodeLens.bat`** _(21 linhas)_
Arquivo BAT — parte do projeto.

---

### 📁 `www/.github/workflows/`
> Pasta 'workflows' — agrupamento de arquivos relacionados.

**`apk-capacitor.yml`** _(45 linhas)_
Arquivo YML — parte do projeto.

**`apk.yml`** _(82 linhas)_
Arquivo YML — parte do projeto.

**`desktop-exe.yml`** _(26 linhas)_
Arquivo YML — parte do projeto.

**`teste.yml`** _(59 linhas)_
Arquivo YML — parte do projeto.

**`windows.yml`** _(95 linhas)_
Arquivo YML — parte do projeto.

---

### 📁 `www/android/app/`
> Pasta 'app' — agrupamento de arquivos relacionados.

**`build.gradle`** _(47 linhas)_
Arquivo GRADLE — parte do projeto.

**`capacitor.build.gradle`** _(20 linhas)_
Arquivo GRADLE — parte do projeto.

---

### 📁 `www/android/capacitor-cordova-android-plugins/`
> Pasta 'capacitor-cordova-android-plugins' — agrupamento de arquivos relacionados.

**`build.gradle`** _(59 linhas)_
Arquivo GRADLE — parte do projeto.

**`cordova.variables.gradle`** _(7 linhas)_
Arquivo GRADLE — parte do projeto.

---

### 📁 `www/dados/banco/`
> Pasta 'banco' — agrupamento de arquivos relacionados.

**`PG_VERSION`** _(2 linhas)_
Arquivo PG_VERSION — parte do projeto.

**`pg_hba.conf`** _(127 linhas)_
Arquivo CONF — parte do projeto.

**`pg_ident.conf`** _(73 linhas)_
Arquivo CONF — parte do projeto.

**`postgresql.auto.conf`** _(3 linhas)_
Arquivo CONF — parte do projeto.

**`postgresql.conf`** _(843 linhas)_
Arquivo CONF — parte do projeto.

**`postmaster.pid`** _(8 linhas)_
Arquivo PID — parte do projeto.

---

### 📁 `www/lib/api-client-react/`
> Pasta 'api-client-react' — agrupamento de arquivos relacionados.

**`index.ts`** _(208 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

---

### 📁 `www/lib/api-zod/`
> Pasta 'api-zod' — agrupamento de arquivos relacionados.

**`index.ts`** _(60 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

---

### 📁 `www/lib/db/`
> Pasta 'db' — agrupamento de arquivos relacionados.

**`index.ts`** _(198 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

---

### 📁 `www/server/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`devServerRegistry.ts`** _(350 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`gemini-ponte.ts`** _(139 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`logger.ts`** _(25 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`persistFiles.ts`** _(143 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`shell.ts`** _(49 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`storage.ts`** _(161 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tar.ts`** _(50 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tts.ts`** _(87 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `www/server/routes/`
> Definicao das URLs e navegacao do app.

**`ai.ts`** _(686 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`code-assistant.ts`** _(162 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`code-run.ts`** _(47 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`dev-server.ts`** _(231 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`exec.ts`** _(347 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`files.ts`** _(184 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`git.ts`** _(215 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`github.ts`** _(258 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`health.ts`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`import-github.ts`** _(169 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index.ts`** _(35 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`preview.ts`** _(141 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`projects.ts`** _(531 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`settings.ts`** _(78 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`snippets.ts`** _(67 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `www/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`ai-panel.tsx`** _(1187 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`code-editor.tsx`** _(241 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`code-viewer.tsx`** _(302 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`error-boundary.tsx`** _(107 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`file-tree.tsx`** _(389 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`git-history-modal.tsx`** _(168 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`github-conta.tsx`** _(132 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`github-deploy-modal.tsx`** _(626 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`layout.tsx`** _(161 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`packages-panel.tsx`** _(537 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`preview-panel.tsx`** _(592 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`terminal-panel.tsx`** _(555 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`theme-provider.tsx`** _(72 linhas)_
Componente PROVIDER — 'fornece' dados/funcoes para todos os componentes filhos via Context API do React.

---

### 📁 `www/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-file-ops.ts`** _(110 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-file-ops'.

**`use-mobile.tsx`** _(22 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(188 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `www/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`utils.ts`** _(16 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `www/src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`assistant.tsx`** _(515 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`home.tsx`** _(672 linhas)_
Componente HOME — pagina/tela inicial do app.

**`not-found.tsx`** _(22 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`playground.tsx`** _(668 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`project-explorer.tsx`** _(700 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`settings.tsx`** _(666 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

---

### 📁 `android/app/src/main/`
> Pasta 'main' — agrupamento de arquivos relacionados.

**`AndroidManifest.xml`** _(32 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `www/dados/banco/global/`
> Pasta 'global' — agrupamento de arquivos relacionados.

**`1214`** _(1 linha)_
Arquivo 1214 — parte do projeto.

**`2846`** _(1 linha)_
Arquivo 2846 — parte do projeto.

**`2964`** _(1 linha)_
Arquivo 2964 — parte do projeto.

**`2966`** _(1 linha)_
Arquivo 2966 — parte do projeto.

**`3592`** _(1 linha)_
Arquivo 3592 — parte do projeto.

**`4060`** _(1 linha)_
Arquivo 4060 — parte do projeto.

**`4175`** _(1 linha)_
Arquivo 4175 — parte do projeto.

**`4177`** _(1 linha)_
Arquivo 4177 — parte do projeto.

**`4181`** _(1 linha)_
Arquivo 4181 — parte do projeto.

**`4183`** _(1 linha)_
Arquivo 4183 — parte do projeto.

**`4185`** _(1 linha)_
Arquivo 4185 — parte do projeto.

**`6000`** _(1 linha)_
Arquivo 6000 — parte do projeto.

**`6100`** _(1 linha)_
Arquivo 6100 — parte do projeto.

**`6243`** _(1 linha)_
Arquivo 6243 — parte do projeto.

**`6244`** _(1 linha)_
Arquivo 6244 — parte do projeto.

---

### 📁 `www/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(55 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(139 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(59 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(50 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(43 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(115 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(83 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(65 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(213 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(83 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(260 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(367 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(153 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(198 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(120 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(201 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(104 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(244 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(179 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(27 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(168 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(69 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(22 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(193 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(26 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(254 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(128 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(31 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(42 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(45 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(159 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(140 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(727 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(26 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(16 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(120 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(53 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(22 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(127 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(61 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `android/app/src/main/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`__ponte.js`** _(99 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `www/android/app/src/main/`
> Pasta 'main' — agrupamento de arquivos relacionados.

**`AndroidManifest.xml`** _(32 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `www/android/capacitor-cordova-android-plugins/src/main/`
> Pasta 'main' — agrupamento de arquivos relacionados.

**`AndroidManifest.xml`** _(8 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `www/dados/banco/base/1/`
> Pasta '1' — agrupamento de arquivos relacionados.

**`12599`** _(1 linha)_
Arquivo 12599 — parte do projeto.

**`12604`** _(1 linha)_
Arquivo 12604 — parte do projeto.

**`12609`** _(1 linha)_
Arquivo 12609 — parte do projeto.

**`12614`** _(1 linha)_
Arquivo 12614 — parte do projeto.

**`1417`** _(1 linha)_
Arquivo 1417 — parte do projeto.

**`1418`** _(1 linha)_
Arquivo 1418 — parte do projeto.

**`16385`** _(1 linha)_
Arquivo 16385 — parte do projeto.

**`16392`** _(1 linha)_
Arquivo 16392 — parte do projeto.

**`16397`** _(1 linha)_
Arquivo 16397 — parte do projeto.

**`16402`** _(1 linha)_
Arquivo 16402 — parte do projeto.

**`16413`** _(1 linha)_
Arquivo 16413 — parte do projeto.

**`16418`** _(1 linha)_
Arquivo 16418 — parte do projeto.

**`16423`** _(1 linha)_
Arquivo 16423 — parte do projeto.

**`16433`** _(1 linha)_
Arquivo 16433 — parte do projeto.

**`2328`** _(1 linha)_
Arquivo 2328 — parte do projeto.

**`2336`** _(1 linha)_
Arquivo 2336 — parte do projeto.

**`2611`** _(1 linha)_
Arquivo 2611 — parte do projeto.

**`2613`** _(1 linha)_
Arquivo 2613 — parte do projeto.

**`2830`** _(1 linha)_
Arquivo 2830 — parte do projeto.

**`2832`** _(1 linha)_
Arquivo 2832 — parte do projeto.

**`2834`** _(1 linha)_
Arquivo 2834 — parte do projeto.

**`2995`** _(1 linha)_
Arquivo 2995 — parte do projeto.

**`3118`** _(1 linha)_
Arquivo 3118 — parte do projeto.

**`3256`** _(1 linha)_
Arquivo 3256 — parte do projeto.

**`3350`** _(1 linha)_
Arquivo 3350 — parte do projeto.

**`3381`** _(1 linha)_
Arquivo 3381 — parte do projeto.

**`3429`** _(1 linha)_
Arquivo 3429 — parte do projeto.

**`3430`** _(1 linha)_
Arquivo 3430 — parte do projeto.

**`3439`** _(1 linha)_
Arquivo 3439 — parte do projeto.

**`3466`** _(1 linha)_
Arquivo 3466 — parte do projeto.

**`3501`** _(1 linha)_
Arquivo 3501 — parte do projeto.

**`3576`** _(1 linha)_
Arquivo 3576 — parte do projeto.

**`3596`** _(1 linha)_
Arquivo 3596 — parte do projeto.

**`3598`** _(1 linha)_
Arquivo 3598 — parte do projeto.

**`4143`** _(1 linha)_
Arquivo 4143 — parte do projeto.

**`4145`** _(1 linha)_
Arquivo 4145 — parte do projeto.

**`4147`** _(1 linha)_
Arquivo 4147 — parte do projeto.

**`4149`** _(1 linha)_
Arquivo 4149 — parte do projeto.

**`4151`** _(1 linha)_
Arquivo 4151 — parte do projeto.

**`4153`** _(1 linha)_
Arquivo 4153 — parte do projeto.

**`4155`** _(1 linha)_
Arquivo 4155 — parte do projeto.

**`4157`** _(1 linha)_
Arquivo 4157 — parte do projeto.

**`4159`** _(1 linha)_
Arquivo 4159 — parte do projeto.

**`4163`** _(1 linha)_
Arquivo 4163 — parte do projeto.

**`4165`** _(1 linha)_
Arquivo 4165 — parte do projeto.

**`4167`** _(1 linha)_
Arquivo 4167 — parte do projeto.

**`4169`** _(1 linha)_
Arquivo 4169 — parte do projeto.

**`4171`** _(1 linha)_
Arquivo 4171 — parte do projeto.

**`4173`** _(1 linha)_
Arquivo 4173 — parte do projeto.

**`6102`** _(1 linha)_
Arquivo 6102 — parte do projeto.

**`6104`** _(1 linha)_
Arquivo 6104 — parte do projeto.

**`6106`** _(1 linha)_
Arquivo 6106 — parte do projeto.

**`6175`** _(1 linha)_
Arquivo 6175 — parte do projeto.

**`6228`** _(1 linha)_
Arquivo 6228 — parte do projeto.

**`6237`** _(1 linha)_
Arquivo 6237 — parte do projeto.

**`826`** _(1 linha)_
Arquivo 826 — parte do projeto.

**`PG_VERSION`** _(2 linhas)_
Arquivo PG_VERSION — parte do projeto.

---

### 📁 `www/dados/banco/base/4/`
> Pasta '4' — agrupamento de arquivos relacionados.

**`12599`** _(1 linha)_
Arquivo 12599 — parte do projeto.

**`12604`** _(1 linha)_
Arquivo 12604 — parte do projeto.

**`12609`** _(1 linha)_
Arquivo 12609 — parte do projeto.

**`12614`** _(1 linha)_
Arquivo 12614 — parte do projeto.

**`1417`** _(1 linha)_
Arquivo 1417 — parte do projeto.

**`1418`** _(1 linha)_
Arquivo 1418 — parte do projeto.

**`2224`** _(1 linha)_
Arquivo 2224 — parte do projeto.

**`2328`** _(1 linha)_
Arquivo 2328 — parte do projeto.

**`2336`** _(1 linha)_
Arquivo 2336 — parte do projeto.

**`2604`** _(1 linha)_
Arquivo 2604 — parte do projeto.

**`2611`** _(1 linha)_
Arquivo 2611 — parte do projeto.

**`2613`** _(1 linha)_
Arquivo 2613 — parte do projeto.

**`2620`** _(1 linha)_
Arquivo 2620 — parte do projeto.

**`2830`** _(1 linha)_
Arquivo 2830 — parte do projeto.

**`2832`** _(1 linha)_
Arquivo 2832 — parte do projeto.

**`2834`** _(1 linha)_
Arquivo 2834 — parte do projeto.

**`2995`** _(1 linha)_
Arquivo 2995 — parte do projeto.

**`3118`** _(1 linha)_
Arquivo 3118 — parte do projeto.

**`3256`** _(1 linha)_
Arquivo 3256 — parte do projeto.

**`3350`** _(1 linha)_
Arquivo 3350 — parte do projeto.

**`3381`** _(1 linha)_
Arquivo 3381 — parte do projeto.

**`3429`** _(1 linha)_
Arquivo 3429 — parte do projeto.

**`3430`** _(1 linha)_
Arquivo 3430 — parte do projeto.

**`3439`** _(1 linha)_
Arquivo 3439 — parte do projeto.

**`3466`** _(1 linha)_
Arquivo 3466 — parte do projeto.

**`3501`** _(1 linha)_
Arquivo 3501 — parte do projeto.

**`3576`** _(1 linha)_
Arquivo 3576 — parte do projeto.

**`3596`** _(1 linha)_
Arquivo 3596 — parte do projeto.

**`3598`** _(1 linha)_
Arquivo 3598 — parte do projeto.

**`4143`** _(1 linha)_
Arquivo 4143 — parte do projeto.

**`4145`** _(1 linha)_
Arquivo 4145 — parte do projeto.

**`4147`** _(1 linha)_
Arquivo 4147 — parte do projeto.

**`4149`** _(1 linha)_
Arquivo 4149 — parte do projeto.

**`4151`** _(1 linha)_
Arquivo 4151 — parte do projeto.

**`4153`** _(1 linha)_
Arquivo 4153 — parte do projeto.

**`4155`** _(1 linha)_
Arquivo 4155 — parte do projeto.

**`4157`** _(1 linha)_
Arquivo 4157 — parte do projeto.

**`4159`** _(1 linha)_
Arquivo 4159 — parte do projeto.

**`4163`** _(1 linha)_
Arquivo 4163 — parte do projeto.

**`4165`** _(1 linha)_
Arquivo 4165 — parte do projeto.

**`4167`** _(1 linha)_
Arquivo 4167 — parte do projeto.

**`4169`** _(1 linha)_
Arquivo 4169 — parte do projeto.

**`4171`** _(1 linha)_
Arquivo 4171 — parte do projeto.

**`4173`** _(1 linha)_
Arquivo 4173 — parte do projeto.

**`6102`** _(1 linha)_
Arquivo 6102 — parte do projeto.

**`6104`** _(1 linha)_
Arquivo 6104 — parte do projeto.

**`6106`** _(1 linha)_
Arquivo 6106 — parte do projeto.

**`6175`** _(1 linha)_
Arquivo 6175 — parte do projeto.

**`6228`** _(1 linha)_
Arquivo 6228 — parte do projeto.

**`6237`** _(1 linha)_
Arquivo 6237 — parte do projeto.

**`826`** _(1 linha)_
Arquivo 826 — parte do projeto.

**`PG_VERSION`** _(2 linhas)_
Arquivo PG_VERSION — parte do projeto.

---

### 📁 `www/dados/banco/base/5/`
> Pasta '5' — agrupamento de arquivos relacionados.

**`12599`** _(1 linha)_
Arquivo 12599 — parte do projeto.

**`12604`** _(1 linha)_
Arquivo 12604 — parte do projeto.

**`12609`** _(1 linha)_
Arquivo 12609 — parte do projeto.

**`12614`** _(1 linha)_
Arquivo 12614 — parte do projeto.

**`1417`** _(1 linha)_
Arquivo 1417 — parte do projeto.

**`1418`** _(1 linha)_
Arquivo 1418 — parte do projeto.

**`2224`** _(1 linha)_
Arquivo 2224 — parte do projeto.

**`2328`** _(1 linha)_
Arquivo 2328 — parte do projeto.

**`2336`** _(1 linha)_
Arquivo 2336 — parte do projeto.

**`2604`** _(1 linha)_
Arquivo 2604 — parte do projeto.

**`2611`** _(1 linha)_
Arquivo 2611 — parte do projeto.

**`2613`** _(1 linha)_
Arquivo 2613 — parte do projeto.

**`2620`** _(1 linha)_
Arquivo 2620 — parte do projeto.

**`2830`** _(1 linha)_
Arquivo 2830 — parte do projeto.

**`2832`** _(1 linha)_
Arquivo 2832 — parte do projeto.

**`2834`** _(1 linha)_
Arquivo 2834 — parte do projeto.

**`2995`** _(1 linha)_
Arquivo 2995 — parte do projeto.

**`3118`** _(1 linha)_
Arquivo 3118 — parte do projeto.

**`3256`** _(1 linha)_
Arquivo 3256 — parte do projeto.

**`3350`** _(1 linha)_
Arquivo 3350 — parte do projeto.

**`3381`** _(1 linha)_
Arquivo 3381 — parte do projeto.

**`3429`** _(1 linha)_
Arquivo 3429 — parte do projeto.

**`3430`** _(1 linha)_
Arquivo 3430 — parte do projeto.

**`3439`** _(1 linha)_
Arquivo 3439 — parte do projeto.

**`3466`** _(1 linha)_
Arquivo 3466 — parte do projeto.

**`3501`** _(1 linha)_
Arquivo 3501 — parte do projeto.

**`3576`** _(1 linha)_
Arquivo 3576 — parte do projeto.

**`3596`** _(1 linha)_
Arquivo 3596 — parte do projeto.

**`3598`** _(1 linha)_
Arquivo 3598 — parte do projeto.

**`4143`** _(1 linha)_
Arquivo 4143 — parte do projeto.

**`4145`** _(1 linha)_
Arquivo 4145 — parte do projeto.

**`4147`** _(1 linha)_
Arquivo 4147 — parte do projeto.

**`4149`** _(1 linha)_
Arquivo 4149 — parte do projeto.

**`4151`** _(1 linha)_
Arquivo 4151 — parte do projeto.

**`4153`** _(1 linha)_
Arquivo 4153 — parte do projeto.

**`4155`** _(1 linha)_
Arquivo 4155 — parte do projeto.

**`4157`** _(1 linha)_
Arquivo 4157 — parte do projeto.

**`4159`** _(1 linha)_
Arquivo 4159 — parte do projeto.

**`4163`** _(1 linha)_
Arquivo 4163 — parte do projeto.

**`4165`** _(1 linha)_
Arquivo 4165 — parte do projeto.

**`4167`** _(1 linha)_
Arquivo 4167 — parte do projeto.

**`4169`** _(1 linha)_
Arquivo 4169 — parte do projeto.

**`4171`** _(1 linha)_
Arquivo 4171 — parte do projeto.

**`4173`** _(1 linha)_
Arquivo 4173 — parte do projeto.

**`6102`** _(1 linha)_
Arquivo 6102 — parte do projeto.

**`6104`** _(1 linha)_
Arquivo 6104 — parte do projeto.

**`6106`** _(1 linha)_
Arquivo 6106 — parte do projeto.

**`6175`** _(1 linha)_
Arquivo 6175 — parte do projeto.

**`6228`** _(1 linha)_
Arquivo 6228 — parte do projeto.

**`6237`** _(1 linha)_
Arquivo 6237 — parte do projeto.

**`826`** _(1 linha)_
Arquivo 826 — parte do projeto.

**`PG_VERSION`** _(2 linhas)_
Arquivo PG_VERSION — parte do projeto.

---

### 📁 `android/app/src/main/res/xml/`
> Pasta 'xml' — agrupamento de arquivos relacionados.

**`rede.xml`** _(8 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `www/android/app/src/main/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`__ponte.js`** _(99 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`capacitor.config.json`** _(9 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`capacitor.plugins.json`** _(2 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

---

### 📁 `www/android/app/src/main/assets/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`cordova.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`cordova_plugins.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`index.html`** _(30 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(27 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(34 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `www/android/app/src/main/res/xml/`
> Pasta 'xml' — agrupamento de arquivos relacionados.

**`config.xml`** _(6 linhas)_
Arquivo XML — parte do projeto.

**`rede.xml`** _(8 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `android/app/src/main/java/app/minisk/shell/`
> Pasta 'shell' — agrupamento de arquivos relacionados.

**`MainActivity.java`** _(273 linhas)_
Arquivo JAVA — parte do projeto.

---

### 📁 `www/android/app/src/main/assets/public/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`icon-CTxW8nPR.svg`** _(2 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`index-YmvJSp3J.css`** _(11 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`manifest-alaULjTv.json`** _(95 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

---

### 📁 `www/android/app/src/main/java/app/minisk/shell/`
> Pasta 'shell' — agrupamento de arquivos relacionados.

**`MainActivity.java`** _(273 linhas)_
Arquivo JAVA — parte do projeto.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS
Tipo: Aplicacao Web Frontend (React)
Stack: React, TypeScript
Arquivos: 380 | Linhas: ~43.240
Rotas API: 53 endpoint(s) detectado(s)
Variaveis de ambiente necessarias: DATA_DIR, STORAGE_PATH, LOG_LEVEL, C, TTS_VOZ, TTS_VELOCIDADE, TTS_TOM, AI_INTEGRATIONS_GEMINI_BASE_URL, AI_INTEGRATIONS_GEMINI_API_KEY, PATH, PORT

Estrutura principal:
  .github/workflows/apk-capacitor.yml
  .github/workflows/apk.yml
  .github/workflows/build-desktop.yml
  .github/workflows/desktop-exe.yml
  .gitignore
  .npmrc
  .sk/hub.json
  .sk/memoria.json
  1.md
  PLANO.md
  README.md
  SISTEMA.md
  android/app/build.gradle
  android/app/src/main/AndroidManifest.xml
  android/app/src/main/assets/__ponte.js
  android/app/src/main/java/app/minisk/shell/MainActivity.java
  android/app/src/main/res/xml/rede.xml
  android/build.gradle
  android/gradle.properties
  android/settings.gradle
  apk.config.json
  capacitor.config.json
  electron/main.cjs
  electron/preload.cjs
  icons/icon.svg
  icons/maskable.svg
  index.html
  main.js
  manifest.json
  package.json
  preload.js
  service-worker.js
  www/.github/workflows/apk-capacitor.yml
  www/.github/workflows/apk.yml
  www/.github/workflows/desktop-exe.yml
  www/.github/workflows/teste.yml
  www/.github/workflows/windows.yml
  www/.gitignore
  www/.npmrc
  www/.sk/plano.md
  www/404.html
  www/LEIA-ME.md
  www/PLANO.md
  www/android/app/build.gradle
  www/android/app/capacitor.build.gradle
  www/android/app/src/main/AndroidManifest.xml
  www/android/app/src/main/assets/__ponte.js
  www/android/app/src/main/assets/capacitor.config.json
  www/android/app/src/main/assets/capacitor.plugins.json
  www/android/app/src/main/assets/public/assets/icon-CTxW8nPR.svg
  www/android/app/src/main/assets/public/assets/index-YmvJSp3J.css
  www/android/app/src/main/assets/public/assets/manifest-alaULjTv.json
  www/android/app/src/main/assets/public/cordova.js
  www/android/app/src/main/assets/public/cordova_plugins.js
  www/android/app/src/main/assets/public/favicon.svg
  www/android/app/src/main/assets/public/index.html
  www/android/app/src/main/assets/public/manifest.json
  www/android/app/src/main/assets/public/sw.js
  www/android/app/src/main/java/app/minisk/shell/MainActivity.java
  www/android/app/src/main/res/xml/config.xml
  www/android/app/src/main/res/xml/rede.xml
  www/android/build.gradle
  www/android/capacitor-cordova-android-plugins/build.gradle
  www/android/capacitor-cordova-android-plugins/cordova.variables.gradle
  www/android/capacitor-cordova-android-plugins/src/main/AndroidManifest.xml
  www/android/capacitor.settings.gradle
  www/android/gradle.properties
  www/android/settings.gradle
  www/apk.config.json
  www/capacitor.config.json
  www/dados/banco/PG_VERSION
  www/dados/banco/base/1/12599
  www/dados/banco/base/1/12604
  www/dados/banco/base/1/12609
  www/dados/banco/base/1/12614
  www/dados/banco/base/1/1417
  www/dados/banco/base/1/1418
  www/dados/banco/base/1/16385
  www/dados/banco/base/1/16392
  www/dados/banco/base/1/16397
  www/dados/banco/base/1/16402
  www/dados/banco/base/1/16413
  www/dados/banco/base/1/16418
  www/dados/banco/base/1/16423
  www/dados/banco/base/1/16433
  www/dados/banco/base/1/2328
  www/dados/banco/base/1/2336
  www/dados/banco/base/1/2611
  www/dados/banco/base/1/2613
  www/dados/banco/base/1/2830
  www/dados/banco/base/1/2832
  www/dados/banco/base/1/2834
  www/dados/banco/base/1/2995
  www/dados/banco/base/1/3118
  www/dados/banco/base/1/3256
  www/dados/banco/base/1/3350
  www/dados/banco/base/1/3381
  www/dados/banco/base/1/3429
  www/dados/banco/base/1/3430
  www/dados/banco/base/1/3439
  www/dados/banco/base/1/3466
  www/dados/banco/base/1/3501
  www/dados/banco/base/1/3576
  www/dados/banco/base/1/3596
  www/dados/banco/base/1/3598
  www/dados/banco/base/1/4143
  www/dados/banco/base/1/4145
  www/dados/banco/base/1/4147
  www/dados/banco/base/1/4149
  www/dados/banco/base/1/4151
  www/dados/banco/base/1/4153
  www/dados/banco/base/1/4155
  www/dados/banco/base/1/4157
  www/dados/banco/base/1/4159
  www/dados/banco/base/1/4163
  www/dados/banco/base/1/4165
  www/dados/banco/base/1/4167
  www/dados/banco/base/1/4169
  www/dados/banco/base/1/4171
  www/dados/banco/base/1/4173
  www/dados/banco/base/1/6102
  www/dados/banco/base/1/6104
  www/dados/banco/base/1/6106
  www/dados/banco/base/1/6175
  www/dados/banco/base/1/6228
  www/dados/banco/base/1/6237
  www/dados/banco/base/1/826
  www/dados/banco/base/1/PG_VERSION
  www/dados/banco/base/4/12599
  www/dados/banco/base/4/12604
  www/dados/banco/base/4/12609
  www/dados/banco/base/4/12614
  www/dados/banco/base/4/1417
  www/dados/banco/base/4/1418
  www/dados/banco/base/4/2224
  www/dados/banco/base/4/2328
  www/dados/banco/base/4/2336
  www/dados/banco/base/4/2604
  www/dados/banco/base/4/2611
  www/dados/banco/base/4/2613
  www/dados/banco/base/4/2620
  www/dados/banco/base/4/2830
  www/dados/banco/base/4/2832
  www/dados/banco/base/4/2834
  www/dados/banco/base/4/2995
  www/dados/banco/base/4/3118
  www/dados/banco/base/4/3256
  www/dados/banco/base/4/3350
  www/dados/banco/base/4/3381
  www/dados/banco/base/4/3429
  www/dados/banco/base/4/3430
  www/dados/banco/base/4/3439
  www/dados/banco/base/4/3466
  www/dados/banco/base/4/3501
  www/dados/banco/base/4/3576
  www/dados/banco/base/4/3596
  www/dados/banco/base/4/3598
  www/dados/banco/base/4/4143
  www/dados/banco/base/4/4145
  www/dados/banco/base/4/4147
  www/dados/banco/base/4/4149
  www/dados/banco/base/4/4151
  www/dados/banco/base/4/4153
  www/dados/banco/base/4/4155
  www/dados/banco/base/4/4157
  www/dados/banco/base/4/4159
  www/dados/banco/base/4/4163
  www/dados/banco/base/4/4165
  www/dados/banco/base/4/4167
  www/dados/banco/base/4/4169
  www/dados/banco/base/4/4171
  www/dados/banco/base/4/4173
  www/dados/banco/base/4/6102
  www/dados/banco/base/4/6104
  www/dados/banco/base/4/6106
  www/dados/banco/base/4/6175
  www/dados/banco/base/4/6228
  www/dados/banco/base/4/6237
  www/dados/banco/base/4/826
  www/dados/banco/base/4/PG_VERSION
  www/dados/banco/base/5/12599
  www/dados/banco/base/5/12604
  www/dados/banco/base/5/12609
  www/dados/banco/base/5/12614
  www/dados/banco/base/5/1417
  www/dados/banco/base/5/1418
  www/dados/banco/base/5/2224
  www/dados/banco/base/5/2328
  www/dados/banco/base/5/2336
  www/dados/banco/base/5/2604
  www/dados/banco/base/5/2611
  www/dados/banco/base/5/2613
  www/dados/banco/base/5/2620
  www/dados/banco/base/5/2830
  www/dados/banco/base/5/2832
  www/dados/banco/base/5/2834
  www/dados/banco/base/5/2995
  www/dados/banco/base/5/3118
  www/dados/banco/base/5/3256
  www/dados/banco/base/5/3350
  www/dados/banco/base/5/3381
  www/dados/banco/base/5/3429
  www/dados/banco/base/5/3430
  www/dados/banco/base/5/3439
  www/dados/banco/base/5/3466
  www/dados/banco/base/5/3501
  www/dados/banco/base/5/3576
  www/dados/banco/base/5/3596
  www/dados/banco/base/5/3598
  www/dados/banco/base/5/4143
  www/dados/banco/base/5/4145
  www/dados/banco/base/5/4147
  www/dados/banco/base/5/4149
  www/dados/banco/base/5/4151
  www/dados/banco/base/5/4153
  www/dados/banco/base/5/4155
  www/dados/banco/base/5/4157
  www/dados/banco/base/5/4159
  www/dados/banco/base/5/4163
  www/dados/banco/base/5/4165
  www/dados/banco/base/5/4167
  www/dados/banco/base/5/4169
  www/dados/banco/base/5/4171
  www/dados/banco/base/5/4173
  www/dados/banco/base/5/6102
  www/dados/banco/base/5/6104
  www/dados/banco/base/5/6106
  www/dados/banco/base/5/6175
  www/dados/banco/base/5/6228
  www/dados/banco/base/5/6237
  www/dados/banco/base/5/826
  www/dados/banco/base/5/PG_VERSION
  www/dados/banco/global/1214
  www/dados/banco/global/2846
  www/dados/banco/global/2964
  www/dados/banco/global/2966
  www/dados/banco/global/3592
  www/dados/banco/global/4060
  www/dados/banco/global/4175
  www/dados/banco/global/4177
  www/dados/banco/global/4181
  www/dados/banco/global/4183
  www/dados/banco/global/4185
  www/dados/banco/global/6000
  www/dados/banco/global/6100
  www/dados/banco/global/6243
  www/dados/banco/global/6244
  www/dados/banco/pg_hba.conf
  www/dados/banco/pg_ident.conf
  www/dados/banco/postgresql.auto.conf
  www/dados/banco/postgresql.conf
  www/dados/banco/postmaster.pid
  www/electron/main.cjs
  www/electron/preload.cjs
  www/icons/icon.svg
  www/icons/maskable.svg
  www/index.html
  www/iniciar.bat
  www/iniciar.sh
  www/lib/api-client-react/index.ts
  www/lib/api-zod/index.ts
  www/lib/db/index.ts
  www/manifest.json
  www/package.json
  www/public/favicon.svg
  www/public/manifest.json
  www/public/sw.js
  www/scripts/abrir-pronto.mjs
  www/scripts/iniciar.mjs
  www/server/app.ts
  www/server/index.ts
  www/server/lib/devServerRegistry.ts
  www/server/lib/gemini-ponte.ts
  www/server/lib/logger.ts
  www/server/lib/persistFiles.ts
  www/server/lib/shell.ts
  www/server/lib/storage.ts
  www/server/lib/tar.ts
  www/server/lib/tts.ts
  www/server/routes/ai.ts
  www/server/routes/code-assistant.ts
  www/server/routes/code-run.ts
  www/server/routes/dev-server.ts
  www/server/routes/exec.ts
  www/server/routes/files.ts
  www/server/routes/git.ts
  www/server/routes/github.ts
  www/server/routes/health.ts
  www/server/routes/import-github.ts
  www/server/routes/index.ts
  www/server/routes/preview.ts
  www/server/routes/projects.ts
  www/server/routes/settings.ts
  www/server/routes/snippets.ts
  www/service-worker.js
  www/src/App.tsx
  www/src/components/ai-panel.tsx
  www/src/components/code-editor.tsx
  www/src/components/code-viewer.tsx
  www/src/components/error-boundary.tsx
  www/src/components/file-tree.tsx
  www/src/components/git-history-modal.tsx
  www/src/components/github-conta.tsx
  www/src/components/github-deploy-modal.tsx
  www/src/components/layout.tsx
  www/src/components/packages-panel.tsx
  www/src/components/preview-panel.tsx
  www/src/components/terminal-panel.tsx
  www/src/components/theme-provider.tsx
  www/src/components/ui/accordion.tsx
  www/src/components/ui/alert-dialog.tsx
  www/src/components/ui/alert.tsx
  www/src/components/ui/aspect-ratio.tsx
  www/src/components/ui/avatar.tsx
  www/src/components/ui/badge.tsx
  www/src/components/ui/breadcrumb.tsx
  www/src/components/ui/button-group.tsx
  www/src/components/ui/button.tsx
  www/src/components/ui/calendar.tsx
  www/src/components/ui/card.tsx
  www/src/components/ui/carousel.tsx
  www/src/components/ui/chart.tsx
  www/src/components/ui/checkbox.tsx
  www/src/components/ui/collapsible.tsx
  www/src/components/ui/command.tsx
  www/src/components/ui/context-menu.tsx
  www/src/components/ui/dialog.tsx
  www/src/components/ui/drawer.tsx
  www/src/components/ui/dropdown-menu.tsx
  www/src/components/ui/empty.tsx
  www/src/components/ui/field.tsx
  www/src/components/ui/form.tsx
  www/src/components/ui/hover-card.tsx
  www/src/components/ui/input-group.tsx
  www/src/components/ui/input-otp.tsx
  www/src/components/ui/input.tsx
  www/src/components/ui/item.tsx
  www/src/components/ui/kbd.tsx
  www/src/components/ui/label.tsx
  www/src/components/ui/menubar.tsx
  www/src/components/ui/navigation-menu.tsx
  www/src/components/ui/pagination.tsx
  www/src/components/ui/popover.tsx
  www/src/components/ui/progress.tsx
  www/src/components/ui/radio-group.tsx
  www/src/components/ui/resizable.tsx
  www/src/components/ui/scroll-area.tsx
  www/src/components/ui/select.tsx
  www/src/components/ui/separator.tsx
  www/src/components/ui/sheet.tsx
  www/src/components/ui/sidebar.tsx
  www/src/components/ui/skeleton.tsx
  www/src/components/ui/slider.tsx
  www/src/components/ui/sonner.tsx
  www/src/components/ui/spinner.tsx
  www/src/components/ui/switch.tsx
  www/src/components/ui/table.tsx
  www/src/components/ui/tabs.tsx
  www/src/components/ui/textarea.tsx
  www/src/components/ui/toast.tsx
  www/src/components/ui/toaster.tsx
  www/src/components/ui/toggle-group.tsx
  www/src/components/ui/toggle.tsx
  www/src/components/ui/tooltip.tsx
  www/src/hooks/use-file-ops.ts
  www/src/hooks/use-mobile.tsx
  www/src/hooks/use-toast.ts
  www/src/index.css
  www/src/lib/utils.ts
  www/src/main.tsx
  www/src/pages/assistant.tsx
  www/src/pages/home.tsx
  www/src/pages/not-found.tsx
  www/src/pages/playground.tsx
  www/src/pages/project-explorer.tsx
  www/src/pages/settings.tsx
  www/termux-atalho.sh
  www/tsconfig.json
  www/vite.config.ts
  www/windows/Abrir-CodeLens.bat
```

---

*Plano gerado pelo SK Code Editor — 23/10/2026, 04:38:30*
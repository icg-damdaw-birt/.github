# ¡Bienvenido al Curso de Integración Continua con GitHub!

Esta organización contiene todos los repositorios de ejemplo y las plantillas para el módulo **ICG** de los ciclos DAM y DAW en BIRT.

### 🚀 Repositorios Principales

Aquí encontrarás las "Apps de Referencia" con la solución completa:
* **API Backend:** `mivideoteca-api`
* **Frontend Web (DAW):** `mivideoteca-web`
* **Frontend App (DAM):** `mivideoteca-app`

### 💀 Plantillas de Arranque (Starters)

Estos son los esqueletos que debes usar como punto de partida para tus tareas:
* **API Backend:** `mivideoteca-api-starter`
* **Frontend Web (DAW):** `mivideoteca-web-starter`
* **Frontend App (DAM):** `mivideoteca-app-starter`

## 🏗️ Arquitectura del proyecto
```
Backend (mivideoteca-api/)     ← Una sola API
    ├── Express + JWT
    ├── Prisma + SQLite 
    └── Puerto 3000

Frontend Mobile (mivideoteca-app/)   ← Flutter
    ├── Provider pattern
    └── Misma API

Frontend Web (mivideoteca-web/)      ← SvelteKit  
    ├── Stores + componentes
    └── Misma API
```

## 🚀 Comandos rápidos
```bash
# Backend
cd mivideoteca-api && npm run dev

# Flutter  
cd mivideoteca-app && flutter run

# Web
cd mivideoteca-web && npm run dev
```


¡Mucho éxito en el curso!

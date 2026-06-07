# My Planner Pro — PWA

## 🚀 Cómo usar

### Opción 1: Archivo único (más fácil)
Abre `MyPlannerPro.html` directamente en tu navegador.  
Para instalar como app, el navegador mostrará automáticamente un banner de instalación.

### Opción 2: Servidor local (recomendado para PWA completa)
```bash
# Con Python
python3 -m http.server 8080

# Con Node.js
npx serve .
```
Luego visita `http://localhost:8080/MyPlannerPro.html`

## ✅ Funcionalidades PWA incluidas
- ⚡ **Service Worker** — caché offline (funciona sin internet)
- 📱 **Instalable** — banner de instalación en Chrome/Edge/Safari
- 💾 **IndexedDB** — persistencia local de todos los datos
- 🌙 **Dark/Light mode** — guardado en localStorage
- 📲 **Responsive** — optimizado para móvil y desktop
- 🔒 **Sin backend** — 100% datos locales, privacidad total

## 📦 Estructura del proyecto React (opcional)
```
my-planner-pwa/
├── MyPlannerPro.html    ← ARCHIVO PRINCIPAL (standalone PWA)
├── public/
│   ├── index.html       ← Para build con CRA
│   ├── manifest.json    ← PWA manifest
│   └── sw.js            ← Service Worker externo
├── src/
│   ├── index.tsx        ← Entry point React
│   └── App.tsx          ← Componente principal
└── package.json         ← Dependencias (si usas npm build)
```

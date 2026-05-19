# TRAIL STRENGTH 80K — App Web

App completa de entrenamiento de fuerza para trail running 80K.  
**localStorage** nativo del navegador → historial siempre guardado.

---

## 🚀 Opción A — GitHub Pages (GRATIS, online siempre)

1. Crea una cuenta en [github.com](https://github.com) si no tienes
2. Crea un repositorio nuevo → **"trail-strength"**
3. Sube el archivo `index.html` al repo
4. Ve a **Settings → Pages → Branch: main → / (root) → Save**
5. En 1 minuto tendrás tu app en: `https://TU-USUARIO.github.io/trail-strength`

---

## ⚡ Opción B — Vercel (GRATIS, deploy en 30 segundos)

1. Ve a [vercel.com](https://vercel.com) → Sign up con GitHub
2. **"Add New Project"** → importa el repo "trail-strength"
3. Deploy → URL instantánea tipo `trail-strength.vercel.app`

---

## 🌐 Opción C — Netlify (GRATIS, drag & drop)

1. Ve a [app.netlify.com](https://app.netlify.com)
2. Arrastra la carpeta **trail_strength_app/** directamente al browser
3. URL lista en segundos: `random-name.netlify.app`

---

## 💾 Opción D — Local (sin internet)

Solo abre `index.html` en Chrome, Firefox o Safari.  
El historial se guarda en localStorage del navegador de ese dispositivo.

---

## 📤 Exportar a Strava / TrainingPeaks

### Método TCX (dentro de la app)
1. Ve a **HISTORIAL → Exportar a Strava / TrainingPeaks**
2. Selecciona una sesión del dropdown
3. Descarga el `.tcx`
4. Súbelo manualmente:
   - **Strava**: strava.com/upload/select
   - **TrainingPeaks**: tp.com → Calendario → + → Subir archivo
   - **Garmin Connect**: connect.garmin.com → Importar datos

### Método JSON (backup completo)
- **Exportar**: botón "⬇ EXPORTAR" → descarga `trail_strength_XXXX.json`
- **Importar**: botón "⬆ IMPORTAR" → restaura todo el historial

---

## 🔑 Notas técnicas

- El historial usa `localStorage` del navegador (sin servidor, sin cuenta)
- La búsqueda de videos usa la API de Claude (requiere conexión)
- Compatible con Chrome, Firefox, Safari, Edge
- Diseñado para pantallas ≥ 768px (desktop/tablet)

---

**Carrera objetivo: 8 de octubre 2026 · 80K Trail Running**

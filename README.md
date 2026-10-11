# 📺 BebixTV

Aplicación web ligera de reproducción de **televisión en directo internacional** con panel de administración integrado. Construida con **HTML + CSS + Vanilla JavaScript** y reproducción HLS mediante `hls.js`.

## ✨ Características

- 🎬 Reproductor HLS en vivo con `hls.js`
- 🌙 Interfaz oscura estilo streaming (azul/gris)
- 🔍 Buscador en tiempo real y filtro por país/grupo
- ⛶ Pantalla completa y recarga del canal
- ⚙️ Panel de administración (BebixAdmin) para:
  - Añadir canales
  - Activar / desactivar canales
  - Eliminar canales con confirmación
  - Exportar `channels.json` actualizado
- 💾 Persistencia local vía `localStorage`

## 📁 Estructura del proyecto

| Archivo | Función |
|--------|---------|
| `index.html` | Reproductor principal (BebixTV) |
| `admin.html` | Panel de administración (BebixAdmin) |
| `channels.json` | Base de datos de canales |
| `README.md` | Documentación |

## 🚀 Despliegue en GitHub Pages

1. Crea un repositorio en GitHub, por ejemplo `bebixtv`.
2. Sube los 4 archivos a la rama `main`:
   ```bash
   git init
   git add .
   git commit -m "BebixTV inicial"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/bebixtv.git
   git push -u origin main

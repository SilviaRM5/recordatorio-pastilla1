# 📌 Recordatorio Pastilla AC 💊  
Una aplicación web que te recordará tomar tu pastilla **AC** todos los días a las 23:00 con una **notificación emergente** y una **vibración** en tu dispositivo móvil.  

## 🌟 Características  
✅ **Notificación automática** a las 23:00.  
✅ **Vibración de recordatorio** (si el dispositivo lo soporta).  
✅ **Modo PWA** (se puede instalar en móviles como una aplicación).  
✅ **Diseño llamativo** con colores rosa, naranja y rojo.  
✅ **Fuente Comic Sans** para un aspecto amigable.  

## 🚀 Cómo usar la aplicación  
1. **Abre el archivo `recordatorio.html`** en tu navegador.  
2. **Activa las notificaciones** haciendo clic en el botón "Activar Notificación".  
3. **Deja la aplicación abierta** para recibir el aviso a las 23:00.  
4. **Si estás en móvil, agrégala a la pantalla de inicio** para que funcione como una app independiente.  

## 📱 Instalación como PWA  
### En Android (Chrome):  
1. Abre la aplicación en tu navegador.  
2. Pulsa el icono de menú (tres puntos).  
3. Selecciona **"Agregar a pantalla de inicio"**.  
4. ¡Listo! Ahora podrás abrirla como una app nativa.  

### En iPhone (Safari):  
1. Abre la aplicación en Safari.  
2. Pulsa el botón de compartir.  
3. Selecciona **"Agregar a pantalla de inicio"**.  
4. Asigna un nombre y confirma.  

## 🎨 Personalización  
Si quieres cambiar los colores o el tamaño del texto, puedes editar estos elementos en `recordatorio.html`:  
- **Color de fondo:** Cambia `bg-pink-300` a otro tono (`bg-red-500`).  
- **Color del botón:** Cambia `bg-red-600` a otro color (`bg-orange-500`).  
- **Fuente:** Si prefieres otra, reemplaza `"Comic Sans MS"` por otro estilo.  

## 📂 Archivos incluidos  
- `recordatorio.html` → La página principal de la aplicación.  
- `manifest.json` → Archivo que permite la instalación en móviles.  
- `sw.js` → Service Worker que optimiza el funcionamiento de la app.  
- `icon.png` → Icono de 512x512 píxeles con fondo rojo o rosa.
# Puedes borrar este archivo — es solo una guía de instalación

## 0. Antes de extraer: verifica cómo se ve por dentro
Haz doble clic en el zip DEBES ver carpetas (assets/, categoria/, guias/, ...)
además de archivos. Si tu visor muestra solo archivos .html sueltos, no lo uses:
extrae con clic derecho -> "Extraer todo" (Windows) o doble clic (Mac).
Al extraer debes ver 17 elementos: 5 archivos y 12 carpetas.
Si ves 20 archivos y cero carpetas, la extracción aplastó las carpetas:
repite con otro método antes de subir nada.

## 1. El repositorio debe llamarse EXACTAMENTE como tu usuario
Tu usuario es: tramites-claros
Tu repositorio debe llamarse: tramites-claros.github.io
(Si lo creaste con otro nombre, es más fácil borrarlo y crearlo de nuevo:
Settings -> General -> bajar hasta "Danger Zone" -> Delete this repository.)

## 2. Subir los archivos
- En la pagina vacia del repositorio, clic en el enlace azul "uploading an existing file"
  (o boton "Add file" -> "Upload files")
- Abre la carpeta extraida, Ctrl+A (Cmd+A en Mac) para seleccionar los 17 elementos,
  y arrastralos TODOS a la caja punteada.
- Antes de Commit: la lista debe mostrar rutas como assets/style.css o
  categoria/salud/index.html. Si muestra "index (2).html" o algo aplanado, cancela.
- Commit changes.

## 3. Activar GitHub Pages
- Settings (pestaña arriba) -> Pages (menu izquierdo)
- Source: Deploy from a branch
- Branch: main  |  carpeta: / (root)  -> Save
- En 1-2 minutos tu sitio vive en: https://tramites-claros.github.io

## 4. Despues
- search.google.com/search-console -> agrega https://tramites-claros.github.io
  como "URL prefix" y envia el sitemap: /sitemap.xml

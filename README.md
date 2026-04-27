# Arqueología Prehistórica · Sitio interactivo

Un único archivo `index.html` autosuficiente con la línea de tiempo y el mapa interactivo basado en los datos de las dos tablas Excel.

## Cómo usarlo en clase

### Opción A · Localmente (la más sencilla)
Hacer doble clic en `index.html`. Se abrirá en el navegador. Necesita conexión a Internet para cargar Leaflet (mapa) desde el CDN.

### Opción B · GitHub Pages (gratis, recomendado para compartir)
1. Crear cuenta en [github.com](https://github.com).
2. Nuevo repositorio → subir `index.html`.
3. Settings → Pages → Source: **main / root** → Save.
4. URL pública: `https://USUARIO.github.io/REPO/`.

### Opción C · Netlify Drop (sin cuenta)
1. Ir a [app.netlify.com/drop](https://app.netlify.com/drop).
2. Arrastrar el archivo `index.html`.
3. Listo: URL pública generada automáticamente.

### Opción D · Cloudflare Pages, Vercel o similares
Cualquier hosting estático gratuito funciona — solo necesita servir un único HTML.

## Funcionalidades

- **Vista combinada mapa + línea de tiempo**: en escritorio ambos paneles se muestran en una misma altura de pantalla; la línea de tiempo tiene scroll interno.
- **Línea de tiempo** con 26 entradas: eras geológicas, períodos paleolíticos, especies de homínidos y culturas líticas. Tooltips al pasar el cursor sobre cada barra.
- **Resaltado comparativo**: al pasar el cursor sobre una barra del timeline o sobre un yacimiento del mapa, aparece una **banda vertical naranja** que cruza toda la línea de tiempo en la franja temporal correspondiente.
- **Mapa mundial** con 25 yacimientos arqueológicos. Click → ficha completa; hover → tooltip + resaltado temporal.
- Diseño basado en el documento PDF de referencia (paleta de colores Plioceno/Pleistoceno, mapa gris claro estilo CARTO Positron).

## Datos

Las dos hojas de Excel están integradas como datos JS dentro del propio `index.html`. Para editar contenidos, modificar los arrays `TIMELINE_ROWS` y `SITES` directamente en el archivo.


### Despliegue en Netlify (¡Nuevo!)
1. Crea una carpeta llamada `arqueologia-mapa`.
2. Mueve el archivo `index.html` (versión 2) dentro de esta carpeta.
3. Ve a [app.netlify.com/drop](https://app.netlify.com/drop).
4. Arrastra la carpeta completa (no el archivo suelto) a la zona indicada.
5. ¡Listo! Tendrás una URL pública para compartir.

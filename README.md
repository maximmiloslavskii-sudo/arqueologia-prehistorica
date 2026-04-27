# Arqueología Prehistórica · versión v7

Cambios principales:

- Código separado en `index.html`, `styles.css` y módulos JS (`data-*`, `map.js`, `timeline.js`, `site-panel.js`, `utils.js`, `app.js`).
- Nueva arquitectura visual: mapa, panel informativo y timeline como zonas independientes.
- En móvil se usan modos de vista: Mapa, Cronología, Especies/culturas, Yacimientos.
- Las fichas largas ya no dependen de popups de Leaflet: foto, texto y fuentes se muestran en un panel visible.
- Conexión timeline ↔ mapa basada en tags explícitos: `speciesTags`, `cultureTags`, `periodTags`, `routeTags`.
- Filtros por foco: pre-sapiens, Homo sapiens temprano y Paleolítico superior.
- Rutas/flechas de dispersión con nivel de confianza y notas de cautela científica.
- Añadido West Turkana · Black Skull para representar Paranthropus aethiopicus.
- Leyenda separa yacimientos, áreas aproximadas y rutas hipotéticas.
- Correcciones de mobile: tap/click fija selección; hover solo actúa como preview.

Nota: las áreas y rutas son esquemas didácticos, no reconstrucciones paleodemográficas exactas.

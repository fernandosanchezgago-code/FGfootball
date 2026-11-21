# FGFootBall Plus

Versión estática de [FGFootBall Plus](https://github.com/new-platipus6767/new-platipus.github.io/tree/45f990515d4db4fe717fd0410cecbaa852bb63fa), preparada para publicar con GitHub Pages. No necesita instalar dependencias ni ejecutar un servidor de aplicación. Los marcadores, las clasificaciones y las noticias se consultan en ESPN y requieren conexión a Internet.

## Publicar en GitHub Pages

1. Descomprime el ZIP. Sube su contenido a la raíz de la rama `main` de tu repositorio. Mantén `index.html`, `teams.json`, `fgfootball.svg`, `.nojekyll` y las carpetas `css/` y `js/` al mismo nivel. No subas solo el ZIP ni metas los archivos en una carpeta adicional.
2. En el repositorio, abre **Settings → Pages**. En **Source**, selecciona **Deploy from a branch**; elige `main` y `/(root)` y pulsa **Save** ([documentación de GitHub Pages](https://docs.github.com/es/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)).
3. Una vez desplegada, abre la URL que GitHub indica en **Settings → Pages**. La página de inicio está en `index.html`; `#inicio` es un ancla de esa página.

## Qué incluye

- `index.html`: portada, resultados, clasificación, estadísticas, noticias, fichajes y herramientas Plus.
- `css/`, `js/`, `fgfootball.svg`, `teams.json`: estilos, lógica, icono y catálogo de equipos. Mantén sus nombres y rutas.
- `.nojekyll`: indica a GitHub Pages que sirva los archivos estáticos sin procesarlos con Jekyll.

## Límites de esta versión

Las cuentas, los favoritos, las alineaciones guardadas, las aportaciones de noticias y las preferencias de cookies se almacenan en el navegador. No se comparten entre dispositivos. Esta copia no recoge direcciones IP para registrar el consentimiento ni incluye un servidor o panel de administración. Las fuentes y datos deportivos externos se consultan por separado.

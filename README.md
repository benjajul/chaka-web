# CHAKA · Vidas Conectadas — sitio web

Sitio estático (HTML + CSS + JS, sin compilación). Se publica tal cual con GitHub Pages.

```
index.html      ← la página completa (7 secciones por #ancla)
precios.json    ← precios exportados desde el programa CHAKA
logos/          ← logos oficiales del brandbook
```

## Actualizar precios
1. En el programa CHAKA: Catálogo → **⬆ Precios para la web**.
2. Reemplaza `precios.json` en este repositorio por el exportado.
3. Haz commit y push. GitHub Pages publica el cambio en uno o dos minutos.

Formato del archivo: ver `conexion-precios-web.md` en el proyecto CHAKA.

## Ver en local
Abre una terminal en esta carpeta y ejecuta `python -m http.server`, luego visita
http://localhost:8000. (Abrir index.html con doble clic no carga precios.json.)

# Our Ever-Expanding Consumerism Has Killed the Earth

Presentación web (HTML + WebGL, sin dependencias). Navegación: flechas / espacio / deslizar en celular, `F` para pantalla completa.

## Estructura
- `index.html` – toda la presentación (HTML, CSS y JS)
- `images/` – las 4 imágenes de fondo

## Probar en local
Las imágenes se cargan como texturas WebGL, así que **no funciona abriendo el archivo con doble clic** (`file://`). Usa un servidor local:

```bash
python3 -m http.server 8000
# abre http://localhost:8000
```

## Publicar en GitHub Pages
1. Sube todo a tu repo.
2. Settings → Pages → Source: `Deploy from a branch` → rama `main` y carpeta `/ (root)`.
3. Tu web queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

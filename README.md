# atila-edge-landing-page

Página de presentación (landing) del proyecto **Atila_Edge** — sismógrafo inteligente
en el borde (*edge AI*), sobre Android/Termux.

Este repositorio contiene **solo la página publicada**. El código del sistema vive en un
repositorio privado; aquí no hay firmware, ni modelos, ni datasets.

## Contenido

| Archivo | Qué es |
|---|---|
| `index.html` | La página completa. HTML y CSS embebidos, sin JavaScript, sin imágenes y sin dependencias externas. |
| `.nojekyll` | Evita que GitHub Pages procese el sitio con Jekyll (no hay nada que procesar). |

## Ver en local

```bash
python3 -m http.server 8000
# luego abrir http://localhost:8000
```

También funciona abriendo `index.html` directamente en el navegador.

## Publicación

GitHub Pages sirve desde la raíz de la rama principal (`main`), sin paso de compilación:
Settings → Pages → *Deploy from a branch* → `main` → `/ (root)`.

URL esperada: `https://galp76.github.io/atila-edge-landing-page/`

## Fuente del contenido

El texto y las cifras provienen de la ficha técnica del proyecto
(`docs/landing/landing.txt` en el repositorio privado) y de su `README.md`.
Las métricas están medidas y documentadas; los matices de medición se publican
junto a ellas, no aparte.

Regla de edición: si una cifra cambia en el repositorio del código, se actualiza aquí.

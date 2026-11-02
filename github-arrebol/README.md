# Arrebol · web

Sitio estático (HTML, imágenes y video). No necesita instalar nada ni compilar.

## Contenido

- `index.html`: la página completa
- `img/`: etiquetas, fotos e imagen de portada
- `v/`: videos (sachet con tapa y detrás de cámara)
- `favicon.png`: ícono de la pestaña

## Publicar en Vercel

1. Sube esta carpeta (`github-arrebol`) a tu repositorio de GitHub.
2. En Vercel: **Add New → Project** y elige el repositorio.
3. En **Root Directory** elige `github-arrebol`.
4. **Framework Preset:** Other. Deja vacíos Build Command y Output Directory.
5. Presiona **Deploy**.

Cada vez que cambies un archivo en GitHub, Vercel vuelve a publicar solo en 1 a 2 minutos.

## Probar en el computador

```
cd github-arrebol
python3 -m http.server 8000
```

Y abre http://localhost:8000

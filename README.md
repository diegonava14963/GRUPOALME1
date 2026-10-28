# Grupo Alme · Manual de diseño de servicios

Proyecto de Ciencia de los Servicios (O2026). Sitio estático: manual de diseño de servicios sobre Grupo Alme y directorio de sus 16 conceptos (restaurantes y antros).

## Estructura

```
index.html        Página principal
css/styles.css    Estilos
js/data.js        Contenido: páginas del manual (P), grupos (G) y locales (V)
js/app.js         Navegación y vistas
img/              Imágenes
```

## Ver en tu computadora

```
python3 -m http.server 8000
```

Abre http://localhost:8000

## Publicar en GitHub Pages

1. Sube todo el contenido de esta carpeta a la raíz del repositorio.
2. En el repositorio: Settings → Pages.
3. En "Build and deployment", elige "Deploy from a branch", rama `main` y carpeta `/ (root)`.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Editar el contenido

Los textos del manual y los datos de cada restaurante están en `js/data.js`.

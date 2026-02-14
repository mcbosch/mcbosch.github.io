# tu nombre — blog personal

Blog minimalista con estética LaTeX, alojado en [GitHub Pages](https://pages.github.com).

## Estructura

```
├── index.html              ← página principal (listado de posts)
├── about.html              ← página "sobre mí"
├── css/
│   └── style.css           ← estilos del blog
├── posts/
│   ├── _plantilla.html     ← plantilla para nuevos posts
│   ├── hola-mundo.html
│   └── sobre-espacios-de-hilbert.html
└── img/                    ← imágenes (crear cuando sea necesario)
```

## Cómo añadir una entrada nueva

1. Copia `posts/_plantilla.html` y renómbrala (ej: `posts/mi-nuevo-post.html`)
2. Edita el título, fecha, etiquetas y contenido
3. Añade un `<li class="post-item">` en `index.html` (al principio de la lista para que quede primero)
4. Haz commit y push

## Fórmulas matemáticas

Usa sintaxis LaTeX: `$...$` para fórmulas en línea y `$$...$$` para fórmulas en bloque. KaTeX las renderiza automáticamente.

## Despliegue

El sitio se despliega automáticamente en `https://USER.github.io` al hacer push a la rama `main`.

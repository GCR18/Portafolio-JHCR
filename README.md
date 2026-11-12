# Portafolio — Jhesef Condori Rondo

Intérprete y educador musical · Cochabamba, Bolivia.

Sitio estático (HTML, CSS y JavaScript en un solo archivo), sin dependencias ni compilación.

## Estructura

```
index.html        Página completa (estilos y scripts incluidos)
img/              Fotografías, partituras y vista previa del CV
audio/            Grabaciones de los arreglos (no se reproducen solas)
docs/             CV en PDF para descargar
```

## Editar contenido

Al final de `index.html`, dentro de `<script>`, está el bloque **CONTENIDO EDITABLE**:

- `TRAYECTORIA`: agrupaciones de la línea de tiempo.
- `PROYECTOS`: arreglos (título, partitura, instrumentación, audio).
- `DOCENCIA`: cargos de docencia y dirección.
- `FRASES`: frases rotativas del inicio.

Para cambiar una foto, reemplaza el archivo en `img/` con el mismo nombre.

## Publicar en GitHub Pages

1. Sube el contenido de esta carpeta a un repositorio (con `index.html` en la raíz).
2. En el repositorio: **Settings → Pages → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos el sitio queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

Para verlo en tu computadora sin subirlo: `python3 -m http.server` dentro de la carpeta y abre `http://localhost:8000`
(abrir el archivo con doble clic también funciona, salvo el dibujo de las ondas de audio).

## Pendiente de completar

- Enlaces a redes sociales y YouTube, cuando existan (se pueden agregar en la sección Contacto y en el pie de página).

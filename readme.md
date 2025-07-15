# Pautas HTML - Banners Interactivos

Este repositorio contiene varios banners interactivos en HTML, CSS y JavaScript, organizados por tipo de interacción y tamaño.

## Estructura del Proyecto

- **360/**  
  Banners con visualización 360° de producto.  
  - `300x600/`, `336x280/`, `580x400/`: Cada carpeta contiene imágenes secuenciales (`01.webp`, `02.webp`, ...) y un `index.html` que permite rotar el producto arrastrando el mouse o tocando la pantalla.

- **before_after/**  
  Banners con efecto de comparación "antes y después".  
  - `200x200/`, `300x50/`, `320x100/`, `468x60/`: Cada carpeta tiene imágenes y un `index.html` con un slider para comparar dos imágenes.

- **erase/**  
  Banners con efecto "raspa y descubre".  
  - `200x200/`, `300x50/`, `320x100/`, `468x60/`: Cada carpeta incluye un canvas y un overlay animado. El usuario puede "raspar" la imagen para revelar el contenido oculto.

- **mixturas/**  
  Banners con selección de variantes de producto.  
  - `300x600/`, `336x280/`, `580x400/`: Permiten alternar entre diferentes imágenes de producto haciendo clic en miniaturas.

## Cómo usar

1. Abre cualquier archivo `index.html` en tu navegador para ver el banner correspondiente.
2. Las imágenes deben estar presentes en cada carpeta para que los efectos funcionen correctamente.
3. Todos los banners abren la página de producto de Auteco al hacer clic en la zona interactiva.

## Personalización

- Puedes modificar las imágenes (`.webp`, `.png`) para adaptarlas a tu producto.
- Los estilos y scripts están embebidos en cada HTML para facilitar la portabilidad.

---

**Autor:**  
Jonathan Brand
LDM
2025
# DIW07_TAREA

## Decisiones de diseño

- **Colores suaves y armoniosos**: Se utilizaron los mismos tonos que en la página web del proyecto Adóptame.
- **Diseño centrado y con márgenes**: Las secciones tienen margen lateral y bordes redondeados, lo que aporta orden y estética visual, especialmente en la sección `presentacion`.
- **Diseño responsive**: A través de media queries, la galería de mascotas se adapta a distintas resoluciones (móvil, tablet, escritorio).

## Animaciones implementadas

1. **Subrayado animado en el `título`**: Al cargar, una línea crece desde el centro hasta los extremos gracias a la animación `expand-line`.

2. **Entrada suave de las mascotas**: Las imágenes SVG aparecen con un efecto de desplazamiento y opacidad (`entrada`), haciéndolas más dinámicas al cargar.

3. **Animación de botón interactivo**: Un efecto de color desliza desde la izquierda cuando se pasa el ratón (`hover`), con transición suave.

4. **Movimiento flotante en las mascotas**: Las `.mascota` flotan de arriba a abajo, de manera alternada con `animation-delay`, dando un efecto de vida.

5. **Interacción visual en SVGs**:
   - **Lengua y ojos del perro**: Parpadeo y sacar la lengua, controlados con `steps()` para dar un efecto intermitente.
   - **Bigotes del gato**: Se dibujan al cargar la página con `stroke-dashoffset`.
   - **Borde del gato**: Se dibuja en bucle, simulando un trazo animado.
   - **Erizo**: Sus astillas giran en direcciones opuestas, con diferentes velocidades.

Estas animaciones buscan captar la atención del usuario de forma sutil y dar vida a los elementos gráficos sin saturar la experiencia visual.

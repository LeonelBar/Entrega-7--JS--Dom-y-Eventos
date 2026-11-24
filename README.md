# 🎮 Super-Arcade — Pre-Entrega 7

Simulador interactivo de catálogo y compra de juegos de PlayStation 2 con interfaz dinámica en el DOM y manejo de eventos en JavaScript.

## Estructura del proyecto

- `index.html`: estructura base con formulario de alta, buscador y grilla `#contenedor`.
- `css/style.css`: estilos con estética PlayStation 2, grilla responsive y portadas.
- `js/main.js`: clase `Juego`, catálogo inicial, renderizado con `innerHTML` y eventos (`submit`, `click`, `keyup`).
- `img/`: portadas de los juegos y `portada-default.jpg` como imagen por defecto.

## Funcionalidades

- **Agregar juego**: carga nombre, precio y stock desde el formulario sin recargar la página.
- **Buscar en tiempo real**: filtra el catálogo mientras escribís en el buscador.
- **Comprar y eliminar**: descuenta stock o quita juegos directamente desde cada tarjeta.
- **Feedback visual**: muestra mensajes en pantalla ante cada acción o validación.

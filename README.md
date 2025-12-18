# Reto Lección 2 - Profile Card

Tarjeta de perfil sencilla hecha con HTML y CSS. El objetivo principal fue centrar la tarjeta sin usar grid ni flex.

## Estructura
- `reto.html`: Marcado principal de la tarjeta.
- `reto.css`: Estilos de la tarjeta y el centrado.
- `img`: Coloca aquí la imagen para la tarjeta.

## Vista rápida
- Fondo oscuro (`#141414`).
- Tarjeta de 240x500 px, bordes redondeados.
- Imagen de perfil circular, nombre, ubicación, descripción y enlaces tipo botón.

## Cómo probar
1) Abre el archivo `reto.html` directamente en tu navegador (doble clic o "Open with Browser").
2) Verifica que `reto.css` esté en la misma carpeta y que la imagen `pamnew.png` exista en la ruta indicada.
3) Ajusta los enlaces de los botones (`href`) con tus URLs reales.

## Personalización rápida
- Cambia colores en `reto.css` (`background-color`, hover de botones, etc.).
- Ajusta el tamaño de la tarjeta modificando `width`/`height` en `.profile-card`.
- Si quieres que el card quede fijo al hacer scroll, cambia `position: absolute;` por `position: fixed;` en `.profile-card`.

## Notas
- No se usa flex ni grid para centrar.
- Para centrado horizontal solamente, podrías usar `margin: 0 auto;` en `.profile-card`.

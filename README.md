# Fogón

Fogón es un sistema de diseño cálido y amable para productos de gastronomía: apps de locales, cupones, menús y reservas.

## Tono

- Hablá en español rioplatense, tuteo con voseo ("Probá", "Elegí", "Reservá"). Frases cortas y directas.
- Sin emojis decorativos. Un botón dice lo que hace: "Canjear cupón", "Reservar mesa".

## Color

- Fondo de pantalla en `surface-100`; tarjetas y paneles en `surface-200`. Texto principal en `ink`, secundario en `ink-muted`.
- `rojo` (vino) es el color de la acción principal: un solo botón `rojo` por pantalla, con texto `on-rojo`.
- `accent` (verde albahaca) para confirmaciones y etiquetas. Puede usarse como texto sobre `surface-100`.
- `honey` solo como relleno decorativo (premios, destacados); nunca para texto.
- Separadores y bordes en `line`. Usá siempre el token, nunca el hex.

## Tipografía

- Titulares en `display` y `title` (Times New Roman); secciones en `heading`.
- Todo lo demás en la fuente del sistema (`sans`): `body` para lectura, `body-sm` para descripciones, `label` para botones y etiquetas.

## Espaciado y formas

- Usá los pasos `space-1` a `space-4` (4, 8, 16, 24 px). Padding de tarjetas: `space-3`; entre bloques: `space-4`.
- Esquinas redondeadas y generosas: `as` en campos, `radius-md` en botones, `radius-lg` en tarjetas grandes, `radius-pill` en chips.
- Sin degradados; la sombra `p` solo en tarjetas elevadas: la jerarquía sale del color y del espacio.

## Iconografía

- Este sistema todavía no incluye logo ni íconos propios. Hasta que se agreguen, el nombre se escribe en `display` y los íconos se hacen con formas simples (círculos, píldoras).

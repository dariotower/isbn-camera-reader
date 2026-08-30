# Lector ISBN con cámara

Web móvil para leer el código de barras de libros y obtener su ISBN-13.

## Funciones
- Cámara trasera del teléfono.
- Lectura EAN-13 mediante ZXing.
- Solo acepta ISBN con prefijo 978 o 979.
- Valida el dígito de control ISBN-13.
- Lectura alternativa desde una foto.
- Historial local.
- Exportación CSV.
- Linterna cuando el navegador/dispositivo la expone.

## Cómo probarlo
La cámara del navegador requiere un contexto seguro:
- Publicalo mediante HTTPS (por ejemplo GitHub Pages, Netlify, Vercel, etc.), o
- ejecutalo en localhost.

No conviene abrir `index.html` directamente como `file://` para probar la cámara.

## Dependencia
Usa `@zxing/browser` 0.1.5 desde UNPKG.

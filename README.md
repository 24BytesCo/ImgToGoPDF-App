# Images-to-PDF Studio

Convierte, une y agrupa imágenes JPG y PNG en un solo PDF, directo en tu navegador. 100% local, gratis, sin publicidad y sin subir archivos. Nació para resolver mi propia necesidad y está abierto para cualquiera que lo necesite: https://24bytesco.github.io/images-to-PDF/

## Propósito
- Pasar imágenes a PDF sin instalar nada ni subirlas a servidores.
- Ofrecer una herramienta ilimitada, sin anuncios y lista para usar en cualquier navegador moderno.

## Características
- Arrastra y suelta, con orden alfabético o manual (drag & drop).
- Convierte, une y agrupa JPG/PNG en un único PDF (A4) en segundos.
- Procesamiento 100% cliente: tus archivos no salen de tu dispositivo.
- Marca de agua de marca fija en el PDF.
- Contadores públicos: visitas, PDFs creados y clicks al badge (sin cookies ni datos personales).
- Formulario de feedback/contacto (nombre, correo/número, mensaje) vía FormSubmit.

## Cómo usar
1. Abre `index.html` en tu navegador o visita https://24bytesco.github.io/images-to-PDF/.
2. Arrastra tus imágenes, ordénalas y pulsa “Convertir a PDF”.
3. (Opcional) Usa el formulario de feedback para dejar un mensaje. Configura tu correo en `index.html` (`data-endpoint`) o en `assets/js/app.js` (`FEEDBACK_ENDPOINT`) si haces tu propio fork.

## Estructura rápida
```
images-to-PDF/
├── index.html
├── assets/
│   ├── css/styles.css
│   └── js/app.js
└── imgs/ (marca de agua)
```

## Stack
- HTML5
- CSS3
- JavaScript (ES6)
- Librería: jsPDF (v2.5.1)

## Contribuir
- Fork + PR con tu mejora. Rama sugerida: `feature/tu-mejora`.
- Ideas: más formatos, mejoras de accesibilidad/SEO, UX, tests, nuevas opciones de salida.

## Licencia
MIT. Disfruta y compártelo. Sin publicidad, sin límites. 

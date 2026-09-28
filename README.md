# Tarjeta MR · Manuel Rivas

Tarjeta de presentación electrónica interactiva de la marca MR: diseño UX/UI, páginas web y contenido con IA.

## Archivos

| Archivo | Qué es |
| --- | --- |
| `index.html` | La tarjeta completa (portada con aurora líquida y la página que se abre al deslizar) |
| `qrcode.js` | Librería que genera el código QR (licencia MIT, Kazuhiko Arase) |
| `og-tarjeta.png` | Imagen de vista previa que aparece al enviar el enlace por WhatsApp |
| `favicon.svg` | Icono de la pestaña del navegador |
| `apple-touch-icon.png` | Icono cuando se guarda la tarjeta en la pantalla de inicio del iPhone |
| `logo-mr.png` | Logo original |
| `.nojekyll` | Indica a GitHub Pages que publique los archivos tal cual |

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `tarjeta`).
2. Sube **todos** los archivos de esta carpeta a la raíz del repositorio (incluido `.nojekyll`).
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. Espera 1 o 2 minutos. Tu tarjeta quedará en `https://TU-USUARIO.github.io/TU-REPOSITORIO/`.

## Activar la vista previa en WhatsApp

Abre `index.html` y, cerca del principio, cambia `TU-USUARIO` y `TU-REPOSITORIO` por los tuyos en estas dos líneas:

```html
<meta property="og:url" content="https://TU-USUARIO.github.io/TU-REPOSITORIO/">
<meta property="og:image" content="https://TU-USUARIO.github.io/TU-REPOSITORIO/og-tarjeta.png">
```

WhatsApp guarda en caché las vistas previas: si ya habías enviado el enlace antes del cambio, prueba enviándolo con `?v=2` al final.

## Datos que usa la tarjeta

- Instagram: @manue_rivas
- Web: https://manuel-rivas-ecosistema.pages.dev
- LinkedIn: https://www.linkedin.com/in/manuel-rivas-09913736a
- WhatsApp: +49 155 6163 8412
- Botón "Cómo llegar": ruta en Google Maps (la dirección no aparece escrita en la tarjeta)

El QR y el botón Compartir usan automáticamente la dirección donde esté publicada la tarjeta.

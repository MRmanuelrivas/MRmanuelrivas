# Tarjeta MR · Manuel Rivas

Tarjeta de presentación electrónica interactiva y bilingüe (español y alemán) de la marca MR: diseño UX/UI, páginas web y contenido con IA.

## Archivos

| Archivo | Qué es |
| --- | --- |
| `index.html` | La tarjeta completa (portada con aurora líquida y la página que se abre al deslizar) |
| `qrcode.js` | Librería que genera el código QR (licencia MIT, Kazuhiko Arase) |
| `og-tarjeta.png` | Imagen de vista previa que aparece al enviar el enlace por WhatsApp |
| `favicon.svg` | Icono de la pestaña del navegador |
| `apple-touch-icon.png` | Icono cuando se guarda la tarjeta en la pantalla de inicio del iPhone |
| `logo-mr.png` | Logo original |
| `manifest.webmanifest`, `sw.js`, `icon-*.png` | Permiten instalar la tarjeta como app y abrirla sin conexión |
| `.nojekyll` | Indica a GitHub Pages que publique los archivos tal cual |

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `tarjeta`).
2. Sube **todos** los archivos de esta carpeta a la raíz del repositorio (incluido `.nojekyll`).
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. Espera 1 o 2 minutos. Tu tarjeta quedará en `https://TU-USUARIO.github.io/TU-REPOSITORIO/`.

## Enlace

La tarjeta está publicada en https://mrmanuelrivas.github.io/MRmanuelrivas/ y la vista previa de WhatsApp ya apunta a esa dirección.

WhatsApp guarda en caché las vistas previas: si ya habías enviado el enlace antes del cambio, prueba enviándolo con `?v=2` al final.

## Datos que usa la tarjeta

- Instagram: @manue_rivas
- Web: https://manuel-rivas-ecosistema.pages.dev
- LinkedIn: https://www.linkedin.com/in/manuel-rivas-09913736a
- WhatsApp: +49 155 6163 8412
- Botón "Cómo llegar": ruta en Google Maps (la dirección no aparece escrita en la tarjeta)

El QR y el botón Compartir usan automáticamente la dirección donde esté publicada la tarjeta.

## Instalar como app

- iPhone: abre el enlace en Safari → Compartir → Añadir a pantalla de inicio.
- Android: abre el enlace en Chrome → menú ⋮ → Instalar aplicación.

Tras cada cambio en `index.html`, sube también `sw.js` cambiando la versión (`tarjeta-mr-v3`) por `v2`, `v3`, etc., para que los teléfonos con la app instalada descarguen la versión nueva.

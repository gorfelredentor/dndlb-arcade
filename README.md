# DNDLB Arcade

Catálogo de repuestos arcade, flipper y retro de Dofus (Néstor David Lucero Bernadac).

## Cómo publicarlo en GitHub Pages

1. Subí todo el contenido de esta carpeta (index.html, img/, video/) a la raíz de un repositorio.
2. En el repositorio, entrá a Settings → Pages.
3. En "Source" elegí la rama `main` y la carpeta `/ (root)`, y guardá.
4. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Cómo editar

- Cotización del dólar: al principio del script en index.html, cambiá `const DOLAR = 1550;` y `DOLAR_FECHA`.
- Productos: están en la lista `const P = [...]`. Cada producto tiene nombre, modelo, precio en dólares (`usd`), descripción, características, fotos (`imgs`, con el número de archivo de la carpeta img/) y la referencia de precio (`ref`).
- WhatsApp y email: `const WHATSAPP` y `const EMAIL` al principio del script.

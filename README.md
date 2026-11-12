# Cuchame

Sitio web de Cuchame: muebles para mascotas (perros y gatos), álamo barnizado.

Es una sola página (`index.html`) con todo adentro: estilos, imágenes y código. No necesita instalar nada.

## Antes de publicarlo
Abrí `index.html` y cambiá el número de WhatsApp (buscá `WHATSAPP_NUMBER`):

    var WHATSAPP_NUMBER = '549XXXXXXXXXX';

Formato: 549 + código de área sin 0 + número sin 15 (ej. `5492611234567`).

## Probarlo en el celu
Subilo a un servidor y abrí la dirección desde el celular.

## Subirlo a GitHub Pages (gratis)
1. Creá un repositorio nuevo en GitHub (por ejemplo `cuchame`).
2. Subí `index.html` y `README.md`.
3. En el repo: Settings > Pages > Source: "Deploy from a branch" > rama `main`, carpeta `/ (root)`.
4. En unos minutos queda en `https://TU-USUARIO.github.io/cuchame/`.

## En otro servidor
Copiá `index.html` a la carpeta pública del servidor (nginx, Apache, hosting compartido, etc.).

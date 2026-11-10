# Joguines Pardo · web estática

## Mientras sea propuesta (antes de que acepten)
- Se ve la barra "Proposta de disseny…" arriba y la web lleva `noindex` (Google no la indexa).
- Publícala en Netlify con un nombre neutro (p. ej. `pardo-proposta.netlify.app`) solo para enseñarla.

## Cuando acepten (pasar a web oficial)
1. `index.html`: borra la línea `<meta name="robots" content="noindex, nofollow">` y la `<div class="proposal">` (están marcadas con `PROPOSTA`).
2. `avis-legal.html` y `privacitat.html`: rellena lo resaltado en amarillo (titular, NIF, correo electrónico, fecha) y quita `class="todo"`.
3. Revisa con la tienda: categorías (y marcas reales), texto de "La botiga", horario y sobre todo la dirección y el teléfono: hay directorios que dan Av. de la Primavera, 11-13 y 936 92 41 27.
4. Añade fotos reales de la tienda, si las dan.
5. Conecta su dominio en Netlify > Domain management.

## Publicar
- Rápido: Netlify Drop (app.netlify.com/drop) y arrastra la carpeta o el zip descomprimido.
- Recomendado: repo privado en GitHub y "Import from Git" en Netlify (cada push publica).

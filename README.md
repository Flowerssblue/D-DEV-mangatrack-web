# mangatrack-web

Páginas estáticas que usa la app MangaTrack (publicar con GitHub Pages desde la rama `main`, raíz):

- `recuperar.html` — destino del enlace del correo de recuperar contraseña.
- `eliminar-cuenta.html` — cómo pedir el borrado de la cuenta y los datos.
- `confirmado.html` — a donde lleva el enlace del correo de confirmación al crear una cuenta.

URLs esperadas por la app:

- https://flowerssblue.github.io/mangatrack-web/recuperar.html
- https://flowerssblue.github.io/mangatrack-web/eliminar-cuenta.html
- https://flowerssblue.github.io/mangatrack-web/confirmado.html

`recuperar.html` y `confirmado.html` tienen que estar en Supabase > Authentication > URL Configuration > Redirect URLs.

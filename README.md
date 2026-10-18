# Eryon Launcher — sitio de descarga (tema verde)

Sitio estático en HTML/CSS/JavaScript para publicar con GitHub Pages. El botón consulta la API pública de GitHub Releases y obtiene el instalador `Eryon-Launcher-*-Setup.exe` de la última publicación.

## Publicación con GitHub Pages

1. Crea un repositorio público nuevo llamado `eryon-launcher-site` en la cuenta `EricCGO`.
2. Sube `index.html`, `favicon.svg` y `README.md` a la raíz de la rama `main`.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**.
6. Cuando termine el despliegue, la página estará en `https://ericcgo.github.io/eryon-launcher-site/`.

La publicación puede tardar unos minutos en aparecer. Cada vez que se publique una release nueva en `EricCGO/eryon-launcher-releases`, el sitio detectará automáticamente el nuevo instalador sin que tengas que editar la página.

## Actualizar el sitio

Edita los archivos y haz commit/push en la rama `main` del repositorio del sitio. No subas el instalador de más de 100 MB a este repositorio: los instaladores quedan en GitHub Releases.

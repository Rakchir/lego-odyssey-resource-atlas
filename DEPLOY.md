# Publicar Odyssey Resource Atlas

El sitio ya está preparado para GitHub Pages mediante `.github/workflows/pages.yml`.

## Primera publicación
1. Crea un repositorio público vacío en GitHub, por ejemplo `lego-odyssey-resource-atlas`.
2. Sube el contenido de esta carpeta a la rama `main`.
3. En GitHub abre **Settings → Pages → Build and deployment → Source → GitHub Actions**.

El workflow **Deploy Odyssey Atlas to GitHub Pages** publicará automáticamente el sitio. Después de esto, cada `git push` a `main` volverá a desplegar la versión nueva.

## URL esperada
Si el usuario de GitHub es `USUARIO` y el repositorio se llama `lego-odyssey-resource-atlas`, la URL normalmente será:

`https://USUARIO.github.io/lego-odyssey-resource-atlas/`

## Compartir materiales
Los enlaces con parámetros del sitio se pueden compartir, por ejemplo:

`https://USUARIO.github.io/lego-odyssey-resource-atlas/?material=dragon-opal`

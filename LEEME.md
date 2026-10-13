# Invitación · Laura 50

Dirección final: **https://laura50invitacion.github.io**

## Publicar
1. En GitHub, con el usuario **laura50invitacion**: **New repository**.
   - Repository name: **`laura50invitacion.github.io`** (exactamente así).
   - Visibilidad: **Public**.
   - Create repository.
2. En el repositorio: **Add file → Upload files**. Arrastrá **todo el contenido de esta carpeta**, incluida la carpeta `media`, con el `index.html` en la raíz. Después **Commit changes**.
3. **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save.
4. En 1 o 2 minutos queda online en https://laura50invitacion.github.io

## Qué hay en la carpeta
- `index.html`: la invitación. La vista previa de WhatsApp ya apunta a esta dirección.
- `media/`: fotos, flores, tragos, tipografías, ícono, imagen para compartir y la canción.
- `404.html`: si alguien escribe mal la dirección, lo lleva a la invitación.
- `robots.txt` + `noindex`: la invitación **no aparece en Google**. Solo la ve quien tenga el link.
- `.nojekyll`: hace que GitHub publique los archivos tal cual.

## Si querés que aparezca en Google
Borrá `robots.txt` y, en `index.html`, la etiqueta `<meta name="robots" content="noindex, nofollow">`.

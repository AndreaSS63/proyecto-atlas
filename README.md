
# Proyecto Atlas — Web Starter

Este paquete contiene una plantilla mínima para publicar tu web del juego en **GitHub Pages**.

## Contenido
- `index.html`: visor de documentos con brillo/contraste, notas persistentes y bloqueo por contraseña.
- `assets/images/`: imágenes del logo y de ejemplo (laboratorio, placeholder bloqueado).

## Cómo publicar en GitHub Pages (rápido)
1. Crea un repositorio: `tuusuario.github.io` (o cualquiera si es sitio de proyecto).
2. Sube estos archivos al repositorio (raíz).
3. En **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main` y carpeta `/ (root)`
4. Espera 1-2 minutos y abre la URL que te indica GitHub.
5. Para usar tu dominio, añade el **CNAME** con `www` → `tuusuario.github.io` desde tu DNS y configura **Custom domain**.

## Personalización
- Edita el array `DOCS` dentro de `index.html` para añadir nuevas pistas, cambiar contraseñas, etc.
- Sustituye `assets/images/laboratorio_acto1.png` por tu foto real del laboratorio.
- Cambia el logo en `assets/images/logo_proyecto_atlas.png` si lo deseas.

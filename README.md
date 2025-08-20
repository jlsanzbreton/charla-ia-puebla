# Charla IA - Puebla de Eca

Presentación interactiva: `presentacion-ia.html`.

Qué hice aquí:
- Presentación en HTML con modo claro/oscuro y navegación por diapositivas.
- Diapositiva final con QR para descargar la versión completa (PDF).

Siguientes pasos para publicar en GitHub Pages:

1) Crear el repositorio remoto en GitHub (vía web o CLI). Ejemplo con GitHub CLI:

```bash
# desde este directorio
gh repo create sanzb/charla-IA-puebla --public --source=. --remote=origin
# empujar branches
git push -u origin main
git push -u origin gh-pages
```

2) Activar Pages en el repositorio: elegir rama `gh-pages` (o `main` > carpeta `/docs`) en la configuración de GitHub Pages.

3) URL resultante: https://<tu-usuario>.github.io/charla-IA-puebla/

Si quieres, yo puedo preparar la rama `gh-pages` lista para publicar y darte los comandos exactos para crear el repo remoto y enviar los cambios.

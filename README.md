# Mi rutina de gimnasio (PWA)

App de rutina de gimnasio para usar en el celular: rutinas por día, bloques (superseries), calendario semanal y mensual, series con temporizador de descanso, historial y progreso por ejercicio.

Es un solo `index.html`, sin backend. Los datos se guardan en el teléfono (localStorage). Usá Exportar/Importar en la pestaña Rutinas para hacer copias de seguridad.

## Publicar en GitHub Pages
1. Crear un repositorio público nuevo.
2. Subir todos los archivos de esta carpeta (no el zip).
3. Settings → Pages → Deploy from a branch → `main` / `(root)`.

## Instalar en el teléfono
- Android (Chrome): menú ⋮ → Instalar app.
- iPhone (Safari): Compartir → Agregar a inicio.

## Actualizar la app
Cada vez que cambies `index.html`, cambiá el número de versión de `sw.js` (por ejemplo `rutina-v7` → `rutina-v8`) para que el teléfono descargue la versión nueva.

# Occamy 🚀🐉

Tu nave para organizar tareas, proyectos y recuerdos. Funciona en el celular como una app instalada.

## Qué hay en esta carpeta

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app completa |
| `manifest.webmanifest` | Nombre, colores e ícono para instalarla como app |
| `sw.js` | Hace que funcione sin internet |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Íconos (tu imagen del dragón) |
| `.nojekyll` | Le dice a GitHub que no procese los archivos |

## Subirla a GitHub (gratis)

1. Entrá a **github.com** y creá una cuenta (o iniciá sesión).
2. Tocá **+** arriba a la derecha → **New repository**.
3. Nombre: `occamy`. Dejalo en **Public**. Tocá **Create repository**.
4. En la página del repositorio, tocá **uploading an existing file**.
5. Arrastrá **todos los archivos de esta carpeta** (descomprimí el .zip primero). Ojo con `.nojekyll`: es un archivo oculto; si no lo ves, no pasa nada, la app funciona igual.
6. Abajo, tocá **Commit changes**.

## Publicarla (para tener un link)

1. En el repositorio: **Settings** → **Pages** (menú de la izquierda).
2. En **Build and deployment** → **Source**: elegí **Deploy from a branch**.
3. En **Branch**: elegí `main` y la carpeta `/ (root)`. Tocá **Save**.
4. Esperá 1 o 2 minutos y recargá. Arriba va a aparecer tu link:
   `https://TU-USUARIO.github.io/occamy/`

## Instalarla en el celular

- **Android (Chrome):** abrí el link → menú ⋮ → **Instalar app** (o **Añadir a pantalla de inicio**).
- **iPhone (Safari):** abrí el link → botón **Compartir** → **Añadir a pantalla de inicio**.

Se instala con tu ícono del dragón y se abre a pantalla completa, sin barra del navegador.

## Cosas que conviene saber

- **Tus datos viven en el celular.** Proyectos, misiones y bitácora se guardan en el navegador de ese dispositivo. Si borrás los datos del navegador o desinstalás la app, se pierden, y no se pasan solos a otro celular.
- **El repositorio público lo puede ver cualquiera**, incluidos los archivos y las imágenes. Tus notas **no** están ahí (están solo en tu celular), pero la imagen del ícono y la cabina sí.
- **Para actualizar la app:** subí el `index.html` nuevo al repositorio (reemplaza al anterior) y cambiá `occamy-v1` por `occamy-v2` dentro de `sw.js`, así el celular baja la versión nueva.
- **Sonido:** el botón de arriba a la derecha cambia entre *Suave*, *Muy suave* y *Silencio*. Los sonidos son graves y de volumen bajo.

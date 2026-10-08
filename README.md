# Angol Flies Araucanía

Página web de Angol Flies, moscas para pesca atadas a mano en Angol.

## Publicar la página (una sola vez)

1. Crea una cuenta en github.com si no tienes.
2. Crea un repositorio nuevo, por ejemplo `angol-flies`, marcado como **Public**.
3. Sube todos los archivos de esta carpeta (botón **Add file → Upload files**), manteniendo las carpetas `data` e `img`.
4. Ve a **Settings → Pages**, en "Source" elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
5. En 1 a 2 minutos la página queda en `https://TU-USUARIO.github.io/angol-flies/`.

## Crear el token para administrar (una sola vez)

1. En GitHub: foto de perfil → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. En "Repository access" elige **Only select repositories** y marca `angol-flies`.
3. En "Permissions → Repository permissions", deja **Contents** en **Read and write**.
4. Genera el token y cópialo (empieza con `github_pat_`). Guárdalo en un lugar seguro; GitHub no lo vuelve a mostrar.

## Agregar o cambiar moscas

1. Entra a `https://TU-USUARIO.github.io/angol-flies/admin.html`.
2. La primera vez pega el token y toca **Conectar**. Queda guardado en ese navegador.
3. Para agregar: nombre, tipo, precio, tallas y foto, y toca **Guardar y publicar**.
4. Para cambiar precio, foto o marcar como agotada: toca **Editar** en la lista.
5. La página pública se actualiza sola en 1 a 2 minutos.

Si dejas el precio vacío, la mosca aparece como "Consultar precio".

## Archivos

- `index.html`: la página pública.
- `admin.html`: el panel para administrar (no aparece enlazado en la página).
- `data/moscas.json`: el catálogo con nombres, tipos, precios y fotos.
- `img/`: fotos y logo.

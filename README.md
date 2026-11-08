# Patolmés (PWA)

Carpeta lista para subir a GitHub Pages:

```
index.html
manifest.webmanifest
sw.js
icons/   (icono calendario + pato, en varios tamaños)
```

## Subirla a GitHub
1. Crea un repositorio nuevo (p. ej. `patolmes`) y sube **el contenido de esta carpeta** (no la carpeta en sí).
2. Settings → Pages → Source: `Deploy from a branch` → `main` / `(root)`.
3. En 1-2 minutos estará en `https://TU-USUARIO.github.io/patolmes/`.
4. Ábrela desde esa dirección en el móvil (no desde el archivo suelto) → menú ⋮ → *Instalar aplicación*.

## Copia en la nube (Gist)
1. GitHub → Settings → Developer settings → Personal access tokens → **Tokens (classic)** → nuevo token con **solo el permiso `gist`**.
2. En la app: Más → Copia en la nube → pega el token y deja el ID vacío → *Conectar y sincronizar*. Se crea un Gist privado con `patolmes.json`.
3. Para otro dispositivo: mismo token + el **ID del Gist** que aparece en esa misma pantalla.
4. El token se guarda solo en el navegador de cada dispositivo; nunca va al repositorio ni al Gist.

## Actualizar la app
Sube el nuevo `index.html` al repositorio. La app pide siempre la versión más reciente al abrirse con conexión, así que no hace falta tocar nada más.
Sube `VER` en `sw.js` solo si cambias la lista de archivos o los iconos.

## Traer los datos de la versión anterior
En la versión vieja: Más → Exportar copia (JSON). En la nueva: Más → Importar copia (JSON). Se combinan sin borrar nada.

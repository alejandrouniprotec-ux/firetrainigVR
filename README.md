[README.md](https://github.com/user-attachments/files/28035461/README.md)
# Centro De Soporte Fire Training

Borrador estático del e-learning / centro de soporte para el simulador Fire Training de Uniprotec Digital.

## Archivos

- `index.html`: página completa con estilos, interacción, módulos y chat FAQ local.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube el archivo `index.html` a la raíz del repositorio.
3. Entra a **Settings > Pages**.
4. En **Build and deployment**, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda los cambios.
6. GitHub generará una URL pública de GitHub Pages.

## Cómo insertar videos

Busca cada bloque que dice:

`Reemplaza este bloque por el iframe o embed del video.`

Y sustituye el contenido de `.video-placeholder` por el iframe del video.

## Chat integrado

El chat incluido es una demo local tipo FAQ. No usa IA real ni backend.

Para conectarlo a IA real, se recomienda usar backend propio, función serverless, Make, Zapier u otro middleware seguro.

No coloques llaves API directamente en `index.html`.

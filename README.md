# Archivo del Carnaval del Campo de Gibraltar

Web estática lista para subir a GitHub Pages, Netlify o Vercel.

## Cómo editar los datos

Edita estos archivos:

- `data/agrupaciones.json` → fichas de agrupaciones.
- `data/fotos.json` → fototeca, carteles y documentos visuales.
- `data/municipios.json` → textos de cada municipio.

## Cómo subir imágenes

Opción sencilla:
1. Mete las fotos dentro de la carpeta `assets`.
2. En `data/fotos.json`, en el campo `imagen`, escribe la ruta.

Ejemplo:

```json
"imagen": "assets/foto-1998.jpg"
```

También puedes pegar enlaces externos de imágenes si están publicados online.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todos estos archivos.
3. Ve a `Settings` → `Pages`.
4. En `Source`, selecciona `Deploy from a branch`.
5. Elige la rama `main` y carpeta `/root`.
6. Guarda.

Tu web aparecerá en una dirección tipo:

`https://tuusuario.github.io/nombre-del-repositorio/`

## Colores usados

- Azul: `#3986ff`
- Rosa: `#f91669`
- Amarillo: `#fcbd0d`
- Verde: `#48bb75`
- Naranja: `#fb5608`
- Blanco

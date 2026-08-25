# 1881 · La moneda antes del fuego

Exposición virtual en nueve salas sobre dos monedas de dos y medio centavos de 1881.

## Estructura

```
index.html                 la exposición completa
medios/                    fotografías y reconstrucciones en video
portada-og.jpg             imagen de vista previa para enlaces
1881-un-archivo.html       versión de respaldo, todo embebido en un solo archivo
```

## Publicar en GitHub Pages

1. Crear un repositorio nuevo (público) en github.com — por ejemplo `1881-moneda`.
2. En la pantalla del repositorio vacío: **uploading an existing file** → arrastrar
   `index.html`, `portada-og.jpg`, `README.md` y la carpeta `medios/` completa.
3. **Commit changes**.
4. **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
5. En uno o dos minutos la exposición queda en
   `https://USUARIO.github.io/1881-moneda/`

## Nota sobre el `og:image`

Para que la vista previa aparezca al compartir el enlace en WhatsApp o redes,
reemplazar en `index.html` las dos apariciones de `portada-og.jpg` por la URL
absoluta una vez publicado:
`https://USUARIO.github.io/1881-moneda/portada-og.jpg`

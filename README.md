# hi-media

Puente de imágenes para programar publicaciones por API.

Las plataformas de scheduling necesitan una URL pública para ingerir una imagen.
Este repo sirve esas URLs de forma directa y estable:

```
https://raw.githubusercontent.com/Impulsa-ia/hi-media/main/<ruta>
```

Solo contiene piezas de marca destinadas a publicarse en redes. Nada privado.

## Contenido

- `frases/` — piezas sueltas 1080x1350, una imagen por post
- `carruseles/<tema>/` — 10 láminas 1080x1350

## Cómo subir

Desde el vault, con `gh` autenticado:

```bash
./"⚙️ Meta/scripts/hi-media-subir.sh" <archivo>.png frases
```

Verifica el `content-type` y solo devuelve la URL si GitHub la sirve como imagen.
El procedimiento completo está en `⚙️ Meta/SOPs/SOP - Frase con Marca.md`.

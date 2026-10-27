# Mi proyecto web: Clean Teeth

- **Nombre:** Alejandro Sánchez Nogales
- **Usuario de GitHub:** alejandro-sanchez0017
- **Tema elegido:** Clean Teeth, una marca de pasta de dientes de lujo

## ¿Por qué he elegido este tema?

Me gustan mucho los productos de cuidado personal y por eso quiero tener
siempre los dientes limpios. Por eso he elegido una marca de pasta
de dientes de lujo con distintas variedades para cada necesidad.

## Palabra del día

contexto

## Qué he hecho en esta entrega

He creado la página `index.html` con la presentación de Clean Teeth,
una imagen del producto, una lista de tres pastas y dos enlaces.
También he creado `datos.xml`, un catálogo con las tres pastas, cada
una con su id, nombre, sabor, precio y volumen. He comprobado que el
XML no tiene errores y que la página se ve bien con Live Server.

## Mapa del sitio

| Fichero | title | Qué contiene |
| :--- | :--- | :--- |
| `index.html` | Inicio \| Clean Teeth | Portada: presentación, quiénes somos, variedades, opinión, ficha resumen y enlaces. |
| `catalogo.html` | Catálogo \| Clean Teeth | Todos los elementos del fichero `datos.xml` con su id, nombre, sabor, precio y cantidad. |
| `cuidados.html` | Cuidados \| Clean Teeth | Recomendaciones de cepillado diario, beneficios de cada gama y cita de especialista. |
| `contacto.html` | Contacto \| Clean Teeth | Información de atención al cliente, puntos de venta y horario en columnas. |

## UD3 · Estructura HTML

Cosas que le faltan a mi `index.html`:
- Completar el `<head>` con el formato de título `Inicio | Clean Teeth` y los metadatos `description`, `keywords` y `author`.
- Agrupar las secciones del `<body>` dentro de bloques `<div>` comentados y añadir subtítulos `<h3>` sin saltos de jerarquía.
- Añadir una separación con `<hr>`, una cita con `<blockquote>`, una ficha en columnas con `<pre>` y entidades HTML como `&copy;` y `&euro;`.

### Validación W3C

| Página | Errores en el validador | Cómo los corregí |
| :--- | :--- | :--- |
| `index.html` | 0 errores | No tuvo errores; revisé que todas las etiquetas y entidades estuvieran bien cerradas. |
| `catalogo.html` | 0 errores | No tuvo errores al seguir la misma estructura que la portada. |
| `cuidados.html` | 0 errores | No tuvo errores en el validador del W3C. |
| `contacto.html` | 0 errores | No tuvo errores; comprobé el cierre correcto del bloque `pre`. |

### Qué he hecho en esta unidad

En esta unidad he completado la cabecera de `index.html` con todos los metadatos y he organizado el cuerpo en bloques `div` comentados respetando la estructura de títulos `h1`, `h2` y `h3`. También he añadido una cita con `blockquote`, una tabla con `pre`, entidades HTML y he creado el mapa del sitio junto con las páginas `catalogo.html` (con los datos de `datos.xml`), `cuidados.html` y `contacto.html`.

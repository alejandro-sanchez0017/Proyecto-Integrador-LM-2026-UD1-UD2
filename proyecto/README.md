# Mi proyecto web: Clean Teeth

- **Nombre:** Alejandro Sánchez Nogales
- **Usuario de GitHub:** alejandro-sanchez0017
- **Tema elegido:** Clean Teeth, una marca de pasta de dientes de lujo

## ¿Por qué he elegido este tema?

Me gustan mucho los productos de cuidado personal y por eso quiero tener
siempre los dientes limpios. Por eso he elegido una marca de pasta
de dientes de lujo con distintas variedades para cada necesidad.

## UD5 · Tablas y formularios

En la página `catalogo.html` voy a poner una tabla comparativa con las pastas de dientes de Clean Teeth, su gama, sabor, formato y precio. El formulario de `contacto.html` servirá para que los clientes puedan hacer consultas, pedir muestras o reservar packs de productos.

## Palabra del día

día 

Fecha de actualización de la palabra del día: 03/11/2026

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


### Por qué uso post y no get

Uso `method="post"` en el formulario porque así los datos personales del cliente y su código VIP viajan ocultos en el cuerpo de la petición y no quedan expuestos en la URL del navegador.

### Prueba temporal con get

Al cambiar el formulario a `method="get"` y pulsar en Enviar, la URL que apareció en el navegador fue:
`contacto.html?nombre=Alejandro+Sanchez&correo=alejandro%40correo.com&tel=612345678&clave=123456&pasta=p01&extras=muestra&departamento=atencion&msg=Hola+quiero+pedir+una+muestra+de+Fresh+Mint`

## UD5 · Tablas y formularios

En la página `catalogo.html` voy a poner una tabla comparativa con las pastas de dientes de Clean Teeth, su gama, sabor, formato y precio. El formulario de `contacto.html` servirá para que los clientes puedan hacer consultas, pedir muestras o reservar packs de productos.

### Qué he hecho en esta unidad

En esta unidad he añadido una tabla completa en `catalogo.html` usando `caption`, `colgroup`, `thead`, `tbody` y `tfoot`, además de unir celdas con `rowspan` y `colspan`. También he completado `contacto.html` con un formulario dividido en dos bloques `fieldset` que incluye los ocho tipos de controles requeridos y sus atributos de validación. Por último, he enlazado `contacto.html` desde `index.html` y he verificado en el validador del W3C que todas las páginas tienen 0 errores.

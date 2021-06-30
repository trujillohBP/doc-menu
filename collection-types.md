# Colecciones

## Acceso_rapido_barra

Modelo para navegación rápida detro o fuera del portal.

### Vista Acceso_rapido_barra

![Acceso_rapido_barra](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/barra_acceso_rapido.png)

### Interfaz registro Acceso_rapido_barra

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Identificador | string | Identificador único de cada registro, sirve para identificarlo y asociarlo con otros modelos |
| Descripcion | string | Texto mostrado junto al botón en la interfaz|
| Accion | [Botón navegacion](components.md#navegacion) | Botón para navegación |

![r-a](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/registro_barra_acceso_rapido.png)

---
---

## Acceso_rapido_bloque

Modelo para navegación rápida detro o fuera del portal, compuesto por un título un párrafo y un botón.

### Vista Acceso_rapido_bloque

![Acceso_rapido_bloque](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/bloque_acceso_rapido.png)

### Interfaz registro Acceso_rapido_barra

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Identificador | string | Identificador único de cada registro, sirve para identificarlo y asociarlo con otros modelos |
| Titulo | string | Texto mostrado como título del modelo |
| Descripcion | string | Texto parrafo del modelo |
| Accion | [Botón navegacion](components.md#navegacion) | Botón para navegación |

![Acceso_rapido_bloque](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/acceso_rapido_bloque_interfaz.png)

---
---

## Api_categoria

Este modelo se utiliza para registrar las distintas categorias a las que puede pertenecer un Api. La principal funcionalidad de este componente es ayudar a la búsqueda y organización de Apis. Este modelo no cuenta con un componente independiente en la interfaz, el listado de Api_categorias aparece como parte de la interfaz del catálogo para permitir filtrar el listado.

### Vista Api_categoria

![Api_categoria](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/api_categorias.png)

### Interfaz registro Api_categoria

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Identificador | string | Identificador único de cada registro, sirve para identificarlo y asociarlo con otros modelos |
| Descripcion | string | Texto en donde se ingresará eñ nombre de la categoría que se mostrará en interfaz |

![Api_categoria](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/api_categoria_interfaz.png)

---
---

## Api

Este modelo se utiliza para registrar toda la información asociada a una Api, para que puede ser vista por los usuarios de forma detallada en cada una de las paginas de detalle o como un breve resumen ya sea en el home, el catálogo o asociada a otras Apis.

### Vista Api detallada

![Api](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/api_detail.png)

### Vista Api resumen

![Api](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/api_resumen.png)

### Interfaz registro Api

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Identificador | string | Identificador único de cada registro, sirve para identificarlo y asociarlo con otros modelos |
| Descripcion | [Cabecera_icono](components.md#cabecera_icono) | Información general del Api |
| Detalles | [Seccion_informativa](components.md#seccion_informativa) | Listado de secciones informativas en donde se muestran los detalles específcos del api |
| Detalle_estatico | [NN](components.md#seccion_informativa) | Componente que muestra información adicional |
| Catalogo | [Catalogo](components.md#catalogo) | Listado de apis relacionadas |
| Categoria | [Api_categoria](collection-types.md#api_categoria) | Listado de categorias a las que pertenece el Api |
| Acceso_rapido | [Acceso_rapido_barra](collection-types.md#acceso_rapido_barra) | Componente para navegación rapida desde página de detalle de Api |
| Acceso_rapido_bloque | [Acceso_rapido_bloque](collection-types.md#acceso_rapido_bloque) | Componente para navegación rapida desde página de detalle de Api |

![Api](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/api_interfaz_creacion.png)

---
---

## Guia

Este modelo se utiliza para registrar información de guías que cuentan con pasos a seguir por los usuarios.

### Vista Guia

![Guia](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/guia.png)

### Interfaz registro Guia

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Identificador | string | Identificador único de cada registro, sirve para identificarlo y asociarlo con otros modelos |
| Cabecera | [Cabecera_simple](components.md#cabecera_simple) | Cabecera de la guía |
| Pasos | [Contenido_icono_lista](components.md#contenido_icono_lista) | Contenido de la guía |
| Acceso_rapido | [Acceso_rapido_barra](collection-types.md#acceso_rapido_barra) | Componente para navegación rapida desde página de detalle de Api |

![Guia](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/guia_crear.png)

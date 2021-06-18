# Modelos únicos

## Faq

Modelo para crear la sección de **Preguntas frecuentes**. Permite crear una lista de preguntas precedida de un título.

### Vista Faq

![faq](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/FAQ.png)

### Interfaz registro Faq

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | string | Titulo mostrado sobre la sección de preguntas |
| Preguntas | [Titulo_parrafo_multiple](components.md#titulo_parrafo_multiple) | Listado de preguntas |
| Informacion_adicional | [Parrafo_enlace](components.md#parrafo_enlace) | Parrafo mostrado al final de la seccón de preguntas |


![faq_crear](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/faq_crear.png)

---
---

## Home

Modelo de la página principal del portal. Contiene toda la información de la pantalla principal a excepción de la sección de preguntas frecuentes y trabaja con nosotros.

### Vista Home

![home](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/home.png)

### Interfaz registro Home

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Inicio | [Infografia_acciones](components.md#infografia_acciones) | Cabecera principal del home |
| Informacion | [Seccion_informativa](components.md#seccion_informativa) | Contenido informativo del home |
| Catalogo | [Catalogo](components.md#catalogo) | Listado de Apis mostrado en home |
| Paso_a_pasa | [Seccion_navegacion](components.md#seccion_navegacion) | Sección de navegación |
| Acceso_rapido | [Acceso_rapido_barra](/collection-types.md#acceso_rapido_barra) | Acceso rápido |

![home_create](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/home_crear.png)


---
---

## Trabaja_con_nosotros

Datos de empresas que están usando productos de banco

### Vista Trabaja_con_nosotros

![work](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/trabaja_nosotros.png)

### Interfaz registro Trabaja_con_nosotros

| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | string | Título del componente |
| Descripcion | string | Descripción del componente |
| Accion | [Botón navegacion](components.md#navegacion) | Navegación |
| Logos | Imagen | Listado de imágens mostradas en interfaz |

![work](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/work_create.png)
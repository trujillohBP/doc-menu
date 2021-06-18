# Componentes
## Bloques
### Accion_simple
Bloque para navegación rápida que cuenta con un título y breve descripción
#### Vista
![accion-simple](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/acceso_rapido_bloque_vista.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Título del bloque  |
| Descripcion |  String | Descripción del bloque |
| Accion | [Botón navegacion](#navegacion) | Acción navegación rápida |

![accion-simple-reg](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/acceso_rapido_bloque.png)

---

### Cabecera_icono
#### Vista
![c_i_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/cabecera_icono_1.png)
![c_i_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/cabecera_icono_2.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Nombre del Api |
| Descripción | String | Descripción del Api |
| Descripcion_corta | String | Descripción resumida del Api |
| Imagen | Imagen | Archivo multimedia para mostrar en interfaz |
| Icono | [Icono](values.md#icono) | Icono mostrado en lugar de la imagen |
| Usar_icono | Booleano | Propiedad para determinar si usar un ícono o una imagen en la interfaz |

![c_i_crear](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/cabecera_icono_crear.png)

---
### Cabecera_simple
#### Vista
![c_s_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/cabecera_simple_crear.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Título de cabecera |
| Descripcion | String | Descripción de cabecera |

![c_s_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/cabecera_simple.png)

---
### Capsula_informacion
#### Vista
![c_i_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/capsula_informacion_crear.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Título de la capsula informativa |
| Descripcion | String | Descripción de la capsula informativa |
| Icono | [Icono](values.md#icono) | Icono mostrado en interfaz |
| Imagen | Imagen | Archivo multimedia para mostrar en interfaz |
| Usar_imagen | Booleano | Propiedad para determinar si usar un ícono o una imagen en la interfaz |


![c_i_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/capsula_informacion.png)

---
### Contenido_icono_lista
#### Vista
![c_i_l_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/contenido_icono_lista_crear.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Orden | Número | Valor para ordenar los registros en caso que se creen varios |
| Etiqueta | String | Texto corto para identificar el registro |
| Titulo | String | Título del registro |
| Icono | [Icono](values.md#icono) | Icono mostrado en interfaz |
| Descripcion | String | Parrafo mostrado en la interfaz |
| Lista | [Item_lista](#item_lista) | Lista de contenido |

![c_i_l_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/contenido_icono_lista.png)

---
### Infografia_acciones
#### Vista
![i_a_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/infografia_accion.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Título del componente |
| Descripcion | String | Descripción del componente |
| Accion_principal | [Botón navegacion](#navegacion) | Acción principal del componente |
| Accion_secundaria | [Botón navegacion](#navegacion) | Acción secundaria del componente |
| Imagen | Imagen | Imagen mostrada en interfaz |

![i_a_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/infografia_accion_crear.png)

---

### Seccion_informativa
#### Vista
![s_i_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/seccion_informativa.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Título del componente |
| Descripcion | String | Párrafo descriptivo del componente |
| Centrar_capsulas | Boolean | Propiedad para determinar si los textos de las cápsulas informativas están centrados o alineados a la izquierda |
| Capsulas | [Capsula_informacion](#capsula_informacion) | Listado de cápsulas informativas |

![s_i_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/seccion_informativa_crear.png)

---

### Seccion_navegacion
#### Vista
![s_n_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/seccion_navegacion.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Titulo del componente |
| Descripcion | String | Descripción del componente |
| Items_navegacion | [Lista_navegacion_item](#lista_navegacion_item) | Items de lista navegación |
| Usar_icono | Booleano | Propiedad para determinar si en interfaz se muestra ícono o imagen |
| Icono | [Icono](values.md#icono) | Icono mostrado en interfaz |
| Imagen | Imagen | Imagen mostrada en interfaz |
| Adicional | [Parrafo_enlace](#parrafo_enlace) | Parrafo con información adicional |

![s_n_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/seccion_navegacion_crear.png)

---

### Titulo_parrafo_multiple
#### Vista
![t_p_1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/titulo_parrafos.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Título del componente |
| Parrafos | String | Parrafos mostrados a continuación del título. Para que los párrafos se muestren en interfaz de forma separada deben ingresarse separados por un Enter |

![t_p_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/titulo_parrafos_crear.png)

---

### Catalogo
#### Vista
![c](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/catalogo.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Titulo | String | Título del componente |
| Descripcion | String | Descripción del componente |
| Navegacion | [Botón navegacion](#navegacion) | Acción navegación rápida |
| Apis | [Api](collection-types.md#api) | Listado de apis que se muestran el el catálogo |

![c_2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/catalogo_crear.png)

---
---

## Botones

### Navegacion
Botón para navegación a un link. Puede ser dentro del propio portal o un link externo.

#### Vista
![nav-bot](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/botones_nav.png)

#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Texto | String | Texto mostrado en interfaz |
| Url | String | Link para navegación |
| Color | [Color navegacion](values.md#color_navegacion) | Opción de color del botón |


![baton_navegacion](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/boton_navegacion.png)

---
---
## Complementarios
Componentes usados como elementos de otro modelos mas grandes

### Item_lista
Texto mostrado con un bullet usado para representar listas de textos
#### Vista
![i-l](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/item_lista.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Contenido | String | Texto mostrado en interfaz |

![i-l-2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/item_lista_crear.png)

---

### Lista_navegacion_item
#### Vista
![l-nav](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/lista_nav_item_crear.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Contenido | String | Texto mostrado en interfaz |
| Url | String | Link para navegación |

![l-nav-2](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/lista_nav_item.png)


---
---
## Parrafos
### Parrafo_enlace
Este componente permite crear un párrafo que contiene enlaces en su texto.
Todo texto ingresado en la interfaz de creación será representado en el portal como texto normal. Para que una sección del texto sea un link debe encerrarce entre [], de este modo en interfaz aparecerá como link. El valor mostrado como link debe ir seguido con el link de navegación dentro de ().

Ejemplo
El siguiente ejemplo es el mostrado en la imagen siguiente

    - `Conoce cómo funciona y elige las APIs con las que harás crecer tu negocio en [nuestro catálogo](https://google.com)`


#### Vista
![p](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/parrafo_links_crear.png)
#### Interfaz registro
| Propiedad | Tipo | Descripción |
| ------ | ------ | ------ |
| Contenido | Texto enriquecido | Contenido del párrafo mostrado en interfaz |

![p-1](https://sadesarrolloportalapis.blob.core.windows.net/strapi-manual/parrafo_links.png)
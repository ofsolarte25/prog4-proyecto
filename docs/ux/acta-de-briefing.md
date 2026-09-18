Proyecto: Bitacora espacial (Archivo Nasa)
Grupo consultor: Grupo 8 Integrantes:Omar Fernando Solarte Palacio - Daniel Alejandro Muñoz Giraldo
Grupo cliente: Grupo 3 Entrevistado: Henry Valencia Lopez
Fecha:16/09/2026 Duración de la entrevista: 35 minutos

EL PROBLEMA

la coleccion met tiene una gran cantidad de obras de arte y no se sabe como crear un recorrido.

Costo del problema (tiempo, dinero, frustración):

Armar el recorrido toma bastante tiempo y verificacion manual.

1.4 Frases textuales del cliente

1. “fue necesario revisar varias obras hasta encontrar las que realmente me interesaban.”
2. “Espero encontrar las obras escribiendo una palabra en un buscador”


EL USUARIO

| Campo | Usuario principal | Usuario secundario |
| Nombre y edad | estudiante  | visitante |
| Ocupación o rol | academico | aficionado |
| Contexto de uso | escolar | curiosidad |
| Dispositivo | computador | movil  |
| Nivel tecnológico | basico | nulo |
| Objetivo principal | investigacion | pasatiempo |
| Principal frustración | busqueda manual | busqueda manual |


LA TAREA PRINCIPAL

Si solo pudiera hacer una cosa, sería:

Buscar resultados en base a una palabra ingresada.

Pasos que sigue para lograrla:

1. ingresar a la pagina.
2. escribir una palabra en el buscador.
3. obtener un listado de obras.
4. seleccionar cada obra para añadirla al recorrido.

Información que necesita para decidir:

la imagen de la obra, el titulo, el autor, la cultura a la que pertenece, el periodo y el departamento del museo.


Información que sobra:

la historia de como se encontro, cuando, y mas detalles que se pueden estudiar despues de armar el recorrido.

CONTENIDO Y DATOS

Datos que debe mostrar cada elemento del listado**

| Dato | ¿Imprescindible o adicional? | ¿Lo entrega la API? |
|Titulo  | imprescindible | si |
|autor  | imprescindible | si |
|cultura  | imprescindible | si |
|periodo  | imprescindible | si |
|departamente | imprescindible | si |
|imagen| imprescindible | requiere varias peticiones|

Criterios de búsqueda y filtrado acordados:

Uso de palabras clave para encontrar resultados aproximados.

Orden por defecto del listado:

-autor
-zona
-cultura

Qué hacer cuando un dato viene vacío:

Cuando hay datos vacios es necesario indicar que no se obtuvieron resultados e instar a modificar la busqueda.

ALCANCE

5.1 Funcionalidades acordadas, en orden de prioridad:

| # | Funcionalidad | Prioridad (alta, media, baja) | ¿Entra en la versión 1? |

| 1 | login | alta | si |
| 2 | busqueda |  alta| si |
| 3 | filtros | media | si |
| 4 | seleccion de articulos| media | si |
| 5 | recorrido interactivo | baja | si |


Fuera de alcance, acordado explícitamente:

- Almacenar la informacion de las obras en una base de datos.
- No se realizan ventas de ningun tipo.
- No se guardan los recorridos de forma local.
- No se incluye una pasarela de pagos.

Referencias que le gustan al cliente y por qué:

No se menciono.

Lo que quiere evitar:

interfaces rotas.
informacion que no corresponde.
Seleccion completamente manual.

Tono y estilo visual esperado (marcar los que apliquen)


[ ] Sobrio        [ ] Cercano       [ ] Juvenil       [X] Institucional
[X] Minimalista   [ ] Colorido      [ ] Editorial     [ ] Técnico



CRITERIOS DE ÉXITO

Cómo sabremos que funcionó:

Se comprueba que la aplicacion funciona al tener un recorrido que contenga las obras seleccionadas tras la busqueda inicial.

7.2 Indicador medible:

- porcentaje de busquedas que muestran resultados correctamente.
- numero de recorridos creados correctamente.
- porcentaje de intentos de agregar una obra a la lista.

7.3 Qué sería un fracaso:

Que el recorrido que se muestre al final del proceso no contenga las obras seleccionadas por el usuario.

Que durante la busqueda se muestren campos vacios o que la interfaz se distorsione cuando suceda esto.

CONSECUENCIAS PARA EL DISEÑO

| Lo que dijo el cliente | Decisión de diseño que tomo | Pantalla o componente |

| quiero que el usuario pueda encontrar obras facilmente | agregar un buscador visible en la pantalla principal  | buscador de texto |
| quiero que se pueda ver la informacion de cada obra  | se diseño una tarjeta con imagen con los datos principales de la obra | detalles de la obra |
| quiero que el usuario pueda seleccionar su recorrido | boton para añadir/eliminar obras del recorrido  | boton agregar/eliminar |
| quiero que sea facil de navegar entre las obras y los recorridos | se agregan botones para regresar, modificar, eliminar y acceder al recorrido | barra de navegacion - menu  |


Los abajo firmantes acuerdan que el proyecto Omar Fernando Solarte Palacio - Daniel Alejandro Muñoz Giraldo
tiene el siguiente alcance para su primera versión:

Se construirá:
1. un buscador.
2. boton de filtros.
3. boton de agregar obras.
4. lista de recorridos.
5. apartado de informacion de las obras.

No se construirá:

1. una base de datos de obras.
2. una pasarela de pagos.
3. un carrito de compras.



El usuario objetivo es: academico y casual.

El criterio de éxito es: Un recorrido de imagenes de obras seleccionadas por el cliente 

Cualquier cambio de alcance posterior a esta acta requiere acuerdo escrito de ambas partes.

Consultor: Daniel Alejandro Muñoz Giraldo - Omar Fernando Solarte Palacio  Cliente: Henry Valencia Lopez

Fecha: 16/09/2026
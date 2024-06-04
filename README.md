# Integradora-Practica02-3b

En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de Versiones, Documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la asignatura de Integradora I

## Comandos Básicos para la Documentación, utilizando el estándar de Markdown (md)
Markdown es el estándar utilizado por Git y GitHub, para maquetar la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.

### 1. Encabezados o Títulos (HEADERS) 
Para poder realizar una buena documentación del proyecto debemos, distribuir correctamente los contenido, para poder delimitar o hacer énfasis (enfatizar) , es decir resaltar las secciones importantes, podemos utilizar los siguiente: 

EJEMPLOS: 
# Encabezado de Nivel 1 - Similar a H1 en HTML 
## Encabezado de Nivel 2 - Similar a H2 en HTML 
### Encabezado de Nivel 3 - Similar a H3 en HTML 
#### Encabezado de Nivel 4 - Similar a H4 en HTML 
##### Encabezado de Nivel 5 - Similar a H5 en HTML 
###### Encabezado de Nivel 6 - Similar a H6 en HTML 
####### Encabezado de Nivel 7 - Solo 6 son los niveles permitidos, a partir de este el maquetado será ignorado.

### 2. Separadores (SEPARATORS)
Si desea marcar una separación más visual de contenidos pordemos utilizarlos indicando tres caractres de "-" continuos, en el maquetado

EJEMPLO: 
---

*Esto es similar a un tag de < HR > en HTML.

### 3. Párrafos (PARAGRPAHS)
Son utilizados para por presentar grandes secciones de texto que describen detalladamente las secciones de la documentación del proyecto.

EJEMPLO:

Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1  Este texto pertenece al párrafo 1.

 Este texto pertenece al párrafo 2  Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2

 Lo que en una página utilizariamos usando la etiqueta < P >.

También podemos aplicar estilos básicos de alineación : 

Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto

<p align="right">
Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación  Este párrafo está alineado a la derecha utilizando la propiedad de alineación   
</p>

<p align="center">
Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación Este  párrafo esta centrado usando la propiedad de alineación Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación  Este  párrafo esta centrado usando la propiedad de alineación 
</p>

<p align="justify">
Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación
</p>
 
 ### 4. Texto Enfatizado  (BOLD, ITALIC, BOLD/ITALIC)
 Si el texto que deseamos enfatizar se encuentra de un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación 

##### Texto en Negrita (BOLD) 
Para poder poner el texto en negrita, este deberá ser encerrado entre dobles **

**EJEMPLO:**

Texto  Texto Texto Texto Texto Texto **Texto Importante**  Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto

##### Texto en Cursiva (ITALIC)
Algunas veces es necesario resaltar algunas secciones o textos en cursiva para que el lector detecte el texto importante, dentro del maquetado con el estándar Markdown lo podemos realizar ubicando el texto entre  * (asteríscos)

**EJEMPLO:**

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Negrita y Cursiva (BOLD & ITALIC)

De igual manera podemos unir ammbos estilos  **Negrita** y *Cursiva* para resaltar los textos que consideremos importantes dentro de la documentación de nuestros proyectos de software, utilizando un triple * (asterísco)

**EJEMPLO:**

Texto Texto Texto Texto Texto ***Texto en Negrita y Cursiva*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto


##### Subrayado (UNDERLINE)

Algunas veces necesitaremos subraya texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML  usando el tag \<ins> y cerrando con  \</ins>

**EJEMPLO:**

Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto Subrayado</ins> Texto.


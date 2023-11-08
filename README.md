# cuaderno
cuaderno lenguajes de marcas

## UNIDAD 1
[índice](#índice)

### Qué es un lenguaje de marcas

El lenguaje de marca se refiere a la forma de redactar un documento o página web, incorporando etiquetas o marcas que contienen información adicional relativa a la estructura del texto o su formato de presentación.


### Evolución de los lenguajes de marcas


- GML


La palabra es Generalized Markup Language,en inglés, es un conjunto de macros que implementan etiquetas de marcado para el procesador de texto de IBM, SCRIPT, SCRIPT/VS.
El desarrollo de GML cambió en 1986 según la norma ISO 8879, al SGML.



- SGML


Son las siglas de Standard Generalized Markup Language o "Lenguaje de Marcado Generalizado Estándar".
Consiste en un sistema para la organización y etiquetado de documentos.Organismo desarrollador ISO para definir lenguajes de marcas generales para documentos descendiente del GML.




### Características de los lenguaje de marcas


Tipo de lenguaje que comnbina texto con información extra acerca del texto.Esa información extra se entremezcla con el texto primario.


### Características y ejemplos de los siguientes lenguajes de marcas:


   - XML
     
  Es un lenguaje de mercado extensible de formato simple basado en texto para representar la información de manera estructurada.

   -  Es un estándar para escribir datos estructurados en un fichero de texto.
  - Parece HTML pero no lo es.
 - Está en formato texto, pero no para ser leído.
  - Consta de una familia de tecnologías.
  - Es prolijo, pero no supone un problema.

  ![alt](https://www.researchgate.net/profile/Rolando_Palermo_Rodriguez_Cruz/publication/311535227/figure/download/fig1/AS:437411000918016@1481298317996/Figura-21-Ejemplo-basico-de-documento-XML-para-la-representacion-de-un-objeto-de-tipo.png)

  - HTML
    
    Es el lenguaje de la web, de manera que la inmensa mayoría de las páginas que existen están escritas en HTML. Define los contenidos de un sitio web de forma textual y estructurada indicando al navegador cómo debe visualizarse el sitio.

    ![alt](https://es.godaddy.com/blog/wp-content/uploads/Ejemplo-negritas-html-768x101.jpg)

   - JSON
   
   Es un formato de texto sencillo para el intercambio de datos. Se trata de un subconjunto de la notación literal de objetos de JavaScript, aunque, debido a su amplia adopción como alternativa a XML, se considera un formato independiente del lenguaje.
    
    
   Ejemplo:

![alt](https://www.info-computer.com/modules/dbblog/views/img/post/como-abrir-los-archivos-json.png)

![alt](https://www.sqlshack.com/wp-content/uploads/2016/06/word-image-128.png)
    

  - YAML

    Es un formato de serialización de datos legible por humanos inspirado en lenguajes como XML,C,Python,Perl, así como en el formato de los correos electrónicos.Un lenguaje de declaración de datos que facilita la legibilidad y la capacidad de escritura del usuario. 

![alt](https://ichi.pro/assets/images/max/724/1*7WUeUPTU6T0Y7sfvi_0mpg.jpeg)
  
 ### XML: Definición y características del metalenguaje
Es un metalenguaje, que va a permitir a través de distintos etiquetados,crear nuevos lenguajes de marcas o dialectos, gracias a unas reglas que define. Es mantenido por la W3C (World Wide Web Consortium), y proviene del estándar SGML.

  - Prologo : Contiene la información (meta información) sobre el resto del documento, como son la versión de XML y el código caracteres utilizados.
  
  - Contenido: Es un documento basado en texto que se puede guardar con la extensión.XML.
  - Atributos: Son la parte de los elementos XML. Un elemento puede tener varios atributos únicos. Se definen las propiedades de los elementos.

  Un atributo en XML, es una información adicional que se le da a una etiqueta en concreto. 

  Comienza con una palabra, seguido del símbolo "=" y la información entre comillas dobles.

  Una etiqueta puede tener 0 o más atributos.
  
  Cada atributo tendrá solo información; y no puede contener como tal otros atributos.
  - Etiquetas: 
 
  Una etiqueta en XML debe tener un inicio que será una palabra entre los símbolos "<" y ">".

  Siempre debe haber una etiqueta de cierre que contendrá la misma palabra de inicio entre los símbolos "</" y ">".

  El par de etiqueta de apertura y cierre se llama elemento.

  Dentro de un elemento, puede encontrarse información (texto), u otros elementos.

  En un documento XML, solo puede encontrarse un elemento raíz.


Puede añadirse comentarios entre los símboloes "<!--" y ">".

Si un elemento esta vacío, puede acortarse usando solo la etiqueta de inicio entre los símbolos "<" y "/>".

Ejemplos en XML 

![alt](https://tse4.mm.bing.net/th?id=OIP.3xRFagU0duA3H94IAbrpXgAAAA&pid=Api&P=0&h=180)

![alt](https://i.stack.imgur.com/cpl8j.jpg)

![alt](https://www.oracle.com/technetwork/es/images/xmltype-database-7-1931055.gif)


## UNIDAD 2

### Documentos XML,estructura:

- Declaración o prólogo

Es un elemento opcional que se incluye al inicio del documento.Incluye los siguientes atributos.
  


  Versión; versión de la especificación XML. Por defecto es 1.0; pero se puede utilizar XML 1.1 si se requieren las nuevas funcionalidades.
  
  Enconding: codificación en la que está escrito el documento.

  Standalone: indica si el documento contiene un DTD en el propio documento (yes) o por el contrario es externo (no).

- Elementos

Un documento xml se compone por una serie de elementos que pueden estar anidados unos con otros. Los elementos tienen las siguientes características:

Un elemento tiene un nombre que se diferencian entre mayúsculas y minúsculas. Además, el nombre puede empezar por _y porun carácter.

Debe haber un único elemento inicial llamado raíz.

Dentro de un elemento, puede contener más elementos o un texto.

Cuando un elemento está vacío, se pone con la siguiente notación. <nombre/>


Los elementos, tienen una serie de relaciones:

Un único elemento Raíz.

Cada uno de los elementos descendientes de otro elemento, se les llama hijos (children).

El elemento ascendente de otro elemento se le llama (parent).

Los elementos con un padre común se les llama hermanos (sibling).


- Atributos

- Comentarios


- Espacios de Nombres

- Entidades

- CDATA

### Validación de documentos: 
* DTD:
  * Entidades

  * Anotaciones

  * Elementos 

  * Atributos

* XMLSchema
  
    * Definición
    * Estructura Básica
    * Elementos Locales y Globales
    * Elementos Simples
    * Elementos Complejos
    * Subelementos
    * Atributos
    * Restricciones
    * Tipos de Datos
    * Comentarios en XMLSChema




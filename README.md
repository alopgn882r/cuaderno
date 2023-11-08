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

Un atributo se imcluye como información adicional dentro de un elemento; tienen las siguientes características.

* Puede comenzar por guion bajo _ o por un carácter, además su nombre no puede contener espacios.

* Deben tener un valor, que puede ir entre comillas ya sean dobles o simples; pero se recomienda el uso de dobles.

* Pueden ser opcionales su aparición y siempre deben de estar dentro de un elemento.
- Comentarios

Un comentario en XML, permite añadir información sin que esta sea procesada. Suele ser util para poner información al documento para el usuario.


- Espacios de Nombres

Un espacio de nombres o namespace, permite distinguir etiquetas que pueden ser ambiguas. Para ello, se puede usar un atributo especial llamado xmlns seguido de dos puntos y el nombre del prefijo a utilizar. Después en el valor del atributo, se establece la URI donde esta definido el DTD de dicho espacio de nombres.
- Entidades

Las entidades, son fragmentos de información predefenidos que nos van a permitir incluir dicha información sin necesidad de repetir dicha información o utilizar caracteres especiales.

* Para utilizar una entidad se comienza con el carácter & y se termina con ;.

* Pueden estar definidas en el DTD o que sean externas.

* Se pueden clasificar en:
  * Generales: Forma parte del documento
  
  Internas: Están definidas en el propio documento.
  Externas:Están definidas en un documento externo.

  * Externas por parámetros: permite transformarlas en un DTD.

  Además, XML incluye unas entidades internas predefinidas.

- CDATA

El elemento CDATA, es un fragmento de información que no será procesador por el analizador; sin embargo, si que se almacenará su información, a diferencia de los comentarios.

![alt](https://cdn.educba.com/academy/wp-content/uploads/2020/05/Xml-CDATA-4.jpg)

### Validación de documentos: 

A la hora de trabajar con documentos XML, hay que tener en cuenta dos cuestiones.

* Que el documento esté bien formado, es decir que cumpla las reglas del metalenguaje XML.

* Que el documento esté validado, esto quiere decir que la estructura del documento cumpla un cierto esquema o vocabulario.

Es importante decir, que para que un documento este bien formado, si:

* Tiene un único elemento Raíz.

* Todos los elementos deben estar cerrados.

* Los elementos tienen que estar anidados correctamente; no se pueden intercalar aperturas y cierres.

* Todos los valores de los atributos están entrecomillados.

* Los nombres de elementos y atributos, deben cumplir sus respectivas reglas.

Para realizar la validación de un documento XML, podemos usar dos herramientas. 

 DTD

 (Document Type Definition), es una serie de reglas que van a permitir validar que la estructura de un documento es válida

 Las reglas contenidas en un DTD tienen que ver con la estructura del documento (elementos, atributos, entidades...); aunque tiene algunas limitaciones que se pueden suplir usando XML Schema.

 Un DTD, puede ser: 

 * Interno: que esta definido en el propio documento.

 * Externo: que esta definido en un fichero externo.

 
 XML Schema



* DTD:
  * Entidades
Permiten utilizar un valor fijo cuando se utiliza esta unidad.

Las entidades pueden ser:

* Internas. Están dentro del propio DTD.
* Externas. Se definen en un fichero externo. Pudiendo ser:
  * Pública
  * Privada


* Anotaciones
Una anotación es un componente que define un formato de un valor, concretamente que no se utilizaran como una entidad XML, como puede ser el caso del valor de un atributo.

Pueden ser Publicas o Privadas.

 * Elementos 
 
 Define la estructura de uno o varios elementos que contienen el elemento. 

Donde contenido puede ser:

* Empty: Vacío.
* ANY:Cualquier valor.
* (#PCDATA): Elemento de tipo carácter.

* (NombreElemento): Elemento Hijo.

* (NombreElemento1,NombreElemento)Lista de elementos hijos.

Es importante saber, que se puede indicar una cardinalidad, a la hora de saber cuantas veces puede repetirse un elemento dentro de otro. 

  * Atributos

  Donde tipoAtributo puede ser:

  * CDATA: Cadena de caracteres.

  * (Valor1/Valor2): Lista de valores.

  * ID: Identificador único.

  * IDREF: Referencia a un identificador de otro elemento.

  * IDREFS: Lista de identificadores de otro elemento.

  * NMTOKENS: Lista de Nombres XML válidos.

  * ENTITY: Referencia a una entidad.

  * ENTITIES: Referencia a un conjunto de entidades.

  * NOTATION: Nombre de una anotación.

  * XML:lang: Idioma del documento.

  * XML:space: Indica si se han de respetar espacios, tabulaciones y retornos de carro múltiples.

  Por otro lado, para ver los valores de un atributo, puede ser: 

  * Valor: valor o lista de valores (separados por 
  |) que puede tomar el atributo.

  * #REQUIRED: Atributo obligatorio.

  * #IMPLIED: Indica que el valor es opcional.

  * #FIXED valor: Indica un valor fijo.

* XMLSchema
  
    * Definición

    Es un lenguaje de esquema utilizado para describir la estructura y las restricciones de los contenidos de los documentos XML de una forma muy precisa, más allá de las normas sintáticas impuestas por el propio lenguaje XML. Se consigue así una percepción del tipo de documento con un nivel alto de abstraccción. 

    * Estructura Básica

Deben tener una estructura jerárquica con lo que respecta a las etiquetas que delimitan sus elementos.

  * Elementos Locales y Globales

   * Elementos Simples

   <xs:element name="mes" type="xs:string" fixed="agosto"/>


   * Elementos Complejos

   <xs:element name="bola">


  <xs:complexType>


  <xs:attribute name="numero" type="numeroDeBola"/>


  </xs:complexType>


</xs:element>


<xs:simpleType name="numeroDeBola">


   <xs:restriction base="xs:positiveInteger">


  <xs:minInclusive value="1"/>


 <xs:maxExclusive value="90"/>


   </xs:restriction>


</xs:simpleType>

   * Subelementos
   * Atributos

   <xs:attribute name="nombre_del_atributo" type="tipo_de_dato"/>

   * Restricciones

   xs:length  Especifica una lontiud fija.
   
   * Tipos de Datos
   * Comentarios en XMLSChema




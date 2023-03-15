***
# *Paradigma OO*
***
*Tabla de contendo.*
1. Paradigma OO.
* Definición de Paradigma.
* Definición de Programación Orientada a Objetos.
* Concepto de abstracción.
* Concepto de encapsulamiento.
* Concepto de herencia.
2. UML.
* Lenguaje de Modelado Unificado.
* Propuesta y Diagrama.

---



## 1. Definición de Paradigma en el contexto de lenguajes de programación.

Un paradigma de programación es una manera o estilo de programación de software. Existen diferentes formas de diseñar un lenguaje de programación y varios modos de trabajar para obtener los resultados que necesitan los programadores.  Se trata de un conjunto de métodos sistemáticos aplicables en todos los niveles del diseño de programas para resolver problemas computacionales[^1].

## 2. Definición de Programación Orientada a Objetos, ¿Cuál fue el primer lenguaje orientado a objetos, quienes y en dónde lo propusieron?
En este modelo de paradigma se construyen modelos de objetos que representan elementos (objetos) del problema a resolver, que tienen características y funciones. Permite separar los diferentes componentes de un programa, simplificando así su creación, depuración y posteriores mejoras. La programación orientada a objetos disminuye los errores y promociona la reutilización del código. Es una manera especial de programar, que se acerca de alguna manera a cómo expresaríamos las cosas en la vida real[^2].

Podemos definir un objeto como una estructura abstracta que, de manera más fiable, describe un posible objeto del mundo real y su relación con el resto del mundo que lo rodea a través de interfaces.  Ejemplos de lenguajes de programación orientados a objetos serían Java, Python o C#.

La programación orientada a objetos se sirve de diferentes conceptos como:

+ Abstracción de datos
+ Encapsulación
+ Eventos
+ Modularidad
+ Herencia
+ Polimorfismo

### *¿Cuál fue el primer lenguaje orientado a objetos, quienes y en dónde lo propusieron?*

Simula (1967) es aceptado como el primer lenguaje que posee las características principales de un lenguaje orientado a objetos. Fue creado para hacer programas de simulación, en donde los "objetos" son la representación de la información más importante. Smalltalk (1972 a 1980) es posiblemente el ejemplo canónico, y con el que gran parte de la teoría de la programación orientada a objetos se ha desarrollado[^3].
Los orígenes de Smalltalk se encuentran en las investigaciones realizadas por Alan Kay, Dan Ingalls, Ted Kaehler, Adele Goldberg y otros durante los años setenta en el Palo Alto Research Center de Xerox (conocido como Xerox PARC), para la creación de un sistema informático orientado a la educación. El objetivo era crear un sistema que permitiese expandir la creatividad de sus usuarios, proporcionando un entorno para la experimentación, creación e investigación.
Quien tuvo la idea fue D. Parnas cuando propuso la disciplina de ocultar la información. Su idea era encapsular cada una de las variables globales de la aplicación en un solo módulo junto con sus operaciones asociadas, sólo mediante las cuales se podía tener acceso a esas variables.
El resto de los módulos (objetos) podían acceder a las variables sólo de forma indirecta mediante las operaciones diseñadas para tal efecto[^4]

## 3. Define con tus palabras el concepto de abstracción, ¿Por qué se considera fundamental en programación? 
La abstracción se utiliza para descartar toda aquella información que no es relevante para el contexto en el que se esté trabajando. Esta depende del interés del observador, así pues consiste en captar las características y funciones que un objeto desempeña y estas son representadas en  clases, por medio de atributos y métodos de dichas clases. 
Un programa es una descripción abstracta de un proceso o fenómeno que sucede en el mundo real, así la abstracción es crucial para entender los procesos que nos rodean, dicha herramienta nos sirve para tratar la complejidad de las clases y atributos de los objetos.

## 4. Explica el concepto de encapsulamiento, busca dos imágenes que te ayuden a describir el concepto, una que tenga algún sistema sin encapsulamiento y otra donde sí lo tenga. Menciona porque es importante y qué problemas puede evitar.
Esta consiste en almacenar y organizar en una clase, las características y funciones de los objetos, representandolas mediante atributos y métodos.Así esta garantiza la integridad de los datos de algún objeto, evita el acceso a datos por cualquier medio distinto que el programador especifique o permita en la clase. Podemos por medio del encapsulamiento hacer uso del ocultamiento de la información.

![Ejemplo 1][logo]

[logo]: https://user-images.githubusercontent.com/126517767/225433837-1265eff6-894e-4047-96b7-08197950d086.png "Ejemplo 1 representación de un código sin encapsulado.  "
> *Ejemplo 1 representación de un código sin encapsulado.*

![Ejemplo 2][logo2]

[logo2]: https://www.ciberaula.com/cursos/java/assets/img/enc_2.PNG "Ejemplo 2 representación de un encapsulado  "
> *Ejemplo 2 representación de un encapsulado*

El encapsulado nos da un nivel de seguridad mayor a nuestras aplicaciones, restringiendo el acceso a métodos y atributos, asegurándonos que el usuario seguirá una ruta especificada por nosotros para acceder a la información. 

## 5. Describe con tus palabras el concepto de herencia e ilustra el concepto con imágenes.
La herencia es el arte de reutilizar código, el arte de extender lo que ya se programó, a algo que también tendrá lo mismo, en pocas palabras un copiar y pegar pero más elegante. 

![Ejemplo 3][logo3]

[logo3]: https://user-images.githubusercontent.com/126517767/225448558-af156f06-6c26-496e-9697-4fbd4a5f9a29.png "Ejemplo 3 representación de un código de herencia.  "
> *Ejemplo 3 representación de un código de herencia .*

Un ejemplo sería la clase espada, pero queremos crear la clase espada de fuego, solo que en la nueva clase se agregan los extras con los que queremos que cuente la nueva espada. Siendo así el mismo objeto pero con distinto propósito. Así pues la clase padre es espada ya que esta da sus atributos y la que recibe siendo espada de fuego la clase hija. Por lo tanto la herencia nos facilita crear nuevas clases de objetos que cuentan con la misma clase, facilitando el proceso y volvernos más productivos.


***
# *UML: Diagrama de clases*
***

## 1. Investiga la historia y haz un resumen del Lenguaje de Modelado Unificado, donde se mencione: quienes son sus principales autores (Booch, Rumbaugh, Jacobson), en que tipo de sistemas se utiliza, que tan utilizado es en años recientes, en particular el Diagrama de Clases. Menciona algunas de las herramientas para el modelado en UML. ¿Sabes de alguna empresa local que utilice este lenguaje?
El Lenguaje Unificado de Modelado (UML) fue creado para forjar un lenguaje de modelado visual común y semántica y sintácticamente rico para la arquitectura, el diseño y la implementación de sistemas de software complejos, tanto en estructura como en comportamiento. UML tiene aplicaciones más allá del desarrollo de software, p. ej., en el flujo de procesos en la fabricación.

Es comparable a los planos usados en otros campos y consiste en diferentes tipos de diagramas. En general, los diagramas UML describen los límites, la estructura y el comportamiento del sistema y los objetos que contiene.

UML no es un lenguaje de programación, pero existen herramientas que se pueden usar para generar código en diversos lenguajes usando los diagramas UML. UML guarda una relación directa con el análisis y el diseño orientados a objetos.

"The Three Amigos" (los tres amigos) de la ingeniería de software, como se los conocía, habían desarrollado otras metodologías. Se asociaron para brindar claridad a los programadores creando nuevos estándares. La colaboración entre Grady, Booch y Rumbaugh fortaleció los tres métodos y mejoró el producto final.

Los esfuerzos de estos pensadores derivaron en la publicación de los documentos UML 0.9 y 0.91 en 1996. Pronto se hizo evidente que varias organizaciones, incluidas Microsoft, Oracle e IBM, consideraron que UML era esencial para su propio desarrollo de negocios. Ellos, junto con muchas otras personas y compañías, establecieron los recursos necesarios para desarrollar un lenguaje de modelado hecho y derecho. "Los tres amigos" publicaron la Guía del usuario para el Lenguaje Unificado de Modelado en 1999, y una actualización que incluye información sobre UML 2.0 en la segunda edición de 2005[^5].

UML cumple con los siguientes requerimientos:

+ Establecer una definición formal de un metamodelo común basado en el estándar MOF (Meta-Object Facility) que especifique la sintaxis abstracta del UML. La sintaxis abstracta define el conjunto de conceptos de modelado UML, sus atributos y sus relaciones, así como las reglas de combinación de estos conceptos para construir modelos UML parciales o completos.
+ Brindar una explicación detallada de la semántica de cada concepto de modelado UML. La semántica define, de manera independiente a la tecnología, cómo los conceptos UML se habrán de desarrollar por las computadoras.
+ Especificar los elementos de notación de lectura humana para representar los conceptos individuales de modelado UML, así como las reglas para combinarlos en una variedad de diferentes tipos de diagramas que corresponden a diferentes aspectos de los sistemas modelados.
+ Definir formas que permitan hacer que las herramientas UML cumplan con esta especificación. Esto se apoya (en una especificación independiente) con una especificación basada en XML de formatos de intercambio de modelos correspondientes (XMI) que deben ser concretados por herramientas compatibles.

El diagrama UML más comúnmente usado, y la base principal de toda solución orientada a objetos. Las clases dentro de un sistema, atributos y operaciones, y la relación entre cada clase. Las clases se agrupan para crear diagramas de clases al crear diagramas de sistemas grandes.

Algunas herramientas para el modelado de clases son: 

+ GitMind: manejo sencillo en la nube.
+ Gliffy: una herramienta UML online para dar los primeros pasos.
+ MagicDraw: todo lo que se necesita para diagramas UML profesionales.
+ Lucidchart: la herramienta UML online para el trabajo en equipo.
+ IBM Rational Rhapsody: entorno de desarrollo gráfico para integrar procesos.

### ¿Sabes de alguna empresa local que utilice este lenguaje?

Conozco el Itstep, que es una academia, está desconozco si lo implementa en algún proyecto fuera de la educación, pero  brinda el servicio de la educación.

## 2. Escribe una propuesta de una máquina que venda distintos artículos y haz el diagrama de clases del sistema que propones. Recuerda que puede haber composición (un teclado se compone de botones) y generalización (tipo de productos, tipo de pago).


---
# Referencias.
[^1]: M. (2022, 14 marzo). ¿Qué son los paradigmas de programación? Profile Software Services. https://profile.es/blog/que-son-los-paradigmas-de-programacion/
[^2]: M. (2022, 14 marzo). ¿Qué son los paradigmas de programación? Profile Software Services. https://profile.es/blog/que-son-los-paradigmas-de-programacion/
[^3]: C. (s. f.). 🥇🥇 Lenguaje Orientado a Objetos. https://www.ciberaula.com/cursos/java/lenguaje_orientado_objetos.php
[^4]: Integrantes:, & Perfil, V. T. M. (s. f.). HISTORIA DE LOS LENGUAJES DE PROGRAMACION ORIENTADA A OBJETOS. http://sis324loo.blogspot.com/2008/09/historia-de-los-lenguajes-de_29.html
[^5]: Qué es el lenguaje unificado de modelado (UML). (s. f.). Lucidchart. https://www.lucidchart.com/pages/es/que-es-el-lenguaje-unificado-de-modelado-uml

# Aprendizaje en programación:

## Git:

Es un software de versionameinto que permite el desarrollo y mantenimiento de aplicaciones. Guarda el registro de los cambios que sufra un archivo. Se puede usar tanto de manera individual como en equipo. Los archivos se guardaran en un repositorio, mismo que almacena virtualmente el proyecto.  Para guardar los cambios que se realizan en un proyecto se usan distitnos comandos como git add, el cual permite subir el archivo al area de preparación y git commit para guardar la última versión. 

El uso de git permite la creación de distitnas ramas para crear distintas versiones de un mismo archivo y unificarlas en su debido momento. Para ello, se emplean los comandos git merge que se usa para fusionar las ramas respetando la historia de la segunda rama, se usa git rebase para fusionar las ramas ubicando los commits de la segunda rama posteriores a los de la primera, y finalmente, git cherry-pick se usa para escoger el commit de una rama y aplicarlo en otra.

En caso de obtener archivos que necesitamos ocultar o “ignorar” empleamos un archivo gitignore en el cual ingresamos cada uno de los archivos que no necesitamos mostrar o que ocupen un espacio en la memoria.

##GitHub: 

Es una plataforma online de desarrollo de software que se usa para almacenar, supervisar y trabajar con proyectos de software. Permite trabajar de manera colaborativa en proyectos de código abierto. Dichos archivos se pueden subir a un repositorio remoto desde un repositorio local con el comando git push, de la misma manera los repositorios se pueden obtener con el comando git pull. Para especificar las versiones del proyecto se usa git tag. Sin embargo, para realizar este proceso, incialmente se debe crear una cuenta en GitHub, poserior a eso se debe crear desde el computador una llave SSH (Secure Shell), dicha llave es una seguridad extra que nos permitirá subir los archivos de manera confiable, de esa manera se podrá crear un repositorio en GitHub y subir los archivos de local a remoto.

---------------------------------------------------------------------------------------------------------------

## Conceptos básicos de programación

- Software: Conjunto de códigos de sistema operativo. Esta compuesto por aplicaciones y programas  para hacer que los dispositivos electronicos funcionen.
- Librería: Herramientas que permiten que el desarrollo de software sea mas eficiente. Proporcionan fragmento de código reutilizables.
Codigo ya escrito que se puede reutilizar para agilizar la tarea de un programador
- Aplicación: Programa informático diseñado como herramienta para facilitar tareas complejas. Se usa para realizar operaciones o funciones epecíficas para el beneficio y necesidad del usuario.
- Api (Application Programming Interfaces): Intermediario entre dos aplicaciones de software que permite su comunicación y que pida datos o acciones epecíficas. (cuando se conecta un juego a la sesión de face) (Usados en aplicaciones para subir a la nube)
- Stock: Conjunto o cantidad de productos que tiene almacenado una empresa.
- Endpoint: Punto final de comunicación. Dirección de una API o backend que se encarga de dar respuesta a una petición. Dispositivo en el que se usa una aplicación o software. Celular blablabla.
Entrada de activos y aplicaciones de una empresa, y representa vulnerabilidad de ciberseguridad.
- Framework: Marco de trabajo que sirve como base para desarrollar un proyecto con objetivos específicos.

#JAVA

Es un lenguaje de programación enfocada a objetos, que permite desarrollar distintos servicios y aplicaciones. Cuenta con distintos elementos como JVM (Java Virtual Machine), en el cual se encuentra todo lo necesario para correr las aplicaciones escritas en java. También cuenta con el JRE (Java Runtime Enviroment) que permite correr el código bytecode de java en los distintos sistemas operativos, este elemento contiene dentro de sí el JVM. Por último, cuenta con JDK (Java Development Kit) el cual, permite desarrollar java y convierte el código fuente en bytecode, también contiene JRE. 

## Conceptos básicos:

- Clase = Es un plano, se le llama abstacción o también puede ser un tipo de dato abstacto.
- Objeto = variable, espacio de almacenamiento, realización de una clase, instanciación
- Función = Es un verbo y también se le denomina método. Se crea con base en el tipo de retorno, nombre, las entradas y el cuerpo de la misma.
- Valor = Adjetivo, lo que se le asigna a un objeto o a una propiedad
- Propiedades: es lo que tiene un objeto, sus características. Pueden ser tanto públicas como privadas y se crean junto con su tipo de retorno, este depende si es un número entero o decimal, si es un boolean o si es una cadena de texto.

##Tipos de datos primitivos:
- Números enteros: byte, short, int, long. -> Depende de que tan extenso sea el número. y el espacio de memoria que ocupe.
- Números decimales: float, double. 
- Carácter simple: char
- Valor true false: boolean.

Álgebra de boole: Es una estructura algebráica que esquematiza operaciones lógicas. Funciona a través de valores como verdadero y falso denotados por los números 1 y 0, además usa los operadores lógicos como la conjunción (y) denotada como ∧, la disyunción (o) denotada como v y la negación (no) denotada como ¬. En java ∧ = &&, v = || y ¬ = !

## Pilares de la programación:

- Abstraccion : Es la capacidad de simplificar las caracteristicas y funcionalidades de objetos del mundo real y describirlas en clases con nombres, propiedades y funciones.
- Encapsulamiento: Es la capacidad de ocultar o privatizar propiedades de un objeto por temas de seguridad, con el cual se puede representar su valor según su necesidad a traves de una funcionalidad.
- Herencia: Es el mecanismo en el cual se extienden las caracteristicas y funcionalidades de una clase madre a su clase hija.
- Polimorfismo: Es la capacidad de enviar mensajes iguales para objetos distintos y del cual se recibe una respuesta distinta. El objeto de la clase madre puede almacenar un objeto de las clases hija.

## Condicionales:

Son estructuras que permiten elegir entre la ejecución de una acción u otra. Se elige a partir de una condición como bien lo dice su nombre, algunas estructuras de control de flujo son: if, else y switch.
Ciclos:

Son una secuencia de instrucciones de código que se ejecuta repetidas veces, hasta que la condición asignada a dicho bucle deja de cumplirse, se usa como una estructura de control. Los ciclos en java son while, do-while y for.

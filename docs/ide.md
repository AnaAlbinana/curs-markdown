# Entornos de desarrollo

Una vez se ha descrito el proceso general para desarrollar y llegar a ejecutar un programa, se hace evidente que hay que tener instalados y correctamente configurados dos programas completamente diferentes e independientes en vuestro ordenador para desarrollarlos: editor, por un lado, y compilador (incluyendo el enlazador) o intérprete por otro, según el tipo de lenguaje. Cada vez que queréis modificar y probar vuestro programa tendréis que ir alternando ejecuciones entre los dos. Realmente, sería mucho más cómodo si todo ello se pudiera hacer desde un único programa, que integrara los tres. Un editor avanzado desde el cual se pueda compilar, enlazar si se tercia, e iniciar la ejecución de código fuente para comprobar si funciona.

Un **IDE** (integrated development environment o entorno integrado de desarrollo) es una herramienta que integra todo lo que hace falta para generar programas de ordenador, de forma que el trabajo sea mucho más cómodo.

La utilización de estas herramientas agiliza increíblemente el trabajo del programador. Además, los IDE más modernos van más allá de integrar editor, compilador y enlazador o intérprete, y aportan otras características que hacen todavía más eficiente la tarea de programar. Por ejemplo:

- Posibilidad de hacer resaltar con códigos de colores los diferentes tipos de instrucciones o aspectos relevantes de la sintaxis del lenguaje soportado, para facilitar la comprensión del código fuente.
- Acceso a documentación y ayuda contextual sobre las instrucciones y sintaxis de los lenguajes soportados.
- Detección, y en algunos casos incluso corrección, automática de errores de sintaxis en el código, de manera similar a un procesador de texto. Así, no hay que compilar para saber que el programa está mal.
- Apoyo simultáneo del desarrollo de lenguajes de programación diferentes.
- Un depurador, una herramienta muy útil que permite pausar la ejecución del programa en cualquier momento o hacer la ejecución instrucción por instrucción, de forma que permite analizar como funciona el programa y detectar errores.
- En los más avanzados, sistemas de ayuda para la creación de interfaces gráficas.

En definitiva, usar un IDE para desarrollar programas es una opción muy recomendable. Aun así, hay que tener presente que son programas más complejos que un simple editor de texto y, como pasaría con cualquier otro programa, hay que dedicar un cierto tiempo a familiarizarse con estos y con las opciones de que disponen.

## JDK

El Java Development Kit proporciona el conjunto de herramientas básico para el desarrollo de aplicaciones con Java estándar. Se puede obtener de manera gratuita en la Web de Oracle, descargándolo desde la dirección:

[https://www.oracle.com/es/java/technologies/javase-downloads.html](https://www.oracle.com/es/java/technologies/javase-downloads.html)

Descarga la versión correspondiente según tu sistema operativo.

Para el caso de los ordenadores del aula, tenemos instalado Debian y, por tanto, se debe descargar la versión: Linux x64 Debian Package.

## Eclipse

Eclipse es un programa informático compuesto por un conjunto de herramientas de programación de código abierto multiplataforma para desarrollar aplicaciones. Esta plataforma, fundamentalmente ha sido utilizada para desarrollar entornos de desarrollo integrados (IDE), como el de Java. Sin embargo, también se puede usar para otros tipos de aplicaciones cliente, como BitTorrent o Azureus.

La definición que da Eclipse acerca de su software es: “una especie de herramienta universal – un IDE abierto y extensible para todo y nada en particular”.

### Instalación

Para la descarga de Eclipse accederemos a la página oficial [https://www.eclipse.org/download](https://www.eclipse.org/downloads/)

Descargaremos Eclipse IDE 2025-06. Normalmente, se detecta automáticamente el sistema operativo, si no es así ves a Download Packages y en la nueva ventana aparecerá la descarga para Linux.
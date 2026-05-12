# Implementación

Si en las dos fases anteriores requieren un especial cuidado en la realización del análisis y el posterior diseño de la solución, la fase de implementación cobra también una especial relevancia. Llevar a la realidad nuestro algoritmo implicará cubrir algunas etapas más que se detallan a continuación.

## Codificación o construcción

Esta etapa consiste en transformar o traducir los resultados obtenidos a un determinado lenguaje de programación de alto nivel.

La codificación del programa suele ser una tarea pesada que requiere un conocimiento completo de las características del lenguaje elegido para conseguir un programa eficaz. Sin embargo, si el diseño del algoritmo se ha realizado en detalle con acciones simples y con buena legibilidad, el proceso de codificación puede reducirse a una simple tarea mecánica. Las reglas de sintaxis que regulan la codificación variarán de un lenguaje a otro y el programador deberá conocer en profundidad dichas reglas para poder diseñar buenos programas.

Para aumentar la productividad, es necesario adoptar una serie de normas, como:

- Estructuras aceptables (programación estructurada)
- Convenciones de nominación: maneras uniformes de designación de archivos y variables.
- Convenciones de comentarios.

Cuando realizamos la traducción del algoritmo al lenguaje de programación obtendremos entonces el **código fuente**, lo que normalmente conocemos por programa.

Pero para que nuestro programa comience a funcionar, antes debe ser traducido a un lenguaje que la máquina entienda. Según el tipo de traductor que se utilice, los lenguajes de alto nivel se clasifican en **lenguajes interpretados** y **lenguajes compilados**.

Son **lenguajes interpretados** aquellos en los que el sistema traduce una instrucción y la ejecuta, y así sucesivamente con las restantes.
Son **lenguajes compilados** aquellos en los que, primero se traduce el programa fuente completo, obteniéndose un código intermedio o módulo objeto (**código objeto**); después, se fusiona este con rutinas o librerías necesarias para su ejecución en un proceso llamado linkado y que obtiene como resultado un módulo ejecutable (**programa ejecutable**).

La ventaja de los lenguajes compilados, frente a los interpretados, son su rápida ejecución y, en caso de necesitar posteriores ejecuciones del mismo programa, se hará del ejecutable almacenado.

Una vez traducido, sea a través de un proceso de compilación o de interpretación, el programa podrá ser ejecutado.

Para comprobar la calidad y estabilidad de la aplicación se han de realizar una serie de pruebas que comprueben las funciones de cada módulo (pruebas unitarias), que los módulos funcionan bien entre ellos (pruebas de interconexión) y que todos funcionan en conjunto correctamente (pruebas de integración). (Se estudiará en la unidad 4)

## Prueba de ejecución y validación

Para esta etapa es necesario implantar la aplicación en el sistema donde va a funcionar, debe ponerse en marcha y comprobar si su funcionamiento es correcto. Utilizando diferentes datos de prueba se verá si el programa responde a los requerimientos especificados, si se detectan nuevos errores, si estos son bien gestionados y si la interfaz es amigable. Se trata de poner a prueba nuestro programa para ver su respuesta en situaciones difíciles.

Mientras se detecten errores y estos no se subsanen no podremos avanzar a la siguiente fase. Una vez corregido el programa y testeado se documentará mediante:

- **Documentación interna**: Encabezados, descripciones, declaraciones del problema y comentarios que se incluyen dentro del código fuente.
- **Documentación externa**: Son los manuales que se crean para una mejor ejecución y utilización del programa.
# Preguntas de investigación

## Daniel Gracia - 1º DAW

## Apartado 7: Investigación sobre colaboración en equipo con Git y GitHub 

1. ¿Qué es un repositorio remoto y en qué se diferencia de uno local? 
 - Un repositorio remoto es el que se encuentra ubicado en la nube (por ejemplo: GitHub), el cual permite que varios desarrolladores puedan trabajar en él desde distintos sitios.

 - Un repositorio local es una copia del repositorio que se encuentra guardada en nuestro equipo. Contiene todos los archivos e historial y permite que hagamos commits y modificaciones sin necesidad de que estemos conectados a la red.


2. ¿Qué es un "fork" en GitHub y cómo se usa en proyectos colaborativos? 
 - En GitHub, el término de “fork” se refiere a una copia de un repositorio en nuestra cuenta personal. Nos permite hacer cambios en cualquier proyecto sin que estos afecten el repositorio original. Esto puede servir a la hora de realizar proyectos de código abierto, ya que se pueden modificar libremente y más tarde mediante un pull request, proponer estos cambios al repositorio original. 


3. ¿Qué es un "pull request" (PR) y cuál es su propósito? Describe el flujo de trabajo típico. 
 - Como se ha explicado en la anterior pregunta, el “pull request” es una solicitud para fusionar cambios desde una rama a otra en un repositorio de GitHub. 

 - El propósito de un pull request es permitir que el código sea revisado antes de integrarlo en la rama principal.

 - En un flujo de trabajo típico, cada nueva función se desarrolla en una rama independiente. Cuando esta se complementa, se crea un pull request en GitHub, que un responsable revisa antes de fusionarla en la rama de producción. Esto garantiza la estabilidad y calidad del código.

4. ¿Qué son los "issues" y los "proyectos" en GitHub? ¿Para qué sirven? 
 - Los “issues” son herramientas para reportar errores, sugerir mejoras o discutir nuevas ideas dentro de un repositorio.

 - Los “proyectos” son tableros que nos permiten organizar, planificar y hacer un seguimientos de los issues y pull request.

5. Explica la importancia de las ramas en un entorno de trabajo colaborativo. ¿Cómo se suelen organizar  las ramas en proyectos grandes (ejemplo: main, dev, feature)?
 - Las ramas en un entorno de trabajo son imprescindibles, ya que estas permiten corregir errores o modificar código de manera aislada sin afectar al propio código principal del proyecto. Solo se fusionan cambios aprobados y listos para la produccón.

 - main (o master) - Es la rama principal y estable del proyecto.
 - dev (o develop) - Es la rama donde se integran los cambios en desarrollo antes de ser promovidos a main.
 - feature - Son ramas para desarrollar nuevas funcionalidades. Estas son creadas desde dev y una vez probadas, se fusionan de nuevo en dev.
 - hotfix - Ramas para corregir errores críticos. Se crean desde el main y una vez aplicados los cambios se fusionan en main y dev.
 - release - Ramas donde se estabilizan nuevas versiones antes de lanzarlas a producción.

 

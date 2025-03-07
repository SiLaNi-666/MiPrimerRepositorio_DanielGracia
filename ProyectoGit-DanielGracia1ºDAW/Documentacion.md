# Proyecto sobre GIT

## Hecho por Daniel Gracia Calvo - 1ºDAW

### Aparatado 1
- 1.1 Instalación de Git:

<img src="/ImagenesProyecto/Instalacion1.png" alt="Captura ejercicio 1.1" width="100%"/>
<img src="/ImagenesProyecto/setup.png" alt="Captura ejercicio 1.1" width="100%"/>
<img src="/ImagenesProyecto/setup2.png" alt="Captura ejercicio 1.1" width="100%"/>


- 1.2 Configuración de usuario y correo electronico:
<img src="/ImagenesProyecto/configUserYMail.png" alt="Captura ejercicio 1.2" width="100%"/>


- 1.3 Verificación de la configuración:
<img src="/ImagenesProyecto/VerificarConfig.png" alt="Captura ejercicio 1.3" width="100%"/>
<img src="/ImagenesProyecto/VerificarConfig2.png" alt="Captura ejercicio 1.3" width="100%"/>


### Apartado 2 Trabajando con un repositorio local

- 1.1 Crear una carpeta llamada MiPrimerRepositorio_TuNombre:
<img src="/ImagenesProyecto/MiPrimerRepositorio.png" alt="Captura ejercicio 2-1.1" width="100%"/>

- Creo la carpeta MiPrimerRepositorio_DanielGracia y me muevo a ella.


- 1.2 Ejecutar git init dentro de la carpete:
<img src="/ImagenesProyecto/GitInit.png" alt="Captura ejercicio 2-1.2" width="100%"/>

- git init es un comando que sirve para inicializar un nuevo repositorio.


- 1.3 Crear un archivo README.md y escribir una breve descripción:
<img src="/ImagenesProyecto/CrearREADME.png" alt="Captura ejercicio 2-1.3" width="100%"/>

- Con code . git nos abre Visual Studio ya que previamente lo hemos configurado de manera que el VS Code sea nuestro editor de texto. Una vez dentro de él, creamos el archivo README.md con la descripción y el nombre.


- 2.1 Añadir el archivo al área de preparación:
<img src="/ImagenesProyecto/AñadirREADMEaStage.png" alt="Captura ejercicio 2-2.1" width="100%"/>

- Git status: Para ver el estado del repositorio y con Git add “nombre del fichero”: para agregar el fichero README.md a git para que esté en la etapa de stage. 


- 2.2 Realizar el primer commit con el texto "Primer commit: Creación del README":
<img src="/ImagenesProyecto/PrimerCommitREADME.png" alt="Captura ejercicio 2-2.2" width="100%"/>


### Apartado 3 Subir un repositorio a GitHub

- 1.1 Acceder a GitHub y crear un repositorio vacio:
<img src="/ImagenesProyecto/CrearRepositorioGitHub.png" alt="Captura ejercicio 3-1.1" width="100%"/>


- 2.1 En la terminal, añadir el repositorio remoto:
<img src="/ImagenesProyecto/VincularRepositorioLocalConGitHub.png" alt="Captura ejercicio 3-2.1" width="100%"/>

- Git remote: nos sirve para que nosotros podamos indicar si vamos a tener un servidor remoto en el cual vamos a poder subir los cambios
- Add origin: Le indicamos de donde tenemos que ir a obtener nuestro codigo y a donde tenemos que subir los cambios que nosotros realicemos. 


- 2.2 Subir los cambios al repositorio remoto:
- Git push: Comando para que nosotros podamos subir nuestros cambios. 
<img src="/ImagenesProyecto/SubirCambiosAGitHub.png" alt="Captura ejercicio 3-2.2" width="100%"/>

- Inicio sesión desde el navegador
<img src="/ImagenesProyecto/ComprobarREADMEenGitHub.png" alt="Captura ejercicio 3-2.2" width="100%"/>

- Compruebo que se ha ejecutado correctamente.


### Apartado 4 Crear una nueva rama

- 1.1 Crear una nueva rama llamada dev:
<img src="/ImagenesProyecto/CreacionRamaDev.png" alt="Captura ejercicio 4-1.1" width="100%"/>

- Con git branch "nombre-de-la-rama" creamos la nueva rama
<img src="/ImagenesProyecto/CambiarARamaDev.png" alt="Captura ejercicio 4-1.1" width="100%"/>

- Si utilizamos "git checkout -b "nombre-de-la-rama"", se crea la rama y automaticamente nos mueve a ella.


- 2.1 Crear un script.js:
<img src="/ImagenesProyecto/CrearScriptjs.png" alt="Captura ejercicio 4-2.1" width="100%"/>


- 2.2 Añadir y realizar un commit con el archivo script.js:
<img src="/ImagenesProyecto/AñadirYHacerCommitDeScript.png" alt="Captura ejercicio 4-2.2" width="100%"/>


- 3.1 Cambia de nuevo a la rama main:
<img src="/ImagenesProyecto/CambiarAMain.png" alt="Captura ejercicio 4-3.1" width="100%"/>


- 3.2 Fusionar los cambios de dev y main:
<img src="/ImagenesProyecto/FusionarDevConMain.png" alt="Captura ejercicio 3-2.1" width="100%"/>

- Merge es el comando empleado para fusionar dos ramas

### Apartado 5 Descargar cambios

- 1.1 Editar el archivo README.md desde GitHub:
<img src="/ImagenesProyecto/EditarREADMEdesdeGitHub.png" alt="Captura ejercicio 5-1.1" width="100%"/>


- 1.1.2 Confirmar los cambios en GitHub:
<img src="/ImagenesProyecto/ConfirmarCambiosDesdeGitHub.png" alt="Captura ejercicio 5-1.1.2" width="100%"/>


- 2.1 En tu repositorio local, descarga los cambios hechos en GitHub:
<img src="/ImagenesProyecto/DescargarCambiosHechosEnGitHub.png" alt="Captura ejercicio 5-2.1" width="100%"/>


- 2.2 Comprueba que los cambios hehcos en GitHub ahora aparecen en tu repositorio local:
<img src="/ImagenesProyecto/ComprobarQueLosCambiosDeGHAparecenEnElRepositorioLocalpng.png" alt="Captura ejercicio 5-2.2" width="100%"/>

<img src="/ImagenesProyecto/ComprobacionDeGHEnLocal2.png" alt="Captura ejercicio 5-2.2" width="100%"/>

### Apartado 6 Conflictos

- 1.1 En la rama main, edita el archivo script.js y edita el mensaje:
<img src="/ImagenesProyecto/Conflicto1.png" alt="Captura ejercicio 6-1.1" width="100%"/>


- 1.2 Realiza un commit con este cambio:
<img src="/ImagenesProyecto/Conflicto2.png" alt="Captura ejercicio 6-1.2" width="100%"/>


- 1.3 Cambia a la rama dev y modifica el mismo archivo:
<img src="/ImagenesProyecto/Conflicto3.png" alt="Captura ejercicio 6-1.3" width="100%"/>


- 1.4 Realiza un commit con este cambio:
<img src="/ImagenesProyecto/Conflicto4.png" alt="Captura ejercicio 6-1.4" width="100%"/>


- 2.1 Cambia a la rama main y fusiona dev
<img src="/ImagenesProyecto/ResolverConflicto1.png" alt="Captura ejercicio 6-2.1" width="100%"/>

<img src="/ImagenesProyecto/ResolverConflicto2.png" alt="Captura ejercicio 6-2.1" width="100%"/>




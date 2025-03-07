# Proyecto sobre GIT
## Hecho por Daniel Gracia Calvo - 1ºDAW

### Aparatado 1
### 1.1 Instalación de Git:
![Instalacion](/ImagenesProyecto/Instalacion1.png)
![Instalacion](/ImagenesProyecto/setup.png)
![Instalacion](/ImagenesProyecto/setup2.png)

### 1.2 Configuración de usuario y correo electronico:
![Instalacion](/ImagenesProyecto/configUserYMail.png)

### 1.3 Verificación de la configuración:
![Instalacion](/ImagenesProyecto/VerificarConfig.png)
![Instalacion](/ImagenesProyecto/VerificarConfig2.png)

### Apartado 2 Trabajando con un repositorio local
### 1.1 Crear una carpeta llamada MiPrimerRepositorio_TuNombre:
![Instalacion](/ImagenesProyecto/MiPrimerRepositorio.png)
#### Creo la carpeta MiPrimerRepositorio_DanielGracia y me muevo a ella.

### 1.2 Ejecutar git init dentro de la carpete:
![Instalacion](/ImagenesProyecto/GitInit.png)
#### git init es un comando que sirve para inicializar un nuevo repositorio.

### 1.3 Crear un archivo README.md y escribir una breve descripción:
![Instalacion](/ImagenesProyecto/CrearREADME.png)
#### Con code . git nos abre Visual Studio ya que previamente lo hemos configurado de manera que el VS Code sea nuestro editor de texto. Una vez dentro de él, creamos el archivo README.md con la descripción y el nombre.

### 2.1 Añadir el archivo al área de preparación:
![Instalacion](/ImagenesProyecto/AñadirREADMEaStage.png)
#### Git status: Para ver el estado del repositorio y con Git add “nombre del fichero”: para agregar el fichero README.md a git para que esté en la etapa de stage. 

### 2.2 Realizar el primer commit con el texto "Primer commit: Creación del README":
![Instalacion](/ImagenesProyecto/PrimerCommitREADME.png)

### Apartado 3 Subir un repositorio a GitHub
#### 1.1 Acceder a GitHub y crear un repositorio vacio:
![Instalacion](/ImagenesProyecto//CrearRepositorioGitHub.png)

#### 2.1 En la terminal, añadir el repositorio remoto:
![Instalacion](/ImagenesProyecto/VincularRepositorioLocalConGitHub.png)

#### Git remote: nos sirve para que nosotros podamos indicar si vamos a tener un servidor remoto en el cual vamos a poder subir los cambios
#### Add origin: Le indicamos de donde tenemos que ir a obtener nuestro codigo y a donde tenemos que subir los cambios que nosotros realicemos. 

### 2.2 Subir los cambios al repositorio remoto:
#### Git push: Comando para que nosotros podamos subir nuestros cambios. 
![Instalacion](/ImagenesProyecto/SubirCambiosAGitHub.png)
#### Inicio sesión desde el navegador
![Instalacion](/ImagenesProyecto/ComprobarREADMEenGitHub.png)
#### Compruebo que se ha ejecutado correctamente.

### Apartado 4 Crear una nueva rama
#### 1.1 Crear una nueva rama llamada dev:
![Instalacion](/ImagenesProyecto/CreacionRamaDev.png)
#### Con git branch "nombre-de-la-rama" creamos la nueva rama
![Instalacion](/ImagenesProyecto/CambiarARamaDev.png)
#### Si utilizamos "git checkout -b "nombre-de-la-rama"", se crea la rama y automaticamente nos mueve a ella.

### 2.1 Crear un script.js:
![Instalacion](/ImagenesProyecto/CrearScriptjs.png)

### 2.2 Añadir y realizar un commit con el archivo script.js:
![Instalacion](/ImagenesProyecto/AñadirYHacerCommitDeScript.png)

### 3.1 Cambia de nuevo a la rama main:
![Instalacion](/ImagenesProyecto/CambiarAMain.png)

### 3.2 Fusionar los cambios de dev y main:
![Instalacion](/ImagenesProyecto/FusionarDevConMain.png)
#### Merge es el comando empleado para fusionar dos ramas

### Apartado 5 Descargar cambios
#### 1.1 Editar el archivo README.md desde GitHub:
![Instalacion](/ImagenesProyecto/EditarREADMEdesdeGitHub.png)

### 1.1.2 Confirmar los cambios en GitHub:
![Instalacion](/ImagenesProyecto/ConfirmarCambiosDesdeGitHub.png)

### 2.1 En tu repositorio local, descarga los cambios hechos en GitHub:
![Instalacion](/ImagenesProyecto/DescargarCambiosHechosEnGitHub.png)

### 2.2 Comprueba que los cambios hehcos en GitHub ahora aparecen en tu repositorio local:
![Instalacion](/ImagenesProyecto/ComprobarQueLosCambiosDeGHAparecenEnElRepositorioLocalpng.png)
![Instalacion](/ImagenesProyecto/ComprobacionDeGHEnLocal2.png)

### Apartado 6 Conflictos
#### 1.1 En la rama main, edita el archivo script.js y edita el mensaje:
![Instalacion](/ImagenesProyecto/Conflicto1.png)

### 1.2 Realiza un commit con este cambio:
![Instalacion](/ImagenesProyecto/Conflicto2.png)

### 1.3 Cambia a la rama dev y modifica el mismo archivo:
![Instalacion](/ImagenesProyecto/Conflicto3.png)

### 1.4 Realiza un commit con este cambio:
![Instalacion](/ImagenesProyecto/Conflicto4.png)

### 2.1 Cambia a la rama main y fusiona dev
![Instalacion](/ImagenesProyecto/ResolverConflicto1.png)
![Instalacion](/ImagenesProyecto/ResolverConflicto2.png)


# Proyecto sobre GIT

## Hecho por Daniel Gracia Calvo - 1ºDAW

### Aparatado 1
- 1.1 Instalación de Git:
https://drive.google.com/uc?export&id=
<img src="https://drive.google.com/uc?export&id=1mFUTUbKBFM8pbrNEquJVVonKJhYyRTqb" alt="Captura ejercicio 1.1" width="100%"/>
<img src="https://drive.google.com/uc?export&id=1nhpkw2nvH2rHGNb_9BPdAmU7P_94CUXr" alt="Captura ejercicio 1.1" width="100%"/>
<img src="https://drive.google.com/uc?export&id=1GZX1GOCPOO4PUoiJAjW59FMRN1gJnV-a" alt="Captura ejercicio 1.1" width="100%"/>


- 1.2 Configuración de usuario y correo electronico:
<img src="https://drive.google.com/uc?export&id=1GZX1GOCPOO4PUoiJAjW59FMRN1gJnV-a" alt="Captura ejercicio 1.2" width="100%"/>


- 1.3 Verificación de la configuración:
<img src="https://drive.google.com/uc?export&id=1h5XTumcbsXWGAP4RP19xQY0RqFnVBjAe" alt="Captura ejercicio 1.3" width="100%"/>
<img src="https://drive.google.com/uc?export&id=1lnig_QW0XTmTIvP8b9aCWEjG_3mF_D9P" alt="Captura ejercicio 1.3" width="100%"/>


### Apartado 2 Trabajando con un repositorio local

- 1.1 Crear una carpeta llamada MiPrimerRepositorio_TuNombre:
<img src="https://drive.google.com/uc?export&id=1EGK_o070SZt3LSqse7zJ4uT41zz8eF1J" alt="Captura ejercicio 2-1.1" width="100%"/>

- Creo la carpeta MiPrimerRepositorio_DanielGracia y me muevo a ella.


- 1.2 Ejecutar git init dentro de la carpete:
<img src="https://drive.google.com/uc?export&id=1sNEAoOqQGrjtCXdZyZEY9rF4y4BYr2JO" alt="Captura ejercicio 2-1.2" width="100%"/>

- git init es un comando que sirve para inicializar un nuevo repositorio.


- 1.3 Crear un archivo README.md y escribir una breve descripción:
<img src="https://drive.google.com/uc?export&id=1pwAjxcxvebq_C-gIU73h0BSDmWMS62Xt" alt="Captura ejercicio 2-1.3" width="100%"/>

- Con code . git nos abre Visual Studio ya que previamente lo hemos configurado de manera que el VS Code sea nuestro editor de texto. Una vez dentro de él, creamos el archivo README.md con la descripción y el nombre.


- 2.1 Añadir el archivo al área de preparación:
<img src="https://drive.google.com/uc?export&id=1yFviyPGgPK-6nRKHxtRbdkxZ19aIxbKv" alt="Captura ejercicio 2-2.1" width="100%"/>

- Git status: Para ver el estado del repositorio y con Git add “nombre del fichero”: para agregar el fichero README.md a git para que esté en la etapa de stage. 


- 2.2 Realizar el primer commit con el texto "Primer commit: Creación del README":
<img src="https://drive.google.com/uc?export&id=1HCtTl3ZFSL7mmCtInwW_Oa40DwKmV9q6" alt="Captura ejercicio 2-2.2" width="100%"/>


### Apartado 3 Subir un repositorio a GitHub

- 1.1 Acceder a GitHub y crear un repositorio vacio:
<img src="https://drive.google.com/uc?export&id=1MAaQDND2ED6tQiKM-bXOr-7u64PaHBQC" alt="Captura ejercicio 3-1.1" width="100%"/>


- 2.1 En la terminal, añadir el repositorio remoto:
<img src="https://drive.google.com/uc?export&id=1b4rxJ_WK9fDJek09_-CAL_vK59twpgF-" alt="Captura ejercicio 3-2.1" width="100%"/>

- Git remote: nos sirve para que nosotros podamos indicar si vamos a tener un servidor remoto en el cual vamos a poder subir los cambios
- Add origin: Le indicamos de donde tenemos que ir a obtener nuestro codigo y a donde tenemos que subir los cambios que nosotros realicemos. 


- 2.2 Subir los cambios al repositorio remoto:
- Git push: Comando para que nosotros podamos subir nuestros cambios. 
<img src="https://drive.google.com/uc?export&id=1uBbhXVj0ysbluR9D4MUANGsVgDrHIgO8" alt="Captura ejercicio 3-2.2" width="100%"/>

- Inicio sesión desde el navegador
<img src="https://drive.google.com/uc?export&id=1D2vzqx2JkPBOQSkO2XzPVJ7QlZqTq_7-" alt="Captura ejercicio 3-2.2" width="100%"/>

- Compruebo que se ha ejecutado correctamente.


### Apartado 4 Crear una nueva rama

- 1.1 Crear una nueva rama llamada dev:
<img src="https://drive.google.com/uc?export&id=1IYwKyJ5JdAHh9mPFrtKCbcpImZ4DO6nX" alt="Captura ejercicio 4-1.1" width="100%"/>

- Con git branch "nombre-de-la-rama" creamos la nueva rama
<img src="https://drive.google.com/uc?export&id=1Ngt4GDSJQfDtl8Gq-jmr_oOuJET7Q8Mh" alt="Captura ejercicio 4-1.1" width="100%"/>

- Si utilizamos "git checkout -b "nombre-de-la-rama"", se crea la rama y automaticamente nos mueve a ella.


- 2.1 Crear un script.js:
<img src="https://drive.google.com/uc?export&id=1nvs8965lDe54f9iN45X3yExyqumo3agF" alt="Captura ejercicio 4-2.1" width="100%"/>


- 2.2 Añadir y realizar un commit con el archivo script.js:
<img src="https://drive.google.com/uc?export&id=1Wy2NNj9c7TWhEUO5jJ-gB4W0iF9Rhh_Y" alt="Captura ejercicio 4-2.2" width="100%"/>


- 3.1 Cambia de nuevo a la rama main:
<img src="https://drive.google.com/uc?export&id=11EzZM3PwbpZUZ70UAXuVm4ubZuwCB0YU" alt="Captura ejercicio 4-3.1" width="100%"/>


- 3.2 Fusionar los cambios de dev y main:
<img src="https://drive.google.com/uc?export&id=1iVmk3esrIVd1KchBoF6Sgpdzx5oykJbv" alt="Captura ejercicio 3-2.1" width="100%"/>

- Merge es el comando empleado para fusionar dos ramas


### Apartado 5 Descargar cambios

- 1.1 Editar el archivo README.md desde GitHub:
<img src="https://drive.google.com/uc?export&id=1UrjwndjzBt5NJNOo3siApsCOS4CRzR-o" alt="Captura ejercicio 5-1.1" width="100%"/>


- 1.1.2 Confirmar los cambios en GitHub:
<img src="https://drive.google.com/uc?export&id=1XUMe2-DOYE3piwYeGYW5yApaFcIFsc8y" alt="Captura ejercicio 5-1.1.2" width="100%"/>


- 2.1 En tu repositorio local, descarga los cambios hechos en GitHub:
<img src="https://drive.google.com/uc?export&id=1EgC0pPTsaBYfA6XtVaQTaoD_7-zyedUu" alt="Captura ejercicio 5-2.1" width="100%"/>


- 2.2 Comprueba que los cambios hehcos en GitHub ahora aparecen en tu repositorio local:
<img src="https://drive.google.com/uc?export&id=1DAsfYqWgwKKokyX_pM7t_kSRRbpSMUDb" alt="Captura ejercicio 5-2.2" width="100%"/>

<img src="https://drive.google.com/uc?export&id=1VUI5l_LKoozM4jfBAQeN4CbiuGOd25VI" alt="Captura ejercicio 5-2.2" width="100%"/>


### Apartado 6 Conflictos

- 1.1 En la rama main, edita el archivo script.js y edita el mensaje:
<img src="https://drive.google.com/uc?export&id=1RnXPU35KoxdnbZB9JNOWp616LIsE7ePe" alt="Captura ejercicio 6-1.1" width="100%"/>


- 1.2 Realiza un commit con este cambio:
<img src="https://drive.google.com/uc?export&id=1i23hHt6xDoKzvutg-FZSfgjRl8fciifD" alt="Captura ejercicio 6-1.2" width="100%"/>


- 1.3 Cambia a la rama dev y modifica el mismo archivo:
<img src="https://drive.google.com/uc?export&id=1kaCLH4aXR7IBq_3DjP6FpjFEdotRGmxM" alt="Captura ejercicio 6-1.3" width="100%"/>


- 1.4 Realiza un commit con este cambio:
<img src="https://drive.google.com/uc?export&id=1qBSd7iD6H-kykB3FxuW4rkCGN0DiHhhU" alt="Captura ejercicio 6-1.4" width="100%"/>


- 2.1 Cambia a la rama main y fusiona dev
<img src="https://drive.google.com/uc?export&id=1-WQfsV96WZK7wksHDAmCp3FMeWhG4ddD" alt="Captura ejercicio 6-2.1" width="100%"/>

<img src="https://drive.google.com/uc?export&id=1A8vpBVV83lVgwrd9tEtOesYfnlI1__BG" alt="Captura ejercicio 6-2.1" width="100%"/>

- 2.2 Resuelve el conflicto manualmente editando el archivo script.js y elige qué versión mantener (o  combina ambas).
<img src="https://drive.google.com/uc?export&id=1m4vlnj4976GTB0VwjUpFvB7-d_o4Ygzx" alt="Captura ejercicio 6-2.2" width="100%"/>

Para resolver este conflicto solo hará falta editar el archivo:
<img src="https://drive.google.com/uc?export&id=1MsLb_kbiAQKILRmOpyKHYhzi_JsrklbT" alt="Captura ejercicio 6-2.2" width="100%"/>

- 2.3 Añadir el archivo y hacer commit
<img src="https://drive.google.com/uc?export&id=1MzohvyD5eOzwaT8UHX7KrCOuZb_4PN6u" alt="Captura ejercicio 6-2.3" width="100%"/>


### Apartado 7. Investigación sobre colaboración en equipo con Git y GitHub
- Contenido subido en el archivo `/colaboracion.md`


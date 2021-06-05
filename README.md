![logotipo](static/media/diabetes.jpg)
# **SIRCODI** :drop_of_blood: :medical_symbol: :argentina:
 ## *Sistema de Registro y Control para Personas con Diabetes.* 
 Este es un Proyecto del tipo Web-App o API Realizado para el Curso de "Programador Python".
 
 
# **Proyecto** :technologist:
 - **Número** --> 2do Proyecto
 - **Tipo** --> Aplicación Web - WebApp - REST API
 - **Lenguaje Backend Utilizado** --> Python
 - **Curso** --> Programador Python 
 - **Carrera** --> Desarrollador Python
 - **Institución Educativa** --> Inove Coding School
 
 
 # **Librería y Módulos Utilizados** :books: :point_right:
 - **Flask** ---> microframework
 - **sqlite3** ---> DB - Data Base
 - **matplotlib**
 - **seaborn**
 - **numpy**
 - **traceback**
 - **io**
 - **logging**
 - **os**
 - **datetime**
 - **configparser**
 
 
 # **Pre-requisitos** 📋
Para poder ejecutar esta aplicación, será necesario tener instalada la versión 3.6 de Python o superior. También es necesario incluir varios módulos.
Recomendamos antes de descargar el repositorio, realizar los siguientes pasos:

```
pip3 install pip -U --upgrade
pip3 install numpy
pip3  install matplotlib
pip3 install -U seaborn
pip3 install -U Flask
```
 
 
 # **Para que el programa funcione correctamente:** :point_right:
 #### *Se debe Bajar los siguientes módulos del repositorio:*
 1. ```app.py``` (Programa Principal)
 2. ```diabetes.py``` (Módulo/Librería que Contiene varias funciones utilizadas para el manejo de la DB)
 3. ```analitycs.py``` (Módulo/Librería que Contiene varias funciones utilizadas para el filtrado y ploteado de la información)
 4. ```config.py``` (Módulo/Librería que Contiene la función para la manipulación del archivo config.ini)
 5. ```config.ini``` (Archivo de Configuración imprescindible para que funcione el programa.)
 6. ```schema.sql``` (Archivo que permite crear las tablas de la DB)
 7. Carpeta ```templates``` (Contiene todos los archivos .html)
 8. Carpeta ```static``` (Contiene las carpetas: ```media``` donde están alojadas las imágenes ```style``` donde están alojados los archivos .css
 
 
 # **Descripción** :page_facing_up:
 Como bien lo aclara el título principal, es un sistema registro y control para aquellas personas con Diabetes.
 El Registro se realiza a través de un formulario donde se le pedirá al usuario/paciente ingresar los siguientes datos: Nombre Completo, 
 Edad, DNI, Sexo Biológico y finalmente el Nivel de Azúcar en Sangre estando en Ayuna.
 Una vez realizado esto y enviado la información, el paciente y/o el médico en cuestión, podrían realizar un monitoreo de los registros mediante
 gráficos y tablas.
 Además permite mostrar un gráfico comparativo de las personas registradas según grupo etario y sexo biológico.
 
 
 # **Modos de Uso** 🔧⚙️
Descargue el repositorio en su pc y abra el proyecto en su editor de código, luego ejecute el archivo ```app.py```. La aplicación crea un servidor local en la dirección http://127.0.0.1:5000/ en donde tendremos alojado el frontend de nuestra aplicación. Las direcciones para acceder a las páginas de la aplicación son:

- http://127.0.0.1:5000/          # Página principal que lo guiará para el uso de la WebApp.
- http://127.0.0.1:5000/formulario # Página en donde podremos ingresar los datos para ser enviados y luego cargados en la DB.
- http://127.0.0.1:5000/niveles/tabla   # Página que muestra todos los registros realizados en formato tabla HTML.
- http://127.0.0.1:5000/niveles/api   # Página que muestra el dataset en formato JSON de los registros realizados --> Útil para Desarrolladores
- http://127.0.0.1:5000/comparativa   # Página que muestra los gráficos de comparaciones de la cantidad de personas según grupo etario y sexo biológico.
- http://127.0.0.1:5000/info   # Página que muestra información y descripción del funcionamiento de la página.
 
 
# **Autor** ✒️
:octocat: **Torres Molina, Emmanuel Oscar** 
 
 
# **Contacto** :e-mail: :point_down:
 - ***email:*** emmaotm@gmail.com
 - ***Mis Otros Repositorios*** --> [Click](https://github.com/eotorresmolina?tab=repositories)
 

# **Versión y Última Actualización** :heavy_check_mark:
 - **Versión:** 1.1
 - **Última Actualización:** 23-12-2020


# **Licencia** 📄 :balance_scale:
Este proyecto tiene un propósito meramente académico y con fines de práctica. Es por ello que no existe garantía en su implementación debido a que se trata de una demostración de uso gratuito que aún está en desarrollo. 


# **Consulta y/o Problemas** :question:
  Ante Cualquier mal funcionamiento del Programa y/o consultas acerca del uso del mismo pueden mandarme un mensaje al mail que más arriba se detalla.
  
  Muchas Gracias por tomarte el tiempo de ver el repositorio y haber llegado hasta acá.
  
  Emmanuel.

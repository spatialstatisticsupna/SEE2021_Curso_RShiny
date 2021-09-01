# Material del curso R-Shiny (SEE 2021)

Este repositorio contiene el programa y el material del curso precongreso ["Aplicación web R-Shiny para el análisis espacial y espacio-temporal de datos de área con aplicaciones en epidemiología (SSTCDapp)"](https://www.reunionanualsee.org/index.php?go=pre_congreso)


## Table of contents

- [Programa](#Programa)
- [Registro e instalación SSTCDapp](#Registro-e-instalación-SSTCDapp)
- [Material del curso](#material-del-curso)


# Programa

- **Docentes**: Aritz Adin (aritz.adin@unavarra.es) y Jaione Etxeberria (jaione.etxeberria@unavarra.es)

- **Día y hora**: 7 de septiembre de 16:00 a 20:00

- **Aula y ubicación**: Aula 17. Facultad de CC. Económicas y Empresariales, 24007 León. ([enlace Google Maps](https://www.google.es/maps/place/42%C2%B036'46.2%22N+5%C2%B033'44.1%22W/@42.6126066,-5.5629022,201m/data=!3m1!1e3!4m6!3m5!1s0xd379a7ff187d675:0x7a47dc49c8111680!7e2!8m2!3d42.6128416!4d-5.5622608?hl=es))

- **Programa detallado**
  - 16:00-17:00
    - Introducción a la representación cartográfica de enfermedades.
    - Breve incursión en modelos que incorporan dependencia espacial y espacio temporal.
    - Presentación de la herramienta web interactiva SSTCDapp y registro.
  - 17:00-17:40
    - Ejemplo 1. Análisis espacial de los riesgos de mortalidad por cáncer de labio en Escocia.
  - 17:40-18:00 Pausa café
  - 18:00-19:45 
    - Ejemplo 2. Análisis espacial de las tasas de mortalidad por cáncer de mama en España.
    - Ejemplo 3. Análisis espacio-temporal de las tasas de mortalidad por cáncer de mama en España.
  - 18:00-19:45 
    - Comentarios, feedback y cierre del curso.


# Registro e instalación SSTCDapp

- **SSTCDapp** es una aplicación web interactiva desarrollada con [*Shiny*](https://shiny.rstudio.com/) para el análisis espacial y espacio-temporal de datos de área (*lattice data*), con un enfoque particular en el campo de la representación cartográfica de enfermedades (*disease mapping* en inglés). El ajuste de los modelos se basa en técnica de inferencia Bayesiana INLA (*integrated nested Laplace approximation*) a través de la libreria [**R-INLA**](https://www.r-inla.org/).

- A diferencia de otros programas utilizados en disease mapping, la aplicación SSTCDapp facilita el ajuste de modelos estadísticos complejos a usuarios no expertos sin necesidad de instalar ningún software en sus propios ordenadores, ya que todos los análisis y cálculos se realizan en un potente servidor remoto.

- Cada nuevo usuario debe registrarse en la aplicación por primera vez a través del enlace https://emi-sstcdapp.unavarra.es/. Una vez introducidos los datos requeridos, se le enviará una contraseña a la dirección de correo electrónico del usuario.

- La contraseña es necesaria para iniciar sesión en la aplicación SSTCDapp y crear una cuenta personal. De esta manera, el usuario podrá enviar los modelos para que se ejecuten en servidor remoto y recopilar los resultados una vez hayan finalizado los cálculos. 

- La aplicación utiliza conexiones SSH para la transferencia de datos al servidor remoto cuando se ajusta al modelo INLA. Ningún usuario tiene acceso a los datos y resultados de cualquier otro usuario, y los archivos de datos cargados por los usuarios se eliminan automáticamente de la aplicación una vez que se han desconectado. 

- También está disponible una **versión de escritorio** con el código fuente de la aplicación que se ejecutará localmente si es necesario, lo que garantiza la confidencialidad de los datos. Para instalar esta versión local, se debe descargar el archivo .zip ubicado en la pestaña *Desktop version* del menú izquierdo de la aplicación y seguir las instrucciones del archivo [README.html](https://emi-sstcdapp.unavarra.es/Curso_SEE2021/README.html).


# Material del curso

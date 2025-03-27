# Users-Creation-Admin-Google
Este proyecto consta de un HTML que proyecta un formulario en la web pidiendo datos de un usuario, en este caso un alumno de un centro. Al enviar los datos se procesan y se envian en formato string al App Scripts de Google mediante un enlace, que es la implementación del Api de Google. 

Cuando los datos llegan al Script, se procesan, se limpian (se quitan espacios, caràcteres especiales...), incluso se juntan o separan paràmetros (por ejemplo los apellidos). 
Una vez los datos tienen el formato necesario, hay funciones de creación de cohort según su curso, nivel y grupo; creación de contraseña aleatoria con requisitos mínimos; generación de un ID según nombre, apellido y si es necesàrio asignación de un número; generación de curso según el año que es y por último, creación del usuario con todos los datos enviados desde el HTML y generados en estas últimas funciones, en el centro de administración de Google.

Funcional.

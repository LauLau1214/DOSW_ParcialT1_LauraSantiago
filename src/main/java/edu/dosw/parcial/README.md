
# Diagrama de contexto

![Diagrama de contexto](../../../../../../docs/uml/DiagramaContexto.png)


# Patrones de diseño

1. Chain of Reponsability 

El tipo de este patron es de comportamiento.
Este patron puede aplicarse porque el proceso de lo que tenemos que hacer es una solicitud que hace el usuario, despues de realizar la solicitud
se pasa a la parte de validacion para poder verificar si se acepta la solicitud y se procesa o no se acepta y se le hace saber al usuario.




# Requerimientos del sistema

**FUNCIONALES**

1. El sistema debe permitir al usuario realizar la solicitud 
2. El sistema debe realizar la verificacion de una o mas solicitudes (Command)
3. El sistema de generar un registro de la solicitud para evitar duplicados.

**NO FUNCIONALES**

4. El sistema debe te usar conexion
5. El sistema debe de proteger los datos de los usuarios.
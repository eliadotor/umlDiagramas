#Elia Dotor Puente - UML 

##E05-01 Ejercicio UML 1 

###Empresa-empleado-cliente

Creamos un diagrama de clases de una empresa, sus empleados y sus clientes.
Es importante tener en cuenta que tanto la *clase Empleado* como la *clase Cliente*
heredan de la *clase Persona*.  

A su vez, un **Empleado** puede ser directivo por lo que creamos la *clase Directivo*
o subordinado de otro empleado. 

La clase empleado tiene una *relación reflexiva*, es decir, consigo misma.

La relación entre *Empleado* y *Empresa* es de **composición* ya que no pueden existir empleados si no existe una empresa.  
 
Mientras que la relación entre *Cliente* y *Empresa* es de **agregación** porque en este caso el cliente no depende de la existencia de la empresa.


________________________________________________________________________________________

[Prácticas UML Elia Dotor Puente](https://github.com/eliadotor/uml)
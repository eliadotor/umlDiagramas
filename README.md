#Elia Dotor Puente - UML 

##E05-01 Ejercicio UML 1 

###Empresa-empleado-cliente

Creamos un diagrama de clases de una empresa, sus empleados y sus clientes.
Es importante tener en cuenta que tanto la *clase Empleado* como la *clase Cliente*
heredan de la *clase Persona*.  

A su vez, un **Empleado** puede ser directivo por lo que creamos la *clase Directivo*
o subordinado de otro empleado. 

La clase empleado tiene una *relación reflexiva*, es decir, consigo misma.

La relación entre *Empleado* y *Empresa* es de **composición** ya que no pueden existir empleados si no existe una empresa.  
 
Mientras que la relación entre *Cliente* y *Empresa* es de **agregación** porque en este caso el cliente no depende de la existencia de la empresa.


________________________________________________________________________________________

##E05-02 Ejercicio UML 2

###Biblioteca

Creamos un diagrama de clases de una biblioteca. En el tendremos la *clase Libro*, la *clase Autor*, 
la *clase Copia*, la *clase Lector*, la *clase multa* y la *clase préstamo*.

En este diagrama todas las relaciones son de *asociación*, excepto la de préstamo con *lector* y *copia* que es una relación de *dependencia*. No existirián préstamos si no hubiese copias de los libros y lectores.  

Tenemos que crear dos tipos *enumerados*, uno para el género del libro y otro para el estado del ejemplar, en los que vamos a especificar los diferentes valores que pueden tomar. Una vez que se han definido, se van a utilizar como el tipo de un atributo, igual que un tipo de dato.
________________________________________________________________________________________



[Prácticas UML Elia Dotor Puente](https://github.com/eliadotor/uml)
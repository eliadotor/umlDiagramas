E05-01 Ejercicio UML 1
======================

Empresa-empleado-cliente
------------------------

<!--Elia Dotor Puente-->


``` mermaid
      classDiagram
      Persona <|-- Empleado
      Persona <|-- Cliente
      Cliente "0..*" --o "1..*" Empresa : cliente
      Empleado <|-- Directivo
      Empleado "1..*" --* "1" Empresa : empleado
      Directivo "0..*" -- "0..*" Empleado : subordinado

      class Persona{
        -nombre : String
        -edad : integer
        +mostrar() void
      }

      class Empleado{
        -sueldoBruto : double
        +calcularSalarioNeto() double
      }

      class Cliente{
        -telefono : String
      }

      class Directivo{
        -categoria : String
      }

      class Empresa{
        -nopmbre : String
      }
```
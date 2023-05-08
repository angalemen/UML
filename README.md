#Diagrama de Flujo

#Animales

#El siguiente diagrama representa la estructura de clase de los tipos de animales de la aplicacion.

```Java

class Perro extends Animal {
   String raza;
   String morder(cosa : String):String{
      return null;
   }
  
  @Override
  void sonar(){}
}

abstract class Animal {
    void alimentar(){} 
    
    abstract void sonar()
}
    
```
  
```mermaid
classDiagram
  
class Perro {  
   +morder(cosa: String): String
}
  
class Animal{
   +void sonar()*
}
   
Animal <|-- Perro
 ```

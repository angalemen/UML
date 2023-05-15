#Diagrama de Flujo

#Animales

#El siguiente diagrama representa la estructura de clase de los tipos de animales de la aplicacion.

```Java

class Camiseta extends Ropa {
   String raza;
   String morder(cosa : String):String{
      return null;
   }
  
  @Override
  void sonar(){}
}

abstract class Ropa {
    void alimentar(){} 
    
    abstract void camiseta()
}
    
```
  
```mermaid
classDiagram
  
class Camiseta {  
   +morder(cosa: String): String
}
  
class Ropa{
   +void sonar()*
}
   
Animal <|-- Camiseta.
 ```

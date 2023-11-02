
Diagrama de objetos:

@startuml

object "Luz" as Luz1 {
  intensidad: Alta
  dirección: Vertical
}

object "Objeto" as Objeto1 {
  altura: 2 metros
  posición: Centro
}

object "Sombra" as Sombra1 {
  longitud: 3 metros
  dirección: Este
}

Luz1 --> Objeto1 : Ilumina
Objeto1 --> Sombra1 : Proyecta

@enduml

Diagrama de clases:

@startuml

class Luz {
  intensidad 
  dirección 
}

class Objeto {
  altura 
  posición 
}

class Sombra {
  longitud 
  dirección 
}

Luz -- Objeto 
Objeto -- Sombra 

@enduml

@startuml

class objeto {}

class formaObjeto{}
class formaSombra{}
class luz {}

objeto "bloquea" - luz
luz "provoca" .. sombra
objeto "proyecta" -- sombra
formaObjeto"define" -- sombra
objeto "tiene" -- formaObjeto
sombra "con" -- formaSombra
formaObjeto "en funcion de" .. formaSombra

@enduml

Imagen:



![image](https://github.com/juanjoc711/23-24-idsw1/assets/114565115/0d108b45-6fa5-4d8e-ac45-5cd97ef77100)




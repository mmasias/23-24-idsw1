Codigo del modelo:
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
www.plantuml.com/plantuml/png/PP3D3S8m38NlcSBolPsX6t3e16dgIaMf3Vb10iJkrA5H8-7Z-pw_H1vYiY7bpHlZl8qHPBfI4dX_Qh18sEobf7lOPADiKx2dwFDBrtIE4foyt3DPX4wfKGDlGHxYzgpl8PQAgYjwaalgTvKrp-DCoyhKqhgPLZf0uvkV1EY4JpR-zG8ImvBPhS8mK_bPg-up4C_bI5y0

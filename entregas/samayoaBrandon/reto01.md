@startuml

class Universidad {

`  `+ nombre: Uneatlantico

}

class Facultad {

`  `+ nombre: String

}

class Departamento {

`  `+ nombre: String

}

class Profesor {

`  `+ nombre: String

`  `+ apellido: String

}

class Estudiante {

`  `+ nombre: String

`  `+ apellido: String

}

class Curso {

`  `+ codigo: String

`  `+ nombre: String

}

class Asignatura {

`  `+ codigo: String

`  `+ nombre: String

}

Universidad -- Facultad : tiene

Facultad -- Departamento : tiene

Facultad -- Estudiante : tiene

Departamento -- Profesor : tiene

Departamento -- Curso : ofrece

Profesor -- Asignatura : imparte

Estudiante -- Curso : inscrito en

Curso -- Asignatura : incluye

@enduml

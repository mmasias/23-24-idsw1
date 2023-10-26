# RUP: Proceso Unificado de Desarrollo

## ¿Por qué?

En el mundo del desarrollo de software, la complejidad y la necesidad de adaptarse a cambios constantes son retos habituales. Para abordar estos desafíos, es esencial contar con un **marco de trabajo estructurado** que guíe a los equipos a través del proceso de desarrollo, minimizando los riesgos y maximizando la eficiencia y calidad del producto final. 

Aquí es donde entra en juego una metodología como RUP (Rational Unified Process), diseñada para proporcionar un enfoque disciplinado, pero adaptable, a la ingeniería de software.

## ¿Qué?

RUP es un proceso de desarrollo software basado en componentes

|||
|-|-|
Basado en componentes|El sistema es construido por componentes de software interconectados y bien definidos vía sus interfaces
Dirigido por Casos de Uso|
Centrado en la arquitectura|
Iterativo e incremental|

### Dirigido por casos de uso

* Usados como un artefacto primordial para establecer el comportamiento deseado del sistema y para comunicar este comportamiento entre los implicados en el sistema.
* Forma sistemática e intuitiva para capturar los requisitos funcionales, adecuadamente representados para los usuarios, clientes y desarrolladores
* Primera entrada para el análisis, diseño, implementación y pruebas del sistema, incluyendo la creación, verificación y validación de la arquitectura del sistema.
* Facilitan el mantenimiento de la aplicación gracias a la trazabilidad y ortogonalidad con las clases.
* Facilitan la planificación de actividades de los roles.

### Centrado en la arquitectura

La arquitectura del sistema es usada como un artefacto primordial para la conceptualización, construcción, gestión y evolución del sistema bajo desarrollo.

Esta clave incluye:

* Disciplina de Análisis
* Disciplina de Diseño
* Disciplina de Implementación
* Disciplina de Pruebas

### Iterativo e incremental

|Iterativo|Incremental|
|-|-|
El proceso involucra un flujo de entregas ejecutables|El proceso involucra la integración continua de la arquitectura del sistema para producir con cada nueva entrega un incremento que aumenta a otra anterior

Esto incluye:

* Disciplina de Gestión del Proyecto
* Disciplina de Entorno
* Disciplina de Configuración y Gestión de Cambios
* Disciplina de Despliegue

## ¿Para qué?

|||
|-|-|
Gestionar riesgos|Mediante la entrega iterativa, los riesgos se identifican y resuelven progresivamente, evitando sorpresas al final del desarrollo.
Mejorar la calidad del software|Al enfocarse en la arquitectura y permitir revisiones constantes, se asegura la calidad y robustez del software.
Facilitar la adaptación a cambios|La naturaleza iterativa permite incorporar cambios en los requisitos o en la tecnología de manera más flexible y controlada.
Claridad en el proceso|Proporciona una guía clara para cada etapa del desarrollo, definiendo qué debe realizarse, por quién y cuándo.

## ¿Cómo?

### Roles

<div align=center>

![](/imagenes/modelosUML/RUProles.svg)

</div>

### Fases



### Iteraciones


### Actividades

|Disciplina|Actividades|
|-|-|
Disciplina de Requisitos|
||1. Encontrar Actores y Casos de Uso
||2. Priorizar Casos de Uso
||3. Detallar Caso de Uso
||4. Estructurar Casos de Uso
||5. Prototipar Interfaz de Usuario
Disciplina de Análisis
||6. Análisis de la Arquitectura
||7. Análisis de Caso de Uso
||8. Análisis de Clase
||9. Análisis de Paquete
Disciplina de Diseño
||10. Diseño de la Arquitectura
||11. Diseño de Caso de Uso
||12. Diseño de Clase
||13. Diseño de Paquete
Disciplina de Implementación
||14. Implementar la Arquitectura
||15. Integración de Sistemas
||16. Implementar Clase
||17. Pruebas Unitarias
||18. Implementar Subsistema
Disciplina de Pruebas
||19. Planificar Pruebas
||20. Diseñar Pruebas
||21. Implementar Pruebas
||22. Realizar Pruebas de Integración
||23. Realizar Pruebas de Sistemas
||24. Evaluar Pruebas

<div align=center>

![](/imagenes/modelosUML/RUPdisciplinas.svg)

</div>
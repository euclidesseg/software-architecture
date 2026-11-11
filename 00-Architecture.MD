# Arquitectura  de software
Es el diseño de alto nivel de un sistema informático, definen cómo se organizan sus componentes,
como se relacionan entre si y cuales son las reglas o principios que organizan su calidad, escalabilidad y mantenimiento.

## Tipos de arquitectura y patronoes comunes
1. Monolítica: Todo el código y la base de datos se encuentran en un solo bloque o proyecto
es facil de iniciar pero dificil de escalar a gran tamño

2. Microservicios: La aplicación se divide en servicios pequeños e independientes que se comunican a través de APIs
facilita escalar partes específicas.

3. En capas (N-Tier): separa el sistema en niveles con responsabilidades únicas.
por ejemplo, presentacion, lógica de negocio y datos.

4. Orientada a eventos (EDA): Los componentes reaccionan a cambios de estado o sucesos en tiempo real.

4. Clean architecture (Arquitectura limpia): Prioriza que el nuecleo de la lógica de negocios sea independiente de frameworks, bases de datos o interfaces externas.

### Atributos

Escalabilidad
Mantenibilidad
Rendimiento
Tolerancia a Fallos

## Diagramas de arquitectura UML
### Vista Lógica
Se enfoca en los requisitos funcionales
y en los objetos del sistema representados comunmente con diagramas de clases UML3

### Vista de procesos
Aborda los requisitos no funcionales como rendimiento y disponibilidad mostrando la ejecucion y orden
de los procesos

## Aspectos de desarrollo y despliegue
### Vista de desarrollo
Describe la estructura jerárquica del software, lenguajes bibliotecas y gestión del proyecto.
### Vista física
Muestra cómo los componentes se despliegan en hardware o nodosm, representado con diagramas
de despliegue UML.

## Escenarios y propósito comun
Escenarios: casos de uso que ilustran como las vistas trabajan juntas para cumplir las tareas del usuario
Propósito común: Todas las vistas se alinean para cumplir con las capacidades
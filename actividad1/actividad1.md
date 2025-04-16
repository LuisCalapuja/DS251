# Parte 1: Introducción  DevOps

## Pregunta 1:
### ¿Por qué surgió la necesidad de DevOps en el desarrollo de software?
- Se quería superar los modelos tradicionales de desarrollo de software, que consistia en equipos aislados y ciclos largos de actualización. DevOps busca crear equipos multifuncionales que aseguren la calidad y colaboración continua. Esto permite acortar ciclos de desarrollo del software.

## Pregunta 2:
### Explica cómo la falta de comunicación y coordinación entre los equipos de desarrollo y operaciones en el pasado llevó a la creación de DevOps.
- El flujo de labores de los equipos de desarrollo, eran secuenciales y enfocados en un solo objetivo sin tener en cuenta otros objetivos del proyecto lo que a la larga, de haber cambios, estos resultarían en grandes modificaciones en el código, retrocediendo etapas y volviendo a empezar de cero en el peor de los casos. Esta falta de coordinación llevaba a un mayor tiempo en el desarrollo de los proyectos.
- Otro punto es el de falta de comunicación entre los equipos de trabajo lo cual no permitía una colaboración eficaz en los avances del proyecto, pasando por alto la detección de errores lo cual se hacia en una etapa más avanzada del proyecto. Esto a su vez llevaría a conflictos entre los grupos de trabajo por la responsabilidad de las fallas.
- Para superar estos conflictos se crea DevOps.


## Pregunta 3:
### Describe cómo el principio de mejora continua impacta tanto en los aspectos técnicos como en los culturales de una organización.
- La mejora continua abarca desde las capacitación y desarrollo profesional, con lo cual cuidamos y potenciamos los recursos humanos de la organización, comprometiéndolos con la visión y misión de la organización. En el aspecto técnico la mejora la gestión de incidencias y la documentación de procesos facilita la trazabilidad del proyecto. 

## Pregunta 4:
### ¿Qué significa que DevOps no se trata solo de herramientas, individuos o procesos?
- DevOps plantea una nueva cultura organizacional, orientada a la colaboración y responsabilidad compartida, lo cual busca mejorar la eficiencia y el ambiente de trabajo. Eliminando las barreras de comunicación entre los equipos, se busca una mayor flujo de ideas, que conlleven a soluciones creativas y de fácil adaptabilidad en el mercado.


## Pregunta 5:
### Según el texto, ¿cómo contribuyen los equipos autónomos y multifuncionales a una implementación exitosa de DevOps?
- Los equipos multifuncionales abarcan equipos de distintos departamentos, lo cual da más puntos de vista para la resolución de problemas, esto mejora no solo la calidad de las respuestas sino que también acelera el proceso de desarrollo. Los equipos autónomos, que tienen independencia en su área de trabajo, pueden proponer ideas innovadoras en la resolución de problemas sin estar limitados por las directrices de la misma organización.

# Parte 2: DevSecOps e IaC

1. **¿Qué significa "desplazar a la izquierda" en el contexto de DevSecOps y por qué es importante?**  
- Al decir "desplazar a la izquierda" se hace referencia a que la seguridad debe implementarse desde las etapas más tempranas del desarrollo del software. Al trabajar en la seguridad desde el principio se facilita la detección de vulnerabilidades, lo cual lleva a la reducción de violaciones de seguridad en la etapa de producción.

2. **Explica cómo IaC mejora la consistencia y escalabilidad en la gestión de infraestructuras.**  
- La infraestructura como código mejora la consistencia al ser empaquetada en contenedores con Docker, donde se guardan las aplicaciones con sus dependencias facilitando su portabilidad y consistencia en los despliegues. La gestión a gran escala de estos contenedores nos lo permite Kubernetes, lo que nos permite que sea escalable, con alta disponibilidad y despliegue controlado.

3. **¿Cuál es la diferencia entre monitoreo y observabilidad? ¿Por qué es crucial la observabilidad en sistemas complejos?**  
- El monitoreo se enfoca en las métricas del sistema, en su recolecion, procesamiento y análisis. La observabilidad trata de un registro de logs y la trazabilidad, en concreto, las modificaciones del sistema que pueden convertirse en problemas para el usuario final.

4. **¿Cómo puede la experiencia del desarrollador impactar el éxito de DevOps en una organización?**  
- La experiencia del desarrollador radica en las buenas practicas que este ejerza sobre el código del proyecto. Los commits que realiza cada que actualiza o modifica el código, para una correcta trazabilidad. Los archivos de texto donde se detalla los cambios y el por qué fueron realizados, todo esto con el fin de una comunicación fluida con el resto de desarrolladores que contribuyen al proyecto, además de los futuros desarrolladores que vayan sumándose al mismo.

5. **Describe cómo InnerSource puede ayudar a reducir silos dentro de una organización.**  
- Innersource tiene la particularidad de aplicar practicas de código abierto dentro de una organización. Es decir toda la organización tiene acceso al código y puede contribuir en su desarrollo, esto a su vez conserva el software para uso interno. Innersource aumenta la visibilidad del desarrollo del código, fortalece la colaboración de colaboradores en la organización y rompe los silos.

6. **¿Qué rol juega la ingeniería de plataformas en mejorar la eficiencia y la experiencia del desarrollador?** 
- La ingeniería de plataformas es un enfoque que puede acelerar la entrega de aplicaciones y el ritmo de producción. Esto lo hace proporcionando capacidades de autoservicio con operaciones de infraestructura automatizada.  
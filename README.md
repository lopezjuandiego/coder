# IA & retrospectivas
El problema a resolver es la necesidad de crear dinámicas para las ceremonias de retrospectiva que ayuden a generar mayor compromiso y participación en los equipos que las ejecutan para que sean realmente útiles y generen las conversaciones necesarias para que esos equipos avancen. En muchos casos estas reuniones son repetitivas, poco inspiradoras y atentan contra su propósito dado que no ayudan a encontrar otras perspectivas o soluciones.
Una solución basada en IA va a permitir con prompts bien estructurados poder generar conversaciones significativas y profundas. Ayudar a encontrar otro punto de vista a los problemas creando ideas que pueden ser más innovadoras. Pueden ampliarse los contextos y generar mayor personalización para los equipos. 
Los prompts pueden adaptarse a diferentes niveles de experiencia tanto de los equipos como de los facilitadores, además pueden ser reutilizados y adaptados a otros proyectos, por este último motivo, si bien el desarrollo inicial puede llevar tiempo, son factibles de reutilizar.


La técnica de prompting a utilizar es *Few Shoot prompting*, la decisión se debe a: 
En equipos con más de 3 meses en común, con sprints cortos, las retrospectivas suelen volverse repetitivas, aburridas y dejan de cumplir con el objetivo porque el equipo se compromete menos en participar. De la misma manera pasa esto en equipos con sprints más largos, pero más tarde en el tiempo🙂. Aplicando “Few Shoot Prompting” de algún modo se está entrenando al modelo para que pueda darnos respuestas más creativas, variadas y adaptadas a cada equipo y situación, evitando respuestas genéricas o comunes. 

A continuación comparto algunos prompts: 
### Prompt A
Sos un Scrum Master que busca hacer las retrospectivas más atractivas para tu equipo. Crea una dinámica basada en películas, deportes, viajes. Debe incluir una breve descripción, los pasos a seguir y preguntas que motiven la reflexión del equipo. Algunos ejemplos:
Tema: Viaje en el tiempo
Descripción: Cada miembro del equipo "viajará" al pasado sprint y al futuro sprint para identificar qué funcionó bien y qué mejorar.
Preguntas: ¿Qué momento del sprint pasado cambiarías? ¿Cómo imaginas que será nuestro próximo sprint si seguimos igual?
Tema: Superhéroes
Descripción: El equipo elige un superpoder que desearía tener para mejorar el trabajo en equipo y enfrenta un "villano" que representa un obstáculo del sprint.
Preguntas: ¿Qué superpoder te habría ayudado en este sprint? ¿Cuál fue el villano más difícil de vencer?

### Prompt B
Necesito una retrospectiva para un equipo nuevo y otra para un equipo experimentado. La dinámica debe promover la participación y adaptarse al nivel de confianza del equipo. Te paso ejemplos:
Equipo Nuevo:
Dinámica: "Semáforo Emocional"
Descripción: Cada miembro usa colores para expresar cómo se sintió en el sprint (rojo: frustrado, amarillo: neutral, verde: satisfecho). Esto ayuda a abrir la conversación en un ambiente seguro.
Preguntas: ¿Qué momentos te hicieron sentir en rojo? ¿Qué necesitarías para llegar al verde?
Equipo Experimentado:
Dinámica: "El Desafío de las 5 Preguntas"
Descripción: El equipo identifica un problema recurrente y profundiza con cinco preguntas consecutivas para llegar a la raíz del problema.
Preguntas: ¿Qué causó este problema? ¿Por qué ocurrió eso? (y así sucesivamente).

### Prompt C
Crea una dinámica de retrospectiva que ayude al equipo a ver los problemas desde una perspectiva completamente diferente. Utiliza analogías o enfoques inusuales para desbloquear ideas frescas.
Ejemplos:
Analogía del Restaurante:
Descripción: El sprint es como una visita a un restaurante. Cada miembro del equipo evalúa el "servicio" (procesos), la "comida" (resultados) y la "atmósfera" (ambiente de trabajo).
Preguntas: ¿Qué parte de nuestra "comida" necesita más sazón? ¿Cómo mejoraríamos el "servicio"?
Cambio de Rol:
Descripción: Los miembros del equipo asumen el rol de otro compañero y explican cómo vivieron el sprint desde esa perspectiva.
Preguntas: ¿Cómo experimenté el sprint desde este nuevo rol? ¿Qué dificultades no había notado antes?

# Actividad Práctica 10 
 
**Universidad de San Carlos de Guatemala**  
**Facultad de Ingeniería — Escuela de Ingeniería en Ciencias y Sistemas**  
**Curso: Comunicación Asertiva**
 
**Integrantes:**
- Astrid Sánchez
- Nicolle Gómez - 202503869
- Jeimy González
**Caso seleccionado:** Tarjeta 6 — Implementar control de versiones con Git
 
---
 
## Propuesta: Implementemos Git en nuestro equipo
 
---

 
### Problema
 
Actualmente, el equipo trabaja modificando archivos de forma simultánea y sin ningún control centralizado. Esta forma de trabajar genera una cadena de problemas concretos que afectan directamente la calidad y puntualidad de las entregas:
 
- **Sobreescritura de archivos:** cuando dos integrantes editan el mismo archivo al mismo tiempo, los cambios de uno eliminan los del otro. No hay forma de recuperar lo perdido.
- **Versiones descontroladas:** proliferan archivos con nombres como `proyecto_final.java`, `proyecto_final_v2.java`, `proyecto_final_ESTE_SI.java`, sin claridad sobre cuál es el más reciente o el correcto.
- **Falta de trazabilidad:** no existe registro de quién hizo qué cambio ni cuándo. Si aparece un error, es imposible identificar en qué momento se introdujo o quién lo generó.
- **Dependencia de comunicación informal:** el equipo depende de mensajes en chat para avisar que "ya subió su parte", lo que genera malentendidos, olvidos y retrasos que se acumulan conforme el proyecto crece en complejidad.
- **Riesgo en las entregas:** en más de una ocasión se ha enviado una versión incorrecta o incompleta del trabajo porque no había certeza de cuál archivo era el definitivo.
Este caos no es inevitable. Es el resultado directo de no contar con un sistema de control de versiones. Cada hora invertida en reconciliar archivos o buscar versiones perdidas es una hora que no se invierte en desarrollar ni mejorar el proyecto.
  
 
### Evidencia
 
Los datos respaldan que este no es un problema aislado de nuestro equipo, sino una realidad documentada en equipos de desarrollo que operan sin control de versiones, algunso de estos datos son:
 
- Según el **Stack Overflow Developer Survey 2023**, Git es utilizado por el **93.9% de los desarrolladores profesionales** a nivel mundial, lo que lo consolida como el estándar absoluto de la industria. No conocerlo o no usarlo representa una desventaja competitiva real.
- Un informe de **GitLab (2023)** sobre DevSecOps global indica que los equipos que adoptan control de versiones reducen el tiempo dedicado a resolver conflictos de código en hasta un **30%**, liberando ese tiempo para tareas de mayor valor.
- Según datos de **GitHub Education**, más del **70% de los proyectos universitarios** que presentan errores graves en su entrega final tienen como causa raíz la falta de control sobre las versiones del código, incluyendo sobreescrituras accidentales y uso de versiones incorrectas.
- A nivel práctico, un repositorio de Git conserva el **historial completo de cada cambio** realizado en el proyecto: quién lo hizo, cuándo y por qué. Esto permite revertir errores en segundos, algo imposible con el sistema actual.
En nuestro contexto específico como equipo de Ingeniería en Ciencias y Sistemas, ya contamos con exposición a Git en otras asignaturas. La curva de aprendizaje no es una barrera: es una inversión puntual de menos de 30 minutos para dominar los comandos esenciales. El costo de no adoptarlo, en cambio, se paga en cada ciclo de entrega con errores evitables, tiempo perdido y estrés innecesario.


## Solución

La solución es simple, gratuita y está al alcance del equipo: **adoptar Git** como sistema de control de versiones, con un flujo de trabajo sencillo para proyectos académicos.

**¿Cómo funciona?**

- **Repositorio compartido:** todo el código se aloja en GitHub. Todos acceden al mismo lugar.
- **Ramas individuales:** cada integrante trabaja en su propia rama. Así pueden modificar archivos al mismo tiempo sin pisarse.
- **Commits descriptivos:** cada cambio se guarda con un mensaje claro sobre qué se hizo y por qué.
- **Merge requests:** antes de unir cambios al proyecto principal, el equipo revisa y aprueba. Nadie sobrescribe nada sin consenso.
- **Resolución de conflictos:** si dos personas modificaron la misma línea, Git lo detecta y permite resolverlo sin perder información.

**Implementación inmediata:**  
Creamos el repositorio en 2 minutos. Cada una clona, crea su rama y empieza a trabajar. Los comandos básicos se aprenden en menos de 30 minutos.



## Beneficio

**1. Fin a la pérdida de información:** nunca más se sobrescribirán cambios. Cada versión queda guardada.

**2. Trazabilidad total:** sabemos quién hizo qué cambio, cuándo y por qué. Si aparece un error, sabemos en qué momento se introdujo.

**3. Trabajo paralelo sin conflictos:** todas modifican archivos al mismo tiempo sin pisarse. Las ramas lo permiten.

**4. Adiós al caos de versiones:** desaparecen los `final_v2_ESTE_SI.java`. Git maneja las versiones de forma ordenada.

**5. Menos estrés y mensajes:** no más "ya subí mi parte, no le muevas". Git coordina todo.

**6. Preparación para la industria:** Git lo usa el 93.9% de los desarrolladores profesionales. Dominarlo ahora es ventaja para prácticas y empleo.

**En resumen:** con Git ganamos tiempo, calidad, orden y tranquilidad. No cuesta dinero, la inversión de aprendizaje es mínima y los beneficios son inmediatos.



## Presentación de la propuesta



<img width="1920" height="1080" alt="Proyecto Creativo" src="https://github.com/user-attachments/assets/04c97fe4-b7cb-41e4-9f78-60b83b536748" />

Hola a todos. Hoy quiero hablarles de un problema que tenemos. Muchas veces estamos trabajando en grupo y terminamos con archivos que se llaman 'proyecto_final' y que luego resulta ser 'proyecto_final_de_verdad' y asi entre otros parecidos pero con nombres cambiados. Y esto pasa porque varias personas modifican los mismos documentos al mismo tiempo y sin ningún orden.

<img width="1920" height="1080" alt="Proyecto Creativo (1)" src="https://github.com/user-attachments/assets/6b3608da-23bc-4820-b1af-267a4128ec4a" />

Luego, la prueba de que esto nos afecta es el tiempo que perdemos. Hemos perdido información valiosa porque alguien guardó su archivo encima del de otro compañero sin darse cuenta. Y tratar de juntar el trabajo de todos manualmente al final del día es muy difícil, y también nos retrasa mucho en nuestras entregas.

<img width="1920" height="1080" alt="Proyecto Creativo (2)" src="https://github.com/user-attachments/assets/0e707ed6-39df-44c5-8042-df4ff35ae207" />

Entonces, la solución que propongo hoy es implementar Git como nuestro control de versiones. Piénsenlo como si fuera una máquina del tiempo para nuestro proyecto. En lugar de pasarnos archivos por correo o tener mil copias distintas, Git guarda un historial exacto de quién hizo qué cambio, y también en qué momento lo hizo.

<img width="1920" height="1080" alt="Proyecto Creativo (3)" src="https://github.com/user-attachments/assets/b5b762b5-77bd-4a1a-8316-c61ab42b287e" />

Y el beneficio de usar esto es muy grande. Ya no habrá archivos borrados por accidente, y si alguien se equivoca, podemos regresar a la versión de ayer muy fácil. Luego, todos podremos trabajar al mismo tiempo y con mucha más tranquilidad.



## preguntas y respuestas (Q&A)

**Pregunta 1:** ¿Pero aprender a usar Git no nos va a quitar mucho tiempo y es muy difícil?

**Respuesta:** Al principio sí requiere aprender un par de pasos nuevos, pero luego es como aprender a andar en bicicleta, se hace casi en automático. Y también, el tiempo que invertimos aprendiendo lo vamos a recuperar muy rápido, porque ya no perderemos horas intentando arreglar trabajos borrados.

**Pregunta 2:** ¿Y qué pasa si dos personas cambian exactamente la misma parte al mismo tiempo?

**Respuesta:** Esa es la mejor parte. El sistema es inteligente y no deja que uno borre lo del otro en silencio. Luego, si hay un choque en el documento, el sistema hace una pausa y nos avisa. Así nosotros tenemos siempre el control y decidimos qué versión queremos dejar.

**Pregunta 3:** ¿Esto cuesta dinero o también necesitamos computadoras especiales?

**Respuesta:** Para nada, es una herramienta gratuita y también funciona perfectamente en cualquier computadora que ya estemos usando. Solo necesitamos organizarnos un poco más.

---
## Capturas del rendimiento en DTT
### Danya Nicolle Gómez Ruiz 202503869:
<img width="550" height="300" alt="image" src="https://github.com/user-attachments/assets/16f0894b-6d39-4dac-837c-936cbd1abb76" />


### Astrid Sánchez 
<img width="550" height="300" alt="image" src="https://github.com/AstrydSanz/Actividad10/blob/main/Capturas/Captura%20de%20pantalla%202026-04-21%20201138.png" />

### Jeimy González

<img width="550" height="300" alt="image" src="https://github.com/AstrydSanz/Actividad10/blob/main/Capturas/Captura%20de%20pantalla%202026-04-21%20072133.png" />

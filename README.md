*Nota: Actualmente se encuentra en construcción.*

# Panel introducción a la seguridad

La idea de este documento es combatir un poco la desinformación, remover ambigüedades, despejar dudas, y crear un espacio en el que podamos referenciar a futuro como un lugar de partida para cualquier persona que quiera introducirse en la seguridad informática.

La propuesta va más allá de *enseñar* cómo comenzar técnicamente, sino de orientar un poco a todos los que se encuentran perdidos y no saben por cómo armarse un camino.

# Disclaimer 
Toda la información contenida en este documento, es una recopilación personal abierta, por lo tanto es subjetiva, y no está sujeta a ninguna verdad absoluta.

# ¿Quiénes somos?
Amigos, colegas, conocidos; un grupo de personas apasionadas de la seguridad informática, que viven de ello (en su mayoría), y comparten desde la empatía con todos los que están en esta situación de iniciación al aprendizaje o desconcierto, ya que hemos estado allí.

Andrés Riancho
Federico Pacheco
Gustavo M. Sorondo
María Jośe Erquiaga
Martin Gallo
Matías A. Ré Medina
Nicolás Waisman
Sebastián Bortnik
Sebastián García
Sheila Berta
Verónica Valeros

# FAQ
## ¿Qué es la seguridad informática?

También conocida como ciberseguridad, está definida de la siguiente manera por ISACA (Information Systems Audit and Control Association ):
*Protección de activos de información, a través del tratamiento de amenazas que ponen en riesgo la información que es procesada, almacenada y transportada por los sistemas de información que se encuentran interconectados"*.


## ¿Cuáles son las grandes ramas de la seginfo?

A nivel organizacional, se podría separar en, pero no limitada a:

**Defensiva (Blue team)**
Equipo seguridad interno que defiende una empresa de atacantes externos (o Red Teams). A diferencia del típico equipo que se encarga de asegurar sistemas acorde a estándares, o para que sean *compliance*[1], estos están en constante vigilia protegiendo a la organización.

Una parte que no está *tan* explotada, al menos en las pequeñas empresas o es considerada poco popular.


**Ofensiva (Red team)**
Tiene fama de ser más divertida. Son equipos externos, que las organizaciones contratan para testear la efectividad de sus sistemas. Lo hacen imitando las técnicas de un atacante.

La mayoría de las empresas de seguridad que se pueden contratar realizan este tipo de servicios.

Muchos lo confunden con Vulnerability Assesment o Penetration Testing, que tienen sus diferencias (ver sección xx)

## ¿Qué cosa no es?
Muchas de las cosas que salen en las noticias, incluyendo las increíbles visuales que tienen algunas películas.

Al final del documento hay buenas recomendaciones por si quieren mirar algo que se asemeje un poco más a la realidad ;)

## No arranqué de jóven, ¿es tarde para mí?
No hace falta haber hackeado la NASA a los 12 años para poder dedicarte a la seguridad informática el resto de tu vida, ni tener un background *sólido* para comenzar, ni una edad en particular.

Hay que tener ganas, y saber organizarse con el tiempo. Entendemos que todas las situaciones son distintas, pero hey, nadie los corre probablemente, así que a disfrutar que es un proceso hermoso, y si no lo está siendo para tí, ojalá que este documento te motive un poco :)

## Quiero hackear, pero no se qué estudiar, ni dónde, ¿qué hago?
No está tan claro el camino, no te preocupes. No hay un lugar específico a donde ir así como los hay en otro tipo de *carreras laborales* que está más trazado. Si bien existen carreras que son complementarias, no es el único camino a seguir.

Elegí lo que te quede más cómodo, recomendamos hacerlo de una manera progresiva para no frustrarte con cosas complicadas desde un principio, y a partir de que se van ganando más conocimientos también se va entendiendo un poco más el panorama, para ese entonces seguramente encontraste algo que te apasionó, y sino revisitar este artículo de ser necesario para volver a orientarse.

## ¿Qué es ser hacker?
Según la RAE, existen dos definiciones:
- Pirata informático
- Persona experta en el manejo de computadoras, que se ocupa de la seguridad de los sistemas y de desarrollar técnicas de mejora.

No reconocemos la primera definición, y seguimos sin entender por qué la segunda fue incorporada sin desplazar a la primera. 

Un hacker NO es un pirata informático.

Entendemos por *hacker* a una palabra que no está sólo arraigada a la seguridad informática, sino a la habilidad para poder encontrar funcionalidades en *cosas* que originalmente no fueron destinadas para ese uso, más allá del contexto.

Un ejemplo muy común del hacking, que no necesariamente está solapado con utilizar herramientas tecnológicas, es la ingeniería social. Hay perfiles laborales que se dedicaron a estudiar comportamiento humano, psicología, persuasión, y sin utilizar la informática obtienen información sensible.

_[Introducir más ejemplos]_

## Lo que me da la universidad no es lo que quiero, ¿qué hago?
Si bien creés que no te da lo que querés de manera inmediata porque en las prácticas no estás sacudiendo exploits y apoderándote de las máquinas de tus compañeros (nota: no lo hagas jamás sin su consentimiento), las carreras de sistemas tienen un aporte y una formación que es indiscutible.

Más allá de la universidad, y el título, si aprovechás cada materia, y la pivoteás para el lado de la seguridad, podés aprender un montón, e ir haciendo en paralelo tu propia carrera complementaria con lo que ves ahí. Y, si además conseguís algún titular que te segundee para que en los trabajos prácticos haya la flexibilidad suficiente para poder incoporporar este complemento del que hablamos, muchísimo mejor.

## ¿Creen que es necesario crear una carrera de seguridad informática?
No nos parece indispensable, ya que como hablamos, las maneras de aprender son varias. Sin embargo estaría bueno sí, al menos como puerta de entrada, y para salir un poco de que la seguridad sólo esté en posgrados o maestrías únicamente (*).

No nos gustaría que en el caso de que exista, se utilice para diferenciar a quienes lo tengan de quienes no, como especie de discriminación, más en un ambiente tan autodidacta como en el que nos encontramos.

(*) Ha habido propuestas pero no han tenido éxito porque en su momento no ha existido el flujo necesario como para que se justifique crear una. Para ello es importante comenzar con optativas, cursos, orientadas a seguridad, empezar a generar más movimiento en el ambiente, hasta que eventualmente termine en algo más extenso que justifique incluirse en un plan académico.


## ¿Son recomendables las certificaciones?
Dependiendo del tipo de certificado. No son algo *necesario*, ni un requisito para poder aprender. Algunas empresas los exigen por cuestiones burocráticas o clientes para demandar una compliance[ref] de algún tipo.

Pero una certificación no te enseña, simplemente son distintos mecanismos de verificación para validar lo que uno ya sabe hasta es momento.

Es más fácil hablar de las que nos paresen relevantes, que las que no. Reconocemos que la certificación OSCP es muy interesante, ya que envuelve aplicar en práctica un montón de conocimientos para apoderarse de distintas máquinas a través de distintas técnicas en un plazo de 24hs. A diferencia de otras que solamente son preguntas teóricas multiple choice, por ejemplo.

## ¿Cuál es la mejor manera de aprender?
Lo importante acá nos parece diferenciar el hecho de aprender algo y eventualmente tener la capacidad para demostrarlo.

Lo que está claro es que uno lo podría hacer en la universidad, estudiando para una certificación, de material de internet o experimentando. ¡La que a vos te sirva!

Es un campo muy versátil y en crecimiento, en el que ningún perfil es incorrecto.

*Sean responsables de sus estudios*, si sienten que la universidad ya no lo es, no gasten energía en culparla, busquen en otro lado, si sienten que necesitan una estructura porque solos no pueden, vayan a la universidad, si ambos caminos no sirvieron sigan buscando que eventualmente lo van a encontrar, y quién sabe, tal vez abran las puertas para darle camino a mucha gente que estuvo en su misma situación.

## ¿Que sería lo básico que necesito para la seguridad informática?

No queremos cerrarnos a decir que hay un básico, porque estaríamos cayendo en una generalización y es sumamente abarcativa. Está claro que mientras más conocimientos poséan mejor van a poder encarar cada situación.

No hay ningún curso mágico de 6 meses que les vaya a dar lo básico para cubrir un todo. Sí existen cursos y diplomaturas que les pueden dar un paneo general para ayudarlos a empezar a definir este camino propio del que tanto hablamos, en el cual te terminarás dando cuenta que para poder hacer ingeniería inversa (reverse engineering) necesitás arrancar como base a programar, entender como funcionan los lenguajes de programación, compiladores, y assembler, por ejemplo.

Hay un montón de material online, de cursos gratuitos en distintas plataformas (ver guías y cursos recomendados) que son útiles como puntos de partida y pueden brindar un lindo insight.

## ¿Qué perfiles se encuentran en el mundo laboral?
Gente recibida, con posgrados, doctorados, haciendo la universidad, que dejó la universidad, que nunca fué a la universidad y estudió sólo por su cuenta, que no terminó el colegio, y más.

La diversidad, en general, es algo que aporta positivamente en los equipos de trabajo. Mientras más diversidad, más puntos de vista y perspectivas distintas se pueden traer a la mesa. Y digamos que el hacking se trata un poco de eso, de tener la capacidad de poder observar las cosas desde distintos lugares.

En resumen, hay de todo :)


## ¿Por qué hay más foco en lo ofensivo que en lo defensivo?
Atacar es más divertido que defender, y defender es muchísimo más difícil que atacar.

Desarrollar una técnica de defensa es también muchísimo más difícil de probar que funciona porque es simplemente esperar hasta que alguien la pueda romper.

También hay muchas investigaciones atacando mecanismos de seguridad, pero que no llegaron a ser una charla, posiblemente ya que no lograron finalmente romperlos, y hay una verdad y es que en algunas conferencias es más atractivo mostrar casos en los que sí.

## ¿Cómo ven el futuro de la seguridad informática?

Hace años en Argentina muchos clientes venían a nosotros cuando ya les había ocurrido un problema, 0 proactividad. Luego de ser auditados otros tenían esa sensación de seguridad que les duraba años, o hasta que volvieran a tener un inconveniente. Con el tiempo fueron contratándonos de maneras más periódicas, al comenzar cada proyecto, e incluso ofrecernos como servicios como parte de los suyos.

Hoy en día, luego de campañas de concientización, en el incremento en los ataques informáticos, y muchas variables más, hemos llegado al punto en el que algunas de esas empresas que mencionábamos, hoy en día tienen equipos de *Blue team* y/o conducen auditorías regularmente.

## Si recién empiezo, ¿es un desperdicio ir a una conferencia?
En absoluto. Incluso nosotros con años de experiencia, siempre nos encontramos con muchas charlas de las cuales no entendemos su mayoría, pero porque también esa es la idea, que los disertantes expongan investigaciones interesantes, muchas de ellas super específicas, a las que dedicaron gran mayor parte de su tiempo, y contra alguien que se dedicó de lleno a un tema en específico no hay punto de comparación.

Recomendamos ir a todas las conferencias que les parezcan interesantes, y disfrutarlas. No frustrarse si no entienden, porque no están diseñadas para que todos entiendan todo.

Algo positivo que tiene en genral este ambiente, por lo menos en Argentina, es que la mayoría de nosotros siempre tenemos un momento para charlar con interesados, así que si tienen dudas las pueden despejar en persona con el mismo disertante de la charla.


## Red Team, Pentesting, ¿son todos lo mismo?

Penetration Test, Vulnerability Assessment, y Red Team Assessment no son sinónimos, aunque a veces algunas empresas los utilicen intercambiadamente.

**Penetration testing**, más conocido como pentesting, es básicamente encontrar vulnerbilidades y errores de configuración, conocidos, y tratar de explotarlos para obtener la mayor cantidad de accesos posibles en un determinado tiempo.

**Red Team Assessment** es similar al pentesting, sólo que el objetivo no es conseguir más accesos ni vulnerabilidades, sino obtener información sensible de la manera más sigilosa posible, entendiendo cómo la empresa responde a este tipo de situaciones y reacciona ante ellas. Se incluyen técnicas de ingeniería social, seguridad física, hacking de dispositivos electrónicos, biométricos, wireless y más.

**Vulnerability Assesment** se podría interpretar como la actividad que engloba encontrar vulnerabilidades en los sistemas, y asesorar a la empresa en cuestión sobre cómo prevenir futuros ataques que las exploten.

## Más allá de las ramas, ¿qué cosas se pueden hacer?

Se podrían definir muchos perfiles laborales, y la verdad que ninguno está limitado a solamente su área, generalmente para trabajar en cada área necesitás un poco de expertise en las otras. Es decir, si estás analizando una aplicación móvil compleja en Objective C (por decir algún lenguaje), también vas a necesitar entender posiblemente algo de critografía y protocolos de internet para poder hacer un buen trabajo.

Algunas de las categorías, en inglés, son las siguientes:
- Networking: aplicar seguridad en redes, protocolos.
- Application: aplicar seguridad en la capa de aplicación.
- Mobile: hacer análisis de aplicaciones móbiles.
- Malware/Spyware Analysis: analizar comportamientos de malware.
- Risk Audit/Management: análisis de riesgos.
- Forensics: técnicas forenses.
- Penetration Testing: tests de penetración.
- Systems security (user level, kernel, os): aplicación de técnicas de seguridad a nivel sistemas operativos, cloud.
- Crypyography: testear, crear o romper seguridad relacionada a algoritmos criptográficos o sistemas de cifrados.

## ¿Qué acercamiento se tiene desde la seguridad con respecto a la educación que se brinda hoy en día?

De a poco vamos *ganando terreno*, mediante concientización. Estamos inculcando de a poco que la seguridad es algo que se aplica como parte del proceso de desarrollo de las aplicaciones, sistemas, y no como algo que viene después.

Es algo que eventualmente con el tiempo va a llegar.

# Conclusión

Cada uno arma su propio camino, no hay una forma única de hacer esto. Esto es muy nuevo para todo el mundo. Así como nosotros tomamos decisiones en ese momento para ver como podíamos ir mejorando, ustedes deberán hacer lo mismo.

Hay que entender que probablemente uno no venga con una pasión adentro, está bueno utilizar la curiosidad como motor, probando, buscando, experimentando. Es cuestión de 

Hackeá tu propio camino al hacking :)

# Recomendaciones generales
- Comenzá progresivamente. No te frustres, todos estuvimos ahí, y eso que te está costando ya lo vas a lograr.
- No te compares, no tiene sentido.
- Aprendé idiomas, particularmente inglés ya que en él está el mayor caudal de información del cual aprendimos. Por suerte hay bastante material en español también, pero muchas son traducciones.
- No pongan afuera la responsabilidad de aprender, está en ustedes. Busquen lo que les sirva, y si no sirve, se cambia.
- Conocete a vos mismo, entendé que te sirve, si estudiar en tu casa, asistir a eventos, asistir a educación pública/privada, lo que sea que te sirva está bien.

# Más información

## Glosario
- exploit:
- compliance:

## Cursos gratuitos
Coursera
edX
Cybrary
CodeAcademy
Udemy
Stanford
Cardiff
MIT OpenCourseware

## Guías en español
[Guía de auto-estudio para la escritura de exploits - Fundación Sadosky](https://fundacion-sadosky.github.io/guia-escritura-exploits)

## Lecturas recomendadas
Hackers (libro)

## Podcasts

## Instituciones que tratan la seguridad
UNICEN Tandil - Introducción a la seguridad informática (optativa)


## Películas & Series
- Mr. Robot: La serie que históricamente tiene más contenido real del mundo del hacking.
- Hackers: Un clásico.


# Referencias

[Penetration Test vs. Red Team Assessment: The Age Old Debate of Pirates vs. Ninjas Continues](https://blog.rapid7.com/2016/06/23/penetration-testing-vs-red-teaming-the-age-old-debate-of-pirates-vs-ninja-continues/)

# Proving grounds (mentorship)

*Insertar: Descripción del sistema de mentoring*

*Insertar: Formulario*

# Salida laboral

Proving grounds
ekodating
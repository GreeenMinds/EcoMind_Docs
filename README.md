#	EcoMind by GreenMinds
<div align="center">
<br><br>
<img src="https://marketingperu.beglobal.biz/wp-content/uploads/2025/01/logo-upc-png-transparente-1.png" alt="drawing" width="100"/> <br><br>

**Universidad Peruana de Ciencias Aplicadas (UPC)**

Facultad de Ingeniería
Carrera de Ingeniería de Software

Ciclo 2026-10 <br><br>

Desarrollo de Aplicaciones Open Source

NRC:11990

Profesor: Juan Antonio Flores Moroco <br><br>

Informe del Trabajo Final

Startup: GreenMinds

Product: EcoMind <br><br>

Integrantes:

u20241e158 - Aponte Pablo, Isabel Luisa

u202410678 - Astocondor Bazan, Alejandra Isabel

u202410254 - Dulanto Espino, Leo César

u202412316 - Diaz Martinez, Alexther Kamil

u202418655 - Laura Acosta, Victor Jhosuef


Abril 2026

</div>

# Registro de Versiones del Informe

| Version | Fecha | Autor | Descripción de modificación |
| -------- | -------- | -------- | -------- |
| 1.0.0    | 4/04/26     | Alejandra Astocondor     | initial commit <br> docs: añadir estructura del proyecto |
| 1.0.0    | 13/04/26     | Alejandra Astocondor <br> Isabel Aponte    | docs: agregar antecedentes y problematica <br> docs: añadir Lean UX Problem Statement <br> docs: Añadir segmento objetivo  |
| 1.1.0    | 16/04/26     | Leo Dulanto   | docs: agregar Lean UX assumptions <br> docs: agregar Lean UX Hypothesis Statements <br> docs: agregar Lean UX Canvas <br> docs: agregar analisis competitivo <br> docs: agregar diseño de entrevistas |

# Projet Report Collaboration Insights

Project Report URL: https://github.com/GreeenMinds/EcoMind_Docs

# Tabla de contenidos

**Capítulo I: Introducción**  
1.1. [Startup Profile](#11-startup-profile)  
1.1.1. [Descripción del startup](#111-descripción-del-startup)  
1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

1.2. [Solution Profile](#12-solution-profile)  
1.2.1. [Antecedentes y problemática](#121-antecedentes-y-problemática)  
1.2.2. [Lean UX Process](#122-lean-ux-process)  
1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)  
1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)  
1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)  

1.3. [Segmentos objetivo](#13-segmentos-objetivo)  


**Capítulo II: Requirements Elicitation & Analysis**  
2.1. [Competidores](#21-competidores)  
2.1.1. [Análisis competitivo](#211-análisis-competitivo)  
2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  

2.2. [Entrevistas](#22-entrevistas)  
2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)  
2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)  
2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)  

2.3. [Needfinding](#23-needfinding)  
2.3.1. [User Personas](#231-user-personas)  
2.3.2. [User Task Matrix](#232-user-task-matrix)  
2.3.3. [User Journey Mapping](#233-user-journey-mapping)  
2.3.4. [Empathy Mapping](#234-empathy-mapping)  

2.4. [Big Picture EventStorming](#24-big-picture-eventstorming)  
2.5. [Ubiquitous Language](#25-ubiquitous-language)  


**Capítulo III: Requirements Specification**  
3.1. [User Stories](#31-user-stories)  
3.2. [Impact Mapping](#32-impact-mapping)  
3.3. [Product Backlog](#33-product-backlog)  


**Capítulo IV: Product Design**  
4.1. [Style Guidelines](#41-style-guidelines)  
4.1.1. [General Style Guidelines](#411-general-style-guidelines)  
4.1.2. [Web Style Guidelines](#412-web-style-guidelines)  

4.2. [Information Architecture](#42-information-architecture)  
4.2.1. [Organization Systems](#421-organization-systems)  
4.2.2. [Labeling Systems](#422-labeling-systems)  
4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
4.2.4. [Searching Systems](#424-searching-systems)  
4.2.5. [Navigation Systems](#425-navigation-systems)  

4.3. [Landing Page UI Design](#43-landing-page-ui-design)  
4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe)  
4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up)  

4.4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)  
4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)  
4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
4.4.3. [Web Applications Mock-ups](#443-web-applications-mock-ups)  
4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)  

4.5. [Web Applications Prototyping](#45-web-applications-prototyping)  

4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
4.6.1. [Design-Level EventStorming](#461-design-level-eventstorming)  
4.6.2. [Software Architecture Context Diagram](#462-software-architecture-context-diagram)  
4.6.3. [Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)  
4.6.4. [Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)  

4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)  
4.7.1. [Class Diagrams](#471-class-diagrams)  

4.8. [Database Design](#48-database-design)  
4.8.1. [Database Diagrams](#481-database-diagrams)  


**Capítulo V: Product Implementation, Validation & Deployment**  
5.1. [Software Configuration Management](#51-software-configuration-management)  
5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)  
5.1.2. [Source Code Management](#512-source-code-management)  
5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)  

5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
5.2.1. [Sprint 1](#521-sprint-1)  
5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1)  
5.2.1.2. [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)  
5.2.1.3. [Sprint Backlog 1](#5213-sprint-backlog-1)  
5.2.1.4. [Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)  
5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)  
5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)  
5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)  
5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)  


**Final**  
[Conclusiones](#conclusiones)  
[Recomendaciones](#recomendaciones)  
[Bibliografía](#bibliografía)  
[Anexos](#anexos)

# Student Outcome

| Criterio Especifico | Acciones realizadas | Conclusiones |
| -------- | -------- | -------- |
| Text     | Text     | Text     |


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción del startup

**Nombre de la startup**

GreenMinds

**Descripción**

ECOMIND es una plataforma interactiva que busca fortalecer la conciencia ambiental en escolares a través de la gamificación y dinámicas educativas como retos y juegos prácticos. Su propuesta no solo transmite conocimientos sobre reciclaje, ahorro de agua, eficiencia energética y cuidado del entorno, sino que también busca transformar hábitos cotidianos al involucrar tanto a los estudiantes como a sus familias y comunidades. A diferencia de otras herramientas, funciona en modalidad online y offline, lo que hace accesible en contextos con limitaciones de conectividad y garantiza su alcance en zonas urbanas y rurales.


**Visión**

Posicionarnos en el corto y mediano plazo como la plataforma educativa de referencia en conciencia ambiental para escolares en el Perú, ampliando gradualmente nuestro alcance hacia otras comunidades y paises de la región. Aspiramos a contribuir en la construcción de una generación más consciente, capaz de integrar hábitos sostenibles en su vida cotidiana y de inspirar cambios positivos en su entorno.


**Misión**

Brindar a los escolares una educación ambiental innovadora, accesible y dinámica que convierta el aprendizaje en una experiencia significativa. A través de la gamificación, buscamos que los niños no solo adquieran conocimientos, sino que desarrollen actitudes responsables y prácticas sostenibles que puedan replicar en su vida diaria y en sus entornos familiares y comunitarios.


**Propuesta de Valor**



**Características principales**



### 1.1.2. Perfiles de integrantes del equipo

| Foto | Nombre | Descripción |
| -------- | -------- | -------- |
| <img src="assets/img/team-photos/isabel-photo.jpg" width="150"> | Aponte Pablo, Isabel Luisa (u20241e158) | Estudiante de Ingeniería de Software. Me interesa la programación y el desarrollo de soluciones prácticas. Tengo conocimientos en C++ y otras herramientas tecnólogicas, me caracterizo por ser responsable, organizada y enfocada en el trabajo en equipo. |
| <img src="assets/img/team-photos/ale-photo.jpg" width="150"> | Astocondor Bazan, Alejandra Isabel (U202410678) | Estudiante de Ingeniería de Software, enfocada en el desarrollo de soluciones tecnológicas. Poseo habilidades en programación y diseño digital. Me caracterizo por mi creatividad, responsabilidad y capacidad de adaptación. |
| <img src="assets\img\team-photos\kamil-photo.jpg" width="150"> | Diaz Martinez, Alexther Kamil (U202412316) | Estudiante de ingeniería de software, me gusta programar, tengo conocimiento en C++ y Python, me gustan los desafíos. Mi meta es aplicar mi optimismo y capacidad técnica para desarrollar software que genere un impacto real. |
| <img src="assets/img/team-photos/leo-photo.jpg" width="150"> | Dulanto Espino, Leo César (U202410254) | Estudiante de Ingeniería de Software, con conocimientos en C++, Python y fundamentos de desarrollo web y Java. Me gusta crear soluciones creativas a problemas y apoyar activamente al equipo en los proyectos. |
| <img src="https://cdn.pixabay.com/photo/2015/10/05/22/37/blank-profile-picture-973460_640.png" width="150"> | Laura Acosta, Victor Jhosuef (u202418655) | — |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

La falta de conciencia ambiental constituye un problema que afecta tanto al planeta como a la calidad de vida de las personas, pues provoca contaminación, riesgos para la salud y un uso ineficiente de recursos básicos como el agua y la energía. Este problema se manifiesta principalmente durante la etapa escolar, cuando deberían consolidarse valores y hábitos sostenibles, pero no siempre ocurre porque los aprendizajes en la escuela no encuentran continuidad en el hogar ni respaldo en la comunidad. 

Surge sobre todo en espacios cercanos a los estudiantes, donde las prácticas cotidianas no refuerzan lo enseñado en el aula. Los más afectados son los escolares de educación básica, en quienes la ausencia de una conciencia ambiental sólida limita la adopción de conductas responsables en su vida diaria. 

Entre las causas destacan: la cultura consumista, que promueve la compra y el desecho excesivo; las prioridades económicas y de seguridad que desplazan la preocupación ambiental; y la falta de educación ambiental, que deja a los ciudadanos sin claridad sobre cómo sus acciones diarias contribuyen al deterioro del entorno. 

Esta situación surge porque los conocimientos transmitidos en la escuela no se consolidan en la práctica cotidiana, ya que los hogares y comunidades mantienen hábitos poco sostenibles. Los datos muestran la magnitud del problema: en el Perú, solo el 1,8 % de los residuos municipales generados en 2022 fueron valorizados, reflejando un bajo aprovechamiento de materiales reciclables. Asimismo, en Madre de Dios, un estudio con estudiantes de secundaria reveló que la mayoría presentaba niveles apenas moderados de conciencia y actitudes ambientales, con solo un porcentaje reducido que alcanzó niveles altos o muy adecuados. 

**Aplicación de 5W+2H:** 

**¿Cuál es el problema? (What?)**

La conciencia ambiental puede entenderse como el nivel de conocimientos, actitudes y prácticas que desarrollan los individuos para actuar de manera responsable con el entorno, integrando valores de respeto y cuidado hacia los recursos naturales (Chuliá, 1995). La falta de esta se ha convertido en un problema que, además de afectar nuestro planeta, impacta directamente en la calidad de vida de las personas, ya que genera entornos contaminados, riesgos para la salud y un uso ineficiente de recursos básicos como el agua y la energía. 

**¿Cuándo sucede el problema? (When?)** 

El problema de la falta de conciencia ambiental se manifiesta principalmente durante la etapa escolar. Es en esta fase donde deberían consolidarse actitudes responsables hacia el entorno y prácticas sostenibles que se mantengan a lo largo de la vida. Sin embargo, cuando este proceso no ocurre de manera adecuada, los escolares no desarrollan una conciencia ambiental sólida, lo que se traduce en conductas poco responsables frente al cuidado del medio ambiente en su vida cotidiana. 

**¿Dónde surge el problema? (Where?)** 

El problema de la falta de conciencia ambiental surge principalmente en los espacios de socialización más cercanos a los estudiantes: la escuela, el hogar y la comunidad. Si bien en las instituciones educativas se incluyen contenidos ambientales en el currículo, estos aprendizajes muchas veces no se consolidan porque no encuentran respaldo en el entorno familiar ni en la cultura comunitaria. Según Róger Martinez (2010), “la educación ambiental debe constituir un proceso integral, que juega su papel en todo el entramado de la enseñanza y el aprendizaje” (p. 97). 

**¿A quiénes les sucede el problema? (Who?)** 

El problema de la falta de conciencia ambiental afecta principalmente a los escolares de educación básica, tanto en primaria como en secundaria, quienes se encuentran en una etapa crucial para la formación de valores y hábitos sostenibles. Estos estudiantes, al no desarrollar una conciencia ambiental sólida, tienen mayores dificultades para incorporar prácticas responsables en su vida cotidiana. 

**¿Cuál es la causa del problema? (Why?)** 

Entre las principales causas están: 

**Cultura de consumismo:** se impulsa a las personas a adquirir productos que no responden a necesidades reales, sino a deseos creados por la publicidad y las tendencias sociales. Este patrón de consumo lleva a valorar más la posesión y el estatus que el uso responsable de los recursos, generando hábitos de compra excesiva, desecho rápido y desperdicio (Reyes, 2018). 

**Prioridades económicas/seguridad:** en muchos contextos, especialmente en países en desarrollo, las preocupaciones inmediatas de la población están relacionadas con la estabilidad económica, la generación de ingresos y la seguridad personal. Estas prioridades suelen desplazar la atención hacia el cuidado del medio ambiente, que se percibe como un tema secundario o de largo plazo. 

**Falta de educación ambiental:**  muchos escolares y ciudadanos desconocen cómo sus acciones cotidianas, como el consumo excesivo de agua, la disposición inadecuada de residuos o el uso indiscriminado de plásticos, contribuyen al deterioro del entorno. 

**¿Qué llevo a la persona a llegar a esa situación?** (How) 

La falta de conciencia ambiental es el resultado de un proceso en el que los aprendizajes recibidos en la escuela no logran consolidarse en su vida cotidiana. Aunque en el aula se transmiten conocimientos básicos sobre reciclaje, ahorro de agua y cuidado de los recursos, estos no encuentran continuidad en el hogar ni respaldo en la comunidad, donde persisten hábitos de sobreconsumo y prácticas poco sostenibles. 

**Estadísticas o datos que sustenten la problemática (How much?)** 

En el Perú, la gestión de residuos sólidos evidencia serias limitaciones. Aunque la valorización de residuos municipales pasó de 17 189 toneladas en 2014 a 148 559 toneladas en 2022, este volumen representa apenas el 1,8 % del total generado a nivel nacional (Ministerio del Ambiente, 2024), lo que refleja un bajo nivel de aprovechamiento de materiales reciclables.

**Figura 1**
*Porcentaje de residuos sólidos municipales valorizados con respecto a lo generado según departamento*

<img src="assets/img/figures/image021.png" width="500">

Nota.*Adaptado de Anuario estadístico del sector Ambiente 2023, por el Ministerio del Ambiente, 2023.*

Un estudio realizado en Madre de Dios mostró que el 35,4 % de los estudiantes tenía un nivel moderado de conciencia ambiental, el 28,7 % un nivel alto y solo el 7,2 % alcanzó un nivel muy alto, mientras que un 5,5 % se ubicó en un nivel muy bajo. Respecto a las actitudes proambientales, el 43,7 % presentó niveles parcialmente adecuados y apenas un 3,3 % logró niveles muy adecuados (Estrada, et al. 2022). 

**Figura 2**

*Resultados descriptivos de conciencia ambiental y las actitudes proambientales de los estudiantes de la Institución Educativa Almirante Miguel Grau Seminario de Madre de Dios, Perú.*

<img src="assets/img/figures/image022.png" width="500">

Nota. *Adaptado de Conciencia ambiental y actitudes proambientales en estudiantes de educación secundaria de Madre de Dios, Perú, por Estrada E., 2022.* 

### 1.2.2. Lean UX Process

#### *1.2.2.1. Lean UX Problem Statements*

El proyecto EcoMind propone una aplicación móvil educativa que promueve la conciencia ambiental en niños mediante retos interactivos y actividades familiares. A través de un diseño centrado en el usuario, inclusivo y gamificado, busca convertir el aprendizaje ecológico en una experiencia divertida y cotidiana. Su objetivo es integrar a padres e hijos en un entorno digital que fomente hábitos sostenibles y fortalezca el compromiso con el cuidado del planeta. 

Dentro de las escuelas primarias, se quiere que los estudiantes transformen la educación ambiental en hábitos sostenibles que se practiquen de manera constante en el hogar y la comunidad. no obstante, observamos que lo aprendido en el aula no cuenta con un proceso continuo y verificable que lo enlace con la rutina cotidiana, lo que se refleja en pocas eco acciones fuera de clase y baja permanencia en el tiempo. Aunque en la actualidad existen diversas plataformas y programas de educación ambiental y gamificación, identificamos que la continuidad, especialmente en el hogar y la comunidad, son débiles. Ahí radica la oportunidad que se desea aprovechar: intervenir en esa brecha de continuidad y verificación del comportamiento ambiental. Finalmente, todo ello ocurre bajo restricciones de tiempo pedagógico, brechas de conectividad y acceso a dispositivos. 

¿Como podríamos garantizar esa continuidad y acompañamiento entre escuela, hogar y comunidad, bajo dichas restricciones? 


#### *1.2.2.2. Lean UX Assumptions*

**Assumptions Worksheet**

1. ¿Quién es el usuario? 

Los usuarios principales son: 

Estudiantes de primaria (9–12 años): niños que inician la formación de hábitos ambientales y requieren actividades visuales, breves e interactivas para consolidar lo aprendido en la escuela.

Padres de familia de escolares de primaria: adultos responsables de reforzar y acompañar las prácticas sostenibles en el hogar, asegurando continuidad en las eco-acciones.

2. ¿Dónde encaja nuestro producto en su trabajo o vida? 

La aplicación se integra en la rutina de los escolares tanto en la escuela como en el hogar. Funciona como: 

Recurso educativo en el aula: apoyo a las clases de educación ambiental a través de actividades gamificadas.

Extensión en el hogar: plataforma para completar mini-retos familiares y dar seguimiento a las eco-acciones.

Conexión comunitaria: registro de actividades ambientales que trascienden el aula y se vinculan con la comunidad.

3. ¿Qué problemas tiene nuestro producto que resolver? 

En escolares de primaria: dificultad para trasladar lo aprendido en la escuela a la vida diaria, ya que los contenidos ambientales no siempre se refuerzan en casa o comunidad.

En padres de familia: falta de recursos y estrategias claras para apoyar a los niños en la práctica de hábitos sostenibles dentro del hogar.

En general: ausencia de retroalimentación y medición de impacto que permitan dar continuidad a las eco-acciones.

4. ¿Cuándo y cómo es usado nuestro producto? 

Durante las clases escolares, en sesiones que integren los contenidos ambientales.

En el hogar, como parte de tareas, eco-retos o proyectos familiares.

En la comunidad, registrando prácticas ambientales conjuntas.

El producto puede usarse en cualquier momento y lugar, tanto en modo online como en modo offline con sincronización diferida, asegurando continuidad incluso en contextos de baja conectividad.

5. ¿Qué características son importantes? 

Mini-retos y actividades progresivas adaptadas a escolares y familias.

Gamificación: puntos, insignias y rankings para incentivar la participación conjunta.

Retroalimentación inmediata con reportes visibles para niños y padres.

Modo offline con registro y posterior sincronización de actividades.

Interfaz visual, inclusiva y fácil de usar, adecuada para niños y adultos.

Reportes de impacto que midan el avance de eco-acciones individuales y colectivas.

6. ¿Cómo debería verse nuestro producto y cómo comportarse?

La aplicación debe presentar un diseño colorido, dinámico e intuitivo, con ilustraciones y personajes que conecten con los escolares y resulten comprensibles para los padres. La navegación debe ser clara, sencilla y atractiva, sin elementos que distraigan del aprendizaje.

En términos de funcionamiento, se espera que la plataforma sea ágil, responsiva y accesible, con tiempos de carga mínimos y transiciones fluidas. Debe comportarse como una experiencia de juego educativo con retroalimentación constante, transmitiendo confianza a las familias mediante reportes verificables de progreso e indicadores claros del impacto de las eco-acciones.

**Assumptions**

- Creo que mis clientes necesitan una plataforma educativa que integre escuela y hogar para reforzar la conciencia ambiental a través de actividades prácticas y gamificadas. 

- Estas necesidades se pueden resolver con mini-retos, eco-acciones verificables y reportes de impacto que motiven la continuidad de hábitos sostenibles. 

- Mis clientes iniciales son (o serán) escolares de primaria (9–12 años) y sus padres de familia, interesados en adoptar hábitos ambientales dentro y fuera del aula. 

- El valor #1 que un cliente quiere de mi servicio es la posibilidad de ver resultados tangibles en la formación de hábitos sostenibles en los niños. 

- El cliente también puede obtener estos beneficios adicionales: participación conjunta entre escuela y hogar, retroalimentación inmediata y reconocimiento familiar y comunitario. 

- Voy a adquirir la mayoría de mis clientes a través de instituciones educativas, programas ambientales escolares y difusión digital en redes sociales. 

- Haré dinero a través de un modelo freemium con acceso gratuito básico y una versión premium con funciones avanzadas de seguimiento e impacto. 

- Mi competencia principal en el mercado será aplicaciones educativas ambientales como Happy Little Planet o Defensor de la Naturaleza. 

- Los venceremos debido a nuestra propuesta integral que combina escuela, hogar y comunidad, con funcionalidad offline y un sistema de reportes verificables. 

- Mi mayor riesgo de producto es que las familias no utilicen la plataforma de manera constante fuera del aula. 

- Resolveremos esto a través de estrategias de gamificación, incentivos visibles (insignias, rankings) y actividades comunitarias que refuercen la continuidad. 

- ¿Qué otras suposiciones tenemos? Que las familias valorarán los reportes de impacto como evidencia de aprendizaje. Si esta suposición se prueba falsa, el proyecto podría tener baja adopción en los hogares. 

#### *1.2.2.3. Lean UX Hypothesis Statements*

**Hypothesis Statement 1**

Creemos que la implementación de actividades didácticas y gamificadas captará el interés de los niños para su contribución hacia el medio ambiente. Sabremos que lo hemos logrado, cuando al menos un 30% de los niños/estudiantes completen los mini-retos de forma semanal.

**Hypothesis Statement 2**

Creemos que añadir un modo offline permitirá acceso desde cualquier lugar y atraerá a nuevos usuarios de sectores o zonas de menos recursos. Sabremos que lo hemos logrado, cuando haya un incremento de 15% de usuarios que sean de zonas rurales o baja conectividad.

**Hypothesis Statement 3**

Creemos que incentivar a padres e hijos con actividades/mini-retos conjuntos harán que agreguen actividades eco-amigables dentro del hogar. Sabremos que lo hemos logrado, cuando al menos un 40% de las familias registradas complete/publique las actividades conjuntas que realizaron

**Hypothesis Statement 4**

Creemos que integrar un sistema de ranking motivara a los niños a una participación constante en las actividades. Sabremos que lo hemos logrado,cuando los niños aumenten en un 5% en tiempo/días de uso de la aplicación de forma mensual.

#### *1.2.2.4. Lean UX Canvas*

Link: https://canva.link/9mzenct40v5ocok

**Figura 3**

*Lean Product Canvas*

![Lean Product Canvas](assets/img/figures/image077.png)

## 1.3. Segmentos objetivo

Los segmentos objetivo comprenden a los usuarios finales a los que nuestra solución busca atender. Para el caso de nuestra plataforma, se han determinado los siguientes perfiles prioritarios:

#### Segmento objetivo #1: Estudiantes de Primaria
Este segmento está constituido por niños y niñas en etapa escolar que se encuentran en una fase crucial para la formación de valores y hábitos sostenibles, y que requieren estímulos visuales y lúdicos para integrar el aprendizaje a su vida diaria.

**Aspectos demográficos:**
* Edad: 9 a 12 años.
* Género: Masculino y femenino.
* Nivel Educativo: Educación Primaria.
* Ubicación: Zonas urbanas y rurales.
* Nivel digital: Nativo digital; usuarios habituales de dispositivos móviles y tablets para juegos (como Roblox) y comunicación (Discord).

**Aspectos conductuales:**
Su aprendizaje es principalmente visual y práctico; prefieren aprender jugando, viendo videos o mediante retos interactivos. Se motivan con sistemas de recompensa y reconocimiento (puntos, insignias). Suelen conocer la teoría sobre el cuidado ambiental por la escuela, pero les cuesta aplicarla de forma constante en casa sin un incentivo o recordatorio dinámico.

**Información estadística de sustento:**
Para el segmento de estudiantes de primaria, las investigaciones indican que, si bien un 65.42% manifiesta una conciencia ambiental alta a nivel teórico, existe una brecha crítica en la práctica real, donde solo el 44.86% alcanza un nivel alto de sensibilidad emocional hacia el entorno (Bendezú, 2019).

**Necesidad:**
El estudiante requiere una experiencia de aprendizaje gamificada que convierta las tareas ecológicas (como reciclar o ahorrar agua) en "misiones" divertidas. Necesita una herramienta que le brinde retroalimentación inmediata sobre sus logros, permitiéndole ver el impacto real de sus acciones de manera sencilla y atractiva.

#### Segmento objetivo #2: Padres de Familia
Este segmento comprende a los adultos responsables del hogar, quienes actúan como el nexo principal para que los hábitos aprendidos en la escuela se consoliden en la rutina familiar cotidiana.
Aspectos demográficos:

* Edad: 30 a 62 años.
* Género: Masculino y femenino.
* Nivel Educativo: Superior técnica, universitaria o secundaria completa.
* Ubicación: Áreas residenciales y comunidades con acceso a servicios básicos.
* Nivel digital: Básico a intermedio; utilizan el celular para comunicación (WhatsApp), redes sociales y gestión laboral/bancaria.

**Aspectos conductuales:**
Valoran profundamente la educación ambiental como parte de la formación de sus hijos, pero enfrentan dificultades de tiempo o falta de estrategias claras para motivarlos. Buscan herramientas que sean seguras, educativas y que fomenten la unión familiar a través de actividades conjuntas.

**Información estadística de sustento:**
Respecto a los padres de familia, las investigaciones destacan que su involucramiento es fundamental, ya que el 72.53% de ellos logra adoptar hábitos sostenibles en el hogar tras la influencia de programas educativos ambientales iniciados por sus hijos (Taco et al., 2025).

**Necesidad:**
El padre de familia requiere una guía práctica y recursos simplificados (como guías o FAQs) para acompañar a sus hijos en el desarrollo de hábitos sostenibles. Necesita reportes de impacto y progreso que le den la seguridad de que sus hijos están aprendiendo de forma verificable, reforzando la conexión entre la escuela y el hogar.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

#### 1. Defensor de la naturaleza  
Defensor de la naturaleza es una aplicación móvil educativa y ecológica dirigida a niños, orientada a fomentar la conciencia ambiental de manera lúdica y accesible. Lanzada por Y-Group Games, esta app ofrece una serie de minijuegos interactivos en los que los pequeños limpian jardines, parques y zonas de juego, plantan árboles y flores, clasifican residuos y limpian ríos y estanques contaminados. La experiencia está diseñada especialmente para enseñar a los niños la importancia de proteger la naturaleza y los entornos que los rodea. (Y-Group Games. (s. f.)  

#### 2. Happy Litle Planet  
Happy Little Planet es una aplicación educativa diseñada para niños, cuyo objetivo es enseñar hábitos sostenibles y el cuidado del medio ambiente de manera lúdica e interactiva. La app combina juegos educativos y libros con audio, proporcionando experiencias de aprendizaje divertidas y dinámicas que ayudan a los niños a comprender conceptos como reciclaje, ahorro de recursos y respeto por la naturaleza. (Adrilo Rincz, s.f.)   

#### 3. Earth Cubs  
Earth Cubs es una aplicación educativa orientada a niños, cuyo propósito es enseñar sobre el medio ambiente, la sostenibilidad y el cambio climático mediante experiencias lúdicas e interactivas. La app combina minijuegos, acertijos, cómics y videos, además de recursos para el aula, ofreciendo un aprendizaje dinámico que motiva a los más pequeños a desarrollar conciencia ambiental y hábitos responsables con la naturaleza. (Earth Cubs, s.f.)

### 2.1.1. Análisis competitivo

**Perfil**

|     | EcoMind | Defensor de la naturaleza | Happy Little plantet | Earth Cubs |
| --- | --- | --- | --- | --- |
| Logos | ![Logo Ecomind](assets/img/figures/image024.png) | ![Logo Defensor de la naturaleza](assets/img/figures/image025.png) | ![Logo Happy Little](assets/img/figures/image026.png) | ![Logo Earth Cubs](assets/img/figures/image027.png) |
| Overview | Plataforma educativa gamificada que enseña hábitos sostenibles a escolares, con acceso online y offline, involucrando a familias y comunidades. | Juego móvil centrado en acciones ambientales directas en un entorno lúdico. | App educativa para niños que enseña hábitos sostenibles y cuidado ambiental mediante juegos interactivos y libros con audio, con acompañamiento de padres. | App educativa gamificada que enseña a los niños sobre el medio ambiente, sostenibilidad y cambio climático a través de minijuegos, acertijos, comics y recursos escolares. |
| Ventaja competitiva | Plataforma inclusiva con acceso online y offline. | Educación ambiental sencilla y entretenida para primeras edades. | Aprendizaje ambiental lúdico y seguro para primeras edades, con participación de los padres y contenido offline. | Contenidos educativos integrales y con impacto real. |

**Perfil de marketing**

|     | EcoMind | Defensor de la naturaleza | Happy Little plantet | Earth Cubs |
| --- | --- | --- | --- | --- |
| Mercado Objetivo | Niños escolares y padres de familia interesados en el cuidado ambiental. | Niños pequeños en la edad preescolar y primaria inicial. | Niños pequeños y padres interesados en educación ambiental. | Niños de nivel preescolar y primarios y sus padres / educadores. |
| Estrategias de Marketing | Promoción en redes sociales. | Promoción en tiendas de apps y atractivo visual infantil. | Promoción en tiendas de apps y blogs/redes sobre educación infantil; atractivo visual y seguro para niños. | Difusión multiplataforma y colaboraciones con escuelas y asociaciones ambientales   |

**Perfil de producto**

|     | EcoMind | Defensor de la naturaleza | Happy Little plantet | Earth Cubs |
| --- | --- | --- | --- | --- |
| Productos y Servicios | Plataforma gamificada con mini retos y juegos educativos. | App móvil con minijuegos ecológicos interactivos. | Juegos interactivos educativos, audiolibros, contenido descargable para uso offline. | Plataforma digital con juegos, videos y recursos educativos. |
| Precios y costos | Gratuita, con suscripciones y microtransacciones. | Gratuita con anuncios. | Gratuita. | App gratuita con acceso a contenidos basicos. |
| Canales de distribución (Web y/o móvil) | Web, app móvil y acceso offline. | App móvil (Google play). | App móvil         (Google Play, App Store) y web oficial. | Web official y apps móviles (App Store, Google play). |

**Análisis SWOT**

|     | EcoMind | Defensor de la naturaleza | Happy Little plantet | Earth Cubs |
| --- | --- | --- | --- | --- |
| Fortalezas | Gamificación que motiva a los jugadores y acceso online y offline. | Juego simple, divertido y accesible para niños pequeños. | Conecta lo digital con acciones reales de conversión. | Combina diversión con educación ambiental y amplia variedad de contenidos. |
| Debilidades | Requiere inversión constante en desarrollo de juegos. | Contenido limitado y depende de la publicidad. | Contenido limitado y poca interactividad social entre usuarios. | Enfoque amplio, y depende de actualizaciones constantes. |
| Oportunidades | Creciente interés en educación ambiental. | Creciente interés en apps educativas ecológicas. | Expansión a edades mayores o contenidos multijugador. | Integración de más contenidos ambientales en su plataforma global. |
| Amenazas | Competencia de apps educativas consolidadas. | Alta competencia de apps educativas similares. | Necesidad de actualizaciones frecuentes y alta competitividad. | Riesgo a quedas rasgada frente a plataformas digitales más innovadoras. |

### 2.1.2. Estrategias y tácticas frente a competidores

#### Estrategias

1. **Acceso inclusivo y continuidad**  
   ECOMIND funcionará tanto online como offline, asegurando que los escolares puedan seguir aprendiendo y realizando actividades educativas incluso en zonas con conectividad limitada o desde sus hogares.

2. **Gamificación y personalización mediante tecnología**  
   La plataforma incorporará gamificación avanzada para el seguimiento del progreso y recomendaciones automáticas. Esto permitirá personalizar el aprendizaje y mantener el interés de los usuarios.

#### Tácticas

#### Desarrollo de contenido hiperlocalizado  
Creación de retos, misiones y juegos basados en situaciones reales, con énfasis en acciones concretas de cuidado ambiental que los escolares puedan aplicar en su entorno.

#### Gamificación con incentivos y seguimiento  
Implementación de puntos, medallas, niveles y rankings para motivar a los niños. Además, los padres podrán acceder a reportes de progreso, reforzando el aprendizaje y fomentando hábitos sostenibles.

#### Aprovechamiento de debilidades de la competencia

1. **Frente a Defensor de la Naturaleza**  
   Dado que su experiencia es limitada y depende de publicidad para financiar el contenido, ECOMIND ofrecerá contenido más completo y libre de anuncios, garantizando aprendizaje continuo y mayor motivación de los usuarios.
   

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Escolares de primaria:**

1. ¿Cuál es tu nombre y cuántos años tienes? 

2. ¿Qué cosas te gusta hacer en tu tiempo libre? 

3. ¿Usas celular, Tablet o computadora? ¿Qué aplicaciones te gustan más? 

4. ¿Has aprendido en tu colegio algo sobre el cuidado del medio ambiente? ¿Qué es lo que más recuerdas? 

5. ¿Qué cosas haces tú en casa para ayudar al planeta? (ejemplo: separar basura, ahorrar agua, apagar luces).

6. ¿Qué es lo que más te divierte o motiva a hacerlo? 

7. Si pudieras aprender con juegos o retos sobre cómo cuidar el medio ambiente, ¿te gustaría? ¿Por qué? 

8. ¿Prefieres usar una aplicación en celular/Tablet o prefieres actividades en papel? ¿Por qué? 

9. ¿Cómo te gusta aprender más? ¿Jugando, viendo videos, ¿leyendo o escuchando? 

**Padres de familia:**

1. ¿Podría contarme un poco de usted? (edad, ocupación, hijos, lugar de residencia). 

2. ¿Qué nivel de confianza tiene en el uso de celulares o aplicaciones?

3. ¿Qué actividades suelen realizar en familia durante la semana? 

4. ¿Qué importancia le da al tema del cuidado del medio ambiente en la educación de sus hijos? 

5. ¿Qué acciones realizan en casa relacionadas con el medio ambiente? 

6. ¿Con qué dificultades se encuentran al intentar enseñar hábitos sostenibles en casa? 

7. Si existiera una aplicación con retos simples para que sus hijos aprendan y practiquen acciones ambientales, ¿la usaría en familia? ¿Por qué sí o por qué no? 

8. ¿Qué cosas le ayudarían a usted a motivar más a sus hijos en este tema? 

9. ¿Qué espera que su hijo logre aprender en los próximos años sobre el medio ambiente? 

### 2.2.2. Registro de entrevistas

**Video de la entrevista** :

https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241e158_upc_edu_pe/IQAc74hewuNHToZcDklOaDB9AXfXi86jJbeHQm1dYv3cQZY?e=jNMFmH

#### Segmento: Padres de Familia
<br>

| **Entrevista No. 1** |
|---|
| <img src="assets/img/figures/imagen078.png" width="335" hspace="240"> |
| **Entrevistado N°1:** Pedro Eulogio Pablo<br> **Edad:** 48 años<br>**Ubicación:** Barranca, Barranca, Lima<br><br> **Entrevista:** <br>**Instante del que inicia:** 0:00<br> **Duración:** 4:34<br><br> **Resumen:** <br><br>Nuestro entrevistado es Pedro Eulogio Pablo, un padre de familia de 48 años que vive en Barranca, región Lima. Tiene dos hijos de 9 y 15 años, quienes acompañan cursos en primaria y secundaria. Su rutina semanal se centra en el trabajo y en el acompañamiento a sus hijos en sus estudios, dedicando las tardes a comprender y revisar sus clases.<br><br>En cuanto al uso de la tecnología, Pedro tiene un nivel básico, ya que utiliza principalmente su celular para llamadas y WhatsApp. En contraste, sus hijos emplean aplicaciones más sofisticadas, acceso a redes sociales. Respecto al medio de la familia, Pedro le otorga gran importancia dentro de la educación familiar. En sus acciones más comunes son el reciclaje, la correcta disposición de los desechos y la limpieza de los espacios. Sin embargo, enfrenta dificultades porque sus hijos a veces olvidan prácticas básicas, como correr los caños o apagar las luces.<br><br>Para mejorar sus prácticas ambientales, Pedro está dispuesto a utilizar una aplicación con retos simples y premios que incentiven a que sus hijos realicen actividades cotidianas que les son importantes. A partir de la información que nos proporciona, hemos identificado que los hijos no solo practican en casa, sino que también comparten estas prácticas con su comunidad, creando autónomos en torno a los incentivos. |


| **Entrevista No. 2** |
|---|
| <img src="assets/img/figures/imagen079.png" width="330" hspace="240"> |
| **Entrevistado N°2:** César Meléndez Romero<br> **Edad:** 62 años<br>**Ubicación:** Independencia, Lima<br><br> **Entrevista:** <br>**Instante del que inicia:** 4:55<br> **Duración:** 5:13<br><br> **Resumen:** <br><br>Nuestro entrevistado es César, un profesor de 62 años que vive en Independencia y cuenta con 1 hijo. La rutina semanal de César se centra en sus clases, y la entrevista aborda la importancia del cuidado del medio ambiente y el uso de una aplicación educativa para este propósito.<br><br>En cuanto al uso de la tecnología, César tiene un conocimiento básico, ya que se siente confiado en su capacidad para usar un teléfono celular y aplicaciones. Respecto al cuidado del medio ambiente, le otorga gran importancia, especialmente con los problemas actuales como las sequías. En su hogar, las acciones más comunes son gestionar el consumo de agua y evitar materiales que emitan gases de efecto invernadero. Sin embargo, enfrenta dificultades porque la gente no es plenamente consciente de la importancia de estas acciones.<br><br>César considera que el apoyo de la tecnología puede ser clave para motivar a su familia. Estaría dispuesto a utilizar una aplicación con retos simples para enseñar acciones ambientales a sus hijos. Para él, lo más importante es que sus hijos valoren y preserven un medio ambiente saludable para el futuro. |


| **Entrevista Nro. 3** |
|---|
|<img src="assets/img/figures/imagen080.png" width="330" hspace="240"> |
| **Entrevistado N°3:** Juan Carlos Huamán Quispe<br> **Edad:** 30 años<br>**Ubicación:** San Juan de Lurigancho, Lima<br><br> **Entrevista:** <br>**Instante del que inicia:** 3:12<br> **Duración:** 4:35<br><br> **Resumen:** <br><br>Nuestro entrevistado es Juan Carlos Huamán Quispe, un padre de familia de 30 años que vive en San Juan de Lurigancho, Lima. Tiene dos hijos de 8 y 3 años, quienes actualmente cursan primaria e inicial. Su rutina semanal combina su trabajo como contador con el acompañamiento a sus hijos, dedicando las noches y fines de semana a compartir actividades familiares.<br><br>En cuanto al uso de la tecnología, Juan Carlos tiene un nivel intermedio, ya que utiliza el celular para llamadas, WhatsApp, correo y aplicaciones bancarias, aunque suele pedir ayuda para instalar o configurar nuevas aplicaciones. Respecto al cuidado del medio ambiente, considera que es un aspecto fundamental en la educación de sus hijos. En su hogar, las acciones más comunes son el reciclaje, el uso de bolsas reutilizables y el ahorro de agua y energía. Sin embargo, enfrenta dificultades porque sus hijos a veces olvidan apagar las luces o colocar la basura en el tacho adecuado.<br><br>Juan Carlos afirma que utilizaría una aplicación con retos ambientales, pues cree que sus hijos aprenden más rápido con dinámicas lúdicas y competitivas. Considera que la motivación se refuerza cuando la escuela y la familia trabajan de la mano, y que los incentivos o pequeños logros ayudan a mantener el interés de los niños. Finalmente, espera que sus hijos aprendan a ser responsables con el medio ambiente, valorando la naturaleza y entendiendo que cada acción, por pequeña que sea, puede marcar la diferencia en su comunidad. |


#### Segmento objetivo: Escolares de Primaria
<br>

| **Entrevista Nro. 1** |
|---|
| <img src="assets/img/figures/imagen081.png" width="330" hspace="250"> |
| **Entrevistado N°1:** Mia Rivera Vivanco Zárate<br> **Edad:** 10 años<br>**Ubicación:** Surquillo, Lima<br><br> **Entrevista:** <br>**Instante del que inicia:** 15:17<br> **Duración:** 4:35<br><br> **Resumen:** <br><br>Nuestra entrevistada es Mia Antonela Rivera Vivanco, una niña de 10 años que actualmente es estudiante de nivel primaria, junto a su madre, Erita Vivanco Zárate.<br><br>En cuanto al uso de la tecnología, utiliza su celular y computadora. Sus aplicaciones favoritas son Pinterest y Roblox, ya que le permiten interactuar con amigos que viven lejos. Para aprender sobre el cuidado del medio ambiente, prefiere juegos y videos porque son más entretenidos. Respecto al cuidado del medio ambiente, recuerda que en su colegio le enseñaron que la contaminación puede afectar a la comunidad en el futuro. En casa, sus acciones más comunes son ahorrar agua y apagar las luces durante el día para aprovechar la luz natural.<br><br>Lo que la motiva a cuidar el planeta es el deseo de que en el futuro siga siendo como lo conocemos hoy y no se convierta en un lugar peor. Prefiere actividades en papel sobre las digitales porque puede reutilizarlas. |

| **Entrevista Nro. 2** |
|---|
| <img src="assets/img/figures/image036.png" width="330" hspace="230"> |
| **Entrevistado N°2:** Pablo Astocondor<br> **Edad:** 11 años<br>**Ubicación:** Pueblo Libre, Lima<br><br> **Entrevista:** <br>**Instante del que inicia:** 19:51<br> **Duración:** 3:15<br><br> **Resumen:** <br><br>Nuestro entrevistado es Pablo, un estudiante de 11 años. En su tiempo libre le gusta jugar con sus juguetes, salir, utilizar la consola o la PC, y también emplear aplicaciones como Roblox para jugar y Discord para comunicarse.<br><br>En relación con el cuidado del medio ambiente, recuerda que en su colegio le han enseñado sobre el ahorro de agua, no botar botellas y guardar chapas. En su casa procura no usar muchas bolsas de plástico. Lo que más lo motiva es haber visto en la provincia la acumulación de basura y cómo afecta tanto a las personas como a los animales, lo que lo hace reflexionar sobre la importancia de reducir los desechos.<br><br>Sobre la forma de aprender, señala que prefiere actividades digitales, aunque también reconoce el valor de las que son en papel. Le gusta aprender escuchando, viendo videos y leyendo textos cortos. Además, considera que los juegos pueden servir como herramienta de aprendizaje si tienen mecánicas bien diseñadas, aunque algunos pueden resultar adictivos.<br><br>Finalmente, Pablo demuestra que disfruta combinar distintas formas de aprendizaje y entretenimiento, mostrando una postura crítica frente al uso de videojuegos educativos. |

| **Entrevista Nro. 3** |
|---|
| <img src="assets/img/figures/image037.png" width="330" hspace="250"> |
| **Entrevistado N°3:** Gianfranco de la Cruz <br> **Edad:** 12 años<br>**Ubicación:** La Molina, Lima<br><br> **Entrevista:** <br>**Instante del que inicia:** 23:06<br> **Duración:** 3:40<br><br> **Resumen:** <br><br>El entrevistado se llama Gianfranco de la Cruz, tiene 12 años y está por culminar la primaria. Le gusta pasar el tiempo usando su celular, ya sea para jugar o ver videos.<br><br>Nos menciona que en su colegio sí le han enseñado de manera regular sobre el cuidado del ambiente, como la implementación de tachos de basura específicos para reciclaje. Sin embargo, fuera del colegio no tiene muy claro qué actividades o acciones puede realizar, aparte de mantener limpias sus zonas de convivencia.<br><br>Por último, menciona que actualmente realiza este tipo de acciones más por ayudar que por motivación propia. Sin embargo, la idea de aprender nuevas formas de apoyo mediante juegos o videos le parecería motivante para esforzarse más. |


### 2.2.3. Análisis de entrevistas

**Segmento: Padres de familia**

**1. Perfil general (edad, ocupación, hijos, residencia):**

* Edad promedio: 47 años (48, 62 y 30).
* Todos tienen hijos en edad escolar (inicial, primaria y secundaria).
* Viven en Lima Metropolitana y Barranca.
     
**2. Nivel de confianza con tecnología (celulares/aplicaciones)**

**Figura 3**

*Nivel de confianza en la tecnología - Padres*

 <img src="assets/img/figures/image038.png" width="330"> 
 
**3. Actividades familiares durante la semana:**

En relación con las actividades familiares, los padres señalaron que durante la semana revisan clases y tareas con sus hijos, conversan en las tardes y comparten más tiempo durante los fines de semana.

**4. Importancia del medio ambiente en la educación de los hijos:**

Sobre la importancia del medio ambiente en la educación de sus hijos, el 100% de los entrevistados lo considera fundamental, asociándolo con problemas actuales como sequías, contaminación y el exceso de desechos.

**5. Acciones ambientales realizadas en casa**

En cuanto a las acciones ambientales realizadas en casa, todos afirmaron practicar el ahorro de agua y energía. Además, realizan reciclaje y utilizan bolsas reutilizables o deposita correctamente los desechos.

**6. Dificultades al enseñar hábitos sostenibles a los hijos**

**Figura 4**

*Dificultades en las enseñanzas - Padres*

 <img src="assets/img/figures/image040.png" width="330"> 
 
**7. Aplicaciones educativas Ambientales**

Frente al uso de aplicaciones educativas ambientales, todos los padres estarían dispuestos a utilizarlas, siempre que sean prácticas y sencillas. 

**8. Motivación para los hijos**

En cuanto a la motivación de los hijos, los padres mencionaron que responden mejor cuando hay premios y logros visibles, dinámicas familiares o cuando sienten que sus acciones tienen un impacto en la comunidad.

**9. Expectativas de aprendizaje ambiental:**

Con respecto a las expectativas de aprendizaje ambiental, los padres desean que sus hijos asuman responsabilidades tanto en el hogar como en la comunidad, y que desarrollen una conciencia crítica frente al consumo de agua, energía y residuos.

**Segmento: Escolares de primaria:**

**1. Perfil general (nombre, edad, residencia):**
* Edad promedio: 11 años (10, 11 y 12).
* Residentes en Lima (Pueblo Libre, La Molina, San Juan de Lurigancho).
  
**2. Actividades en tiempo libre:**

Respecto a sus actividades en el tiempo libre, los escolares disfrutan jugar en consola o computadora, pasar tiempo en plataformas digitales

**Figura 5**

*Apps favoritas de escolares de primaria*

<img src="assets/img/figures/image042.png" width="330"> 

**Figura 6**

Uso de aparatos tecnológicos- Escolares

<img src="assets/img/figures/image044.png" width="330"> 
 
**4. Aprendizaje escolar sobre medio ambiente:**

Sobre el aprendizaje escolar en temas ambientales, los niños identificaron prácticas como el ahorro de agua y energía, la separación de basura, la reducción de plásticos y la conciencia frente a la contaminación futura.

**5. Acciones ambientales en casa:**

Dentro de las acciones ambientales en casa practican apagar luces y ahorrar agua, otro practica el reciclaje o la reducción de bolsas plásticas, y también se enfocan en mantener limpio su espacio,

**6. Motivación para hacerlo:**

**Figura 7**

*Motivación de escolares*

<img src="assets/img/figures/image046.png" width="330">
 
**7. Aprender con juegos o retos**

**Figura 8**
*Juegos educativos - Escolares*

<img src="assets/img/figures/image048.png" width="330"> 
 
**8. Preferencias entre lo digital o papel**

**Figura 9**

*Preferencia en los escolares*

<img src="assets/img/figures/image050.png" width="330"> 
  
**9. Forma de aprender favorita**

En cuanto a la forma de aprender, todos mostraron interés en juegos y retos relacionados con el medio ambiente.

**Análisis comparativo**

El análisis de entrevistas evidencia una diferencia clara en el nivel de confianza tecnológica entre padres e hijos. Mientras que los padres presentan un manejo básico o intermedio, lo que implica la necesidad de aplicaciones simples y fáciles de usar, los escolares muestran un dominio más alto de dispositivos y plataformas digitales, lo que refleja una motivación clara hacia el aprendizaje mediante entornos digitales.

En cuanto a la educación ambiental, los padres perciben este aspecto como una responsabilidad tanto familiar como comunitaria, asociándolo a prácticas de ahorro y reciclaje en el hogar. Por su parte, los hijos lo relacionan más directamente con el futuro y con su entorno inmediato, mostrando interés en acciones como el cuidado del agua, la energía y la reducción de plásticos. Sin embargo, ambos segmentos comparten limitaciones que deben considerarse. Los padres enfrentan la falta de constancia de sus hijos al mantener hábitos sostenibles, así como una escasa conciencia comunitaria. 

En el caso de los escolares, algunos presentan una motivación débil al asumir estas prácticas y existe el riesgo de que las aplicaciones o juegos se vuelvan adictivos si no se diseñan adecuadamente. Frente a este panorama, se identifica una oportunidad clara para el desarrollo de una aplicación educativa ambiental con retos sencillos, dinámicos e incentivados que fortalezcan el vínculo entre familia y la conciencia ambiental.

## 2.3. Needfinding

### 2.3.1. User Personas



### 2.3.2. User Task Matrix



### 2.3.3. User Journey Mapping



### 2.3.4. Empathy Mapping



## 2.4. Big Picture EventStorming



## 2.5. Ubiquitous Language



# Capítulo III: Requirements Specification

## 3.1. User Stories
**Epics**

| Epic ID | Título | Descripción |
| --- | --- | --- |
| E1 | Actividades gamificadas  | Como estudiante, quiero acceder a actividades gamificadas sobre cuidado ambiental, para aprender de forma entretenida y mantener mi interés en el tema. |
| E2 | Participación familiar | Como padre, quiero que la aplicación ofrezca actividades y proyectos grupales, para fortalecer la interacción, colaboración y aprendizaje dentro de mi familia. |
| E3 | Información clara y amigable | Como estudiante, quiero acceder a información sencilla y fácil de comprender sobre las actividades, para aprender sin perder la motivación. |
| E4 | Acceso a comunidad | Como estudiante, quiero una sección que me permita interactuar con otros usuarios y compartir logros, para sentir motivación en mejorar continuamente. |
| E5 | Accesibilidad | Como estudiante o padre, quiero que la aplicación funcione de manera rápida, sencilla y accesible en cualquier dispositivo, para contar con una experiencia fluida y agradable en cualquier situación.  |
| E6 | Landing page informativa | Como estudiante o padre, quiero acceder a una página informativa de EcoMind, para conocer la propuesta del producto y unirme a la comunidad. |


## 3.2. Impact Mapping



## 3.3. Product Backlog



# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines



### 4.1.2. Web Style Guidelines



## 4.2. Information Architecture

### 4.2.1. Organization Systems



### 4.2.2. Labeling Systems



### 4.2.3. SEO Tags and Meta Tags



### 4.2.4. Searching Systems



### 4.2.5. Navigation Systems



## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe



### 4.3.2. Landing Page Mock-up



## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes



### 4.4.2. Web Applications Wireflow Diagrams



### 4.4.3. Web Applications Mock-ups



### 4.4.4. Web Applications User Flow Diagrams



## 4.5. Web Applications Prototyping



## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming



### 4.6.2. Software Architecture Context Diagram



### 4.6.3. Software Architecture Container Diagrams



### 4.6.4. Software Architecture Components Diagrams



## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams



## 4.8. Database Design

### 4.8.1. Database Diagrams



# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration



### 5.1.2. Source Code Management



### 5.1.3. Source Code Style Guide & Conventions



### 5.1.4. Software Deployment Configuration



## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. *Sprint Planning 1*



#### 5.2.1.2. *Aspect Leaders and Collaborators*



#### 5.2.1.3. *Sprint Backlog 1*



#### 5.2.1.4. *Development Evidence for Sprint Review*



#### 5.2.1.5. *Execution Evidence for Sprint Review*



#### 5.2.1.6. *Services Documentation Evidence for Sprint Review*



#### 5.2.1.7. *Software Deployment Evidence for Sprint Review*



#### 5.2.1.8. *Team Collaboration Insights during Sprint*



# Conclusiones



# Recomendaciones



# Bibliografía



# Anexos



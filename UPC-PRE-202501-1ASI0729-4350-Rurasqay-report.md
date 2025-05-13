
# <center>COURSE PROJECT<center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Desarrollo de Aplicaciones Open Source - 4350</strong><br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez </strong><br>
    <br>INFORME TB1
</p>

<center>

#### Startup: **RurasqaySoft**
#### Product: **EasyStock**

</center>

### <center>Team Members</center>
<center>

| Member                       | Code       |
|------------------------------|------------|
| Alvarado De La Cruz, Juan Carlos | u202216150 |
| Barrientos Quispe, Marcelo | u20221e646 |
| Rioja Nuñez, Franco Diego | u202221597 |
| Nakasone Gomes, Marco Antonio | u202210790 |
| Rivera Ticllacuri, Omar Harold | u202214214 |

<br> ABRIL 2025
</center>

<center>

# Registro de Versiones del Informe

| Version | Fecha      | Autor                           | Descripción de Modificación                                                    |
|---------|------------|---------------------------------|--------------------------------------------------------------------------------|
|0.0    | 02/04/2025 |  Grupo 3|   Creación del documento                             |
|   | 04/04/2025 |        |                            |
|   | 04/04/2025 |     |                         |

</center>

# Project Report Collaboration Insights
Analiza cómo la colaboración y la gestión de tareas influyeron en los resultados del proyecto, destacando fortalezas y áreas de mejora para optimizar futuras estrategias.

# Contenido
[Registro de Versiones del Informe](#registro-de-versiones-del-informe)  
[Project Report Collaboration Insights](#project-report-collaboration-insights)  
[Student Outcome](#student-outcome)  

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysi](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 

[2.4. Ubiquitous Language](#24-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)    
[3.2. User Stories](#32-user-stories)  
[3.3. Impact Mapping](#33-impact-mapping)  
[3.4. Product Backlog](#34-product-backlog)  

[Capítulo IV: Product Design](#capítulo-iv-product-design)  

[4.1. Style Guidelines.](#41-style-guidelines)  
[4.1.1. General Style Guidelines.](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines.](#412-web-style-guidelines)  

[4.2. Information Architecture.](#42-information-architecture)  
[4.2.1. Organization Systems.](#421-organization-systems)  
[4.2.2. Labeling Systems.](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tags.](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems.](#424-searching-systems)  
[4.2.5. Navigation Systems.](#425-navigation-systems)  

[4.3. Landing Page UI Design.](#43-landing-page-ui-design)  
[4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)  

[4.4. Web Applications UX/UI Design.](#44-web-applications-ux-ui-design)  
[4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)  
[4.4.3. Web Applications Mock-ups.](#443-web-applications-mock-ups)  
[4.4.4. Web Applications User Flow Diagrams.](#444-web-applications-user-flow-diagrams)  

[4.5. Web Applications Prototyping.](#45-web-applications-prototyping)  

[4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram.](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)  

[4.7. Software Object-Oriented Design.](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams.](#471-class-diagrams)  
[4.7.2. Class Dictionary.](#472-class-dictionary)  

[4.8. Database Design.](#48-database-design)  
[4.8.1. Database Diagram.](#481-database-diagram)  

[Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation-deployment)  

[5.1. Software Configuration Management.](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management.](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions.](#513-source-code-style-guide--conventions)
[5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)  

[5.2. Landing Page, Services & Applications Implementation.](#52-landing-page-services--applications-implementation)
[5.2.1. Sprint n.](#521-sprint-n)  
[5.2.1.1. Sprint Planning n.](#5211-sprint-planning-n)  
[5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)  
[5.2.1.3. Sprint Backlog n.](#5213-sprint-backlog-n)  
[5.2.1.4. Development Evidence for Sprint Review.](#5214-development-evidence-for-sprint-review)  
[5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)  
[5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)  
[5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)  
[5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)  

[Conclusiones](#conclusiones)  
[Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)  
[Video About-the-Team.](#video-about-the-team)  

[Bibliografía](#bibliografía)  

[Anexos](#anexos)

# **Student Outcome**

**ABET - EAC - Student Outcome 3:** Capacidad de comunicarse efectivamente con un rango de audiencias.

|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Comunica oralmente con efectividad a diferentes rangos de audiencia. | <br> **Marco Nakasone:** <br> **TB1:** <br> Durante la primera entrega me encargue de hacer una parte del capítulo 3, agregando las epics, las user stories, los impact mapping y el product backlog, pude obtener más conocimiento de como se puede hacer bien un impact mapping, y a la vez como poder integrar las historias de usuario en un proyecto. <br> <br> **Omar Rivera:**<br>**TB1:**<br> Durante el desarrollo del proyecto, me enfoqué en el Capítulo 4, contribuyendo activamente en el product design, especialmente en la creación y estructura de la Landing Page, así como en los elementos visuales que garantizan una experiencia coherente y atractiva para el usuario.<br> <br> **Juan Carlos Alvarado:** <br> **TB1:** <br> Participé activamente en las presentaciones del equipo, explicando la problemática identificada a partir de los segmentos objetivo y las entrevistas. Me encargué de comunicar con claridad el enfoque de EasyStock y sus beneficios para distintos perfiles de emprendedores. Esto me ayudó a reforzar mis habilidades para comunicar ideas técnicas a audiencias no técnicas. <br> <br> **Marcelo Barrientos Quispe:** <br> **TB1:** <br> Durante la primera entrega me encargue del C4 model, el data base diagram, class diagram que son necesarias para el funcionamiento del producto a realizar.<br> <br> **Franco Diego Rioja Nuñez:** <br> **TB1:** <br> Durante esta entrega me encargue de hacer el Capitulo 2 en el cual analicé a la competencia y vi las posibles oportunidades contra ellos. |
|Comunica por escrito con efectividad a diferentes rangos de audiencia.| <br> **Marco Nakasone:** <br> **TB1:** <br> Durante la primera entrega pude crear las historias de usuario, basandome en entrevistas e informacion recopilada con respecto a nuestro proyecto, aquí pude aprender mejor sobre lo que necesitan nuestros usuarios objetivos.<br>**Omar Rivera:** <br> **TB1:** <br> En el Capítulo 4, me encargué del diseño UI, incluyendo la elaboración de las Style Guidelines y la estructura visual de la Landing Page. Mi trabajo se centró en brindar una experiencia clara, intuitiva y estéticamente cuidada para los usuarios de la aplicación web.<br><br> **Juan Carlos Alvarado:** <br> **TB1:** <br> Me encargué de redactar el Capítulo I del informe, incluyendo la descripción de la startup, antecedentes y problemática, análisis 5W2H, Lean UX Process y Lean UX Canvas. También elaboré respuestas realistas basadas en user stories para entrevistas simuladas. Esto me permitió aplicar una comunicación escrita técnica y estructurada, manteniendo claridad para lectores con o sin experiencia técnica. <br> <br> **Marcelo Barrientos Quispe:** <br> **TB1:** <br> En el transcurso de la entrega me enfoque en un desarrollo estructurado y organizado para tenerlo como base necesaria para el proyecto siendo esta la guía básica para realizar con la cual guiarnos y avanzar dicho proyecto <br> <br> **Franco Diego Rioja Nuñez:** <br> **TB1:** <br> Durante esta entrega me encargue de la revisión de las entrevistas de las personas relacionadas con el segmento objetivo y ver cuales son nuestras debilidades y usar el feedback de los entrevistados para poder seguir progresando. | 

# Capítulo I: Introduccion
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
**RurasqaySoft** es una startup de base tecnológica orientada a brindar soluciones digitales prácticas para los desafíos reales que enfrentan emprendedores y pequeñas empresas en Perú. Nuestro objetivo es desarrollar herramientas accesibles que digitalicen procesos clave como el control de inventarios, permitiendo a los usuarios mejorar su eficiencia, evitar pérdidas y tomar decisiones basadas en datos.

**Misión:** Desarrollar soluciones tecnológicas accesibles que ayuden a los emprendedores a gestionar eficientemente sus operaciones, promoviendo sostenibilidad y crecimiento.

**Visión:** Convertirse en referente latinoamericano en soluciones digitales para la gestión operativa de micro y pequeñas empresas.

### 1.1.2. Perfiles de integrantes del equipo

| Foto | Apellido y Nombre | Carrera | Acerca de | Código |
|------|-------------------|---------|-----------|--------|
| <img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/project-report/Images/marco.jpg?raw=true" width="300"/> | Nakasone Gomes, Marco Antonio | Ingeniería de Software | Soy estudiante de Ingeniería de software, tengo cualidades como la perseverancia, que me va a ayudar a ser resiliente ante cualquier adversidad que se nos presente más adelante en el trabajo y también soy buen compañero de trabajo que siempre quiere lo mejor para su grupo. | u202210790 |
| <img src="Images/Omar.jpeg"/>| Omar Harold Rivera Ticllacuri | Ingeniería de Software | Soy estudiante de Ingeniería de Software, tengo 20 años. Me considero una persona disciplinada y responsable, con experiencia en el desarrollo de software de entretenimiento. Estoy comprometido a aportar al grupo para cumplir con éxito los objetivos del proyecto. |  u202214214 |
| <img src='./Images/marcelo.png'/> | Marcelo Barrientos Quispe | Ingeniería de Software | Soy estudiante de Ingeniería de Software, tengo 19 años. Me considero alguien muy a fin a las tecnologías de Javascript y sus frameworks como React, Angular y Node. Me considero buen compañero y muy compretido con el curso y con el trabajo. | u20221e646 |
| <img src='./Images/diego.jpg'/> | Franco Diego Rioja Nuñez | Ingeniería de Software |Soy estudiante de Ingeniería de Software, apasionado por el aprendizaje continuo y la formación autodidacta. Me destaco por mi buena disposición para el trabajo en equipo y mi habilidad para desenvolverme eficazmente en entornos colaborativos. | u202221597 |
|<img src="Images/juan.jpg"> | Alvarado De La Cruz, Juan Carlos | Ingeniería de Software | Soy estudiante de la carrera de Ing. de Software. Me gusta resolver problemas y aprender cosas que son de mi interés, tengo experiencia programando en C++ y en Python. | u202216150 |

## 1.2. Solution Profile
EasyStock es una solución tecnológica innovadora que transforma la gestión de inventarios para emprendedores que trabajan con productos sensibles o en grandes cantidades. A través de una plataforma digital intuitiva, EasyStock permite controlar el stock de insumos y monitorear en tiempo real las condiciones del entorno en que se almacenan, asegurando que se mantengan en óptimas condiciones.

Además, ofrece un plan premium con sensores inteligentes que supervisan constantemente la materia prima. Estos dispositivos generan alertas y notificaciones cuando se detectan variaciones que puedan comprometer la calidad o cantidad de los productos, permitiendo a los responsables actuar de inmediato. En resumen, EasyStock no solo reduce el riesgo de pérdidas, sino que optimiza el control logístico y fortalece la eficiencia operativa de los emprendimientos.

### 1.2.1. Antecedentes y problemática
Muchos emprendedores que gestionan productos sensibles o en grandes volúmenes enfrentan dificultades constantes para mantener un control eficiente de sus inventarios. La ausencia de herramientas accesibles y automatizadas para monitorear el stock y las condiciones ambientales de los insumos genera un entorno propenso a errores humanos, desperdicio de materia prima y pérdidas económicas significativas. Además esta situación se agrava cuando los procesos son manuales o poco estandarizados, lo que incrementa la carga operativa y reduce la capacidad de respuesta ante imprevistos.

Con el objetivo de comprender a fondo las necesidades de nuestros usuarios y enfocar nuestro trabajo conforme a los principios de Lean UX, llevamos a cabo un análisis del contexto y la problemática mediante la técnica de las "5W’s & 2H’s". Esta herramienta, fundamental en Lean UX, nos permitió identificar oportunidades clave para desarrollar un diseño verdaderamente centrado en el usuario. A continuación, se expone la información obtenida.

#### Análisis con técnica de The 5 W’s and 2 H’s

#### **What**
**¿Cuál es el problema?**  
EasyStock busca resolver una serie de desafíos que afectan directamente a emprendedores que gestionan productos sensibles o en grandes cantidades. Entre estos problemas se encuentran las pérdidas económicas causadas por el deterioro de insumos mal almacenados, el uso de métodos manuales e ineficientes para el control de inventario como cuadernos o planillas de Excel, la falta de alertas oportunas ante cambios críticos en las condiciones ambientales, y la escasa visibilidad en tiempo real que dificulta la toma de decisiones operativas, generando errores humanos y una mayor carga de trabajo.

#### **When**
**¿Cuándo sucede?**  
A lo largo de todo el ciclo operativo del negocio, incluyendo el almacenamiento, la distribución, la recepción y el despacho de productos, el problema se vuelve crítico  en momentos en los que no hay personal disponible para supervisar el estado del inventario.

**¿Cuándo utiliza el cliente el producto?** 
Los clientes utilizan EasyStock cuando necesitan realizar tareas operativas como verificar niveles de stock, o monitorear las condiciones ambientales de los insumos almacenados. Especialmente útil durante actividades críticas como el cierre del día, ausencia de personal supervisando, ya que permite automatizar alertas y tomar decisiones inmediatas basadas en datos actualizados al instante.

#### **Where**
**¿Dónde surge el problema?**  
El problema ocurre en almacenes de pequeños negocios, tiendas físicas, cocinas industriales o centros de distribución informales, donde la falta de monitoreo de insumos
es ineficiente.

#### **Who (¿Quiénes son los afectados?)**  
**¿Quiénes están involucrados?**
Los principales involucrados son emprendedores que trabajan con productos sensibles a factores ambientales, como alimentos, plástico o materia prima, así como aquellos que manejan grandes volúmenes de inventario sin sistemas automatizados de control. Además, el problema impacta al personal operativo y a los propietarios de negocios, quienes enfrentan pérdidas recurrentes de insumos debido a una gestión inadecuada del inventario.

**¿A quiénes le sucede el problema?**
El problema afecta a emprendedores que poseen dificultades para gestionar sus productos.

**¿Quién utilizará el producto?**
El producto será utilizado por emprendedores que trabajan con insumos y el personal encargado de gestionar los inventarios, supervisar las condiciones de almacenamiento y recibir alertas en tiempo real.

#### **Why**  
**¿Por qué sucede el problema?**
El problema surge debido a la falta de eficiencia en el control y monitoreo de insumos, que impiden una respuesta adecuada a cualquier situación crítica como un cambio
drástico en el ambiente, generando perdidas económicas para los emprendedores.

**¿Qué llevó al usuario a esta situación?**
La falta de herramientas actalizadas y eficientes que ayuden a automatizar dichos procesos en tiempo real para así evitar perdidas de material y facilitar la gestión de los insumos. 

#### **How (¿Cómo se resuelve?)**  
**¿En qué condiciones los clientes usan nuestro producto?**
Los clientes de EasyStock usan el producto cuando necesitan gestionar su inventario de productos sensibles o en grandes volúmenes, especialmente en situaciones donde no pueden supervisar manualmente las condiciones de almacenamiento.  

**¿Cómo nos conocerán los usuarios?**
Los usuarios conocerán el producto a través de estrategias de marketing digital, como anuncios en redes sociales o recomendaciones en el sector. También podrán conocerlo por medio de testimonios de otros emprendedores, demostraciones en eventos o a través de asociaciones con entidades que apoyen a emprendedores y pequeñas empresas.

#### **How much**
**¿En qué cantidad sucede el problema?** 
El problema ocurre en una gran cantidad de pequeños negocios y emprendedores, generando pérdidas económicas y errores operativos de manera frecuente. Esto sucede a diario, particularmente en momentos críticos de gestión, como la recepción, almacenamiento y despacho de productos.


### 1.2.2. Lean UX Process
En esta sección se desarrollará el proceso de Lean UX, el cual contempla la visión del modelo de negocio que respaldará nuestro producto de software. Este enfoque metodológico nos permite enfocar los esfuerzos en el diseño de la solución y en la comprensión profunda de los problemas detectados a través del pensamiento de diseño. Utilizamosremos la plantilla de Business Opportunity Statements (Gothelf, 2022) como guía para enfocar al equipo en el desarrollo de un servicio libre de limitaciones que frenen la innovación y la rapidez. Esta metodología nos permite abordar el proyecto desde las necesidades reales del cliente, favoreciendo un proceso más ágil y enfocado hacia un lanzamiento exitoso.


#### 1.2.2.1. Lean UX Problem Statements

**Domain:** 
Nos enfocamos en el sector de la gestión y monitoreo de inventarios para empresas y negocios, un ámbito fundamental que abarca desde pequeños emprendimientos hasta medianas empresas con operaciones más complejas. Cada negocio tiene necesidades particulares relacionadas con el control de sus insumos, especialmente cuando se trata de productos sensibles al ambiente o de alto volumen. 

**Customers Segment** 
Nuestro público objetivo incluye tanto a empresarios y emprendedores como al personal encargado de monitorear y gestionar los insumos dentro de sus negocios. Reconocemos que cada empresa trabaja con distintos tipos de insumos, lo que representa un desafío en términos de conservación, control y seguimiento. Por ello, hemos desarrollado una plataforma adaptable y fácil de usar que facilita una gestión eficiente y precisa, brindando a los responsables una herramienta confiable para tomar decisiones oportunas y reducir riesgos operativos.

**Paint point:** 
- **Pérdidas económicas por deterioro o vencimiento de insumos mal almacenados:**
Muchos negocios sufren pérdidas debido al deterioro de insumos sensibles que no son almacenados en condiciones adecuadas, donde la temperatura y humedad son factores críticos. La falta de monitoreo en tiempo real impide detectar a tiempo problemas ambientales que afectan la calidad del producto.

- **Falta de control y visibilidad en tiempo real:**
La ausencia de herramientas automatizadas dificulta tener una visión actualizada del inventario. Esto impide tomar decisiones informadas de reposición o despacho, generando retrasos y errores. La visibilidad en tiempo real es clave para reaccionar rápidamente ante cualquier cambio en el stock o las condiciones de los insumos.

- **Uso de métodos manuales e ineficientes:**
Muchos emprendedores siguen utilizando cuadernos o planillas Excel para gestionar sus insumos, lo que aumenta el riesgo de errores humanos. Estos métodos no escalan con el crecimiento del negocio y dificultan el análisis de datos. Además, requieren tiempo y esfuerzo constante para mantenerse actualizados.

- **Sobrecarga operativa en horarios críticos como cierres, cambios de turno o ausencia de personal:**
Durante los cierres de jornada o cambios de turno, es común que el inventario quede sin supervisión. Esto incrementa el riesgo de pérdidas, robos o deterioro de productos sin que nadie lo detecte a tiempo. La falta de alertas automáticas o monitoreo constante deja al negocio expuesto en momentos críticos.

**Gap:** 
La principal brecha para implementar nuestro producto en los emprendimientos radica en la falta de digitalización y cultura tecnológica en la gestión de inventarios. Muchos emprendedores aún utilizan métodos manuales como cuadernos o hojas de cálculo, lo que representa una barrera de adopción y confianza hacia soluciones automatizadas. Esta brecha se refleja en la resistencia al cambio por temor a lo desconocido, la limitación de recursos tecnológicos en pequeños negocios, y el desconocimiento del impacto real que una mala gestión de insumos puede tener en la rentabilidad. Superar esta brecha implica concientizar sobre los beneficios de la automatización y ofrecer una solución accesible, adaptable y fácil de usar.

**Vision:** 
Nuestra vision es ofrecer una plataforma de calidad, integral y de facil acceso para que nuestros usuarios gestionen de forma eficiente sus insumos.  

**Strategy:** 
Implementaremos sensores inteligentes, datos reales y a tiempo real que se podran visualizar en el dashboard, alertas y recomendaciones.

**Initial Segment:** 
Inicialmente, nos dirigimos a los empresarios y emprendedores que buscan gestionar y monitorear de manera eficiente sus insumos o materia prima. Dichos usuarios o clientes, necesitan acceso a una plataforma amigable y sencilla para un uso sin dificultad. 

#### 1.2.2.2. Lean UX Assumptions

#### **Users:**
- Empresarios o emprendedores que buscar monitorear y gestionar sus insumos
- Personal del emprendimiento encargado de gestionar y monitorear los insumos

#### **Users Outcomes:**

**Segmento de Empresarios o Emprendedores:**
- Acceder a una plataforma digital que les permita monitorear y gestionar sus insumos de manera eficiente y en tiempo real.

- Recibir alertas automáticas ante cambios críticos en el ambiente (como temperatura o humedad) que puedan afectar la calidad de los productos.

- Visualizar reportes y análisis del estado del inventario para tomar decisiones informadas sobre compras, reposición o almacenamiento.

-Reducir pérdidas económicas por deterioro o mal manejo de insumos gracias al monitoreo inteligente y continuo.

**Segmento de Personal Encargado del Inventario:**
- Utilizar la plataforma para verificar niveles de stock y condiciones ambientales de forma rápida y sencilla desde cualquier dispositivo.

- Recibir notificaciones inmediatas cuando los insumos requieren atención, evitando errores y retrasos.

- Registrar movimientos de inventario sin necesidad de métodos manuales, mejorando la precisión y reduciendo la carga operativa.

- Automatizar tareas repetitivas y contar con una herramienta que los apoye durante cambios de turno o ausencias de supervisión.

**Suposiciones de Negocio:**
- Creemos que existe una creciente demanda por soluciones eficientes que permitan a negocios y emprendimientos controlar y monitorear sus inventarios en tiempo real, reduciendo pérdidas y mejorando la gestión operativa.

- Reconocemos la presencia de competidores en el sector de gestión de inventarios, pero confiamos en que nuestra propuesta innovadora, basada en monitoreo inteligente y automatización, nos permitirá diferenciarnos y destacar en el mercado.

- Estamos convencidos de que nuestros clientes valorarán la funcionalidad y practicidad de nuestro producto, adoptándolo con facilidad y adaptándose rápidamente a los beneficios que ofrece para una gestión óptima de sus insumos.

**Suposiciones de Usuarios:**
- **¿Quién utiliza nuestra plataforma?** 
Nuestra plataforma está dirigida a empresarios, emprendedores y su personal encargado de la gestión de insumos, especialmente aquellos que manejan productos sensibles o en grandes volúmenes y requieren un control eficiente y automatizado de su inventario.

- **¿Cómo se integra nuestro producto en la rutina diaria?** 
EasyStock se incorpora a las actividades operativas como la verificación de stock, supervisión del estado de los insumos y generación de alertas en tiempo real.

- **¿Cuáles son los desafíos que aborda nuestro producto?**
Aborda problemas críticos como el deterioro de insumos por mala conservación, errores humanos en el control manual del inventario, falta de visibilidad en tiempo real y la ausencia de alertas preventivas ante cambios en condiciones ambientales.

- **¿Qué imagen deseamos proyectar con nuestro producto?** 
Queremos proyectar una imagen de innovación, confiabilidad y eficiencia, posicionándonos como una solución tecnológica de vanguardia que facilita la gestión inteligente de inventarios en emprendimientos y negocios.

- **¿Cuál es el propósito fundamental de nuestra aplicación?** 
El propósito de EasyStock es prevenir pérdidas económicas mediante el monitoreo automatizado de inventarios. Ademas de facilitar su facil monitoreo.

- **¿Qué funcionalidades destacan en nuestra aplicación?** 
Entre sus principales funcionalidades se encuentran el monitoreo ambiental en tiempo real, generación automática de alertas, reportes de stock, historial de inventario y una interfaz intuitiva que facilita el uso por parte del personal operativo.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que** si implementamos sensores que monitorean temperatura, humedad y peso en tiempo real, **entonces** los usuarios podrán prevenir pérdidas de productos sensibles, **lo que resultará** en una mayor satisfacción y retención.
- **Creemos que** si ofrecemos recomendaciones y reportes visuales, **entonces** los emprendedores podrán tomar decisiones informadas, **lo que resultará** en una mejora operativa y reducción de errores.
- **Creemos que** si facilitamos el registro de productos mediante escaneo o importación de archivos, **entonces** los usuarios podrán adoptar la plataforma rápidamente, **lo que resultará** en una mayor adopción inicial.

#### 1.2.2.4. Lean UX Canvas
El Lean UX Canvas de EasyStock identifica los problemas de los emprendedores para encontrar estacionamiento y de los propietarios para maximizar su uso. Propone soluciones como sensores infrarrojos y sistemas de reserva anticipada para mejorar la eficiencia y satisfacción del usuario, validando su efectividad mediante hipótesis y métricas claras.

| Elemento                     | Descripción                                                                                     |
|-----------------------------|-------------------------------------------------------------------------------------------------|
| **Usuarios**                | Emprendedores que trabajan con productos perecibles o con inventario de alto volumen.           |
| **Problemas**               | Pérdidas por mal almacenamiento, errores humanos, falta de visibilidad.                        |
| **Solución propuesta**      | Plataforma con sensores conectados, dashboards, alertas y recomendaciones automáticas.          |
| **Resultados esperados**    | Conservación óptima de productos, reducción de errores, mayor control operativo.                |
| **Métricas clave**          | Reducción de mermas, ahorro de tiempo, tasa de alertas atendidas, nivel de adopción.            |

---

## 1.3. Segmentos Objetivo

### Segmento 1: Emprendedores que gestionan productos sensibles o grandes volúmenes de inventario

Descripción: Personas que elaboran, almacenan o comercializan productos que requieren un control riguroso, ya sea por su sensibilidad a condiciones ambientales como temperatura o humedad, o por el alto volumen de unidades que deben administrar. Muchos aún dependen de métodos manuales como cuadernos o Excel, lo que incrementa el riesgo de errores y pérdidas.

Ejemplos: Productores de alimentos, reposteros, emprendedores de cosmética natural, farmacéuticos artesanales, artesanos textiles, emprendedores de ecommerce y pequeños fabricantes.

Necesidad principal: Contar con una solución digital que permita monitorear continuamente las condiciones ambientales de los insumos y automatizar el control de stock, facilitando la toma de decisiones oportunas, reduciendo errores y evitando pérdidas económicas.

Sustento estadístico: Según el INEI (2023), el 67% de microempresas del sector alimentos y bebidas no utiliza sistemas digitales para la gestión de insumos. Además, un estudio del BID (2022) indica que el 74% de las microempresas en LATAM no tiene un sistema automatizado de control de inventarios.# Capitulo II: Requeriments Elicitation & Analysis

## 2.1. Competidores 

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding 

### 2.3.1. User Personas
### 2.3.2. User Task Matrix 
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-Is Scenario Mapping

## 2.4. Ubiquitous Language

# Capitulo III: Requeriments Specification

## 3.1. To-Be Scenario Mapping 
## 3.2. User Stories


## 3.3. Impact Mapping
## 3.4. Product Backlog

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
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary

## 4.8. Database Design
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint n
#### 5.2.1.1. Sprint Planning n
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog n
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones
## Conclusiones y recomendaciones

## Video About-the-Team

## Bibliografía

## Anexos

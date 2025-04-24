
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

### 1.2.1. Antecedentes y problemática

**Enunciado del problema:**  
Emprendedores que gestionan productos sensibles o en grandes cantidades carecen de herramientas accesibles para monitorear y controlar sus inventarios de forma eficiente. Esto genera pérdidas económicas, errores humanos y sobrecarga operativa.

**Objetivo general del sistema:**  
Diseñar e implementar una solución digital que facilite la gestión inteligente del inventario, incluyendo monitoreo en tiempo real de condiciones ambientales, alertas automáticas y recomendaciones personalizadas para la optimización del almacenamiento.

**Objetivos específicos:**
- Digitalizar la gestión de inventarios para reducir errores y tiempos operativos.
- Implementar monitoreo en tiempo real mediante sensores.
- Emitir alertas ante condiciones críticas (temperatura, humedad, peso).
- Proporcionar reportes gráficos y recomendaciones para optimización.

**Restricciones:**
- La solución debe ser accesible desde la web y dispositivos móviles.
- El sistema debe permitir integración con sensores de bajo costo.
- Se debe ofrecer como servicio (SaaS) con planes escalables.

#### Análisis con técnica de The 5 W’s and 2 H’s

**Who (¿Quiénes son los afectados?)**  
- Emprendedores que gestionan productos sensibles al ambiente (alimentos, cosméticos, farmacéuticos).
- Emprendedores que manipulan grandes volúmenes de inventario sin automatización.
- Personal operativo y dueños de negocios que pierden insumos por mala gestión.

**What (¿Qué sucede?)**  
- Pérdidas económicas por deterioro de productos mal almacenados.
- Control manual ineficiente del inventario (cuadernos, Excel).
- Falta de alertas oportuna ante cambios en condiciones críticas.
- Dificultad para tomar decisiones operativas por falta de visibilidad en tiempo real.

**Where (¿Dónde ocurre?)**  
- Almacenes de pequeños negocios, tiendas físicas, cocinas industriales, centros de distribución informales.

**When (¿Cuándo sucede?)**  
- Durante todo el ciclo operativo del negocio: almacenamiento, distribución, recepción de productos, despacho.
- De forma crítica en horarios de cierre, cambios de turno, o cuando no hay personal atento al estado del inventario.

**Why (¿Por qué ocurre?)**  
- Porque no existe una solución accesible, automatizada y adaptada al contexto de emprendedores peruanos.
- Porque los sensores inteligentes suelen ser costosos o difíciles de integrar sin soporte técnico.
- Porque la mayoría de herramientas actuales están pensadas para empresas grandes.

**How (¿Cómo se resuelve?)**  
- Con una plataforma web fácil de usar, que permita registrar productos, vincular sensores y visualizar alertas en tiempo real.
- Implementando dashboards, reportes y recomendaciones basadas en datos históricos.
- Permitiendo la administración remota del inventario y condiciones de almacenamiento.

**How much (¿Cuánto cuesta o cuánto implica?)**  
- Los usuarios podrán elegir entre planes mensuales accesibles con funcionalidades escalables. *(Precio por definir)*.
- Se ofrecerá el alquiler de sensores como servicio para reducir la inversión inicial.
- El modelo de negocio será por suscripción tipo SaaS.


### 1.2.2. Lean UX Process

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Dominio:** Gestión de inventarios en pequeños negocios.  
**Segmento inicial:** Emprendedores con productos sensibles o de gran volumen.  
**Punto de dolor (pain point):** Pérdida de productos y sobrecarga operativa.  
**Brecha (gap):** Ausencia de soluciones adaptadas al contexto local.  
**Visión:** Brindar control en tiempo real y eficiencia operativa con bajo costo.  
**Estrategia:** Implementar sensores inteligentes, visualización en dashboards, alertas y recomendaciones.

#### 1.2.2.2. Lean UX Assumptions

- Los usuarios enfrentan dificultades para mantener condiciones adecuadas de almacenamiento sin supervisión constante.
- Los usuarios estarían dispuestos a pagar por una solución que reduzca sus pérdidas.
- Los sensores pueden ser integrados sin requerir conocimientos técnicos avanzados.
- El mercado objetivo usa dispositivos móviles o laptops para sus operaciones.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que** si implementamos sensores que monitorean temperatura, humedad y peso en tiempo real, **entonces** los usuarios podrán prevenir pérdidas de productos sensibles, **lo que resultará** en una mayor satisfacción y retención.
- **Creemos que** si ofrecemos recomendaciones y reportes visuales, **entonces** los emprendedores podrán tomar decisiones informadas, **lo que resultará** en una mejora operativa y reducción de errores.
- **Creemos que** si facilitamos el registro de productos mediante escaneo o importación de archivos, **entonces** los usuarios podrán adoptar la plataforma rápidamente, **lo que resultará** en una mayor adopción inicial.

#### 1.2.2.4. Lean UX Canvas

| Elemento                     | Descripción                                                                                     |
|-----------------------------|-------------------------------------------------------------------------------------------------|
| **Usuarios**                | Emprendedores que trabajan con productos perecibles o con inventario de alto volumen.           |
| **Problemas**               | Pérdidas por mal almacenamiento, errores humanos, falta de visibilidad.                        |
| **Solución propuesta**      | Plataforma con sensores conectados, dashboards, alertas y recomendaciones automáticas.          |
| **Resultados esperados**    | Conservación óptima de productos, reducción de errores, mayor control operativo.                |
| **Métricas clave**          | Reducción de mermas, ahorro de tiempo, tasa de alertas atendidas, nivel de adopción.            |

---

## 1.3. Segmentos Objetivo

### Segmento 1: Emprendedores que gestionan productos sensibles al ambiente

**Descripción:** Personas que elaboran, almacenan o venden productos que requieren condiciones específicas para mantenerse en buen estado, como temperatura, humedad o peso controlado.

**Ejemplos:** Productores de alimentos, reposteros, emprendedores de cosmética natural, farmacéuticos artesanales.

**Necesidad principal:** Monitorear de forma continua las condiciones ambientales de almacenamiento, recibir alertas automáticas y actuar rápidamente para evitar pérdidas.

**Sustento estadístico:** Según el INEI, el 67% de microempresas del sector alimentos y bebidas no utiliza sistemas digitales para la gestión de insumos (2023).

---

### Segmento 2: Emprendedores que manejan altos volúmenes de inventario manualmente

**Descripción:** Personas que, a pesar de manejar muchos productos, siguen utilizando métodos manuales (papel, Excel) para controlar entradas, salidas y stock.

**Ejemplos:** Artesanos textiles, emprendedores de ecommerce, vendedores por redes sociales, pequeños fabricantes.

**Necesidad principal:** Digitalizar el control de inventario para reducir errores, ahorrar tiempo y mejorar la trazabilidad de los productos.

**Sustento estadístico:** Un estudio del BID (2022) indica que el 74% de las microempresas en LATAM no tiene un sistema automatizado de control de inventarios.

# Capitulo II: Requeriments Elicitation & Analysis

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


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
|Comunica oralmente con efectividad a diferentes rangos de audiencia. | <br> **Marco Nakasone:** <br> **TB1:** <br> Durante la primera entrega me encargue de hacer una parte del capítulo 3, agregando las epics, las user stories, los impact mapping y el product backlog, pude obtener más conocimiento de como se puede hacer bien un impact mapping, y a la vez como poder integrar las historias de usuario en un proyecto. <br>|
|Comunica por escrito con efectividad a diferentes rangos de audiencia.| <br> **Marco Nakasone:** <br> **TB1:** <br> Durante la primera entrega pude crear las historias de usuario, basandome en entrevistas e informacion recopilada con respecto a nuestro proyecto, aquí pude aprender mejor sobre lo que necesitan nuestros usuarios objetivos.| 

# Capítulo I: Introduccion
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

***Mision:***

***Visión:***

### 1.1.2. Perfiles de integrantes del equipo

|                                                                   | Apellido y Nombre               | Carrera                | Acerca de                                                                                                                                                                                                                                                                                                                                                                      | Habilidades                                                                                             |
|-------------------------------------------------------------------|---------------------------------|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| |  | Ingeniería de Software | Escribir aqui | Escribir aqui |
| |  | Ingeniería de Software | Escribir aqui | Escribir aqui |
| |  | Ingeniería de Software | Escribir aqui | Escribir aqui |
| |  | Ingeniería de Software | Escribir aqui | Escribir aqui |
| |  | Ingeniería de Software | Escribir aqui | Escribir aqui |

## 1.2. Solution Profile

Product Name: 

### 1.2.1. Antecedentes y problemática
**Antecedentes:**

**Problematicas:**

**What**
* 

**Why: ¿Por qué es importante que se gestione el inventario en los restaurantes?**

**Who: ¿Quienes se ven afectados?**
*

**When: ¿Cuándo sucede la problemática?**
* 

**Where: ¿Dondé implementaríamos nuestra solución?**
*

**How: ¿Cómo ayudará nuestra solución?**

**How much: ¿Cúanto costará?**

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas.

## 1.3. Segmentos Objetivos

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
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

En la próxima sección, se presentará el sprint #1 con la primera versión del trabajo para la entrega del proyecto, donde se mostrará la organización, distribución y resultados del landing page.

Sprint # |Date |Time |Location |Prepared By |Attendees|
| :- | :- | :- | :- | :- | :- |
|1|10/04/2025 |7:00 pm|Reunión mediante Meet| Alvarado De La Cruz, Juan Carlos|<p>Barrientos Quispe, Marcelo . </p><p>Rioja Nuñez, Franco Diego.</p><p>Nakasone Gomes, Marco.</p><p>Rivera Ticllacuri, Omar Harold</p>|
|Sprint 1 Goal |Sprint 1 Velocity |Sum of Story Points||||
|Elaborar y diseñar el landing page informativa para la aplicación EasyStock.|<p>18</p><p></p>|18||||

#### 5.2.1.2. Aspect Leaders and Collaborators
En el desarrollo del landing page y el reporte de KeepItFresh, se han identificado líderes responsables y colaboradores clave para cada aspecto funcional y técnico del proyecto. Esta distribución asegura una ejecución eficiente, promoviendo la especialización, la colaboración entre áreas y una comunicación fluida entre todos los miembros del equipo.

#### 5.2.1.3. Sprint Backlog 1

En el primer sprint, el equipo se enfocó en crear una landing page atractiva y funcional, organizando y asignando tareas mediante el cuadro de Sprint según las habilidades de cada miembro.

|Sprint #||Sprint 1||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|User Story||Work Item / Task||||||
|Id|Title|Id|Title|Descripción|Estimación (Hours)|Assigned to|Status (In -process / To - review / Done)|
|US01|Descripción de la web|UT01|Acerca de la web|Descripción de lo que trata nuestra pagina web. |4|Barrientos Quispe, Marcelo|Done|
|US02|Accesibilidad del contenido|UT02|Disponibilidad accesible del contenido.|Que la página muestre el contenido correctamente (imágenes y enlaces).|8|Rioja Nuñez, Franco|Done|
|US02|Accesibilidad del contenido|UT03|Diseño responsive de la página|Que la página se visualice correctamente en cualquier dispositivo.|6|Rivera Ticllacuri, Omar Harold|Done|

#### 5.2.1.4. Development Evidence for Sprint Review
Evidencia del desarrollo mediante commits:

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/evidence.png?raw=true" style="width: 100%;"/>

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/evidence1.png?raw=true" style="width: 100%;"/>

#### 5.2.1.5. Execution Evidence for Sprint Review
En este sprint hemos logrado desplegar el diseño de la landing page, aquí podemos encontrar las secciones en donde el usuario va a conocer nuestro producto, con el que se va a familiarizar con los costos de nuestros servicios, etc.

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/home.png?raw=true" style="width: 100%;"/>

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/about.png?raw=true" style="width: 100%;"/>

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/features.png?raw=true" style="width: 100%;"/>

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/plans.png?raw=true" style="width: 100%;"/>

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/exp.png?raw=true" style="width: 100%;"/>

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/contact.png?raw=true" style="width: 100%;"/>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Esta sección reúne la documentación de los servicios que gestionan la vinculación entre creadores de contenido e instituciones comerciales dentro de la plataforma. Se detalla la estructura de los endpoints que permiten consultar perfiles de influencers, los cuales contienen información relevante sobre su base de seguidores, indicadores clave de rendimiento, tarifas de colaboración, y registros de campañas anteriores con sus respectivos resultados. 

También se incluyen endpoints que permiten acceder a valoraciones y recomendaciones emitidas por marcas que han trabajado con dichos influencers.

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/service%20for%20sprints,%20este%20era.png?raw=true"/>

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Utilizando la funcionalidad de GitHub Pages, llevamos a cabo el proceso de despliegue del sitio web correspondiente a este Sprint. Para ello, accedimos a la configuración del repositorio y completamos los campos requeridos por la plataforma.

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/despliegue%201.png?raw=true">

## Pagina Desplegada

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/despliegue%202.png?raw=true">

link de la pagina: https://upc-pre-202501-1asi0729-4350-rurasqay.github.io/UPC-PRE-202501-1ASI0729-4350-Rurasqay-landing-page/

#### 5.2.1.8. Team Collaboration Insights during Sprint

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/service%20for%20sprints.png?raw=true">

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/insight.png?raw=true"/>


## 5.2.2. Sprint 2
### 5.2.2.1.Sprint Planning 2.

En la siguiente sección se presenta el sprint #2, centrado en la implementación de la aplicación WebResponsive de EasyStock, donde se integraron funcionalidades clave priorizadas de las épicas principales, como la gestión de productos, sensores y sistema de alertas.

|Sprint #|Date|Time|Location|Prepared By|Attendees|
| :- | :- | :- | :- | :- | :- |
|2|24/04/2025|6:30 pm|Reunión mediante Meet|Alvarado De La Cruz, Juan Carlos|<p>Barrientos Quispe, Marcelo.</p><p>Nakasone Gomes, Marco.</p><p>Franco Diego.</p><p>Rivera Ticllacuri, Omar Harold</p><p>Alvarado De La Cruz, Juan Carlos</p>|
|Sprint 2 Goal|Sprint 2 Velocity|Sum of Story Points||||
|Desarrollar la aplicación WebResponsive con funcionalidades clave: agregar/editar productos, visualización de sensores y activación de alertas.|<p>25</p>|25||||

### 5.2.2.2. Aspect Leaders and Collaborators.
#### 5.2.2.3. Sprint Backlog 2


|Sprint #||Sprint 1||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|User Story||Work Item / Task||||||
|Id|Title|Id|Title|Descripción|Estimación (Hours)|Assigned to|Status (In -process / To - review / Done)|
|US01|Descripción de la web|UT01|Acerca de la web|Descripción de lo que trata nuestra página web.|4|Barrientos Quispe, Marcelo|Done|
|US02|Accesibilidad del contenido|UT02|Disponibilidad accesible del contenido.|Que la página muestre el contenido correctamente (imágenes y enlaces).|8|Rioja Nuñez, Franco|Done|
|US02|Accesibilidad del contenido|UT03|Diseño responsive de la página|Que la página se visualice correctamente en cualquier dispositivo.|6|Rivera Ticllacuri, Omar Harold|Done|
|Sprint #||Sprint 2||||||
|User Story||Work Item / Task||||||
|Id|Title|Id|Title|Descripción|Estimación (Hours)|Assigned to|Status (In -process / To - review / Done)|
|US03|Aplicación WebResponsive con funcionalidades clave|UT04|Desarrollo base de la app responsive|Estructura inicial de la app con soporte responsive y navegación general.|6|Equipo completo|Done|
|US04|Gestión de productos|UT05|Agregar productos|Permitir a los usuarios agregar productos con nombre, precio y descripción.|4|Marco Nakasone|Done|
|US04|Gestión de productos|UT06|Editar productos|Funcionalidad para modificar información de productos existentes.|4|Marco Nakasone|Done|
|US04|Gestión de productos|UT07|Detalle de producto|Visualizar los detalles individuales de cada producto.|3|Marco Nakasone|Done|
|US05|Alertas del sistema|UT08|Activación de alertas|Módulo para activar alertas ante eventos relevantes del sistema.|3|Marcelo Barrientos Quispe|Done|
|US06|Gestión de sensores|UT09|Asignar sensor|Funcionalidad para asociar sensores a ubicaciones o productos.|5|Diego Franco|Done|
|US06|Gestión de sensores|UT10|Vista de sensores|Vista que permite visualizar los sensores activos y sus datos.|4|Juan Alvarado|Done|

#### 5.2.2.4. Development Evidence for Sprint 2 Review
Evidencia del desarrollo mediante commits:
Commits de la rama inventory:
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/project-report/Images/commits-inventory.PNG?raw=true"/>

Commits de la rama master:
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/project-report/Images/commits-master.PNG?raw=true"/>

Commits de la rama products-sensors-view:
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/project-report/Images/commits-products.PNG?raw=true"/>

Commits de la rama sensors-view:
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/project-report/Images/commits-sensors.PNG?raw=true"/>

#### 5.2.2.5. Execution Evidence for Sprint 2 Review

Durante este sprint se logró desplegar exitosamente el frontend de la aplicación web EasyStock, incorporando las funcionalidades esenciales priorizadas. Entre las principales características implementadas se encuentran: el registro y edición de productos, la visualización de la lista completa de productos, la vista detallada de sensores disponibles, así como la asignación de sensores a productos específicos. Además, se incluyó el módulo de gestión del producto por parte del rol correspondiente y el sistema de alertas activas, permitiendo una supervisión eficiente del estado de los productos almacenados. Estas funcionalidades representan un avance significativo en el desarrollo del sistema, alineándose con los objetivos establecidos en las épicas clave del proyecto.

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/addproduct.png?raw=true"/>
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/editproduct.png?raw=true"/>
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/project-report/Images/commits-products.PNG?raw=true"/>
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/sensors%20view.png?raw=true"/>
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/main/Images/asignar%20sensores.jpg?raw=true"/>

#### 5.2.2.6. Services Documentation Evidence for Sprint 2 Review

#### 5.2.2.7. Software Deployment Evidence for Sprint 2 Review

#### 5.2.2.8. Team Collaboration Insights during Sprint 2

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/insights1.png?raw=true"/>
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/insigths2.png?raw=true"/>

front:

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/insightsfront.png?raw=true">
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/product-implementation/Images/insightsfront2.png?raw=true">

# Conclusiones
## Conclusiones y recomendaciones

## Video About-the-Team

## Bibliografía

## Anexos

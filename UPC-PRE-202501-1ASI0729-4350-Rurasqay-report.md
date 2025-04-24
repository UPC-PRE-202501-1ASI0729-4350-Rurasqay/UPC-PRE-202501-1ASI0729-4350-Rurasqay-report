
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

### Sensitech:
#### Ofrece monitoreo automatizado de temperatura y humedad en almacenes mediante sensores inalámbricos. Proporciona alertas en tiempo real y acceso remoto a datos históricos, cumpliendo con normativas como las Buenas Prácticas de Distribución (cGDP) .

### Sistema Borea de Torsa:
#### Implementado por empresas como Barker en Perú, este sistema permite la supervisión en tiempo real de temperatura y humedad en almacenes, mejorando la trazabilidad y cumpliendo con normativas del sector alimentario .

### Bambu B2B
#### Plataforma SaaS que automatiza reportes y consolida datos de ventas e inventarios en tiempo real. Ofrece alertas de stock, previsión de demanda y personalización avanzada para adaptarse a las necesidades específicas de cada empresa .

### 2.1.1. Análisis competitivo

## Competitive Analysis Landscape

### ¿Por qué llevar a cabo este análisis?  

### Comprender el entorno competitivo de EasyStock nos permitirá evaluar qué tan alineados estamos con las necesidades del mercado, identificar elementos clave que nos diferencien y detectar áreas de mejora en comparación con soluciones similares

|                        Competidores                        | EasyStock  | Sensitech                                                                                                                    | Sistema Borea de Torsa                                                                                                    | Bambu B2B                                                                                                              |
|:----------------------------------------------------------:|------------|------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
|                          **Logo**                          |
|                         **Perfil**                         |
|                          Overview                          | Startup enfocada en la gestión de inventarios para emprendedores mediante sensores de temperatura y peso.	           | Empresa global especializada en soluciones de visibilidad de la cadena de frío para productos sensibles a la temperatura.	   | Sistema de monitoreo continuo de temperatura y humedad para almacenes y transporte, con enfoque en eficiencia energética.		 | Plataforma SaaS que automatiza reportes y consolida datos de ventas e inventarios en tiempo real para el sector retail.|
| Ventaja competitiva <br> ¿Qué valor ofrece a los clientes? | Modelo flexible de suscripción y alquiler de sensores, interfaz amigable y enfoque en emprendedores de sectores específicos.	           | Amplia experiencia global, cumplimiento de normativas internacionales y soluciones integrales para la cadena de suministro.	 | Reducción significativa del consumo energético y climatización autónoma de almacenes.                                     | Personalización avanzada, previsión de demanda y compatibilidad con tecnologías como RFID y códigos de barras.         |
|                    **Perfil Marketing**                    |
|                      Mercado objetivo                      | Emprendedores en sectores alimentario, textil y manufacturero en Perú.	           | Empresas globales en sectores de alimentos, ciencias de la vida, bienes de consumo e industrial.	                            | Empresas en sectores logístico, farmacéutico y agroalimentario en España y América Latina.	                               | Empresas del sector retail que buscan optimizar la gestión de ventas e inventarios.                                    
|                  Estrategias de marketing                  | Enfoque en educación y soporte al cliente, recursos educativos y soporte continuo.	           | Participación en ferias internacionales, contenido educativo y alianzas estratégicas.                                        | Casos de estudio, contenido técnico y presencia en eventos del sector logístico.                                          | Campañas de marketing digital, webinars y contenido personalizado para el sector retail.                               |
|                   **Perfil de Producto**                   |
|                   Productos & Servicios                    | Monitoreo en tiempo real de inventarios, alertas automáticas y optimización de recursos.	           | Monitores de temperatura, indicadores electrónicos, registradores de datos y soluciones de monitoreo de instalaciones.       | Sensores y registradores de temperatura, humedad y gases, con plataforma de gestión de datos.                             | Automatización de reportes, consolidación de datos de ventas e inventarios, y previsión de demanda.                    |
|                      Precios & Costos                      | Modelo de suscripción mensual con opciones de alquiler de sensores.	           | Precios personalizados según necesidades del cliente y alcance del proyecto.          | Inversión inicial con retorno estimado en menos de un año gracias al ahorro energético.	   | Planes de suscripción adaptados al tamaño y necesidades de la empresa.                                                 |
|        Canales de distribución <br> (Web y/o Móvil)        | Plataforma web y aplicación móvil.	           | Plataforma web con acceso a través de dispositivos móviles.	                                                            | Plataforma web con acceso a través de dispositivos móviles.	                                                                                                                          | Plataforma web con integración a sistemas de punto de venta y dispositivos móviles.                                    |
|                     **Análisis SWOT**                      |
|                         Fortalezas                         | Flexibilidad en el modelo de negocio, enfoque en emprendedores y facilidad de uso.	           | Experiencia global, cumplimiento de normativas y soluciones integrales.	                                                                                                                             | Eficiencia energética, monitoreo en tiempo real y climatización autónoma.	                                                                                                                          | Personalización, previsión de demanda y compatibilidad tecnológica.                                                    |
|                        Debilidades                         | Presencia limitada en el mercado internacional           | Costos elevados para pequeñas empresas y complejidad en la implementación.	                                                                                                                            | Enfoque limitado a sectores específicos y necesidad de inversión inicial.	                                                                                                                          | Enfoque en el sector retail, lo que puede limitar su aplicabilidad en otros sectores.                                  |
|                       Oportunidades                        | Expansión a otros mercados de América Latina y desarrollo de nuevas funcionalidades.	           | Integración con tecnologías emergentes y expansión a nuevos mercados.	                                                                                                                             | Aplicación en nuevos sectores y desarrollo de nuevas funcionalidades.	                                                                                                                          | Expansión a otros sectores y mejora continua de la plataforma.                                                         |
|                          Amenazas                          | Competencia creciente en el mercado de gestión de inventarios y cambios en las regulaciones locales.	           | Competencia de nuevas empresas tecnológicas y cambios en las regulaciones internacionales.	                                                                                                                             | Avances tecnológicos de la competencia y cambios en las regulaciones del sector.	                                                                                                                          | Cambios en las tendencias del retail y aparición de nuevas soluciones tecnológicas.|


### 2.1.2. Estrategias y tácticas frente a competidores

| **MATRIZ FODA y C.A.M.E** | **Oportunidades: Creciente necesidad de digitalización y automatización de inventarios** | **Amenazas: Aumento de competidores tecnológicos y cambios en regulación de dispositivos IoT** |
|---------------------------|------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| **Fortalezas:** <br> Tecnología accesible, modelo por suscripción y enfoque en emprendedores | Potenciar la fidelización mediante un soporte constante y personalizado para evitar la migración a soluciones más complejas o costosas. Resaltar el valor de los sensores físicos como diferenciador único. | Mantener vigilancia activa sobre regulaciones y adaptar los sensores a normativas. Aprovechar la simplicidad de EasyStock para posicionarse como alternativa más fácil frente a soluciones complejas. |
| **Debilidades:** <br> Poca presencia internacional | Intensificar campañas de visibilidad en redes, ferias locales y alianzas con incubadoras para construir reputación y reconocimiento. | Mostrar que la solución es adaptable a cualquier sector y escala. Resaltar que no requiere infraestructura costosa como otras opciones del mercado. |

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

#### En esta sección se presentan las preguntas realizadas a los entrevistados, organizadas en tres partes: introducción, preguntas centrales y cierre.

### 1. Introducción
#### Aquí es donde se recopila la información clave para validar la problemática y evaluar el interés en una solución como EasyStock.

1. ¿Podrías contarme brevemente sobre tu emprendimiento y los productos que manejas?
2. ¿Cuánto tiempo llevas operando con tu emprendimiento?
3. ¿Cuál es tu rol principal dentro del emprendimiento?
---

### 2. Preguntas centrales
#### Estas preguntas sirven para establecer confianza y comprender el entorno general del emprendimiento.

4. ¿Qué tipo de insumos o productos suelen almacenar con más frecuencia?
5. ¿Te apoyas en tecnología para automatizar procesos o prefieres hacerlo todo manualmente?
6. ¿Cómo gestionas actualmente el inventario de tus productos o insumos?
7. ¿Qué tan frecuente es que pierdas productos por mal almacenamiento (por ejemplo, por temperatura o caducidad)?
8. ¿Has tenido dificultades para saber cuándo reponer stock o qué productos ya no están en condiciones óptimas?
9. ¿Con qué frecuencia realizas controles físicos de tu inventario? ¿Te toma mucho tiempo?

---

### 3. Cierre 
#### Estas preguntas ayudan a validar la propuesta de valor y entender qué funcionalidades serían más útiles para el usuario.

10. ¿Te interesaría tener sensores que te alerten si un alimento o insumo está fuera de su temperatura ideal?
11. ¿Qué tan útil crees que sería tener un sistema que te notifique automáticamente sobre irregularidades en tus almacenes?
12. ¿Qué características te parecerían imprescindibles en una herramienta de gestión de inventario como esta?
13. ¿Qué nivel de dificultad o curva de aprendizaje estarías dispuesto a aceptar para usar una nueva plataforma?

### 2.2.2. Registro de entrevistas


### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding 

### 2.3.1. User Personas

## Segmento Objetivo 1

<img src="./Images/Luis Gálvez_User Persona.png"></img>

## Segmento Objetivo 2

<img src="./Images/Luis Gómez_User Persona.png"></img>

### 2.3.2. User Task Matrix 

## Segmento Objetivo 1

<img src="./Images/task matrix 1.PNG"></img>

## Segmento Objetivo 2

<img src="./Images/task matrix 2.PNG"></img>

### 2.3.3. User Journey Mapping

## Segmento Objetivo 1

<img src="./Images/Segmento 1 journey map 1.png"></img>

## Segmento Objetivo 2

<img src="./Images/Segmento 2 journey map 2.png"></img>

### 2.3.4. Empathy Mapping

## Segmento Objetivo 1

<img src="./Images/Empathy map segmento 1.png"></img>

## Segmento Objetivo 2

<img src="./Images/Empathy map segmento 2.png"></img>

### 2.3.5. As-Is Scenario Mapping

## Segmento Objetivo 1

<img src="./Images/Scenario Mapping Segmento 1.PNG"></img>

## Segmento Objetivo 2

<img src="./Images/Scenario Mapping Segmento 2.PNG"></img>

## 2.4. Ubiquitous Language

### En esta sección se muestran los términos y conceptos que se usan usualmente en nustro proyecto.

* **Ítem:** Representa cualquier elemento gestionado en el inventario (alimento, materia prima, producto terminado).
* **Stock:** La cantidad actual disponible de un Ítem.
* **Alerta:** Notificación sobre cambios importantes en el stock o condiciones.
* **Condición:** Atributo relevante de un Ítem (ej. temperatura, peso, fecha de caducidad).
* **Pedido:** Solicitud para adquirir más Ítems.
* **Reposición:** Acción de reabastecer el stock de un Ítem.
* **Entrada:** Registro del aumento de stock de un Ítem.
* **Salida:** Registro de la disminución de stock de un Ítem.
* **Proveedor:** Entidad que suministra los Ítems.
* **Ubicación:** Lugar donde se almacena un Ítem.
* **Informe:** Resumen de datos relevantes del inventario.
* **Catálogo:** Lista de todos los Ítems gestionados.
* **Transacción:** Cualquier movimiento que afecta el stock de un Ítem.
* **Usuario:** Persona que utiliza EasyStock.
* **Almacén:** Espacio físico de almacenamiento.
* **Límite:** Valor establecido para generar alertas (ej. stock mínimo, temperatura máxima).
* **Unidad:** Medida en la que se gestiona el stock (ej. kg, unidades, metros).

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

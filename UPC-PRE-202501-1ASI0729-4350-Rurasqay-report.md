# `<center>`COURSE PROJECT`<center>`

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

### `<center>`Team Members`</center>`

<center>

| Member                           | Code       |
| -------------------------------- | ---------- |
| Alvarado De La Cruz, Juan Carlos | u202216150 |
| Barrientos Quispe, Marcelo       | u20221e646 |
| Rioja Nuñez, Franco Diego       | u202221597 |
| Nakasone Gomes, Marco Antonio    | u202210790 |
| Rivera Ticllacuri, Omar Harold   | u202214214 |

`<br>` ABRIL 2025

</center>

<center>

# Registro de Versiones del Informe

| Version | Fecha      | Autor   | Descripción de Modificación |
| ------- | ---------- | ------- | ----------------------------- |
| 0.0     | 02/04/2025 | Grupo 3 | Creación del documento       |
|         | 04/04/2025 |         |                               |
|         | 04/04/2025 |         |                               |

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

[Capítulo II: Requirements Elicitation &amp; Analysi](#capítulo-ii-requirements-elicitation--analysis)

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

[Capítulo V: Product Implementation, Validation &amp; Deployment](#capítulo-v-product-implementation-validation-deployment)

[5.1. Software Configuration Management.](#51-software-configuration-management)
[5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
[5.1.2. Source Code Management.](#512-source-code-management)
[5.1.3. Source Code Style Guide &amp; Conventions.](#513-source-code-style-guide--conventions)
[5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)

[5.2. Landing Page, Services &amp; Applications Implementation.](#52-landing-page-services--applications-implementation)
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

| Criterio Especifico                                                    | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Conclusiones                                                                                                                                                                                                                                                                                                                                               |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Comunica oralmente con efectividad a diferentes rangos de audiencia.   | `<br>` **Marco Nakasone:** `<br>` **TB1:** `<br>` Durante la primera entrega me encargue de hacer una parte del capítulo 3, agregando las epics, las user stories, los impact mapping y el product backlog, pude obtener más conocimiento de como se puede hacer bien un impact mapping, y a la vez como poder integrar las historias de usuario en un proyecto. `<br>` `<br>` **Omar Rivera:**`<br>`**TB1:**`<br>` Durante el desarrollo del proyecto, me enfoqué en el Capítulo 4, contribuyendo activamente en el product design, especialmente en la creación y estructura de la Landing Page, así como en los elementos visuales que garantizan una experiencia coherente y atractiva para el usuario.`<br>` `<br>` **Juan Carlos Alvarado:** `<br>` **TB1:** `<br>` Participé activamente en las presentaciones del equipo, explicando la problemática identificada a partir de los segmentos objetivo y las entrevistas. Me encargué de comunicar con claridad el enfoque de EasyStock y sus beneficios para distintos perfiles de emprendedores. Esto me ayudó a reforzar mis habilidades para comunicar ideas técnicas a audiencias no técnicas. `<br>` `<br>` **Marcelo Barrientos Quispe:** `<br>` **TB1:** `<br>` Durante la primera entrega me encargue del C4 model, el data base diagram, class diagram que son necesarias para el funcionamiento del producto a realizar.`<br>` `<br>` **Franco Diego Rioja Nuñez:** `<br>` **TB1:** `<br>` Durante esta entrega me encargue de hacer el Capitulo 2 en el cual analicé a la competencia y vi las posibles oportunidades contra ellos.                                                                                              | TB1: el equipo demostró un enfoque integral combinando estrategia, diseño, análisis técnico y comunicación efectiva, lo que permitió sentar las `<br>`bases sólidas para el desarrollo de EasyStock como una solución viable y centrada en las necesidades reales de los emprendedores.                                                          |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | `<br>` **Marco Nakasone:** `<br>` **TB1:** `<br>` Durante la primera entrega pude crear las historias de usuario, basandome en entrevistas e informacion recopilada con respecto a nuestro proyecto, aquí pude aprender mejor sobre lo que necesitan nuestros usuarios objetivos.`<br>`**Omar Rivera:** `<br>` **TB1:** `<br>` En el Capítulo 4, me encargué del diseño UI, incluyendo la elaboración de las Style Guidelines y la estructura visual de la Landing Page. Mi trabajo se centró en brindar una experiencia clara, intuitiva y estéticamente cuidada para los usuarios de la aplicación web.`<br><br>` **Juan Carlos Alvarado:** `<br>` **TB1:** `<br>` Me encargué de redactar el Capítulo I del informe, incluyendo la descripción de la startup, antecedentes y problemática, análisis 5W2H, Lean UX Process y Lean UX Canvas. También elaboré respuestas realistas basadas en user stories para entrevistas simuladas. Esto me permitió aplicar una comunicación escrita técnica y estructurada, manteniendo claridad para lectores con o sin experiencia técnica. `<br>` `<br>` **Marcelo Barrientos Quispe:** `<br>` **TB1:** `<br>` En el transcurso de la entrega me enfoque en un desarrollo estructurado y organizado para tenerlo como base necesaria para el proyecto siendo esta la guía básica para realizar con la cual guiarnos y avanzar dicho proyecto `<br>` `<br>` **Franco Diego Rioja Nuñez:** `<br>` **TB1:** `<br>` Durante esta entrega me encargue de la revisión de las entrevistas de las personas relacionadas con el segmento objetivo y ver cuales son nuestras debilidades y usar el feedback de los entrevistados para poder seguir progresando. | Tb1: El equipo combinó investigación profunda, diseño centrado en el usuario y una sólida base estructural,`<br>`permitiendo construir una propuesta coherente y alineada con las necesidades reales del segmento objetivo,`<br>` a través de un trabajo colaborativo que integra análisis, diseño, redacción técnica y validación continua. |

# Capítulo I: Introduccion

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**RurasqaySoft** es una startup de base tecnológica orientada a brindar soluciones digitales prácticas para los desafíos reales que enfrentan emprendedores y pequeñas empresas en Perú. Nuestro objetivo es desarrollar herramientas accesibles que digitalicen procesos clave como el control de inventarios, permitiendo a los usuarios mejorar su eficiencia, evitar pérdidas y tomar decisiones basadas en datos.

**Misión:** Desarrollar soluciones tecnológicas accesibles que ayuden a los emprendedores a gestionar eficientemente sus operaciones, promoviendo sostenibilidad y crecimiento.

**Visión:** Convertirse en referente latinoamericano en soluciones digitales para la gestión operativa de micro y pequeñas empresas.

### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                                                                                                                                                     | Apellido y Nombre                | Carrera                 | Acerca de                                                                                                                                                                                                                                                                             | Código    |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| `<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/project-report/Images/marco.jpg?raw=true" width="300"/>` | Nakasone Gomes, Marco Antonio    | Ingeniería de Software | Soy estudiante de Ingeniería de software, tengo cualidades como la perseverancia, que me va a ayudar a ser resiliente ante cualquier adversidad que se nos presente más adelante en el trabajo y también soy buen compañero de trabajo que siempre quiere lo mejor para su grupo. | u202210790 |
| `<img src="Images/Omar.jpeg"/>`                                                                                                                                                        | Omar Harold Rivera Ticllacuri    | Ingeniería de Software | Soy estudiante de Ingeniería de Software, tengo 20 años. Me considero una persona disciplinada y responsable, con experiencia en el desarrollo de software de entretenimiento. Estoy comprometido a aportar al grupo para cumplir con éxito los objetivos del proyecto.            | u202214214 |
| `<img src='./Images/marcelo.png'/>`                                                                                                                                                    | Marcelo Barrientos Quispe        | Ingeniería de Software | Soy estudiante de Ingeniería de Software, tengo 19 años. Me considero alguien muy a fin a las tecnologías de Javascript y sus frameworks como React, Angular y Node. Me considero buen compañero y muy compretido con el curso y con el trabajo.                                  | u20221e646 |
| `<img src='./Images/diego.jpg'/>`                                                                                                                                                      | Franco Diego Rioja Nuñez        | Ingeniería de Software | Soy estudiante de Ingeniería de Software, apasionado por el aprendizaje continuo y la formación autodidacta. Me destaco por mi buena disposición para el trabajo en equipo y mi habilidad para desenvolverme eficazmente en entornos colaborativos.                               | u202221597 |
| `<img src="Images/juan.jpg">`                                                                                                                                                          | Alvarado De La Cruz, Juan Carlos | Ingeniería de Software | Soy estudiante de la carrera de Ing. de Software. Me gusta resolver problemas y aprender cosas que son de mi interés, tengo experiencia programando en C++ y en Python.                                                                                                              | u202216150 |

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

| Elemento                       | Descripción                                                                            |
| ------------------------------ | --------------------------------------------------------------------------------------- |
| **Usuarios**             | Emprendedores que trabajan con productos perecibles o con inventario de alto volumen.   |
| **Problemas**            | Pérdidas por mal almacenamiento, errores humanos, falta de visibilidad.                |
| **Solución propuesta**  | Plataforma con sensores conectados, dashboards, alertas y recomendaciones automáticas. |
| **Resultados esperados** | Conservación óptima de productos, reducción de errores, mayor control operativo.     |
| **Métricas clave**      | Reducción de mermas, ahorro de tiempo, tasa de alertas atendidas, nivel de adopción.  |

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

|                          Competidores                          | EasyStock                                                                                                                      | Sensitech                                                                                                                   | Sistema Borea de Torsa                                                                                                     | Bambu B2B                                                                                                               |
| :-------------------------------------------------------------: | ------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
|                         **Logo**                         | `<img src="Images/LogoEasyStock.png" width="100px"/>`                                                                        | `<img src="/Images/sensitech.png" width="100px">`                                                                         | `<img src="/Images/torsa.png" width="100px" />`                                                                          | `<img src="/Images/bambub2b.png" width="100px" />`                                                                    |
|                        **Perfil**                        |                                                                                                                                |                                                                                                                             |                                                                                                                            |                                                                                                                         |
|                            Overview                            | Startup enfocada en la gestión de inventarios para emprendedores mediante sensores de temperatura y peso.                     | Empresa global especializada en soluciones de visibilidad de la cadena de frío para productos sensibles a la temperatura.  | Sistema de monitoreo continuo de temperatura y humedad para almacenes y transporte, con enfoque en eficiencia energética. | Plataforma SaaS que automatiza reportes y consolida datos de ventas e inventarios en tiempo real para el sector retail. |
| Ventaja competitiva`<br>` ¿Qué valor ofrece a los clientes? | Modelo flexible de suscripción y alquiler de sensores, interfaz amigable y enfoque en emprendedores de sectores específicos. | Amplia experiencia global, cumplimiento de normativas internacionales y soluciones integrales para la cadena de suministro. | Reducción significativa del consumo energético y climatización autónoma de almacenes.                                  | Personalización avanzada, previsión de demanda y compatibilidad con tecnologías como RFID y códigos de barras.      |
|                   **Perfil Marketing**                   |                                                                                                                                |                                                                                                                             |                                                                                                                            |                                                                                                                         |
|                        Mercado objetivo                        | Emprendedores en sectores alimentario, textil y manufacturero en Perú.                                                        | Empresas globales en sectores de alimentos, ciencias de la vida, bienes de consumo e industrial.                            | Empresas en sectores logístico, farmacéutico y agroalimentario en España y América Latina.                             | Empresas del sector retail que buscan optimizar la gestión de ventas e inventarios.                                    |
|                    Estrategias de marketing                    | Enfoque en educación y soporte al cliente, recursos educativos y soporte continuo.                                            | Participación en ferias internacionales, contenido educativo y alianzas estratégicas.                                     | Casos de estudio, contenido técnico y presencia en eventos del sector logístico.                                         | Campañas de marketing digital, webinars y contenido personalizado para el sector retail.                               |
|                  **Perfil de Producto**                  |                                                                                                                                |                                                                                                                             |                                                                                                                            |                                                                                                                         |
|                      Productos & Servicios                      | Monitoreo en tiempo real de inventarios, alertas automáticas y optimización de recursos.                                     | Monitores de temperatura, indicadores electrónicos, registradores de datos y soluciones de monitoreo de instalaciones.     | Sensores y registradores de temperatura, humedad y gases, con plataforma de gestión de datos.                             | Automatización de reportes, consolidación de datos de ventas e inventarios, y previsión de demanda.                  |
|                        Precios & Costos                        | Modelo de suscripción mensual con opciones de alquiler de sensores.                                                           | Precios personalizados según necesidades del cliente y alcance del proyecto.                                               | Inversión inicial con retorno estimado en menos de un año gracias al ahorro energético.                                 | Planes de suscripción adaptados al tamaño y necesidades de la empresa.                                                |
|        Canales de distribución`<br>` (Web y/o Móvil)        | Plataforma web y aplicación móvil.                                                                                           | Plataforma web con acceso a través de dispositivos móviles.                                                               | Plataforma web con acceso a través de dispositivos móviles.                                                              | Plataforma web con integración a sistemas de punto de venta y dispositivos móviles.                                   |
|                    **Análisis SWOT**                    |                                                                                                                                |                                                                                                                             |                                                                                                                            |                                                                                                                         |
|                           Fortalezas                           | Flexibilidad en el modelo de negocio, enfoque en emprendedores y facilidad de uso.                                             | Experiencia global, cumplimiento de normativas y soluciones integrales.                                                     | Eficiencia energética, monitoreo en tiempo real y climatización autónoma.                                               | Personalización, previsión de demanda y compatibilidad tecnológica.                                                  |
|                           Debilidades                           | Presencia limitada en el mercado internacional                                                                                 | Costos elevados para pequeñas empresas y complejidad en la implementación.                                                | Enfoque limitado a sectores específicos y necesidad de inversión inicial.                                                | Enfoque en el sector retail, lo que puede limitar su aplicabilidad en otros sectores.                                   |
|                          Oportunidades                          | Expansión a otros mercados de América Latina y desarrollo de nuevas funcionalidades.                                         | Integración con tecnologías emergentes y expansión a nuevos mercados.                                                    | Aplicación en nuevos sectores y desarrollo de nuevas funcionalidades.                                                     | Expansión a otros sectores y mejora continua de la plataforma.                                                         |
|                            Amenazas                            | Competencia creciente en el mercado de gestión de inventarios y cambios en las regulaciones locales.                          | Competencia de nuevas empresas tecnológicas y cambios en las regulaciones internacionales.                                 | Avances tecnológicos de la competencia y cambios en las regulaciones del sector.                                          | Cambios en las tendencias del retail y aparición de nuevas soluciones tecnológicas.                                   |

### 2.1.2. Estrategias y tácticas frente a competidores

| **MATRIZ FODA y C.A.M.E**                                                                          | **Oportunidades: Creciente necesidad de digitalización y automatización de inventarios**                                                                                                                 | **Amenazas: Aumento de competidores tecnológicos y cambios en regulación de dispositivos IoT**                                                                                                  |
| -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Fortalezas:** `<br>` Tecnología accesible, modelo por suscripción y enfoque en emprendedores | Potenciar la fidelización mediante un soporte constante y personalizado para evitar la migración a soluciones más complejas o costosas. Resaltar el valor de los sensores físicos como diferenciador único. | Mantener vigilancia activa sobre regulaciones y adaptar los sensores a normativas. Aprovechar la simplicidad de EasyStock para posicionarse como alternativa más fácil frente a soluciones complejas. |
| **Debilidades:** `<br>` Poca presencia internacional                                             | Intensificar campañas de visibilidad en redes, ferias locales y alianzas con incubadoras para construir reputación y reconocimiento.                                                                           | Mostrar que la solución es adaptable a cualquier sector y escala. Resaltar que no requiere infraestructura costosa como otras opciones del mercado.                                                    |

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

# Entrevista 1 - Bryan Espejo

<img src="/Images/e1.png">

## Conclusion

Bryan tiene una repostería artesanal y gestiona su inventario manualmente,
lo que le ha causado pérdidas por fallas en refrigeración. Prefiere métodos simples
y busca una herramienta fácil de usar que le ofrezca alertas, escaneo de productos y reportes. Está dispuesto a aprender si la plataforma le ahorra tiempo y reduce errores.

**Link de la entrevista:** [Ver Entrevista](https://drive.google.com/file/d/1r0G4PQULNXFDnoZZ9ryi-GXQiYMPuc3Z/viewusp=sharing)

# Entrevista 2 - Joan Teves

<img src="/Images/e2.png">

## Conclusion

Joan dirige un taller textil y usa Google Sheets para controlar inventario,
pero enfrenta pérdidas por desactualización. Busca una herramienta visual y
fácil de usar que le ofrezca alertas, escaneo, importación de datos e historiales,
y que incluya soporte como tutoriales.

**Link de la entrevista:** [Ver Entrevista](https://drive.google.com/file/d/1HRAXXt7-R5y4nMqztPJnCtutI_7U9AkR/view)

# Entrevista 3 - Cyndi Ortega

<img src="/Images/e3.png">

## Conclusion

Cyndi Ortega, con 9 años en publicidad y producción, almacena insumos como acrílico y
cartón. Usa Excel para el inventario, pero ha tenido problemas de control que afectan
su productividad. Está interesada en una solución precisa, con sensores que monitoreen
stock y temperatura para evitar pérdidas.

**Link de la entrevista:** [Ver Entrevista](https://drive.google.com/file/d/1oL1nUDNqsp6ycozSXOkDyd19I8mG3GSU/view?usp=sharing)

# Entrevista 3 - Tahily Esparta

<img src="/Images/e4.png">

## Conclusion

Tahily Esparta, emprendedora de 21 años en Chorrillos, gestiona un negocio de fiambres y
enfrenta dificultades con el control manual de inventario, por lo que valora una herramienta
fácil de usar con alertas automáticas que le ahorre tiempo y reduzca pérdidas por mal almacenamiento.

### 2.2.3. Análisis de entrevistas

En general, los emprendedores entrevistados comparten la necesidad de una herramienta de gestión de inventario sencilla, visual y funcional que les permita reducir pérdidas por desorganización o mal almacenamiento, optimizar su tiempo y mejorar el control de productos sensibles; todos están dispuestos a adoptar nuevas tecnologías siempre que cuenten con soporte, alertas automáticas y faciliten su trabajo diario.

## 2.3. Needfinding

### 2.3.1. User Personas

## Segmento Objetivo 1

`<img src="./Images/Luis Gálvez_User Persona.png"></img>`

## Segmento Objetivo 2

`<img src="./Images/Luis Gómez_User Persona.png"></img>`

### 2.3.2. User Task Matrix

## Segmento Objetivo 1

`<img src="./Images/task matrix 1.PNG"></img>`

## Segmento Objetivo 2

`<img src="./Images/task matrix 2.PNG"></img>`

### 2.3.3. User Journey Mapping

## Segmento Objetivo 1

`<img src="./Images/Segmento 1 journey map 1.png"></img>`

## Segmento Objetivo 2

`<img src="./Images/Segmento 2 journey map 2.png"></img>`

### 2.3.4. Empathy Mapping

## Segmento Objetivo 1

`<img src="./Images/Empathy map segmento 1.png"></img>`

## Segmento Objetivo 2

`<img src="./Images/Empathy map segmento 2.png"></img>`

### 2.3.5. As-Is Scenario Mapping

## Segmento Objetivo 1

`<img src="./Images/Scenario Mapping Segmento 1.PNG"></img>`

## Segmento Objetivo 2

`<img src="./Images/Scenario Mapping Segmento 2.PNG"></img>`

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

### Propietario:

| **Fases**   | **Monitoreo Centralizado del Negocio**                              | **Gestión Estratégica del Equipo y Recursos**                         | **Evaluación y Mejora del Rendimiento**                               | **Toma de Decisiones Informada**                                      |
|-------------|----------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|
| **Doing**   | Visualiza dashboards en tiempo real con datos ambientales y de stock. | Gestiona usuarios, roles y sensores desde una sola interfaz.         | Consulta informes descargables (PDF) y métricas de desempeño.         | Compara ventas vs stock y analiza productos más/menos rotados.        |
| **Thinking**| "Tengo todo bajo control desde una vista integral."                  | "Puedo ajustar fácilmente quién tiene acceso y qué sensores usamos."  | "Es fácil evaluar el rendimiento del equipo y del sistema."            | "Tomo decisiones basadas en datos claros y confiables."               |
| **Feeling** | Tranquilo y empoderado con herramientas estratégicas.                | Confiado en que el sistema se adapta al crecimiento del negocio.      | Satisfecho con la trazabilidad de la operación.                        | Seguro de estar optimizando recursos y mejorando resultados.          |

### Gestor:

| **Fases**   | **Ingreso Ágil y Preciso de Productos**                             | **Asignación y Control Ambiental de Sensores**                        | **Seguimiento y Corrección de Anomalías**                            | **Optimización de Tareas y Registro de Actividades**                  |
|-------------|----------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|
| **Doing**   | Registra productos vía QR, Excel o formulario en segundos.           | Asigna sensores y visualiza condiciones ambientales en tiempo real.   | Recibe alertas si algo falla o las condiciones se salen de rango.     | Consulta su historial de acciones y busca productos fácilmente.       |
| **Thinking**| "Puedo registrar y actualizar el inventario sin perder tiempo."      | "Sé exactamente qué producto está en qué condición."                  | "Estoy al tanto de cualquier problema apenas ocurre."                 | "Sé qué hice y qué me falta hacer, sin depender de nadie más."        |
| **Feeling** | Eficiente y motivado al ver resultados inmediatos.                   | Conectado y atento al estado del almacén.                             | Responsable y en control frente a imprevistos.                        | Organizado y valorado por su impacto en la operación.                |

## 3.2. User Stories

| **Epic 1: Gestión de Inventario**                                                                                                                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** emprendedor<br>**Quiero** gestionar y registrar mi inventario de productos de manera eficiente<br>**Para** tener un control preciso del stock disponible, evitar desabastecimientos y facilitar la toma de decisiones operativas |

| **ID**     | **Título**                                | **Historia de Usuario**                                                                                                            | **Escenarios de Prueba**                                                                                                                                                                                                                                                          | **Prioridad** |
| ---------- | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E1 - US001 | Registro Manual de Producto               | Como gestor, quiero registrar productos manualmente, para tener un control actualizado del inventario.                             | **Escenario 1**: El usuario llena un formulario con nombre, cantidad y categoría del producto. <br> **Escenario 2**: El sistema valida que todos los campos estén completos antes de registrar. <br> **Escenario 3**: Si hay un error (e.g., campo vacío), se muestra un mensaje. | Alta          |
| E1 - US002 | Importación Masiva de Productos           | Como gestor, quiero importar productos desde un archivo Excel, para ahorrar tiempo en el registro inicial del inventario.          | **Escenario 1**: El usuario sube un archivo Excel con productos. <br> **Escenario 2**: El sistema verifica el formato y procesa los datos. <br> **Escenario 3**: Si el archivo tiene errores, se notifican los errores específicos.                                               | Alta          |
| E1 - US003 | Escaneo de Productos para Registro Rápido | Como gestor, quiero escanear productos para registrarlos rápidamente en el inventario, para mejorar la eficiencia.                 | **Escenario 1**: El sistema detecta un código QR o código de barras válido. <br> **Escenario 2**: El sistema muestra los datos precargados del producto. <br> **Escenario 3**: Si no se reconoce el código, se muestra un mensaje de error.                                       | Media         |
| E1 - US004 | Búsqueda de Productos por Nombre o Lote   | Como gestor, quiero buscar productos por nombre o lote, para ubicar rápidamente su información en el sistema. Y asignar productos a estanterías.                     | **Escenario 1**: El usuario escribe parte del nombre o código. <br> **Escenario 2**: El sistema sugiere coincidencias. <br> **Escenario 3**: Si no hay resultados, se notifica al usuario.                                                                                        | Alta          |
| E1 - US005 | Ajuste Rápido de Stock                    | Como gestor, quiero ajustar manualmente el stock de un producto, para corregir diferencias o actualizar cantidades en tiempo real. | **Escenario 1**: El usuario selecciona un producto y cambia la cantidad. <br> **Escenario 2**: El sistema guarda el cambio y actualiza el historial. <br> **Escenario 3**: Si la cantidad ingresada es inválida (e.g., número negativo), se rechaza la acción con un mensaje.     | Alta          |

| **Epic 2: Monitoreo en Tiempo Real con Sensores**                                                                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** gestor de inventario<br>**Quiero** monitorear las condiciones ambientales de mis productos en tiempo real a través de sensores<br>**Para** asegurar que se mantengan en las condiciones óptimas de almacenamiento y prevenir daños por cambios de temperatura, humedad o peso |

| **ID**     | **Título**                               | **Historia de Usuario**                                                                                                                                         | **Escenarios de Prueba**                                                                                                                                                                                                                                                                     | **Prioridad** |
| ---------- | ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E2 - US006 | Visualización en Tiempo Real de Sensores | Como gestor, quiero ver en tiempo real los datos de los sensores asociados a un producto o lote, para asegurarme de que se mantenga en condiciones óptimas.     | **Escenario 1**: El usuario selecciona un producto y lote desde una lista. <br> **Escenario 2**: El sistema muestra temperatura, humedad o peso en tiempo real. <br> **Escenario 3**: Si un sensor se desconecta, se indica con una alerta visual.                                           | Alta          |
| E2 - US007 | Asignación de Sensores a Productos       | Como gestor, quiero asignar sensores a productos o ubicaciones específicas, para monitorear sus condiciones correctamente.                                      | **Escenario 1**: El usuario selecciona un sensor disponible y lo vincula a un producto. <br> **Escenario 2**: El sistema confirma la asignación y actualiza el estado del sensor. <br> **Escenario 3**: Si un sensor ya está asignado, no se puede volver a vincular hasta que sea liberado. | Alta          |
| E2 - US008 | Ver Historial de Condiciones Ambientales | Como gestor, quiero consultar el historial de temperaturas o condiciones de un producto, para asegurar la trazabilidad y verificar cumplimiento de condiciones. | **Escenario 1**: El usuario ingresa el nombre del producto o su lote. <br> **Escenario 2**: El sistema muestra un gráfico con las temperaturas registradas durante los últimos días. <br> **Escenario 3**: El sistema permite descargar el historial en formato CSV o PDF.                   | Alta          |
| E2 - US009 | Monitoreo por Ubicación                  | Como gestor, quiero visualizar los datos de sensores según la ubicación en el almacén, para facilitar la inspección física y el seguimiento.                    | **Escenario 1**: El usuario elige una zona del almacén desde un mapa o lista. <br> **Escenario 2**: Se muestran los sensores activos en esa ubicación. <br> **Escenario 3**: Si no hay sensores activos, se muestra un aviso.                                                                | Media         |
| E2 - US010 | Estado de Conectividad de Sensores       | Como propietario, quiero saber si un sensor se encuentra inactivo o desconectado, para poder enviar soporte técnico y evitar pérdidas.                          | **Escenario 1**: El sistema detecta si un sensor deja de enviar datos por cierto tiempo. <br> **Escenario 2**: Se muestra una notificación automática en la plataforma. <br> **Escenario 3**: Se envía una alerta por correo o dentro del dashboard indicando el sensor afectado.            | Alta          |

| **Epic 3: Alertas Automáticas de Condiciones Anómalas**                                                                                                                                                                                                                       |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** propietario<br>**Quiero** recibir alertas automáticas cuando las condiciones de los productos no estén dentro del rango óptimo<br>**Para** poder tomar acciones correctivas de inmediato, evitando posibles pérdidas de productos sensibles y manteniendo la calidad |

| **ID**     | **Título**                                    | **Historia de Usuario**                                                                                                                                             | **Escenarios de Prueba**                                                                                                                                                                                                                                               | **Prioridad** |
| ---------- | --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E3 - US011 | Generación de Alertas por Temperatura Anómala | Como propietario, quiero recibir alertas automáticas cuando un producto sale del rango de temperatura adecuado, para reaccionar a tiempo y evitar daños.            | **Escenario 1**: Un sensor detecta una temperatura fuera del rango. <br> **Escenario 2**: Se genera automáticamente una alerta visual en el dashboard. <br> **Escenario 3**: Se envía una notificación por correo o dentro de la plataforma.                           | Alta          |
| E3 - US012 | Configuración de Rangos Permitidos            | Como gestor, quiero poder configurar los rangos óptimos de temperatura, humedad o peso por producto, para que las alertas sean precisas según el tipo de mercancía. | **Escenario 1**: El usuario ingresa el producto y define el rango permitido. <br> **Escenario 2**: El sistema guarda la configuración y la asocia al producto. <br> **Escenario 3**: Se muestran errores si se ingresan valores inválidos.                             | Alta          |
| E3 - US013 | Notificación de Desconexión de Sensor         | Como propietario, quiero ser notificado si un sensor deja de enviar datos, para poder reemplazarlo o repararlo antes de que afecte la calidad de los productos.     | **Escenario 1**: Un sensor deja de emitir datos por más de X minutos. <br> **Escenario 2**: El sistema detecta la desconexión y genera una alerta. <br> **Escenario 3**: El propietario recibe una notificación automática con el nombre del sensor y su ubicación.    | Alta          |
| E3 - US014 | Registro de Alertas Emitidas                  | Como gestor, quiero revisar un historial de todas las alertas generadas, para llevar control de los eventos anómalos y su resolución.                               | **Escenario 1**: El usuario accede a un módulo de historial de alertas. <br> **Escenario 2**: Se muestran las alertas filtradas por fecha, producto y tipo. <br> **Escenario 3**: El usuario puede exportar el historial a PDF o Excel.                                | Media         |
| E3 - US015 | Alerta por Producto Crítico en Stock          | Como propietario, quiero recibir alertas si un producto con condiciones anómalas está en stock crítico, para priorizar su salida o reubicación.                     | **Escenario 1**: El sistema detecta un producto en condiciones anómalas y con stock bajo. <br> **Escenario 2**: Se muestra una alerta de doble prioridad en el dashboard. <br> **Escenario 3**: Se sugiere una acción recomendada, como reubicación o revisión manual. | Media         |

| **Epic 4: Visualización de Datos y Reportes**                                                                                                                                                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** gerente de almacén<br>**Quiero** acceder a reportes visuales y gráficos detallados sobre las condiciones de los productos y el rendimiento de los sensores<br>**Para** analizar la información de manera fácil y tomar decisiones informadas para mejorar la gestión del inventario |

| **ID**     | **Título**                                        | **Historia de Usuario**                                                                                                                                             | **Escenarios de Prueba**                                                                                                                                                                                                                     | **Prioridad** |
| ---------- | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E4 - US016 | Visualización de Temperaturas en Gráfica          | Como gerente de almacén, quiero visualizar las temperaturas registradas por los sensores en una gráfica por hora, para analizar tendencias y prevenir incidentes.   | **Escenario 1**: El usuario selecciona un producto o lote.<br>**Escenario 2**: El sistema muestra una gráfica de temperatura por hora.<br>**Escenario 3**: El gráfico cambia si se modifica la fecha o el sensor seleccionado.               | Alta          |
| E4 - US017 | Reporte Detallado de Sensores Activos             | Como gerente, quiero ver un reporte con todos los sensores activos, para asegurarme de que están funcionando correctamente.                                         | **Escenario 1**: El usuario accede al módulo de sensores.<br>**Escenario 2**: El sistema muestra una tabla con sensores activos, su ubicación y estado.<br>**Escenario 3**: El usuario puede filtrar por tipo de sensor o zona.              | Alta          |
| E4 - US018 | Descarga de Reportes en PDF                       | Como gerente, quiero poder descargar los reportes de condiciones ambientales y sensores en formato PDF, para compartirlos con otros equipos o para archivarlos.     | **Escenario 1**: El usuario hace clic en “Descargar Reporte”.<br>**Escenario 2**: El sistema genera el PDF con los datos visibles.<br>**Escenario 3**: El archivo se descarga correctamente con el nombre del producto, fecha y hora.        | Media         |
| E4 - US019 | Historial de Condiciones Ambientales por Producto | Como gestor, quiero consultar el historial de temperatura, humedad o peso de un producto específico, para asegurarme de que se ha mantenido en condiciones óptimas. | **Escenario 1**: El usuario busca un producto por nombre o lote.<br>**Escenario 2**: El sistema muestra un historial detallado por fecha.<br>**Escenario 3**: El usuario puede cambiar el rango de fechas o exportar los datos.              | Alta          |
| E4 - US020 | Comparación de Ventas vs Stock                     | Como propietario del negocio, quiero visualizar una tabla que compare las ventas de cada producto con su stock disponible, para identificar qué productos requieren reposición o tienen sobreinventario.        | **Escenario 1**: El sistema muestra una tabla con columnas de producto, unidades vendidas y stock actual.<br>**Escenario 2**: SSe destacan los productos con ventas altas y bajo stock (riesgo de quiebre) o ventas bajas y alto stock (riesgo de sobreinventario).<br>**Escenario 3**: El usuario puede ordenar por cualquiera de las columnas y exportar la tabla en formato Excel o PDF. | Media         |

| **Epic 5: Sistema de Recomendaciones para Optimización**                                                                                                                                                                                                                                        |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** propietario de un negocio<br>**Quiero** recibir recomendaciones basadas en datos para optimizar el uso del espacio de almacenamiento y las condiciones de mis productos<br>**Para** mejorar la eficiencia operativa y reducir los desperdicios, asegurando la calidad de los productos |

| **ID**     | **Título**                                     | **Historia de Usuario**                                                                                                                                                          | **Escenarios de Prueba**                                                                                                                                                                                                                                           | **Prioridad** |
| ---------- | ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| E5 - US021 | Recomendaciones de Mejora por Producto         | Como propietario, quiero recibir sugerencias sobre cómo mejorar el almacenamiento de un producto específico, para evitar deterioros y pérdidas.                                  | **Escenario 1**: El sistema analiza el historial ambiental del producto.<br>**Escenario 2**: Se generan recomendaciones basadas en desviaciones frecuentes.<br>**Escenario 3**: Las recomendaciones se muestran en una vista clara dentro del perfil del producto. | Alta          |
| E5 - US022 | Sugerencias para Optimización de Espacio       | Como gestor, quiero recibir sugerencias de reorganización de productos según su rotación, para aprovechar mejor el espacio disponible en el almacén.                             | **Escenario 1**: El sistema evalúa los productos de alta y baja rotación.<br>**Escenario 2**: Se proponen zonas de almacenamiento más eficientes.<br>**Escenario 3**: El usuario puede aceptar o ignorar las sugerencias.                                          | Media         |
| E5 - US023 | Alertas de Producto con Baja Rotación          | Como administrador, quiero que el sistema me notifique si un producto lleva mucho tiempo sin moverse del inventario, para tomar acciones correctivas como promociones o cambios. | **Escenario 1**: El sistema identifica productos con baja rotación.<br>**Escenario 2**: Se muestra una alerta o sugerencia para revisar su estrategia.<br>**Escenario 3**: El usuario puede acceder a un resumen del historial de ventas o movimientos.            | Alta          |
| E5 - US024 | Recomendaciones Basadas en Clima               | Como emprendedor, quiero que el sistema me indique en qué momentos del día es mejor almacenar o mover ciertos productos sensibles, según las condiciones climáticas del almacén. | **Escenario 1**: El sistema revisa datos de temperatura y humedad por hora.<br>**Escenario 2**: Se muestran intervalos óptimos sugeridos para operaciones.<br>**Escenario 3**: El usuario puede activar o desactivar esta función.                                 | Media         |
| E5 - US025 | Evaluación del Cumplimiento de Recomendaciones | Como propietario, quiero saber si las recomendaciones fueron aplicadas y su impacto, para evaluar si ayudaron a mejorar la conservación del inventario.                          | **Escenario 1**: El sistema guarda cambios realizados tras sugerencias.<br>**Escenario 2**: Se compara el estado ambiental antes y después.<br>**Escenario 3**: Se genera un pequeño resumen de impacto en la calidad del almacenamiento.                          | Media         |

| **Epic 6: Suscripción y Administración de Planes**                                                                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** usuario de la plataforma<br>**Quiero** poder gestionar mi suscripción y planes de servicio<br>**Para** seleccionar el plan que mejor se adapte a mis necesidades, asegurando acceso a las funcionalidades y sensores adecuados para mi negocio |

# Epic 6: Suscripción y Administración de Planes

| **ID**     | **Título**                           | **Historia de Usuario**                                                                                                                              | **Escenarios de Prueba**                                                                                                                                                                                                                    | **Prioridad** |
| ---------- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E6 - US026 | Selección de Plan de Suscripción     | Como usuario nuevo, quiero poder elegir un plan de suscripción al registrarme, para acceder al nivel de funcionalidades que se ajusten a mi negocio. | **Escenario 1**: Se muestra una lista de planes disponibles al registrarse.<br>**Escenario 2**: Al seleccionar un plan, se registran sus beneficios y límites.<br>**Escenario 3**: El plan queda asociado al usuario.                       | Alta          |
| E6 - US027 | Cambio de Plan en Cualquier Momento  | Como usuario registrado, quiero poder cambiar de plan cuando lo necesite, para ajustar mis necesidades según el crecimiento de mi emprendimiento.    | **Escenario 1**: El usuario accede a su perfil y selecciona cambiar de plan.<br>**Escenario 2**: El sistema valida si hay una diferencia de precio.<br>**Escenario 3**: El nuevo plan se activa y el anterior queda deshabilitado.          | Alta          |
| E6 - US028 | Visualización de Beneficios por Plan | Como usuario, quiero ver claramente qué incluye cada plan de suscripción, para elegir el que más me conviene.                                        | **Escenario 1**: Se presenta una tabla comparativa de beneficios por plan.<br>**Escenario 2**: El usuario puede filtrar por tipo de uso (emprendedor, gestor, etc.).<br>**Escenario 3**: Se resalta el plan actual del usuario.             | Media         |
| E6 - US029 | Renovación Automática del Plan       | Como usuario, quiero que mi plan se renueve automáticamente cada mes/año, para no perder acceso a la plataforma.                                     | **Escenario 1**: El sistema registra la fecha de suscripción inicial.<br>**Escenario 2**: Se ejecuta la renovación al llegar la fecha de vencimiento.<br>**Escenario 3**: Se notifica al usuario antes de la renovación.                    | Media         |
| E6 - US030 | Cancelación de la Suscripción        | Como usuario, quiero poder cancelar mi plan de suscripción cuando lo desee, para no generar más cargos si ya no necesito el servicio.                | **Escenario 1**: El usuario accede al panel de suscripción.<br>**Escenario 2**: Se muestra un mensaje de confirmación con efectos de la cancelación.<br>**Escenario 3**: El acceso se revoca después del vencimiento del periodo ya pagado. | Alta          |

| **Epic 7: Alquiler y Activación de Sensores Físicos**                                                                                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** propietario<br>**Quiero** alquilar y activar sensores físicos para monitorear las condiciones de mis productos<br>**Para** asegurar que mis productos estén siempre bajo condiciones controladas sin tener que invertir en la compra de sensores permanentemente |

| **ID**     | **Título**                                    | **Historia de Usuario**                                                                                                                                                          | **Escenarios de Prueba**                                                                                                                                                                                                                                                                                        | **Prioridad** |
| ---------- | --------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E7 - US031 | Alquiler de Sensores Físicos                  | Como propietario, quiero alquilar sensores físicos para monitorear las condiciones de mis productos, para asegurar que mis productos estén siempre bajo condiciones controladas. | **Escenario 1**: El propietario accede a una lista de sensores disponibles para alquilar.<br>**Escenario 2**: Se selecciona un sensor y se muestra el costo por periodo de alquiler.<br>**Escenario 3**: El sensor es agregado al inventario del usuario y se puede activar desde el panel.                     | Alta          |
| E7 - US032 | Activación de Sensores en Productos           | Como propietario, quiero poder activar sensores en productos específicos, para iniciar el monitoreo en tiempo real de sus condiciones.                                           | **Escenario 1**: El propietario selecciona un producto en su inventario.<br>**Escenario 2**: Se elige el sensor correspondiente.<br>**Escenario 3**: El sistema muestra que el sensor está activado y empieza a registrar datos en tiempo real.                                                                 | Alta          |
| E7 - US033 | Monitoreo del Estado de los Sensores          | Como propietario, quiero poder ver el estado de los sensores activados (en funcionamiento o inactivos), para verificar que todos están funcionando correctamente.                | **Escenario 1**: El propietario accede al panel de monitoreo de sensores.<br>**Escenario 2**: Se muestran los sensores activos e inactivos.<br>**Escenario 3**: El sistema notifica si un sensor está fuera de servicio o desactivado.                                                                          | Alta          |
| E7 - US034 | Registro de Alquiler y Activación de Sensores | Como administrador, quiero que se registre automáticamente el alquiler y activación de sensores en el sistema, para llevar un control de las operaciones realizadas.             | **Escenario 1**: El sistema registra cada alquiler de sensor con fecha y producto asignado.<br>**Escenario 2**: El alquiler y activación quedan reflejados en el historial de la cuenta del propietario.<br>**Escenario 3**: El sistema verifica que el sensor esté activado antes de completar la transacción. | Media         |
| E7 - US035 | Desactivación y Devolución de Sensores        | Como propietario, quiero poder desactivar y devolver sensores cuando ya no los necesite, para liberar espacio y evitar costos adicionales.                                       | **Escenario 1**: El propietario desactiva un sensor desde el panel de control.<br>**Escenario 2**: Se muestra un mensaje de confirmación de desactivación.<br>**Escenario 3**: El sistema actualiza el estado del sensor como "devuelto" y termina el alquiler.                                                 | Alta          |

| **Epic 8: Gestión de Usuarios y Roles**                                                                                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** administrador de la plataforma<br>**Quiero** gestionar los usuarios y asignarles roles dentro de la plataforma<br>**Para** controlar el acceso a las funcionalidades según las responsabilidades de cada miembro del equipo, garantizando la seguridad y eficiencia en la operación |

| **ID**     | **Título**                             | **Historia de Usuario**                                                                                                                                                 | **Escenarios de Prueba**                                                                                                                                                                                                                                                                 | **Prioridad** |
| ---------- | -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E8 - US036 | Creación de Usuarios                   | Como administrador, quiero crear nuevos usuarios en la plataforma, para que otros miembros del equipo puedan acceder y utilizar el sistema según sus roles y permisos.  | **Escenario 1**: El administrador accede al panel de gestión de usuarios.<br>**Escenario 2**: El administrador ingresa los datos del nuevo usuario (nombre, correo, rol).<br>**Escenario 3**: El sistema crea el nuevo usuario y muestra un mensaje de confirmación.                     | Alta          |
| E8 - US037 | Asignación de Roles a Usuarios         | Como administrador, quiero asignar roles específicos a cada usuario, para definir qué funcionalidades pueden acceder y utilizar dentro de la plataforma.                | **Escenario 1**: El administrador selecciona un usuario existente.<br>**Escenario 2**: El administrador asigna un rol (por ejemplo, gestor, propietario, administrador).<br>**Escenario 3**: El sistema guarda los cambios y muestra un mensaje de confirmación.                         | Alta          |
| E8 - US038 | Edición de Usuarios y Roles            | Como administrador, quiero poder editar los datos y roles de los usuarios existentes, para hacer ajustes según sea necesario en la asignación de permisos.              | **Escenario 1**: El administrador selecciona un usuario a editar.<br>**Escenario 2**: El administrador cambia el rol o datos del usuario.<br>**Escenario 3**: El sistema guarda y actualiza los cambios y muestra un mensaje de confirmación.                                            | Media         |
| E8 - US039 | Desactivación de Usuarios              | Como administrador, quiero desactivar usuarios que ya no necesiten acceso a la plataforma, para mantener la seguridad y controlar el acceso a la información.           | **Escenario 1**: El administrador selecciona un usuario a desactivar.<br>**Escenario 2**: El administrador confirma la desactivación del usuario.<br>**Escenario 3**: El sistema desactiva el acceso del usuario y muestra un mensaje de confirmación.                                   | Alta          |
| E8 - US040 | Visualización de Actividad de Usuarios | Como administrador, quiero ver un registro de las actividades de los usuarios, para hacer un seguimiento de sus acciones y garantizar el uso correcto de la plataforma. | **Escenario 1**: El administrador accede al historial de actividad de usuarios.<br>**Escenario 2**: Se muestran las acciones realizadas por los usuarios (inicio de sesión, cambios de datos, etc.).<br>**Escenario 3**: El sistema permite filtrar las actividades por fecha y usuario. | Media         |

## 3.3. Impact Mapping

### Propietarios:
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/requirements-specification/Images/impactPropietario.png?raw=true" style="width: 100%;"/>

### Gestores:

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/requirements-specification/Images/impactPropietario.png?raw=true" style="width: 100%;"/>

## 3.4. Product Backlog

| Orden | User Story Id | Título                                         | Descripción                                                                                                               | Story Points |
| ----- | ------------- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------ |
| 1     | E1 - US001    | Registro Manual de Producto                    | Como gestor, quiero registrar productos manualmente, para tener un control actualizado del inventario.                    | 2            |
| 2     | E1 - US002    | Importación Masiva de Productos                | Como gestor, quiero importar productos desde un archivo Excel, para ahorrar tiempo en el registro inicial del inventario. | 3            |
| 3     | E1 - US004    | Búsqueda de Productos por Nombre o Lote        | Como gestor, quiero buscar productos por nombre o lote, para ubicar rápidamente su información.                           | 1            |
| 4     | E1 - US005    | Ajuste Rápido de Stock                         | Como gestor, quiero ajustar manualmente el stock, para corregir diferencias en tiempo real.                               | 2            |
| 5     | E2 - US006    | Visualización en Tiempo Real de Sensores       | Como gestor, quiero ver en tiempo real los datos de los sensores, para asegurarme de mantener condiciones óptimas.        | 3            |
| 6     | E2 - US007    | Asignación de Sensores a Productos             | Como gestor, quiero asignar sensores a productos, para monitorear sus condiciones correctamente.                          | 3            |
| 7     | E2 - US008    | Ver Historial de Condiciones Ambientales       | Como gestor, quiero consultar el historial ambiental de un producto, para asegurar la trazabilidad.                       | 3            |
| 8     | E2 - US010    | Estado de Conectividad de Sensores             | Como propietario, quiero saber si un sensor está inactivo, para enviar soporte técnico y evitar pérdidas.                 | 2            |
| 9     | E3 - US011    | Generación de Alertas por Temperatura          | Como propietario, quiero recibir alertas automáticas por temperatura fuera del rango, para reaccionar a tiempo.           | 2            |
| 10    | E3 - US012    | Configuración de Rangos Permitidos             | Como gestor, quiero configurar los rangos óptimos, para que las alertas sean precisas.                                    | 2            |
| 11    | E3 - US013    | Notificación de Desconexión de Sensor          | Como propietario, quiero ser notificado si un sensor deja de enviar datos, para reemplazarlo o repararlo.                 | 2            |
| 12    | E4 - US016    | Visualización de Temperaturas en Gráfica       | Como gerente, quiero visualizar las temperaturas por hora, para analizar tendencias.                                      | 2            |
| 13    | E4 - US017    | Reporte Detallado de Sensores Activos          | Como gerente, quiero ver sensores activos, para asegurarme de que funcionan correctamente.                                | 2            |
| 14    | E4 - US019    | Historial Ambiental por Producto               | Como gestor, quiero consultar el historial ambiental de un producto, para verificar condiciones.                          | 2            |
| 15    | E5 - US021    | Recomendaciones de Mejora por Producto         | Como propietario, quiero recibir sugerencias de almacenamiento, para evitar deterioros.                                   | 3            |
| 16    | E5 - US023    | Alertas de Producto con Baja Rotación          | Como administrador, quiero ser notificado si un producto tiene baja rotación, para tomar acciones.                        | 2            |
| 17    | E6 - US026    | Selección de Plan de Suscripción               | Como usuario nuevo, quiero elegir un plan, para acceder a funcionalidades según mi negocio.                               | 2            |
| 18    | E6 - US027    | Cambio de Plan en Cualquier Momento            | Como usuario registrado, quiero cambiar de plan cuando lo necesite, para ajustarme a mis necesidades.                     | 2            |
| 19    | E6 - US030    | Cancelación de la Suscripción                  | Como usuario, quiero cancelar mi plan cuando lo desee, para no generar más cargos.                                        | 2            |
| 20    | E7 - US031    | Alquiler de Sensores Físicos                   | Como propietario, quiero alquilar sensores, para monitorear mis productos sin comprarlos.                                 | 3            |
| 21    | E7 - US032    | Activación de Sensores en Productos            | Como propietario, quiero activar sensores en productos específicos, para monitorearlos en tiempo real.                    | 2            |
| 22    | E8 - US036    | Creación de Usuarios                           | Como administrador, quiero crear nuevos usuarios, para que otros accedan a la plataforma.                                 | 2            |
| 23    | E8 - US037    | Asignación de Roles a Usuarios                 | Como administrador, quiero asignar roles específicos, para controlar el acceso a funcionalidades.                         | 2            |
| 24    | E1 - US003    | Escaneo de Productos para Registro Rápido      | Como gestor, quiero escanear productos, para registrarlos rápidamente en el inventario.                                   | 3            |
| 25    | E2 - US009    | Monitoreo por Ubicación                        | Como gestor, quiero ver datos de sensores por zona, para facilitar inspecciones físicas.                                  | 2            |
| 26    | E3 - US014    | Registro de Alertas Emitidas                   | Como gestor, quiero revisar un historial de alertas generadas, para llevar control de eventos.                            | 2            |
| 27    | E3 - US015    | Alerta por Producto Crítico en Stock           | Como propietario, quiero recibir alertas si un producto anómalo está en stock crítico.                                    | 2            |
| 28    | E4 - US018    | Descarga de Reportes en PDF                    | Como gerente, quiero descargar reportes en PDF, para archivarlos o compartirlos.                                          | 1            |
| 29    | E4 - US020    | Tabla Comparativa de Sensores                  | Como administrador, quiero ver una tabla que compare sensores, para detectar fallas o baja precisión.                     | 2            |
| 30    | E5 - US022    | Sugerencias para Optimización de Espacio       | Como gestor, quiero sugerencias de reorganización, para aprovechar mejor el espacio del almacén.                          | 2            |
| 31    | E5 - US024    | Recomendaciones Basadas en Clima               | Como emprendedor, quiero recomendaciones de horarios óptimos para mover productos sensibles.                              | 2            |
| 32    | E5 - US025    | Evaluación del Cumplimiento de Recomendaciones | Como propietario, quiero saber si las recomendaciones fueron aplicadas y su impacto.                                      | 2            |
| 33    | E6 - US028    | Visualización de Beneficios por Plan           | Como usuario, quiero ver qué incluye cada plan, para elegir el que más me conviene.                                       | 1            |
| 34    | E6 - US029    | Renovación Automática del Plan                 | Como usuario, quiero que mi plan se renueve automáticamente, para no perder acceso.                                       | 1            |
| 35    | E7 - US033    | Monitoreo del Estado de los Sensores           | Como propietario, quiero ver si los sensores están activos o inactivos, para verificar funcionamiento.                    | 2            |
| 36    | E7 - US034    | Registro de Alquiler y Activación de Sensores  | Como administrador, quiero registrar alquiler y activación de sensores, para tener control.                               | 2            |
| 37    | E7 - US035    | Desactivación y Devolución de Sensores         | Como propietario, quiero desactivar y devolver sensores, para evitar costos adicionales.                                  | 2            |
| 38    | E8 - US038    | Edición de Usuarios y Roles                    | Como administrador, quiero editar datos y roles de usuarios, para hacer ajustes en permisos.                              | 1            |
| 39    | E8 - US039    | Desactivación de Usuarios                      | Como administrador, quiero desactivar usuarios que no necesiten acceso, para mayor seguridad.                             | 2            |
| 40    | E8 - US040    | Visualización de Actividad de Usuarios         | Como administrador, quiero ver un historial de acciones de los usuarios, para garantizar el uso correcto.                 | 2            |

# Capítulo IV: Product Design

## 4.1. Style Guidelines

En esta sección, se presentarán de forma estructurada los estilos y herramientas que se emplearán para llevar a cabo el diseño de nuestra solución.

### 4.1.1. General Style Guidelines

**Brand Overiew**
Administrar un inventario puede convertirse en una tarea compleja para muchos emprendedores, especialmente cuando se trata de productos sensibles o de alto volumen. La falta de herramientas accesibles para monitorear el estado de los insumos y automatizar procesos genera errores, pérdidas económicas y una gran carga de trabajo. EasyStock nace como una solución pensada para optimizar la gestión de almacenes en pequeños y medianos emprendimientos. Utilizando sensores inteligentes que miden temperatura, peso y otros parámetros clave, nuestra plataforma permite monitorear inventarios en tiempo real y recibir alertas automáticas, garantizando la conservación de productos y mejorando la eficiencia operativa.
**Brand Name**
El nombre EasyStock refleja claramente nuestra propuesta de valor: facilitar (Easy) el control de inventarios o stocks (Stock). Es un nombre directo, simple y fácil de recordar, ideal para conectar con nuestro público objetivo: emprendedores que buscan soluciones accesibles y efectivas. Además, el uso del inglés le otorga un alcance global, permitiendo que la marca se adapte a futuros mercados internacionales.

A continuación, se presenta el Logo:
![Logo](Images/LogoEasyStock.png)
![Logo](Images/LogoW.png)

**Typography**

La tipografía en EasyStock ha sido cuidadosamente seleccionada para transmitir profesionalismo, simplicidad y modernidad. Utilizamos una combinación tipográfica que equilibra carácter y legibilidad: "Oswald" para los títulos, por su presencia fuerte y estructura condensada que aporta impacto visual, y entre "Arimo" y "Mulish" para los textos, debido a su claridad, suavidad y excelente rendimiento en interfaces digitales. La jerarquía tipográfica se organiza en encabezados, cuerpo de texto, botones y enlaces, asegurando una experiencia visual coherente y armoniosa.
![Typography](Images/Fonts.png)
**Colors**
La paleta de colores de EasyStock está diseñada para generar confianza, orden y eficiencia. Cada color fue seleccionado considerando su impacto emocional y su funcionalidad en la interfaz desarrollada.

- **Color Primario (#C60619):** Este rojo vibrante y profundo transmite urgencia, acción inmediata y control. Es el color principal de la marca, usado en botones clave y encabezados importantes, reforzando la necesidad de monitoreo en tiempo real y decisiones ágiles.
- **Color Secundario (#FF7C39):** Este rojo anaranjado capta rápidamente la atención y es ideal para advertencias o alertas sobre el estado de los insumos. Su intensidad visual lo hace útil en elementos que requieren respuesta inmediata.
- **Color Secundario (#FF6200):** Un naranja fuerte que aporta dinamismo y energía. Se emplea para destacar acciones secundarias, recomendaciones o procesos interactivos que guían al usuario dentro del sistema.
- **Color Secundario (#FFA360):** Este tono más claro de naranja proporciona un contraste cálido y armonioso. Se utiliza en secciones informativas o como fondo para destacar sin abrumar.
- **Color Secundario (#FFC397):** Un tono durazno claro que transmite cercanía y accesibilidad. Ideal para tarjetas informativas, ilustraciones o componentes visuales secundarios.
- **Color Secundario (#FFE1D5):** Suaviza la interfaz y permite una lectura cómoda. Funciona como fondo complementario o en áreas que necesitan un enfoque más relajado y limpio.
- **Color de Contraste (#60030C):** Este rojo oscuro profundo refuerza la identidad visual en contrastes marcados o elementos de marca como el logo. Aporta solidez y seriedad al diseño.
- **Colores de apoyo adicionales:** También se utilizan tonos como `#950015`, `#DE2E03`, `#C00000`, `#FF703A`, `#FF733F`, y `#BD2A11` en detalles específicos para enriquecer visualmente la interfaz sin perder coherencia.
- **Colores para texto y contraste:** Se emplea el **negro (#000000)** y el **blanco (#FFFFFF)** para garantizar legibilidad en títulos, párrafos, botones y fondos según el contexto. Estos colores aseguran un contraste claro y accesible en la interfaz.
  ![Paleta de Colores](Images/ColorsStyle.png)
  *Colores realizados en el figma: https://www.figma.com/design/TxnqzpKuoMpU5seAHM7C4j/EasyStock?node-id=74-247&p=f&t=je4Qxg6oNKqqpHSI-0*

**Spacing**
El spacing a considerar para mantener el contenido entendible será:

- Button padding: 8 px (vertical), 16–38 px (horizontal)
- Input fields: auto (sin altura fija), 16 px (espacio entre campos usando margin-top)
- Margin entre secciones: 60 px
- Height entre textos: 30 px en h2, 10–15 px en p

**Dimensions**
En EasyStock se optó por una comunicación clara, accesible y profesional, pero sin dejar de ser cercana. La marca busca transmitir confianza y eficiencia, usando un lenguaje directo que oriente al usuario sin resultar frío o impersonal. Queremos que nuestros clientes sientan que tienen el control de su inventario con una herramienta moderna, útil y fácil de entender, evitando tecnicismos innecesarios y manteniendo siempre un tono amable y resolutivo.

### 4.1.2. Web Style Guidelines

Se estableció una guía detallada para la presentación de los productos, la cual define los componentes que deben utilizarse en la página web. Esta guía considera la paleta de colores previamente mencionada, con el objetivo de captar la atención de los usuarios y fomentar una navegación más atractiva e intuitiva por los productos. Enlace al esquema:

![Components](Images/Components.png)
EasyStock contará con una interfaz web responsive, capaz de adaptarse sin problemas a cualquier dispositivo, desde smartphones hasta monitores de escritorio. El diseño está enfocado en ofrecer una experiencia intuitiva, clara y rápida, permitiendo a los usuarios tomar decisiones inmediatas sobre su inventario sin complicaciones.

Se ha optado por implementar el patrón Z, que guía la mirada del usuario a través de una secuencia lógica: inicio en el logo (esquina superior izquierda), navegación hacia el menú (esquina superior derecha), desplazamiento visual hacia el contenido principal (centro), y final en la información corporativa y contactos (parte inferior derecha). Esta estructura mejora la retención del contenido y asegura que los elementos más importantes estén en zonas de alto impacto visual.

Los colores y espacios están pensados para reducir la fatiga visual, mientras que las animaciones suaves y las alertas visuales permiten que el usuario reaccione rápidamente ante cualquier cambio en su inventario.
![alt text](Images/PatronZ.jpg)

## 4.2. Information Architecture

A lo largo de esta sección, se expondrán los criterios y fundamentos que respaldan la forma en que se estructura el contenido en las versiones web y móvil de EasyStock, incluyendo tanto la página principal como la aplicación. La propuesta busca garantizar una experiencia de navegación clara y sencilla, permitiendo que los usuarios localicen de manera rápida y eficiente la información y las herramientas disponibles.

### 4.2.1. Organization Systems

Para estructurar la arquitectura de la información en EasyStock, se ha implementado un sistema jerárquico tanto en la Landing Page como en la Aplicación Web. Esta estrategia permite una navegación clara e intuitiva, asegurando que los usuarios puedan acceder con facilidad a la información y funcionalidades que necesitan.

**Visual Organization**

En EasyStock se optó por una organización visual basada en la jerarquía para facilitar la lectura y comprensión del contenido. De esta manera, el usuario puede identificar de inmediato qué información tiene mayor relevancia dentro del sistema. Se asignaron distintos tamaños de texto dependiendo del peso informativo: para los títulos principales se utilizaron tamaños entre 48px y 40px, mientras que los subtítulos emplean tamaños entre 32px y 24px, y los textos secundarios como descripciones o instrucciones utilizan tamaños entre 16px y 14px. Además, se implementó una estructura secuencial especialmente en los flujos de registro de productos, actualización de stock y generación de reportes, para guiar al usuario paso a paso y evitar errores.

**Categorization Schemes**

Para la categorización, se escogieron tres esquemas:

**Alfabético**

Los productos dentro del inventario se presentan de forma alfabética en las secciones de consulta y edición, lo que permite a los encargados encontrar artículos específicos de forma rápida y eficiente, sin importar el volumen del inventario.

**Cronológico**

Los movimientos de inventario  como entradas y salidas de productos se registran y muestran de manera cronológica, lo cual facilita el seguimiento de la trazabilidad del stock. Así, los usuarios pueden verificar fácilmente qué productos han sido ingresados o retirados más recientemente.

**Audiencia**

Dado que EasyStock está pensado tanto para gerentes como para operarios de almacén, la interfaz adapta el contenido mostrado según el tipo de usuario. Por ejemplo, los gerentes acceden a reportes analíticos y gráficos de rendimiento, mientras que los operarios visualizan opciones más operativas como el escaneo de productos y el control diario del inventario. Esta separación asegura que cada grupo de usuarios reciba información relevante a sus necesidades, evitando sobrecarga de datos y mejorando la eficiencia del uso de la aplicación.

### 4.2.2. Labeling Systems

Para etiquetar visualmente los botones y funcionalidades dentro de nuestra aplicación desarrollada con Angular, optamos por una solución que permita a los usuarios identificar fácilmente la función de cada elemento. Por esta razón, seleccionamos los íconos proporcionados por PrimeNG Icons (https://primefaces.org/primeng/icons), ya que se integran de forma nativa con Angular y ofrecen un diseño intuitivo y representativo de las acciones que acompañan.

Estos íconos se incorporarán en todos los módulos de la aplicación Angular a través de los componentes de PrimeNG, asegurando una experiencia de usuario fluida, accesible y visualmente coherente. La integración se realizará directamente en las plantillas HTML utilizando las clases de íconos que proporciona PrimeNG, lo que permite una implementación rápida y estandarizada en el proyecto.

En la landing page del sistema, se utilizarán exclusivamente íconos de redes sociales como Instagram, Facebook y X (Twitter) para facilitar canales de contacto directo con los usuarios.

### Etiquetas de Encabezados (Headings)

Las etiquetas de encabezado permiten identificar claramente las secciones principales tanto en la landing page como en la aplicación:

- **Inicio / Home**: Sección principal de bienvenida con un banner central, mensajes clave y botones de acción para iniciar sesión o registrarse.
- **Características / Features**: Expone de manera clara lo que ofrece EasyStock, como control de stock, sensores integrados, alertas automáticas y reportes.
- **Beneficios / Benefits**: Destaca cómo la plataforma mejora la gestión de inventario, optimiza procesos y reduce errores.
- **Planes / Plans**: Describe las opciones de suscripción y precios disponibles, ayudando al usuario a comparar y elegir.
- **Funcionamiento / How it Works**: Explica el flujo de uso del sistema paso a paso para cada tipo de usuario.
- **Testimonios / Testimonials**: Presenta experiencias reales de usuarios que ya han implementado EasyStock.

### Etiquetas Textuales (Text Labels)

Estas etiquetas están presentes en botones, formularios y paneles para indicar acciones o funcionalidades específicas dentro de la aplicación:

- **Buscar producto / Search Product**: Permite encontrar productos por nombre, categoría o código.
- **Añadir producto / Add Product**: Opción para registrar nuevos productos en el sistema.
- **Registrar entrada / Register Entry** y **Registrar salida / Register Exit**: Acciones para actualizar el inventario en tiempo real.
- **Ajustes de stock / Stock Adjustment**: Función para corregir manualmente cantidades.
- **Reportes y estadísticas / Reports and Stats**: Acceso a datos visuales y analíticos.
- **Gestión de usuarios / User Management**: Control de accesos y permisos por roles.
- **Mi plan y facturación / My Plan and Billing**: Visualización del plan activo, historial de pagos y actualizaciones.
- **Configuración / Settings**: Preferencias del sistema, idioma, notificaciones y más.
- **Soporte / Support**: Acceso a ayuda técnica y contacto con el equipo.

### Etiquetas Icónicas (Iconic Labels)

Estas etiquetas utilizan íconos reconocibles para mejorar la experiencia del usuario a través de una navegación visual más intuitiva:

- **Icono de Lupa**: Representa la acción de buscar.
- **Icono de Caja**: Indica la sección de productos e inventario.
- **Icono de Flecha Derecha / Izquierda**: Representa las entradas y salidas de stock.
- **Icono de Alerta**: Señala alertas de stock bajo o vencimiento.
- **Icono de Engranaje**: Acceso a configuraciones generales del sistema.
- **Icono de Usuario**: Gestión de perfiles, usuarios y permisos.
- **Icono de Factura**: Información sobre suscripción y facturación.

Estas etiquetas se encuentran en la barra de navegación principal, paneles laterales, formularios y dashboards, guiando al usuario de forma eficiente y clara por toda la plataforma.

---

### 4.2.3. SEO Tags and Meta Tags

Los **SEO Tags** y **Meta Tags** son fundamentales para que la **Landing Page** y la **Aplicación Web** de **EasyStock** sean correctamente indexadas por los motores de búsqueda, mejorando su posicionamiento y accesibilidad.

**Landing Page**

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- for mobile -->
<title>EasyStock - Gestión de inventario inteligente</title>
<meta name="description" content="Optimiza el control de tus productos con EasyStock, la solución inteligente para la gestión de inventario de tu negocio.">
<meta name="keywords" content="gestión de inventario, control de stock, sistema de inventario, administración de productos, EasyStock">
<meta name="author" content="Rurasqay">

```

**Aplicaiones Web**

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<title>EasyStock - Plataforma de control de inventario</title>
<meta name="description" content="Registra productos, gestiona movimientos, revisa reportes y mantén tu inventario actualizado con EasyStock. La solución para PYMES.">
<meta name="keywords" content="gestión de stock, inventario en tiempo real, control de productos, reportes de inventario, EasyStock">
<meta name="author" content="Rurasqay">

```

**Explicación**

``<meta charset="UTF-8">``: Define la codificación de caracteres utilizada, permitiendo el uso correcto de acentos, símbolos y caracteres especiales.

``<meta name="viewport" content="width=device-width, initial-scale=1.0">``: Hace que el diseño de la página sea responsive, adaptándose a diferentes tamaños de pantalla y dispositivos móviles.

``<title>``: Es el título que aparece en la pestaña del navegador y es uno de los elementos más relevantes para el SEO.

``<meta name="description" content="...">``: Proporciona una descripción corta y clara de la página que aparecerá en los resultados de búsqueda, atrayendo a los usuarios a hacer clic.

``<meta name="keywords" content="...">``: Incluye palabras claves relevantes para que los motores de búsqueda relacionen mejor el contenido de EasyStock con las búsquedas de los usuarios.

``<meta name="author" content="...">``: Identifica al equipo responsable del desarrollo de la aplicación y la página web.

### 4.2.4. Searching Systems

Los sistemas de búsqueda en **EasyStock** están diseñados para facilitar al usuario el acceso inmediato a la información que necesita, sin generar confusión o pérdida de tiempo. Estos métodos permiten filtrar, localizar y consultar datos de forma eficiente, incluso dentro de un inventario complejo o distribuido en múltiples ubicaciones.

#### Búsqueda por caracteres

La barra de búsqueda principal permite al usuario localizar productos, categorías o proveedores ingresando palabras clave como:

- Nombre del producto
- Código de identificación
- Marca o referencia

A medida que el usuario escribe, se mostrarán **sugerencias automáticas** con coincidencias relevantes para acelerar el proceso.

#### Búsqueda por ubicación

En contextos con múltiples almacenes, los usuarios podrán utilizar **filtros de ubicación** para visualizar únicamente los elementos almacenados en una sede específica. Esta opción es ideal para empresas con sedes descentralizadas o franquicias.

#### Búsqueda por mapa

Para una experiencia aún más visual e intuitiva, **EasyStock** integra una vista tipo mapa que permite seleccionar almacenes desde un panel geolocalizado. Al hacer clic en uno, se mostrará un resumen de su inventario y movimientos asociados.

#### Filtros avanzados

Una vez realizada la búsqueda, los resultados pueden refinarse usando filtros como:

- Fecha de ingreso
- Cantidad en stock
- Categoría del producto
- Proveedor
- Estado del stock (por ejemplo: bajo, crítico, normal)

Esto garantiza que incluso en grandes volúmenes de datos, el usuario siempre podrá encontrar con precisión lo que busca.

#### Asociación semántica en etiquetas

Para reforzar la comprensión del sistema, las etiquetas utilizadas en botones y menús (como "Contacto", "Agregar producto", "Ver historial") están diseñadas para ser **intuitivas y semánticamente claras**. Esto ayuda a los usuarios a relacionar rápidamente el contenido con su funcionalidad, evitando sobrecargar las interfaces con textos extensos.

### 4.2.5. Navigation Systems

El sistema de navegación de **EasyStock** ha sido cuidadosamente diseñado para guiar a los usuarios a través de la **Landing Page** y la **Aplicación Web** de forma intuitiva, clara y eficiente. El objetivo es permitir que tanto propietarios como gestores de inventario cumplan sus metas dentro de la plataforma sin fricciones, logrando una experiencia satisfactoria desde el primer uso.

### Estructura de navegación

La aplicación cuenta con una navegación jerárquica basada en un menú principal y accesos directos que permiten al usuario:

- **Iniciar sesión o registrarse** desde la landing page.
- Acceder al **Dashboard**, con una vista general del inventario.
- Navegar a secciones clave como:
  - **Productos**
  - **Movimientos**
  - **Alertas**
  - **Sensores**
  - **Configuración**
  - **Soporte**

Además, cada sección incluye botones visibles y accesos rápidos para realizar acciones como:

- Añadir nuevos productos
- Ajustar cantidades de stock
- Registrar entradas o salidas de mercancía

### Navegación especializada para propietarios

Los usuarios con rol de propietario pueden acceder a módulos adicionales como:

- **Reportes y estadísticas** con visualizaciones gráficas del rendimiento del inventario
- **Gestión de ventas** para analizar la relación entre inventario y actividad comercial
- **Gestión de usuarios** para administrar accesos y roles
- **Mi plan y facturación** para controlar su suscripción

### Adaptabilidad y experiencia móvil

Todo el sistema de navegación ha sido desarrollado con un enfoque **responsive**, permitiendo que la experiencia sea coherente en **computadoras, tablets y móviles**. Los elementos visuales como **colores**, **íconos intuitivos** y **etiquetas claras** refuerzan la orientación dentro de la aplicación incluso para usuarios sin experiencia previa en software de gestión.

## 4.3. Landing Page UI Design

Presentamos los resultados del diseño de la Aplicación Web en Figma.

### 4.3.1. Landing Page Wireframe

En esta sección se mostrarán los wireframes de la landing page, los cuales son representaciones de baja fidelidad que permiten visualizar la estructura y distribución de los elementos en la página. Estos esquemas no contemplan aún el uso de colores ni imágenes, ya que su propósito es definir la organización básica del contenido.
Link: https://www.figma.com/design/TxnqzpKuoMpU5seAHM7C4j/EasyStock?node-id=0-1&t=VS8JJf7IDHNU1S4k-1
Para Desktop Browser:
![DeskopBrowser](Images/LandingW.jpg)
Para Mobile Browser:
![MobileBrowser](Images/EasyStock_page-0069.jpg)

### 4.3.2. Landing Page Mock-up

En esta sección se mostrarán los Mock-ups de la landing page, los cuales son representaciones de alta  fidelidad que permiten visualizar la estructura y distribución de los elementos en la página. Estos esquemas no contemplan aún el uso de colores ni imágenes, ya que su propósito es definir la organización básica del contenido.
Link: https://www.figma.com/design/TxnqzpKuoMpU5seAHM7C4j/EasyStock?node-id=0-1&t=VS8JJf7IDHNU1S4k-1
Para Desktop Browser:
![DeskopBrowser](Images/LandingM.jpg)
Para Mobile Browser:
![MobileBrowser](Images/Mobile.png)

## 4.4. Web Applications UX/UI Design

En esta sección se describe el proceso de diseño de la aplicación web, abarcando desde la elaboración de los wireframes hasta la creación de los mock-ups. Durante este desarrollo se consideraron las guías de estilo y los principios de arquitectura de la información previamente definidos, con el objetivo de asegurar una coherencia visual adecuada con la landing page del proyecto.

### 4.4.1. Web Applications Wireframes

Iniciar Sesión / Registro
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0070.jpg)
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0077.jpg)
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0088.jpg)
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0071.jpg)
Gestión de Membresías
![GestionMembresia](Images/EasyStock/EasyStock_page-0130.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0131.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0094.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0079.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0085.jpg)
Determinar el tipo de usuario
![TipoUsuario](Images/EasyStock/EasyStock_page-0083.jpg)
![TipoUsuario](Images/EasyStock/EasyStock_page-0095.jpg)
![TipoUsuario](Images/EasyStock/EasyStock_page-0110.jpg)
Ingreso de Información para el Tipo de Usuario
![Informacion Usuario](Images/EasyStock/AddUsersW.png)
Grupo de Usuarios:
![Informacion Usuario](Images/EasyStock/EasyStock_page-0101.jpg)
`<img src="Images/EasyStock/EasyStock_page-0101.jpg" alt="Informacion" width="200"/>`
Detalles de cada producto para los encargados de stock
`<img src="Images/EasyStock/EasyStock_page-0096.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/EasyStock_page-0091.jpg" alt="Informacion" width="200"/>``<img src="Images/EasyStock/EasyStock_page-0098.jpg" alt="Informacion" width="200"/>`

Registrar una entrada o salida de inventario y añadir notas
`<img src="Images/EasyStock/EasyStock_page-0092.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/Captura de pantalla 2025-04-20 103856.png" alt="Informacion" width="200"/>``<img src="Images/EasyStock/Captura de pantalla 2025-04-20 103918.png" alt="Informacion" width="200"/>`

Pantalla de historial de movimientos por grupo o área
`<img src="Images/EasyStock/EasyStock_page-0099.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/Captura de pantalla 2025-04-20 103946.png" alt="Informacion" width="200"/>``<img src="Images/EasyStock/EASY2.png" alt="Informacion" width="200"/>`

Pantalla de alertas activas de los sensores
`<img src="Images/EasyStock/EasyStock_page-0100.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/EasyStock_page-0104.jpg" alt="Informacion" width="200"/>``<img src="Images/EasyStock/EasyStock_page-0105.jpg" alt="Informacion" width="200"/>`

### 4.4.2. Web Applications Wireflow Diagrams

User Goal: El usuario desea registrarse en la plataforma para empezar a gestionar su inventario.
![WireflowDiagrams](Images/WireFlows%20(7).png)
![WireflowDiagrams](Images/WireFlows%20(6).png)

User Goal: El usuario necesita acceder a su cuenta en EasyStock.
![WireflowDiagrams](Images/WireFlows%20(5).png)
User Goal: El usuario ha olvidado su contraseña y desea restablecerla.
![WireflowDiagrams](Images/WireFlows%20(2).png)
User Goal: El usuario desea añadir un nuevo producto a su inventario.
![WireflowDiagrams](Images/WireFlows%20(4).png)
User Goal: El usuario desea ver el historial de entradas y salidas de un producto específico.

![WireflowDiagrams](Images/WireFlows%20(1).png)
User Goal: El usuario desea añadir un nuevo sensor a productos y desea ver el historial de datos ambientales
![WireflowDiagrams](Images/WireFlows%20(3).png)

### 4.4.3. Web Applications Mock-ups

En esta parte se mostrarán los wireframes de la aplicación web, los cuales representan esquemas de baja fidelidad que funcionan como un plano inicial. Su propósito es definir la estructura general de la interfaz antes de avanzar hacia la aplicación de guías de estilo e incorporación de elementos visuales.

Iniciar Sesión / Registro
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0026.jpg)
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0029.jpg)
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0057.jpg)
![IniciarSesionRegistro](Images/EasyStock/EasyStock_page-0027.jpg)
Gestión de Membresías
![GestionMembresia](Images/EasyStock/EasyStock_page-0060.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0061.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0064.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0044.jpg)
![GestionMembresia](Images/EasyStock/EasyStock_page-0030.jpg)
Determinar el tipo de usuario
![TipoUsuario](Images/EasyStock/EasyStock_page-0042.jpg)
![TipoUsuario](Images/EasyStock/EasyStock_page-0010.jpg)
![TipoUsuario](Images/EasyStock/EasyStock_page-0031.jpg)
Ingreso de Información para el Tipo de Usuario
![Informacion Usuario](Images/EasyStock/AddUsers.png)
Grupo de Usuarios:
![Informacion Usuario](Images/EasyStock/EasyStock_page-0016.jpg)
`<img src="Images/EasyStock/EasyStock_page-0016.jpg" alt="Informacion" width="200"/>`
Detalles de cada producto para los encargados de stock
`<img src="Images/EasyStock/EasyStock_page-0011.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/EasyStock_page-0008.jpg" alt="Informacion" width="200"/>``<img src="Images/EasyStock/EasyStock_page-0013.jpg" alt="Informacion" width="200"/>`

Registrar una entrada o salida de inventario y añadir notas
`<img src="Images/EasyStock/EasyStock_page-0009.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/Captura de pantalla 2025-04-20 103806.png" alt="Informacion" width="200"/>``<img src="Images/EasyStock/Captura de pantalla 2025-04-20 103817.png" alt="Informacion" width="200"/>`

Pantalla de historial de movimientos por grupo o área
`<img src="Images/EasyStock/EasyStock_page-0014.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/Captura de pantalla 2025-04-20 103828.png" alt="Informacion" width="200"/>``<img src="Images/EasyStock/EASY.png" alt="Informacion" width="200"/>`

Pantalla de alertas activas de los sensores
`<img src="Images/EasyStock/EasyStock_page-0036.jpg" alt="Informacion" width="200"/><img src="Images/EasyStock/EasyStock_page-0019.jpg" alt="Informacion" width="200"/>``<img src="Images/EasyStock/EasyStock_page-0020.jpg" alt="Informacion" width="200"/>`

### 4.4.4. Web Applications User Flow Diagrams

User Goal: El usuario desea registrarse en la plataforma para empezar a gestionar su inventario.
![FlowDiagramas](Images/UserFlow%20(7).png)
![FlowDiagramas](Images/UserFlow%20(6).png)

User Goal: El usuario necesita acceder a su cuenta en EasyStock.
![FlowDiagramas](Images/UserFlow%20(5).png)
User Goal: El usuario ha olvidado su contraseña y desea restablecerla.
![FlowDiagramas](Images/UserFlow%20(3).png)
User Goal: El usuario desea añadir un nuevo producto a su inventario.
![FlowDiagramas](Images/UserFlow%20(4).png)
User Goal: El usuario desea ver el historial de entradas y salidas de un producto específico.

![FlowDiagramas](Images/UserFlow%20(2).png)
User Goal: El usuario desea añadir un nuevo sensor a productos y desea ver el historial de datos ambientales
![FlowDiagramas](Images/UserFlow%20(1).png)

## 4.5. Web Applications Prototyping

En esta sección se presentará el prototipo interactivo de nuestra aplicación web, el cual servirá para ilustrar su funcionamiento previsto. Esto nos permitirá contar con una referencia visual y funcional de lo que aspiramos a desarrollar, brindando una idea concreta del comportamiento que tendrá la aplicación en su versión final.

Enlace al video del prototipo: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EaBBRoukLtxFnUDCHRyeV7UBEX5jB5Lu4pN8vgtUFk_RAg?e=Mitknb&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Software Architecture Context Diagram

## Context Diagram

<img src='./Images/context.png'/>

### 4.6.2. Software Architecture Container Diagrams

## Container Diagram

<img src='./Images/container.png' />

### 4.6.3. Software Architecture Components Diagrams

## Components Diagram

<img src='./Images/component.png' />

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

<img src='./Images/classDiagram.jpg'/>

### 4.7.2. Class Dictionary

| Clase                           | Posible Función                                                                                                                                                 |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Usuario**               | Representa a los usuarios del sistema, almacenando su información personal y permitiendo la gestión de sus suscripciones.                                      |
| **Suscripcion**           | Define la suscripción de un usuario a un plan, incluyendo detalles como la fecha de inicio, fin y estado.                                                       |
| **PlanSuscripcion**       | Describe los diferentes planes de suscripción disponibles, con información sobre su nombre, precio, duración y características.                              |
| **Emprendimiento**        | Representa las unidades de negocio o emprendimientos dentro del sistema, con información sobre su nombre, sector y ubicación.                                  |
| **Almacen**               | Define los almacenes donde se gestionan los insumos, incluyendo su nombre, ubicación y capacidad.                                                               |
| **Insumo**                | Representa los diferentes tipos de insumos o materiales utilizados, con detalles como su nombre, descripción, unidad de medida, precio y fecha de vencimiento.  |
| **Alerta**                | Almacena información sobre las alertas generadas por el sistema, posiblemente relacionadas con niveles bajos de stock o condiciones ambientales fuera de rango. |
| **AsigcionSensor**        | Representa los sensores, registrando su ID, almacén asociado, fecha de asignacion                                                                               |
| **CondicionesIdealess**   | Registra las condiciones ambientales medidas, como temperatura y humedad, posiblemente asociadas a un almacén.                                                  |
| **Sensor**                | Representa un sensor genérico, con atributos como su ID, tipo, estado y ubicación.                                                                             |
| **LecturaSensor**         | Almacena las lecturas o mediciones realizadas por los sensores, incluyendo el valor leído, la fecha y hora de la lectura y el sensor al que pertenece.          |
| **HistorialOptimizacion** | Almacena las lecturas o mediciones realizadas por los sensores, incluyendo el valor leído, la fecha y hora de la lectura y el sensor al que pertenece.          |
| **TipoInsumo**            | Define los diferentes tipos de insumos que se manejan en el sistema, con un ID y un nombre descriptivo.                                                          |

## 4.8. Database Design

### 4.8.1. Database Diagram

## Database diagram:

<img src='./Images/diagram.jpg'/>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

#### En esta parte se mencionaran los productos de software usados para el desarrollo del proyecto.

### Product UX/UI Desing

1. UXPresia: Se utilizó esta herramienta para la elaboración de User Personas, Empathy Maps, Journey Maps e Impact Maps
2. Figma: Usamos esta herramienta para la creación de los wireframes, mock-ups y prototipos de aplicaciones móviles y de escritorio.
3. Miro: Usamos esta herramienta para la elaboración del AS-IS y TO-BE Scenario Maps

### Software Development

4. Viusal Stuido Code: Esta herramienta fue usada para la elaboración de la landing page y las aplicaciones web.
5. Github: Usamos la herramienta para poder trbajar aplicando GitFlow para desarrolar el proyecto de una manera organizada.

### Project Management and Collaboration

6. WhatsApp: Este aplicativo fue vital para la comunicación rápida con el equipo.

### Software Documentation

7. Vertabelo: Esta herramienta se usó para hacer bases de datos de manera de rápida.
8. StarUML: Esta herrmiendo fue usada para poder realizar el Diagrama de clases

### 5.1.2. Source Code Management

Para llevar un seguimiento ordenado de las diversas modificaciones del proyecto, se implementó una organización en GitHub. Esto simplificó el control de las diferentes versiones del código y permitió una colaboración más fluida entre los colaboradores.

- [Organización en GitHub](https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay)
- [Landing Page Repository](https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-landing-page)
- [Report Repository](https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report)

## Flujo de trabajo con GitFlow

Para mejorar la organización del código y facilitar el control de versiones, se implementó la estrategia **GitFlow**. Este modelo divide el desarrollo en distintas ramas con funciones específicas, asegurando una integración ordenada y controlada.

### Ramas principales

- **main**: Esta rama contiene las versiones finales del software, listas para ser desplegadas en producción.
- **develop**: Sirve como entorno de integración. Aquí se agrupan y prueban todas las nuevas funcionalidades antes de pasarlas a producción. Cuando una funcionalidad está lista y validada, se fusiona en esta rama.

### Ramas auxiliares

- **feature**: Se utilizan para el desarrollo de nuevas funcionalidades o mejoras. Estas ramas se crean a partir de `develop` y, al finalizar el trabajo, se integran nuevamente a ella.
  Esta separación ayuda a mantener la estabilidad del entorno principal de desarrollo y facilita la revisión del código.

### Convención de commits

Para mantener claridad y coherencia en el historial de cambios, se adopta una convención estándar para los mensajes de commit, especificando el **tipo** de cambio introducido.

#### type: Describe la naturaleza del cambio realizado en el código.

Los tipos más utilizados son:

- **fix**: Corrección de errores.Se utiliza cuando se soluciona un bug o comportamiento no deseado en el sistema.
- **chore**: Tareas de mantenimiento o configuraciones que no afectan directamente el código de producción.Incluye cambios como configuración de linters, ajustes de dependencias o scripts auxiliares.
- **feat**: Implementación de una nueva funcionalidad o característica.Se utiliza para añadir capacidades nuevas al sistema.
- **docs**: Cambios relacionados exclusivamente con la documentación.
  Incluye actualizaciones en archivos README, comentarios o guías del proyecto.

### 5.1.3. Source Code Style Guide & Conventions

#### Diseño y Construcción de la Landing Page

Durante el desarrollo de la landing page, empleamos tecnologías como HTML, CSS y JavaScript, guiándonos por los principios establecidos en las guías de estilo de Google para mantener un código limpio, organizado y conforme a los estándares web modernos.

### HTML y CSS

Nos basamos en los lineamientos descritos en el archivo `styles.txt`, que recoge buenas prácticas orientadas a mejorar la calidad del código CSS. Algunas de las directrices que seguimos fueron:

- **Declaración del tipo de documento**: Indicamos el tipo de documento al inicio (`<!DOCTYPE html>`) para asegurar una interpretación adecuada en todos los navegadores.
- **Uso de minúsculas en las etiquetas HTML**: Usamos etiquetas HTML en minúscula como `<section>`, `<nav>` o `<footer>`, garantizando una escritura coherente y ordenada.
- **Atributos entre comillas**: Colocamos entre comillas los valores de todos los atributos HTML, por ejemplo: `<div class="contenedor">`, lo que previene errores de análisis del código.
- **Atributos esenciales en las imágenes**: Añadimos atributos como `alt`, `width` y `height` en las imágenes, favoreciendo la accesibilidad y la eficiencia en la carga del sitio.
- **Reglas CSS bien estructuradas**: Escribimos reglas CSS bien comentadas y estructuradas, agrupando estilos relacionados para mejorar la comprensión del archivo.
- **Orden lógico de propiedades CSS**: Ordenamos las propiedades CSS de forma lógica (por ejemplo: primero propiedades de caja como `display`, `margin`, luego `color`, `font`, etc.), según lo sugerido en `css.txt`.
- **Uso de nombres descriptivos en selectores**: Usamos selectores con nombres claros en formato kebab-case (`.btn-secundario`, `.contenedor-principal`) para facilitar su identificación.
- **Metaetiquetas en el `<head>`**: Incorporamos etiquetas `<meta>` dentro del `<head>` del documento para configurar correctamente la codificación, el diseño en móviles y otros parámetros relevantes.

#### JavaScript

En cuanto al uso de JavaScript, aplicamos las recomendaciones de la guía de estilo de Google, lo que nos ayudó a mantener un código legible y robusto. Las prácticas más relevantes incluyeron:

- **Uso de `let` y `const`**: Se usa `let` para declarar la variable `currentLang`, ya que su valor puede cambiar. Esto mejora la previsibilidad del código. Si fuera una constante, se usaría `const`.
- **Formato `camelCase`**: Los nombres de las funciones y variables siguen el estilo `camelCase` (como `switchLanguage` y `currentLang`), lo que mejora la claridad y la consistencia del código.
- **Uso de comillas simples**: Todas las cadenas de texto están delimitadas por comillas simples, en línea con las recomendaciones de estilo.
- **Punto y coma al final de las sentencias**: Cada declaración termina con un punto y coma, lo que ayuda a evitar errores de ejecución en JavaScript.
- **Funciones pequeñas y reutilizables**: La función `switchLanguage` es pequeña y clara, lo que facilita su mantenimiento y reutilización.

### 5.1.4. Software Deployment Configuration

En esta sección se describe cómo llevamos a cabo el despliegue de nuestra landing page utilizando el servicio automatizado de GitHub Pages. A continuación, se presentan los pasos necesarios para completar este proceso.

- Es fundamental contar con un repositorio que contenga la landing page que se desea publicar.
  ![Report Repository](Images/P2.png)
- Ingresamos al repositorio y agregamos los archivos HTML, CSS y JavaScript correspondientes según sea necesario.
  ![Report Repository](Images/P3.png)
- Es necesario acceder a la sección de configuración dentro del repositorio.
  ![Report Repository](Images/P4.png)
- En la configuración, debemos ubicar y seleccionar la sección correspondiente a GitHub Pages.
  ![Report Repository](Images/P6.png)
- Una vez dentro de la sección de GitHub Pages, seleccionamos la rama del repositorio que queremos desplegar y hacemos clic en el botón de "guardar" para iniciar el proceso de despliegue.
  ![Report Repository](Images/P5.png)
- Cuando el proceso de compilación haya finalizado, se generará un enlace que nos permitirá acceder y visualizar nuestra landing page ya desplegada.
  ![Report Repository](Images/P7.png)

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

En la próxima sección, se presentará el sprint #1 con la primera versión del trabajo para la entrega del proyecto, donde se mostrará la organización, distribución y resultados del landing page.

| Sprint #                                                                       | Date                         | Time                | Location               | Prepared By                      | Attendees                                                                                                                                                    |
| :----------------------------------------------------------------------------- | :--------------------------- | :------------------ | :--------------------- | :------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                                                                              | 10/04/2025                   | 7:00 pm             | Reunión mediante Meet | Alvarado De La Cruz, Juan Carlos | `<p>`Barrientos Quispe, Marcelo . `</p><p>`Rioja Nuñez, Franco Diego.`</p><p>`Nakasone Gomes, Marco.`</p><p>`Rivera Ticllacuri, Omar Harold`</p>` |
| Sprint 1 Goal                                                                  | Sprint 1 Velocity            | Sum of Story Points |                        |                                  |                                                                                                                                                              |
| Elaborar y diseñar el landing page informativa para la aplicación EasyStock. | `<p>`18`</p><p>``</p>` | 18                  |                        |                                  |                                                                                                                                                              |

#### 5.2.1.2. Aspect Leaders and Collaborators

En el desarrollo del landing page y el reporte de KeepItFresh, se han identificado líderes responsables y colaboradores clave para cada aspecto funcional y técnico del proyecto. Esta distribución asegura una ejecución eficiente, promoviendo la especialización, la colaboración entre áreas y una comunicación fluida entre todos los miembros del equipo.

#### 5.2.1.3. Sprint Backlog 1

En el primer sprint, el equipo se enfocó en crear una landing page atractiva y funcional, organizando y asignando tareas mediante el cuadro de Sprint según las habilidades de cada miembro.

| Sprint #   |                             | Sprint 1         |                                         |                                                                          |                     |                                |                                           |
| :--------- | :-------------------------- | :--------------- | :-------------------------------------- | :----------------------------------------------------------------------- | :------------------ | :----------------------------- | :---------------------------------------- |
| User Story |                             | Work Item / Task |                                         |                                                                          |                     |                                |                                           |
| Id         | Title                       | Id               | Title                                   | Descripción                                                             | Estimación (Hours) | Assigned to                    | Status (In -process / To - review / Done) |
| US01       | Descripción de la web      | UT01             | Acerca de la web                        | Descripción de lo que trata nuestra pagina web.                         | 4                   | Barrientos Quispe, Marcelo     | Done                                      |
| US02       | Accesibilidad del contenido | UT02             | Disponibilidad accesible del contenido. | Que la página muestre el contenido correctamente (imágenes y enlaces). | 8                   | Rioja Nuñez, Franco           | Done                                      |
| US02       | Accesibilidad del contenido | UT03             | Diseño responsive de la página        | Que la página se visualice correctamente en cualquier dispositivo.      | 6                   | Rivera Ticllacuri, Omar Harold | Done                                      |

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

`<img src="./Images/service for sprints, este era.png"/>`

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Utilizando la funcionalidad de GitHub Pages, llevamos a cabo el proceso de despliegue del sitio web correspondiente a este Sprint. Para ello, accedimos a la configuración del repositorio y completamos los campos requeridos por la plataforma.

`<img src="./Images/despliegue 1.png">`

## Pagina Desplegada

`<img src="./Images/despliegue 2.png">`

link de la pagina: https://upc-pre-202501-1asi0729-4350-rurasqay.github.io/UPC-PRE-202501-1ASI0729-4350-Rurasqay-landing-page/

#### 5.2.1.8. Team Collaboration Insights during Sprint

`<img src="./Images/service for sprints.png">`

<img src="./Images/insight.png"/>

# Conclusiones

**Avance inicial significativo**

- La finalización de la landing page representa un primer hito alcanzado dentro del proyecto EasyStock. Este entregable permite comunicar de manera clara el objetivo de la plataforma y su propuesta de valor hacia los usuarios objetivo.

**Validación temprana de la propuesta**

- La publicación de la landing page ofrece una primera oportunidad para recolectar feedback externo, identificar el nivel de interés del público y ajustar el enfoque del producto si fuese necesario.

**Alineación del equipo con los objetivos del proyecto**

- Este primer sprint ha permitido que todos los miembros del equipo se alineen en torno a los objetivos del proyecto, comprendiendo de forma integral las necesidades de los usuarios y la funcionalidad mínima esperada.

**Identificación de mejoras en comunicación visual**

- Durante el desarrollo de la landing page se identificaron aspectos clave relacionados con la experiencia de usuario (UX) y el diseño visual que deberán ser refinados en próximos sprints para mejorar la efectividad del mensaje.

**Preparación para etapas siguientes del desarrollo**

- Este primer avance sienta las bases para el desarrollo de funcionalidades más complejas en los próximos sprints. Asimismo, permite proyectar futuras acciones como validaciones con usuarios reales, integración de formularios y generación de métricas.

## Video About-the-Team

## Bibliografía

## Anexos

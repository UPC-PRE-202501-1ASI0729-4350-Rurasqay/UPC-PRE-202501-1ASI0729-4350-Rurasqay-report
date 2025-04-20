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

| Member                           | Code       |
| -------------------------------- | ---------- |
| Alvarado De La Cruz, Juan Carlos | u202216150 |
| Barrientos Quispe, Marcelo       | u20221e646 |
| Rioja Nuñez, Franco Diego        | u202221597 |
| Nakasone Gomes, Marco Antonio    | u202210790 |
| Rivera Ticllacuri, Omar Harold   | u202214214 |

<br> ABRIL 2025

</center>

<center>

# Registro de Versiones del Informe

| Version | Fecha      | Autor   | Descripción de Modificación |
| ------- | ---------- | ------- | --------------------------- |
| 0.0     | 02/04/2025 | Grupo 3 | Creación del documento      |
|         | 04/04/2025 |         |                             |
|         | 04/04/2025 |         |                             |

</center>

# Project Report Collaboration Insights

Analiza cómo la colaboración y la gestión de tareas influyeron en los resultados del proyecto, destacando fortalezas y áreas de mejora para optimizar futuras estrategias.

Reporte:  
Organización:  
Landing Page:

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

**Student Outcome**

**ABET - EAC - Student Outcome 3:** Capacidad de comunicarse efectivamente con un rango de audiencias.

| Criterio Especifico                                                    | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                             | Conclusiones |
| ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| Comunica oralmente con efectividad a diferentes rangos de audiencia.   | <br> **Marco Nakasone:** <br> **TB1:** <br> Durante la primera entrega me encargue de hacer una parte del capítulo 3, agregando las epics, las user stories, los impact mapping y el product backlog, pude obtener más conocimiento de como se puede hacer bien un impact mapping, y a la vez como poder integrar las historias de usuario en un proyecto. <br> |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | <br> **Marco Nakasone:** <br> **TB1:** <br> Durante la primera entrega pude crear las historias de usuario, basandome en entrevistas e informacion recopilada con respecto a nuestro proyecto, aquí pude aprender mejor sobre lo que necesitan nuestros usuarios objetivos.                                                                                     |

# Capítulo I: Introduccion

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**_Mision:_**

**_Visión:_**

### 1.1.2. Perfiles de integrantes del equipo

|     | Apellido y Nombre | Carrera                | Acerca de     | Habilidades   |
| --- | ----------------- | ---------------------- | ------------- | ------------- |
|     |                   | Ingeniería de Software | Escribir aqui | Escribir aqui |
|     |                   | Ingeniería de Software | Escribir aqui | Escribir aqui |
|     |                   | Ingeniería de Software | Escribir aqui | Escribir aqui |
|     |                   | Ingeniería de Software | Escribir aqui | Escribir aqui |
|     |                   | Ingeniería de Software | Escribir aqui | Escribir aqui |

## 1.2. Solution Profile

Product Name:

### 1.2.1. Antecedentes y problemática

**Antecedentes:**

**Problematicas:**

**What**

- **Why: ¿Por qué es importante que se gestione el inventario en los restaurantes?**

  **Who: ¿Quienes se ven afectados?**

- **When: ¿Cuándo sucede la problemática?**

- **Where: ¿Dondé implementaríamos nuestra solución?**

- **How: ¿Cómo ayudará nuestra solución?**

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

| **Epic 1: Gestión de Inventario**                                                                                                                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cómo** emprendedor<br>**Quiero** gestionar y registrar mi inventario de productos de manera eficiente<br>**Para** tener un control preciso del stock disponible, evitar desabastecimientos y facilitar la toma de decisiones operativas |

| **ID**     | **Título**                                | **Historia de Usuario**                                                                                                            | **Escenarios de Prueba**                                                                                                                                                                                                                                                          | **Prioridad** |
| ---------- | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| E1 - US001 | Registro Manual de Producto               | Como gestor, quiero registrar productos manualmente, para tener un control actualizado del inventario.                             | **Escenario 1**: El usuario llena un formulario con nombre, cantidad y categoría del producto. <br> **Escenario 2**: El sistema valida que todos los campos estén completos antes de registrar. <br> **Escenario 3**: Si hay un error (e.g., campo vacío), se muestra un mensaje. | Alta          |
| E1 - US002 | Importación Masiva de Productos           | Como gestor, quiero importar productos desde un archivo Excel, para ahorrar tiempo en el registro inicial del inventario.          | **Escenario 1**: El usuario sube un archivo Excel con productos. <br> **Escenario 2**: El sistema verifica el formato y procesa los datos. <br> **Escenario 3**: Si el archivo tiene errores, se notifican los errores específicos.                                               | Alta          |
| E1 - US003 | Escaneo de Productos para Registro Rápido | Como gestor, quiero escanear productos para registrarlos rápidamente en el inventario, para mejorar la eficiencia.                 | **Escenario 1**: El sistema detecta un código QR o código de barras válido. <br> **Escenario 2**: El sistema muestra los datos precargados del producto. <br> **Escenario 3**: Si no se reconoce el código, se muestra un mensaje de error.                                       | Media         |
| E1 - US004 | Búsqueda de Productos por Nombre o Lote   | Como gestor, quiero buscar productos por nombre o lote, para ubicar rápidamente su información en el sistema.                      | **Escenario 1**: El usuario escribe parte del nombre o código. <br> **Escenario 2**: El sistema sugiere coincidencias. <br> **Escenario 3**: Si no hay resultados, se notifica al usuario.                                                                                        | Alta          |
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
| E4 - US020 | Tabla Comparativa de Sensores                     | Como administrador, quiero ver una tabla que compare el rendimiento de todos los sensores por tipo, para detectar posibles fallas o sensores menos precisos.        | **Escenario 1**: El sistema agrupa sensores por tipo (temperatura, humedad, peso).<br>**Escenario 2**: Se muestran métricas de precisión, errores y frecuencia de reporte.<br>**Escenario 3**: El usuario puede ordenar o exportar la tabla. | Media         |

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

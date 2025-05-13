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

### Epics:

| Epic ID | Título                         | Objetivo                                                                                                                      |
|-------|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| E1     | Gestión de Inventario                  | Como emprendedor, quiero gestionar y registrar mi inventario para tener control preciso del stock y evitar desabastecimientos. |
| E2     | Monitoreo en Tiempo Real con Sensores  | Como gestor, quiero monitorear condiciones ambientales en tiempo real para prevenir daños por cambios de temperatura/humedad. |
| E3     | Alertas Automáticas                    | Como propietario, quiero recibir alertas cuando las condiciones no sean óptimas para tomar acciones correctivas inmediatas.     |
| E4     | Visualización de Datos y Reportes      | Como gerente, quiero acceder a reportes visuales para analizar información y mejorar la gestión del inventario.                |
| E5     | Sistema de Recomendaciones             | Como propietario, quiero recibir recomendaciones basadas en datos para optimizar espacio y condiciones de almacenamiento.      |
| E6     | Suscripción y Administración de Planes | Como usuario, quiero gestionar mi suscripción para acceder a funcionalidades adecuadas a mi negocio.                          |
| E7     | Alquiler de Sensores Físicos           | Como propietario, quiero alquilar sensores para monitorear condiciones sin comprarlos permanentemente.                        |
| E8     | Gestión de Usuarios y Roles            | Como administrador, quiero gestionar usuarios y roles para controlar accesos y garantizar seguridad.                          |
| E9     | Desarrollo de Landing Page Inicial            | Como visitante de la plataforma, quiero ver una landing page clara y funcional, para entender rápidamente el propósito del producto, el equipo y los valores, desde cualquier dispositivo.                          |


### User Stories:

| **ID**     | **Título**                                | **Historia de Usuario**                                                                                                            | **Criterios de Aceptación**                                                                                                                                                                                                                                                          | 
| ---------- | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | 
| **E1 - US001** | Registro Manual de Producto        | Como gestor, quiero registrar productos manualmente para tener un control actualizado.  | **Escenario 1:**<br>**Dado** que el usuario accede al formulario de registro<br>**Cuando** ingresa: nombre "Harina 000", cantidad "50", categoría "Insumos"<br>**Entonces** el sistema guarda el producto y muestra "Registro exitoso".<br><br>**Escenario 2:**<br>**Dado** un formulario con campo "nombre" vacío<br>**Cuando** intenta guardar<br>**Entonces** el sistema muestra "Complete todos los campos requeridos". |
| **E1 - US002** | Importación Masiva de Productos   | Como gestor, quiero importar productos desde Excel para ahorrar tiempo.                | **Escenario 1:**<br>**Dado** un archivo Excel con 100 productos (columnas: código, nombre, stock)<br>**Cuando** sube el archivo<br>**Entonces** el sistema muestra "100 productos importados correctamente".<br><br>**Escenario 2:**<br>**Dado** un archivo .txt en lugar de .xlsx<br>**Cuando** intenta importar<br>**Entonces** el sistema muestra "Formato no soportado: use plantilla Excel". |
| **E1 - US003** | Escaneo de Productos              | Como gestor, quiero escanear productos para registrarlos rápidamente.                  | **Escenario 1:**<br>**Dado** un código QR válido asociado a "Aceite de Oliva 1L"<br>**Cuando** escanea el código<br>**Entonces** el sistema autocompleta: nombre "Aceite de Oliva", capacidad "1L", categoría "Aceites".<br><br>**Escenario 2:**<br>**Dado** un código dañado no legible<br>**Cuando** intenta escanear<br>**Entonces** el sistema muestra "Código no reconocido: registre manualmente". |
| **E1 - US004** | Búsqueda de Productos             | Como gestor, quiero buscar productos por nombre/lote para ubicarlos rápido.            | **Escenario 1:**<br>**Dado** 3 productos que contienen "azúcar" en su nombre<br>**Cuando** busca "azu"<br>**Entonces** el sistema muestra sugerencias: "Azúcar rubia", "Azúcar blanca", "Azúcar orgánica".<br><br>**Escenario 2:**<br>**Dado** un lote "LOTE-2024-ABC" inexistente<br>**Cuando** busca este lote<br>**Entonces** el sistema muestra "0 resultados: verifique el código". |
| **E1 - US005** | Ajuste Rápido de Stock            | Como gestor, quiero ajustar stock para corregir diferencias.                          | **Escenario 1:**<br>**Dado** un producto con stock actual 100 unidades<br>**Cuando** cambia a 120 unidades y guarda<br>**Entonces** el sistema actualiza el stock y registra "Ajuste +20 unidades".<br><br>**Escenario 2:**<br>**Dado** un campo de stock vacío<br>**Cuando** intenta guardar<br>**Entonces** el sistema muestra "Ingrese un valor numérico válido". |
| **E2 - US006** | Visualización en Tiempo Real de Sensores | Como gestor, quiero ver datos de sensores en tiempo real para asegurar condiciones óptimas. | **Escenario 1:**<br>**Dado** un producto "Leche Fresca" (lote: LF-2024-001)<br>**Cuando** el usuario selecciona el lote en el dashboard<br>**Entonces** el sistema muestra: temperatura 4°C, humedad 70%, actualizado hace 5 segundos.<br><br>**Escenario 2:**<br>**Dado** un sensor desconectado por 15 minutos<br>**Cuando** el usuario consulta el dashboard<br>**Entonces** el sistema muestra un icono rojo parpadeante y "Última conexión: 14:30". |
| **E2 - US007** | Asignación de Sensores a Productos | Como gestor, quiero asignar sensores para monitorear condiciones específicas. | **Escenario 1:**<br>**Dado** un sensor disponible (ID: SENS-045)<br>**Cuando** lo asigna al producto "Queso Madurado"<br>**Entonces** el sistema actualiza su estado a "Vinculado" y registra la hora de asignación.<br><br>**Escenario 2:**<br>**Dado** un sensor ya asignado a "Jamón Ibérico"<br>**Cuando** intenta reasignarlo a otro producto<br>**Entonces** el sistema muestra "Sensor ocupado: libere primero". |
| **E2 - US008** | Ver Historial de Condiciones Ambientales | Como gestor, quiero consultar historial ambiental para verificar cumplimiento. | **Escenario 1:**<br>**Dado** un producto almacenado por 30 días<br>**Cuando** selecciona "Ver historial"<br>**Entonces** el sistema muestra gráfico de temperaturas con picos máximos/mínimos diarios.<br><br>**Escenario 2:**<br>**Dado** un rango de fechas (01/01 a 15/01/2024)<br>**Cuando** exporta a CSV<br>**Entonces** el archivo contiene 360 registros horarios (15 días × 24 horas). |
| **E2 - US009** | Monitoreo por Ubicación | Como gestor, quiero visualizar sensores por zona para facilitar inspecciones. | **Escenario 1:**<br>**Dado** el almacén dividido en zona A/B/C<br>**Cuando** selecciona "Zona B" en el mapa interactivo<br>**Entonces** el sistema lista 3 sensores activos con última medición hace <1 minuto.<br><br>**Escenario 2:**<br>**Dado** una zona sin sensores asignados<br>**Cuando** consulta esa área<br>**Entonces** el sistema muestra "Ningún sensor activo: considere instalación". |
| **E2 - US010** | Estado de Conectividad de Sensores | Como propietario, quiero detectar sensores inactivos para evitar pérdidas. | **Escenario 1:**<br>**Dado** un sensor sin comunicación por 2 horas<br>**Cuando** se genera alerta automática<br>**Entonces** el sistema: (1) Notifica en dashboard, (2) Envía SMS al técnico, (3) Registra incidencia.<br><br>**Escenario 2:**<br>**Dado** un sensor recuperado tras falla<br>**Cuando** reanuda transmisión<br>**Entonces** el sistema actualiza estado a "Activo" y envía confirmación por email. |
| **E3 - US011** | Generación de Alertas por Temperatura Anómala | Como propietario, quiero alertas automáticas para prevenir daños por temperatura inadecuada. | **Escenario 1:**<br>**Dado** un producto "Yogur Griego" con rango configurado (2°C a 6°C)<br>**Cuando** el sensor reporta 8°C por 15 minutos<br>**Entonces** el sistema: (1) Activa alerta roja en dashboard, (2) Envía email a "alerta@empresa.com", (3) Registra evento en historial.<br><br>**Escenario 2:**<br>**Dado** temperatura vuelve a rango seguro (5°C)<br>**Cuando** se actualizan los datos<br>**Entonces** la alerta cambia a estado "Resuelta" automáticamente. |
| **E3 - US012** | Configuración de Rangos Permitidos | Como gestor, quiero definir parámetros precisos para cada producto. | **Escenario 1:**<br>**Dado** el producto "Salmón Ahumado"<br>**Cuando** se configuran: temp. (-2°C a +4°C), humedad (80-85%)<br>**Entonces** el sistema guarda los valores y los aplica a futuras mediciones.<br><br>**Escenario 2:**<br>**Dado** un intento de ingresar humedad al 120%<br>**Cuando** se guarda la configuración<br>**Entonces** el sistema muestra "Error: rango de humedad inválido (máx 95%)". |
| **E3 - US013** | Notificación de Desconexión de Sensor | Como propietario, quiero detectar fallas en sensores para mantener la calidad. | **Escenario 1:**<br>**Dado** un sensor en "Cámara 3" sin comunicación por 45 minutos<br>**Cuando** se supera el umbral de 30 minutos<br>**Entonces** el sistema: (1) Notifica por SMS al técnico, (2) Marca zona como "Riesgo", (3) Genera ticket de soporte automático.<br><br>**Escenario 2:**<br>**Dado** un sensor recupera conexión<br>**Cuando** envía nuevos datos<br>**Entonces** el sistema actualiza estado a "Estable" y notifica por email. |
| **E3 - US014** | Registro de Alertas Emitidas | Como gestor, quiero auditar eventos críticos para mejorar procesos. | **Escenario 1:**<br>**Dado** 15 alertas generadas en la última semana<br>**Cuando** se filtra por "Tipo: Temperatura"<br>**Entonces** el sistema muestra 8 registros con detalles: producto, hora, valor medido.<br><br>**Escenario 2:**<br>**Dado** un reporte seleccionado<br>**Cuando** se exporta a Excel<br>**Entonces** el archivo contiene columnas: Fecha, Hora, Sensor, Valor, Acción Tomada. |
| **E3 - US015** | Alerta por Producto Crítico en Stock | Como propietario, quiero priorizar acciones sobre productos en riesgo. | **Escenario 1:**<br>**Dado** "Queso Brie" con: stock=5 unidades (mínimo=10) y temp=10°C (máx=8°C)<br>**Cuando** se detecta la condición<br>**Entonces** el sistema: (1) Muestra alerta "URGENTE" en rojo, (2) Sugiere "Retirar inmediatamente", (3) Bloquea nuevas ventas.<br><br>**Escenario 2:**<br>**Dado** stock crítico pero condiciones óptimas<br>**Cuando** se verifica el producto<br>**Entonces** el sistema solo muestra alerta amarilla "Reponer stock". |
| **E4 - US016** | Visualización de Temperaturas en Gráfica | Como gerente, quiero analizar tendencias térmicas para prevenir incidentes. | **Escenario 1:**<br>**Dado** el producto "Helado de Vainilla" (lote: HV-0724)<br>**Cuando** selecciona "Últimas 24 horas" en el filtro<br>**Entonces** el sistema muestra una gráfica lineal con picos de -18°C a -15°C y promedia -16.5°C.<br><br>**Escenario 2:**<br>**Dado** un sensor sin datos históricos<br>**Cuando** intenta generar la gráfica<br>**Entonces** el sistema muestra "No hay datos disponibles para este periodo". |
| **E4 - US017** | Reporte Detallado de Sensores Activos | Como gerente, quiero verificar el estado operativo de los sensores. | **Escenario 1:**<br>**Dado** 15 sensores instalados (12 activos, 3 inactivos)<br>**Cuando** filtra por "Estado: Activo"<br>**Entonces** el sistema lista los 12 sensores con: ID, ubicación exacta y última medición hace <2 minutos.<br><br>**Escenario 2:**<br>**Dado** una zona sin sensores asignados<br>**Cuando** aplica filtro por "Zona: Congelados"<br>**Entonces** el sistema muestra "0 sensores registrados en esta área". |
| **E4 - US018** | Descarga de Reportes en PDF | Como gerente, quiero compartir reportes técnicos formalmente. | **Escenario 1:**<br>**Dado** un reporte de 30 páginas generado<br>**Cuando** descarga en PDF<br>**Entonces** el archivo incluye: logo corporativo, tabla de contenidos, y datos en formato A4 (210x297mm).<br><br>**Escenario 2:**<br>**Dado** un error de generación de PDF<br>**Cuando** falla la descarga<br>**Entonces** el sistema muestra "Error: intente nuevamente en 5 minutos" y registra el incidente. |
| **E4 - US019** | Historial Ambiental por Producto | Como gestor, quiero auditar condiciones de almacenamiento históricas. | **Escenario 1:**<br>**Dado** "Salmón Noruego" almacenado por 90 días<br>**Cuando** exporta historial a CSV<br>**Entonces** el archivo contiene 2,160 registros (1 por hora) con columnas: Fecha, Hora, Temp(°C), Humedad(%).<br><br>**Escenario 2:**<br>**Dado** un rango de fechas inválido (15/07/2024 a 01/07/2024)<br>**Cuando** intenta consultar<br>**Entonces** el sistema muestra "Rango temporal no válido: la fecha final debe ser posterior a la inicial". |
| **E4 - US020** | Comparación Ventas vs Stock | Como propietario, quiero optimizar mi inventario basado en demanda. | **Escenario 1:**<br>**Dado** "Atún en Lata" con: stock=500 unidades, ventas=1,200 unidades/mes<br>**Cuando** genera el reporte<br>**Entonces** el sistema: (1) Destaca en rojo "Déficit: -700 unidades", (2) Sugiere "Aumentar producción al 150%".<br><br>**Escenario 2:**<br>**Dado** "Galletas Integrales" con stock=300 unidades y ventas=50 unidades/mes<br>**Cuando** ordena por "Sobreinventario"<br>**Entonces** el sistema muestra este producto primero con alerta amarilla "Reducir compras en 80%". |
| **E5 - US021** | Recomendaciones de Mejora por Producto | Como propietario, quiero optimizar el almacenamiento para reducir pérdidas. | **Escenario 1:**<br>**Dado** "Chocolate Negro" con 5 desviaciones de temperatura (>25°C) en 7 días<br>**Cuando** el sistema analiza su historial<br>**Entonces** recomienda: "Almacenar en zona refrigerada (18-20°C) y evitar exposición solar".<br><br>**Escenario 2:**<br>**Dado** un producto sin desviaciones registradas<br>**Cuando** se consultan recomendaciones<br>**Entonces** el sistema muestra "Condiciones óptimas: mantener protocolo actual". |
| **E5 - US022** | Sugerencias para Optimización de Espacio | Como gestor, quiero reorganizar el almacén según demanda. | **Escenario 1:**<br>**Dado** "Café Molido" (rotación alta: 200 uds/semana) en zona remota<br>**Cuando** el sistema evalúa patrones<br>**Entonces** sugiere: "Reubicar cerca del área de despacho para reducir tiempos de picking".<br><br>**Escenario 2:**<br>**Dado** "Té Verde" (rotación baja: 10 uds/mes)<br>**Cuando** se ignoran las sugerencias<br>**Entonces** el sistema registra "Recomendación pendiente" y notifica cada 15 días. |
| **E5 - US023** | Alertas de Producto con Baja Rotación | Como administrador, quiero actuar sobre stock estancado. | **Escenario 1:**<br>**Dado** "Mermelada de Arándano" sin ventas en 60 días<br>**Cuando** se activa la alerta<br>**Entonces** el sistema propone: "Paquete promocional 2x1 o donación a comedores".<br><br>**Escenario 2:**<br>**Dado** un producto con rotación recuperada<br>**Cuando** se revisa el historial<br>**Entonces** el sistema muestra gráfico de ventas post-promoción (+300% en 2 semanas). |
| **E5 - US024** | Recomendaciones Basadas en Clima | Como emprendedor, quiero programar operaciones en horarios óptimos. | **Escenario 1:**<br>**Dado** picos de humedad >80% entre 14:00-16:00<br>**Cuando** se consultan horarios sugeridos<br>**Entonces** el sistema recomienda: "Mover productos secos antes de las 11:00".<br><br>**Escenario 2:**<br>**Dado** la función desactivada<br>**Cuando** se intenta usar<br>**Entonces** el sistema muestra "Habilite esta opción en Configuración > Alertas Inteligentes". |
| **E5 - US025** | Evaluación de Cumplimiento de Recomendaciones | Como propietario, quiero medir el impacto de las mejoras. | **Escenario 1:**<br>**Dado** la reubicación de "Queso Azul" a zona más fría<br>**Cuando** se comparan datos (antes/después)<br>**Entonces** el sistema muestra: "Reducción del 70% en variaciones térmicas".<br><br>**Escenario 2:**<br>**Dado** una recomendación no implementada<br>**Cuando** se evalúa su impacto potencial<br>**Entonces** el sistema proyecta: "Ahorro estimado de $1,200/mes si se aplica". |
| **E6 - US026** | Selección de Plan de Suscripción    | Como usuario nuevo, quiero elegir un plan que se ajuste a mi negocio.                  | **Escenario 1:**<br>**Dado** un usuario en registro inicial<br>**Cuando** accede a "Planes Disponibles"<br>**Entonces** el sistema muestra 3 opciones: Básico (10 sensores), Profesional (50 sensores), Empresa (ilimitado).<br><br>**Escenario 2:**<br>**Dado** la selección del plan "Profesional"<br>**Cuando** completa el pago<br>**Entonces** el sistema habilita 50 sensores y envía confirmación por email. |
| **E6 - US027** | Cambio de Plan en Cualquier Momento | Como usuario registrado, quiero actualizar mi plan según necesidades.                 | **Escenario 1:**<br>**Dado** un usuario con plan "Básico" activo<br>**Cuando** actualiza a "Empresa"<br>**Entonces** el sistema: (1) Calcula prorrateo ($120 diferencia), (2) Emite factura proforma, (3) Habilita sensores ilimitados en 2h.<br><br>**Escenario 2:**<br>**Dado** un downgrade de plan<br>**Cuando** excede los límites del nuevo plan<br>**Entonces** el sistema notifica "Desactive 15 sensores antes del cambio". |
| **E6 - US028** | Visualización de Beneficios por Plan | Como usuario, quiero comparar planes para tomar decisiones informadas.               | **Escenario 1:**<br>**Dado** un emprendedor de alimentos<br>**Cuando** filtra por "Recomendado para sector alimentario"<br>**Entonces** el sistema resalta el plan "Profesional" con: monitoreo 24/7 y alertas FDA.<br><br>**Escenario 2:**<br>**Dado** un usuario con plan "Empresa"<br>**Cuando** consulta beneficios<br>**Entonces** el sistema muestra en verde "VIP: Soporte prioritario 24/7". |
| **E6 - US029** | Renovación Automática del Plan       | Como usuario, quiero continuidad de servicio sin interrupciones.                     | **Escenario 1:**<br>**Dado** una suscripción mensual con tarjeta válida<br>**Cuando** llega el día 30 del mes<br>**Entonces** el sistema: (1) Cobra $99, (2) Envía recibo PDF, (3) Mantiene acceso ininterrumpido.<br><br>**Escenario 2:**<br>**Dado** un pago rechazado<br>**Cuando** falla la renovación<br>**Entonces** el sistema: (1) Notifica por SMS/email, (2) Da 3 días de gracia, (3) Suspende acceso tras 72h. |
| **E6 - US030** | Cancelación de la Suscripción        | Como usuario, quiero dejar de usar el servicio sin cargos recurrentes.               | **Escenario 1:**<br>**Dado** un usuario que pagó hasta el 15/07<br>**Cuando** cancela el 10/07<br>**Entonces** el sistema: (1) Permite uso hasta 15/07, (2) Elimina datos el 16/07, (3) Envía encuesta de retiro.<br><br>**Escenario 2:**<br>**Dado** una cancelación durante periodo gratuito<br>**Cuando** confirma la acción<br>**Entonces** el sistema revoca acceso inmediatamente y elimina datos en 24h. |
| **E7 - US031** | Alquiler de Sensores Físicos       | Como propietario, quiero alquilar sensores para garantizar condiciones controladas.     | **Escenario 1:**<br>**Dado** un catálogo con 3 tipos de sensores (Temperatura, Humedad, GPS)<br>**Cuando** selecciona "Sensor GPS Trimble TDC100" a $15/día<br>**Entonces** el sistema: (1) Reserva el sensor, (2) Genera contrato digital, (3) Programa envío en 24h.<br><br>**Escenario 2:**<br>**Dado** un sensor agotado en stock<br>**Cuando** intenta alquilar<br>**Entonces** el sistema muestra "Disponible a partir del 20/08" y opción de pre-reserva. |
| **E7 - US032** | Activación de Sensores en Productos | Como propietario, quiero vincular sensores a productos para monitoreo preciso.         | **Escenario 1:**<br>**Dado** el producto "Caviar Ruso" y sensor "TERMO-007" alquilado<br>**Cuando** asigna el sensor al producto<br>**Entonces** el sistema: (1) Muestra "Activado", (2) Inicia transmisión cada 30 segundos, (3) Bloquea reasignación por 24h.<br><br>**Escenario 2:**<br>**Dado** un sensor no configurado<br>**Cuando** intenta activarlo<br>**Entonces** el sistema muestra "Complete calibración primero (Guía paso a paso)". |
| **E7 - US033** | Monitoreo del Estado de Sensores    | Como propietario, quiero verificar el funcionamiento de los sensores en tiempo real.    | **Escenario 1:**<br>**Dado** 10 sensores activos y 2 inactivos<br>**Cuando** filtra por "Estado: Crítico"<br>**Entonces** el sistema lista: "SENS-022: Batería 5%", "SENS-045: Sin señal 2h".<br><br>**Escenario 2:**<br>**Dado** un sensor en modo mantenimiento<br>**Cuando** consulta su estado<br>**Entonces** el sistema muestra "En calibración: disponible el 15/08 a las 14:00". |
| **E7 - US034** | Registro de Alquiler y Activación   | Como administrador, quiero auditar el uso de sensores.                                | **Escenario 1:**<br>**Dado** un alquiler de 5 sensores el 01/08<br>**Cuando** consulta el historial<br>**Entonces** el sistema muestra: usuario, fechas, costos ($75), y productos asociados.<br><br>**Escenario 2:**<br>**Dado** un sensor no activado dentro de 72h<br>**Cuando** revisa registros<br>**Entonces** el sistema notifica "Alerta: sensor inactivo - costo mínimo $10 aplicado". |
| **E7 - US035** | Desactivación y Devolución         | Como propietario, quiero gestionar sensores obsoletos para optimizar costos.          | **Escenario 1:**<br>**Dado** un sensor con 2 días restantes de alquiler<br>**Cuando** solicita devolución anticipada<br>**Entonces** el sistema: (1) Calcula reembolso proporcional ($20), (2) Genera etiqueta de retorno, (3) Desactiva monitoreo en 1h.<br><br>**Escenario 2:**<br>**Dado** una devolución con daño físico<br>**Cuando** el técnico verifica<br>**Entonces** el sistema aplica cargo de $50 y actualiza estado a "Requiere reparación". |
| **E8 - US036** | Creación de Usuarios               | Como administrador, quiero agregar nuevos usuarios para gestionar accesos.             | **Escenario 1:**<br>**Dado** un rol "Supervisor" predefinido<br>**Cuando** crea un usuario con: nombre "Ana López", correo "ana@empresa.com", rol "Supervisor"<br>**Entonces** el sistema: (1) Envía email de activación, (2) Genera contraseña temporal, (3) Registra en bitácora.<br><br>**Escenario 2:**<br>**Dado** un correo duplicado "juan@empresa.com"<br>**Cuando** intenta guardar<br>**Entonces** el sistema muestra "Error: correo ya registrado". |
| **E8 - US037** | Asignación de Roles a Usuarios     | Como administrador, quiero controlar permisos mediante roles específicos.              | **Escenario 1:**<br>**Dado** el usuario "Pedro Méndez" sin roles asignados<br>**Cuando** se le asigna "Gestor de Almacén"<br>**Entonces** el sistema: (1) Habilita módulos de inventario, (2) Restringe ajustes financieros, (3) Notifica por email.<br><br>**Escenario 2:**<br>**Dado** un rol eliminado "Auditor Externo"<br>**Cuando** intenta asignarlo<br>**Entonces** el sistema muestra "Rol no disponible: contacte al soporte". |
| **E8 - US038** | Edición de Usuarios y Roles        | Como administrador, quiero actualizar información de usuarios para mantener datos actualizados. | **Escenario 1:**<br>**Dado** un usuario con teléfono "+51 999888777"<br>**Cuando** actualiza a "+51 987654321"<br>**Entonces** el sistema: (1) Valida el formato, (2) Solicita confirmación vía SMS, (3) Registra el cambio.<br><br>**Escenario 2:**<br>**Dado** un intento de eliminar al único administrador<br>**Cuando** guarda los cambios<br>**Entonces** el sistema bloquea la acción y muestra "Se requiere al menos un administrador activo". |
| **E8 - US039** | Desactivación de Usuarios          | Como administrador, quiero revocar accesos innecesarios para proteger datos sensibles. | **Escenario 1:**<br>**Dado** un usuario despedido "Carlos Ruiz"<br>**Cuando** desactiva su cuenta<br>**Entonces** el sistema: (1) Cierra sesiones activas, (2) Encripta sus datos, (3) Notifica al equipo de seguridad.<br><br>**Escenario 2:**<br>**Dado** un usuario desactivado que intenta ingresar<br>**Cuando** usa sus credenciales<br>**Entonces** el sistema muestra "Cuenta suspendida: contacte al administrador". |
| **E8 - US040** | Visualización de Actividad de Usuarios | Como administrador, quiero auditar acciones críticas para garantizar cumplimiento. | **Escenario 1:**<br>**Dado** 500 registros de actividad<br>**Cuando** filtra por "Usuario: María" y "Acción: Eliminación"<br>**Entonces** el sistema muestra 3 eventos con detalles: fecha, hora y IP de origen.<br><br>**Escenario 2:**<br>**Dado** una exportación de registros<br>**Cuando** selecciona formato CSV<br>**Entonces** el archivo incluye columnas: Timestamp (UTC), Usuario, Acción, Impacto. |
| **E11 - US041** | Diseño Responsive de la Landing Page | Como visitante, quiero que la landing page se adapte a cualquier dispositivo, para tener una experiencia fluida desde PC, tablet o celular. | **Escenario 1:**<br>**Dado** que ingreso desde un celular<br>**Cuando** accedo a la página principal<br>**Entonces** todos los elementos se adaptan al ancho y se ven correctamente.<br><br>**Escenario 2:**<br>**Dado** que ingreso desde una laptop<br>**Cuando** visualizo la landing page<br>**Entonces** los textos, imágenes y secciones están bien distribuidos sin desbordamientos. |
| **E11 - US042** | Sección de Información del Producto | Como visitante, quiero ver una breve descripción del producto, para entender qué problema resuelve y cómo me beneficia. | **Escenario 1:**<br>**Dado** que estoy en la landing page<br>**Cuando** hago scroll hasta la sección de producto<br>**Entonces** veo un texto claro con su función, características clave y beneficios.<br><br>**Escenario 2:**<br>**Dado** que reviso el contenido<br>**Cuando** hago clic en "Conocer más"<br>**Entonces** soy dirigido a una sección con más detalles o un enlace externo si aplica. |
| **E11 - US043** | Sección "Conócenos" del Equipo | Como visitante, quiero conocer quiénes desarrollan el producto, para confiar en su profesionalismo y propósito. | **Escenario 1:**<br>**Dado** que estoy en la landing page<br>**Cuando** llego a la sección del equipo<br>**Entonces** veo nombres, roles y una breve descripción de cada miembro.<br><br>**Escenario 2:**<br>**Dado** que hay varios integrantes<br>**Cuando** la pantalla es pequeña<br>**Entonces** las tarjetas del equipo se adaptan a una vista en columna. |
| **E11 - US044** | Sección de Valores del Proyecto | Como visitante, quiero ver los valores y principios detrás del proyecto, para saber si me identifico con su misión. | **Escenario 1:**<br>**Dado** que estoy explorando la landing<br>**Cuando** llego a la sección de valores<br>**Entonces** se muestran 3 a 5 valores con íconos y frases cortas.<br><br>**Escenario 2:**<br>**Dado** que hago clic en un valor<br>**Cuando** se despliega información<br>**Entonces** puedo leer más sobre cómo se aplica ese valor en el producto. |
| **E11 - US045** | Botón de Ingreso al Sistema con Menú Navegable | Como visitante, quiero tener un botón que me lleve al sistema y un menú que me permita navegar entre secciones, para acceder rápidamente a lo que necesito. | **Escenario 1:**<br>**Dado** que estoy en la parte superior de la landing<br>**Cuando** hago clic en "Ingresar"<br>**Entonces** soy redirigido al frontend funcional del sistema.<br><br>**Escenario 2:**<br>**Dado** que veo el menú de navegación<br>**Cuando** hago clic en "Producto", "Equipo" o "Valores"<br>**Entonces** la vista se desplaza suavemente a la sección correspondiente. |
| **E1 - TS001** | Escaneo de Código QR desde la Cámara | Como usuario del sistema, quiero escanear el código QR de un producto usando la cámara del dispositivo, para registrar su trazabilidad de forma rápida y automática. | **Escenario 1:**<br>**Dado** que estoy en la pantalla de escaneo<br>**Cuando** permito el acceso a la cámara y escaneo un QR válido<br>**Entonces** se registra el producto escaneado en el sistema.<br><br>**Escenario 2:**<br>**Dado** que estoy en la pantalla de escaneo<br>**Cuando** el código QR no es válido<br>**Entonces** se muestra un mensaje de error indicando que no se pudo identificar el producto.<br><br>**Escenario 3:**<br>**Dado** que el navegador no permite acceder a la cámara<br>**Cuando** intento escanear un producto<br>**Entonces** se muestra una advertencia con instrucciones para habilitar el permiso. |
| **E2 - TS002** | Visualización de Productos Escaneados | Como usuario, quiero ver un listado con los productos que han sido escaneados, para poder verificar su información rápidamente. | **Escenario 1:**<br>**Dado** que ya he escaneado productos<br>**Cuando** ingreso a la pantalla de productos escaneados<br>**Entonces** veo una tabla con el nombre, fecha de escaneo y temperatura actual.<br><br>**Escenario 2:**<br>**Dado** que no hay productos escaneados<br>**Cuando** ingreso a la pantalla<br>**Entonces** veo un mensaje indicando que aún no hay productos registrados. |
| **E3 - TS003** | Visualización de la Trazabilidad de un Producto | Como usuario, quiero ver el historial completo de temperatura y ubicación de un producto, para asegurarme de que se ha almacenado correctamente. | **Escenario 1:**<br>**Dado** que selecciono un producto en el listado<br>**Cuando** hago clic en el botón "Ver Trazabilidad"<br>**Entonces** se muestra una línea de tiempo con eventos de ubicación y temperatura.<br><br>**Escenario 2:**<br>**Dado** que el producto no tiene registros de trazabilidad<br>**Cuando** intento ver su historial<br>**Entonces** se muestra un mensaje indicando que no hay datos disponibles aún. |
| **E4 - TS004** | Formulario para Agregar Productos Manualmente | Como usuario del sistema, quiero llenar un formulario con los datos del producto, para poder registrar nuevos productos sin depender de archivos ni escáneres. | **Escenario 1:**<br>**Dado** que estoy en la pantalla de "Agregar Producto"<br>**Cuando** completo todos los campos requeridos<br>**Entonces** el botón "Guardar" se habilita y se guarda el producto correctamente.<br><br>**Escenario 2:**<br>**Dado** que dejo campos vacíos o ingreso datos inválidos<br>**Cuando** intento guardar el formulario<br>**Entonces** se muestra un mensaje de error indicando qué debe corregirse.<br><br>**Escenario 3:**<br>**Dado** que se ha guardado un producto<br>**Cuando** regreso a la lista de productos<br>**Entonces** puedo ver el nuevo producto agregado al final de la lista. |
| **E5 - TS005** | Alerta de Temperatura fuera de Rango | Como usuario, quiero recibir una alerta visual si un producto supera su rango de temperatura, para tomar acciones rápidamente y evitar riesgos. | **Escenario 1:**<br>**Dado** que estoy viendo el listado de productos<br>**Cuando** uno de ellos supera su temperatura permitida<br>**Entonces** se muestra un ícono de advertencia o cambio de color.<br><br>**Escenario 2:**<br>**Dado** que todos los productos están en rangos normales<br>**Cuando** ingreso a la pantalla<br>**Entonces** no se muestran alertas. |
| **E6 - TS006** | Filtro por Categoría de Producto | Como usuario, quiero filtrar los productos por categoría, para encontrar rápidamente los productos que necesito revisar. | **Escenario 1:**<br>**Dado** que tengo múltiples productos registrados<br>**Cuando** selecciono una categoría del filtro<br>**Entonces** solo se muestran los productos correspondientes.<br><br>**Escenario 2:**<br>**Dado** que no hay productos en una categoría<br>**Cuando** la selecciono<br>**Entonces** se muestra un mensaje de "No hay productos en esta categoría". |
| **E7 - TS007** | Integración con Datos Simulados de Sensores | Como desarrollador, quiero conectar el sistema con datos simulados de sensores, para probar el comportamiento del sistema sin hardware real. | **Escenario 1:**<br>**Dado** que el sistema está en modo simulación<br>**Cuando** visualizo la trazabilidad<br>**Entonces** se muestran datos generados de temperatura y ubicación.<br><br>**Escenario 2:**<br>**Dado** que apago la simulación<br>**Cuando** vuelvo a consultar los productos<br>**Entonces** los valores simulados dejan de actualizarse. |
| **E8 - TS008** | Exportar Trazabilidad a PDF | Como usuario, quiero exportar el historial de trazabilidad de un producto a PDF, para poder compartirlo o archivarlo. | **Escenario 1:**<br>**Dado** que estoy viendo la trazabilidad de un producto<br>**Cuando** hago clic en "Exportar PDF"<br>**Entonces** se descarga un archivo con los datos del producto.<br><br>**Escenario 2:**<br>**Dado** que el producto no tiene datos<br>**Cuando** intento exportar<br>**Entonces** se muestra un mensaje de advertencia que indica que no hay contenido para exportar. |
| **E9 - TS009** | Indicador de Estado del Producto | Como usuario, quiero ver un estado general del producto (óptimo / riesgo / crítico), para evaluar rápidamente su condición. | **Escenario 1:**<br>**Dado** que el producto tiene temperaturas normales<br>**Cuando** veo su estado<br>**Entonces** aparece como "Óptimo".<br><br>**Escenario 2:**<br>**Dado** que el producto ha estado fuera de su rango varias veces<br>**Cuando** consulto su estado<br>**Entonces** aparece como "Crítico" o "Riesgo", según la gravedad. |
| **E10 - TS010** | Responsive Design para Móviles | Como usuario con celular, quiero que la aplicación se adapte bien a pantallas pequeñas, para poder usar todas las funciones desde cualquier dispositivo. | **Escenario 1:**<br>**Dado** que ingreso desde un dispositivo móvil<br>**Cuando** navego entre pantallas<br>**Entonces** todos los elementos se adaptan sin desbordarse.<br><br>**Escenario 2:**<br>**Dado** que uso la cámara o el formulario desde un celular<br>**Cuando** interactúo con los controles<br>**Entonces** la experiencia es fluida y los botones son accesibles. |

## 3.3. Impact Mapping

### Segmento 1:
<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/requirements-specification/Images/Segmento%201.png?raw=true" style="width: 100%;"/>

### Segmento 2:

<img src="https://github.com/UPC-PRE-202501-1ASI0729-4350-Rurasqay/UPC-PRE-202501-1ASI0729-4350-Rurasqay-report/blob/feature/requirements-specification/Images/Segmento%202%20(1).png?raw=true" style="width: 100%;"/>

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
| 41     | E9 - US041     | Diseño Responsive de la Landing Page          | Como visitante, quiero que la landing page se adapte a cualquier dispositivo, para tener una experiencia fluida.         | 5            |
| 42     | E9 - US042     | Sección de Información del Producto           | Como visitante, quiero ver una breve descripción del producto, para entender qué problema resuelve y cómo me beneficia.  | 3            |
| 43     | E9 - US045     | Botón de Ingreso al Sistema con Menú Navegable| Como visitante, quiero tener un botón que me lleve al sistema y un menú para navegar entre secciones.                    | 5            |
| 44     | E9 - US043     | Sección "Conócenos" del Equipo                | Como visitante, quiero conocer quiénes desarrollan el producto, para confiar en su profesionalismo y propósito.          | 3            |
| 45     | E9 - US044     | Sección de Valores del Proyecto               | Como visitante, quiero ver los valores y principios detrás del proyecto, para saber si me identifico con su misión.      | 3            |

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

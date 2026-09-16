# Informe de Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**

**Carrera de Ingeniería de Software**

**1ACC0238 — Aplicaciones para Dispositivos Móviles**

**NRC: 13975**

**Docente:** Por completar

**Equipo:** NovaTech

**Proyecto:** TerraTech

**Integrantes**

| Código | Apellidos y nombres |
| --- | --- |
| U20231D390 | Bendezú Navarro, Rúbens Fitzgerald |
| Por completar | Integrante 2 (Por completar) |
| Por completar | Integrante 3 (Por completar) |
| Por completar | Integrante 4 (Por completar) |
| Por completar | Integrante 5 (Por completar) |

**Periodo: 202620**

**Mes y año:** Septiembre 2026

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| --- | --- | --- | --- |
| 0.1.0 | 15/09/2026 | Bendezú Navarro, Rúbens Fitzgerald | Elaboración completa de la sección 2.3.5 Big Picture EventStorming, sección 2.5 Strategic-Level Domain-Driven Design (Candidate Context Discovery, Domain Storytelling, Bounded Context Canvases, Context Mapping y Diagramas C4 de Contexto, Contenedores y Despliegue), perfil de integrante, objetivos SMART y Student Outcome 7. |

## Project Report Collaboration Insights

**Repositorio del informe:** [TerraTech Project Report](https://github.com/AppMovil-Dato/terratech-project-report)

### AV1

Durante este primer hito del proyecto (AV1), el equipo organizó el trabajo mediante el flujo GitFlow a partir de la rama `develop`, asignando responsabilidades específicas por capítulos y artefactos de diseño. La colaboración se gestionó a través de ramas `feature/*` individuales con Pull Requests y trazabilidad mediante Conventional Commits.

| Integrante | Usuario de GitHub | Actividades realizadas | Commits | Evidencia |
| --- | --- | --- | --- | --- |
| Bendezú Navarro, Rúbens Fitzgerald | Lucemz | Liderazgo y documentación de Big Picture EventStorming (2.3.5), Strategic DDD (2.5), Domain Storytelling, Bounded Context Canvases, Context Mapping, Diagramas C4 (Contexto, Contenedores, Despliegue) y perfil de integrante. | 2 commits | Rama `feature/strategic-ddd-c4` |
| Por completar | Por completar | Capítulo I: Presentación, Startup Profile, Solution Profile y Lean UX | Por completar | Por completar |
| Por completar | Por completar | Capítulo II: Competidores y Entrevistas (2.1 y 2.2) | Por completar | Por completar |
| Por completar | Por completar | Capítulo II: Needfinding y Requisitos (2.3 y 2.4) | Por completar | Por completar |
| Por completar | Por completar | Capítulo II: Tactical DDD (2.6) | Por completar | Por completar |

Ampliar esta sección en TB1, AV2 y TB2.

## Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [AV1](#av1)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Presentación](#capítulo-i-presentación)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. Big Picture EventStorming](#235-big-picture-eventstorming)
    - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
  - [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](#243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
    - [2.5.1. EventStorming](#251-eventstorming)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.x. Bounded Context: [Nombre por completar]](#26x-bounded-context-nombre-por-completar)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
  - [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
- [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)
  - [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)
    - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
    - [4.2.x. Sprint n](#42x-sprint-n)
  - [4.3. Validation Interviews](#43-validation-interviews)
    - [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)
    - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)
    - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video App Validation](#video-app-validation)
  - [Video About-the-Product](#video-about-the-product)
  - [Video About-the-Team](#video-about-the-team)
- [Glosario](#glosario)
- [Bibliografía](#bibliografía)
  - [Dominio de negocio](#dominio-de-negocio)
  - [Métodos y técnicas de ingeniería de software](#métodos-y-técnicas-de-ingeniería-de-software)
  - [Lenguajes, frameworks y herramientas](#lenguajes-frameworks-y-herramientas)
- [Anexos](#anexos)
  - [Anexo A. Videos de Exposiciones](#anexo-a-videos-de-exposiciones)
  - [Anexo B. Artefactos complementarios](#anexo-b-artefactos-complementarios)

## Student Outcome

**ABET - EAC - Student Outcome 7**

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7.

| Criterio específico | Acciones realizadas | Conclusiones |
| --- | --- | --- |
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | **Bendezú Navarro, Rúbens Fitzgerald (AV1):** Investigó y aplicó los principios de Domain-Driven Design (DDD) Estratégico (descubrimiento de Bounded Contexts, Domain Storytelling, Bounded Context Canvases y Context Mapping) junto con el modelado de arquitectura C4 (Contexto, Contenedores y Despliegue) orientado a aplicaciones móviles nativas Android con persistencia local Room y arquitectura limpia, asegurando una base técnica escalable para el monitoreo agrícola. *(Demás integrantes por completar en sus respectivas entregas).* | **Conclusión AV1:** El equipo aplicó metodologías formales de modelado estratégico de dominio y arquitectura de software orientada a dispositivos móviles, permitiendo estructurar los límites del sistema TerraTech de forma desacoplada y coherente con las necesidades del sector agrario peruano. |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. | **Bendezú Navarro, Rúbens Fitzgerald (AV1):** Reconoció la importancia de la autoformación constante en patrones de diseño arquitectónico móvil moderno (Jetpack Compose, Kotlin Coroutines, StateFlow y Offline-first data caching) para resolver problemáticas de baja conectividad en zonas rurales y garantizar la resiliencia operativa de la solución tecnológica. *(Demás integrantes por completar en sus respectivas entregas).* | **Conclusión AV1:** Se evidenció que la adopción de nuevas herramientas y estándares de la industria móvil resulta indispensable para abordar con éxito desafíos de ingeniería de software en entornos productivos no convencionales como el agro. |

## Objetivos SMART

| Integrante | Objetivo | Específico | Medible | Alcanzable | Relevante | Plazo |
| --- | --- | --- | --- | --- | --- | --- |
| Bendezú Navarro, Rúbens Fitzgerald | Certificación Profesional en Android | Obtener la certificación oficial Google Associate Android Developer (AAD). | Aprobar el examen práctico oficial y publicar al menos 2 aplicaciones con Jetpack Compose y Clean Architecture. | Estudiando 10 horas semanales y aplicando los conocimientos en proyectos de producción. | Consolida el perfil profesional en desarrollo nativo móvil de alto rendimiento. | 6 meses post-graduación |
| Bendezú Navarro, Rúbens Fitzgerald | Especialización en Arquitectura Cloud y DDD | Obtener la certificación AWS Certified Solutions Architect - Associate. | Completar la ruta formativa de Cloud Architecture y aprobar la certificación con puntaje $\ge 800/1000$. | Desarrollando laboratorios prácticos de microservicios, eventos distribuidos y DDD durante 8 meses. | Permite diseñar arquitecturas móviles y cloud escalables y resilientes a nivel empresarial. | 14 meses post-graduación |

## Capítulo I: Presentación

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

Completar la descripción de NovaTech, su propósito, misión, visión y propuesta de valor relacionada con TerraTech.

#### 1.1.2. Perfiles de integrantes del equipo

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr>
    <td rowspan="7" style="width: 25%; text-align: center; vertical-align: middle;">
      <img src="assets/images/team/fitzgerald-bendezu.png" alt="Rúbens Fitzgerald Bendezú Navarro" width="160" style="border-radius: 8px; border: 1px solid #cbd5e1;" />
    </td>
    <th style="width: 25%; text-align: left; padding: 6px;">Apellidos y nombres</th>
    <td style="width: 50%; padding: 6px;">Bendezú Navarro, Rúbens Fitzgerald</td>
  </tr>
  <tr>
    <th style="text-align: left; padding: 6px;">Código de estudiante</th>
    <td style="padding: 6px;">U20231D390</td>
  </tr>
  <tr>
    <th style="text-align: left; padding: 6px;">Carrera</th>
    <td style="padding: 6px;">Ingeniería de Software</td>
  </tr>
  <tr>
    <th style="text-align: left; padding: 6px;">Descripción personal</th>
    <td style="padding: 6px;">Estudiante de Ingeniería de Software con alto interés y especialización en el desarrollo de aplicaciones móviles nativas y el diseño de arquitecturas de software empresariales limpias y escalables. Apasionado por la aplicación de metodologías ágiles, Domain-Driven Design (DDD) y soluciones tecnológicas de alto impacto social y productivo en sectores estratégicos como la agricultura de precisión.</td>
  </tr>
  <tr>
    <th style="text-align: left; padding: 6px;">Conocimientos técnicos</th>
    <td style="padding: 6px;">Kotlin, Android Jetpack Compose, Coroutines, StateFlow, Room Database, Java 21, Spring Boot 3, PostgreSQL, Git/GitHub, GitFlow, Docker, Arquitectura Hexagonal / Limpia, Modelado C4 y Domain-Driven Design.</td>
  </tr>
  <tr>
    <th style="text-align: left; padding: 6px;">Habilidades y aporte al equipo</th>
    <td style="padding: 6px;">Liderazgo técnico en modelado de dominio y diseño de arquitectura de software, pensamiento analítico, capacidad de abstracción de problemas complejos del negocio, resolución de problemas y enfoque en la calidad y robustez del código.</td>
  </tr>
</table>

*(Fichas de los demás integrantes del equipo por completar).*

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

Describir los antecedentes de TerraTech y la problemática agrícola que atenderá la solución móvil. Sustentar el problema, los objetivos y las restricciones que delimitan el alcance.

Aplicar la técnica 5W + 2H:

| Pregunta | Aspecto que debe desarrollarse | Respuesta y fuente |
| --- | --- | --- |
| Who | Personas afectadas y responsables de las tareas del campo | Por completar |
| What | Problema concreto que enfrenta el usuario | Por completar |
| Where | Ubicación y entorno en que ocurre | Por completar |
| When | Momento y frecuencia del problema | Por completar |
| Why | Causas y consecuencias | Por completar |
| How | Proceso actual y herramientas utilizadas | Por completar |
| How much | Magnitud del problema, tiempo o costo | Por completar |

Definir las capacidades que se conservarán o adaptarán de TerraTech para la experiencia móvil. Precisar la relación entre monitoreo de campos, dispositivos, reportes y las necesidades de los segmentos seleccionados.

En el alcance considerar aplicación nativa y multiplataforma, almacenamiento local, acceso a un recurso interno del dispositivo, API REST propia, integración con un servicio externo y landing page. Incluir una funcionalidad que requiera investigar y aplicar una tecnología, biblioteca o servicio no utilizado en clase, justificando su selección y documentando el aprendizaje.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

Redactar un Problem Statement para todo el proyecto utilizando la plantilla Brand new initiative. Considerar todos los segmentos, el estado actual del dominio, las necesidades no atendidas por otras soluciones, la estrategia propuesta, el segmento inicial y los comportamientos medibles que indicarán éxito.

##### 1.2.2.2. Lean UX Assumptions

Enumerar varios supuestos por cada uno de los cinco tipos:

| ID | Tipo | Supuesto |
| --- | --- | --- |
| BA-01 | Business Assumptions | Completar creencias sobre mercado, viabilidad y monetización. |
| BOA-01 | Business Outcome Assumptions | Completar resultados medibles esperados para el negocio. |
| UA-01 | User Assumptions | Completar creencias sobre perfiles y segmentos. |
| UOA-01 | User Outcome and Benefit Assumptions | Completar objetivos y beneficios esperados por los usuarios. |
| FA-01 | Feature Assumptions | Completar funcionalidades propuestas para atender esas necesidades. |

##### 1.2.2.3. Lean UX Hypothesis Statements

Elaborar una hipótesis por cada Feature Assumption, relacionando resultado del negocio, usuarios, beneficio y funcionalidad.

> Creemos que lograremos [resultado del negocio] si [personas] alcanzan [beneficio o resultado del usuario] con [funcionalidad o solución].

| ID | Feature Assumption | Hipótesis | Criterio de éxito |
| --- | --- | --- | --- |
| H-01 | FA-01 | Por completar | Por completar |

##### 1.2.2.4. Lean UX Canvas

Incluir el Lean UX Canvas y explicar la relación entre problema, resultados del negocio, usuarios, beneficios, soluciones, hipótesis y experimentos.

### 1.3. Segmentos objetivo

Describir cada segmento, sus características demográficas, necesidades y contexto de uso de dispositivos móviles. Incorporar estadísticas y fuentes de sustento.

| ID | Segmento | Características | Necesidades | Contexto de uso | Sustento estadístico |
| --- | --- | --- | --- | --- | --- |
| SEG-01 | Por completar | Por completar | Por completar | Por completar | Por completar |

## Capítulo II: Requirements Development and Software Solution Design

### 2.1. Competidores

Identificar y describir al menos tres competidores directos o justificar la selección de competidores indirectos.

#### 2.1.1. Análisis competitivo

Explicar el objetivo del Competitive Analysis Landscape. Incluir nombre y logo de cada competidor, fuentes de consulta y análisis FODA para TerraTech y sus competidores.

| Dimensión | TerraTech | Competidor 1 | Competidor 2 | Competidor 3 |
| --- | --- | --- | --- | --- |
| Overview | Por completar | Por completar | Por completar | Por completar |
| Ventaja competitiva y valor ofrecido | Por completar | Por completar | Por completar | Por completar |
| Mercado objetivo | Por completar | Por completar | Por completar | Por completar |
| Estrategias de marketing | Por completar | Por completar | Por completar | Por completar |
| Productos y servicios | Por completar | Por completar | Por completar | Por completar |
| Precios y costos | Por completar | Por completar | Por completar | Por completar |
| Canales de distribución | Por completar | Por completar | Por completar | Por completar |
| Fortalezas | Por completar | Por completar | Por completar | Por completar |
| Debilidades | Por completar | Por completar | Por completar | Por completar |
| Oportunidades | Por completar | Por completar | Por completar | Por completar |
| Amenazas | Por completar | Por completar | Por completar | Por completar |

#### 2.1.2. Estrategias y tácticas frente a competidores

Describir las estrategias para afrontar las fortalezas de los competidores, aprovechar sus debilidades y responder al entorno de oportunidades y amenazas.

| Hallazgo | Estrategia | Táctica |
| --- | --- | --- |
| Por completar | Por completar | Por completar |

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

Preparar preguntas principales y complementarias por segmento. Recoger información demográfica, personalidad, habilidades, marcas e influencias, dispositivos, canales digitales, objetivos, frustraciones y antecedentes relevantes para construir los arquetipos.

| Segmento | Pregunta principal | Preguntas complementarias | Información buscada |
| --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar |

#### 2.2.2. Registro de entrevistas

Realizar de tres a cinco entrevistas por segmento. Consolidarlas en un video MP4 en el OneDrive indicado por el docente, con edición de tres a cinco minutos por entrevista e identificación del entrevistado, segmento y fecha.

| ID | Segmento | Nombres y apellidos | Edad | Distrito | Fecha | Tiempo de inicio | Video y captura |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ENT-001 | Por completar | Por completar | Por completar | Por completar | Por completar | Por completar | Por completar |

Incluir un resumen descriptivo por entrevista con las respuestas y características que servirán de base para los arquetipos.

#### 2.2.3. Análisis de entrevistas

Analizar las características objetivas y subjetivas por segmento mediante cuadros y porcentajes. Relacionar los resultados con los registros y resúmenes.

| Segmento | Variable | Valor observado | Frecuencia | Total de entrevistados | Porcentaje | Entrevistas relacionadas |
| --- | --- | --- | --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar | Por completar | Por completar | Por completar |

### 2.3. Needfinding

#### 2.3.1. User Personas

Elaborar en UXPressia una ficha por segmento. Incluir introducción, captura, enlace y explicación de su relación con las entrevistas y el análisis competitivo.

#### 2.3.2. User Task Matrix

Registrar tareas que los usuarios realizan para cumplir sus objetivos. Incluir columnas de frecuencia e importancia para cada User Persona y explicar las principales diferencias y coincidencias.

| Tarea | Persona 1: frecuencia | Persona 1: importancia |
| --- | --- | --- |
| Por completar | Por completar | Por completar |

Agregar las columnas correspondientes a las demás personas.

#### 2.3.3. User Journey Mapping

Elaborar en UXPressia un User Journey Map As-Is por persona, vinculado con su ficha. Describir el recorrido actual completo e incluir captura y explicación.

#### 2.3.4. Empathy Mapping

Elaborar en UXPressia un mapa por persona. Describir qué necesita hacer, dice, ve, hace, escucha, piensa y siente, incluyendo pains y gains. Presentar capturas y explicar el proceso.

#### 2.3.5. Big Picture EventStorming

Para comprender el flujo global del dominio agrícola y modelar holísticamente el ciclo de vida de la solución **TerraTech**, el equipo llevó a cabo una sesión colaborativa de **Big Picture EventStorming**. Esta dinámica permitió alinear el conocimiento agronómico y técnico, identificando eventos del negocio, disparadores, agregados, políticas de decisión, puntos de dolor (*hotspots*) y oportunidades estratégicas.

##### Participantes de la sesión
* **Facilitador y Arquitecto de Dominio:** Bendezú Navarro, Rúbens Fitzgerald
* **Product Owner & UX Lead:** NovaTech Team
* **Desarrolladores & Analistas de Negocio:** Equipo de Ingeniería de Software NovaTech

##### Artefacto Visual del Big Picture EventStorming

![Big Picture EventStorming](assets/images/strategic-ddd/big-picture-event-storming.svg)

##### Etapas del Proceso y Estructura de la Línea de Tiempo del Negocio

El modelado se estructuró a lo largo de 5 fases cronológicas e interconectadas:

1. **Fase 1: Onboarding y Registro de Parcelas**
   * **Commands:** `RegisterUser`, `RegisterParcel`.
   * **Domain Events:** `UserRegistered`, `ParcelCreated`.
   * **Aggregates:** `Parcel` (contiene ID, coordenadas geoespaciales GPS, área en hectáreas, tipo de cultivo y clasificación de suelo).
   * **Read Model:** `ParcelDashboardView` (visualización cartográfica de lotes y estado general en el móvil).
   * **Hotspot / Desafío:** *Precisión y Conectividad GPS en Campo:* En zonas rurales aisladas la cobertura de red y precisión satelital pueden ser intermitentes. Se definió soporte *Offline-First* con almacenamiento local Room y trazado manual de polígonos.

2. **Fase 2: Monitoreo y Telemetría Climática**
   * **Commands:** `FetchWeatherData`, `RecordSoilInspection`.
   * **Domain Events:** `WeatherDataSynchronized`, `SoilInspectionRecorded`.
   * **Aggregates:** `SoilInspection` (registro de humedad, pH, textura, fecha/hora y registro fotográfico).
   * **Read Model:** `SoilMoistureMapView` (mapa de calor y gráficos históricos de humedad del suelo).
   * **Políticas:** Disparo periódico automático de sincronización climática externa mediante coordenadas de parcela.

3. **Fase 3: Análisis y Diagnóstico Agronómico**
   * **Policies:** `OnInspectionOrWeatherUpdate` (evalúa balances hídricos y factores de riesgo biológico ante cambios bruscos de temperatura o humedad).
   * **Commands:** `GenerateCropReport`.
   * **Aggregates:** `CropHealthReport` (score de salud, riesgo de plagas/enfermedades, recomendación hídrica y de fertilización).
   * **Domain Events:** `CropReportGenerated`.
   * **Read Model:** `AgronomicSummaryView` (indicadores sintéticos y recomendaciones accionables para el agricultor).
   * **Hotspot:** *Diagnóstico Offline:* Capacidad de la app móvil de calcular recomendaciones preliminares mediante un motor local embebido cuando no hay acceso a internet.

4. **Fase 4: Alertas y Notificaciones Críticas**
   * **Policies:** `OnCriticalThresholdExceeded` (detecta temperaturas menores a 2°C para heladas inminentes o estrés hídrico severo prolongado).
   * **Commands:** `DispatchAlertNotification`, `AcknowledgeAlert`.
   * **Aggregates:** `AlertNotification` (nivel de criticidad, mensaje, fecha/hora de emisión y acuse de recibo).
   * **Domain Events:** `AlertDispatched` (enviado vía Firebase Cloud Messaging directamente al dispositivo Android).
   * **Read Model:** `ActiveAlertsInbox` (bandeja de notificaciones priorizadas).

5. **Fase 5: Comunidad y Transferencia de Conocimiento**
   * **Commands:** `CreateForumPost`, `SubmitAgronomistAdvice`.
   * **Aggregates:** `ForumPost` (autor, título, fotos de cultivos con anomalías, categoría agronómica, respuestas y votos).
   * **Domain Events:** `ForumPostPublished`, `AdviceAccepted`.
   * **Read Model:** `CommunityFeedView` (muro de consultas comunitarias y buenas prácticas).
   * **Oportunidad:** *Red de Especialistas Certificados:* Facilitar la conexión directa entre pequeños productores agrícolas y agrónomos colegiados para asesorías remotas rápidas.

#### 2.3.6. Ubiquitous Language

Definir términos del dominio en inglés, con equivalencia en español opcional y definición en español.

| Término | Definición |
| --- | --- |
| Por completar | Por completar |

### 2.4. Requirements specification

#### 2.4.1. User Stories

Identificar Epics y elaborar una ficha por User Story. Incorporar Technical Stories para capacidades sin interacción directa con usuarios y Spike Stories para investigación o pruebas de viabilidad.

| Story ID | User | Priority | Epic |
| --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar |

**Title:** Por completar.

**Description:** Como [rol], deseo [capacidad], para [beneficio].

**Acceptance Criteria:** redactar varios escenarios Given–When–Then, en presente y tercera persona, verificables y sin detalles de interfaz. Para APIs, utilizar el rol Developer y considerar escenarios request/response. Para spikes, especificar objetivo de investigación y resultados que permitan verificar su conclusión.

#### 2.4.2. Impact Mapping

Elaborar en UXPressia el mapa con varios Business Goals SMART, Actors/Personas, Impacts, Deliverables y User Stories. Incluir captura, enlace y explicación.

| Business Goal | Actor / Persona | Impact | Deliverable | User Story |
| --- | --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar | Por completar |

#### 2.4.3. Product Backlog

Priorizar por valor de negocio y estimar las historias. Considerar la landing page desde el primer sprint. Incluir captura y enlace público al backlog en la herramienta de gestión.

| Orden | User Story ID | Título | Story Points (1 / 2 / 3 / 5 / 8) | Sprint |
| --- | --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar | Por completar |

### 2.5. Strategic-Level Domain-Driven Design

El diseño estratégico de **Domain-Driven Design (DDD)** permite descomponer la complejidad del dominio de la agricultura de precisión en límites organizacionales y de software bien definidos (*Bounded Contexts*), garantizando una arquitectura desacoplada, mantenible y alineada con los objetivos del negocio agrícola.

#### 2.5.1. EventStorming

El modelado estratégico partió de la sesión de *Big Picture EventStorming*, refinando los eventos del negocio para identificar agrupaciones de conceptos cohesivos con su propio modelo de dominio y lenguaje ubicuo.

##### 2.5.1.1. Candidate Context Discovery

A partir de la afinidad de eventos, comandos y reglas de negocio, se descubrieron y clasificaron **5 Bounded Contexts estratégicos**:

| Bounded Context | Tipo de Dominio | Justificación Estratégica |
| --- | --- | --- |
| **Field & Parcel Management** | **Core Domain** | Ventaja competitiva principal: Representación geoespacial de lotes agrícolas, gestión de cultivos asignados y recolección de muestras de suelo en campo mediante la app móvil. |
| **Crop Analytics & Reporting** | **Core Domain** | Diferenciador crítico: Motor de diagnóstico agronómico que correlaciona datos de suelo y variables meteorológicas para emitir recomendaciones preventivas de fertilización y riesgo de plagas. |
| **Alerts & Notifications** | **Supporting Domain** | Soporte esencial: Monitoreo constante de umbrales climáticos (heladas inminentes $< 2^\circ\text{C}$, estrés hídrico) y despacho prioritario de notificaciones push móviles. |
| **Farmer Community & Collaboration** | **Supporting Domain** | Soporte de valor: Espacio colaborativo y foro técnico donde agricultores comparten dudas y reciben asistencia directa de ingenieros agrónomos. |
| **IAM & Security** | **Generic Domain** | Capacidad estándar genérica: Autenticación segura mediante tokens JWT, control de acceso basado en roles (Agricultor / Agrónomo) y gestión de perfiles. |

##### 2.5.1.2. Domain Message Flows Modeling

Para representar cómo colaboran los Bounded Contexts y los actores en los escenarios operativos clave, se aplicó la técnica de **Domain Storytelling**:

![Domain Storytelling](assets/images/strategic-ddd/domain-storytelling.svg)

**Narrativa del flujo principal de monitoreo preventivo:**
1. El **Agricultor** accede a la app móvil TerraTech y registra una nueva inspección de suelo (`RecordSoilInspection`) con parámetros de humedad, pH y fotografías tomadas en campo.
2. La app móvil almacena la inspección en la base de datos local **Room** (para garantizar operatividad offline) y la sincroniza con el backend mediante `POST /api/v1/inspections` en cuanto detecta conectividad.
3. El servicio de backend consulta las condiciones meteorológicas y el pronóstico de 7 días del servicio externo **OpenWeatherMap API** mediante las coordenadas GPS de la parcela.
4. Con los datos consolidados, el contexto **Crop Analytics & Reporting** procesa el balance hídrico y genera el reporte `CropHealthReport` evaluando el riesgo biológico y térmico.
5. Si los pronósticos indican una helada inminente o anomalía severa, se dispara la política `OnCriticalThresholdExceeded`, instruyendo al contexto **Alerts & Notifications** a emitir una notificación urgente.
6. El gateway **Firebase Cloud Messaging (FCM)** despacha la notificación push de alta prioridad que despierta el dispositivo móvil del agricultor alertándolo preventivamente.
7. Ante dudas específicas, el agricultor publica una consulta en la **Comunidad**, donde un **Ingeniero Agrónomo** revisa la telemetría asociada y responde técnicamente.

##### 2.5.1.3. Bounded Context Canvases

A continuación se presentan los Canvases estratégicos detallados para cada uno de los 5 Bounded Contexts:

###### Bounded Context Canvas 1: IAM & Security
* **Nombre:** IAM (Identity & Access Management)
* **Clasificación Estratégica:** Generic Domain
* **Propósito:** Proveer autenticación segura, emisión/validación de tokens JWT y autorización basada en roles (Agricultor, Ingeniero Agrónomo, Administrador).
* **Entradas (Inbound):** Comandos `RegisterUserAccount`, `AuthenticateUser`, `UpdateUserProfile`.
* **Salidas (Outbound):** Eventos `UserRegistered`, `UserAuthenticated`, `RoleAssigned`.
* **Lenguaje Ubicuo Local:** `UserAccount`, `Credential`, `Role`, `SessionToken`, `UserProfile`.
* **Reglas de Negocio e Invariantes:** Contraseñas cifradas con algoritmo BCrypt; tokens JWT con expiración definida de 24 horas; roles inmutables salvo autorización administrativa.
* **Dependencias:** Ninguna (Contexto base Upstream).

###### Bounded Context Canvas 2: Field & Parcel Management
* **Nombre:** Field & Parcel Management
* **Clasificación Estratégica:** Core Domain
* **Propósito:** Gestionar el ciclo de vida de los predios y lotes agrícolas, sus geometrías geoespaciales GPS, cultivos asignados e historial de inspecciones de suelo.
* **Entradas (Inbound):** Comandos `RegisterParcel`, `UpdateParcelBoundaries`, `RecordSoilInspection`.
* **Salidas (Outbound):** Eventos `ParcelCreated`, `ParcelUpdated`, `SoilInspectionRecorded`.
* **Lenguaje Ubicuo Local:** `Parcel`, `GeoPolygon`, `CropType`, `SoilInspection`, `MoistureLevel`, `SoilPH`.
* **Reglas de Negocio e Invariantes:** Una parcela debe poseer un polígono cerrado válido mayor a 0.01 hectáreas; las inspecciones de suelo requieren porcentaje de humedad entre 0% y 100% y pH entre 0 y 14.
* **Dependencias:** Consume identidades de IAM; alimenta de telemetría a Crop Analytics.

###### Bounded Context Canvas 3: Crop Analytics & Reporting
* **Nombre:** Crop Analytics & Reporting
* **Clasificación Estratégica:** Core Domain
* **Propósito:** Motor de diagnóstico agronómico que sintetiza telemetría de suelo y clima para generar diagnósticos de salud del cultivo y planes de riego/fertilización.
* **Entradas (Inbound):** Eventos `SoilInspectionRecorded`, `WeatherDataSynchronized`, comando `GenerateCropReport`.
* **Salidas (Outbound):** Eventos `CropReportGenerated`, `CriticalThresholdDetected`.
* **Lenguaje Ubicuo Local:** `CropHealthReport`, `HealthScore`, `PestRiskIndex`, `IrrigationRecommendation`, `AgronomicRule`.
* **Reglas de Negocio e Invariantes:** El `HealthScore` se normaliza en escala de 0 a 100; si el déficit hídrico supera el 40%, se emite recomendación prioritaria de riego.
* **Dependencias:** Depende de Field & Parcel Management (datos del lote) y de OpenWeatherMap API (clima externo).

###### Bounded Context Canvas 4: Alerts & Notifications
* **Nombre:** Alerts & Notifications
* **Clasificación Estratégica:** Supporting Domain
* **Propósito:** Monitorear umbrales agronómicos y climáticos de riesgo para despachar notificaciones push a los dispositivos móviles Android de los productores.
* **Entradas (Inbound):** Evento `CriticalThresholdDetected`, comando `DispatchAlertNotification`, comando `AcknowledgeAlert`.
* **Salidas (Outbound):** Evento `AlertDispatched`, `AlertAcknowledged`.
* **Lenguaje Ubicuo Local:** `AlertNotification`, `SeverityLevel` (INFO, WARNING, CRITICAL), `PushPayload`, `DeviceToken`, `AcknowledgmentStatus`.
* **Reglas de Negocio e Invariantes:** Las alertas de severidad `CRITICAL` deben despacharse inmediatamente con prioridad alta en FCM; reintentos automáticos si falla la conexión.
* **Dependencias:** Consume eventos de Crop Analytics y se integra con el servicio externo Firebase FCM.

###### Bounded Context Canvas 5: Farmer Community & Collaboration
* **Nombre:** Farmer Community & Collaboration
* **Clasificación Estratégica:** Supporting Domain
* **Propósito:** Facilitar la interacción comunitaria, resolución de consultas sobre plagas y difusión de buenas prácticas entre productores y agrónomos.
* **Entradas (Inbound):** Comandos `CreateForumPost`, `SubmitExpertAnswer`, `VoteAnswer`.
* **Salidas (Outbound):** Eventos `ForumPostPublished`, `ExpertAnswerSubmitted`, `AnswerMarkedAsAccepted`.
* **Lenguaje Ubicuo Local:** `ForumPost`, `AgronomistAdvice`, `PostCategory`, `UpvoteCount`, `ExpertBadge`.
* **Reglas de Negocio e Invariantes:** Solo usuarios con rol verificado de Ingeniero Agrónomo pueden otorgar respuestas catalogadas como `ExpertAdvice`; el autor del post es el único que puede marcar una respuesta como aceptada.
* **Dependencias:** Consume identidades de IAM; referencia códigos de parcela de forma desacoplada.

---

#### 2.5.2. Context Mapping

El **Context Map** define formalmente las relaciones de integración y gobernanza de datos entre los Bounded Contexts y los servicios externos:

![Strategic Context Map](assets/images/strategic-ddd/context-map.svg)

##### Patrones de Relación y Matriz de Integración

| Contexto Upstream (U) | Contexto Downstream (D) | Patrón DDD Adoptado | Justificación Técnica y de Diseño |
| --- | --- | --- | --- |
| **IAM & Security** | **Field & Parcel Management** | *Customer / Supplier* | IAM provee la identidad autenticada (`userId`) requerida para asignar propietarios a las parcelas agrícolas. |
| **IAM & Security** | **Farmer Community** | *Conformist* | La comunidad acepta directamente el modelo de identidad y perfil emitido por IAM sin transformaciones adicionales. |
| **Field & Parcel Management** | **Crop Analytics & Reporting** | *Customer / Supplier* | Analytics depende de los datos estructurales del predio e historial de inspecciones provistos por Parcel Management. |
| **OpenWeatherMap API** | **Crop Analytics & Reporting** | *Anti-Corruption Layer (ACL)* | La ACL aísla el modelo de dominio interno de TerraTech de las estructuras de datos propietarias y cambios de la API pública meteorológica. |
| **Crop Analytics & Reporting** | **Alerts & Notifications** | *Published Language / Events* | Analytics publica eventos de dominio asíncronos (`CriticalThresholdDetected`) que Notifications consume para enviar push alerts. |
| **Alerts & Notifications** | **Firebase Cloud Messaging** | *Anti-Corruption Layer (ACL)* | Adapter que traduce el agregado `AlertNotification` al payload específico de Firebase HTTP v1 API. |

---

#### 2.5.3. Software Architecture

La solución de software de TerraTech se modela mediante el enfoque **C4 Model**, estructurado en tres niveles de abstracción orientados a una aplicación móvil nativa Android con backend en la nube.

##### 2.5.3.1. Software Architecture Context Level Diagrams (C4 Nivel 1)

El diagrama de contexto define los límites del sistema TerraTech, sus usuarios clave y las integraciones con servicios externos de terceros:

![C4 Context Diagram](assets/images/strategic-ddd/c4-context.svg)

* **Actores Principales:**
  * **Agricultor / Productor Agrícola:** Interactúa con la app móvil para delimitar parcelas, registrar mediciones de suelo, recibir alertas tempranas de heladas y aplicar planes de fertilización.
  * **Ingeniero Agrónomo:** Analiza el estado fitosanitario de los cultivos y brinda soporte técnico a los agricultores a través de la comunidad.
* **Sistema TerraTech:** Plataforma integral que procesa datos de campo, correlaciona variables ambientales y genera diagnósticos preventivos.
* **Sistemas Externos SaaS:**
  * **OpenWeatherMap API:** Provee telemetría y pronósticos climáticos georreferenciados.
  * **Firebase Cloud Messaging (FCM):** Plataforma de mensajería push para notificación en tiempo real en dispositivos móviles.

##### 2.5.3.2. Software Architecture Container Level Diagrams (C4 Nivel 2)

El diagrama de contenedores detalla las aplicaciones ejecutables, almacenes de datos y protocolos de comunicación que componen la solución:

![C4 Container Diagram](assets/images/strategic-ddd/c4-container.svg)

* **Contenedores de la Solución:**
  1. **Android Mobile Application (Kotlin / Jetpack Compose):** Aplicación nativa para smartphones Android. Emplea arquitectura *MVVM + Clean Architecture*, StateFlow para reactividad, inyección de dependencias con Hilt/Koin y cliente Retrofit para comunicación HTTPS con el backend.
  2. **Local SQLite / Room Database:** Base de datos embebida en el dispositivo móvil Android. Almacena en caché local las parcelas, reportes e inspecciones pendientes de sincronización para habilitar operatividad continua en zonas rurales sin cobertura de internet (*Offline-First*).
  3. **Web Landing Page (HTML5 / CSS3 / JavaScript / Vue):** Sitio web institucional responsivo optimizado para SEO, presentación comercial y descarga del archivo APK de la aplicación móvil.
  4. **Backend REST API (Java 21 / Spring Boot 3):** API monolítica modular organizada por capas DDD (Domain, Application, Interface, Infrastructure). Expone endpoints REST documentados bajo estándar OpenAPI 3.0 protegidos con Spring Security y JWT.
  5. **Relational Database (PostgreSQL 16):** Base de datos relacional centralizada que persiste la información estructurada de usuarios, parcelas, reportes, alertas y posts de la comunidad.

##### 2.5.3.3. Software Architecture Deployment Diagrams (C4 Nivel 3 / Despliegue)

El diagrama de despliegue representa la distribución de los artefactos de software en los entornos de hardware físico y cloud, detallando protocolos de red y seguridad:

![C4 Deployment Diagram](assets/images/strategic-ddd/c4-deployment.svg)

* **Nodos de Infraestructura y Despliegue:**
  * **Nodo Cliente — Smartphone Android:** Dispositivo móvil con sistema operativo Android 11.0 o superior (API 30+). Ejecuta el paquete binario de la app (`TerraTech.apk` / `.aab`), con drivers nativos de geolocalización (`FusedLocationProviderClient`), cámara (`CameraX`), almacenamiento SQLite Room y servicio receptor en segundo plano (`FirebaseMessagingService`).
  * **Nodo Cloud — Amazon Web Services / Google Cloud Platform:**
    * **Contenedor Docker (Spring Boot REST API):** Instancia Linux de alto rendimiento ejecutando el contenedor con OpenJDK 21. Configurado con proxy inverso HTTPS/TLS 1.3 en puerto seguro 443, tareas programadas (`@Scheduled`) para cálculo recurrente de heladas y pool de conexiones HikariCP.
    * **Instancia de Base de Datos Administrada (Cloud SQL / AWS RDS PostgreSQL 16):** Instancia gestionada en red privada VPC con almacenamiento persistente SSD NVMe, cifrado en reposo AES-256 y respaldos automatizados.
  * **Nodo SaaS Externo:** Servidores de OpenWeatherMap y la infraestructura de Google Play Services / Firebase para la entrega garantizada de notificaciones push móviles.

### 2.6. Tactical-Level Domain-Driven Design

Repetir la siguiente subsección por cada Bounded Context identificado, reemplazando «x» por el número correspondiente.

#### 2.6.x. Bounded Context: [Nombre por completar]

##### 2.6.x.1. Domain Layer

Explicar las clases del dominio y las reglas de negocio: Entities, Value Objects, Aggregates, Factories, Domain Services e interfaces de Repositories, según corresponda.

| Clase o interfaz | Categoría | Propósito | Atributos | Métodos | Relaciones |
| --- | --- | --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar | Por completar | Por completar |

##### 2.6.x.2. Interface Layer

Describir Controllers, Consumers y demás clases de presentación o interfaz, con atributos, métodos y relaciones.

##### 2.6.x.3. Application Layer

Describir las clases que coordinan los flujos del negocio, incluyendo Command Handlers y Event Handlers que correspondan.

##### 2.6.x.4. Infrastructure Layer

Describir las clases de persistencia, repositorios y acceso a servicios externos, bases de datos o mensajería.

##### 2.6.x.5. Bounded Context Software Architecture Component Level Diagrams

Presentar y explicar C4 de componentes para los contenedores del contexto, con responsabilidades, interacciones y tecnologías.

##### 2.6.x.6. Bounded Context Software Architecture Code Level Diagrams

###### 2.6.x.6.1. Bounded Context Domain Layer Class Diagrams

Incluir UML de clases, interfaces y enumeraciones del dominio, con atributos, métodos, visibilidad, relaciones, dirección y multiplicidades. Utilizar LucidChart o PlantUML DSL.

###### 2.6.x.6.2. Bounded Context Database Design Diagram

Presentar y explicar las estructuras de persistencia por producto: tablas, columnas, claves, restricciones y relaciones cuando corresponda. Utilizar LucidChart o Vertabelo.

## Capítulo III: Solution UI/UX Design

### 3.1. Product design

#### 3.1.1. Style Guidelines

##### 3.1.1.1. General Style Guidelines

Completar: branding, tipografía, colores, espaciado, tono y sustento de decisiones inclusivas.

#### 3.1.2. Information Architecture

##### 3.1.2.1. Organization Systems

Completar: organización y categorización del contenido.

##### 3.1.2.2. Labelling Systems

Completar: etiquetas consistentes y comprensibles.

##### 3.1.2.3. SEO Tags and Meta Tags

Completar: title, description, keywords, author y elementos ASO de la aplicación.

##### 3.1.2.4. Searching Systems

Completar: búsquedas, filtros y resultados.

##### 3.1.2.5. Navigation Systems

Completar: navegación de landing y aplicaciones.

#### 3.1.3. Landing Page UI Design

##### 3.1.3.1. Landing Page Wireframe

Completar: desktop y mobile browser, capturas y explicación.

##### 3.1.3.2. Landing Page Mock-up

Completar: ambas resoluciones en Figma, coherencia visual e inclusividad.

#### 3.1.4. Mobile Applications UX/UI Design

##### 3.1.4.1. Mobile Applications Wireframes

Completar: pantallas móviles en Figma.

##### 3.1.4.2. Mobile Applications Wireflow Diagrams

Completar: uno por user goal en LucidChart u Overflow, con explicación.

##### 3.1.4.3. Mobile Applications Mock-ups

Completar: vistas finales en Figma.

##### 3.1.4.4. Mobile Applications User Flow Diagrams

Completar: happy path y rutas alternativas por objetivo, consistentes con wireflows.

##### 3.1.4.5. Mobile Applications Prototyping

Completar: prototipos interactivos en Figma, evidencia en video, captura y enlace.

## Capítulo IV: Product Implementation & Validation

### 4.1. Software Configuration Management

#### 4.1.1. Software Development Environment Configuration

Especificar productos, versiones, propósito y enlaces de las herramientas de gestión, requisitos, diseño, desarrollo, pruebas, despliegue y documentación.

#### 4.1.2. Source Code Management

Incluir repositorios por producto y explicar GitFlow, ramas main y develop, convenciones para feature, release y hotfix, Conventional Commits y Semantic Versioning.

#### 4.1.3. Source Code Style Guide & Conventions

Definir convenciones por lenguaje, nomenclatura en inglés y referencias utilizadas.

#### 4.1.4. Software Deployment Configuration

Describir pasos reproducibles para desplegar cada producto e incluir el diagrama de despliegue C4.

### 4.2. Landing Page & Mobile Application Implementation

Desarrollar las siguientes secciones para Sprint 1 en TB1, Sprint 2 en AV2 y Sprint 3 en TB2. Reemplazar «n» por el sprint y «x» por su posición.

#### 4.2.x. Sprint n

##### 4.2.x.1. Sprint Planning n

| Campo | Información |
| --- | --- |
| Fecha y hora | Por completar |
| Lugar | Por completar |
| Prepared By | Por completar |
| Attendees | Por completar |
| Sprint anterior: Review Summary | Por completar cuando corresponda |
| Sprint anterior: Retrospective Summary | Por completar cuando corresponda |
| Sprint Goal | Por completar: resultado, impacto, usuarios y métrica |
| Sprint Velocity | Por completar |
| Sum of Story Points | Por completar |

##### 4.2.x.2. Aspect Leaders and Collaborators

Incluir tabla de integrantes, usuarios GitHub y roles Leader/Collaborator por aspecto del sprint.

##### 4.2.x.3. Sprint Backlog n

Incluir objetivo, captura y enlace público del tablero.

| Story ID | Story Title | Task ID | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar | Por completar | Por completar | Por completar | To-do |

Utilizar estados To-do, In-Process, To-Review y Done según el avance.

##### 4.2.x.4. Development Evidence for Sprint Review

Describir los avances e incluir una tabla de repositorio, rama, Commit ID, Commit Message, Commit Message Body y fecha.

##### 4.2.x.5. Testing Suite Evidence for Sprint Review

Presentar pruebas unitarias, de integración y de aceptación, su relación con historias y clases, archivos Gherkin cuando corresponda, repositorios y commits de pruebas.

##### 4.2.x.6. Execution Evidence for Sprint Review

Describir lo alcanzado, incluir capturas de las vistas implementadas y enlace al video de ejecución y navegación.

##### 4.2.x.7. Services Documentation Evidence for Sprint Review

Documentar endpoints con OpenAPI: verbo HTTP, ruta, parámetros, respuestas, ejemplos, enlaces, capturas y commits relacionados.

##### 4.2.x.8. Software Deployment Evidence for Sprint Review

Describir pasos de despliegue, configuración de recursos, capturas y enlaces de los productos publicados.

##### 4.2.x.9. Team Collaboration Insights during Sprint

Presentar capturas y análisis de contribuciones en GitHub, explicando los aportes de los integrantes por producto.

### 4.3. Validation Interviews

#### 4.3.1. Diseño de Entrevistas

Definir tareas y user flows para validar la landing page y las aplicaciones con cada segmento.

#### 4.3.2. Registro de Entrevistas

Registrar de tres a cinco entrevistas por segmento: nombres, apellidos, edad, distrito, captura, enlace al video, tiempo de inicio, duración y resumen de apreciaciones.

#### 4.3.3. Evaluaciones según heurísticas

Aplicar el formato del Anexo E del enunciado. Incluir tareas evaluadas, tabla de problemas, severidad de 1 a 4, heurística o principio vulnerado, descripción, captura y recomendación.

## Conclusiones

### Conclusiones y recomendaciones

Completar por entrega las conclusiones sobre la problemática, supuestos, hipótesis y criterios de éxito, relacionándolos con los resultados obtenidos. Incluir recomendaciones para los siguientes pasos del producto.

### Video App Validation

Documentar la evaluación de la aplicación con usuarios, distribución mediante Firebase App Distribution o servicio similar y evaluación heurística. Incluir captura, duración y enlace al video.

### Video About-the-Product

Incluir un video de uno a dos minutos sobre el modelo de negocio, características y beneficios de TerraTech, con demostración y testimonios de usuarios. Incorporar captura, duración y enlaces a OneDrive y YouTube, y publicarlo en la landing page. Presentar primera versión en AV2 y versión final en TB2.

### Video About-the-Team

Presentar el proceso de trabajo, escenas de sesiones del equipo, retrospectiva y testimonios individuales sobre actividades, aprendizaje y logro del Student Outcome. Incluir resumen, pauta de tiempos, captura y enlaces de publicación. Presentar primera versión en AV2 y versión final en TB2.

## Glosario

Definir los términos técnicos, abreviaturas y acrónimos utilizados en el informe.

| Término | Definición |
| --- | --- |
| Por completar | Por completar |

## Bibliografía

Registrar las referencias en APA 7 y citarlas en las secciones correspondientes.

### Dominio de negocio

Incluir fuentes sobre problemática agrícola, segmentos, estadísticas y contexto del mercado.

### Métodos y técnicas de ingeniería de software

Incluir las fuentes utilizadas para Lean UX, DDD, arquitectura, entrevistas, requisitos y demás técnicas aplicadas.

### Lenguajes, frameworks y herramientas

Incluir las fuentes de las tecnologías y herramientas seleccionadas para TerraTech.

Para el informe final, incorporar al menos cuatro papers Q1 o Q2 con no más de dos años de antigüedad: dos del dominio del problema y dos sobre técnicas de desarrollo móvil aplicadas en el proyecto.

| Referencia APA 7 | Categoría | Año | Cuartil y fuente | Aplicación en el proyecto |
| --- | --- | --- | --- | --- |
| Por completar | Por completar | Por completar | Por completar | Por completar |

## Anexos

### Anexo A. Videos de Exposiciones

| Entrega | Enlace al video | Duración |
| --- | --- | --- |
| AV1 | Por completar | Máximo 15 minutos |
| TB1 | Por completar | Máximo 15 minutos |
| AV2 | Por completar | Máximo 15 minutos |
| TB2 | Por completar | Máximo 15 minutos |

Incluir captura representativa y enlace privado del video por entrega. La exposición debe presentar a los integrantes ante cámara y mostrar las diapositivas y artefactos junto con la explicación.

### Anexo B. Artefactos complementarios

Incorporar tablas, gráficos y otros elementos cuya extensión amerite ubicarlos como anexos. Identificar cada artefacto y relacionarlo con su sección del informe.

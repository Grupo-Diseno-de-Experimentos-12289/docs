<p align="center">
    <img src="assets/images/upclogo.png" alt="upc-logo" width="250px" height="250px"/>
</p>

<h1 align="center">
    Universidad Peruana de Ciencias Aplicadas
</h1>

<h3 align="center">
    Carrera: Ingeniería de Software
    <br> <br>
    Curso: SI0732 - Diseño de Experimentos de Ingeniería de Software
    <br> <br>
    Sección: 12289
    <br> <br>
    Profesor: Juan Antonio Flores Moroco
    <br> <br>
    Ciclo: 2026-01 
    <br> <br>
    Informe de Trabajo Parcial
    <br> <br>
    Startup: Pandora
    <br> <br>
    Producto: TravelMatch  
</h3>

<div align="center">

| <div style="width:500px">Alumno</div> | <div style="width:200px">Código</div> |
|:-------------------------------------:|:-------------------------------------:|
|        Tenorio Medina, Piero Francesco        |              u202318731               |

</div>

<div align="center"> Mayo 2026 </div>

<hr>

## Registro de Versiones del Informe

| Versión | Fecha | <div style="width:250px">Autor(es) </div> | <div align="center" style="width:400px">Descripción de la modificación</div> |
|:-------:|:-----:|:-----------------------------------------:|-------------------------------------------------------------|
TP | | |

<hr>

## Tabla de Contenidos

[Registro de Versiones del Informe] 

[Tabla de Contenidos](#tabla-de-contenidos)

[Student Outcome](#tabla-de-contenidos)

[Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de Integrantes del Equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivos](#13-segmentos-objetivos)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Product Backlog](#33-product-backlog)
  - [3.4. Impact Mapping](#34-impact-mapping)  

[Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
    - [4.4.1. Mobile Applications Wireframes.](#441-mobile-applications-wireframes)
    - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
    - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
- [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
    - [4.5.1. Android Mobile Applications Prototyping](#451-mobile-applications-prototyping)
    - [4.5.2. IOS Mobile Mobile Applications Prototyping](#452-mobile-applications-prototyping)
- [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
    - [4.6.1. Web Applications Wireframes.](#461-web-applications-wireframes)
    - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
    - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
    - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
- [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
- [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagrams](#481-software-architecture-context-diagrams)
    - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
- [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams](#491-class-diagrams)
    - [4.9.2. Class Dictionary](#492-class-dictionary)
- [4.10. Database Design](#410-database-design)
    - [4.10.1. Database Diagram](#4101-database-diagram)

[Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Product Implementation & Development](#52-software-implementation-development)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlog)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio-saas)
    - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
    - [5.2.6. Implemented RESTful API and/or Serveless Backend Evidence](#526-implemented-restful-api-serveless-backend-evidence)
    - [5.2.7. RESTful API documentation](#527-restful-api-documentation)
    - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
- [5.3. Video About-the-Product](#53-video-about-the-product)

[Capitulo VI: Product Verification & Validation ](#capitulo-vi-product-verification--validation)
- [6.1. Testing Suites & Validation](#61-testing-suites--validation)
    - [6.1.1. Core Entities Unit Test](#611-core-entities-unit-test)
    - [6.1.2. Core Integration Test](#612-core-integration-test)
    - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
    - [6.1.4. Core System Test](#614-core-system-test)

[Capitulo VII: DevOps Practices](#capitulo-vii-devops-practices)
- [7.1. Continuous Integration](#71-continuous-integration)
    - [7.1.1. Tools and Practices](#711-tools-and-practices)
    - [7.1.2. Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
- [7.2. Continuous Integration](#72-continuous-integration)
    - [7.2.1. Tools and Practices](#721-tools-and-practices)
    - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
- [7.3. Continuous deployment](#73-continuous-deployment)
    - [7.3.1. Tools and Practices](#731-tools-and-practices)
    - [7.3.2. Production Deployment Pipeline Components](#732-production-deployemnte-pipeline-component)

[Conclusiones](#conclusiones)
  - [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)

[Bibliografía](#bibliografía)

[Anexos](#anexos)


<hr>

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 4**

Criterio:  La capacidad de reconocer responsabilidades éticas y profesionales en 
situaciones de ingeniería y hacer juicios informados, que deben considerar el 
impacto de las soluciones de ingeniería en contextos globales, económicos, 
ambientales y sociales. 

| <div style="width:100px">Criterio específico</div> | <div align="center" style="width:250px">Acciones Realizadas</div> | <div align="center" style="width:250px">Conclusiones</div> |
|:-------------------:|-------------------|------------|
|Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software |a|a |
|Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales | a |a| 

<hr>

## Capítulo I: Introducción 

### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup
Nuestra startup, TravelMatch, surge a partir de una problemática latente en el sector turístico: la fragmentación de la oferta de actividades y experiencias locales, lo que dificulta a los turistas planificar sus viajes de forma personalizada, segura y eficiente. Hoy en día, quienes viajan deben navegar por múltiples sitios, redes sociales y foros para encontrar excursiones o experiencias, muchas veces enfrentándose a información incompleta, desactualizada o poco confiable.

Por otro lado, las agencias de turismo locales carecen de canales digitales eficientes para visibilizar sus servicios, competir con grandes operadores y gestionar sus reservas en tiempo real.

Ante este contexto, proponemos una plataforma web de turismo y actividades personalizadas, que actúe como puente entre turistas y agencias locales. Nuestra solución permite a los viajeros explorar y reservar experiencias según destino, tipo de actividad y presupuesto, mientras que ofrece a las agencias una interfaz intuitiva para gestionar su catálogo y atender reservas con agilidad.

La propuesta de valor se centra en:

- Para los turistas: una experiencia de búsqueda fluida, segura y adaptada a sus preferencias.
- Para las agencias: visibilidad digital, herramientas de gestión y potencial de crecimiento.

El modelo de negocio se sustentará en:

- Comisiones por cada reserva gestionada a través de la plataforma.

- Planes premium para agencias que deseen destacar sus servicios y acceder a beneficios adicionales.

| Misión | Visión |
|:-------:|:-------:|
|Ofrecer una plataforma digital intuitiva y confiable que conecte a turistas con experiencias auténticas, promoviendo el turismo local y facilitando la digitalización de pequeñas y medianas agencias.|Convertirnos en la plataforma líder en experiencias turísticas personalizadas en Peru, siendo reconocidos por nuestra innovación, impacto social y compromiso con el desarrollo del turismo sostenible.|

#### 1.1.2. Perfiles de integrantes del equipo

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática
En los últimos años, el sector turístico ha experimentado una transformación significativa, impulsada principalmente por la digitalización y los cambios en las preferencias de los viajeros. De acuerdo con un estudio realizado por Google, el interés por el término 'viajar' en Perú registró un incremento superior al 33% durante el año 2022. Adicionalmente, según un informe del Ministerio de Comercio Exterior y Turismo (Mincetur), la llegada de turistas internacionales al país experimentó un aumento del 39,2% entre los meses de enero y agosto de 2024.

A pesar de este creciente interés, los turistas enfrentan desafíos al planificar sus itinerarios, especialmente en lo que respecta a la reserva de actividades y experiencias locales. La información dispersa, la falta de plataformas centralizadas y la escasa presencia digital de muchas agencias locales dificultan la personalización y seguridad en la planificación de viajes.

Paralelamente, el sector de agencias de viajes en Perú enfrenta problemas de informalidad. En 2022, el Ministerio de Comercio Exterior y Turismo (Mincetur) clausuró varias agencias en Lima por operar sin licencia y sin personal calificado . Esta situación no solo afecta la confianza de los turistas, sino que también limita el desarrollo sostenible del turismo local.

Por consiguiente, con el propósito de obtener una comprensión más precisa de las necesidades de nuestros usuarios, hemos llevado a cabo un estudio de sus antecedentes históricos y la problemática en cuestión utilizando la metodología de las 5W y 2H. 

**Análisis 5W2H**

| **Pregunta** | **Respuesta** |
|:-----:|:-----:|
|**What (¿Qué?)** <br> ¿Cuál es el problema?|Existe una desconexión significativa entre los turistas y las agencias de turismo locales, dificultando la planificación y reserva de actividades auténticas y seguras.|
|**When (¿Cuándo?)** <br> ¿Cuándo sucede el problema?|Este problema se ha intensificado en los últimos años, especialmente tras la pandemia de COVID-19, que obligó a muchas agencias a cerrar o reducir sus operaciones, y con el aumento del interés en viajes nacionales e internacionales.|
|**Where (¿Dónde?)** <br> ¿Dónde se presenta el problema de negocio?|Principalmente en Perú, donde destinos turísticos populares como Cusco, Lima y Arequipa presentan una alta demanda, pero también una oferta fragmentada y, en ocasiones, informal.|
|**Who (¿Quién?)** <br> ¿Quiénes están involucrados?|Turistas nacionales e internacionales que buscan experiencias locales auténticas, y agencias de turismo locales que carecen de herramientas digitales para promocionar y gestionar sus servicios.|
|**Why (¿Por qué?)** <br> ¿Por qué se origina el problema?|La falta de plataformas digitales centralizadas, la escasa presencia en línea de muchas agencias locales y la informalidad en el sector impiden a los viajeros acceder fácilmente a experiencias personalizadas y confiables.|
|**How (¿Cómo?)** <br> ¿Cómo afecta este problema a las personas involucradas?|Los turistas enfrentan dificultades para encontrar opciones seguras, personalizadas y verificadas, lo que puede afectar negativamente su experiencia de viaje. Por otro lado, las agencias locales pierden oportunidades de negocio, visibilidad y competitividad en un mercado cada vez más digitalizado.|
|**How much (¿Cuánto?)** <br> ¿Cuánto impacto genera el problema en la sociedad?|El impacto es significativo, ya que limita el desarrollo del sector turístico formal, fomenta la informalidad y la desconfianza, y reduce el potencial económico de comunidades locales que dependen del turismo para su sustento. También frena la innovación y la digitalización del ecosistema turístico nacional.|

#### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
Actualmente, los turistas enfrentan dificultades para encontrar opciones de actividades turísticas que se alineen con sus intereses y necesidades específicas. Esta falta de acceso a información clara, organizada y relevante limita su capacidad de tomar decisiones informadas.

Por otro lado, muchas agencias de viaje locales, a pesar de ser formales, tienen problemas para obtener visibilidad en un mercado donde predomina la oferta informal difundida principalmente a través de redes sociales y plataformas no reguladas. Esta situación reduce su competitividad, afecta su sostenibilidad y contribuye a la desconfianza general en los servicios turísticos disponibles.

Esta desconexión entre turistas y agencias está afectando negativamente la confianza de los usuarios y el desarrollo del sector turístico formal en Perú.

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

1. Creemos que nuestros clientes necesitan encontrar y reservar experiencias turísticas personalizadas de forma confiable y eficiente.
2. Estas necesidades se resuelven con una plataforma web que centralice ofertas de actividades de agencias verificadas, con filtros por interés, ubicación y presupuesto.
3.	Nuestros clientes iniciales serán turistas nacionales y extranjeros que visitan Perú, así como agencias de turismo formalmente constituidas que buscan digitalizar sus servicios.
4.  El valor más importante de lo que el cliente requiere de nuestro servicio es una experiencia de viaje personalizada, segura y sin complicaciones.
5.	El cliente puede tener los siguientes beneficios adicionales: acceso a reseñas de otros usuarios, itinerarios organizados, descuentos exclusivos, y soporte digital durante el viaje.
6.	Vamos a adquirir clientes mediante estrategias de marketing digital (SEO, redes sociales, influencers de viajes), alianzas con agencias y posicionamiento en buscadores de experiencias.
7.	Haremos dinero a través de comisiones por reservas realizadas a través de la plataforma y planes premium para agencias.
8.	Nuestra competencia principal serán plataformas internacionales como Booking, Airbnb Experiences y la oferta informal en redes sociales.
9.	Los venceremos ya que nuestra plataforma tiene un enfoque local, curaduría de experiencias auténticas, alianza con agencias formales, y una interfaz intuitiva con filtros relevantes.
10.	Nuestro mayor riesgo es la baja adopción por parte de agencias o la falta de confianza de los usuarios en nuevas plataformas.
11.	Resolveremos esto mediante estrategias de onboarding amigables, incentivos iniciales, verificación pública de agencias y testimonios visibles de clientes satisfechos.
12. Qué otras suposiciones tenemos que, si resultan falsas, harán que nuestro negocio/proyecto fracase?
    - Que los turistas están dispuestos a reservar experiencias turísticas por adelantado desde una plataforma digital.
    - Que las agencias formales ven valor en integrarse a un sistema centralizado y están dispuestas a adaptarse a su uso.

**User Assumptions**

1.	¿Quién será nuestro usuario? 
    - Turistas nacionales y extranjeros con acceso a internet, con intención de explorar nuevas experiencias en sus destinos.
    - Representantes de agencias de turismo interesadas en aumentar su visibilidad y reservas.
2.	¿Dónde encaja nuestro producto en su vida?
    - En la etapa de planificación de viaje, al buscar actividades que enriquezcan su experiencia.
    - En el caso de agencias, como parte de su canal de ventas y atención al cliente.
3.	¿Qué problemas resuelve nuestro producto?
    - Dificultad para encontrar experiencias confiables, personalizadas y seguras.
    - Desorganización de itinerarios.
    - Limitada presencia digital de agencias locales confiables.
4.	¿Cómo y Cuándo es usado nuestro producto?
    - Antes del viaje (exploración y reservas) y durante el viaje (gestión de itinerarios y asistencia).
    - En dispositivos móviles y de escritorio, principalmente mediante el navegador web.
5.	¿Qué características son importantes?
	- Filtros de búsqueda por intereses, ubicación, precio, reseñas.
    - Perfil y catálogo de agencias.
    - Organización del itinerario.
    - Pago seguro y notificaciones.
6.  ¿Cómo luce y se comporta nuestro producto?
    - Con una interfaz limpia, intuitiva y confiable, accesible para distintos niveles de experiencia tecnológica.
    - Rápida carga, navegación fluida, diseño adaptado a dispositivos móviles.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que**, si ofrecemos a los turistas una plataforma donde puedan explorar actividades segmentadas por tipo de experiencia, destino, presupuesto y duración, entonces podrán tomar decisiones más informadas, mejorando su experiencia de viaje. **Sabremos que** hemos logrado este resultado **cuando** observemos un incremento sostenido en la cantidad de reservas exitosas y una tasa alta de satisfacción del usuario (medida por reseñas y feedback post-actividad).

- **Creemos que**, al proporcionar a las agencias una interfaz administrativa sencilla para gestionar su catálogo, recibir notificaciones de reservas y analizar métricas básicas, aumentará su participación activa y la disponibilidad de oferta formal. **Sabremos que** esta hipótesis es válida **cuando** se registre un incremento progresivo en el número de agencias registradas y publicaciones activas.

- **Creemos que**, si promovemos exclusivamente agencias registradas y verificadas (según regulaciones del MINCETUR), entonces generaremos mayor confianza en el usuario final y fomentaremos la formalización del sector. **Sabremos que** esta hipótesis se confirma **cuando** veamos un crecimiento sostenido en la base de usuarios activos y una reducción en las quejas relacionadas a malas experiencias con proveedores.

- **Creemos que**, si integramos herramientas de personalización (como recomendaciones según el historial o intereses declarados), entonces los usuarios encontrarán actividades más alineadas a sus expectativas. **Sabremos que** esto es cierto **cuando** aumente el tiempo de navegación en la plataforma y la tasa de conversión de visitas en reservas.

#### 1.2.2.4. Lean UX Canvas
<p align="center">
    <img src="assets/LeanUX_Canvas.jpg" alt="lean-ux-canvas"/>
</p>

### 1.3. Segmentos objetivo
Los siguientes segmentos clave permiten establecer una base sólida para el lanzamiento de la aplicación.
Su elección busca facilitar la conexión entre turistas y agencias, y sentar las bases para el crecimiento
del turismo personalizado en la plataforma.

- **Segmento objetivo 1: Agencias de turismo locales**

| _Aspectos demográficos_ | _Aspectos geográficos_ | _Aspectos psicográficos_ |
|-------------------------|------------------------|--------------------------|
| Sexo: masculino y femenino <br> Edades: entre 25-60 años <br> Nivel socioeconómico: clases B y C (media-alta y media) | Nacionalidad: Peruana <br> Zona geográfica: Urbana y zonas turísticas <br> Departamento: Diversas regiones del Perú, especialmente Lima, Cusco, Arequipa, Ica, Puno y Madre de Dios | Necesidad de expandir su presencia digital y aumentar su cartera de clientes <br> Interesadas en herramientas que automaticen reservas y muestren su oferta de forma atractiva. <br> Valoran plataformas que reduzcan su carga operativa, sean fáciles de usar y mejoren su competitividad frente a grandes operadores turísticos. |


- **Segmento objetivo 2: Turistas nacionales e internacionales**

| _Aspectos demográficos_ | _Aspectos geográficos_ | _Aspectos psicográficos_ |
|-------------------------|------------------------|--------------------------|
| - Sexo: masculino y femenino <br> - Edades: entre 18-65 años <br> - Nivel socioeconómico: clases A, B y C (alta, media-alta y media) | - Nacionalidad: Peruana y extranjera <br> - Zona geográfica: Urbana (para salidas) y destinos turísticos del Perú <br> - Departamento: Origen en Lima, Cusco, Arequipa u otros, con desplazamiento hacia zonas de interés turístico | - Buscan experiencias personalizadas, prácticas y seguras durante sus viajes <br> - Valoran la facilidad de comparar, filtrar y reservar actividades desde una sola plataforma <br> - Dispuestos a pagar por experiencias únicas y auténticas, adaptadas a sus intereses y presupuesto |

- **Segmento objetivo 3: Viajeros por trabajo (Turismo corporativo)**

| _Aspectos demográficos_ | _Aspectos geográficos_ | _Aspectos psicográficos_ |
|-------------------------|------------------------|--------------------------|
| - Sexo: masculino y femenino <br> - Edades: entre 25-55 años <br> - Nivel socioeconómico: clases A y B (alta y media-alta) | - Nacionalidad: Peruana y extranjera <br> - Zona geográfica: Urbana (ciudades principales con movimiento empresarial) <br> - Departamento: Principalmente Lima Metropolitana, Arequipa, Trujillo, Cusco | - Buscan aprovechar su tiempo libre durante viajes laborales para conocer la ciudad o relajarse <br> - Valoran la eficiencia, rapidez y calidad del servicio al reservar actividades de corta duración <br> - Interesados en experiencias bien organizadas, con horarios compatibles con su agenda de trabajo y disponibles cerca de su ubicación |

<hr>


## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores
#### 2.1.1. Análisis competitivo
<table><tr><th colspan="6" valign="top"><a name="_dns5lxqlpwhz"></a>Competitive Analysis Landscape </th></tr>
<tr><td colspan="2" rowspan="2" valign="top"><p></p><p>¿Por qué llevar a cabo este análisis?</p></td><td colspan="4" rowspan="2" valign="top"><p>El objetivo principal de realizar este análisis de la competencia es poder identificar las fortalezas, debilidades, oportunidades y amenazas de la propia empresa en comparación con los principales competidores del mercado.</p><p>Esto nos permitirá tomar decisiones informadas sobre la mejor manera de posicionarnos, diferenciarnos y aprovechar las oportunidades que el mercado nos ofrece.</p></td></tr>
<tr></tr>
</table>

<table><tr>
    <th colspan="2" valign="top"></th>
    <th valign="top">
      <p>TravelMatch</p>
      <img src="assets/logos/TravelMatchLogo.png" alt="Logo de TravelMatch" width="100">
    </th>
    <th valign="top">
      <p>GetYourGuide</p>
      <img src="assets/logos/GetLogo.PNG" alt="Logo de GetYourGuide" width="100">
    </th>
    <th valign="top">
      <p>Viator</p>
      <img src="assets/logos/ViatorLogo.PNG" alt="Logo de Viator" width="100">
    </th>
    <th valign="top">
      <p>Klook</p>
      <img src="assets/logos/KlookLogo.PNG" alt="Logo de Klook" width="100">
    </th>
  </tr>
<tr><td rowspan="2" valign="top"><p></p><p>Perfil</p></td><td valign="top">Overview</td><td valign="top">Es una plataforma web que conecta a turistas con agencias para reservar actividades personalizadas según destino, experiencia y presupuesto. Las agencias gestionan su catálogo y reservas en tiempo real. El modelo de negocio incluye comisiones y suscripciones premium.</td><td valign="top">Es una plataforma que permite a los viajeros reservar tours y actividades en todo el mundo. Ofrece experiencias filtradas por destino, precio y tipo, y conecta a turistas con proveedores locales. Utiliza un modelo de comisión por reserva y servicios premium para agencias.. </td><td valign="top">Es una plataforma respaldada por TripAdvisor que ofrece reservas de actividades turísticas personalizadas. Permite a los usuarios buscar experiencias por ubicación y tipo, y a los proveedores gestionar su catálogo en tiempo real. Su modelo se basa en comisiones y promoción destacada.</td><td valign="top"><p>Es una app de origen asiático que facilita la reserva de experiencias locales, entradas y transporte en más de 100 países. Brinda confirmación inmediata y herramientas para que los proveedores gestionen su oferta. Monetiza mediante comisiones y servicios de visibilidad.</p><p></p></td></tr>
<tr><td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td><td valign="top">Conecta a turistas con agencias para crear experiencias completamente personalizadas según sus preferencias y presupuesto, ofreciendo una alternativa flexible y enfocada en la personalización.</td><td valign="top">Ofrece una amplia selección de actividades verificadas en todo el mundo con una plataforma fácil de usar, lo que brinda confianza, variedad y flexibilidad a los viajeros al momento de reservar.</td><td valign="top">Permite acceder a miles de experiencias turísticas respaldadas por TripAdvisor, integrando reseñas y comparaciones que facilitan la toma de decisiones informadas al reservar.</td><td valign="top">Facilita la reserva rápida de experiencias auténticas con confirmación inmediata y precios competitivos, ideal para viajeros que buscan comodidad y eficiencia.</td></tr>
<tr><td rowspan="2" valign="top"><p></p><p>Perfil de Marketing </p></td><td valign="top">Mercado objetivo</td><td valign="top">Agencias de turismo que desean digitalizar su oferta, turistas nacionales e internacionales que buscan actividades personalizadas, y viajeros por trabajo que desean optimizar su tiempo libre con experiencias locales.</td><td valign="top">Turistas internacionales y locales que buscan experiencias organizadas, excursiones y actividades en destinos populares, principalmente de ocio y cultura.</td><td valign="top"><p>Viajeros globales interesados en tours guiados, actividades culturales y excursiones, especialmente aquellos que valoran las reseñas y la confiabilidad de una marca reconocida como TripAdvisor.</p><p></p></td><td valign="top">Turistas jóvenes, viajeros independientes y tecnológicos, especialmente en Asia y grandes ciudades, que buscan experiencias rápidas, auténticas y accesibles desde el mó</td></tr>
<tr><td valign="top">Estrategias de marketing</td><td valign="top"><p>Implementa campañas en redes sociales dirigidas a turistas y agencias, estrategias de posicionamiento SEO local e internacional, alianzas con agencias regionales y marketing de contenidos enfocado en experiencias personalizadas. Además, utiliza promociones cruzadas y testimonios para generar confianza y atraer nuevos usuarios.</p><p></p></td><td valign="top">Utiliza marketing digital intensivo, incluyendo SEO, publicidad en Google Ads, redes sociales y colaboraciones con influencers de viajes. También invierte en contenido optimizado y campañas en plataformas de video para generar confianza y visibilidad global.</td><td valign="top">Aprovecha la integración con TripAdvisor para captar tráfico orgánico, destacando actividades dentro de sus páginas. Además, emplea campañas de email marketing, publicidad digital y alianzas con operadores turísticos para ampliar su alcance.</td><td valign="top"><p>Se enfoca en marketing de contenidos, redes sociales y colaboraciones con influencers y youtubers de viajes, especialmente en el mercado asiático. También lanza promociones exclusivas, descuentos en fechas especiales y campañas móviles con notificaciones push.</p><p></p></td></tr>
<tr><td rowspan="3" valign="top"><p></p><p>Perfil de producto</p></td><td valign="top">Productos & Servicios</td><td valign="top"><p>Ofrece paquetes turísticos personalizados, excursiones, actividades locales según intereses y presupuesto, sistema de reservas en tiempo real, catálogo digital para agencias, y opciones de visibilidad premium dentro de la plataforma.</p><p></p></td><td valign="top"><p>Ofrece tours guiados, entradas a atracciones turísticas, excursiones de un día, experiencias gastronómicas, actividades de aventura, traslados y servicios personalizados en múltiples destinos.</p><p></p></td><td valign="top">Brinda acceso a tours y excursiones, entradas sin colas, actividades culturales y de entretenimiento, experiencias únicas (como clases de cocina o catas), y paquetes combinados con cancelación flexible.</td><td valign="top">Proporciona entradas a atracciones, experiencias locales, transporte (trenes, buses, tarjetas SIM), actividades temáticas, eventos especiales, paquetes turísticos y servicios adicionales como seguros de viaje.</td></tr>
<tr><td valign="top">Precios & Costos</td><td valign="top">Variados</td><td valign="top">Variados</td><td valign="top">Variados</td><td valign="top">Variados</td></tr>
<tr><td valign="top">Canales de distribución (Web y/o Móvil)</td><td valign="top">Web/Móvil</td><td valign="top">Web/Móvil</td><td valign="top">Web/Móvil</td><td valign="top">Web/Móvil</td></tr>
<tr><td rowspan="5" valign="top"><p></p><p>Análisis SWOT</p></td><td colspan="5" valign="top">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva</td></tr>
<tr><td valign="top">Fortalezas</td><td valign="top"><p>Ofrece experiencias personalizadas para turistas y agencias.</p><p>Conecta directamente a agencias de turismo con clientes, eliminando intermediarios.</p><p>Sistema de reservas en tiempo real, lo que optimiza la experiencia del cliente.</p><p>Modelo de negocio flexible basado en comisiones y suscripciones.</p><p></p></td><td valign="top"><p>Gran variedad de actividades en múltiples destinos.</p><p>Reputación confiable gracias a las reseñas de usuarios.</p><p>Plataforma fácil de usar con opciones de pago flexibles.</p><p>Presencia global en más de 150 países.</p><p></p></td><td valign="top"><p>Respaldo y confianza de TripAdvisor, lo que genera credibilidad.</p><p>Amplia gama de tours y actividades a nivel mundial.</p><p>Fuerte presencia en mercados desarrollados.</p><p></p></td><td valign="top"><p>Enfoque en experiencias auténticas y locales.</p><p>Fuerte presencia en Asia y popularidad creciente en mercados occidentales.</p><p>Amplia oferta de productos (transporte, entradas, actividades).</p><p>Plataforma móvil optimizada.</p><p></p></td></tr>
<tr><td valign="top">Debilidades</td><td valign="top"><p>Necesidad de atraer a un volumen significativo de agencias para ser competitiva.</p><p>Competencia con plataformas establecidas como Viator y GetYourGuide.</p><p>Dependencia de la calidad de las agencias asociadas.</p><p></p></td><td valign="top"><p>Alta competencia con otras plataformas de reservas de actividades.</p><p>Dependencia de las comisiones de los proveedores, lo que puede afectar los márgenes.</p><p>Limitada personalización de las experiencias en algunos casos.</p><p></p></td><td valign="top"><p>Fuerte dependencia de TripAdvisor para la generación de tráfico.</p><p>Poca flexibilidad en la personalización de experiencias para turistas.</p><p>La competencia directa de plataformas como GetYourGuide y Klook.</p><p></p></td><td valign="top"><p>Dependencia de un mercado asiático que puede volverse saturado.</p><p>Limitada presencia en algunos mercados turísticos importantes como Europa y América Latina.</p><p>Escasa personalización en algunos servicios.</p><p></p></td></tr>
<tr><td valign="top">Oportunidades</td><td valign="top"><p>Expansión a mercados globales con un enfoque local.</p><p>Crecimiento de la demanda de experiencias personalizadas post-pandemia.</p><p>Colaboraciones con agencias de turismo locales y servicios complementarios.</p><p></p></td><td valign="top"><p>Expansión en mercados emergentes y destinos menos explotados.</p><p>Crecimiento en el turismo post-pandemia con nuevas experiencias.</p><p>Colaboraciones con agencias de turismo locales para diversificar la oferta.</p><p></p></td><td valign="top"><p>Expansión en mercados emergentes, especialmente en Asia y América Latina.</p><p>Innovación en la experiencia del usuario con tecnologías emergentes (realidad aumentada, inteligencia artificial).</p><p>Creación de alianzas estratégicas con agencias turísticas locales.</p><p></p></td><td valign="top"><p>Expansión en mercados globales fuera de Asia.</p><p>Alianzas con grandes empresas de turismo para ofrecer paquetes exclusivos.</p><p>Expansión de la oferta de servicios más allá de las actividades turísticas.</p><p></p></td></tr>
<tr><td valign="top">Amenazas</td><td valign="top"><p>Alta competencia en el mercado de reservas de actividades turísticas.</p><p>Cambios en las regulaciones locales o internacionales de turismo.</p><p>Riesgo de no diferenciarse suficientemente en un mercado con muchas opciones similares.</p><p></p></td><td valign="top"><p>Inestabilidad en la industria del turismo debido a factores globales (crisis económicas, pandemias).</p><p>Cambios en las regulaciones de viajes y turismo en distintos países.</p><p>Competencia creciente de plataformas como Viator, Klook y nuevas startups.</p><p></p></td><td valign="top"><p>Cambios en las regulaciones turísticas o políticas de reembolsos.</p><p>La creciente demanda de experiencias personalizadas que pueden no ser completamente cubiertas por Viator.</p><p>Aumento de la competencia con plataformas más flexibles.</p><p></p></td><td valign="top"><p>Competencia fuerte con otras plataformas globales como GetYourGuide y Viator.</p><p>Cambios en las preferencias de los viajeros hacia experiencias más personalizadas y sostenibles.</p><p>Riesgo de saturación de mercado en Asia.</p><p></p></td></tr>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

**1. Estrategias de Crecimiento y Expansión:**

- **#1 Expansión de alianzas con agencias de turismo locales e internacionales:**

    TravelMatch forjará colaboraciones estratégicas con agencias de turismo locales y globales, permitiendo que estas se integren de manera fluida en la plataforma para ofrecer una variedad más amplia de paquetes turísticos y experiencias personalizadas. Esto impulsará el crecimiento de la plataforma al aumentar la base de agencias asociadas y diversificar la oferta para los usuarios.

- **#2 Creación de un programa de fidelización para turistas frecuentes:**

    TravelMatch lanzará un programa de recompensas y membresía premium para turistas frecuentes. Este programa incentivará a los viajeros a realizar más reservas dentro de la plataforma, con beneficios como descuentos exclusivos, acceso anticipado a ofertas especiales y experiencias VIP, fomentando la lealtad de los usuarios a largo plazo.

- **#3 Expansión a mercados internacionales con enfoque local:**

    TravelMatch se expandirá a nuevos mercados internacionales, comenzando con destinos turísticos populares, pero ofreciendo un enfoque altamente localizado, adaptado a las preferencias culturales y necesidades de los viajeros en esas regiones. Esto permitirá captar una base de usuarios diversa y brindar experiencias altamente relevantes.

**2. Estrategias de Innovación y Diferenciación:**

- **#1 Personalización mediante análisis de preferencias del usuario:**

    TravelMatch implementará un sistema que permita personalizar las recomendaciones de paquetes turísticos y actividades en función de las preferencias y comportamientos de los usuarios. Aunque no se utilicen IA avanzadas, se podrán crear filtros que permitan a los usuarios explorar opciones adaptadas a su destino, tipo de experiencia y presupuesto.

- **#2 Mejora de la experiencia de usuario a través de un diseño optimizado y funcional:**
    La plataforma se diseñará de forma sencilla, intuitiva y fácil de navegar, permitiendo a los usuarios encontrar rápidamente las actividades que desean. Esto incluirá filtros detallados, clasificación de destinos y actividades, y un proceso de reserva claro y rápido, mejorando la experiencia del usuario y facilitando la toma de decisiones.

- **#3 Ofrecimiento de paquetes de viaje personalizados por agentes locales:**
    En lugar de depender de algoritmos complejos, TravelMatch ofrecerá la posibilidad de crear itinerarios de viaje personalizados con la ayuda de agentes de viajes locales que conozcan los destinos de manera profunda. Esto agregará un valor adicional, ya que los usuarios podrán recibir recomendaciones de expertos que comprendan el destino y sus necesidades.

**3. Tácticas:**

- **Desarrollo de Producto:**
    - **Ciclos de desarrollo ágil:** Implementar procesos ágiles para realizar iteraciones rápidas en la plataforma, mejorando constantemente la experiencia del usuario basándose en los comentarios y el feedback directo de los turistas y agencias.
    - **Pruebas A/B continuas:** Realizar pruebas A/B para optimizar la experiencia de usuario, desde la interfaz de usuario hasta las funcionalidades del sistema de reservas, asegurando que las mejoras se basen en datos reales de uso y preferencias de los usuarios.

- **Fidelización del Usuario:**
    - **Programa de lealtad y membresías premium:** Crear un sistema de recompensas para los viajeros recurrentes y agencias destacadas. Las membresías premium otorgarán beneficios exclusivos, como descuentos, acceso prioritario y visibilidad aumentada en la plataforma para las agencias de turismo.
    - **Feedback y mejora continua:** Establecer canales de comunicación directa con los usuarios (tanto turistas como agencias) para recibir sugerencias y mejorar la plataforma. Utilizar análisis de datos de interacciones pasadas para ofrecer una experiencia más satisfactoria en futuras reservas.

- **Expansión Tecnológica:**
    - **Optimización multiplataforma:** Asegurar que TravelMatch funcione de manera óptima tanto en dispositivos móviles como en plataformas web, garantizando un acceso constante y sin interrupciones a la plataforma desde cualquier dispositivo, en cualquier lugar y momento.



### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas

En esta sección de preguntas, nuestro objetivo es comprender mejor las necesidades, motivaciones y preferencias de nuestros segmentos objetivos dentro del ecosistema turístico. A continuación, se muestran las preguntas:

- **Segmento #1: Agencias de turismo locales**

    **Preguntas principales:**
    -  ¿Qué canales usas actualmente para promocionar tus paquetes turísticos? ¿Qué tan efectivos los consideras?
    -  ¿Con qué frecuencia recibes reservas online? ¿Qué retos enfrentas en su gestión?
    -  ¿Qué importancia le das a tener una presencia digital sólida frente a la competencia?
    -  ¿Estás satisfecho con las herramientas tecnológicas actuales que usas para tu agencia? ¿Por qué?
    -  ¿Qué funcionalidades consideras más útiles en una plataforma que conecte agencias con turistas?
    -  ¿Has tenido dificultades para destacar frente a agencias más grandes o con más recursos?
    -  ¿Qué valoras más al elegir una herramienta digital: facilidad de uso, alcance de clientes, personalización o soporte técnico?

    **Preguntas complementarias:**
    -  ¿Qué tipo de turistas suelen contratar tus servicios (edad, nacionalidad, intereses)?
    -  ¿Qué porcentaje de tus reservas proviene de canales digitales?
    -  ¿Te interesa acceder a planes premium o suscripciones que te den mayor visibilidad?
    -  ¿Cuáles son las temporadas donde más te gustaría tener apoyo digital para la gestión de tu oferta?
    -  ¿Qué tan dispuesto estarías a pagar una comisión por cada reserva concretada a través de una plataforma?

- **Segmento #2: Turistas nacionales e internacionales**

    **Preguntas principales:**
    -  ¿Cómo sueles planificar tus viajes dentro del Perú? ¿Qué herramientas usas para ello?
    -  ¿Qué tan importante es para ti personalizar tus experiencias de viaje según tus intereses?
    -  ¿Has tenido dificultades encontrando actividades o excursiones que se adapten a tu presupuesto o estilo de viaje?
    -  ¿Qué tipo de actividades valoras más al viajar (culturales, aventura, gastronomía, relax, etc.)?
    -  ¿Prefieres reservar todo por separado o en paquetes que combinen varias experiencias?
    -  ¿Qué tan relevante es para ti poder comparar precios, duración y valoraciones desde una sola plataforma?
    -  ¿Qué factores te dan más confianza al reservar actividades en línea (opiniones, reputación de la agencia, medios de pago, seguridad)?

    **Preguntas complementarias:**
    -  ¿Estás dispuesto a pagar un poco más por una experiencia auténtica y personalizada?
    -  ¿Te interesaría recibir recomendaciones de actividades según tu ubicación y tus intereses?
    -  ¿Qué tan cómodo te resulta hacer reservas desde tu celular cuando estás viajando?
    -  ¿Te gustaría tener la opción de contactar directamente con la agencia antes de reservar?
    -  ¿Te ha pasado que llegaste a un destino sin saber qué actividades hacer y dónde contratarlas?

- **Segmento #3: Viajeros por trabajo (Turismo corporativo)**

    **Preguntas principales:**
    - ¿Con qué frecuencia viajas por motivos laborales dentro del país?
    -  ¿Sueles tener tiempo libre entre reuniones o compromisos laborales cuando viajas?
    -  ¿Qué tipo de actividades te gustaría realizar durante tu tiempo libre? (Tours cortos, experiencias gastronómicas, relajación, etc.)
    -  ¿Qué valoras más al reservar actividades durante viajes de trabajo: rapidez, ubicación cercana, disponibilidad inmediata, etc.?
    -  ¿Utilizas apps o plataformas para organizar tu tiempo libre cuando estás fuera por trabajo? ¿Cuáles?
    -  ¿Te resulta complicado encontrar actividades con horarios flexibles o compatibles con tus jornadas laborales?
    -  ¿Estás interesado en experiencias personalizadas que se adapten a tu perfil profesional y tus gustos personales?

    **Preguntas complementarias:**
    -  ¿Prefieres reservar actividades antes de viajar o una vez ya estás en la ciudad?
    - ¿Te gustaría recibir recomendaciones automáticas según tu horario, ubicación y tipo de viaje?
    -  ¿Qué tan cómodo te sentirías usando una app que combine actividades turísticas y servicios prácticos para viajeros de negocio?
    -  ¿Qué nivel de confianza necesitas para reservar con una agencia nueva o desconocida?
    -  ¿Consideras útil una opción para generar comprobantes o facturas automáticamente al reservar?

#### 2.2.2. Registro de entrevistas
<!-- Segmento objetivo 1: AGENCIAS -->

- **Entrevista 1:**

<p align="center">
    <img src="assets/entrevistas/entrevista-maria.png" alt="entrevista-maria" width=60% >
</p>

<div align="center">

| Entrevistado | Maria Rodriguez Benites |
|----|-----|
|Edad|44|
|Residencia|Lima|
|Segmento|Agencia|
|Enlace de la entrevista| [https://youtu.be/hdzxGndELyA](https://youtu.be/hdzxGndELyA)|

</div>

_Resumen:_ La entrevistada menciona que en su agencia utilizan principalmente redes sociales (Facebook, Instagram, TikTok) y plataformas como Google Ads y TripAdvisor para promocionar paquetes turísticos, lo cual ha sido efectivo para atraer turistas. Ademas, menciona que la mayoría de sus reservas proviene de canales digitales, pero enfrentan retos como la sincronización en tiempo real de la disponibilidad de los paquetes, especialmente en temporadas altas como verano y feriados. Considera que si bien las herramientas tecnológicas actuales cumplen con lo básico, desea soluciones más integradas para gestionar reservas, pagos y marketing. Valora funcionalidades como disponibilidad en tiempo real, opciones de pago flexibles y un buen soporte técnico. Por ultimo, se encuentra dispuesta a pagar una comisión razonable por cada reserva si la plataforma ofrece un buen retorno en visibilidad y eficiencia.

---

- **Entrevista 2:**

<p align="center">
    <img src="assets/entrevistas//entrevista-tony.png" alt="entrevista-tony" width=60% >
</p>

<div align="center">

| Entrevistado | Tony Blades Sarmiento |
|----|-----|
|Edad|28|
|Residencia|Lima|
|Segmento|Agencia|
|Enlace de la entrevista| [https://youtu.be/zkip_T6onFg](https://youtu.be/zkip_T6onFg)|

</div>

_Resumen:_ El entrevistado comenta que utilizan redes sociales como Facebook, Instagram y WhatsApp. También disponen de una página web con optimizaciones limitadas para sus necesidades. Si bien considera útiles estas herramientas, no las percibe como eficientes. Además, señala que uno de los principales desafíos que enfrenta es la confirmación de pagos y la falta de coordinación cuando los clientes dudan en concretar una compra. Asimismo, menciona que le gustaría contar con una plataforma intuitiva que integre funcionalidades de pago, mensajería y análisis de datos, facilitando así la conexión con sus clientes. Finalmente, expresa su disposición a pagar una suscripción para obtener beneficios durante las temporadas de mayor demanda.

---

**Entrevista 3:**

<p align="center">
    <img src="assets/entrevistas/entrevista-david.png" alt="entrevista-david" width=60% >
</p>

<div align="center">

| Entrevistado | David Perez Garcia |
|----|-----|
|Edad|22|
|Residencia|Lima|
|Enlace de la entrevista| [https://youtu.be/5S-RLPOGsRA](https://youtu.be/5S-RLPOGsRA)|

</div>

_Resumen:_ El entrevistado trabaja para una agencia de turismo peruana, utiliza redes sociales y WhatsApp para promocionar sus servicios, lo cual es efectivo para clientes jóvenes y locales, pero limitado para turistas extranjeros. Aunque las reservas online son comunes en temporada alta, la gestión de múltiples canales genera problemas. Pérez reconoce la necesidad de una sólida presencia digital y herramientas integradas con calendarios en tiempo real, chat directo, gestión de pagos, estadísticas y un perfil completo para competir y generar confianza. Su agencia se enfoca en jóvenes de 20 a 35 años interesados en experiencias auténticas, con un 70% de reservas online. Está dispuesto a invertir en soluciones digitales transparentes y fáciles de usar que mejoren la visibilidad, especialmente en temporadas altas.

---

<!-- Segmento objetivo 2: TURISTAS NACIONALES E INTERNACIONALES -->

**Entrevista 4:**

<p align="center">
    <img src="assets/entrevistas/entrevista-adrian.png" alt="entrevista-adrian" width=60% >
</p>

<div align="center">

| Entrevistado | Adrian Yañez Mendez |
|----|-----|
|Edad|20|
|Residencia|Lima|
|Segmento|Turista Nacional|
|Enlace de la entrevista| [https://youtu.be/EetEBccMXDg](https://youtu.be/EetEBccMXDg)|

</div>

_Resumen:_ El entrevistado, un turista limeño de 20 años, organiza sus viajes inspirándose en redes sociales como Instagram y TikTok, y complementa su planificación con Google Maps, TripAdvisor y blogs de viaje. Le da gran importancia a la personalización de sus experiencias, priorizando actividades culturales, de aventura y fotografía. Aunque prefiere paquetes turísticos bien estructurados, a menudo encuentra opciones costosas o genéricas, por lo que valora plataformas que permitan comparar precios, duración y opiniones en un solo lugar. Está dispuesto a pagar más por experiencias auténticas y personalizadas, y le resulta cómodo hacer reservas desde su celular, siempre que la app sea intuitiva. También considera esencial poder comunicarse con la agencia antes de reservar y recibir recomendaciones según su ubicación e intereses.

---

**Entrevista 5:**

<p align="center">
    <img src="assets/entrevistas/entrevista-sebastian.png" alt="entrevista-sebastian" width=60% >
</p>

<div align="center">

| Entrevistado | Sebastian Arevalo Torres |
|----|-----|
|Edad|23|
|Residencia|Chile|
|Segmento|Turista Internacional|
|Enlace de la entrevista| [https://youtu.be/3z10bH6wOBY](https://youtu.be/3z10bH6wOBY)|

</div>

_Resumen:_ El entrevistado, turista chileno de 23 años, organiza sus viajes por Perú con anticipación usando Google Travel, Booking.com y YouTube, priorizando experiencias auténticas alejadas del turismo convencional. Valora especialmente las actividades culturales y gastronómicas, como visitar mercados y museos, y suele reservar por separado para tener mayor control, aunque considera paquetes si están bien estructurados. Le resulta esencial comparar precios, duración y opiniones desde una sola plataforma, y confía principalmente en las reseñas de otros viajeros. Está dispuesto a pagar más por experiencias únicas que beneficien a comunidades locales, y aprecia recibir recomendaciones personalizadas según su ubicación e intereses. Además, considera muy cómodo hacer reservas desde su celular y le parece crucial poder contactar a la agencia antes de reservar, especialmente para resolver dudas sobre idioma, disponibilidad o detalles del tour.

---

**Entrevista 6:**

<p align="center">
    <img src="assets/entrevistas/entrevista-diego.png" alt="entrevista-diego" width=60% >
</p>

<div align="center">

| Entrevistado | Diego Santiago Lima |
|----|-----|
|Edad|21|
|Residencia|Arequipa|
|Segmento|Turista Nacional|
|Enlace de la entrevista| [https://youtu.be/CLrBogoQrVM](https://youtu.be/CLrBogoQrVM)|

</div>

_Resumen:_ El entrevistado, mochilero arequipeño de 21 años, organiza sus viajes de forma espontánea utilizando grupos de Facebook, Telegram y TikTok para encontrar recomendaciones de última hora. Valora la personalización de sus experiencias y prefiere improvisar sobre la marcha, adaptando sus actividades según su estado de ánimo, el clima o la gente que conoce. Sus intereses se centran en la gastronomía y actividades culturales accesibles o gratuitas. Prefiere reservar servicios por separado para mantener flexibilidad y controlar su presupuesto. Considera crucial poder comparar precios y valoraciones en una sola plataforma, y confía en las opiniones de otros jóvenes mochileros. Aunque busca opciones económicas, está dispuesto a pagar más por experiencias únicas. Para él, es fundamental recibir recomendaciones personalizadas según su ubicación y contar con opciones de pago como Yape o Plin. Además, valora poder contactar con la agencia antes de reservar y suele llegar a destinos sin itinerario fijo, confiando en su celular como herramienta principal para planificar y reservar en el camino.

---

<!-- Segmento objetivo 3: TURISTAS CORPORATIVOS -->

**Entrevista 7:**

<p align="center">
    <img src="assets/entrevistas/entrevista-cesar.png" alt="entrevista-cesar" width=60% >
</p>

<div align="center">

| Entrevistado | Cesar Vasquez Lopez |
|----|-----|
|Edad|55|
|Residencia|Lima|
|Enlace de la entrevista| [https://youtu.be/AeP60c6hXrs](https://youtu.be/AeP60c6hXrs)|

</div>

_Resumen:_ El entrevistado, quien por su trabajo viaja con frecuencia a Paracas, Nazca, Chincha e Ica, tiene interés en visitar atractivos turísticos como las Líneas de Nazca, las Islas Ballestas y la Huacachina en su tiempo libre. Para él, la puntualidad del servicio es primordial en una plataforma de gestión de paquetes turísticos. Actualmente, utiliza WhatsApp y Google Maps para organizar sus itinerarios laborales, pero le resulta difícil encontrar tiempo libre. Por ello, valoraría una aplicación que se adapte a sus horarios personales y laborales, brindándole la oportunidad de realizar visitas turísticas. Finalmente, considera crucial la recomendación de otros clientes al elegir una agencia de viajes.

---

**Entrevista 8:**

<p align="center">
    <img src="assets/entrevistas/entrevista-eduardo.jpg" alt="entrevista-eduardo" width=60% >
</p>

<div align="center">

| Entrevistado | Eduardo Montalvo |
|----|-----|
|Edad| 25 |
|Residencia|Lima|
|Enlace de la entrevista| [https://youtu.be/_GoZZZpl_5c](https://youtu.be/_GoZZZpl_5c)|

</div>

_Resumen:_ El entrevistado es un viajero corporativo en Perú que viaja laboralmente dos veces al mes (Lima, Trujillo, Arequipa, ocasionalmente Cusco/Chiclayo) y a veces tiene tiempo libre. Prefiere tours cortos o gastronomía local cerca de su alojamiento, valorando la rapidez y disponibilidad inmediata. Usa Google Maps y TripAdvisor, pero desearía una app para viajeros de negocios con horarios flexibles y recomendaciones personalizadas según su ubicación y agenda, idealmente con reserva en destino. Le atraería una app que combine actividades, servicios y facturación automática, confiando en agencias con buenas reseñas y contacto claro.

---

**Entrevista 9:**

<p align="center">
    <img src="assets/entrevistas/entrevista-abigail.jpg" alt="entrevista-abigail" width=60% >
</p>

<div align="center">

| Entrevistado | Abigail Goñe |
|----|-----|
|Edad|21|
|Residencia|Lima|
|Enlace de la entrevista| [https://www.youtube.com/watch?v=XB2zMZLNVMY](https://www.youtube.com/watch?v=XB2zMZLNVMY)|

</div>

_Resumen:_  La entrevistada viaja laboralmente tres veces al mes (Arequipa, Trujillo, Piura) y a veces tiene 1-2 horas libres. Prefiere visitas cortas a sitios arqueológicos o gastronomía local, valorando rapidez y cercanía. Usa Google Maps, Yelp y TikTok, pero desearía una app con opciones turísticas, tiempos y reservas integradas. Le cuesta encontrar actividades con horarios flexibles. Le interesan sugerencias personalizadas y prefiere reservar en destino por cambios de agenda. Idealmente, busca una app con recomendaciones automáticas según su ubicación y horario, que combine actividades y servicios prácticos, incluyendo facturación automática. Confía en agencias nuevas con buenas opiniones, web actualizada y atención rápida.

---

#### 2.2.3. Análisis de entrevistas


- **Segmento objetivo 1 - Dueños de agencia de viajes**

    Las entrevistas con María Rodríguez, Tony Blades y David Pérez revelan puntos en común significativos que validan la propuesta de valor de TravelMatch para las agencias de turismo locales.

    - _Dependencia de Canales Digitales y Limitaciones:_ Las tres fuentes coinciden en la importancia de los canales digitales para la captación de clientes. El 100% de las agencias entrevistadas utilizan activamente redes sociales (Facebook e Instagram son recurrentes), y al menos una de ellas (33%) menciona el uso de plataformas de publicidad online como Google Ads y TripAdvisor. Sin embargo, a pesar de su efectividad para ciertos segmentos, reconocen limitaciones para alcanzar audiencias más amplias (turistas extranjeros) o para una gestión integral de sus operaciones.

    - _Prevalencia de Reservas Online y Desafíos de Gestión:_ Tanto María como David señalan que una parte significativa de sus reservas proviene de canales digitales (María indica "la mayoría" y David un 70%). No obstante, esto conlleva desafíos importantes. El 67% de las agencias (María y David) experimentan problemas con la sincronización en tiempo real de la disponibilidad, especialmente en temporadas altas. Además, la gestión de múltiples canales (redes sociales, WhatsApp, web propia, plataformas de publicidad) genera ineficiencias y dificulta la coordinación, como lo destaca Tony con los problemas en la confirmación de pagos y el seguimiento de clientes indecisos.

    - _Necesidad de Soluciones Integradas:_ Existe un consenso unánime (100% de las agencias) en la necesidad de herramientas tecnológicas más integradas. Expresan el deseo de funcionalidades que vayan más allá de las soluciones básicas que utilizan actualmente (mencionado por María).

    - _Disposición a Invertir por Valor:_ Las tres fuentes muestran una disposición a invertir en una plataforma como TravelMatch si esta ofrece un valor claro. María está dispuesta a pagar una comisión "razonable" por un buen retorno en visibilidad y eficiencia. Tony considera pagar una suscripción por beneficios en temporadas altas. David también está dispuesto a invertir en soluciones "transparentes y fáciles de usar" que mejoren la visibilidad y los resultados, especialmente en temporadas de alta demanda. Esto sugiere una sensibilidad al modelo de negocio propuesto (comisiones y planes premium), siempre y cuando se demuestre un retorno tangible.

    - **Conclusiones**

        - Existe una clara validación de la problemática identificada: la fragmentación de la gestión y la necesidad de canales digitales más eficientes e integrados para las agencias locales.
        - La propuesta de valor de TravelMatch resuena con las necesidades expresadas, especialmente en cuanto a la integración de funcionalidades clave como la gestión de disponibilidad, pagos y comunicación con los clientes.
        - El modelo de negocio basado en comisiones y planes premium parece viable, dado la disposición de las agencias a invertir a cambio de mayor visibilidad y eficiencia, especialmente en temporadas altas.
        - La facilidad de uso y un buen soporte técnico serán cruciales para la adopción y el éxito de la plataforma entre las agencias.

- **Segmento objetivo 2 - Turistas nacionales e internacionales**
    
    Las entrevistas con Adrián Yáñez, Sebastián Arévalo y Diego Santiago, a pesar de sus diferencias en estilo de viaje, revelan necesidades y comportamientos comunes que TravelMatch puede abordar.

    - _Influencia de Plataformas Digitales en la Planificación:_ Los tres entrevistados utilizan activamente plataformas digitales para inspirarse y planificar sus viajes. El 100% menciona redes sociales (Instagram y TikTok son populares), y herramientas como Google Maps, TripAdvisor, Google Travel, YouTube, blogs de viaje y grupos de Facebook/Telegram también son relevantes. Esto subraya la importancia de una sólida presencia online y la capacidad de TravelMatch para integrarse o ser descubierto a través de estos canales.

    - _Valoración de la Personalización y la Autenticidad:_ Los tres turistas demuestran un fuerte interés en la personalización de sus experiencias. Adrián prioriza actividades culturales, de aventura y fotografía; Sebastián busca experiencias auténticas alejadas del turismo convencional, con foco en lo cultural y gastronómico; y Diego valora la improvisación y actividades gastronómicas y culturales accesibles. El 100% busca experiencias que se adapten a sus intereses específicos y valoran la autenticidad.

    - _Necesidad de Comparación y Transparencia:_ Los tres entrevistados resaltan la importancia de poder comparar precios, duración y opiniones en un solo lugar. Adrián y Sebastián lo mencionan explícitamente, mientras que Diego considera crucial comparar precios y valoraciones. Esto indica una necesidad de TravelMatch de ofrecer una interfaz clara y completa para la comparación de opciones.

    - _Disposición a Pagar por Experiencias de Valor:_ Si bien Diego busca opciones económicas, los tres están dispuestos a pagar más por experiencias auténticas, personalizadas o únicas. Adrián menciona estar dispuesto a pagar más por experiencias auténticas y personalizadas, Sebastián por experiencias únicas que beneficien a comunidades locales, y Diego por experiencias únicas. Esto sugiere que el precio no es el único factor determinante, y que TravelMatch puede ofrecer experiencias premium si el valor percibido es alto.

    - _Importancia de la Reserva Móvil y la Comunicación:_ Los tres consideran cómodo o esencial poder hacer reservas desde su celular y valoran la posibilidad de comunicarse con la agencia antes de reservar. Adrián y Sebastián lo mencionan directamente, y Diego confía en su celular para planificar y reservar en el camino. Esto enfatiza la necesidad de una app móvil intuitiva y funcionalidades de comunicación directa dentro de la plataforma.

    - _Preferencias de Pago:_ Diego menciona la importancia de opciones de pago locales como Yape o Plin, lo cual es un factor a considerar para la adopción local.

    - **Conclusiones**

        - Preferencias de Pago: Diego menciona la importancia de opciones de pago locales como Yape o Plin, lo cual es un factor a considerar para la adopción local.
        - La propuesta de valor de TravelMatch de ofrecer una experiencia de búsqueda fluida, segura y adaptada a las preferencias del turista es altamente relevante para este segmento.
        - La funcionalidad de comparación de precios, duración y opiniones será crucial para atraer y retener a los usuarios.        
        - TravelMatch debe ser lo suficientemente flexible para atender tanto a viajeros que planifican con anticipación como a aquellos más espontáneos.

    
- **Segmento objetivo 3 - Turistas corporativos**
    
    Las entrevistas con César Vásquez, Eduardo Montalvo y Abigail Goñe ofrecen una perspectiva sobre las necesidades de los viajeros corporativos que buscan aprovechar su tiempo libre durante sus desplazamientos laborales.

    - _Oportunidades de Turismo en Tiempo Libre Limitado:_ César Vásquez, quien viaja con frecuencia por trabajo en la región de Ica, expresa un claro interés en visitar atractivos turísticos locales en su tiempo libre, aunque actualmente le resulta difícil encontrarlo. Esto sugiere una oportunidad para TravelMatch de ofrecer actividades que se ajusten a las ventanas de tiempo libre de los viajeros corporativos. Eduardo y Abigail también mencionan tener tiempo libre limitado entre sus compromisos laborales.

    - _Valoración de la Puntualidad y la Adaptabilidad Horaria:_ Para César, la puntualidad del servicio es primordial. Además, valora una aplicación que se adapte a sus horarios personales y laborales. Esta necesidad de flexibilidad horaria y confiabilidad en los tiempos es un factor clave para este segmento. Eduardo y Abigail también resaltan la dificultad de encontrar actividades con horarios compatibles con sus jornadas laborales.

    - _Uso de Herramientas Digitales Básicas y Deseo de Integración:_ César utiliza WhatsApp y Google Maps para su logística laboral, pero no para actividades turísticas. Eduardo y Abigail utilizan Google Maps y otras plataformas generales (TripAdvisor, Yelp, TikTok) pero expresan el deseo de una app específica para viajeros de negocios que integre opciones turísticas, tiempos estimados y reservas. Esto refuerza la necesidad de una plataforma integrada como TravelMatch que simplifique la búsqueda y reserva de actividades.

    - _Interés en Experiencias Específicas:_ Eduardo prefiere tours cortos o gastronomía local, mientras que Abigail se inclina por visitas cortas a sitios arqueológicos o gastronomía local. Esto sugiere que, si bien el tiempo es limitado, existe un interés en experiencias culturales y gastronómicas concisas.

    - _Relevancia de la Personalización y las Recomendaciones Automáticas:_ Eduardo y Abigail desean recomendaciones personalizadas según su ubicación, horario e intereses. Abigail también busca recomendaciones automáticas. Esto valida la importancia de un motor de recomendaciones inteligente dentro de TravelMatch que considere el contexto del viaje de negocios.

    - **Conclusiones**

        - Existe una oportunidad para TravelMatch de atender las necesidades de los viajeros corporativos que desean aprovechar sus limitados periodos de tiempo libre para realizar actividades turísticas.
        - La plataforma debe priorizar la puntualidad, la flexibilidad horaria y la conveniencia de ubicación de las actividades ofrecidas.
        - Un sistema de recomendaciones basado en la ubicación, el horario disponible y los intereses del viajero corporativo es crucial.       
        - Generar confianza a través de reseñas y perfiles de agencia detallados es fundamental para la adopción.


### 2.3. Needfinding
#### 2.3.1. User Personas
Basados en los resultados de las entrevistas y el análisis de datos, hemos definido las características clave de cada segmento objetivo estudiado. Esta información nos permitió desarrollar User Personas detallados para cada grupo, con el fin de comprender a profundidad su contexto, metas, motivaciones, dolores y perfil general. Para la creación de estos User Personas, empleamos la plataforma colaborativa UXPressia como herramienta principal de diseño.


<p align="center">
    <img src="assets/recursos/User_Persona_Adrian.jpg" alt="User-Persona-Adrian"/>
</p>

<p align="center">
    <img src="assets/recursos/User_Persona_Tony.jpg" alt="User-Persona-Tony"/>
</p>

<p align="center">
    <img src="assets/recursos/User_Persona_Cesar.jpg" alt="User-Persona-Cesar"/>
</p>

#### 2.3.2. User Task Matrix

***Segmento 1: Dueños de agencia de viajes***

|**Tony Blades**|||
| :-: | :- | :- |
|**Actividades**|**Frecuencia**|**Importancia**|
|Publicar en 3-5 redes sociales|Alta|Alta|
|Crear anuncios en Google Ads de forma manual|Alta|Alta|
|Recibir consultas por WhatsApp/email|Alta|Alta|
|Actualizar disponibilidad en hojas de cálculo|Media|Alta|
|Coordinar con proveedores por teléfono|Media|Media|
|Imprimir vouchers manualmente|Media|Alta|

***Segmento 2: Turistas nacionales e internacionales***

|**Adrián Méndez**|||
| :-: | :- | :- |
|**Actividades**|**Frecuencia**|**Importancia**|
|Buscar en Google, blogs y TikTok|Alta|Alta|
|Guardar opciones en favoritos|Alta|Alta|
|Abrir 5 pestañas para comparar precios|Alta|Alta|
|Preguntar a amigos por WhatsApp|Media|Alta|
|Reservar en 3 plataformas distintas|Media|Alta|
|Descargar vouchers en PDF|Media|Media|
|Coordinar transporte y horarios por separado|Media|Alta|

***Segmento 3: Turistas corporativos***

|**César Vásquez**|||
| :-: | :- | :- |
|**Actividades**|**Frecuencia**|**Importancia**|
|Usar Google Maps para encontrar atracciones cercanas|Alta|Alta|
|Revisar TripAdvisor en el celular|Alta|Alta|
|LLamar a agencias para confirmar disponibilidad|Alta|Alta|
|Enviar emails con detalles de horarios|Alta|Alta|
|Usar Uber para llegar al tour|Media|Alta|
|Revisar itinerario en notas del móvil|Alta|Alta|
|Buscar WiFi para subir fotos a LinkedIn|Media|Media|
|Intentar reclamar por servicio deficiente|Media|Media|

#### 2.3.3. User Journey Mapping
Introducción al End-to-End Journey:
El viaje del usuario ilustrado abarca un ciclo completo desde la exploración inicial hasta la retroalimentación post-experiencia, enfocándose en facilitar actividades adaptadas a necesidades específicas, como agendas laborales ajustadas o preferencias personales.

Descubrimiento: Los usuarios buscan actividades alineadas con sus intereses y disponibilidad, enfrentando desafíos como catálogos desorganizados, horarios inflexibles y descripciones poco claras.

Selección: Comparan opciones basándose en opiniones, ubicación y duración, pero tropiezan con información contradictoria o métodos de pago no locales que ralentizan la decisión.

Reserva: Priorizan rapidez y seguridad, especialmente en contextos corporativos, aunque procesos largos de verificación y falta de integración con plataformas de pago ágiles generan fricción.

Experiencia y Feedback: Buscan disfrutar sin complicaciones logísticas, pero la falta de incentivos o mecanismos simplificados para compartir opiniones resulta en baja participación.


***Segmento 1: Dueños de agencia de viajes***

<p align="center">
    <img src="assets/recursos/User_Journey_Mapping1.png" alt="User-Journey-Mapping"/>
</p>

***Segmento 2: Turistas nacionales e internacionales***

<p align="center">
    <img src="assets/recursos/User_Journey_Mapping2.png" alt="User-Journey-Mapping"/>
</p>

***Segmento 3: Turistas corporativos***

<p align="center">
    <img src="assets/recursos/User_Journey_Mapping3.png" alt="User-Journey-Mapping"/>
</p>

#### 2.3.4. Empathy Mapping

#### 2.3.4.1. Empathy Mapping Turistas nacionales e internacionales

<p align="center">
    <img src="assets/recursos/Empathy_Mapping_Turistass.jpg" alt="Empathy-Mapping-Turistas"/>
</p>

#### 2.3.4.2. Empathy Mapping Agencias de turismo locales

<p align="center">
    <img src="assets/recursos/Empathy_Mapping_Agencias.jpg" alt="Empathy-Mapping-Agencias"/>
</p>

#### 2.3.4.3. Empathy Mapping Viajeros por trabajo

<p align="center">
    <img src="assets/recursos/Empathy_Mapping_Viajeros.jpg" alt="Empathy-Mapping-Viajeros"/>
</p>

#### 2.3.5. As-is Scenario Mapping


#### 2.3.5.1. As-is Scenario Mapping Turistas nacionales e internacionales

<p align="center">
    <img src="assets/recursos/as-is-turistas_v2.png" alt="as-is-turistas_v2"/>
</p>

#### 2.3.5.2. As-is Scenario Mapping Agencias de turismo locales

<p align="center">
    <img src="assets/recursos/as-is-agencias_v2.png" alt="as-is-agencias_v2"/>
</p>

#### 2.3.5.3. As-is Scenario Mapping Viajeros por trabajo

<p align="center">
    <img src="assets/recursos/as-is-viajeros_v2.png" alt="as-is-viajeros_v2"/>
</p>

### 2.4. Ubiquitous Language

| **Término (Inglés)**       | **Término (Español)**       | **Descripción** |
|----------------------------|----------------------------|----------------|
| **Traveler**               | Viajero                    | Usuario de la plataforma que busca descubrir, reservar o personalizar experiencias turísticas, ya sea de forma individual o en grupo. |
| **Travel Agency**          | Agencia de viajes          | Entidad registrada en la plataforma que ofrece paquetes turísticos, experiencias personalizadas o servicios relacionados con viajes. |
| **Experience**             | Experiencia                | Actividad o conjunto de actividades que conforman un paquete turístico (cultural, gastronómico, deportivo, etc.). |
| **Recommended Plan**       | Plan recomendado           | Propuesta de actividades generadas automáticamente según los intereses, preferencias y perfil del viajero. |
| **Match**                  | Coincidencia / Compatibilidad | Grado de afinidad entre un viajero y una agencia o experiencia, basado en intereses, presupuesto y ubicación. |
| **Booking Request**        | Solicitud de reserva       | Acción mediante la cual un viajero inicia el proceso de reservar una experiencia o paquete. |
| **Availability**           | Disponibilidad             | Periodo de tiempo y capacidad en los que una agencia puede ofrecer una experiencia. |
| **Profile**                | Perfil                     | Datos personales y preferencias de viaje asociados a un usuario (viajero o agencia). |
| **Feedback**               | Retroalimentación          | Opiniones, comentarios o calificaciones de los viajeros después de realizar una experiencia. |
| **Tour Package**           | Paquete turístico          | Conjunto de servicios y actividades agrupadas (transporte, alojamiento, alimentación, etc.). |
| **Local Partner**          | Aliado local               | Proveedor asociado a una agencia que ofrece servicios específicos (guías, restaurantes, transportistas). |
| **Seasonality**            | Estacionalidad             | Variación en la demanda o disponibilidad según la época del año, festividades o clima. |
| **Target Audience**        | Audiencia objetivo         | Grupo de personas con características específicas (edad, intereses) al que va dirigida una experiencia. |

<hr>


## Capítulo III:  Requirements Specification 
### 3.1. To-Be Scenario Mapping
### 3.2. User Stories
### 3.3. Product Backlog
### 3.4. Impact Mapping

## Capítulo IV: Product Design  
### 4.1. Style Guidelines
#### 4.1.1. General Style Guidelines 
#### 4.1.2. Web Style Guidelines
#### 4.1.3. Mobile Style Guidelines
#### 4.1.3.1. iOS Mobile Style Guidelines
#### 4.1.3.2. Android Mobile Style Guidelines

### 4.2. Information Architecture
#### 4.2.1. Organization Systems
#### 4.2.2. Labeling Systems
#### 4.2.3. SEO Tags and Meta Tags
#### 4.2.4. Searching Systems
#### 4.2.5.  Navigation Systems

### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
#### 4.3.2. Landing Page Mock-up

### 4.4. Mobile Applications UX/UI Design
#### 4.4.1. Mobile Applications Wireframes
#### 4.4.2. Mobile Applications Wireflow Diagrams
#### 4.4.3. Mobile Applications Mock-ups
#### 4.4.4. Mobile Applications User Flow Diagrams

### 4.5. Mobile Applications Prototyping
#### 4.5.1. Android Mobile Applications Prototyping
#### 4.5.2. iOS Mobile Applications Prototyping

### 4.6. Web Applications UX/UI Design
#### 4.6.1. Web Applications Wireframes
#### 4.6.2. Web Applications Wireflow Diagrams
#### 4.6.3. Web Applications Mock-ups
#### 4.6.4. Web Applications User Flow Diagrams

### 4.7. Web Applications Prototyping

### 4.8. Domain-Driven Software Architecture
#### 4.8.1. Software Architecture Context Diagram
#### 4.8.2. Software Architecture Container Diagrams
#### 4.8.3. Software Architecture Components Diagrams

### 4.9. Software Object-Oriented Design
#### 4.9.1. Class Diagrams
#### 4.9.2. Class Dictionary

### 4.10. Database Design
#### 4.10.1. Relational/Non-Relational Database Diagram


## Capítulo V: Product Implementation 
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
#### 5.1.2. Source Code Management
#### 5.1.3. Source Code Style Guide & Conventions
#### 5.1.4. Software Deployment Configuration

### 5.2. Product Implementation & Deployment
#### 5.2.1. Sprint Backlogs
#### 5.2.2. Implemented Landing Page Evidence
#### 5.2.3. Implemented Frontend-Web Application Evidence
#### 5.2.4. Acuerdo de Servicio - SaaS
#### 5.2.5. Implemented Native-Mobile Application Evidence
#### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence
#### 5.2.7. RESTful API documentation
#### 5.2.8. Team Collaboration Insights

### 5.3. Video About-the-Product

## Capítulo VI:  Product Verification & Validation 
### 6.1. Testing Suites & Validation
#### 6.1.1. Core Entities Unit Tests
#### 6.1.2. Core Integration Tests
#### 6.1.3. Core Behavior-Driven Development
#### 6.1.4. Core System Tests

## Capítulo VII: DevOps Practices 
### 7.1. Continuous Integration
#### 7.1.1. Tools and Practices
#### 7.1.2. Build & Test Suite Pipeline Components

### 7.2. Continuous Delivery
#### 7.2.1. Tools and Practices
#### 7.2.2. Stages Deployment Pipeline Components

### 7.3. Continuous deployment
#### 7.3.1. Tools and Practices
#### 7.3.2. Production Deployment Pipeline Components

## Conclusiones
## BIbliografía
## Anexos

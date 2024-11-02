<h2>Universidad Peruana de Ciencias Aplicadas</h2>

<img src="https://seeklogo.com/images/U/universidad-peruana-de-ciencias-aplicadas-upc-logo-B98C3A365C-seeklogo.com.png" alt="UPC Logo" width="15%" height="15%">

<h2>Informe del Trabajo Final</h2>

<h3>Curso: Arquitecturas de Software Emergentes</h3>
<h3>Carrera: Ingeniería de Software </h3>
<h3>Sección: SW83</h3>
<h3>Profesor: Royer Edelwer Rojas Malasquez</h3>

<strong>Startup:</strong> NewMinds

<strong>Producto:</strong> FacialTruth

<h3>Integrantes:</h3>

<ul>
  <li>Andrés Doig Apostol (u201712256)</li>
  <li>Alonso Fernando Robles Astuñaupa (u202112662)</li>
  <li>Christian Jose Zeta Valenzuela (u202011688)</li>
  <li>Dámaris Jemima Tasayco Vilcamiza (u202119605)</li>
  <li>Erick Gabriel Urbizagstegui Alvarez (u20201e465)</li>
</ul>

**<h3>Noviembre, 2024</h3>**

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|--------------|--------------|--------------|--------------|
| 1           | 08/09/2024      | - Andrés Doig Apostol<br>- - Alonso Fernando Robles Astuñaupa<br>- Christian Jose Zeta Valenzuela<br>- Dámaris Jemima Tasayco Vilcamiza<br>- Erick Gabriel Urbizagstegui Alvarez    | Implementación del capítulo 1 al 4.      |
| 2           | 27/09/2024      | - Andrés Doig Apostol<br>- - Alonso Fernando Robles Astuñaupa<br>- Christian Jose Zeta Valenzuela<br>- Dámaris Jemima Tasayco Vilcamiza<br>- Erick Gabriel Urbizagstegui Alvarez    | Implementación del capítulo 5 al 6. Corrección de errores de la entrega anterior.     |
| 2           | 02/11/2024      | - Andrés Doig Apostol<br>- - Alonso Fernando Robles Astuñaupa<br>- Christian Jose Zeta Valenzuela<br>- Dámaris Jemima Tasayco Vilcamiza<br>- Erick Gabriel Urbizagstegui Alvarez    | Implementación del capítulo 7. Corrección de errores de la entrega anterior.     |

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs\*\*](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. Event Storming](#421-event-storming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)
- [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)
  - [5.1. Bounded Context: Sesion](#51-bounded-context-sesion)
    - [5.1.1. Domain Layer](#511-domain-layer)
    - [5.1.2. Interface Layer](#512-interface-layer)
    - [5.1.3. Application Layer](#513-application-layer)
    - [5.1.4. Infrastructure Layer](#514-infrastructure-layer)
    - [5.1.5. Bounded Context Software Architecture Component Level Diagrams](#515-bounded-context-software-architecture-component-level-diagrams)
    - [5.1.6. Bounded Context Software Architecture Code Level Diagrams](#516-bounded-context-software-architecture-code-level-diagrams)
      - [5.1.6.1. Bounded Context Domain Layer Class Diagrams](#5161-bounded-context-domain-layer-class-diagrams)
      - [5.1.6.2. Bounded Context Database Design Diagram](#5162-bounded-context-database-design-diagram)
  - [5.2. Bounded Context: Deteccion](#52-bounded-context-deteccion)
    - [5.2.1. Domain Layer](#521-domain-layer)
    - [5.2.2. Interface Layer](#522-interface-layer)
    - [5.2.3. Application Layer](#523-application-layer)
    - [5.2.4. Infrastructure Layer](#524-infrastructure-layer)
    - [5.2.5. Bounded Context Software Architecture Component Level Diagrams](#525-bounded-context-software-architecture-component-level-diagrams)
    - [5.2.6. Bounded Context Software Architecture Code Level Diagrams](#526-bounded-context-software-architecture-code-level-diagrams)
      - [5.2.6.1. Bounded Context Domain Layer Class Diagrams](#5261-bounded-context-domain-layer-class-diagrams)
      - [5.2.6.2. Bounded Context Database Design Diagram](#5262-bounded-context-database-design-diagram)
  - [5.3. Bounded Context: Procesamiento](#53-bounded-context-procesamiento)
    - [5.3.1. Domain Layer](#531-domain-layer)
    - [5.3.2. Interface Layer](#532-interface-layer)
    - [5.3.3. Application Layer](#533-application-layer)
    - [5.3.4. Infrastructure Layer](#534-infrastructure-layer)
    - [5.3.5. Bounded Context Software Architecture Component Level Diagrams](#535-bounded-context-software-architecture-component-level-diagrams)
    - [5.3.6. Bounded Context Software Architecture Code Level Diagrams](#536-bounded-context-software-architecture-code-level-diagrams)
      - [5.3.6.1. Bounded Context Domain Layer Class Diagrams](#5361-bounded-context-domain-layer-class-diagrams)
      - [5.3.6.2. Bounded Context Database Design Diagram](#5362-bounded-context-database-design-diagram)
  - [5.4. Bounded Context: Resultados](#54-bounded-context-resultados)
    - [5.4.1. Domain Layer](#541-domain-layer)
    - [5.4.2. Interface Layer](#542-interface-layer)
    - [5.4.3. Application Layer](#543-application-layer)
    - [5.4.4. Infrastructure Layer](#544-infrastructure-layer)
    - [5.4.5. Bounded Context Software Architecture Component Level Diagrams](#545-bounded-context-software-architecture-component-level-diagrams)
    - [5.4.6. Bounded Context Software Architecture Code Level Diagrams](#546-bounded-context-software-architecture-code-level-diagrams)
      - [5.4.6.1. Bounded Context Domain Layer Class Diagrams](#5461-bounded-context-domain-layer-class-diagrams)
      - [5.4.6.2. Bounded Context Database Design Diagram](#5462-bounded-context-database-design-diagram)
- [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
  - [6.1. Style Guidelines](#61-style-guidelines)
    - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile \& Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.1. Labeling Systems](#621-labeling-systems)
    - [6.2.2. Searching Systems](#622-searching-systems)
    - [6.2.3. SEO Tags and Meta Tags](#623-seo-tags-and-meta-tags)
    - [6.2.4. Navigation Systems](#624-navigation-systems)
  - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    - [6.4.3. Application Mock-ups](#643-application-mock-ups)
    - [6.4.4. Applications User Flow Diagrams](#644-applications-user-flow-diagrams)
  - [6.5. Application Prototyping](#65-application-prototyping)
- [Capítulo VII: Product Implementation, Validation \& Deployment](#capítulo-vii-product-implementation-validation--deployment)
  - [7.1. Software Configuration Management](#71-software-configuration-management)
    - [7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)
    - [7.1.2. Source Code Management](#712-source-code-management)
    - [7.1.3. Source Code Style Guide \& Conventions](#713-source-code-style-guide--conventions)
    - [7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)
  - [7.2. Solution Implementation](#72-solution-implementation)
    - [7.2.1. Sprint 1](#721-sprint-1)
      - [7.2.1.1. Sprint Planning 1.](#7211-sprint-planning-1)
      - [7.2.1.2. Sprint Backlog 1.](#7212-sprint-backlog-1)
      - [7.2.1.3. Development Evidence for Sprint Review](#7213-development-evidence-for-sprint-review)
      - [7.2.1.4. Testing Suite Evidence for Sprint Review](#7214-testing-suite-evidence-for-sprint-review)
      - [7.2.1.5. Execution Evidence for Sprint Review](#7215-execution-evidence-for-sprint-review)
      - [7.2.1.6. Services Documentation Evidence for Sprint Review](#7216-services-documentation-evidence-for-sprint-review)
      - [7.2.1.7. Software Deployment Evidence for Sprint Review.](#7217-software-deployment-evidence-for-sprint-review)
      - [7.2.1.8. Team Collaboration Insights during Sprint](#7218-team-collaboration-insights-during-sprint)
  - [7.3. Validation Interviews](#73-validation-interviews)
    - [7.3.1. Diseño de entrevistas](#731-diseño-de-entrevistas)
    - [7.3.2. Registro de Entrevistas.](#732-registro-de-entrevistas)
    - [7.3.3. Evaluaciones según heurísticas.](#733-evaluaciones-según-heurísticas)
    - [7.4. Video About-the-Product.](#74-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome

| Criterio Específico | Acciones realizadas | Conclusiones |
|---------|---------|---------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | <br><br> **TB1** <br><br> **Andrés Doig Apostol** <br> Realizó el capítulo 1, identificando la problemática y necesidades de nuestro negocio. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Realizó el capítulo 2 del informe, teniendo que analizar el cómo serían las entrevistas y quiénes son nuestros competidores <br><br> **Christian Jose Zeta Valenzuela** <br> Realizó el capítulo 4 del informe, explicando el propósito del diseño, las herramientas usadas y las restricciones que tendrá el proyecto. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Realizó el capítulo 4, pensando en las User Stories y catalogándolas según su prioridad. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Realizó el capítulo 4 del informe, diseñando los bounded contexts del sistema y su arquitectura siguiendo el modelo C4.<br><br> **TP1** <br><br> **Andrés Doig Apostol** <br> Durante el proyecto, he presentado los resultados de manera clara y objetiva, adaptando mi lenguaje a diferentes especialidades y niveles jerárquicos, facilitando así la comprensión y toma de decisiones. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Realizó el diseño de wireframes y mockups del landing page y de la aplicación principal de nuestra solución de software. <br><br> **Christian Jose Zeta Valenzuela** <br> Apoyó en la creación de diseños de puntos claves de nuestra solución, como el landing page y la aplicación principal. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Durante el proyecto, he presentado los resultados de los sistemas de etiquetado, navegación, búsqueda y SEO de manera clara y objetiva, utilizando un lenguaje apropiado para que todos los participantes pudieran comprender y aportar en la toma de decisiones efectivas. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Realicé los diagramas de código de los bounded context. Para esto tuve que identificar los entities principales y los commandhandlers que se usarían. Asimismo, creé los diagramas de contenedores para cada bounded context. <br><br> **TB2** <br><br> **Andrés Doig Apostol** <br> Elaboré todo el condiguration management para el proyecto. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Elaboré los apartados ¿Quiénes Somos? y Contáctanos del landing page. <br><br> **Christian Jose Zeta Valenzuela** <br> Elaboré los apartados Producto y Enfoque del landing page. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Gestioné las reuniones para los sprints, así como el sprint planning y la documentación de este. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Creé el proyecto del landing page, configuré sus estilos y elaboré el apartado Inicio.  | **TB1** <br><br> Se realizaron los capítulos del 1 al 4, pensando desde qué oproblemática atacaríamos y cómo, hasta cómo plantearíamos la arquitectura de nuestra solución.<br><br>**TP1** <br><br> Se realizaron los capítulos 5 y 6. Esto conllevó a elaborar diseños de bajo nivel de cómo estarían compuestas las clases que constituirían los bounded contexts, así como crear los diseños de bases de datos. Asimismo, se pensó y materializó el diseño del landing page y la aplicación principal de nuestra solución de software.<br><br>**TB2** <br><br> Se materializó el diseño pensado para el landing page. Para esto se establecieron reglas y se documentó todo el proceso. |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | <br><br> **TB1** <br><br> **Andrés Doig Apostol** <br> Realizó el capítulo 1, identificando la problemática y necesidades de nuestro negocio. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Realizó el capítulo 2 del informe, teniendo que analizar el cómo serían las entrevistas y quiénes son nuestros competidores <br><br> **Christian Jose Zeta Valenzuela** <br> Realizó el capítulo 4 del informe, explicando el propósito del diseño, las herramientas usadas y las restricciones que tendrá el proyecto. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Realizó el capítulo 4, pensando en las User Stories y catalogándolas según su prioridad. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Realizó el capítulo 4 del informe, diseñando los bounded contexts del sistema y su arquitectura siguiendo el modelo C4.<br><br> **TP1** <br><br> **Andrés Doig Apostol** <br> Durante el proyecto, he presentado los resultados de manera clara y objetiva, adaptando mi lenguaje a diferentes especialidades y niveles jerárquicos, facilitando así la comprensión y toma de decisiones. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Realizó el diseño de wireframes y mockups del landing page y de la aplicación principal de nuestra solución de software. <br><br> **Christian Jose Zeta Valenzuela** <br> Apoyó en la creación de diseños de puntos claves de nuestra solución, como el landing page y la aplicación principal. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Durante el proyecto, he presentado los resultados de los sistemas de etiquetado, navegación, búsqueda y SEO de manera clara y objetiva, utilizando un lenguaje apropiado para que todos los participantes pudieran comprender y aportar en la toma de decisiones efectivas. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Realicé los diagramas de código de los bounded context. Para esto tuve que identificar los entities principales y los commandhandlers que se usarían. Asimismo, creé los diagramas de contenedores para cada bounded context. <br><br> **TB2** <br><br> **Andrés Doig Apostol** <br> Elaboré todo el condiguration management para el proyecto. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Elaboré los apartados ¿Quiénes Somos? y Contáctanos del landing page. <br><br> **Christian Jose Zeta Valenzuela** <br> Elaboré los apartados Producto y Enfoque del landing page. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Gestioné las reuniones para los sprints, así como el sprint planning y la documentación de este. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Creé el proyecto del landing page, configuré sus estilos y elaboré el apartado Inicio.  | **TB1** <br><br> Se realizaron los capítulos del 1 al 4, pensando desde qué oproblemática atacaríamos y cómo, hasta cómo plantearíamos la arquitectura de nuestra solución.<br><br>**TP1** <br><br> Se realizaron los capítulos 5 y 6. Esto conllevó a elaborar diseños de bajo nivel de cómo estarían compuestas las clases que constituirían los bounded contexts, así como crear los diseños de bases de datos. Asimismo, se pensó y materializó el diseño del landing page y la aplicación principal de nuestra solución de software.<br><br>**TB2** <br><br> Se materializó el diseño pensado para el landing page. Para esto se establecieron reglas y se documentó todo el proceso. |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestra startup tiene como misión mejorar la calidad de la investigación de mercado a través de tecnología avanzada que elimina el sesgo humano. Nos enfocamos en el desarrollo de una aplicación de escritorio que utiliza una cámara para registrar y analizar los gestos faciales de los participantes durante la prueba de productos. Esta solución automatiza el análisis de expresiones, proporcionando información más objetiva y útil para la toma de decisiones empresariales.

**Misión**

Nuestra misión es revolucionar la investigación de mercado al aplicar tecnología de análisis facial avanzada que elimina el sesgo humano, permitiendo a las empresas tomar decisiones más informadas y efectivas. Nos comprometemos a proporcionar herramientas innovadoras que automatizan el análisis de expresiones faciales, generando insights precisos y objetivos que impulsan el éxito empresarial.

**Visión**

Nuestra visión es ser líderes en tecnología de análisis facial, transformando la forma en que las empresas comprenden y responden a las necesidades y emociones de sus consumidores. Aspiramos a empoderar a las empresas con soluciones tecnológicas de vanguardia que optimicen sus estrategias de mercado y contribuyan al desarrollo económico.

### 1.1.2. Perfiles de integrantes del equipo

**Andrés Doig Apostol (u201712256)**

![Imagen](https://i.gyazo.com/c3e313672aa39db67fd7e511958c73db.jpg)

**Alonso Fernando Robles Astuñaupa (u202112662)**

![Imgur](https://i.imgur.com/GHaRGNq.png)

**Christian Jose Zeta Valenzuela (u202011688)**

![Imgur](https://i.gyazo.com/17277169ee7a560ba0659d35259d8215.jpg)

**Dámaris Jemima Tasayco Vilcamiza (u202119605)**

![Imgur](https://i.gyazo.com/068f2d92cb7f0aef736a6630391fca15.jpg)

**Erick Gabriel Urbizagastegui Alvarez (u20201e465)**

![Imgur](https://i.gyazo.com/dfe1d07a5f4f455fa469181c9726bfe2.jpg)

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

**Who ¿Quiénes van a ser los beneficiarios?**
  
- El problema afecta principalmente a empresas y equipos de marketing que utilizan focus groups para recopilar opiniones y reacciones de los consumidores durante la fase de pruebas de nuevos productos. Estas organizaciones dependen de datos precisos para mejorar sus productos y estrategias de mercado.

**What ¿Cuál es el problema?**

- El desafío radica en la falta de confiabilidad de las opiniones subjetivas expresadas por los participantes en focus groups. Los sesgos conscientes e inconscientes de los participantes, como el deseo de complacer al facilitador o de ajustarse a la norma social, generan datos que no reflejan con precisión las verdaderas emociones o preferencias. Como resultado, las decisiones empresariales se ven comprometidas.

**Where ¿Dónde se originó el problema?**
  
- La situación se presenta en entornos de investigación de mercado, como focus groups o pruebas de productos organizadas por empresas de diversos sectores, tanto presenciales como virtuales. Estos estudios suelen llevarse a cabo en laboratorios de mercado o entornos controlados.


**When ¿Cuándo se originó el problema?**

- Este problema ocurre durante las pruebas de productos en las etapas iniciales del ciclo de vida de un producto, cuando las empresas buscan obtener retroalimentación de los consumidores para ajustar sus estrategias de diseño, marketing o comercialización.

**Why ¿Por qué se originó el problema?**

- El problema surge porque los métodos tradicionales de recopilación de datos se basan en las expresiones verbales de los participantes, las cuales no siempre representan sus verdaderos sentimientos o reacciones. Las empresas necesitan datos confiables para tomar decisiones de diseño y comercialización informadas, pero los datos sesgados dificultan esta tarea.

**How ¿Cómo debe hacerse?**
- Actualmente, las empresas utilizan encuestas y sesiones de focus groups donde los participantes verbalizan sus opiniones, pero este método no es adecuado para capturar las reacciones emocionales auténticas. Existe una necesidad de automatizar el proceso de captura de reacciones emocionales para reducir el impacto del sesgo humano y obtener datos más precisos.

**How Much ¿Cómo el costo influye en la problemática?**

- El impacto de este problema es significativo, ya que la falta de precisión en los datos puede llevar a decisiones equivocadas en las fases de diseño y marketing, afectando los resultados comerciales. Además, las empresas invierten tiempo y recursos considerables en realizar estudios de mercado que no siempre proporcionan un retorno de valor en términos de información confiable.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1:**<br>
En el ámbito de la investigación de mercado, las empresas enfrentan el reto de obtener retroalimentación auténtica y confiable de los consumidores durante las pruebas de productos. Los métodos tradicionales, como los focus groups, dependen en gran medida de las opiniones verbales de los participantes, las cuales pueden ser influenciadas por sesgos conscientes e inconscientes, lo que resulta en datos inexactos o poco fiables. Este problema compromete la capacidad de las empresas para tomar decisiones informadas sobre el diseño y comercialización de sus productos.
¿Cómo podemos desarrollar una solución tecnológica que permita a las empresas capturar y analizar de manera precisa las emociones y reacciones de los consumidores mediante el uso de cámaras y algoritmos de reconocimiento facial, mejorando la fiabilidad de los estudios de mercado y reduciendo el impacto de los sesgos humanos?

**Problem Statement 2:**<br>
Las empresas que buscan lanzar nuevos productos al mercado dependen en gran medida de las reacciones de los consumidores para validar sus decisiones de diseño y marketing. Sin embargo, los métodos actuales de recolección de datos en focus groups y encuestas están sujetos a sesgos de comportamiento y de cortesía, donde los participantes podrían no expresar sus verdaderas opiniones. Esta falta de autenticidad en las respuestas compromete la capacidad de las empresas para obtener información precisa, lo que puede llevar a errores en las decisiones estratégicas y a productos que no cumplen con las expectativas del mercado.
¿Cómo podemos crear una solución que, a través de la detección y el análisis de gestos faciales, permita a las empresas obtener retroalimentación auténtica y sin sesgos de los consumidores, brindando así información más confiable para el desarrollo y la comercialización de productos?

**Problem Statement 3:**<br>
En la era digital, las empresas necesitan procesar grandes volúmenes de datos de forma rápida y eficaz para mejorar sus productos y servicios. Sin embargo, las técnicas tradicionales de análisis de focus groups implican procesos manuales que son lentos, subjetivos y requieren expertos que interpreten las emociones y reacciones de los participantes. Este enfoque no solo es ineficiente, sino que también deja espacio para la interpretación sesgada de los resultados, lo que puede afectar negativamente la toma de decisiones.

***¿Cómo podemos desarrollar una solución automatizada que capture y analice gestos faciales en tiempo real durante las pruebas de productos, permitiendo a las empresas obtener resultados rápidos, objetivos y libres de interpretación humana, mejorando así la eficiencia y la precisión en el análisis de la respuesta del consumidor?***

#### 1.2.2.2. Lean UX Assumptions

- Asumimos que las reacciones faciales son un indicador confiable de las emociones y preferencias de los consumidores durante las pruebas de productos.

- Asumimos que los equipos de marketing y diseño de productos tienen la capacidad técnica necesaria para implementar una solución de análisis de gestos faciales sin requerir formación especializada.

- Asumimos que las empresas valoran los resultados rápidos y precisos de estudios de mercado y están dispuestas a adoptar soluciones que mejoren la eficiencia de estos procesos.

- Asumimos que las empresas innovadoras que lanzan productos nuevos necesitan una solución que elimine el sesgo humano en las pruebas de productos y que estarán dispuestas a invertir en esta tecnología.

- Asumimos que las agencias de investigación de mercado buscan formas de mejorar la precisión de sus estudios para proporcionar datos más valiosos a sus clientes empresariales.

- Asumimos que los análisis automatizados de expresiones faciales son lo suficientemente precisos como para reducir significativamente el tiempo y esfuerzo requeridos para interpretar los resultados de un focus group.

- Asumimos que las empresas están cada vez más abiertas a realizar estudios de mercado de manera remota, utilizando tecnologías de videoconferencia junto con análisis automatizados de reacciones emocionales.

- Asumimos que las empresas ven valor en la capacidad de almacenar y comparar datos históricos de las reacciones emocionales de los consumidores para analizar tendencias a lo largo del tiempo.

- Asumimos que las políticas de privacidad y seguridad de datos son una preocupación clave para las empresas y que cumplir con estos estándares será crucial para que confíen en nuestra solución.

- Asumimos que una prueba gratuita de nuestra solución permitirá a las empresas experimentar el valor de nuestra tecnología, lo que aumentará su disposición a adoptarla en sus procesos regulares de investigación de mercado.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis 1:**<br>
Creemos que si utilizamos cámaras para registrar gestos faciales durante las pruebas de productos, entonces capturaremos reacciones emocionales más auténticas y reduciremos el sesgo en la retroalimentación.

**Hypothesis 2:**<br>
Creemos que si desarrollamos una aplicación intuitiva y fácil de usar, entonces los equipos de marketing podrán implementar la tecnología sin necesidad de formación técnica avanzada.

**Hypothesis 3:**<br>
Creemos que si la aplicación detecta y analiza gestos faciales en tiempo real, entonces los resultados del estudio de mercado serán más rápidos y precisos.

**Hypothesis 4:**<br>
Creemos que si nos enfocamos en empresas que lanzan productos innovadores, entonces tendremos un segmento clave que valorará la objetividad y la precisión de los datos de focus groups.

**Hypothesis 5:**<br>
Creemos que si ofrecemos la solución a agencias de investigación de mercado, entonces podrán mejorar la calidad de los estudios para sus clientes empresariales.

**Hypothesis 6:**<br>
Creemos que si integramos análisis automatizados de gestos faciales con informes detallados, entonces reduciremos el tiempo de análisis que actualmente requieren los focus groups tradicionales.

**Hypothesis 7:**<br>
Creemos que si la solución es compatible con sistemas de videoconferencia, entonces las empresas podrán realizar estudios de mercado de forma remota sin perder precisión en la captura de reacciones.

**Hypothesis 8:**<br>
Creemos que si el sistema puede almacenar y comparar datos históricos de expresiones faciales, entonces las empresas podrán analizar cambios de tendencias emocionales a lo largo del tiempo.

**Hypothesis 9:**<br>
Creemos que si la aplicación cumple con estrictos estándares de privacidad y seguridad de datos, entonces las empresas confiarán en el uso de nuestra tecnología para estudios confidenciales.

**Hypothesis 10:**<br>
Creemos que si dirigimos nuestra solución a equipos de marketing y diseño de producto en empresas entre medianas y grandes, entonces capturaremos un segmento con los recursos para invertir en tecnología avanzada de análisis de mercado.

**Hypothesis 11:**<br>
Creemos que si automatizamos la identificación de gestos faciales clave asociados con emociones específicas, entonces las empresas obtendrán una mayor claridad sobre la percepción emocional de sus productos.

**Hypothesis 12:**<br>
Creemos que si desarrollamos una interfaz de usuario altamente visual y basada en gráficos para los informes, entonces los usuarios podrán interpretar fácilmente los resultados de los estudios.

**Hypothesis 13:**<br>
Creemos que si nuestra solución reduce los tiempos de análisis de focus groups en un 50%, entonces las empresas podrán realizar más estudios en menos tiempo y tomar decisiones más rápidas.

**Hypothesis 14:**<br>
Creemos que si integramos nuestra aplicación con herramientas de CRM (Customer Relationship Management), entonces las empresas podrán vincular las emociones de los consumidores directamente con las ventas y el comportamiento posterior.

**Hypothesis 15:**<br>
Creemos que si ofrecemos una prueba gratuita de nuestra solución para empresas, entonces más organizaciones estarán dispuestas a probar la tecnología y convertirla en una parte integral de sus procesos de investigación de mercado.

#### 1.2.2.4. Lean UX Canvas 

![Imagen](https://i.gyazo.com/9d2f4b9a77e9b73e606df73e1ac4bbe0.jpg)

## 1.3. Segmentos objetivo

El principal segmento objetivo de nuestra solución son los empresarios que buscan mejorar la precisión de los estudios de mercado. Estos usuarios requieren datos confiables para tomar decisiones informadas sobre la dirección de sus productos. Al ofrecer una herramienta que automatiza el análisis de las emociones de los consumidores, apuntamos a empresas que valoran la innovación tecnológica y la optimización de sus procesos de investigación de mercado.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

![Imagen](https://i.gyazo.com/e974aec0594ac11cf43748a7e0f987f4.png)
![Imagen](https://gyazo.com/30a37a8184c263855504b0a8d50f57d2.png)
![Imagen](https://gyazo.com/5aabe722ac58484b17d0e55dda5a59b5.png)
![Imagen](https://gyazo.com/1565fef3ca6707ffa1173afb592c5aed.png)

### 2.1.2. Estrategias y tácticas frente a competidores

**Diferenciación en Características:**<br>
- Estrategia: Desarrollar características únicas en FacialTruth que no estén presentes en los productos de la competencia.
- Táctica: Implementa funciones adicionales como integración con otros dispositivos.

**Enfoque en la Experiencia del Usuario:**<br>
- Estrategia: Ofrece una experiencia de usuario superior a través de la simplicidad y la facilidad de uso.
- Táctica: Diseña una interfaz de usuario intuitiva en la aplicación de escritorio, proporcionar soporte técnico accesible, y asegurar una instalación y configuración sin problemas

**Estrategia de Precios Competitivos:**<br>
- Estrategia: Establece una estrategia de precios que ofrezca una buena relación calidad-precio en comparación con los competidores.
- Táctica: Ofrece un servicio gratuito

**Estrategia de Asociaciones y Colaboraciones:**<br>
- Estrategia: Forma alianzas con empresas de tecnología o publicidad para aumentar la visibilidad y credibilidad del producto.
- Táctica: Colaborar con marcas, empresas o productos notables  para validar la eficacia del dispositivo y utilizar sus recomendaciones en campañas de marketing, o establecer alianzas estratégicas para ofrecer FacialTruth a los clientes.

**Campañas de Marketing y Educación:**<br>
- Estrategia: Realiza campañas de marketing dirigidas y programas educativos para aumentar la conciencia sobre la importancia de un correcto análisis de la información  y los beneficios de FacialTruth.
- Táctica: Utilizar publicidad en redes sociales, blogs de comunicaciones, y webinars para educar a los consumidores sobre los beneficios de un correcto estudio de mercado, y destacar cómo FacialTruth puede mejorar ese proceso.
     
## 2.2. Entrevistas 

### 2.2.1. Diseño de entrevistas

**Preguntas a empresarios**<br>
- ¿Cómo llevas a cabo actualmente la evaluación de nuevos productos antes de lanzarlos al mercado?
- ¿Qué herramientas o métodos utilizas para recoger opiniones de los consumidores sobre tus productos?
- ¿Cuáles son las principales dificultades que enfrentas al interpretar las opiniones de los focus groups?
- ¿Qué tan confiables son las opiniones que recibes actualmente sobre tus productos?
- ¿Has experimentado casos en los que la información obtenida en un focus group no se alineó con la aceptación real del producto en el mercado?
- ¿Qué aspectos te gustaría mejorar en el proceso de evaluación de tus productos?
- ¿Cómo te gustaría que una herramienta tecnológica agregue o mejore el trabajo de los focus groups tradicionales?
- ¿Qué tipo de resultados o insights te gustaría obtener de una herramienta que analiza gestos faciales? (e.g., reportes detallados, gráficos, alertas automáticas)
- ¿Crees que una solución basada en el análisis de gestos faciales sería bien recibida por otros emprendedores o empresas en tu sector?
- ¿Cómo crees que esta solución podría impactar la forma en que lanzas productos en el futuro?

### 2.2.2. Registro de entrevistas

Video de entrevistas: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EW67S70zZghIs5hZuvG582oBf4XPFGoNE1kYVbqRKvANBg?e=o2LFMn](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EW67S70zZghIs5hZuvG582oBf4XPFGoNE1kYVbqRKvANBg?e=o2LFMn)

**Entrevista 1**

![Imagen](https://i.gyazo.com/52fca163a4951167963578e286918102.png)

**Entrevistador**: Christian Jose Zeta Valenzuela

**Entrevistado**: Humberto Martinez

**Timing**: 00:00

**Resumen de la entrevista**: Durante la entrevista, se discutieron aspectos clave sobre la evaluación de productos y la recopilación de información de usuarios para mejorar la experiencia del cliente. La empresa utiliza herramientas como DataDog para monitorear el uso de funcionalidades y colabora estrechamente con el equipo de producto para definir métricas. Sin embargo, mapear y programar estos elementos presenta desafíos significativos. Aunque una solución tecnológica para analizar gestos faciales es interesante, se considera que sería costosa y difícil de sostener. A pesar de que las opiniones de los focus groups son valiosas, a veces no se alinean con la aceptación real del producto en el mercado, y se reconoció la necesidad de mejorar en la interpretación y uso de estos datos para la evolución de los productos.

**Entrevista 2**

![Imagen](https://i.gyazo.com/02e0e11de29a34c5911c2bf99edfded2.png)

**Entrevistador**: Erick Gabriel Urbizagastegui Alvarez

**Entrevistado**: Salvador Torres

**Timing**: 05:36

**Resumen de la entrevista**: Durante la entrevista con Salvador Torre, se abordaron sus métodos para evaluar productos, destacando que generalmente consulta con familiares o amigos cercanos y no utiliza herramientas formales, solo redes sociales o comunicación oral. Sin embargo, enfrenta el problema de que algunas personas no son completamente transparentes en sus opiniones sobre sus productos. Salvador vende barras energéticas y ha tenido experiencias negativas en el pasado donde no logró vender sus productos. Considera que la idea de abordar el sesgo humano es prometedora y podría ayudar a impulsar su microempresa, mejorando sus ventas y llevando su negocio al siguiente nivel.

**Entrevista 3**

![Imagen](https://i.gyazo.com/835c3087322da09fc808405919d6c4c3.png)

**Entrevistador**: Erick Gabriel Urbizagastegui Alvarez

**Entrevistado**: Valeria Nevado

**Timing**: 15:03

**Resumen de la entrevista**: En la entrevista con Valeria Navarro, se discutió su enfoque para recolectar opiniones sobre su producto en su pequeña empresa. Valeria suele consultar a familiares o compañeros, y utiliza principalmente redes sociales o interacciones directas para obtener comentarios. Sin embargo, enfrenta dificultades en la recolección de opiniones, ya que no siempre son 100% transparentes y a veces son contradictorias, lo que complica su interpretación. A pesar de estos desafíos, Valeria considera que la idea de una aplicación que aborde el sesgo humano podría ser una excelente herramienta para mejorar su negocio.

### 2.2.3. Análisis de entrevistas 

En las entrevistas, se destacó un patrón común en la evaluación de productos y la recopilación de información de usuarios. Humberto Martínez mencionó el uso de herramientas como DataDog para monitorear funcionalidades, pero enfrentó desafíos con el mapeo y programación, y cuestionó la viabilidad de soluciones tecnológicas complejas como el análisis de gestos faciales. Salvador Torres y Valeria Navarro, por su parte, recurren a métodos informales como consultas con familiares y redes sociales, pero enfrentan problemas con la falta de transparencia y opiniones contradictorias. Ambos ven potencial en abordar el sesgo humano para mejorar sus negocios, sugiriendo que nuevas tecnologías o enfoques podrían optimizar la interpretación y uso de datos en la evolución de productos.

## 2.3. Needfinding

### 2.3.1. User Personas

![Imagen](https://i.gyazo.com/473836f5dfa9f76ac64e411eab15599a.png)

### 2.3.2. User Task Matrix

![Imagen](https://gyazo.com/7c3997254860e720f3c30fd037053b7c.png)

### 2.3.3. Empathy Mapping

![Imagen](https://i.gyazo.com/02d3b73742bb53e541daa3013a9e5683.png)

### 2.3.4. As-is Scenario Mapping

![Imagen](https://i.gyazo.com/f014f86a0b88709c1777114f2212879d.png)

## 2.4. Ubiquitous Language

Dada la naturaleza de la solución existen términos que posiblemente para diversos individuos tengan conceptos diferentes, por ello, en está sección se definirán los conceptos claves con la finalidad de evitar malentendidos.

- Participantes: Personas elegidas para realizar una prueba de productos, interactuando y proporcionando reacciones de esta misma.
- Prueba de productos: Actividad en la que se presenta un producto, con la finalidad de evaluar la experiencia y reacciones de los participantes.
- Análisis de datos: Proceso de revisar e interpretar la información recolectada en las actividades propuestas.
- Informe: Documento que resumen los hallazgos, incluyendo gráficos, recomendaciones o lo que se considere necesario.
- Reacción de los participantes: Respuestas emocionales y comportamientos de un individuo envase a un estímulo.
- Patrón de comportamiento: Tendencias recurrentes en las reacciones de los participantes.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

![Imagen](https://gyazo.com/5213a5fe6d886002678372c21a743907.png)

## 3.2. User Stories

![Imagen](https://gyazo.com/203a1ab8021096505f803427b8182788.png)
![Imagen](https://gyazo.com/16b0bde03beb5e352d57928ca411e85a.png)
![Imagen](https://gyazo.com/8f6d8961ec3b21c2cc8cf740771a45ed.png)
![Imagen](https://gyazo.com/716f5e2163db791bda6888ea8f303a54.png)
![Imagen](https://gyazo.com/36640e697aef518ad7ed60fdf57f1e10.png)
![Imagen](https://gyazo.com/dd11783ef5ef3374efd66652211ebd6b.png)
![Imagen](https://gyazo.com/e427e20246675585d0944d3362232685.png)
![Imagen](https://gyazo.com/6348ca9923c9e138ffe981ae646c8dc3.png)
![Imagen](https://gyazo.com/327ec45934f11e05fe090c36435a006a.png)
![Imagen](https://gyazo.com/c998ddf5e8efb5e78b59ae51218e5c55.png)
![Imagen](https://gyazo.com/3b9a131c0ecd61a75df65fa7059dda15.png)

## 3.3. Impact Mapping

![Imagen](https://gyazo.com/9ab8631e9867dea0b2861425c1766a9a.png)

## 3.4. Product Backlog

![Imagen](https://gyazo.com/888856ba686846b016839c8251797c0f.png)
![Imagen](https://gyazo.com/9e411dee1614596f83d23e1093274ff9.png)
![Imagen](https://gyazo.com/d7e53319bc640ffdf12c9434da74922c.png)
![Imagen](https://gyazo.com/1b868aa471ead446e913de2c449a38ae.png)

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design
### 4.1.1. Design Purpose

**Propósito del Diseño**

El propósito del diseño estratégico es crear una solución automatizada para el análisis de gestos faciales que elimine el sesgo humano y proporcione datos precisos en estudios de mercado. Esta solución busca ofrecer a las empresas una herramienta confiable para la captura y análisis de emociones durante las pruebas de productos, mejorando la calidad y precisión de los datos recolectados.

### 4.1.2. Attribute-Driven Design Inputs**

#### 4.1.2.1. Primary Functionality (Primary User Stories)

En esta sección se especifican las User Stories que tienen mayor relevancia en términos de requisitos funcionales y que impactan la arquitectura de la solución. Estas historias son fundamentales para la operación del sistema y han sido seleccionadas debido a su importancia en las decisiones de diseño.

![Imagen](https://gyazo.com/d83c65c71d32b70725edde2dbfef5445.png)
![Imagen](https://gyazo.com/e51060bffcb29209ee7c1d319e5c981a.png)
![Imagen](https://gyazo.com/847d86ac0b4a2e95fb3564f4fc33bd04.png)
![Imagen](https://gyazo.com/9d9bd1738bebbc6fef57ff3adfe737cb.png)

#### 4.1.2.2. Quality Attribute Scenarios

**Scenario 1: Performance**

- Atributo: Tiempo de respuesta
- Estímulo: El participante realiza una expresión facial
- Artefacto: Sistema de análisis facial
- Entorno: Entorno estándar de prueba
- Respuesta: El sistema debe procesar y mostrar los resultados de la expresión facial en menos de 2 segundos.
- Medida: Tiempo desde la captura hasta la visualización del resultado.

**Scenario 2: Security**

- Atributo: Protección de datos
- Estímulo: Intento de acceso no autorizado a los datos
- Artefacto: Base de datos PostgreSQL
- Entorno: Red de acceso remoto
- Respuesta: El sistema debe bloquear accesos no autorizados y alertar al administrador.
- Medida: Número de intentos fallidos y alertas generadas.

**Scenario 3: Usability**

- Atributo: Facilidad de uso
- Estímulo: Interacción con la interfaz de usuario
- Artefacto: Interfaz desarrollada con PyQt6
- Entorno: Entorno de prueba con usuarios reales
- Respuesta: La interfaz debe permitir completar tareas en menos de 5 minutos.
- Medida: Tiempo promedio para completar tareas y retroalimentación de usuarios.

#### 4.1.2.3. Constraints

- Restricción 1: La aplicación debe funcionar en sistemas operativos Windows y Linux, utilizando PyQt6 para la interfaz gráfica.
- Restricción 2: La solución debe integrar el análisis de gestos faciales mediante Pyfeat, asegurando compatibilidad y eficiencia.
- Restricción 3: Los datos deben ser almacenados en una base de datos PostgreSQL, cumpliendo con las normativas de privacidad y seguridad de datos.
- Restricción 4: La aplicación debe garantizar un rendimiento adecuado incluso con grandes volúmenes de datos y mantener una alta precisión en el análisis facial.

### 4.1.3. Architectural Drivers Backlog

**Driver 1: Precisión en el Análisis Facial**

- Descripción: La precisión en la detección y análisis de gestos faciales es crucial para la validez de los estudios de mercado.
- Importancia para Stakeholders: Alta
- Impacto en Architecture Technical Complexity: Alta

**Driver 2: Rendimiento y Tiempo de Respuesta**

- Descripción: El sistema debe procesar y reportar los resultados rápidamente para ser útil en pruebas de productos en tiempo real.
- Importancia para Stakeholders: Alta
- Impacto en Architecture Technical Complexity: Media

**Driver 3: Seguridad de Datos**

- Descripción: Protección de datos personales y resultados de las pruebas contra accesos no autorizados y cumplir con las normativas de privacidad.
- Importancia para Stakeholders: Alta
- Impacto en Architecture Technical Complexity: Alta

### 4.1.4. Architectural Design Decisions

- Decisión 1: Implementar el análisis facial con Pyfeat, dado su enfoque especializado en el procesamiento de datos faciales.
- Decisión 2: Utilizar PyQt6 para desarrollar una interfaz de usuario intuitiva y compatible con múltiples plataformas.
- Decisión 3: Almacenar los datos en PostgreSQL para asegurar una base de datos robusta y segura.
- Decisión 4: Implementar algoritmos de reconocimiento facial que proporcionen resultados en tiempo real para mejorar la eficiencia de los estudios de mercado.

### 4.1.5. Quality Attribute Scenario Refinements

**Scenario Refinement for Performance**

- Scenario(s): Rendimiento en el análisis de gestos faciales
- Business Goals: Asegurar respuestas rápidas durante las pruebas de productos.
- Relevant Quality Attributes: Tiempo de respuesta
- Stimulus: Captura de una expresión facial del participante
- Scenario Components: Procesamiento y visualización del resultado en menos de 2 segundos.
- Stimulus Source: Participante
- Environment: Entorno de prueba con condiciones normales de cámara
- Artifact (if Known): Sistema de análisis facial
- Response: Resultados precisos y rápidos.
- Response Measure: Tiempo desde la captura hasta la visualización del resultado.
- Questions: ¿El sistema mantiene el tiempo de respuesta requerido bajo diferentes condiciones?
- Issues: Evaluar la consistencia en el rendimiento con diferentes volúmenes de datos.

**Scenario Refinement for Security**

- Scenario(s): Seguridad en el manejo de datos
- Business Goals: Proteger los datos personales y cumplir con regulaciones de privacidad.
- Relevant Quality Attributes: Protección de datos
- Stimulus: Intentos de acceso no autorizado
- Scenario Components: Bloqueo de acceso no autorizado y generación de alertas.
- Stimulus Source: Usuario externo
- Environment: Red de acceso remoto
- Artifact (if Known): Base de datos PostgreSQL
- Response: Bloqueo y alerta de accesos no autorizados.
- Response Measure: Número de intentos fallidos y alertas generadas.
- Questions: ¿Cómo se gestiona y se informa sobre los intentos de acceso no autorizado?
- Issues: Verificar la robustez de las medidas de seguridad implementadas.

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. Event Storming

![Imagen](https://gyazo.com/75e9a1c084eb6c2ebb37b8493cfadb87.png)

### 4.2.2. Candidate Context Discovery

Se realizó un event-storming como equipo y se lograron identificar los siguientes 4 bounded contexts:
- Sesión: Se encarga de gestionar la creación y finalización de las sesiones de registro de gestos faciales.
- Detección: Se encarga de ubicar la cara del usuario y registrar los gestos faciales que este haga.
- Procesamiento: Se encarga de procesar los datos que reciba de la detección de gestos faciales para generar conclusiones.
- Resultados: Se encarga de registrar los resultados obtenidos durante la sesión.

![Imagen](https://gyazo.com/48452c777f0d11318209574796a5a0a5.png)

### 4.2.3. Domain Message Flows Modeling

**Iniciar detección de gestos faciales**

![Imagen](https://gyazo.com/8438e11684422fcff18ecb1e4699c32d.jpg)

Para iniciar la detección de gestos faciales, el usuario deberá interactuar con la interfaz gráfica de usuario de la aplicación de escritorio. De esta forma, podrá iniciar la sesión de evaluación, la cual, a su vez, registrará la fecha y hora en la que se está generando esta misma. Luego de esto, el bounded context de Sesión enviará una orden al bounded context de Detección para iniciar la detección facial, y luego iniciar la detección de gestos faciales.

**Finalizar detección de gestos faciales**

![Imagen](https://gyazo.com/2023a48d080f86d02f5cb067d2985134.jpg)

Para finalizar la detección de gestos faciales, el usuario deberá interactuar con la interfaz gráfica de usuario de la aplicación de escritorio. De esta forma, podrá finalizar la sesión, y esta, a su vez, registrará la fecha y hora de finalización, para posteriormente enviar, al bounded context de Detección, órdenes de finalización de detección facial y de envío de datos crudos al módulo de procesamiento.

**Procesar datos obtenidos**

![Imagen](https://gyazo.com/4a2f54305c4121651e4f005d253a8bd9.jpg)

Para procesar los datos obtenidos de la detección de gestos faciales, el bounded context de Detección enviará estos datos crudos al bounded context de Procesamiento junto a una orden para iniciar el procesamiento de los datos. Una vez el bounded context de Procesamiento haya recibido la orden, usará los datos de la detección facial para obtener las métricas de cuales han sido los gestos faciales más prevalecientes, las conclusiones y un resumen general.

**Registrar resultados obtenidos**

![Imagen](https://gyazo.com/42b083c6f7f751729afefd776220680e.jpg)

Para registrar los resultados obtenidos durante la evaluación, el bounded context de Procesamiento enviará una orden al bounded context de Resultados para registrar las conclusiones y el resumen generado en la base de datos de la aplicación.

### 4.2.4. Bounded Context Canvases

**Sesión**

![Imagen](https://gyazo.com/3f5f24b7d6e859c20a0c3b3e7253df5c.jpg)

**Detección**

![Imagen](https://gyazo.com/6ccc82e10796345f42512429a1651910.jpg)

**Procesamiento**

![Imagen](https://gyazo.com/f0d6557493052d5411fee8128615eedb.jpg)

**Resultados**

![Imagen](https://gyazo.com/6fbb9ab4ecf8101ea3b0d62a937db3dc.jpg)

### 4.2.5. Context Mapping

![Imagen](https://gyazo.com/027a6d917076e435405ad29b81f20327.jpg)

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

![Imagen](https://gyazo.com/f84a41544f1cb522b8634148c79dce82.png)

### 4.3.2. Software Architecture Context Level Diagrams

![Imagen](https://gyazo.com/96e2773d5e555e41fe5b65b06ec3a92f.png)

### 4.3.3. Software Architecture Container Level Diagrams

![Imagen](https://gyazo.com/093fd0a839e9067ed5558d96fe401b65.png)

### 4.3.4. Software Architecture Deployment Diagrams

![Imagen](https://gyazo.com/034013a5645fc76e92a54617dc83bef9.png)

# Capítulo V: Tactical-Level Software Design

## 5.1. Bounded Context: Sesion

### 5.1.1. Domain Layer

**Entities**

- Sesion

**Interfaces**

- ISesionRepository
- ISesionService

### 5.1.2. Interface Layer

**Controllers**

- SesionsController

### 5.1.3. Application Layer

**Command Handlers**

- CrearSesionCommandHandler
- FinalizarSesionCommandHandler

### 5.1.4. Infrastructure Layer

Este bounded context no se comunica con un sistema externo.

### 5.1.5. Bounded Context Software Architecture Component Level Diagrams

![](https://gyazo.com/eca8d4e45945bffb986afccc2ee7ebdc.jpg)

### 5.1.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.1.6.1. Bounded Context Domain Layer Class Diagrams

![](https://gyazo.com/2c3ec586c6b7df5f556a88975e863cfa.png)

#### 5.1.6.2. Bounded Context Database Design Diagram

![](https://gyazo.com/d999417b427a4ddfddd5a4acf1435ffc.png)

## 5.2. Bounded Context: Deteccion

### 5.2.1. Domain Layer

**Entities**

- Deteccion

**Interfaces**

- IDeteccionRepository
- IDeteccionService

### 5.2.2. Interface Layer

**Controllers**

- DeteccionesController

### 5.2.3. Application Layer

**Command Handlers**

- RegistrarDeteccionCommandHandler

### 5.2.4. Infrastructure Layer

Este bounded context no se comunica con un sistema externo.

### 5.2.5. Bounded Context Software Architecture Component Level Diagrams

![](https://gyazo.com/257486ed212eee44996ece9f4429f548.jpg)

### 5.2.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.2.6.1. Bounded Context Domain Layer Class Diagrams

![](https://gyazo.com/ec4f8b23bd86403ff1fee7f507ab1caa.png)

#### 5.2.6.2. Bounded Context Database Design Diagram

![](https://gyazo.com/89501543c83db7f7646e4a0cdcf61295.png)

## 5.3. Bounded Context: Procesamiento

### 5.3.1. Domain Layer

**Entities**

- Procesamiento

**Interfaces**

- IProcesamientoRepository
- IProcesamientoService

### 5.3.2. Interface Layer

**Controllers**

- ProcesamientosController

### 5.3.3. Application Layer

**Command Handlers**

- ProcesarDeteccionCommandHandler

### 5.3.4. Infrastructure Layer

Este bounded context no se comunica con un sistema externo.

### 5.3.5. Bounded Context Software Architecture Component Level Diagrams

![](https://gyazo.com/964f4abe433abf34e729d252aea6c087.jpg)

### 5.3.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.3.6.1. Bounded Context Domain Layer Class Diagrams

![](https://gyazo.com/18a484642fc7f77f6e4513a714cb1da7.png)

#### 5.3.6.2. Bounded Context Database Design Diagram

![](https://gyazo.com/d0f62cb97f5180bae5a946a0bdf96cb1.png)

## 5.4. Bounded Context: Resultados

### 5.4.1. Domain Layer

**Entities**

- Resultado

**Interfaces**

- IResultadoRepository
- IResultadoService

### 5.4.2. Interface Layer

**Controllers**

- ResultadosController

### 5.4.3. Application Layer

**Command Handlers**

- GuardarResultadoCommandHandler

### 5.4.4. Infrastructure Layer

Este bounded context no se comunica con un sistema externo.

### 5.4.5. Bounded Context Software Architecture Component Level Diagrams

![](https://gyazo.com/5e6faa3492adb98f114861e29e057917.jpg)

### 5.4.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.4.6.1. Bounded Context Domain Layer Class Diagrams

![](https://gyazo.com/1774d07d6f61657a62b8adf822b97657.png)

#### 5.4.6.2. Bounded Context Database Design Diagram

![](https://gyazo.com/92e23ea6019b2c2f2f531d0808791bbd.png)

# Capítulo VI: Solution UX Design

## 6.1. Style Guidelines

En esta sección se definen las guías de estilo para la interfaz de usuario de FacialTruth. Estas pautas establecen los principios visuales y de interacción que deben seguirse para asegurar una experiencia de usuario coherente, accesible y visualmente atractiva en todas las plataformas. El objetivo es crear una identidad visual distintiva y profesional, optimizando la legibilidad, la usabilidad y la consistencia en el diseño de la aplicación.

### 6.1.1. General Style Guidelines

**Typography**

- Font Family: Utilizar fuentes sans-serif como Arial, Helvetica o Roboto para asegurar legibilidad y modernidad en la interfaz.
- Font Sizes:
  - Títulos principales (h1): 24-32 px.
  - Subtítulos (h2, h3): 18-24 px.
  - Texto de párrafo: 14-16 px.
  - Etiquetas y botones: 12-14 px.
- Line Height: 1.5 para párrafos y 1.2 para títulos.
- Font Weight:
  - Títulos: Bold (700).
  - Texto de párrafo: Normal (400).
  - Enlaces y botones: Semibold (600).
**Color Palette**
- Primary Colors:
  - Azul (#0056b3) para elementos interactivos como botones y enlaces.
  - Blanco (#FFFFFF) para fondos principales.
  - Gris oscuro (#333333) para texto principal.
- Secondary Colors:
  - Naranja (#ff6600) para elementos de énfasis como llamadas a la acción.
  - Verde (#00b300) para estados de éxito y mensajes de confirmación.
- Background Colors:
  - Fondo general: Gris claro (#f7f7f7).
  - Fondos de secciones y tarjetas: Blanco (#FFFFFF).
**Button Styles**
- Primary Buttons:
  - Fondo azul (#0056b3).
  - Texto blanco (#FFFFFF).
  - Bordes redondeados con un radio de 4px.
  - Hover: Fondo azul oscuro (#003d80), sombra sutil.
- Secondary Buttons:
  - Fondo blanco (#FFFFFF).
  - Borde azul (#0056b3).
  - Texto azul (#0056b3).
  - Hover: Fondo gris claro (#f0f0f0), borde azul más oscuro (#003d80).
**Form Elements**
- Inputs:
  - Bordes redondeados con un radio de 4px.
  - Fondo blanco (#FFFFFF) con borde gris claro (#cccccc).
  - Al enfocar, borde azul (#0056b3).
- Labels:
  - Texto gris oscuro (#333333), tamaño 14px.
- Checkboxes y Radios:
  - Estilo moderno con borde redondeado y color de marca.
**Spacing**
- Padding y Margins:
  - 16px para separaciones generales.
  - 24px para contenedores grandes.
- Grid System:
  - Sistema de columnas 12, con márgenes de 16px entre columnas.
- Iconography:
  - Utilizar iconos simples y de línea clara.
  - Tamaño de iconos entre 16-24 px, dependiendo de su uso.
  - Color de iconos: Gris oscuro (#333333) o azul (#0056b3).
**Imagery**
- Imágenes deben tener alta calidad y resolución mínima de 72 dpi.
- Usar imágenes que refuercen la identidad visual y que estén alineadas con los valores de la empresa.
**Accessibility**
- Contraste de color adecuado (al menos 4.5:1 para texto regular).
- Textos alternativos descriptivos para todas las imágenes.
- Navegación compatible con teclado.

### 6.1.2. Web, Mobile & Devices Style Guidelines

**Responsive Design**
- Mobile First Approach: Diseñar primero para dispositivos móviles y luego escalar a pantallas más grandes.
- Breakpoints:
  - Móvil pequeño: < 576px.
  - Móvil grande: 576px - 768px.
  - Tablets: 768px - 992px.
  - Escritorio: > 992px.
**Navigation**
- Menú hamburguesa para dispositivos móviles.
- Barras de navegación fijas en la parte superior para facilitar la usabilidad.
- Usar breadcrumbs en pantallas más grandes para mostrar la ubicación actual del usuario.
**Touch Targets**
- Todos los elementos interactivos deben tener un área mínima de 48px x 48px para facilitar la interacción táctil.
**Text Scaling**
- Usar unidades relativas (em, rem) para asegurar que el texto se ajuste adecuadamente a diferentes tamaños de pantalla.
- Botones y enlaces deben escalar proporcionalmente para mantenerse accesibles.
**Images & Media**
- Imágenes responsivas que cambian de tamaño según el dispositivo.
- Uso de formatos eficientes (WebP, JPEG para imágenes; MP4 para videos).
**Animations**
- Evitar animaciones complejas en dispositivos móviles.
- Utilizar transiciones suaves y rápidas (200-300ms) para cambios de estado en botones y formularios.

## 6.2. Information Architecture

### 6.2.1. Labeling Systems

En FacialTruth, hemos diseñado un sistema de etiquetado simple y coherente que organiza la navegación de nuestra página. Los ítems del menú son:
- Inicio: Un punto de partida para conocer nuestra propuesta de valor y los beneficios de nuestra herramienta.
- Producto: Detalles sobre nuestra solución de análisis de gestos faciales y cómo mejoran la investigación de mercado.
- Enfoque: Información sobre la misión, visión y el equipo detrás de FacialTruth.
- Teams: Equipo que realiza la solución.
- Contáctanos: Una sección para que los usuarios puedan comunicarse con nosotros para obtener más información o solicitar demos.

Este sistema busca ofrecer una experiencia de navegación clara y directa, permitiendo a los usuarios acceder fácilmente a la información que necesitan. A continuación, puedes ver un ejemplo visual de cómo se presentan estos ítems en nuestra interfaz:

![](https://gyazo.com/727e540c76940bbd861ce8058999ba67.png)

### 6.2.2. Searching Systems

En FacialTruth, nos enfocamos en ofrecer a los usuarios una experiencia de búsqueda intuitiva y eficiente dentro de nuestra aplicación. Para lograrlo, implementamos un sistema de búsqueda por palabra clave que permite a los usuarios encontrar rápidamente gestos específicos, emociones o resultados de pruebas. Además, incluimos filtros que facilitan la búsqueda, como el tipo de gesto (sonrisa, fruncir), el nivel de emoción (alto, medio, bajo) y el resultado de la prueba (aprobado, rechazado). Después de realizar una búsqueda, presentamos los resultados de manera clara y organizada, utilizando tarjetas con íconos representativos y breves descripciones, lo que les permite comprender la información de un vistazo.

### 6.2.3. SEO Tags and Meta Tags

**Landing Page**

- Title: En este título, buscamos captar la atención de los usuarios y resumir nuestra misión en FacialTruth
  ![](https://gyazo.com/20a307e58232e0caac79e81a722a6458.png)
- Meta Tags Description: En esta descripción, queremos ofrecer un resumen atractivo de lo que hacemos. Nuestro objetivo es resaltar cómo nuestra tecnología de análisis de gestos faciales elimina el sesgo humano en la investigación de mercado.
  ![](https://gyazo.com/6beccdfeaed4f4df904a676029c2be95.png)
- Keywords: Aquí seleccionamos palabras clave que nuestros usuarios potenciales podrían buscar. Estas palabras son esenciales para aumentar nuestra visibilidad en los motores de búsqueda y conectar con quienes necesitan nuestros servicios.
  ![](https://gyazo.com/90bb7b7ff6d0623ca9c473dbff3feccd.png)
- Authors: Al indicar quiénes somos parte del equipo de FacialTruth, aportamos credibilidad a la información presentada. Esto refuerza que somos los responsables de esta innovadora solución en la investigación de mercado.
  ![](https://gyazo.com/a35ca477eb6f25782ee0b50d57028fce.png)

### 6.2.4. Navigation Systems

En FacialTruth, nos esforzamos por crear una experiencia de navegación fluida y satisfactoria para los usuarios. Hemos diseñado una barra de navegación intuitiva que proporciona accesos directos a secciones clave como "Inicio", "Cómo Funciona", "Resultados" y "Contacto". Utilizamos breadcrumbs para que los usuarios puedan regresar fácilmente a secciones anteriores y mantener un sentido de orientación. Además, incluimos botones destacados con llamados a la acción, como "Iniciar Prueba" y "Solicitar Demo", que guían a los usuarios a realizar acciones específicas. Para enriquecer la experiencia, implementamos un scroll infinito que presenta contenido relevante a medida que los usuarios navegan hacia abajo en la página. Así, buscamos asegurar que cada interacción sea fluida y cumpla con las expectativas de los visitantes.

## 6.3. Landing Page UI Design

### 6.3.1. Landing Page Wireframe

Hemos creado una representación inicial en forma de bosquejo de baja fidelidad para la página de inicio de FacilTruth

![](https://gyazo.com/1b6671e53f31b2a4d8670e31524a43db.png)
![](https://gyazo.com/eb84c0bc6b4ef5eb1c2655d4b86453c4.png)
![](https://gyazo.com/4b0c1ef38f32481b2b3b8a4217a2bd12.png)
![](https://gyazo.com/6471718a5529a7c8fab77f9aa79b11df.png)

### 6.3.2. Landing Page Mock-up

El Landing Page se desarrolló utilizando un prototipo de fidelidad intermedia en forma de Mock Up. A continuación, te presentamos una vista previa de nuestra propuesta:

![](https://gyazo.com/99b37999f3e428acc1bb444aecb02593.png)
![](https://gyazo.com/43c94d8a8fd67d17d963c301f1fe6adb.png)
![](https://gyazo.com/bcfc8f9efe532992c99105546bd96a4a.png)
![](https://gyazo.com/7848f2435ec8dbabb5e2df23b1443bce.png)

## 6.4. Applications UX/UI Design

Para mejor visualización, acceder al siguiente link: 
[https://www.figma.com/design/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=3-137&t=NlIqntJ1exuV7doR-1](https://www.figma.com/design/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=3-137&t=NlIqntJ1exuV7doR-1 )

### 6.4.1. Applications Wireframes

Dentro de toda la colección, se procederá a incluir algunos ejemplos:

PERFIL DE USUARIO: El usuario puede visualizar sus datos como Nombre , Apellido, Celular, Correo. El usuario podrá cambiar su foto de perfil presionando el botón. Cambiar foto de perfil ,también podrá actualizar sus datos presionando el botón Actualizar Datos y también podrá cerrar sesión en la cuenta presionando el botón Cerrar Sesión.

![](https://gyazo.com/fe2000da1923fc53be15d69fa28845ce.png)
![](https://gyazo.com/05d7ed291db5c76230913bee719140de.png)
![](https://gyazo.com/d6fe08545128884a0bcdb0e39f5fba8c.png)
![](https://gyazo.com/36511fbe51cee38042454e79c6b6bd8e.png)
![](https://gyazo.com/46f33439df6e91badafcf74e152e9287.png)

### 6.4.2. Applications Wireflow Diagrams

![](https://gyazo.com/57c74d60fe5a6e03dd28a2bfd2f0b50d.png)

Como se puede visualizar, se presenta una imagen general del flujo de la solución.
Para una mejor visualización, ir al siguiente link:

[https://www.figma.com/design/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=3-137&t=NlIqntJ1exuV7doR-1](https://www.figma.com/design/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=3-137&t=NlIqntJ1exuV7doR-1)

### 6.4.3. Application Mock-ups

Algunos ejemplos basados en el futuro desarrollo de la solución:

![](https://gyazo.com/d19b4485fa8933397278f4b479430d11.png)
![](https://gyazo.com/1d64ebf5175ea0fd0ec8affdf8bf3bc8.png)
![](https://gyazo.com/2b9e5c9962c700b6e3f67b4e6ff1cbea.png)
![](https://gyazo.com/0674024626a97f958409881ebbdf8340.png)
![](https://gyazo.com/590cddd836e3d55fe5cddd81b65ee7a8.png)

Para una mejor visualización, ir al siguiente link:

[https://www.figma.com/design/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=3-137&t=NlIqntJ1exuV7doR-1](https://www.figma.com/design/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=3-137&t=NlIqntJ1exuV7doR-1)

### 6.4.4. Applications User Flow Diagrams

**Ventana de Inicio Sesión**

![](https://gyazo.com/1999b75419dc619e187ad6afaf0ac83e.png)

**Ventana de Inicio Sesión (recuperar contraseña)**

![](https://gyazo.com/bdc99a00d1f5a5e5069f6137fa999d42.png)

**Página Inicio**

![](https://gyazo.com/66818b9cdf9690ad29209cb14f432a6d.png)

**Ventana Prueba**

![](https://gyazo.com/30637a2fdfc256ccf244177c4ef61fad.png)

**Ventana Resultado**

![](https://gyazo.com/2c9b10d9b2c154a86b1fd179b8f83cc1.png)

**Ventana Perfil**

![](https://gyazo.com/79dd04605f211d32b7cd0b7f762c1bef.png)

## 6.5. Application Prototyping

![](https://gyazo.com/7894c71dbcef7c36a88b3f76069f2dc5.png)

Link del prototipo en Figma: [https://www.figma.com/proto/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=16-4383&node-type=canvas&t=tpuo3uapfiCQ5Iu8-1&scaling=scale-down&content-scaling=fixed&page-id=3%3A137&starting-point-node-id=16%3A4383&share=1](https://www.figma.com/proto/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=16-4383&node-type=canvas&t=tpuo3uapfiCQ5Iu8-1&scaling=scale-down&content-scaling=fixed&page-id=3%3A137&starting-point-node-id=16%3A4383&share=1)

# Capítulo VII: Product Implementation, Validation & Deployment

## 7.1. Software Configuration Management

### 7.1.1. Software Development Environment Configuration

Se utilizarán herramientas específicas para cada fase del proyecto, cubriendo desde la planificación hasta la implementación y pruebas. A continuación, se presenta la configuración del entorno de desarrollo:

![](https://gyazo.com/8cfca52c4d78a051036786ce32d5dd6c.png)

### 7.1.2. Source Code Management

Se implementará GitHub como plataforma principal para la gestión del código fuente y seguimiento de cambios, utilizando el flujo de trabajo GitFlow.
- Ramas principales:
  - main: Contendrá versiones estables listas para producción.
  - develop: Utilizada para integrar características en desarrollo.
- Ramas adicionales:
  - feature/nombre-feature: Para nuevas funcionalidades.
  - release/número-versión: Preparación de versiones para despliegue.
  - hotfix/nombre-hotfix: Corrección de errores críticos en producción.
  
**Convenciones de commits:**
Se aplicarán Conventional Commits con mensajes descriptivos.
Ejemplo:
- bash
- Code kopieren
- feat(UI): Add login feature for users
- fix(api): Resolve issue with authentication

**Control de versiones semánticas:**
Se seguirá el esquema Semantic Versioning 2.0.0 para numeración de versiones, por ejemplo, v1.0.0.

### 7.1.3. Source Code Style Guide & Conventions

El estilo del código debe seguir las convenciones estándar para asegurar legibilidad y mantenibilidad:
- Lenguajes utilizados:
  - Python: PEP8
  - TypeScript: Google TypeScript Style Guide
  - Gherkin: Conventions for Readable Specifications
  - SQL: Estilo en mayúsculas para comandos.
- Nomenclatura:
  - Todo el código se escribirá en inglés para mantener consistencia y facilitar la colaboración.
    
    Ejemplo:
    - Variables: user_email, total_amount
    - Funciones: calculateTotal(), getUserInfo()

### 7.1.4. Software Deployment Configuration

El despliegue de la solución se realizará utilizando procesos manuales, garantizando control y calidad. A continuación, se detallan los pasos para el despliegue:

**Preparación del entorno de despliegue**: Clonar el repositorio del proyecto desde GitHub.

- git clone <URL_del_repositorio>
- cd <nombre_proyecto>

**Instalación de dependencias**: Ejecutar los comandos necesarios para instalar las dependencias.

- npm install  # En caso de usar Node.js
- pip install -r requirements.txt  # En caso de usar Python

**Ejecución de pruebas**: Verificar que todas las pruebas pasen antes del despliegue.

- npm test  # Pruebas para Node.js
- pytest tests/  # Pruebas en Python

**Despliegue en el entorno de producción**:
- Subir los archivos necesarios al servidor.
- Configurar la base de datos PostgreSQL y verificar las conexiones.
- Asegurarse de que la interfaz gráfica (desarrollada con PyQt6) funcione correctamente.

**Validación**:
Realizar pruebas finales en el entorno de producción para asegurar que todos los componentes funcionen como se espera.

**Diagrama de Despliegue (Modelo C4)**:
En el Deployment Diagram se muestra cómo interactúan los componentes del sistema, incluyendo:
- Aplicación de escritorio: Utiliza PyQt6.
- Base de datos: PostgreSQL.
- Servicios backend: API RESTful para la comunicación entre los componentes.

Este proceso de despliegue manual asegura que cada paso sea validado cuidadosamente, minimizando riesgos antes de la puesta en producción.

Github: [https://github.com/NewMinds-FacialTruth](https://github.com/NewMinds-FacialTruth)

Landing Page: [https://facial-truth-landing.vercel.app/](https://facial-truth-landing.vercel.app/)

## 7.2. Solution Implementation

### 7.2.1. Sprint 1

#### 7.2.1.1. Sprint Planning 1.

![](https://gyazo.com/b16df6eab64e570c1be705b74975c46f.png)

#### 7.2.1.2. Sprint Backlog 1.

![](https://gyazo.com/cd8fcb22663f28375fde9f85695e73c2.png)

#### 7.2.1.3. Development Evidence for Sprint Review

![](https://gyazo.com/36a14b958173a9ca8704cc268325f580.png)

#### 7.2.1.4. Testing Suite Evidence for Sprint Review

**No aplica debido a que en esta entrega se realizó el landing page.**

#### 7.2.1.5. Execution Evidence for Sprint Review

Durante este sprint, nos enfocamos en completar el landing page y el prototipo de la aplicación.

![](https://gyazo.com/dadc4d49edc9e9c79df346577b37d5f9.png)
![](https://gyazo.com/6d81437e86f4596b50fb1ff55980cfca.png)
![](https://gyazo.com/fb74400da83f440e2bf8fc6f048a3c3d.png)
![](https://gyazo.com/ac0221eddcb6345cf6b8561bae9d5248.png)
![](https://gyazo.com/123aa66fc1d4bd0d1ca2c0eef1c45822.png)

#### 7.2.1.6. Services Documentation Evidence for Sprint Review

**Para este primer Sprint no fue contemplada la evidencia de la documentación de nuestros servicios.**

#### 7.2.1.7. Software Deployment Evidence for Sprint Review.

Para este primer avance, el cual abarcaba la landing page, y el prototipado de la aplicación en Figma, se llevó a cabo un despliegue de la landing page por medio de Vercel.

![](https://gyazo.com/e10001c7e00e186b3dcaf5b1325d7531.png)

#### 7.2.1.8. Team Collaboration Insights during Sprint

![](https://gyazo.com/4b23826d065bbbe3bfca62a7a5b73e85.png)

## 7.3. Validation Interviews

### 7.3.1. Diseño de entrevistas

Preguntas a empresarios
- Después de conocer el funcionamiento de FacialTruth, ¿en qué aspectos de su proceso actual de evaluación de productos cree que esta herramienta podría aportar más valor?
- ¿Considera que FacialTruth podría mejorar la precisión y objetividad en sus estudios de mercado? ¿Qué tan importante le parece contar con datos emocionales objetivos en su industria?
- ¿Cómo percibe el uso de un análisis automatizado de emociones en comparación con métodos tradicionales como focus groups o encuestas?
- ¿Le resulta interesante la posibilidad de reducir el sesgo humano en la interpretación de emociones? ¿En qué situaciones cree que sería particularmente útil para su empresa?
- ¿Hasta qué punto cree que FacialTruth podría ayudar a evitar discrepancias entre las emociones capturadas en estudios previos y la reacción del consumidor en el mercado?
- ¿Qué tipo de resultados específicos le gustaría ver en los reportes de FacialTruth para facilitar su toma de decisiones (por ejemplo, gráficos emocionales, alertas automáticas, comparativas)?
- ¿Cómo se imagina integrando una herramienta de análisis de emociones en tiempo real como FacialTruth en su proceso de lanzamiento de productos?
- ¿Qué nivel de aceptación cree que tendría FacialTruth en su sector? ¿Le parece que otros empresarios podrían encontrarla útil?
- ¿Cree que contar con datos emocionales más precisos y objetivos a través de FacialTruth podría impactar significativamente sus estrategias de mercado?
- ¿Qué expectativas tiene respecto al impacto de FacialTruth en su empresa a largo plazo en términos de acercamiento y adaptación a las necesidades de sus consumidores?

### 7.3.2. Registro de Entrevistas.

**No aplica debido a que, en este sprint, el producto aun no está terminado.**

### 7.3.3. Evaluaciones según heurísticas.

**No aplica debido a que, en este sprint, el producto aun no está terminado.**

### 7.4. Video About-the-Product.

![](https://gyazo.com/d2c0dacfa350681cfcaf7ec59b1fe76d.png)
Video About the Product: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EVFXBQnq_-BLignUCthDiwEB4lYGDTPfGhdijpTuGdc3Hw?e=swhzbW&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EVFXBQnq_-BLignUCthDiwEB4lYGDTPfGhdijpTuGdc3Hw?e=swhzbW&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

# Conclusiones

- Realizar un correcto Event Storming resulta clave para identificar los Bounded Contexts que compondrán la solución de Software.
- La detección de gestos faciales se puede lograr mediante el uso de puntos claves en la cara de la persona que se ubique frente a la cámara, y su procesamiento mediante redes neuronales.
- El diseño de la solución debe ser amigable para que pueda ser entendido por usuarios que no estén relacionados al desarrollo de software. Esto ayuda a que dichos usuarios no pierdan el interés en el producto.

# Bibliografía

# Anexos

Repositorio de github del informe: [https://github.com/Softwares-Emergentes-WX83-Grupo-4/Informe-del-Trabajo-Final](https://github.com/Softwares-Emergentes-WX83-Grupo-4/Informe-del-Trabajo-Final)

Video de entrevistas: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EW67S70zZghIs5hZuvG582oBf4XPFGoNE1kYVbqRKvANBg?e=o2LFMn](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EW67S70zZghIs5hZuvG582oBf4XPFGoNE1kYVbqRKvANBg?e=o2LFMn)

Video de exposición TP1: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EeFRUiTBQQFKoue-Y1h9PncBIG2drO_8J1GyRbmsrP86Pg?e=AXgPh0](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EeFRUiTBQQFKoue-Y1h9PncBIG2drO_8J1GyRbmsrP86Pg?e=AXgPh0)

Prototipo de la aplicación en Figma: [https://www.figma.com/proto/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=16-4383&node-type=canvas&t=tpuo3uapfiCQ5Iu8-1&scaling=scale-down&content-scaling=fixed&page-id=3%3A137&starting-point-node-id=16%3A4383&share=1](https://www.figma.com/proto/xGWa7By4YRaokcp1bqquCT/Wireframes-and-Mock-ups?node-id=16-4383&node-type=canvas&t=tpuo3uapfiCQ5Iu8-1&scaling=scale-down&content-scaling=fixed&page-id=3%3A137&starting-point-node-id=16%3A4383&share=1)
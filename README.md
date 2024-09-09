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

**<h3>Setiembre, 2024</h3>**

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|--------------|--------------|--------------|--------------|
| 1           | 08/09/2024      | - Andrés Doig Apostol<br>- - Alonso Fernando Robles Astuñaupa<br>- Christian Jose Zeta Valenzuela<br>- Dámaris Jemima Tasayco Vilcamiza<br>- Erick Gabriel Urbizagstegui Alvarez    | Implementación del capítulo 1 al 4.      |

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [Startup Profile](#startup-profile)
    - [Descripción de la Startup](#descripción-de-la-startup)
    - [Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
  - [Solution Profile](#solution-profile)
    - [Antecedentes y problemática](#antecedentes-y-problemática)
    - [Lean UX Process](#lean-ux-process)
      - [Lean UX Problem Statements](#lean-ux-problem-statements)
      - [Lean UX Assumptions](#lean-ux-assumptions)
      - [Lean UX Hypothesis Statements](#lean-ux-hypothesis-statements)
      - [Lean UX Canvas](#lean-ux-canvas)
  - [Segmentos objetivo](#segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [Competidores](#competidores)
    - [Análisis competitivo](#análisis-competitivo)
    - [Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
  - [Entrevistas](#entrevistas)
    - [Diseño de entrevistas](#diseño-de-entrevistas)
    - [Registro de entrevistas](#registro-de-entrevistas)
    - [Análisis de entrevistas](#análisis-de-entrevistas)
  - [Needfinding](#needfinding)
    - [User Personas](#user-personas)
    - [User Task Matrix](#user-task-matrix)
    - [Empathy Mapping](#empathy-mapping)
    - [As-is Scenario Mapping](#as-is-scenario-mapping)
    - [Ubiquitous Language](#ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [To-Be Scenario Mapping](#to-be-scenario-mapping)
    - [User Stories](#user-stories)
    - [Impact Mapping](#impact-mapping)
    - [Product Backlog](#product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [Strategic-Level Attribute-Driven Design](#strategic-level-attribute-driven-design)
    - [Design Purpose](#design-purpose)
    - [Attribute-Driven Design Inputs\*\*](#attribute-driven-design-inputs)
      - [Primary Functionality (Primary User Stories)](#primary-functionality-primary-user-stories)
      - [Quality Attribute Scenarios](#quality-attribute-scenarios)
      - [Constraints](#constraints)
    - [Architectural Drivers Backlog](#architectural-drivers-backlog)
    - [Architectural Design Decisions](#architectural-design-decisions)
    - [Quality Attribute Scenario Refinements](#quality-attribute-scenario-refinements)
  - [Strategic-Level Domain-Driven Design](#strategic-level-domain-driven-design)
    - [Event Storming](#event-storming)
    - [Candidate Context Discovery](#candidate-context-discovery)
    - [Domain Message Flows Modeling](#domain-message-flows-modeling)
    - [Bounded Context Canvases](#bounded-context-canvases)
    - [Context Mapping](#context-mapping)
  - [Software Architecture](#software-architecture)
    - [Software Architecture System Landscape Diagram](#software-architecture-system-landscape-diagram)
    - [Software Architecture Context Level Diagrams](#software-architecture-context-level-diagrams)
    - [Software Architecture Container Level Diagrams](#software-architecture-container-level-diagrams)
    - [Software Architecture Deployment Diagrams](#software-architecture-deployment-diagrams)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome

| Criterio Específico | Acciones realizadas | Conclusiones |
|---------|---------|---------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | <br><br> **TB1** <br><br> **Andrés Doig Apostol** <br> Realizó el capítulo 1, identificando la problemática y necesidades de nuestro negocio. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Realizó el capítulo 2 del informe, teniendo que analizar el cómo serían las entrevistas y quiénes son nuestros competidores <br><br> **Christian Jose Zeta Valenzuela** <br> Realizó el capítulo 4 del informe, explicando el propósito del diseño, las herramientas usadas y las restricciones que tendrá el proyecto. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Realizó el capítulo 4, pensando en las User Stories y catalogándolas según su prioridad. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Realizó el capítulo 4 del informe, diseñando los bounded contexts del sistema y su arquitectura siguiendo el modelo C4. | **TB1** <br><br> Se realizaron los capítulos del 1 al 4, pensando desde qué oproblemática atacaríamos y cómo, hasta cómo plantearíamos la arquitectura de nuestra solución. |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | <br><br> **TB1** <br><br> **Andrés Doig Apostol** <br> Realizó el capítulo 1, identificando la problemática y necesidades de nuestro negocio. <br><br> **Alonso Fernando Robles Astuñaupa** <br> Realizó el capítulo 2 del informe, teniendo que analizar el cómo serían las entrevistas y quiénes son nuestros competidores <br><br> **Christian Jose Zeta Valenzuela** <br> Realizó el capítulo 4 del informe, explicando el propósito del diseño, las herramientas usadas y las restricciones que tendrá el proyecto. <br><br> **Dámaris Jemima Tasayco Vilcamiza** <br> Realizó el capítulo 4, pensando en las User Stories y catalogándolas según su prioridad. <br><br> **Erick Gabriel Urbizagastgui Alvarez** <br> Realizó el capítulo 4 del informe, diseñando los bounded contexts del sistema y su arquitectura siguiendo el modelo C4. | **TB1** <br><br> Se realizaron los capítulos del 1 al 4, pensando desde qué oproblemática atacaríamos y cómo, hasta cómo plantearíamos la arquitectura de nuestra solución. |

# Capítulo I: Introducción

## Startup Profile

### Descripción de la Startup

Nuestra startup tiene como misión mejorar la calidad de la investigación de mercado a través de tecnología avanzada que elimina el sesgo humano. Nos enfocamos en el desarrollo de una aplicación de escritorio que utiliza una cámara para registrar y analizar los gestos faciales de los participantes durante la prueba de productos. Esta solución automatiza el análisis de expresiones, proporcionando información más objetiva y útil para la toma de decisiones empresariales.

**Misión**

Nuestra misión es revolucionar la investigación de mercado al aplicar tecnología de análisis facial avanzada que elimina el sesgo humano, permitiendo a las empresas tomar decisiones más informadas y efectivas. Nos comprometemos a proporcionar herramientas innovadoras que automatizan el análisis de expresiones faciales, generando insights precisos y objetivos que impulsan el éxito empresarial.

**Visión**

Nuestra visión es ser líderes en tecnología de análisis facial, transformando la forma en que las empresas comprenden y responden a las necesidades y emociones de sus consumidores. Aspiramos a empoderar a las empresas con soluciones tecnológicas de vanguardia que optimicen sus estrategias de mercado y contribuyan al desarrollo económico.

### Perfiles de integrantes del equipo

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

## Solution Profile

### Antecedentes y problemática

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

### Lean UX Process

#### Lean UX Problem Statements

**Problem Statement 1:**<br>
En el ámbito de la investigación de mercado, las empresas enfrentan el reto de obtener retroalimentación auténtica y confiable de los consumidores durante las pruebas de productos. Los métodos tradicionales, como los focus groups, dependen en gran medida de las opiniones verbales de los participantes, las cuales pueden ser influenciadas por sesgos conscientes e inconscientes, lo que resulta en datos inexactos o poco fiables. Este problema compromete la capacidad de las empresas para tomar decisiones informadas sobre el diseño y comercialización de sus productos.
¿Cómo podemos desarrollar una solución tecnológica que permita a las empresas capturar y analizar de manera precisa las emociones y reacciones de los consumidores mediante el uso de cámaras y algoritmos de reconocimiento facial, mejorando la fiabilidad de los estudios de mercado y reduciendo el impacto de los sesgos humanos?

**Problem Statement 2:**<br>
Las empresas que buscan lanzar nuevos productos al mercado dependen en gran medida de las reacciones de los consumidores para validar sus decisiones de diseño y marketing. Sin embargo, los métodos actuales de recolección de datos en focus groups y encuestas están sujetos a sesgos de comportamiento y de cortesía, donde los participantes podrían no expresar sus verdaderas opiniones. Esta falta de autenticidad en las respuestas compromete la capacidad de las empresas para obtener información precisa, lo que puede llevar a errores en las decisiones estratégicas y a productos que no cumplen con las expectativas del mercado.
¿Cómo podemos crear una solución que, a través de la detección y el análisis de gestos faciales, permita a las empresas obtener retroalimentación auténtica y sin sesgos de los consumidores, brindando así información más confiable para el desarrollo y la comercialización de productos?

**Problem Statement 3:**<br>
En la era digital, las empresas necesitan procesar grandes volúmenes de datos de forma rápida y eficaz para mejorar sus productos y servicios. Sin embargo, las técnicas tradicionales de análisis de focus groups implican procesos manuales que son lentos, subjetivos y requieren expertos que interpreten las emociones y reacciones de los participantes. Este enfoque no solo es ineficiente, sino que también deja espacio para la interpretación sesgada de los resultados, lo que puede afectar negativamente la toma de decisiones.

***¿Cómo podemos desarrollar una solución automatizada que capture y analice gestos faciales en tiempo real durante las pruebas de productos, permitiendo a las empresas obtener resultados rápidos, objetivos y libres de interpretación humana, mejorando así la eficiencia y la precisión en el análisis de la respuesta del consumidor?***

#### Lean UX Assumptions

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

#### Lean UX Hypothesis Statements

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

#### Lean UX Canvas 

![Imagen](https://i.gyazo.com/9d2f4b9a77e9b73e606df73e1ac4bbe0.jpg)

## Segmentos objetivo

El principal segmento objetivo de nuestra solución son los empresarios y los equipos de marketing que buscan mejorar la precisión de los estudios de mercado. Estos usuarios requieren datos confiables para tomar decisiones informadas sobre la dirección de sus productos. Al ofrecer una herramienta que automatiza el análisis de las emociones de los consumidores, apuntamos a empresas que valoran la innovación tecnológica y la optimización de sus procesos de investigación de mercado.

# Capítulo II: Requirements Elicitation & Analysis

## Competidores

### Análisis competitivo

![Imagen](https://i.gyazo.com/e974aec0594ac11cf43748a7e0f987f4.png)
![Imagen](https://gyazo.com/30a37a8184c263855504b0a8d50f57d2.png)
![Imagen](https://gyazo.com/5aabe722ac58484b17d0e55dda5a59b5.png)
![Imagen](https://gyazo.com/1565fef3ca6707ffa1173afb592c5aed.png)

### Estrategias y tácticas frente a competidores

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
     
## Entrevistas 

### Diseño de entrevistas

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

### Registro de entrevistas

**Entrevista 1**

![Imagen](https://i.gyazo.com/52fca163a4951167963578e286918102.png)

**Entrevistador**: Christian Jose Zeta Valenzuela

**Entrevistado**: Humberto Martinez

**Resumen de la entrevista**: Durante la entrevista, se discutieron aspectos clave sobre la evaluación de productos y la recopilación de información de usuarios para mejorar la experiencia del cliente. La empresa utiliza herramientas como DataDog para monitorear el uso de funcionalidades y colabora estrechamente con el equipo de producto para definir métricas. Sin embargo, mapear y programar estos elementos presenta desafíos significativos. Aunque una solución tecnológica para analizar gestos faciales es interesante, se considera que sería costosa y difícil de sostener. A pesar de que las opiniones de los focus groups son valiosas, a veces no se alinean con la aceptación real del producto en el mercado, y se reconoció la necesidad de mejorar en la interpretación y uso de estos datos para la evolución de los productos.

**Entrevista 2**

![Imagen](https://i.gyazo.com/02e0e11de29a34c5911c2bf99edfded2.png)

**Entrevistador**: Erick Gabriel Urbizagastegui Alvarez

**Entrevistado**: Salvador Torres

**Resumen de la entrevista**: Durante la entrevista con Salvador Torre, se abordaron sus métodos para evaluar productos, destacando que generalmente consulta con familiares o amigos cercanos y no utiliza herramientas formales, solo redes sociales o comunicación oral. Sin embargo, enfrenta el problema de que algunas personas no son completamente transparentes en sus opiniones sobre sus productos. Salvador vende barras energéticas y ha tenido experiencias negativas en el pasado donde no logró vender sus productos. Considera que la idea de abordar el sesgo humano es prometedora y podría ayudar a impulsar su microempresa, mejorando sus ventas y llevando su negocio al siguiente nivel.

**Entrevista 3**

![Imagen](https://i.gyazo.com/835c3087322da09fc808405919d6c4c3.png)

**Entrevistador**: Erick Gabriel Urbizagastegui Alvarez

**Entrevistado**: Valeria Nevado

**Resumen de la entrevista**: En la entrevista con Valeria Navarro, se discutió su enfoque para recolectar opiniones sobre su producto en su pequeña empresa. Valeria suele consultar a familiares o compañeros, y utiliza principalmente redes sociales o interacciones directas para obtener comentarios. Sin embargo, enfrenta dificultades en la recolección de opiniones, ya que no siempre son 100% transparentes y a veces son contradictorias, lo que complica su interpretación. A pesar de estos desafíos, Valeria considera que la idea de una aplicación que aborde el sesgo humano podría ser una excelente herramienta para mejorar su negocio.

### Análisis de entrevistas 

En las entrevistas, se destacó un patrón común en la evaluación de productos y la recopilación de información de usuarios. Humberto Martínez mencionó el uso de herramientas como DataDog para monitorear funcionalidades, pero enfrentó desafíos con el mapeo y programación, y cuestionó la viabilidad de soluciones tecnológicas complejas como el análisis de gestos faciales. Salvador Torres y Valeria Navarro, por su parte, recurren a métodos informales como consultas con familiares y redes sociales, pero enfrentan problemas con la falta de transparencia y opiniones contradictorias. Ambos ven potencial en abordar el sesgo humano para mejorar sus negocios, sugiriendo que nuevas tecnologías o enfoques podrían optimizar la interpretación y uso de datos en la evolución de productos.


## Needfinding

### User Personas

![Imagen](https://i.gyazo.com/473836f5dfa9f76ac64e411eab15599a.png)

### User Task Matrix

![Imagen](https://gyazo.com/7c3997254860e720f3c30fd037053b7c.png)

### Empathy Mapping

![Imagen](https://i.gyazo.com/02d3b73742bb53e541daa3013a9e5683.png)

### As-is Scenario Mapping

![Imagen](https://i.gyazo.com/f014f86a0b88709c1777114f2212879d.png)

### Ubiquitous Language

Dada la naturaleza de la solución existen términos que posiblemente para diversos individuos tengan conceptos diferentes, por ello, en está sección se definirán los conceptos claves con la finalidad de evitar malentendidos.

- Participantes: Personas elegidas para realizar una prueba de productos, interactuando y proporcionando reacciones de esta misma.
- Prueba de productos: Actividad en la que se presenta un producto, con la finalidad de evaluar la experiencia y reacciones de los participantes.
- Análisis de datos: Proceso de revisar e interpretar la información recolectada en las actividades propuestas.
- Informe: Documento que resumen los hallazgos, incluyendo gráficos, recomendaciones o lo que se considere necesario.
- Reacción de los participantes: Respuestas emocionales y comportamientos de un individuo envase a un estímulo.
- Patrón de comportamiento: Tendencias recurrentes en las reacciones de los participantes.

# Capítulo III: Requirements Specification

### To-Be Scenario Mapping

![Imagen](https://gyazo.com/5213a5fe6d886002678372c21a743907)

### User Stories

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

### Impact Mapping

![Imagen](https://gyazo.com/9ab8631e9867dea0b2861425c1766a9a.png)

### Product Backlog

![Imagen](https://gyazo.com/888856ba686846b016839c8251797c0f.png)
![Imagen](https://gyazo.com/9e411dee1614596f83d23e1093274ff9.png)
![Imagen](https://gyazo.com/d7e53319bc640ffdf12c9434da74922c.png)
![Imagen](https://gyazo.com/1b868aa471ead446e913de2c449a38ae.png)

# Capítulo IV: Strategic-Level Software Design

## Strategic-Level Attribute-Driven Design
### Design Purpose

**Propósito del Diseño**

El propósito del diseño estratégico es crear una solución automatizada para el análisis de gestos faciales que elimine el sesgo humano y proporcione datos precisos en estudios de mercado. Esta solución busca ofrecer a las empresas una herramienta confiable para la captura y análisis de emociones durante las pruebas de productos, mejorando la calidad y precisión de los datos recolectados.

### Attribute-Driven Design Inputs**

#### Primary Functionality (Primary User Stories)

En esta sección se especifican las User Stories que tienen mayor relevancia en términos de requisitos funcionales y que impactan la arquitectura de la solución. Estas historias son fundamentales para la operación del sistema y han sido seleccionadas debido a su importancia en las decisiones de diseño.

![Imagen](https://gyazo.com/d83c65c71d32b70725edde2dbfef5445.png)
![Imagen](https://gyazo.com/e51060bffcb29209ee7c1d319e5c981a.png)
![Imagen](https://gyazo.com/847d86ac0b4a2e95fb3564f4fc33bd04.png)
![Imagen](https://gyazo.com/9d9bd1738bebbc6fef57ff3adfe737cb.png)

#### Quality Attribute Scenarios

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

#### Constraints

- Restricción 1: La aplicación debe funcionar en sistemas operativos Windows y Linux, utilizando PyQt6 para la interfaz gráfica.
- Restricción 2: La solución debe integrar el análisis de gestos faciales mediante Pyfeat, asegurando compatibilidad y eficiencia.
- Restricción 3: Los datos deben ser almacenados en una base de datos PostgreSQL, cumpliendo con las normativas de privacidad y seguridad de datos.
- Restricción 4: La aplicación debe garantizar un rendimiento adecuado incluso con grandes volúmenes de datos y mantener una alta precisión en el análisis facial.

### Architectural Drivers Backlog

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

### Architectural Design Decisions

- Decisión 1: Implementar el análisis facial con Pyfeat, dado su enfoque especializado en el procesamiento de datos faciales.
- Decisión 2: Utilizar PyQt6 para desarrollar una interfaz de usuario intuitiva y compatible con múltiples plataformas.
- Decisión 3: Almacenar los datos en PostgreSQL para asegurar una base de datos robusta y segura.
- Decisión 4: Implementar algoritmos de reconocimiento facial que proporcionen resultados en tiempo real para mejorar la eficiencia de los estudios de mercado.

### Quality Attribute Scenario Refinements

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

## Strategic-Level Domain-Driven Design

### Event Storming

![Imagen](https://gyazo.com/75e9a1c084eb6c2ebb37b8493cfadb87.png)

### Candidate Context Discovery

Se realizó un event-storming como equipo y se lograron identificar los siguientes 4 bounded contexts:
- Sesión: Se encarga de gestionar la creación y finalización de las sesiones de registro de gestos faciales.
- Detección: Se encarga de ubicar la cara del usuario y registrar los gestos faciales que este haga.
- Procesamiento: Se encarga de procesar los datos que reciba de la detección de gestos faciales para generar conclusiones.
- Resultados: Se encarga de registrar los resultados obtenidos durante la sesión.

![Imagen](https://gyazo.com/48452c777f0d11318209574796a5a0a5.png)

### Domain Message Flows Modeling

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

### Bounded Context Canvases

**Sesión**

![Imagen](https://gyazo.com/3f5f24b7d6e859c20a0c3b3e7253df5c.jpg)

**Detección**

![Imagen](https://gyazo.com/6ccc82e10796345f42512429a1651910.jpg)

**Procesamiento**

![Imagen](https://gyazo.com/f0d6557493052d5411fee8128615eedb.jpg)

**Resultados**

![Imagen](https://gyazo.com/6fbb9ab4ecf8101ea3b0d62a937db3dc.jpg)

### Context Mapping

![Imagen](https://gyazo.com/027a6d917076e435405ad29b81f20327.jpg)

## Software Architecture

### Software Architecture System Landscape Diagram

![Imagen](https://gyazo.com/f84a41544f1cb522b8634148c79dce82.png)

### Software Architecture Context Level Diagrams

![Imagen](https://gyazo.com/96e2773d5e555e41fe5b65b06ec3a92f.png)

### Software Architecture Container Level Diagrams

![Imagen](https://gyazo.com/093fd0a839e9067ed5558d96fe401b65.png)

### Software Architecture Deployment Diagrams

![Imagen](https://gyazo.com/034013a5645fc76e92a54617dc83bef9.png)

# Conclusiones

# Bibliografía

# Anexos

Repositorio de github: [https://github.com/Softwares-Emergentes-WX83-Grupo-4/Informe-del-Trabajo-Final](https://github.com/Softwares-Emergentes-WX83-Grupo-4/Informe-del-Trabajo-Final)

Video de entrevistas: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EW67S70zZghIs5hZuvG582oBf4XPFGoNE1kYVbqRKvANBg?e=o2LFMn](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EW67S70zZghIs5hZuvG582oBf4XPFGoNE1kYVbqRKvANBg?e=o2LFMn)

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
<br>
<img src="/images/upc-logo.png"></img><br>
<br>
    <strong>Ingeniería de Software - 5to Ciclo</strong><br>
<br>
    <strong>Desarrollo de Aplicaciones Open Source - WX55</strong><br>  
<br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez</strong><br>
    <br> <strong>INFORME DE TRABAJO FINAL - TB1 </strong> 
</p>

<p align="center">
    <strong>Startup: </strong><br>
    <strong>Producto: </strong>
</p>

<h3 align="center" >Team Members:</h3>
<div>
    <table align="center">
        <tr>
            <th style="text-aling:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
                <td>Gabriel Anthony Braithuaite Toledo</td>
            <td>U20201e889</td>
        </tr>
        <tr>
            <td>Adrian Alonso Calle Huayanca</td>
            <td>U202011657</td>
        </tr>
        <tr>
                <td>Hardie Alfonso Holguín Gamarra</td>
            <td>U202220250</td>
        </tr>
        <tr>
            <td>Mateo Italo Loechle Arias</td>
            <td>U202215004</td>
        </tr>
        <tr>
            <td>David Bryan Rodriguez Santos</td>
            <td>u202212236</td>
        </tr>
    </table>

<tr>
    <td><b>Mes y año: </b> 05/09/2024</td>
</tr>
</div>
<br>


# Informe del proyecto

## Registro de Versiones del Informe


| Versión |   Fecha    | Autor | Descripción de modificación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
|:-------:|:----------:|:-----:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
|   TB1   | 05/09/2024 |Todos los integrantes |                                                                                                                                                                                                                                                                                                                                     |

## Project Report Collaboration Insights
## Contenido
### Tabla de contenidos:


- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#chapter-1)
  - [1.1. Startup Profile](#startup-profile)
    - [1.1.1. Descripción de la Startup](#startup-description)
    - [1.1.2. Perfiles de integrantes del equipo](#profile-members)
  - [1.2. Solution Profile](#solution-profile)
    - [1.2.1. Antecedentes y problemática](#background-and-problems)
    - [1.2.2. Lean UX Process](#lean-ux)
      - [1.2.2.1. Lean UX Problem Statements](#lean-ux-problem)
      - [1.2.2.2. Lean UX Assumptions](#lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#lean-ux-hypothesis)
      - [1.2.2.4. Lean UX Canvas](#lean-ux-canvas)
  - [1.3. Segmentos objetivo](#target-segments)
- [Capítulo II: Requirements Elicitation & Analysis](#chapter-2)
  - [2.1. Competidores](#competitors)
    - [2.1.1. Análisis competitivo](#competitive-analysis)
    - [2.1.2. Estrategias y tácticas frente a competidores](#strategy-tactics)
  - [2.2. Entrevistas](#interviews)
    - [2.2.1. Diseño de entrevistas](#interviews-design)
    - [2.2.2. Registro de entrevistas](#interviews-registry)
    - [2.2.3. Análisis de entrevistas](#interviews-analysis)
  - [2.3. Needfinding](#needfinding)
    - [2.3.1. User Personas](#user-personas)
    - [2.3.2. User Task Matrix](#user-task-matrix)
    - [2.3.3. User Journey Mapping](#user-journey-mapping)
    - [2.3.4. Empathy Mapping](#empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#ubiquitous-language)
- [Capítulo III: Requirements Specification](#chapter-3)
  - [3.1. To-Be Scenario Mapping](#to-be-scenario-mapping)
  - [3.2. User Stories](#user-stories)
  - [3.3. Impact Mapping](#impact-mapping)
  - [3.4. Product Backlog](#product-backlog)
- [Capítulo IV: Product Design](#chapter-4)
  - [4.1. Style Guidelines](#style-guidelines)
    - [4.1.1. General Style Guidelines](#general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#web-style-guidelines)
  - [4.2. Information Architecture](#information-architecture)
    - [4.2.1. Organization Systems](#organization-systems)
    - [4.2.2. Labeling Systems](#labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#searching-systems)
    - [4.2.5. Navigation Systems](#navigation-systems)
  - [4.3. Landing Page UI Design](#landing-page-ui)
    - [4.3.1. Landing Page Wireframe](#landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#landing-page-mockup)
  - [4.4. Web Applications UX/UI Design](#web-application-ux-ui)
    - [4.4.1. Web Applications Wireframes](#web-application-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#web-application-wireflow)
    - [4.4.2. Web Applications Mock-ups](#web-appliaction-mockups)
    - [4.4.3. Web Applications User Flow Diagrams](#user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#software-object-oriented-design)
    - [4.7.1. Class Diagrams](#class-diagrams)
    - [4.7.2. Class Dictionary](#class-dictionary)
  - [4.8. Database Design](#database-design)
    - [4.8.1. Database Diagram](#database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#chapter-5)
  - [5.1. Software Configuration Management](#software-configuration)
    - [5.1.1. Software Development Environment Configuration](#software-development)
    - [5.1.2. Source Code Management](#source-code)
    - [5.1.3. Source Code Style Guide & Conventions](#source-code-style-guide-and-conventions)
    - [5.1.4. Software Deployment Configuration](#software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#landing-page-services-applications-implementation)
    - [5.2.X. Sprint n](#sprint-x)
      - [5.2.X.1. Sprint Planning n](#sprint-planning-x)
      - [5.2.X.2. Sprint Backlog n](#spring-backlog-x)
      - [5.2.X.3. Development Evidence for Sprint Review](#development-evidence-for-sprint-review-x)
      - [5.2.X.4. Testing Suite Evidence for Sprint Review](#testing-suite-evidence-for-sprint-review)
      - [5.2.X.5. Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review)
      - [5.2.X.6. Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review)
      - [5.2.X.7. Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review)
      - [5.2.X.8. Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#interview-design-2)
    - [5.3.2. Registro de Entrevistas](#interview-registry-2)
    - [5.3.3. Evaluaciones según heurísticas](#heuristic-exam)
  - [5.4. Video About-the-Product](#about-the-productions)
- [Conclusiones](#conclusions)
- [Conclusiones y recomendaciones](#recomendations)
- [Video About-the-Team](#about-the-team)
- [Bibliografía](#bibliography)
- [Anexos](#links)


<h4 id="student-outcome"> Student Outcome</h4>
<h3 id="chapter-1">Capítulo I: Introducción</h3>
<h4 id="startup-profile">1.1. Startup Profile</h4>
<h4 id="startup-description"> 1.1.1. Descripción de la Startup</h4>
<h4 id="profile-members">1.1.2. Perfiles de integrantes del equipo</h4>
<h4 id="solution-profile">1.2. Solution Profile</h4>
<h4 id="background-and-problems">1.2.1 Antecedentes y problemática</h4>
<h4 id="lean-ux">1.2.2 Lean UX Process.</h4>
<h4 id="lean-ux-problem">1.2.2.1. Lean UX Problem Statements.</h4>
<h4 id="lean-ux-assumptions">1.2.2.2. Lean UX Assumptions.</h4>
<h4 id="lean-ux-hypothesis">1.2.2.3. Lean UX Hypothesis Statements.</h4>
<h4 id="lean-ux-canvas">1.2.2.4. Lean UX Canvas.</h4>
<h4 id="target-segments">1.3. Segmentos objetivo.</h4>
<h3 id="chapter-2">Capítulo II: Requirements Elicitation & Analysis</h3>
<h4 id="competitors">2.1. Competidores.</h4>
Algunos competidores en el campo de la gestión de restaurantes incluyen Toast, TouchBistro y Inforest.
<h4 id="competitive-analysis">2.1.1. Análisis competitivo.</h4>

# Competitive Analysis Landscape


<table>
  <tr>
    <th colspan="6"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Evaluar a fondo el entorno competitivo, identificando competidores, sus fortalezas y debilidades, y entender sus estrategias.</td>
  </tr>
  <tr>
    <th colspan="2"></th>
    <th>NoNocleus</th>
    <th>Toast</th>
    <th>TouchBistro</th>
    <th>Inforest</th>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Plataforma integral para la gestión de restaurantes que optimiza procesos clave como stock, mesas, cocina, y proveedores, mejorando la eficiencia operativa.</td>
    <td>Software de gestión de restaurantes basado en la nube que ayuda a los negocios a optimizar operaciones como pedidos, pagos, inventario y análisis de ventas, mejorando así su eficiencia y rentabilidad.</td>
    <td>TouchBistro es una empresa canadiense con sede en Toronto que se especializa en el desarrollo de sistemas de punto de venta (POS) para restaurantes.</td>
    <td>Inforest es un software modular diseñado para automatizar la gestión y operación de negocios gastronómicos y afines. Ofrece una variedad de funcionalidades para optimizar procesos, generar reportes y estadísticas, gestionar ventas y unificar operaciones. Además, proporciona servicio técnico 24/7.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva</td>
    <td>Integración modular adaptable a diferentes necesidades y conexión automatizada entre módulos clave para reducir desperdicios y maximizar la rentabilidad.</td>
    <td>Alta personalización y hardware especializado.</td>
    <td>Simplicidad, uso sin conexión, enfoque en pequeñas empresas.</td>
    <td>Flexibilidad y menor costo.</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de marketing</td>
    <td>Mercado objetivo</td>
    <td>Pequeños y medianos restaurantes, así como cadenas que buscan digitalizar y escalar sus operaciones.</td>
    <td>Restaurantes medianos y grandes.</td>
    <td>Pequeños y medianos restaurantes, cafeterías.</td>
    <td>Restaurantes pequeños en mercados específicos.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Marketing digital, demostraciones gratuitas, y presencia en ferias del sector gastronómico y tecnológico.</td>
    <td>Enfoque en tecnología avanzada y grandes cadenas.</td>
    <td>Marketing centrado en facilidad de uso y pequeños negocios.</td>
    <td>Enfoque en soluciones económicas para nichos específicos.</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de producto</td>
    <td>Productos & Servicios</td>
    <td>Módulos de gestión de stock, mesas, reservas, pedidos a proveedores, y reportes financieros, con integración a sistemas POS.</td>
    <td>Sistema POS, gestión de pedidos y empleados, informes.</td>
    <td>Sistema POS para iPad, gestión de mesas y reservas.</td>
    <td>Sistema POS básico, ajustado a las necesidades locales.</td>
  </tr>
  <tr>
    <td>Precios y costos</td>
    <td>Modelo de suscripción mensual desde $50 para pequeñas operaciones y planes personalizables para cadenas.</td>
    <td>Moderados a altos, dependiendo de las funciones y hardware.</td>
    <td>Costos accesibles para PYMEs.</td>
    <td>Costos bajos, enfocado en pequeñas empresas.</td>
  </tr>
  <tr>
    <td>Canales de distribución</td>
    <td>Distribución en línea a través del sitio web oficial y servicios de implementación in situ.</td>
    <td>Web, aplicaciones móviles, integraciones con plataformas de entrega.</td>
    <td>iPad, soporte web.</td>
    <td>Web, opciones móviles limitadas.</td>
  </tr>
  <tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Adaptabilidad modular y soporte técnico dedicado.</td>
    <td>Personalización, integraciones avanzadas.</td>
    <td>Facilidad de uso, independencia de internet.</td>
    <td>Costo bajo, flexibilidad en implementación.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Dependencia de internet y necesidad de personal capacitado para la configuración inicial.</td>
    <td>Costos relativamente altos, curva de aprendizaje.</td>
    <td>Funciones avanzadas limitadas.</td>
    <td>Reconocimiento de marca bajo, funcionalidad limitada.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Dependencia de internet y necesidad de personal capacitado para la configuración inicial.</td>
    <td>Expansión internacional, nuevas tecnologías.</td>
    <td>Mercados con internet limitado, desarrollo de nichos.</td>
    <td>Mercados emergentes, alianzas locales.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competencia creciente y posibles cambios regulatorios.</td>
    <td>Competencia creciente, cambios regulatorios.</td>
    <td>Aumento de competidores con funciones más avanzadas.</td>
    <td>Competencia de POS más conocidos, cambios en demanda.</td>
  </tr>
</table>


<h4 id="strategy-tactics">2.1.2. Estrategias y tácticas frente a competidores.</h4>
#### Estrategias:

- Experiencia de usuario superior: Enfócate en crear una interfaz intuitiva, fácil de usar y visualmente atractiva. La facilidad de adopción y uso puede ser un factor clave para atraer a nuevos clientes.
- Prueba gratuita o demostración: Permite a los clientes potenciales probar tu software antes de comprometerse, lo que puede reducir la barrera de entrada.
- Precio competitivo: Si es posible, ofrece un precio más bajo que tus competidores, especialmente para atraer a pequeñas y medianas empresas.

#### Tacticas:
- Redes sociales: Utiliza las redes sociales para interactuar con tu audiencia, compartir contenido, promocionar tu software y generar conversaciones.
- Comparte historias de clientes satisfechos que hayan logrado resultados positivos con tu software. Esto puede ser muy persuasivo para los clientes potenciales.

<h4 id="interviews">2.2. Entrevistas.</h4>
<h4 id="interviews-design">2.2.1. Diseño de entrevistas.</h4>

#### Preguntas generales:

- ¿Cuáles considera que son los factores clave para el éxito de un restaurante en el mercado actual?
- ¿Qué características o funcionalidades considera esenciales en un software de gestión de restaurantes?
- ¿Qué papel juega la tecnología en la gestión y operación de un restaurante moderno?

#### Segmento objetivo: Administrador

- Cómo describiría el flujo típico de trabajo en su restaurante, desde la toma de pedidos hasta el servicio al cliente?
- ¿Cuáles son los mayores desafíos que enfrenta en la gestión diaria de su restaurante (ej: control de inventario, gestión de personal, satisfacción del cliente)?
- ¿Qué procesos o tareas le gustaría optimizar o automatizar en su restaurante?
- ¿Qué sistemas o herramientas tecnológicas utiliza actualmente en su restaurante (ej: punto de venta, sistema de reservas, software de contabilidad)? 
- ¿Está satisfecho con las herramientas tecnológicas que utiliza actualmente? ¿Por qué o por qué no?

#### Segmento objetivo: Proveedor

- ¿Qué tipo de productos o servicios ofrece a los restaurantes?
- ¿A qué tipo de restaurantes suministra principalmente (ej: tamaño, tipo de cocina, ubicación)?
- ¿Qué sistemas o herramientas utiliza actualmente para gestionar sus pedidos y la comunicación con los restaurantes?
- ¿Está satisfecho con las herramientas que utiliza actualmente? ¿Por qué o por qué no?
- ¿Cuáles son los principales desafíos que enfrenta en su negocio como proveedor de restaurantes?

<h4 id="interviews-registry">2.2.2. Registro de entrevistas.</h4>
<h4 id="interviews-analysis">2.2.3. Análisis de entrevistas.</h4>
<h4 id="needfinding">2.3. Needfinding.</h4>
<h4 id="user-personas">2.3.1. User Personas.</h4>

<img src = "/images/user-persona-1.png" alt="User Persona 1"/>
<h4 id="user-task-matrix">2.3.2. User Task Matrix.</h4>

| Tarea                                    | Persona                | Frecuencia | Importancia |
|------------------------------------------|------------------------|------------|-------------|
| Gestionar inventario y stock             | Laura, Administradora  | Diaria      | Alta        |
| Coordinar pedidos con proveedores        | Laura, Administradora  | Semanal     | Alta        |
| Gestionar comunicación con proveedores  | Laura, Administradora  | Diaria      | Media       |
| Revisar reportes de ventas               | Laura, Administradora  | Semanal     | Alta        |

<h4 id="user-journey-mapping">2.3.3. User Journey Mapping.</h4>

<img src="/images/user-journey-mapping.png" alt="user-journey-mapping">
<h4 id="empathy-mapping">2.3.4. Empathy Mapping.</h4>
<img src="/images/empathy-map-1.png" alt="empathy-mapping">

<h4 id="as-is-scenario-mapping">2.3.5. As-is Scenario Mapping.</h4>

<img src="/images/as-is-scenary-map.png" alt="as-is-scenary-map"/>
<h4 id="ubiquitous-language">2.4. Ubiquitous Language.</h4>

Definición del lenguaje común para el equipo de NoNucleus:

- Mesas: Áreas asignadas para los comensales en el restaurante, gestionadas por el módulo de mesas. 
- Reservas: Solicitudes de los clientes para asegurar una mesa en una fecha y hora específica, gestionadas por el módulo de reservas.
- Stock: Cantidad de insumos disponibles para preparar platos, gestionado por el módulo de stock.
- Merma: Pérdida de insumos por vencimiento o accidentes, registrada en el módulo de merma.
- Pedidos: Órdenes de insumos solicitadas a proveedores, gestionadas por el módulo de pedidos.

Este lenguaje será usado consistentemente en la documentación, comunicación y desarrollo del software para asegurar claridad y evitar malentendidos.

<h3 id="chapter-3">Capítulo III: Requirements Specification</h3>
<h4 id="to-be-scenario-mapping">3.1. To-Be Scenario Mapping.</h4>
<h4 id="user-stories">3.2. User Stories.</h4>
<h4 id="impact-mapping">3.3. Impact Mapping.</h4>
<h4 id="product-backlog">3.4. Product Backlog.</h4>
<h3 id="chapter-4">Capítulo IV: Product Design</h3>
<h4 id="style-guidelines">4.1. Style Guidelines.</h4>
<h4 id="general-style-guidelines">4.1.1. General Style Guidelines.</h4>
<h4 id="web-style-guidelines">4.1.2. Web Style Guidelines.</h4>
<h4 id="information-architecture">4.2. Information Architecture.</h4>
<h4 id="organization-systems">4.2.1. Organization Systems.</h4>
<h4 id="labeling-systems">4.2.2. Labeling Systems.</h4>
<h4 id="seo-tags-and-meta-tags">4.2.3. SEO Tags and Meta Tags</h4>
<h4 id="searching-systems">4.2.4. Searching Systems.</h4>
<h4 id="navigation-systems">4.2.5. Navigation Systems.</h4>
<h4 id="landing-page-ui">4.3. Landing Page UI Design.</h4>
<h4 id="landing-page-wireframe">4.3.1. Landing Page Wireframe.</h4>
<h4 id="landing-page-mockup">4.3.2. Landing Page Mock-up.</h4>
<h4 id="web-application-ux-ui">4.4. Web Applications UX/UI Design.</h4>
<h4 id="web-application-wireframes">4.4.1. Web Applications Wireframes.</h4>
<h4 id="web-application-wireflow">4.4.2. Web Applications Wireflow Diagrams.</h4>
<h4 id="web-appliaction-mockups">4.4.2. Web Applications Mock-ups.</h4>
<h4 id="user-flow-diagrams">4.4.3. Web Applications User Flow Diagrams.</h4>
<h4 id="web-applications-prototyping">4.5. Web Applications Prototyping.</h4>
<h4 id="domain-driven-software-architecture">4.6. Domain-Driven Software Architecture.</h4>
<h4 id="software-architecture-context-diagram">4.6.1. Software Architecture Context Diagram.</h4>
<h4 id="software-architecture-container-diagrams">4.6.2. Software Architecture Container Diagrams.</h4>
<h4 id="software-architecture-components-diagrams">4.6.3. Software Architecture Components Diagrams.</h4>
<h4 id="software-object-oriented-design">4.7. Software Object-Oriented Design.</h4>
<h4 id="class-diagrams">4.7.1. Class Diagrams.</h4>
<h4 id="class-dictionary">4.7.2. Class Dictionary.</h4>
<h4 id="database-design">4.8. Database Design.</h4>
<h4 id="database-diagram">4.8.1. Database Diagram.</h4>
<h3 id="chapter-5">Capítulo V: Product Implementation, Validation & Deployment</h3>
<h4 id="software-configuration">5.1. Software Configuration Management.</h4>
<h4 id="software-development">5.1.1. Software Development Environment Configuration.</h4>
<h4 id="source-code">5.1.2. Source Code Management.</h4>
<h4 id="source-code-style-guide-and-conventions">5.1.3. Source Code Style Guide & Conventions.</h4>
<h4 id="software-deployment-configuration">5.1.4. Software Deployment Configuration.</h4>
<h4 id="landing-page-services-applications-implementation">5.2. Landing Page, Services & Applications Implementation.</h4>
<h4 id="sprint-x">5.2.X. Sprint n</h4>
<h4 id="sprint-planning-x">5.2.X.1. Sprint Planning n.</h4>
<h4 id="spring-backlog-x">5.2.X.2. Sprint Backlog n.</h4>
<h4 id="development-evidence-for-sprint-review-x">5.2.X.3. Development Evidence for Sprint Review.</h4>
<h4 id="testing-suite-evidence-for-sprint-review">5.2.X.4. Testing Suite Evidence for Sprint Review.</h4>
<h4 id="execution-evidence-for-sprint-review">5.2.X.5. Execution Evidence for Sprint Review.</h4>
<h4 id="services-documentation-evidence-for-sprint-review">5.2.X.6. Services Documentation Evidence for Sprint Review.</h4>
<h4 id="software-deployment-evidence-for-sprint-review">5.2.X.7. Software Deployment Evidence for Sprint Review.</h4>
<h4 id="team-collaboration-insights-during-sprint">5.2.X.8. Team Collaboration Insights during Sprint.</h4>
<h4 id="validation-interviews">5.3. Validation Interviews.</h4>
<h4 id="interview-design-2">5.3.1. Diseño de Entrevistas.</h4>
<h4 id="interview-registry-2">5.3.2. Registro de Entrevistas.</h4>
<h4 id="heuristic-exam">5.3.3. Evaluaciones según heurísticas.</h4>
<h4 id="about-the-productions">5.4. Video About-the-Product.</h4>
<h4 id="conclusions">Conclusiones</h4>
<h4 id="recomendations">Conclusiones y recomendaciones.</h4>
<h4 id="about-the-team">Video About-the-Team.</h4>
<h4 id="bibliography">Bibliografía</h4>
<h4 id="links">Anexos</h4>


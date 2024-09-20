
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

En esta sección se identifican los principales competidores que ofrecen productos digitales similares o parcialmente equivalentes. Entre ellos se destacan soluciones como Toast, TouchBistro e Inforest, cada uno con enfoques específicos en la gestión y la automatización en restaurantes.

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

- Entrevista 1: Darla

<img src="/images/interview/user-1.png">

* Sexo: Femenino
* Edad: 25 años
* Distrito donde vive: Lima

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212236_upc_edu_pe/Eah7IXHNlLROtk69nE4K6cUBbecC-4xR--jhWgPOahtegg?e=uohWdA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

* Momento en el que inicia: 0:00
* Duracion: 2:25
* Entrevistador: David Bryan Rodriguez Santos
* Resumen:

Darla es una mujer de 25 años que vive en Lima. Destaca como factores clave para el éxito de un restaurante la buena calidad de la comida y el control del inventario. Considera esencial en un software de gestión la integración de los módulos, la automatización de procesos y el acceso móvil. El flujo típico en su restaurante incluye tomar pedidos, transmitirlos a la cocina, servir la comida y revisar las ventas. Los mayores desafíos que enfrenta son el control del inventario y la coordinación del personal. Le gustaría optimizar la gestión del inventario y automatizar el seguimiento del personal. Actualmente, usan un sistema POS, software de reservas y contabilidad, pero siente que la falta de integración entre ellos es un problema. Es soltera con ingresos medios y trabaja como gerente de restaurante. Utiliza principalmente smartphone y laptop, y se comunica a través de WhatsApp, correo electrónico y redes sociales profesionales. Es proactiva, orientada a la eficiencia, con habilidades en gestión de personal y operaciones. Está interesada en tecnologías innovadoras para la industria de la restauración. Sus objetivos son mejorar la eficiencia operativa del restaurante e implementar sistemas integrados de gestión. Sus frustraciones incluyen sistemas desconectados que dificultan el control total del negocio y la pérdida de tiempo en procesos manuales. Tiene cinco años de experiencia en la industria y busca constantemente maneras de innovar y mejorar la experiencia tanto para el personal como para los clientes.

- Entrevista 2: Vanfic Gustavok

<img src="/images/interview/m.jpeg"> 

* Sexo: Masculino
* Edad: 49 años
* Distrito donde vive: Lima

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202220250_upc_edu_pe/ET0b7nkH9IZDviA0pdi0o9QBh9uleEn3GtrOeE16Mgkniw?e=d3Er84&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


* Momento en el que inicia: 4:24
* Duracion: 2:20
* Entrevistador: Mateo Loechle

* Resumen:

Vanfic Gustavok es un hombre de 49 años que vive en Lima. Durante una entrevista con Mateo Loechle que comenzó en el minuto 4:24 y duró 2 minutos y 20 segundos, compartió su visión sobre las funcionalidades esenciales de un software de gestión de restaurantes. Vanfic cree que dicho software debe incluir gestión de mesas y reservas, control de inventario, seguimiento de ventas, gestión de pedidos en cocina, integración con proveedores y capacidades de análisis y reportes financieros. Considera que estas funciones son cruciales para automatizar procesos y optimizar las operaciones diarias.
Como propietario de un restaurante desde hace más de diez años, ha experimentado las dificultades de manejar múltiples sistemas no integrados. Utiliza dispositivos como smartphones y laptops para sus tareas diarias y se comunica principalmente a través de correo electrónico y aplicaciones de mensajería instantánea. Valora la eficiencia y está en constante búsqueda de tecnologías que le permitan mejorar la gestión de su negocio.
Vanfic se siente frustrado por la falta de integración entre los diferentes sistemas que utiliza actualmente, como el POS, el software de reservas y las herramientas de contabilidad. Su objetivo es encontrar una solución unificada que le facilite el control total de su negocio, reduciendo la carga de trabajo manual y minimizando errores. Es una persona detallista y orientada a la mejora continua, siempre buscando innovar y ofrecer una mejor experiencia tanto para su equipo como para sus clientes.

- Entrevista 1: Anghelo Basauri

<img src="/images/interview/ha.jpeg">

* Sexo: Masculino
* Edad: 27 años
* Distrito donde vive: Rimac

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202220250_upc_edu_pe/ET0b7nkH9IZDviA0pdi0o9QBh9uleEn3GtrOeE16Mgkniw?e=d3Er84&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

* Momento en el que inicia: 4:24
* Duracion: 3:12
* Entrevistador: Hardie Holguín

* Resumen:

Anghelo Basauri es un hombre de 27 años que vive en el distrito de Rímac. La entrevista, realizada por Hardie Holguín, comenzó a las 4:24 y tuvo una duración de 3 minutos y 12 segundos. Entre los mayores desafíos que menciona se encuentran el control preciso del inventario, garantizar la calidad constante de los platos, gestionar eficazmente al personal y proporcionar una excelente experiencia al cliente. También encuentra complicado manejar la logística de los proveedores y las fluctuaciones en la demanda.
Anghelo desea optimizar la gestión de inventario y pedidos para asegurar que siempre haya suficientes insumos sin sobrecargar el stock. Le gustaría automatizar la comunicación con los proveedores para reducir tiempos de respuesta y minimizar errores. Es gerente de un restaurante y utiliza dispositivos como smartphones y laptops para sus tareas diarias. Se comunica principalmente a través de correo electrónico y aplicaciones de mensajería instantánea. Valora la tecnología como una herramienta para mejorar la eficiencia operativa y está interesado en soluciones que le ayuden a superar los desafíos mencionados.

- Entrevista 1: Keyner Hancco

<img src="/images/interview/hk.jpeg">
* Sexo: Masculino
* Edad: 25 años
* Distrito donde vive: Santa Anita

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202220250_upc_edu_pe/ET0b7nkH9IZDviA0pdi0o9QBh9uleEn3GtrOeE16Mgkniw?e=d3Er84&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

* Momento en el que inicia: 7:10
* Duracion: 5:32
* Resumen: Hardie Holguín

* Analisis:

Keyner Hancco es un hombre de 25 años que vive en Santa Anita. Fue entrevistado por Hardie Holguín, comenzando a las 7:10 y con una duración de 5 minutos y 32 segundos. Para él, la rapidez y precisión en el servicio son aspectos críticos, junto con la facilidad para realizar reservas y pedidos. Considera fundamental mejorar la comunicación entre el personal y los clientes para garantizar que sus necesidades sean atendidas eficientemente. En general, está satisfecho con las herramientas que utiliza, aunque cree que siempre hay margen de mejora. Le gustaría que algunas funciones fueran más intuitivas y que la integración con los proveedores fuera más fluida. También menciona que la personalización de ciertos reportes sería una mejora importante. Es soltero, supervisor en un restaurante de comida rápida, con ingresos medios. Utiliza smartphone y tablet, y se comunica a través de WhatsApp, correo electrónico y aplicaciones de gestión de restaurantes. Es proactivo, orientado al cliente, con habilidades en gestión de equipos y resolución de problemas. Está interesado en tecnología móvil y aplicaciones que mejoren la eficiencia operativa. Sus objetivos son mejorar la experiencia del cliente mediante servicios más rápidos y precisos e implementar sistemas que faciliten las reservas y pedidos en línea. Sus frustraciones incluyen herramientas poco intuitivas que dificultan el flujo de trabajo e integración deficiente con proveedores que causa demoras. Tiene cinco años de experiencia en la industria de la restauración y siempre busca formas de implementar soluciones digitales que mejoren tanto la eficiencia operativa como la satisfacción del cliente.

- Entrevista 1: Elismar Sarmiento

<img src="/images/interview/gl.jpeg">

* Sexo: Femenino
* Edad: 25 años
* Distrito donde vive: Callao

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202220250_upc_edu_pe/ET0b7nkH9IZDviA0pdi0o9QBh9uleEn3GtrOeE16Mgkniw?e=d3Er84&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


* Momento en el que inicia: 12:57
* Duracion: 4:10
* Entrevistador: Gabriel Braihuate
* Resumen:

Elismar Sarmiento es una mujer de 25 años que vive en Pueblo Libre, Lima, Perú. Está casada y tiene ingresos medios. Utiliza Google Chrome como buscador principal y LinkedIn es su canal principal de interacción digital. Trabaja en el área de proveedores, donde sus funciones incluyen el contacto directo con clientes, organizar pedidos y entregas, y gestionar la información relacionada. Cree que la calidad de los alimentos utilizados en los restaurantes es clave para su éxito y que la tecnología es importante para la gestión y comunicación con los clientes. Ofrece productos de alta calidad como verduras, frutas, lácteos y especias, principalmente a restaurantes, casinos y hoteles. Utiliza WhatsApp y Outlook para comunicarse y Excel para gestionar los pedidos, pero no está completamente satisfecha con estas herramientas porque le resulta tedioso transferir datos del correo a Excel y a veces los pedidos se pierden en WhatsApp o correo debido al gran volumen de mensajes. Su principal dificultad es la comunicación con sus clientes.

<h4 id="interviews-analysis">2.2.3. Análisis de entrevistas.</h4>

#### Administrador de Restaurante:

Durante las entrevistas con los administradores de restaurante, se identificaron varios puntos clave que destacan sus principales necesidades y desafíos. En primer lugar, enfatizaron la importancia de contar con un sistema eficiente para gestionar las reservas y la asignación de mesas, ya que una mala organización en este aspecto puede afectar negativamente la experiencia del cliente. Asimismo, señalaron la necesidad de una herramienta integral que permita un control exhaustivo del inventario y de los proveedores, lo cual impacta directamente en la reducción de costos y en la optimización del proceso de abastecimiento.
Un tema recurrente fue la importancia de generar reportes y estadísticas en tiempo real, especialmente en relación con las ventas, el desperdicio de alimentos y el uso de ingredientes. Los administradores valoran la capacidad de tener un cierre de caja detallado y preciso, así como una visión clara de la rentabilidad de cada plato para mejorar la toma de decisiones estratégicas. También destacaron desafíos como garantizar la calidad constante de los platos, gestionar eficazmente al personal y mejorar la comunicación entre el equipo y los clientes para atender sus necesidades de manera eficiente.
Además, manifestaron que la falta de integración entre los sistemas actuales (como POS, software de reservas y contabilidad) es un problema común. Desean herramientas más intuitivas que permitan una mejor integración con los proveedores y la personalización de reportes. La automatización de procesos, como el seguimiento del personal y la gestión de pedidos en cocina, fue mencionada como una mejora importante para optimizar las operaciones diarias.

#### Proveedor:

En cuanto a los proveedores, las entrevistas revelaron que su principal interés radica en la simplificación y mejora de la comunicación con los restaurantes. Mencionaron la importancia de contar con un sistema que les permita gestionar pedidos de manera más ágil y estructurada, evitando errores y reduciendo el tiempo de espera entre la orden y la entrega. La comunicación a través de herramientas como WhatsApp y correo electrónico a veces resulta ineficiente, llevando a la pérdida de pedidos y a procesos tediosos como la transferencia manual de datos.
Los proveedores expresaron la necesidad de tener visibilidad sobre las previsiones de demanda y el historial de compras de los restaurantes, lo que les ayudaría a planificar mejor su producción y entrega. También valoran los sistemas que permiten una integración directa con los inventarios de los restaurantes, de modo que puedan ajustar sus ofertas y volúmenes de productos según las necesidades reales del cliente, mejorando así la eficiencia en toda la cadena de suministro. Consideran que la tecnología juega un rol crucial en modernizar estas interacciones y en facilitar una gestión más eficiente y efectiva de los pedidos y comunicaciones.

<h4 id="needfinding">2.3. Needfinding.</h4>
<h4 id="user-personas">2.3.1. User Personas.</h4>

#### Segmento: Administrador de restaurantes

Martín es un proveedor de insumos gastronómicos de 42 años. Su principal objetivo es establecer relaciones comerciales duraderas con restaurantes, automatizar pedidos y ofrecer un servicio confiable. Tiene buena organización, pero nivel medio en tecnología. Está frustrado por la falta de sistemas centralizados y la competencia que ofrece precios bajos. Prefiere canales como LinkedIn y las interacciones cara a cara.

<img src = "/images/user-persona/user-persona-1.png" alt="User Persona 1"/>

#### Segmento: Proveedor

Laura es administradora de un restaurante de 45 años. Busca optimizar la gestión, reducir desperdicios y mejorar la satisfacción del cliente. Tiene experiencia en organización y se maneja bien con la tecnología. Sus principales frustraciones son la falta de integración de sistemas y el desperdicio de insumos. Sus canales favoritos son Facebook, LinkedIn y las interacciones cara a cara.

<img src = "/images/user-persona/user-persona-2.png" alt="User Persona 2"/>

<h4 id="user-task-matrix">2.3.2. User Task Matrix.</h4>


| **Tareas**                                        | **Frecuencia** | **Usuario Principal** | **Objetivo del Usuario**                                                                 | **Frustraciones del Usuario**                                                                 | **Oportunidades de la Plataforma**                                                                                           |
|---------------------------------------------------|----------------|-----------------------|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Gestionar pedidos de insumos**                  | Diaria          | Ambos                 | Laura solicita insumos y Martín los procesa y gestiona                                  | Laura: Dificultad para controlar el inventario <br> Martín: Errores manuales en los pedidos    | Automatización en tiempo real de los pedidos y gestión del inventario para reducir errores y mejorar tiempos de entrega.      |
| **Coordinar entregas y logística**                | Diaria          | Ambos                 | Martín organiza el envío y Laura recibe los insumos puntualmente                        | Laura: Entregas retrasadas <br> Martín: Mala coordinación logística                           | Sistema de seguimiento en tiempo real que notifique a ambos usuarios del estado de las entregas.                              |
| **Monitorear niveles de stock**                   | Semanal         | Laura                 | Mantener el stock en niveles óptimos para evitar escasez o sobreabastecimiento           | Laura: Desperdicio de insumos o escasez de productos                                          | Plataforma que automatice la actualización de stock, basada en los pedidos y las ventas del restaurante.                      |
| **Actualizar catálogo de productos**              | Semanal         | Martín                | Asegurar que sus clientes vean los productos disponibles y ofertas                      | Martín: Falta de visibilidad de su catálogo de productos                                      | Sección centralizada donde Martín pueda actualizar su catálogo y Laura acceda a él en tiempo real, incluyendo ofertas.        |
| **Negociar condiciones de compra y precios**      | Mensual         | Ambos                 | Laura busca precios competitivos y Martín quiere establecer relaciones comerciales sólidas | Martín: Competencia con precios bajos <br> Laura: Falta de opciones competitivas            | Funcionalidad para negociar directamente desde la plataforma, agilizando acuerdos y condiciones comerciales.                   |
| **Generar y enviar facturas**                     | Semanal         | Ambos                 | Martín necesita facturar y Laura debe controlar los gastos del restaurante               | Martín: Falta de automatización en la facturación <br> Laura: Problemas para controlar costos | Facturación automática vinculada a los pedidos, con reportes que faciliten la administración y el control financiero.         |
| **Revisar informes de pedidos y consumo**         | Mensual         | Ambos                 | Evaluar el rendimiento de los productos, las ventas y los pedidos                        | Laura: Falta de información clara sobre el uso de insumos <br> Martín: Poca visibilidad de ventas | Informes detallados que incluyan estadísticas de pedidos, ventas y stock, para tomar mejores decisiones estratégicas.        |
| **Ofrecer descuentos y promociones**              | Ocasional       | Martín                | Atraer nuevos clientes y fidelizar a los actuales                                        | Martín: Poca visibilidad de sus ofertas                                                       | Plataforma que permita la creación y promoción de descuentos y ofertas, visibles para clientes como Laura.                    |
| **Gestionar devoluciones y reclamos**             | Ocasional       | Ambos                 | Resolver incidencias relacionadas con la calidad o entrega de los insumos                | Laura: Mala calidad o entregas tardías <br> Martín: Reclamos que afectan la relación comercial | Integrar una funcionalidad para gestionar devoluciones y reclamos, facilitando la comunicación y resolución rápida.            |
| **Capacitar al equipo en nuevas herramientas**    | Ocasional       | Laura                 | Asegurar que su equipo use eficientemente la plataforma para optimizar operaciones       | Laura: Dificultad de su equipo para adaptarse a nuevas tecnologías                            | Tutoriales integrados en la plataforma y soporte técnico para facilitar el aprendizaje del equipo de Laura.                   |
| **Solicitar informes de disponibilidad de productos** | Ocasional    | Laura                 | Verificar la disponibilidad de productos antes de hacer pedidos                         | Laura: Falta de información actualizada sobre la disponibilidad                               | Sistema en tiempo real que muestre la disponibilidad de insumos, facilitando la planificación de pedidos.                    |


<h4 id="user-journey-mapping">2.3.3. User Journey Mapping.</h4>

#### Segmento: Administrador de restaurantes

Los usuarios sienten ansiedad por la curva de aprendizaje del equipo, lo que destaca la necesidad de mejorar la accesibilidad del producto y ofrecer tutoriales más fáciles de seguir.
A pesar de la satisfacción con la reducción de desperdicios, los usuarios expresan frustraciones con la interfaz, lo que sugiere oportunidades para recibir retroalimentación constante y mejorar la usabilidad del sistema.

<img src="/images/user-journey-mapping/user-journey-mapping-1.png" alt="user-journey-mapping-1">

#### Segmento: Proveedor

Los usuarios buscan automatizar la gestión de pedidos, pero tienen preocupaciones sobre la compatibilidad con sus sistemas actuales, lo que indica la importancia de resaltar la facilidad de integración en los materiales promocionales.
Aunque se muestra satisfacción con la reducción de errores, los usuarios aún experimentan frustraciones con algunos aspectos de la interfaz, lo que señala la necesidad de mejorar y personalizarla, especialmente para proveedores.

<img src="/images/user-journey-mapping/user-journey-mapping-2.png" alt="user-journey-mapping-2">

<h4 id="empathy-mapping">2.3.4. Empathy Mapping.</h4>

#### Segmento: Administrador de restaurantes

Los usuarios sienten ansiedad por posibles fallas del sistema y buscan mejorar la eficiencia del personal, sintiendo alivio cuando las operaciones fluyen sin problemas.
Escuchan quejas de clientes sobre demoras en pedidos, sugerencias del personal para mejorar procesos y notificaciones del sistema sobre inventarios bajos.
Suelen ver informes de stock y ventas, menús, listas de precios, reservas y pedidos en línea, además de los movimientos del personal.

<img src="/images/empathy-map/empathy-map-1.png" alt="empathy-mapping-1">

#### Segmento: Proveedor

Los usuarios se preocupan por la exactitud y puntualidad de los pedidos, con ansiedad sobre la compatibilidad de NoNucleus con sus sistemas actuales, aunque sienten alivio cuando las entregas son sin complicaciones.
Escuchan comentarios sobre la puntualidad de los pedidos, sugerencias de clientes para mejorar la entrega y notificaciones del sistema sobre nuevos pedidos.
Observan detalles de pedidos recibidos y pendientes en NoNucleus, notificaciones de cambios en las solicitudes y reportes sobre cantidad y tiempos de entrega.

<img src="/images/empathy-map/empathy-map-2.png" alt="empathy-mapping-2">

<h4 id="as-is-scenario-mapping">2.3.5. As-is Scenario Mapping.</h4>

#### Segmento: Administrador de restaurantes

Pasos y acciones: Llega temprano, revisa inventario y stock, asigna tareas al personal, supervisa las operaciones, resuelve problemas del día y cierra revisando ventas e inventario.
Pensamientos: Preocupación por el stock y las responsabilidades del personal, buscando asegurar eficiencia en el servicio y resolver problemas rápidamente. Al final del día, reflexiona sobre posibles mejoras para mañana.
Sentimientos: Preocupación, ansiedad al inicio del día, satisfacción tras una buena jornada, frustración ante problemas y alivio al cerrar el día.

<img src="/images/as-is-scenary-map/as-is-scenary-map-1.png" alt="as-is-scenary-map-1"/>

#### Segmento: Proveedor

Pasos y acciones: Inicia revisando pedidos, verifica que estén organizados, coordina las rutas de entrega, supervisa las entregas, recibe feedback y actualiza NoNucleus.
Pensamientos: Preocupación por el stock y la organización de los pedidos, buscando que las entregas sean puntuales y sin errores. Reflexiona sobre problemas potenciales y cómo mejorar la próxima vez.
Sentimientos: Preocupación y ansiedad al inicio, determinación durante el proceso, frustración si surgen problemas y alivio tras recibir feedback y cerrar el día.

<img src="/images/as-is-scenary-map/as-is-scenary-map-2.png" alt="as-is-scenary-map-2"/>

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
<p>
    En este capítulo se desarrollará las bases para contar con un repositorio central y organizado de uso común que incluye assets, fonts. Esto con el fin de mantener una presentación consistente y enfocada
    </p>
    <p>Dentro de las dimensiones que adoptaremos en le tono de comunicación y lenguaje aplicado tendremos que será serio, formal, respetuoso y sereno ya que se trata del manejo de inventario de una empresa del rubro de restaurantes lo cual requiere todo lo mencionado.
</p>
<h4 id="style-guidelines">4.1. Style Guidelines.</h4>
<h4 id="general-style-guidelines">4.1.1. General Style Guidelines.</h4>


Branding:

- Este logo simboliza nuestro rubro a la administracion de inventarios para restaurantes. Al obtener nuestros servicios, las empresan podrán tener mejores margenes de ganancias al mejorar su administracion
    <img src="/images/RE-GRILL.png"></img><br>

Typography:
- La tipografía de nuestro logo tendrá un estilo marcado el cual es Arial teniendo diversas ventajas, especialmente en términos de legibilidad, compatibilidad y simplicidad. Con esta tipografía reflejamos la innovación así como la creatividad que es lo que sobresale de nuestra aplicación.
- Otro factor por el cual elegimos Arial se debe a su gran rendimiento dado que es una tipografía preinstalada, lo que hace que no sea necesario cargarla desde un servidor externo, reduciendo el tiempo de carga de la página web.

Colors:
- Nosotros elegimos la paleta de colores para que el usuario al visitar nuestro sitio web ellos se sientan cómodos y que sobre todo les brinde seguridad y confort. El azul oscuro (#004080) demuestra confianza, profesionalismo y estabilidad. El blanco (#ffffff)
  <img src="/images/COLORES-WEB.png"></img><br> 

    

<h4 id="web-style-guidelines">4.1.2. Web Style Guidelines.</h4>

Icons:
- Al desarrollar una página web, los ícenos son fundamentales para crear una interfaz de usuario que sea clara e intuitiva. Estos pequeños elementos visuales son clave para facilitar la comprensión de distintas secciones de la página web. Los íconos ayudan a lo usuarios a identifica rápidamente la función de cada componente , y su diseño simple y claro garantiza que sean fácilmente interpretables, además, usar íconos de manera coherente en toda la página es esencial para reducir la confusión y mejorara la experiencial de usuario.
- Los íconos que utilizaremos serán los breakpoints, de los cuales usaremos con mayor frecuencia serán los 768px y 1024px, debido a que son los más comunes del mercado actual.


<h4 id="information-architecture">4.2. Information Architecture.</h4>
<h4 id="organization-systems">4.2.1. Organization Systems.</h4>

- Al entrar a nuestra página web, el usuario podrá visualizar diferentes secciones: inicio, Request Demo, about us, plans, contacto Us.

<h4 id="labeling-systems">4.2.2. Labeling Systems.</h4>

- En nuestra página web tendremos un sistema de etiquetado que son los siguientes: 
* About Us 
* Features 
* Plans
* benefits
* Q&A
* Contact Us
* Idioma


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


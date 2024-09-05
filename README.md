
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

            <td>u202011657</td>
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
<h4 id="competitive-analysis">2.1.1. Análisis competitivo.</h4>
<h4 id="strategy-tactics">2.1.2. Estrategias y tácticas frente a competidores.</h4>
<h4 id="interviews">2.2. Entrevistas.</h4>
<h4 id="interviews-design">2.2.1. Diseño de entrevistas.</h4>
<h4 id="interviews-registry">2.2.2. Registro de entrevistas.</h4>
<h4 id="interviews-analysis">2.2.3. Análisis de entrevistas.</h4>
<h4 id="needfinding">2.3. Needfinding.</h4>
<h4 id="user-personas">2.3.1. User Personas.</h4>
<h4 id="user-task-matrix">2.3.2. User Task Matrix.</h4>
<h4 id="user-journey-mapping">2.3.3. User Journey Mapping.</h4>
<h4 id="empathy-mapping">2.3.4. Empathy Mapping.</h4>
<h4 id="as-is-scenario-mapping">2.3.5. As-is Scenario Mapping.</h4>
<h4 id="ubiquitous-language">2.4. Ubiquitous Language.</h4>
<h3 id="chapter-3">Capítulo III: Requirements Specification</h3>
<h4 id="to-be-scenario-mapping">3.1. To-Be Scenario Mapping.</h4>

<img src="/images/ad.jpeg"></img><br>
<img src="/images/pr.jpeg"></img><br>
 
<h4 id="user-stories">3.2. User Stories.</h4>

| Epic / Story ID 	    | Título 	                                                | Descripción 	                                                                                                                                                                                                                                                 | Criterios de Aceptación 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Relacionado con Epic ID 	                                                                            |
|----------------------|---------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| EP01               	 | Gestión de Inventario y Stock	                          | *Como* administrador *Quiero* gestionar eficientemente el inventario y stock del restaurante *Para* asegurar que los ingredientes estén siempre disponibles y reducir el desperdicio.                                                                         | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP02               	 | Optimización del Costo de Producción y Facturación	     | *Como* administrador *Quiero* calcular y optimizar el costo de producción y gestionar la facturación *Para* asegurar la rentabilidad del restaurante.                                                                                                         | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP03               	 | Control y Reporte de Uso de Ingredientes  	             | *Como* administrador *Quiero* llevar un control detallado de la merma y generar reportes sobre el uso de ingredientes *Para* optimizar la gestión del inventario.                                                                                             | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP04               	 | Operaciones Eficientes en la Caja 	                     | *Como* administrador *Quiero* realizar operaciones de cierre de caja detallado y gestionar las transacciones de manera precisa *Para* asegurar una contabilidad clara.                                                                                        | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP06               	 | Landing Page Optimizada	                                | *Como* usuario interesado, *Quiero* una página de destino fácil de usar y optimizada que ofrezca información clara y accesible sobre la aplicación *Para* facilitar la toma de decisiones informadas y mejorar la interacción con el equipo de la aplicación. | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP07               	 | Gestión de Reservas	                                    | *Como* administrador *Quiero* gestionar las reservas de mesas de manera eficiente *Para* asegurar un servicio rápido y eficiente.                                                                                                                             | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP08              	  | Contactar restaurante                                   | Como proveedor  Quiero contactar al restaurante en el que estoy interesado Para llegar a un acuerdo y establecer una alianza                                                                                                                                  | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP09              	  | Gestion de mesas y sillas                               | Como cliente Quiero reservar una mesa en el restaurante Para asegurarme de tener un lugar disponible en el restaurante                                                                                                                                        | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP10                 | Gestión de Proveedores                                  | Como proveedor, quiero gestionar mis datos para mantener un registro actualizado con el restaurante.                                                                                                                                                          | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde                                                                                       |
| EP11                 | Evaluación de Proveedores                               | Como administrador, quiero evaluar a los proveedores para asegurar la calidad de los productos.                                                                                                                                                               | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde          |
| US-01             	  | Acceso a Cantidades de Stock                            | Como administrador, quiero acceder a las cantidades actuales de stock para planificar la producción y las compras.                                                                                                                                            | <b>Scenario 01:</b> Ver Cantidades Disponibles Dado</b> que soy administrador<br>Cuando</b> acceda al sistema de gestión de inventario<br>Entonces</b>  podré ver las cantidades actuales de cada ingrediente en stock, y el sistema mostrará alertas cuando el stock esté por debajo de un nivel predefinido.<br><br> Scenario 02:</b> Recibir Notificación de Bajo Stock<br>Dado</b>  que el stock de un ingrediente está bajo,<br>Cuando</b>  acceda al sistema de gestión de inventario,<br>Entonces</b> recibiré una notificación de bajo stock para que pueda tomar medidas inmediatas.    | EP01                                                                                                 |
| US-02             	  | Ingreso de Stock                                        | Como proveedor, quiero registrar nuevas entradas de inventario para mantener un registro actualizado de los ingredientes que ingrese.                                                                                                                         | <b>Scenario 01:</b> Registrar Nuevas Entradas<br>Dado que soy administradorCuando</b> reciba un nuevo lote de ingredientes,<br>Entonces</b>puedo registrar esta entrada en el sistema con la cantidad y la fecha de ingreso, y el sistema actualizará automáticamente el stock disponible.<br><br>Scenario 02:</b> Verificar Registro de Entrada<br>Dado</b> que he registrado una nueva entrada de stock,<br>Cuando</b> revise el registro<br>Entonces</b>  podré ver la nueva entrada registrada con todos los detalles correspondientes.<br><br>                                              | EP01                                                                                                 |
| US-03             	  | Tomar Pedidos desde la Mesa                             | Como administrador, quiero introducir pedidos directamente en la aplicación desde la mesa para que estos se envíen automáticamente a la cocina.                                                                                                               | <b>Scenario 01:</b>Tomar Pedidos desde la Mesa<br><b>Dado</b> que estoy tomando un pedido,<br><b>Cuando</b> introduzca los ítems en la aplicación,<br><b>Entonces</b> estos deben enviarse automáticamente al sistema de cocina.<br><br><b>Scenario 02:</b> Modificar Pedido Antes de Enviar<br> <b>Dado</b>  que he tomado un pedido,<br><b>Cuando</b>  el cliente haga una modificación,<br><b>Entonces</b>  el sistema debe permitir la modificación del pedido antes de enviarlo a la cocina.<br><br>                                                                                        | EP07                                                                                                 |
| US-04             	  | Cálculo del Costo de Producción                         | Como administrador, quiero consultar el costo de los ingredientes por plato para ajustar precios o recetas según sea necesario.                                                                                                                               | <b>Scenario 01:</b> Consultar Costos de Producción<br>Dado</b> que soy administrador,<br>Cuando</b> acceda a un plato específico<br>Entonces</b>el sistema debe mostrar el costo detallado de cada ingrediente y el costo total de producción del plato.<br><br>Scenario 02:</b> Modificar Receta y Recalcular Costos<br>Dado</b>  que quiero ajustar una receta,<br>Cuando</b> modifique los ingredientes en el sistema,<br>Entonces</b>  el sistema debe recalcular automáticamente el costo de producción del plato y actualizarlo en la base de datos.<br><br>                               | EP02                                                                                                 |
| US-05             	  | Reporte de Uso de Ingredientes                          | Como administrador, quiero ver estadísticas sobre el uso de ingredientes para ajustar los pedidos y optimizar la producción.                                                                                                                                  | Scenario 01:</b> Generar Reporte de Uso de Ingredientes<br>Dado</b> que soy administrador,<br>Cuando</b>  acceda a los reportes de uso de ingredientes,<br>Entonces</b> el sistema debe mostrar gráficos y estadísticas detalladas del uso de cada ingrediente durante un período específico.<br><br>Scenario 02:</b>  Ajustar Pedidos Basado en el Reporte<br>Dado</b>  que he revisado el reporte de uso de ingredientes,<br>Cuando</b> note un aumento en el uso de ciertos ingredientes,<br>Entonces</b> podré ajustar los pedidos para evitar la escasez y optimizar la producción.<br><br> | EP03                                                                                                 |
| US-06             	  | Landing page - Estructuración                           | Como visitante de la landing page, quiero encontrar una navegación intuitiva que me permita acceder fácilmente a la información sobre sus características.                                                                                                    | Escenario 1: "Landing page estructurada" Dado que el visitante está en la landing page, cuando el visitante accede a la página principal, entonces la landing page ofrece los medios necesarios para una navegación fácil y clara. Escenario 2: "Organización no intuitiva"Dado que el visitante está en la landing page, cuando el visitante accede a la página principal, entonces la landing page no proporciona formas de navegación amigables para el usuario.                                                                                                                              | EP06                                                                                                 |
| US-07             	  | Landing page – Contenido informativo                    | Como visitante de la landing page, quiero encontrar contenido detallado y fácil de entender sobre las funcionalidades y beneficios de la aplicación para poder tomar una decisión informada sobre su uso.                                                     | Escenario 1: "Contenido landing page"Dado que el visitante está en la landing page, cuando el visitante navega por la landing page, entonces la página presenta información clara, fácil de entender y accesible para cualquier visitante.Escenario 2: "Contenido confuso o insuficiente" Dado que el visitante está en la landing page, cuando el visitante navega por la landing page, entonces la página no ofrece información clara, lo que la hace inaccesible para diferentes visitantes.                                                                                                  | EP06                                                                                                 |
| US-08             	  | Landing page - Compatibilidad móvil                     | Como visitante de la landing page, quiero que sea responsiva para poder utilizarla en cualquier dispositivo.                                                                                                                                                  | Escenario 1: "Compatibilidad con dispositivos móviles"Dado que el visitante está en la landing page, cuando el visitante accede a la landing page desde su dispositivo móvil, entonces puede navegar por la página sin problemas.Escenario 2: "Problemas de visualización o navegación"Dado que el visitante está en la landing page, cuando el visitante accede a la landing page desde su dispositivo móvil, entonces encuentra problemas de visualización o navegación.                                                                                                                       | EP06                                                                                                 |
| US-09             	  | Landing page - Formulario de contacto                   | Como visitante de la landing page, quiero encontrar un formulario de contacto para poder comunicarme con el equipo de la aplicación.                                                                                                                          | Escenario 1: "Acceso al formulario de contacto"Dado que el visitante está en la sección de contacto, cuando el visitante llena el formulario con los datos solicitados por la landing page, entonces la página envía los datos al equipo de la aplicación.Escenario 2: "Falta de formulario de contacto"Dado que el visitante está en la sección de contacto, cuando el visitante intenta enviar el formulario sin completar los campos obligatorios, entonces la landing page muestra un mensaje de error solicitando que se complete el formulario.                                            | EP06                                                                                                 |
| US-10             	  | Landing page - Contenido multimedia                     | Como visitante de la landing page, quiero encontrar contenido multimedia para obtener información de manera más dinámica.                                                                                                                                     | Escenario 1: "Contenido multimedia disponible"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page carga todos los recursos multimedia y los muestra al visitante.Escenario 2: "Falta de contenido multimedia"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page no carga los recursos multimedia, resultando en una página monótona y vacía.                                                                  | EP06                                                                                                 |
| US-11             	  | Landing page - Call-to-action                           | Como visitante de la landing page, quiero encontrar call-to-actions para solicitar una demo.                                                                                                                                                                  | Escenario 1: "Call-to-action funcional"Dado que el visitante está en la sección de inicio de la landing page, cuando el visitante navega por la sección y presiona el botón de call-to-action para pedir una demo, entonces la landing page lo redirige a la sección de contacto.Escenario 2: "Falla del call-to-action"Dado que el visitante está en la sección de inicio de la landing page, cuando el visitante navega por la sección y presiona el botón de call-to-action para pedir una demo, entonces la landing page no realiza ninguna acción.                                          | EP06                                                                                                 |
| US-12             	  | Landing page - Testimonios                              | Como visitante de la landing page, quiero encontrar testimonios de usuarios para conocer sus experiencias con la aplicación.                                                                                                                                  | Escenario 1: "Testimonios disponibles"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page muestra testimonios de usuarios satisfechos con la aplicación.Escenario 2: "Falta de testimonios"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page no muestra testimonios de usuarios, lo que dificulta la toma de decisiones del visitante.                                                                       | EP06                                                                                                 |
| US-13             	  | Asignación de Mesas                                     | Como adminnistrador, quiero tener acceso a la cantidad de mesas y sillas para organizar los pedidos y las reservas.                                                                                                                                           | Scenario 01: Gestionar Asignación de MesasDado que soy mesero,Cuando un cliente es asignado a una mesa, Entonces puedo actualizar el estado de la mesa a "ocupada" en el sistema.   Scenario 02: Visualizar Estado de MesasDado que soy mesero,Cuando quiera ver el estado del restaurante,Entonces el sistema debe mostrar un mapa visual del restaurante con el estado actualizado de cada mesa (ocupada, disponible, reservada, etc.).                                                                                                                                                        | EP09                                                                                                 |
| US-14             	  | Ingreso y modificiacion Pedidos                         | Como administrador, quiero agregar los pedidos de los clientes para asegurar un servicio rápido y eficiente.                                                                                                                                                  | Scenario 01: Tomar Pedidos de ClientesDado que soy mesero,Cuando un cliente haga un pedido,Entonces puedo registrar los ítems en el sistema y enviarlos a la cocina.   Scenario 02: Modificar PedidoDado que soy mesero,Cuando un cliente solicite una modificación en su pedido,Entonces puedo realizar los cambios en el sistema antes de enviarlo a la cocina.   <br> Scenarario 02: </b>                                                                                                                                                                                                     | EP07                                                                                                 |
| US-15             	  | Ingreso y confirmación de Reservas                      | Como administrador, quiero agregar las reservas de mesas para asegurar un servicio rápido y eficiente.                                                                                                                                                        | Scenario 01: Tomar Reservas de MesasDado que soy mesero,Cuando un cliente solicite una reserva,Entonces puedo registrar la reserva en el sistema y asignar una mesa disponible.   Scenario 02: Confirmar ReservaDado que soy mesero,Cuando un cliente llegue al restaurante,Entonces puedo confirmar la reserva y asignar una mesa disponible.                                                                                                                                                                                                                                                   | EP09                                                                                                 |
| US-16             	  | Generación de Facturas                                  | Como administrador, quiero generar facturas para los clientes para asegurar un servicio rápido y eficiente.                                                                                                                                                   | Scenario 01: Generar Facturas para ClientesDado que soy cajero,Cuando un cliente finaliza su comida,Entonces puedo generar una factura detallada que incluya todos los ítems consumidos.   Scenario 02: Enviar Factura ElectrónicaDado que el cliente ha solicitado una factura electrónica,Cuando la factura se genere,Entonces el sistema debe permitir la emisión de la factura electrónica y su envío por correo electrónico al cliente.                                                                                                                                                     | EP04                                                                                                 |
| US-17             	  | Reporte de Ventas                                       | Como administrador, quiero ver estadísticas sobre las ventas para tomar decisiones informadas sobre la gestión del restaurante.                                                                                                                               | Scenario 01: Generar Reporte de VentasDado que soy administrador,Cuando acceda a los reportes de ventas,Entonces el sistema debe mostrar gráficos y estadísticas detalladas de las ventas durante un período específico.   Scenario 02: Analizar Datos de VentasDado que soy administrador,Cuando revise los reportes de ventas,Entonces podré analizar los datos y tomar decisiones informadas sobre la gestión del restaurante.                                                                                                                                                                | EP04                                                                                                 |
| US-18             	  | Reporte de Caja                                         | Como administrador, quiero ver estadísticas sobre las transacciones de caja para asegurar una contabilidad clara.                                                                                                                                             | Scenario 01: Generar Reporte de CajaDado que soy cajero,Cuando acceda a los reportes de caja,Entonces el sistema debe mostrar gráficos y estadísticas                                                                                                                                                                                                                                                                                                                                                                                                                                            | EP04                                                                                                 |                                       
| US-19             	  | Acceso a cantidad de Uso de Ingredientes                | Como administrador, quiero ver estadísticas sobre el uso de ingredientes para ajustar los pedidos y optimizar la producción.                                                                                                                                  | Scenario 01: Generar Reporte de Uso de IngredientesDado que soy administrador,Cuando acceda a los reportes de uso de ingredientes,Entonces el sistema debe mostrar gráficos y estadísticas detalladas del uso de cada ingrediente durante un período específico.   Scenario 02: Ajustar Pedidos Basado en el ReporteDado que he revisado el reporte de uso de ingredientes,Cuando note un aumento en el uso de ciertos ingredientes,Entonces podré ajustar los pedidos para evitar la escasez y optimizar la producción.                                                                         | EP03                                                                                                 | 
| US-20             	  | Reporte de Uso de Ingredientes                          | Como administrador, quiero ver estadísticas sobre el uso de ingredientes para ajustar los pedidos y optimizar la producción.                                                                                                                                  | Scenario 01: Generar Reporte de Uso de IngredientesDado que soy administrador,Cuando acceda a los reportes de uso de ingredientes,Entonces el sistema debe mostrar gráficos y estadísticas detalladas del uso de cada ingrediente durante un período específico.   Scenario 02: Ajustar Pedidos Basado en el ReporteDado que he revisado el reporte de uso de ingredientes,Cuando note un aumento en el uso de ciertos ingredientes,Entonces podré ajustar los pedidos para evitar la escasez y optimizar la producción.                                                                         | EP03                                                                                                 |
| US-21                | Registrar nuevo proveedor                               | Como proveedor, quiero registrar mis datos para mantener un registro actualizado con el restaurante.                                                                                                                                                          | **Scenario 01:** Registrar proveedor exitosamente<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de registro de proveedor y lo envíe,<br>**Entonces** el sistema debe guardar la información del proveedor y mostrar una confirmación de registro.<br><br>**Scenario 02:** Error al registrar proveedor<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de registro de proveedor y lo envíe,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema durante el registro.                                                  | EP10                                                                                                 |
| US-22                | Evaluar proveedor                                       | Como proveedor, quiero ser evaluado por el restaurante para asegurar la calidad de mis productos.                                                                                                                                                             | **Scenario 01:** Evaluar proveedor exitosamente<br>**Dado** que soy proveedor,<br>**Cuando** el restaurante complete el formulario de evaluación de proveedor y lo envíe,<br>**Entonces** el sistema debe guardar la evaluación y mostrar una confirmación de envío.<br><br>**Scenario 02:** Error al evaluar proveedor<br>**Dado** que soy proveedor,<br>**Cuando** el restaurante complete el formulario de evaluación de proveedor y lo envíe,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema durante la evaluación.                                    | EP11                                                                                                 |
| US-23                | Actualizar datos del proveedor                          | Como proveedor, quiero actualizar mis datos para mantener la información actualizada con el restaurante.                                                                                                                                                      | **Scenario 01:** Actualizar datos exitosamente<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de actualización de datos y lo envíe,<br>**Entonces** el sistema debe guardar la información actualizada y mostrar una confirmación de actualización.<br><br>**Scenario 02:** Error al actualizar datos<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de actualización de datos y lo envíe,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema durante la actualización.                                              | EP10                                                                                                 |
| US-24                | Ver resultados de evaluación                            | Como proveedor, quiero ver los resultados de mi evaluación para conocer mi desempeño.                                                                                                                                                                         | **Scenario 01:** Ver resultados exitosamente<br>**Dado** que soy proveedor,<br>**Cuando** acceda a la sección de resultados de evaluación,<br>**Entonces** podré ver los resultados de mi evaluación.<br><br>**Scenario 02:** Error al ver resultados<br>**Dado** que soy proveedor,<br>**Cuando** acceda a la sección de resultados de evaluación,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema al cargar los resultados.                                                                                                                               | EP11                                                                                                 | 
| US-25                | Solicitar información sobre productos                   | Como proveedor, quiero solicitar información sobre los productos del restaurante para evaluar posibles colaboraciones.                                                                                                                                        | **Scenario 01:** Solicitar información exitosamente<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de solicitud de información y lo envíe,<br>**Entonces** el sistema debe enviar la solicitud al restaurante y mostrar una confirmación de envío.<br><br>**Scenario 02:** Error al solicitar información<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de solicitud de información y lo envíe,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema durante el envío.                                                | EP08                                                                                                 |
| US-26                | Programar una reunión con el restaurante                | Como proveedor, quiero programar una reunión con el restaurante para discutir posibles acuerdos de colaboración.                                                                                                                                              | **Scenario 01:** Programar reunión exitosamente<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de programación de reunión y lo envíe,<br>**Entonces** el sistema debe enviar la solicitud de reunión al restaurante y mostrar una confirmación de envío.<br><br>**Scenario 02:** Error al programar reunión<br>**Dado** que soy proveedor,<br>**Cuando** complete el formulario de programación de reunión y lo envíe,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema durante el envío.                                               | EP08                                                                                                 |
| US-27                | Ver disponibilidad de mesas                             | Como cliente, quiero ver la disponibilidad de mesas en tiempo real para planificar mi visita al restaurante.                                                                                                                                                  | **Scenario 01:** Ver disponibilidad exitosamente<br>**Dado** que soy cliente,<br>**Cuando** acceda a la sección de disponibilidad de mesas,<br>**Entonces** el sistema debe mostrar la disponibilidad de mesas en tiempo real.<br><br>**Scenario 02:** Error al ver disponibilidad<br>**Dado** que soy cliente,<br>**Cuando** acceda a la sección de disponibilidad de mesas,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema al cargar la disponibilidad.                                                                                                  | EP09                                                                                                 |
| US-28                | Reservar mesa específica                                | Como cliente, quiero reservar una mesa específica para asegurarme de tener el lugar que prefiero en el restaurante.                                                                                                                                           | **Scenario 01:** Reservar mesa exitosamente<br>**Dado** que soy cliente,<br>**Cuando** complete el formulario de reserva de mesa específica y lo envíe,<br>**Entonces** el sistema debe registrar la reserva y mostrar una confirmación de reserva.<br><br>**Scenario 02:** Error al reservar mesa<br>**Dado** que soy cliente,<br>**Cuando** complete el formulario de reserva de mesa específica y lo envíe,<br>**Entonces** el sistema debe mostrar un mensaje de error si ocurre algún problema durante la reserva.                                                                          | EP09                                                                                                 |
| US-29                | Probar la velocidad de carga de la página               | Como visitante de la landing page, quiero que la página cargue rápidamente para tener una mejor experiencia de usuario.                                                                                                                                       | **Scenario 01:** Carga rápida<br>**Dado** que soy visitante,<br>**Cuando** acceda a la landing page,<br>**Entonces** la página debe cargar en menos de 3 segundos.<br><br>**Scenario 02:** Carga lenta<br>**Dado** que soy visitante,<br>**Cuando** acceda a la landing page,<br>**Entonces** la página debe mostrar un mensaje de error si la carga tarda más de 3 segundos.                                                                                                                                                                                                                    | EP06                                                                                                 |
| US-30                | Acceder a la landing page desde diferentes dispositivos | Como visitante de la landing page, quiero que la página sea accesible desde cualquier dispositivo para poder navegarla fácilmente.                                                                                                                            | **Scenario 01:** Acceso desde dispositivos móviles<br>**Dado** que soy visitante,<br>**Cuando** acceda a la landing page desde un dispositivo móvil,<br>**Entonces** la página debe ser completamente funcional y fácil de navegar.<br><br>**Scenario 02:** Acceso desde dispositivos de escritorio<br>**Dado** que soy visitante,<br>**Cuando** acceda a la landing page desde un dispositivo de escritorio,<br>**Entonces** la página debe ser completamente funcional y fácil de navegar.                                                                                                     | EP06                                                                                                 |





<h4 id="impact-mapping">3.3. Impact Mapping.</h4>
<img src="/images/mp.jpeg"></img><br>
<img src="/images/mpi.jpeg"></img><br>
<h4 id="product-backlog">3.4. Product Backlog.</h4>
<img src="/images/PT.jpeg"></img><br>

<h3 id="chapter-4">Capítulo IV: Product Design</h3>
<h4 id="style-guidelines">4.1. Style Guidelines.</h4>
<p>
  En este capítulo se desarrollará las bases para contar con un repositorio central y organizado de uso común que incluye assets, fonts. Esto con el fin de mantener una presentación consistente y enfocada.
</p>
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
<p>En este capítulo se detallará la implementación del producto, la validación y la 
configuración de despliegue del software.</p>

<h4 id="software-configuration">5.1. Software Configuration Management.</h4>

<p>
    En este apartado, se detallan las herramientas y configuraciones empleadas para mantener la consistencia y organización del entorno de desarrollo durante el ciclo de vida del proyecto. La gestión de la configuración del software es crucial para asegurar que todos los miembros del equipo trabajan de manera coordinada, utilizando las mismas versiones de herramientas y respetando las convenciones establecidas. Esta sección abarca desde la configuración del entorno de desarrollo hasta la gestión del código fuente y el despliegue de la solución.
</p>

<h4>5.1.1 Software Development Environment Configuration</h4>

<h4>Project Management</h4>

<p><strong>Discord:</strong><br>
Discord ha sido la herramienta principal de comunicación y coordinación del equipo. Se ha utilizado para realizar reuniones virtuales, mantener discusiones continuas sobre el progreso del proyecto, y para compartir recursos y actualizaciones de forma eficiente.<br>
<strong>Ruta de referencia:</strong> <a href="https://discord.com/">Discord</a>
</p>

<p><strong>Trello:</strong><br>
Trello se ha para la gestión del proyecto, permitiendo la visualización y actualización del estado de tareas y sprints en los que trabaja el equipo. Aunque su uso ha sido ocasional, ha proporcionado una estructura básica para el seguimiento de actividades.<br>
<strong>Ruta de referencia:</strong> <a href="https://trello.com/">Trello</a>
</p>

<h4>Product UX/UI Design</h4>

<p>Para la elaboración de la interfaz de usuario y la experiencia de usuario, se emplearán las siguientes herramientas:</p>

<ul>
    <li><strong>Figma:</strong> Una plataforma colaborativa de diseño que permite la creación de wireframes, mock-ups y prototipos interactivos. Será utilizada para diseñar tanto las interfaces de usuario como los flujos de interacción de la aplicación.</li>
    <li><strong>LucidChart:</strong> Herramienta de diagramación en línea que será utilizada para la elaboración de wireflows y user flows, facilitando la visualización y planificación de las interacciones y navegaciones dentro de la aplicación.</li>
</ul>

<p><strong>Rutas de referencia:</strong></p>
<ul>
    <li><a href="https://www.figma.com/login" target="_blank">Figma</a></li>
    <li><a href="https://www.lucidchart.com/" target="_blank">LucidChart</a></li>
</ul>

<h4>Software Development</h4>

<p>Para el desarrollo del software, se han seleccionado las siguientes herramientas y tecnologías, con el fin de proporcionar un entorno robusto y eficiente para el desarrollo del proyecto:</p>

<ul>
    <li><strong>IntelliJ IDEA Ultimate:</strong> Un entorno de desarrollo integrado (IDE) potente y completo, que ofrece herramientas avanzadas para el desarrollo de aplicaciones. Será utilizado para escribir, depurar y gestionar el código del proyecto, aprovechando sus características de soporte para múltiples lenguajes y sistemas de control de versiones.</li>
    <li><strong>HTML5:</strong> El lenguaje estándar de marcado para la creación de páginas web. Será empleado en el desarrollo del frontend de la aplicación, estructurando el contenido de manera semántica y accesible.</li>
    <li><strong>CSS:</strong> Hojas de estilo en cascada utilizadas para diseñar y estilizar la presentación visual de la aplicación web. Permitirá definir el diseño responsivo y adaptativo del frontend.</li>
</ul>

<p><strong>Rutas de referencia:</strong></p>
<ul>
    <li><a href="https://www.jetbrains.com/idea/" target="_blank">IntelliJ IDEA Ultimate</a></li>
    <li><a href="https://www.w3schools.com/html/html5_syntax.asp" target="_blank">HTML5</a></li>
    <li><a href="https://google.github.io/styleguide/htmlcssguide.html" target="_blank">CSS</a></li>
</ul>

<h4>Software Deployment</h4>

<p>En esta sección, se detallan las herramientas y plataformas utilizadas para el despliegue de las aplicaciones desarrolladas, garantizando que estén accesibles y operativas en el entorno de producción.</p>

<ul>
    <li><strong>Git:</strong> Una herramienta de control de versiones que facilita el registro y la gestión de las distintas versiones del software desarrollado. Su propósito es mantener un historial de cambios y simplificar la corrección de errores. Los integrantes del equipo acceden a través de la línea de comandos en sus sistemas locales.</li>
    <li><strong>GitHub:</strong> Una plataforma en la nube que hospeda los repositorios de código del proyecto. Permitirá la colaboración en tiempo real y la revisión de contribuciones de cada miembro del equipo.</li>
</ul>

<p><strong>Rutas de referencia:</strong></p>
<ul>
    <li><a href="https://git-scm.com/" target="_blank">Git</a></li>
    <li><a href="https://github.com/" target="_blank">GitHub</a></li>
</ul>

<h4>Software Documentation</h4>

<p>En esta sección, se especifican las herramientas utilizadas para la documentación del software, proporcionando un registro detallado de los aspectos técnicos y funcionales del proyecto.</p>

<ul>
    <li><strong>GitHub:</strong> Además de servir como plataforma para el control de versiones y la colaboración en el código, GitHub también se utiliza para alojar la documentación del proyecto. Los miembros del equipo pueden acceder y actualizar la documentación a través de los repositorios del proyecto.</li>
</ul>

<p><strong>Ruta de referencia:</strong></p>
<ul>
    <li><a href="https://github.com/" target="_blank">GitHub</a></li>
</ul>

<h4 id="source-code">5.1.2. Source Code Management.</h4>

<p>El equipo utilizará GitHub como plataforma principal para el control de versiones, implementando el modelo <strong>GitFlow</strong>. A continuación, se describen los medios y el esquema de organización que se aplicarán para el seguimiento de modificaciones:</p>

<h4>Repositorios de GitHub</h4>
<ul>
    <li><strong>Landing Page</strong>: <a href="https://github.com/grupo3-upc202402-wx55/landing-page">Repositorio Landing Page</a></li>
    <li><strong>Project Report</strong>: <a href="https://github.com/grupo3-upc202402-wx55/project_report">Repositorio del project report</a></li>
    
</ul>
<p>Cada repositorio alojará el código fuente correspondiente a su respectivo producto, además de incluir archivos de pruebas unitarias e integración en el caso de los Web Services.</p>

<h4>Implementación de GitFlow</h4>
<p>Se implementará el modelo <strong>GitFlow</strong> para el control de versiones, siguiendo las convenciones establecidas por Vincent Driessen en su artículo "A successful Git branching model". El esquema de ramas incluirá:</p>
<ul>
    <li><strong>Main branch</strong>: La rama principal donde se alojarán las versiones estables del proyecto.</li>
    <li><strong>Develop branch</strong>: Rama de desarrollo donde se integran las nuevas funcionalidades antes de pasar a la rama principal.</li>
    <li><strong>Feature branches</strong>: Cada nueva característica o capítulo desarrollado por el equipo se trabajará en una rama específica. Las convenciones para nombrar estas ramas seguirán un patrón descriptivo, por ejemplo, <code>feat/chapter-5</code>.</li>
    <li><strong>Release branches</strong>: Ramas destinadas a preparar una nueva versión para el lanzamiento, siguiendo el esquema de versionado semántico.</li>
    <li><strong>Hotfix branches</strong>: Ramas para corregir errores críticos en versiones ya lanzadas, aplicando convenciones similares a las usadas en las Release branches.</li>
</ul>
<h4>Conventional Commits</h4>
<p>El equipo aplicará las convenciones de <strong>Conventional Commits</strong> para los mensajes de commit, asegurando que cada cambio en el código sea fácilmente comprensible y rastreable. Los mensajes seguirán la estructura:</p>
<ul>
    <li><code>tipo(scope): mensaje</code></li>
    <li><strong>Tipo:</strong> indica la naturaleza del cambio (e.g., feat, fix, chore).</li>
    <li><strong>Scope:</strong> define la sección del código afectada (e.g., ui, backend).</li>
    <li><strong>Mensaje:</strong> descripción concisa del cambio realizado.</li>
</ul>

<h4 id="source-code-style-guide-and-conventions">5.1.3. Source Code Style Guide & Conventions.</h4>

<h4>HTML</h4>
<ul>
    <li><strong>Estructura del Documento:</strong> Declara el tipo de documento en la primera línea: &lt;!DOCTYPE html&gt;. Usa una estructura de etiqueta HTML válida: &lt;html&gt;, &lt;head&gt;, &lt;body&gt;. Cierra todos los elementos HTML: &lt;p&gt;Texto&lt;/p&gt;.</li>
    <li><strong>Comentarios:</strong> Escribe comentarios en una sola línea cuando sean cortos. Usa comentarios para secciones importantes: &lt;!-- Inicio de la sección de navegación --&gt;.</li>
    <li><strong>Atributos:</strong> Usa comillas dobles para los valores de los atributos: &lt;img src="imagen.jpg" alt="Descripción"&gt;. Especifica siempre los atributos alt y las dimensiones width y height en las imágenes.</li>
    <li><strong>Indentación y Espaciado:</strong> Usa dos espacios para la indentación. No uses espacios alrededor de los signos de igual en los atributos.</li>
</ul>
<p><a href="https://html.spec.whatwg.org/">Referencia</a></p>

<h4>CSS</h4>
<ul>
    <li><strong>Indentación y Espaciado:</strong> Usa dos espacios para la indentación; no uses tabulaciones. El código CSS debe estar en minúsculas.</li>
    <li><strong>Comentarios:</strong> Usa comentarios para explicar secciones complejas del código.</li>
    <li><strong>Nombres de Clases:</strong> Utiliza nombres de clase significativos que reflejen el propósito del elemento. Evita los nombres de clases genéricos como .box o .container.</li>
    <li><strong>Organización:</strong> Agrupa las reglas CSS relacionadas en un solo bloque.</li>
</ul>
<p><a href="https://google.github.io/styleguide/htmlcssguide.html">Referencia</a></p>

<h4>JavaScript</h4>
<ul>
    <li><strong>Indentación y Espaciado:</strong> Usa dos espacios para la indentación. Mantén un espacio después de las comas y antes de los corchetes de apertura.</li>
    <li><strong>Comentarios:</strong> Usa comentarios para explicar la lógica del código, especialmente en bloques complejos.</li>
    <li><strong>Nombres de Variables y Funciones:</strong> Usa nombres descriptivos y en camelCase para variables y funciones. Por ejemplo, getUserInfo en lugar de getuserinfo.</li>
    <li><strong>Estructura del Código:</strong> Usa funciones y módulos para mantener el código organizado y reutilizable. Evita el uso de código no utilizado y realiza limpieza regularmente.</li>
</ul>
<p><a href="https://google.github.io/styleguide/jsguide.html">Referencia</a></p>

<h4>TypeScript</h4>
<ul>
    <li><strong>Indentación y Espaciado:</strong> Usa dos espacios para la indentación. Sigue el formato recomendado por el estándar TypeScript.</li>
    <li><strong>Comentarios:</strong> Usa comentarios para describir el propósito de las funciones y las interfaces.</li>
    <li><strong>Nombres de Variables y Funciones:</strong> Usa camelCase para variables y funciones. Usa PascalCase para nombres de clases e interfaces.</li>
    <li><strong>Tipos:</strong> Especifica tipos explícitos en las variables y las funciones para mayor claridad y seguridad de tipo.</li>
</ul>
<p><a href="https://google.github.io/styleguide/tsguide.html">Referencia</a></p>

<h4>Java</h4>
<ul>
    <li><strong>Indentación y Espaciado:</strong> Usa cuatro espacios para la indentación. Sigue las convenciones de espaciado estándar en el código Java.</li>
    <li><strong>Comentarios:</strong> Usa comentarios Javadoc para documentar clases y métodos.</li>
    <li><strong>Nombres de Variables y Funciones:</strong> Usa camelCase para nombres de variables y métodos. Usa PascalCase para nombres de clases.</li>
    <li><strong>Organización del Código:</strong> Sigue la estructura de paquetes recomendada y organiza el código en clases y métodos claros.</li>
</ul>
<p><a href="https://google.github.io/styleguide/javaguide.html">Referencia</a></p>

<h4>Gherkin (para archivos .feature)</h4>
<ul>
    <li><strong>Estructura de las Características:</strong> Usa Feature, Scenario, Given, When, Then para estructurar los archivos .feature.</li>
    <li><strong>Nombres y Descripciones:</strong> Usa descripciones claras y concisas en inglés. Usa un formato de verbo en presente para los pasos del escenario.</li>
</ul>
<p><a href="https://cucumber.io/docs/gherkin/reference/">Referencia</a></p>

<h4 id="software-deployment-configuration">5.1.4. Software Deployment Configuration.</h4>

<h4>Landing Page Deployment</h4>
<p>Para desplegar la landing page del proyecto, se utilizará GitHub Pages. A continuación se detallan los pasos necesarios para configurar y realizar el despliegue:</p>
   <ol>
      <li><strong>Crear una carpeta para el despliegue:</strong> Creamos una carpeta llamada <code>"docs"</code> en el repositorio. Esta carpeta alojará todos los archivos necesarios para la landing page.</li>
      <li><strong>Organizar los archivos:</strong> Aseguramos que los archivos de la landing page sigan las siguientes nomenclaturas:
          <ul>
              <li><code>"index.html"</code> para la página principal.</li>
              <li><code>"styles.css"</code> para los estilos de la página.</li>
              <li>Una carpeta llamada <code>"img"</code> que contenga todas las imágenes utilizadas.</li>
          </ul>
      </li>
      <li><strong>Subir los archivos al repositorio:</strong> Cargamos los archivos en la carpeta <code>"docs"</code> mediante un commit al repositorio en GitHub.</li>
      <li><strong>Configurar GitHub Pages:</strong> En GitHub, nos dirigimos a la pestaña <code>Settings</code> del repositorio, luego a <code>Pages</code>. Seleccionamos el branch <code>"main"</code> y especificamos la carpeta <code>"docs"</code> como la fuente de la página.</li>
      <li><strong>Esperar la publicación:</strong> Esperamos a que GitHub realice las comprobaciones necesarias. Una vez finalizado el proceso, obtendremos un enlace que llevará a la landing page desplegada.</li>
   </ol>

<h4 id="landing-page-services-applications-implementation">5.2. Landing Page, Services & Applications Implementation.</h4>
<p>
    En esta sección, explicamos y documentamos el proceso de implementación, pruebas, documentación y despliegue de la Landing Page, Web Services y Frontend Web Applications. A medida que avanzamos en el desarrollo, desglosamos el trabajo en secciones específicas para cada Sprint, comenzando con el Sprint 1, donde detallamos la planificación y ejecución de las tareas.
</p>
<h4 id="sprint-x">5.2.1. Sprint 1</h4>
<p>Es fundamental que el equipo dedique especial atención a la identificación del Sprint Goal, siguiendo las guías establecidas por el Scrum Guide. El Sprint Goal debe enfocarse en el negocio o en la perspectiva de los usuarios, buscando la entrega de un nuevo feature o un set de features.</p>
<p>Para nuestro Sprint, utilizamos la estructura sugerida por Scrum.org para redactar el Sprint Goal:</p>

<h4 id="sprint-planning-x">5.2.1.1. Sprint Planning 1.</h4>
<p>En el Sprint #1, que comienza el 29/08/2024, nos enfocaremos en desarrollar una landing page  para Re-Grill. El objetivo es crear una página que no solo capte la atención de los visitantes, sino que también transmita claramente los beneficios de nuestro producto. Este sprint estará dedicado al diseño y desarrollo de la landing page para cumplir con nuestros objetivos estratégicos.</p>

<table>
    <tr>
        <td>Sprint #</td>
        <td>Sprint 1</td>
    </tr>
    <tr>
        <td>Sprint Planning Background  </td>
    </tr>
    <tr>
        <td>Date</td>
        <td>2024-08-29</td>
    </tr>
    <tr>
        <td>Time</td>
        <td>16:00 PM</td>
    </tr>
    <tr>
        <td>Location</td>
        <td>Virtual via discord</td>
    </tr>
    <tr>
        <td>Prepared By </td>
        <td>Gabriel Anthony Braithuaite Toledo, Hardie Alfonso Holguín Gamarra</td>
    </tr>
    <tr>
        <td>Attendees (to planning <br>meeting) </td>
        <td>Gabriel Anthony Braithuaite Toledo, Adrian Alonso Calle Huayanca, Hardie Alfonso Holguín Gamarra, Mateo Italo Loechle Arias, David Bryan Rodriguez Santos</td>
    </tr>
    <tr>
        <td>Sprint Goal &amp; User Stories </td>
    </tr>
    <tr>
        <td>Sprint 1 Goal </td>
        <td>Desarrollar una landing page atractiva para Re-Grill, diseñada para captar la atención de los visitantes y comunicar de manera efectiva los beneficios del producto. El cumplimiento se medirá en función de la finalización del diseño, la implementación y la puesta en producción de la landing page.</td>
    </tr>
    <tr>
        <td>Sprint 1 Velocity </td>
        <td>El equipo ha establecido una capacidad de 30 Story Points para el Sprint 1, enfocándose en completar todas las tareas necesarias para el desarrollo de la landing page de Re-Grill.  </td>
    </tr>
    <tr>
        <td>Sum of Story Points </td>
        <td>30</td>
    </tr>
</table>
<h4 id="spring-backlog-x">5.2.1.2. Sprint Backlog 1.</h4>

<p>El Sprint Backlog para el Sprint #1 tiene como objetivo principal el desarrollo de una landing page para Re-Grill. Este sprint se centrará en la creación y despliegue de una página web atractiva que comunique de manera efectiva los beneficios del producto. La lista de tareas y user stories asociadas a este sprint se ha diseñado para garantizar que se cumpla este objetivo de manera eficiente.</p>
<p><a href="https://trello.com/b/LSbTHu4A/open-source">Link a Trello</a></p>

<table>
    <tr>
        <td>Sprint # </td>
        <td>Sprint 1 </td>
    </tr>
    <tr>
        <td>User Story  </td>
        <td></td>        
        <td>Work-Item / Task </td>
        <td></td>
    </tr>
    <tr>
        <td>Id</td>
        <td>Title</td>
        <td>Id</td>
        <td>Title</td>
        <td>Description</td>
        <td>Estimation (Hours) </td>
        <td>Assigned To</td>
        <td>Status (To-do/In Process / To Review / Done)</td>
    </tr>
<!--US01 -->  
    <tr>
        <td>US01</td>
        <td>Crear Wireframe de la Landing Page</td>
        <td>WI01</td>
        <td>Definir estructura de la página</td>
        <td>Definir la estructura y los elementos principales de la landing page, incluyendo la ubicación de los elementos y la jerarquía visual.</td>
        <td>4</td>
        <td>Adrian Alonso Calle Huayanca</td>
        <td>Done</td>
    </tr>
<!--US02 --> 
    <tr>
        <td>US02</td>
        <td>Desarrollar la Landing Page</td>
        <td>WI02</td>
        <td>Implementar el diseño de la página</td>
        <td>Desarrollar la landing page siguiendo el wireframe definido, incluyendo la estructura HTML y los estilos CSS necesarios.</td>
        <td>12</td>
        <td>Hardie Alfonso Holguín Gamarra / Mateo Italo Loechle Arias </td>
        <td>Done</td>
    </tr>
<!--US03 --> 
    <tr>
        <td>US03</td>
        <td>Revisar y Ajustar la Landing Page</td>
        <td>WI03</td>
        <td>Realizar pruebas y ajustes</td>
        <td>Revisar la landing page para identificar posibles mejoras y ajustes. Realizar pruebas de usabilidad y correcciones necesarias.</td>
        <td>6</td>
        <td>David Bryan Rodriguez Santos</td>
        <td>Done</td>
    </tr> 
<!--US04 -->
    <tr>
        <td>US04</td>
        <td>Desplegar la Landing Page</td>
        <td>WI04</td>
        <td>Configurar el despliegue</td>
        <td>Configurar el despliegue de la landing page en un entorno de producción. Asegurar que la página esté accesible y funcional.</td>
        <td>8</td>
        <td>Gabriel Anthony Braithuaite Toledo</td>
        <td>Done</td>
    </tr>
</table>
<h4 id="development-evidence-for-sprint-review-x">5.2.1.3. Development Evidence for Sprint Review.</h4>
<p>Durante el Sprint #1, se lograron avances significativos en la implementación de los componentes clave del proyecto Re-Grill, centrados principalmente en el desarrollo de la Landing Page. Estos avances se alinean con el objetivo principal del sprint, que es diseñar y desplegar una página web atractiva y funcional para captar la atención de los usuarios y comunicar los beneficios del producto de manera efectiva.</p>
<table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id </td>
        <td>Commit Message </td>
        <td>Commit Message Body</td>
        <td>Commited on (Date) </td>
    </tr>
    <tr>
        <td>Gaboo04/landing-page </td>
        <td>feature/landing-page</td>
        <td>557bf8a</td>
        <td>feat: add links to the head, header, main section, about us section and features section.</td>
        <td>Add images for landing page, add html file for english page.</td>
        <td>05/09/2024</td>
    </tr>
    <tr>
        <td>HOLGUINUPC/landing-page </td>
        <td>main</td>
        <td>e2a6afe</td>
        <td>feat: css 50% completed</td>
        <td>add benefits style, hero style, added logo img nav nav ul styles, added .container adn section style</td>
        <td>05/09/2024</td>
    </tr>
    <tr>
        <td>LowMathzzz/landing-page </td>
        <td>main</td>
        <td>6d41e03</td>
        <td>feat(styles): added features and footer on styles layer.</td>
        <td>added mobile responsive config on styles layer,  added tables responsive config on styles layer.</td>
        <td>05/09/2024</td>
    </tr>
    <tr>
        <td>DavidBryanRodriguezSantos/landing-page </td>
        <td>main</td>
        <td>f778cda</td>
        <td>feat(es-page): create spanish page</td>
        <td>create spanish page</td>
        <td>05/09/2024</td>
    </tr>    
    <tr>
        <td>U202011657/landing-page </td>
        <td>main</td>
        <td>bdf0608</td>
        <td>feat:Update index.html</td>
        <td>report-1</td>
        <td>05/09/2024</td>
    </tr>
    <tr><td>https://github.com/grupo3-upc202402-wx55/landing-page</td></tr>
    

</table>
<h4 id="testing-suite-evidence-for-sprint-review">5.2.1.4. Testing Suite Evidence for Sprint Review.</h4>
<p>En esta sección, presentamos las evidencias relacionadas con las pruebas de aceptación automatizadas realizadas para la landing page de Re-Grill, desarrollada en el Sprint 1. A lo largo de este sprint, se lograron los objetivos planteados: planificación, desarrollo y despliegue de la landing page. Las pruebas de aceptación se diseñaron para garantizar que la landing page cumpla con los requisitos y expectativas definidos en los User Stories correspondientes. </p>

<table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id </td>
        <td>Commit Message </td>
        <td>Commit Message Body</td>
        <td>Commited on (Date) </td>
    </tr>
    <tr>
        <td>Gaboo04/landing-page</td>
        <td>feat/testing</td>
        <td>ee1b2de</td>
        <td>feat:add acceptance tests for landing page.</td>
        <td>acceptance tests based on user stories designed for landing page development</td>
        <td>31/08/2021</td>
    </tr>
</table>
<h4 id="execution-evidence-for-sprint-review">5.2.1.5. Execution Evidence for Sprint Review.</h4>
<p>En este Sprint, se logró desarrollar y desplegar exitosamente la landing page para Re-Grill. Se completaron todas las tareas planificadas, incluyendo la creación del wireframe, el desarrollo de la página, su revisión y ajuste, así como el despliegue en el entorno de producción. La landing page refleja fielmente el diseño y la funcionalidad esperados, proporcionando una interfaz atractiva y funcional para los usuarios.  </p>
<h5>Screenshots de las Principales Vistas Implementadas</h5>
<p>Se adjuntan capturas de pantalla de las principales vistas de la landing page desarrollada en el Sprint 1, mostrando el diseño y la estructura de la página.</p>
<h5>Se implementó el Header</h5>
<p>En esta sección se pueden observar las principales opciones de la página, un call to action y una descripción sobre nuestra compañía y nuestros valores. </p>
<img src="/images/landing-page-header-img.png" alt="Landing page header img">
<img src="/images/landing-page-body-img.png" alt="Descripción del producto">
<h5>Se implementó la sección de features y plans.</h5>
<p>En estas secciones se describen las principales características que tiene Re-grill, así como los diferentes planes de suscripción ques se ofrece.</p>
<img src="/images/landing-page-feature-plans-img.png" alt="Features and plans del producto">
<h5>Se implementó la sección de Benefits y Questions & Answers </h5>
<p>En esta sección se describen los beneficios de Re-Grill y se resuelven las preguntas más frecuentes que los usuarios puedan tener.</p>
<img src="/images/landing-page-benefits-q&a-img.png" alt="Benefits and Questions & Answers">
<h5>Se implementó el footer con la opción de contacto</h5>
<p>En esta sección se muestra la información de contacto de la empresa, así como un formulario para que los usuarios puedan enviar sus consultas.</p>
<img src="/images/landing-page-contact-footer-img.png" alt="Footer de la landing page">

<h4 id="services-documentation-evidence-for-sprint-review">5.2.1.6. Services Documentation Evidence for Sprint Review.</h4>
<p>En este Sprint, el enfoque principal fue el desarrollo y despliegue de la landing page de Re-Grill. No se implementaron Web Services en esta etapa, por lo que no se incluye documentación relacionada con endpoints o servicios web. La implementación y documentación de Web Services será abordada en Sprints futuros, conforme se expanda la funcionalidad del producto.</p>

<h4 id="software-deployment-evidence-for-sprint-review">5.2.1.7. Software Deployment Evidence for Sprint Review.</h4>
<p>
    Durante el Sprint 1, nos enfocamos en el despliegue de la landing page de Re-Grill. El objetivo fue asegurar que la página esté accesible para los usuarios finales a través de un entorno de producción confiable. A continuación, se detalla el proceso de despliegue, incluyendo la creación de cuentas necesarias, la configuración de recursos en GitHub Pages, y la automatización de ciertas tareas para facilitar futuros despliegues.
</p>
<h5>Creación y Configuración de Repositorio en GitHub</h5>
        <ul>
            <li>Se creó un repositorio en GitHub dentro de la organización, donde se alojó el código fuente de la landing page.</li>
            <li>Se configuró la rama <code>main</code> como la principal para el despliegue, y la rama <code>feat/testing</code> para pruebas de aceptación.</li>
            <li>Se habilitó GitHub Pages en la rama <code>main</code> para facilitar el despliegue automático de la landing page.</li>
        </ul>
<h5>Evidencias Gráficas del Despliegue</h5>
<p>A continuación, se muestran capturas de pantalla que ilustran el proceso despliegue:</p>
<img src="/images/landing-page-header-img.png" alt="Header de la landing page">
<img src="/images/landing-page-body-img.png" alt="Body de la landing page">
<img src="/images/landing-page-feature-plans-img.png" alt="Features and plans de la landing page">
<img src="/images/landing-page-benefits-q&a-img.png" alt="Benefits and Questions & Answers de la landing page">
<img src="/images/landing-page-contact-footer-img.png" alt="Contact Footer de la landing page">

<h4 id="team-collaboration-insights-during-sprint">5.2.1.8. Team Collaboration Insights during Sprint.</h4>
<p>
    Durante el Sprint 1, nos aseguramos de que todas las actividades de implementación fueran realizadas con la colaboración de todos los miembros del equipo. Cada integrante contribuyó a la creación y desarrollo de la landing page de Re-Grill, utilizando diversas herramientas de colaboración. A continuación, se presentan los detalles sobre las actividades del equipo y las evidencias gráficas que reflejan la colaboración y los commits en GitHub.
</p>
<table>
    <tr>
        <td>Team Member</td>
        <td>Activity </td>
    </tr>
    <tr>
        <td>Gabriel Anthony Braithuaite Toledo</td>
        <td>Implementación de las secciones header, implementación de parte del main section en el index.html.</td>
    </tr>
    <tr>
        <td>Adrian Alonso Calle Huayanca</td>
        <td>Desarrollo del wireframe, mock up y completar sección del main en el index.html.</td>
    </tr>
    <tr>
        <td>Hardie Alfonso Holguín Gamarra	</td>
        <td>Implementación de los estilos para parte del body y containers en el styles.css</td>
    </tr>
    <tr>
        <td>Mateo Italo Loechle Arias</td>
        <td>Implementación de los estilos para completar el body y configuración del responsive en el styles.css</td>
    </tr>
    <tr>
        <td>David Bryan Rodriguez Santos</td>
        <td>Implementación del switching de idioma realizando una versión en español del landing page en el index-es.html.</td>
    </tr>
</table>

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





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
<img src="/images/Laura.jpeg"></img><br>
<img src="/images/Mig.jpeg"></img><br>
<h4 id="product-backlog">3.4. Product Backlog.</h4>
<img src="/images/PT.jpeg"></img><br>

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


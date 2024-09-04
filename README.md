
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
<h4 id="user-stories">3.2. User Stories.</h4>

| Epic / Story ID 	    | Título 	                                            | Descripción 	                                                                                                                                                                                                                                                 | Criterios de Aceptación 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Relacionado con Epic ID 	 |
|----------------------|-----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| EP01               	 | Gestión de Inventario y Stock	                      | *Como* administrador *Quiero* gestionar eficientemente el inventario y stock del restaurante *Para* asegurar que los ingredientes estén siempre disponibles y reducir el desperdicio.                                                                         | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde            |
| EP04               	 | Optimización del Costo de Producción y Facturación	 | *Como* administrador *Quiero* calcular y optimizar el costo de producción y gestionar la facturación *Para* asegurar la rentabilidad del restaurante.                                                                                                         | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde            |
| EP05               	 | Control y Reporte de Uso de Ingredientes  	         | *Como* administrador *Quiero* llevar un control detallado de la merma y generar reportes sobre el uso de ingredientes *Para* optimizar la gestión del inventario.                                                                                             | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde            |
| EP06               	 | Operaciones Eficientes en la Caja 	                 | *Como* administrador *Quiero* realizar operaciones de cierre de caja detallado y gestionar las transacciones de manera precisa *Para* asegurar una contabilidad clara.                                                                                        | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde            |
| EP07               	 | Gestión de Pedidos y Asignación de Mesas            | *Como* administrador *Quiero* gestionar pedidos y la asignación de mesas de manera eficiente *Para* mejorar el servicio al cliente.                                                                                                                           | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde            |
| EP08               	 | Landing Page Optimizada	                            | *Como* usuario interesado, *Quiero* una página de destino fácil de usar y optimizada que ofrezca información clara y accesible sobre la aplicación *Para* facilitar la toma de decisiones informadas y mejorar la interacción con el equipo de la aplicación. | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde            |
| EP09               	 | Gestión de Reservas	                                | *Como* administrador *Quiero* gestionar las reservas de mesas de manera eficiente *Para* asegurar un servicio rápido y eficiente.                                                                                                                             | No Corresponde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No Corresponde            |
| EP10              	  | 
| US-03             	  | Acceso a Cantidades de Stock                        | Como administrador, quiero acceder a las cantidades actuales de stock para planificar la producción y las compras.                                                                                                                                            | <b>Scenario 01:</b> Ver Cantidades Disponibles Dado</b> que soy administrador<br>Cuando</b> acceda al sistema de gestión de inventario<br>Entonces</b>  podré ver las cantidades actuales de cada ingrediente en stock, y el sistema mostrará alertas cuando el stock esté por debajo de un nivel predefinido.<br><br> Scenario 02:</b> Recibir Notificación de Bajo Stock<br>Dado</b>  que el stock de un ingrediente está bajo,<br>Cuando</b>  acceda al sistema de gestión de inventario,<br>Entonces</b> recibiré una notificación de bajo stock para que pueda tomar medidas inmediatas.    | EP01                      |
| US-04             	  | Ingreso de Stock                                    | Como administrador, quiero registrar nuevas entradas de inventario para mantener un registro actualizado de los ingredientes disponibles.                                                                                                                     | <b>Scenario 01:</b> Registrar Nuevas Entradas<br>Dado que soy administradorCuando</b> reciba un nuevo lote de ingredientes,<br>Entonces</b>puedo registrar esta entrada en el sistema con la cantidad y la fecha de ingreso, y el sistema actualizará automáticamente el stock disponible.<br><br>Scenario 02:</b> Verificar Registro de Entrada<br>Dado</b> que he registrado una nueva entrada de stock,<br>Cuando</b> revise el registro<br>Entonces</b>  podré ver la nueva entrada registrada con todos los detalles correspondientes.<br><br>                                              | No Corresponde            |
| US-05             	  | Tomar Pedidos desde la Mesa                         | Como administrador, quiero introducir pedidos directamente en la aplicación desde la mesa para que estos se envíen automáticamente a la cocina.                                                                                                               | <b>Scenario 01:</b>Tomar Pedidos desde la Mesa<br><b>Dado</b> que estoy tomando un pedido,<br><b>Cuando</b> introduzca los ítems en la aplicación,<br><b>Entonces</b> estos deben enviarse automáticamente al sistema de cocina.<br><br><b>Scenario 02:</b> Modificar Pedido Antes de Enviar<br> <b>Dado</b>  que he tomado un pedido,<br><b>Cuando</b>  el cliente haga una modificación,<br><b>Entonces</b>  el sistema debe permitir la modificación del pedido antes de enviarlo a la cocina.<br><br>                                                                                        | EP07                      |
| US-06             	  | Cálculo del Costo de Producción                     | Como administrador, quiero consultar el costo de los ingredientes por plato para ajustar precios o recetas según sea necesario.                                                                                                                               | <b>Scenario 01:</b> Consultar Costos de Producción<br>Dado</b> que soy administrador,<br>Cuando</b> acceda a un plato específico<br>Entonces</b>el sistema debe mostrar el costo detallado de cada ingrediente y el costo total de producción del plato.<br><br>Scenario 02:</b> Modificar Receta y Recalcular Costos<br>Dado</b>  que quiero ajustar una receta,<br>Cuando</b> modifique los ingredientes en el sistema,<br>Entonces</b>  el sistema debe recalcular automáticamente el costo de producción del plato y actualizarlo en la base de datos.<br><br>                               | No Corresponde            |
| US-09             	  | Reporte de Uso de Ingredientes                      | Como administrador, quiero ver estadísticas sobre el uso de ingredientes para ajustar los pedidos y optimizar la producción.                                                                                                                                  | Scenario 01:</b> Generar Reporte de Uso de Ingredientes<br>Dado</b> que soy administrador,<br>Cuando</b>  acceda a los reportes de uso de ingredientes,<br>Entonces</b> el sistema debe mostrar gráficos y estadísticas detalladas del uso de cada ingrediente durante un período específico.<br><br>Scenario 02:</b>  Ajustar Pedidos Basado en el Reporte<br>Dado</b>  que he revisado el reporte de uso de ingredientes,<br>Cuando</b> note un aumento en el uso de ciertos ingredientes,<br>Entonces</b> podré ajustar los pedidos para evitar la escasez y optimizar la producción.<br><br> | No Corresponde            |
| US-10             	  | Landing page - Estructuración                       | Como visitante de la landing page, quiero encontrar una navegación intuitiva que me permita acceder fácilmente a la información sobre sus características.                                                                                                    | Escenario 1: "Landing page estructurada" Dado que el visitante está en la landing page, cuando el visitante accede a la página principal, entonces la landing page ofrece los medios necesarios para una navegación fácil y clara. Escenario 2: "Organización no intuitiva"Dado que el visitante está en la landing page, cuando el visitante accede a la página principal, entonces la landing page no proporciona formas de navegación amigables para el usuario.                                                                                                                              | EP08                      |
| US-11             	  | Landing page – Contenido informativo                | Como visitante de la landing page, quiero encontrar contenido detallado y fácil de entender sobre las funcionalidades y beneficios de la aplicación para poder tomar una decisión informada sobre su uso.                                                     | Escenario 1: "Contenido landing page"Dado que el visitante está en la landing page, cuando el visitante navega por la landing page, entonces la página presenta información clara, fácil de entender y accesible para cualquier visitante.Escenario 2: "Contenido confuso o insuficiente" Dado que el visitante está en la landing page, cuando el visitante navega por la landing page, entonces la página no ofrece información clara, lo que la hace inaccesible para diferentes visitantes.                                                                                                  | EP08                      |
| US-12             	  | Landing page - Compatibilidad móvil                 | Como visitante de la landing page, quiero que sea responsiva para poder utilizarla en cualquier dispositivo.                                                                                                                                                  | Escenario 1: "Compatibilidad con dispositivos móviles"Dado que el visitante está en la landing page, cuando el visitante accede a la landing page desde su dispositivo móvil, entonces puede navegar por la página sin problemas.Escenario 2: "Problemas de visualización o navegación"Dado que el visitante está en la landing page, cuando el visitante accede a la landing page desde su dispositivo móvil, entonces encuentra problemas de visualización o navegación.                                                                                                                       | EP08                      |
| US-13             	  | Landing page - Formulario de contacto               | Como visitante de la landing page, quiero encontrar un formulario de contacto para poder comunicarme con el equipo de la aplicación.                                                                                                                          | Escenario 1: "Acceso al formulario de contacto"Dado que el visitante está en la sección de contacto, cuando el visitante llena el formulario con los datos solicitados por la landing page, entonces la página envía los datos al equipo de la aplicación.Escenario 2: "Falta de formulario de contacto"Dado que el visitante está en la sección de contacto, cuando el visitante intenta enviar el formulario sin completar los campos obligatorios, entonces la landing page muestra un mensaje de error solicitando que se complete el formulario.                                            | EP08                      |
| US-14             	  | Landing page - Contenido multimedia                 | Como visitante de la landing page, quiero encontrar contenido multimedia para obtener información de manera más dinámica.                                                                                                                                     | Escenario 1: "Contenido multimedia disponible"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page carga todos los recursos multimedia y los muestra al visitante.Escenario 2: "Falta de contenido multimedia"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page no carga los recursos multimedia, resultando en una página monótona y vacía.                                                                  | EP08                      |
| US-15             	  | Landing page - Call-to-action                       | Como visitante de la landing page, quiero encontrar call-to-actions para solicitar una demo.                                                                                                                                                                  | Escenario 1: "Call-to-action funcional"Dado que el visitante está en la sección de inicio de la landing page, cuando el visitante navega por la sección y presiona el botón de call-to-action para pedir una demo, entonces la landing page lo redirige a la sección de contacto.Escenario 2: "Falla del call-to-action"Dado que el visitante está en la sección de inicio de la landing page, cuando el visitante navega por la sección y presiona el botón de call-to-action para pedir una demo, entonces la landing page no realiza ninguna acción.                                          | EP08                      |
| US-16             	  | Landing page - Testimonios                          | Como visitante de la landing page, quiero encontrar testimonios de usuarios para conocer sus experiencias con la aplicación.                                                                                                                                  | Escenario 1: "Testimonios disponibles"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page muestra testimonios de usuarios satisfechos con la aplicación.Escenario 2: "Falta de testimonios"Dado que el visitante está en la landing page, cuando el visitante navega por la página y sus diferentes secciones, entonces la landing page no muestra testimonios de usuarios, lo que dificulta la toma de decisiones del visitante.                                                                       | EP08                      |
| US-17             	  | Asignación de Mesas                                 | Como adminnistrador, quiero tener acceso a la cantidad de mesas y sillas para organizar los pedidos y las reservas.                                                                                                                                           | Scenario 01: Gestionar Asignación de MesasDado que soy mesero,Cuando un cliente es asignado a una mesa, Entonces puedo actualizar el estado de la mesa a "ocupada" en el sistema.   Scenario 02: Visualizar Estado de MesasDado que soy mesero,Cuando quiera ver el estado del restaurante,Entonces el sistema debe mostrar un mapa visual del restaurante con el estado actualizado de cada mesa (ocupada, disponible, reservada, etc.).                                                                                                                                                        | EP07                      |
| US-18             	  | Ingreso y modificiacion Pedidos                     | Como administrador, quiero agregar los pedidos de los clientes para asegurar un servicio rápido y eficiente.                                                                                                                                                  | Scenario 01: Tomar Pedidos de ClientesDado que soy mesero,Cuando un cliente haga un pedido,Entonces puedo registrar los ítems en el sistema y enviarlos a la cocina.   Scenario 02: Modificar PedidoDado que soy mesero,Cuando un cliente solicite una modificación en su pedido,Entonces puedo realizar los cambios en el sistema antes de enviarlo a la cocina.   <br> Scenarario 02: </b>                                                                                                                                                                                                     | EP07                      |
| US-19             	  | Ingreso y confirmación de Reservas                  | Como administrador, quiero agregar las reservas de mesas para asegurar un servicio rápido y eficiente.                                                                                                                                                        | Scenario 01: Tomar Reservas de MesasDado que soy mesero,Cuando un cliente solicite una reserva,Entonces puedo registrar la reserva en el sistema y asignar una mesa disponible.   Scenario 02: Confirmar ReservaDado que soy mesero,Cuando un cliente llegue al restaurante,Entonces puedo confirmar la reserva y asignar una mesa disponible.                                                                                                                                                                                                 | EP09                      |
| US-20             	  | Generación de Facturas                              | Como administrador, quiero generar facturas para los clientes para asegurar un servicio rápido y eficiente.                                                                                                                                                   | Scenario 01: Generar Facturas para ClientesDado que soy cajero,Cuando un cliente finaliza su comida,Entonces puedo generar una factura detallada que incluya todos los ítems consumidos.   Scenario 02: Enviar Factura ElectrónicaDado que el cliente ha solicitado una factura electrónica,Cuando la factura se genere,Entonces el sistema debe permitir la emisión de la factura electrónica y su envío por correo electrónico al cliente.                                                                                                                                                                                                 | EP04                      |
| US-21             	  | Reporte de Ventas                                   | Como administrador, quiero ver estadísticas sobre las ventas para tomar decisiones informadas sobre la gestión del restaurante.                                                                                                                               | Scenario 01: Generar Reporte de VentasDado que soy administrador,Cuando acceda a los reportes de ventas,Entonces el sistema debe mostrar gráficos y estadísticas detalladas de las ventas durante un período específico.   Scenario 02: Analizar Datos de VentasDado que soy administrador,Cuando revise los reportes de ventas,Entonces podré analizar los datos y tomar decisiones informadas sobre la gestión del restaurante.                                                                                                                                                                                                 | EP04                      |
| US-22             	  | Reporte de Caja                                     | Como administrador, quiero ver estadísticas sobre las transacciones de caja para asegurar una contabilidad clara.                                                                                                                                             | Scenario 01: Generar Reporte de CajaDado que soy cajero,Cuando acceda a los reportes de caja,Entonces el sistema debe mostrar gráficos y estadísticas
| US-23             	  | Acceso a cantidad de Uso de Ingredientes            | Como administrador, quiero ver estadísticas sobre el uso de ingredientes para ajustar los pedidos y optimizar la producción.                                                                                                                                  | Scenario 01: Generar Reporte de Uso de IngredientesDado que soy administrador,Cuando acceda a los reportes de uso de ingredientes,Entonces el sistema debe mostrar gráficos y estadísticas detalladas del uso de cada ingrediente durante un período específico.   Scenario 02: Ajustar Pedidos Basado en el ReporteDado que he revisado el reporte de uso de ingredientes,Cuando note un aumento en el uso de ciertos ingredientes,Entonces podré ajustar los pedidos para evitar la escasez y optimizar la producción.                                                                                                                                                                                                 | EP05                      | 
| US-24             	  |

<tr>
    <td>US-07</td> 
    <td></td>

<table>
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
<tr>
    <td>US-01</td> 
    <td>Ver descripción clara y concisa de los servicios en la landing page</td>
    <td>Como visitante, quiero ver una descripción clara y concisa de los servicios ofrecidos en la landing page, para comprender rápidamente cómo pueden beneficiar a mi operación agrícola o ganadera.</td>
    <td>
        <b>Scenario 01:</b> Contactar a los desarrolladores<br>
        <b>Dado</b> que el visitante tiene una consulta <br>
        <b>Cuando</b> redacte un mensaje y su correo electronico para contactar a los desarrolladores<br>
        <b>Entonces</b> el mensaje le llegara a los desarrolladores.<br><br>
    </td>
    <td>EP01</td> 
</tr>
<tr>
    <td>US-02</td> 
    <td>Vinculo entre el Landing Page y la Aplicación Web</td>
    <td>Como visitante interesado en la aplicación, quiero probar la aplicación web desde la Landing Page.</td>
    <td>
        <b>Scenario 01:</b> El visitante ingresa a la aplicación<br>
        <b>Dado</b> que el visitante desea usar la aplicación<br>
        <b>Cuando</b> ingrese a la landing page y encuentre el botón para acceder a la aplicación. <br>
        <b>Entonces</b> el visitante será redirigido a la aplicación web y podrá convertirse en nuestro usuario.<br><br>
   </td>
    <td>EP02</td> 
</tr>



<tr>
    <td>US-03</td> 
    <td>Acceso a Cantidades de Stock</td>
    <td>Como administrador, quiero acceder a las cantidades actuales de stock para planificar la producción y las compras.</td>
    <td>
        <b>Scenario 01:</b> Ver Cantidades Disponibles<br>
        <b>Dado</b> que soy administrador<br>
        <b>Cuando</b> acceda al sistema de gestión de inventario<br>
        <b>Entonces</b>  podré ver las cantidades actuales de cada ingrediente en stock, y el sistema mostrará alertas cuando el stock esté por debajo de un nivel predefinido.<br><br>
        <b>Scenario 02:</b> Recibir Notificación de Bajo Stock<br>
        <b>Dado</b>  que el stock de un ingrediente está bajo,<br>
        <b>Cuando</b>  acceda al sistema de gestión de inventario,<br>
        <b>Entonces</b> recibiré una notificación de bajo stock para que pueda tomar medidas inmediatas.
    </td> 
    <td>EP03</td> 
</tr>
<tr>
    <td>US-04</td> 
    <td>Ingreso de Stock</td>
    <td>Como administrador, quiero registrar nuevas entradas de inventario para mantener un registro actualizado de los ingredientes disponibles.</td>
    <td>
        <b>Scenario 01:</b> Registrar Nuevas Entradas<br>
        <b>Dado</b>  que soy administrador<br>
        <b>Cuando</b> reciba un nuevo lote de ingredientes,<br>
        <b>Entonces</b>puedo registrar esta entrada en el sistema con la cantidad y la fecha de ingreso, y el sistema actualizará automáticamente el stock disponible.<br><br>
        <b>Scenario 02:</b> Verificar Registro de Entrada<br>
        <b>Dado</b> que he registrado una nueva entrada de stock,<br>
        <b>Cuando</b> revise el registro<br>
        <b>Entonces</b>  podré ver la nueva entrada registrada con todos los detalles correspondientes.<br><br>
    </td> 
    <td>EP12</td> 
</tr>
<tr>
    <td>US-05</td> 
    <td> Cálculo del Costo de Producción</td>
    <td>Como administrador, quiero consultar el costo de los ingredientes por plato para ajustar precios o recetas según sea necesario.</td>
    <td>
        <b>Scenario 01:</b> Consultar Costos de Producción<br>
        <b>Dado</b> que soy administrador,<br>
        <b>Cuando</b> acceda a un plato específico<br>
        <b>Entonces</b>el sistema debe mostrar el costo detallado de cada ingrediente y el costo total de producción del plato.<br><br>
        <b>Scenario 02:</b> Modificar Receta y Recalcular Costos<br>
        <b>Dado</b>  que quiero ajustar una receta,<br>
        <b>Cuando</b> modifique los ingredientes en el sistema,<br>
        <b>Entonces</b>  el sistema debe recalcular automáticamente el costo de producción del plato y actualizarlo en la base de datos.<br><br>
    </td> 
    <td>EP12</td> 
</tr>
<tr>
    <td>US-06</td> 
    <td>Gestión de Facturación</td>
    <td> Como cajero, quiero generar y gestionar facturas para los clientes de manera rápida y eficiente.</td>
    <td>
        <b>Scenario 01:</b> Generar Facturas para Clientes<br>
        <b>Dado</b> que soy cajero,<br>
        <b>Cuando</b> un cliente finaliza su comida,<br>
        <b>Entonces</b> puedo generar una factura detallada que incluya todos los ítems consumidos.<br><br>
        <b>Scenario 02:</b> Enviar Factura Electrónica<br>
        <b>Dado</b> que el cliente ha solicitado una factura electrónica,<br>
        <b>Cuando</b>  la factura se genere,s<br>
        <b>Entonces</b>  el sistema debe permitir la emisión de la factura electrónica y su envío por correo electrónico al cliente.<br><br>
    </td> 
    <td>EP09</td> 
</tr>
<tr>
    <td>US-07</td> 
    <td>Registro de Merma</td>
    <td>Como administrador, quiero registrar y monitorear las mermas de ingredientes para ajustar las compras futuras y reducir pérdidas.</td>
    <td>
        <b>Scenario 01:</b>Registrar y Monitorear Merma<br>
        <b>Dado</b>  que se produce una merma en los ingredientes,<br>
        <b>Cuando</b> registre la merma en el sistema,<br>
        <b>Entonces</b> el sistema debe permitir el registro de la cantidad perdida y generar un reporte semanal que muestre las mermas acumuladas.<br><br>
        <b>Scenario 02:</b> Analizar Datos de Merma<br>
        <b>Dado</b> que he registrado las mermas en el sistema,<br>
        <b>Cuando</b>  acceda al reporte semanal,<br>
        <b>Entonces</b> podré analizar los datos de merma y ajustar las órdenes de compra en consecuencia.<br><br>
    </td>
    <td>EP09</td>
<tr>
    <td>US-08</td> 
    <td>Reporte de Uso de Ingredientes</td>
    <td> Como administrador, quiero ver estadísticas sobre el uso de ingredientes para ajustar los pedidos y optimizar la producción.</td>
    <td>
        <b>Scenario 01:</b> Generar Reporte de Uso de Ingredientes<br>
        <b>Dado</b> que soy administrador,<br>
        <b>Cuando</b>  acceda a los reportes de uso de ingredientes,<br>
        <b>Entonces</b> el sistema debe mostrar gráficos y estadísticas detalladas del uso de cada ingrediente durante un período específico.<br><br>
        <b>Scenario 02:</b>  Ajustar Pedidos Basado en el Reporte<br>
        <b>Dado</b>  que he revisado el reporte de uso de ingredientes,<br>
        <b>Cuando</b> note un aumento en el uso de ciertos ingredientes,<br>
        <b>Entonces</b> podré ajustar los pedidos para evitar la escasez y optimizar la producción.<br><br>
    </td> 
    <td>EP09</td> 
</tr>

<tr>
    <td>US-09</td> 
    <td>Cierre de Caja Detallado</td>
    <td>Como cajero, quiero generar reportes de cierre de caja diario con detalles de transacciones para asegurar que todo esté en orden al final del día.</td>
    <td>
        <b>Scenario 01:</b> Generar Reporte de Cierre de Caja<br>
        <b>Dado</b> que es el final del día,<br>
        <b>Cuando</b> realice el cierre de caja,<br>
        <b>Entonces</b>el sistema debe generar un reporte detallado con todas las transacciones realizadas, incluyendo efectivo, tarjetas y otros métodos de pago.<br><br>
        <b>Scenario 02:</b> Exportar o Imprimir Reporte de Cierre<br>
        <b>Dado</b> que he generado el reporte de cierre de caja,<br>
        <b>Cuando</b>  lo necesite para mis archivos,<br>
        <b>Entonces</b> el sistema debe permitir la impresión o exportación del reporte para su archivo.<br><br>
    </td> 
    <td>EP13</td> 
</tr>

<tr>
    <td>US-10</td> 
    <td>Tomar Pedidos desde la Mesa</td>
    <td>Como mesero, quiero introducir pedidos directamente en la aplicación desde la mesa para que estos se envíen automáticamente a la cocina.</td>
    <td>
        <b>Scenario 01:</b>Tomar Pedidos desde la Mesa<br>
        <b>Dado</b> que estoy tomando un pedido,<br>
        <b>Cuando</b> introduzca los ítems en la aplicación,<br>
        <b>Entonces</b> estos deben enviarse automáticamente al sistema de cocina.<br><br>
        <b>Scenario 02:</b> Modificar Pedido Antes de Enviar<br>
        <b>Dado</b>  que he tomado un pedido,<br>
        <b>Cuando</b>  el cliente haga una modificación,<br>
        <b>Entonces</b>  el sistema debe permitir la modificación del pedido antes de enviarlo a la cocina.<br><br>
    </td> 
    <td>EP07</td> 
</tr>

<tr>
    <td>US-11</td> 
    <td>Asignación de Mesas</td>
    <td>Como dueño de la granja, quiere saber información detallada sobre el estado de sus cultivos y ganado, para poder administrarlos de manera rápida e informada.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la información detallada<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control de cultivos y ganado<br>
        <b>Entonces</b> el sistema le muestra una lista de todos sus cultivos y ganado con su información detallada.<br><br>
        <b>Scenario 02:</b> Visualización de detalles de cultivos<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> selecciona un cultivo específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre el cultivo, como fecha de siembra, variedades, estado de crecimiento, necesidades de riego y fertilización, etc.<br><br>
        <b>Scenario 03:</b> Visualización de detalles de ganado<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> selecciona un animal o grupo de animales específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre el ganado, como edad, raza, historial de salud, dieta, y cualquier otro detalle relevante.<br><br>
        <b>Scenario 04:</b> Seguimiento de cambios en el estado<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> los cultivos o el ganado experimentan cambios en su estado, como crecimiento, enfermedad, o reproducción<br>
        <b>Entonces</b> el sistema actualiza automáticamente la información mostrada para reflejar los cambios recientes.
    </td> 
    <td>EP07</td> 
</tr>

<tr>
    <td>US-12</td> 
    <td>Ver estadísticas financieras</td>
    <td>Como dueño de la granja, quiere saber estadísticas financieras, para poder administrar correctamente la economía de su granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso a las estadísticas financieras<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control financiero<br>
        <b>Entonces</b> el sistema le muestra una variedad de estadísticas financieras relevantes para su granja.<br><br>
        <b>Scenario 02:</b> Visualización de ingresos y gastos<br>
        <b>Dado</b> que está viendo las estadísticas financieras<br>
        <b>Cuando</b> revisa la sección de ingresos y gastos<br>
        <b>Entonces</b> el sistema le muestra un desglose detallado de los ingresos y gastos de su granja, clasificados por categoría y período de tiempo.<br><br>
        <b>Scenario 03:</b> Análisis de rentabilidad<br>
        <b>Dado</b> que está viendo las estadísticas financieras<br>
        <b>Cuando</b> revisa la sección de análisis de rentabilidad<br>
        <b>Entonces</b> el sistema le muestra métricas y gráficos que le ayudan a evaluar la rentabilidad de su granja, como margen de beneficio, retorno sobre la inversión, etc.
    </td> 
    <td>EP05</td> 
</tr>

<tr>
    <td>US-13</td> 
    <td>Registrar el cumplimiento de tareas con detalles de producción</td>
    <td>Como trabajador en la granja, quiere registrar el cumplimiento de sus tareas con detalles como la cantidad, calidad y fecha de cosecha, para mantener un registro preciso de la producción de la granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso al registro de cumplimiento de tareas<br>
        <b>Dado</b> que es un trabajador autenticado en el sistema<br>
        <b>Cuando</b> accede a su panel de control de tareas<br>
        <b>Entonces</b> el sistema le muestra una lista de tareas asignadas y un formulario para registrar el cumplimiento de las mismas.<br><br>
        <b>Scenario 02:</b> Registro de detalles de producción<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea<br>
        <b>Cuando</b> ingresa los detalles de producción, como cantidad cosechada, calidad del producto, fecha de cosecha, etc.<br>
        <b>Entonces</b> el sistema registra estos detalles junto con la tarea cumplida.<br><br>
        <b>Scenario 03:</b> Registro de calidad del producto<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea relacionada con la producción<br>
        <b>Cuando</b> ingresa la calidad del producto, como grado de madurez, tamaño, estado de frescura, etc.<br>
        <b>Entonces</b> el sistema registra esta información para proporcionar un registro detallado de la calidad de la producción.<br><br>
        <b>Scenario 04:</b> Seguimiento de fechas de cosecha<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea de cosecha<br>
        <b>Cuando</b> ingresa la fecha de cosecha<br>
        <b>Entonces</b> el sistema registra la fecha de cosecha junto con los demás detalles de producción.<br><br>
        <b>Scenario 05:</b> Revisión y edición de registros<br>
        <b>Dado</b> que es un trabajador y desea revisar o editar registros de cumplimiento de tareas anteriores<br>
        <b>Cuando</b> accede al historial de registros de cumplimiento de tareas<br>
        <b>Entonces</b> el sistema le permite ver y editar los detalles registrados previamente, manteniendo un registro preciso y actualizado de la producción de la granja.
    </td> 
    <td>EP12</td> 
</tr>

<tr>
    <td>US-14</td> 
    <td>Emitir alertas de emergencia de manera eficaz</td>
    <td>Como trabajador en la granja, quiere emitir alertas sobre cualquier emergencia a sus colegas y supervisores de manera eficaz e inmediata.</td>
    <td>
        <b>Scenario 01:</b> Acceso rápido a la función de alerta de emergencia<br>
        <b>Dado</b> que es un trabajador en la granja<br>
        <b>Cuando</b> se encuentra en una situación de emergencia<br>
        <b>Entonces</b> quiere acceder rápidamente a la función de alerta de emergencia en la aplicación o dispositivo proporcionado.<br><br>
        <b>Scenario 02:</b> Selección del tipo de emergencia<br>
        <b>Dado</b> que está emitiendo una alerta de emergencia<br>
        <b>Cuando</b> selecciona el tipo de emergencia que está enfrentando, como incendio, accidente, lesión, etc.<br>
        <b>Entonces</b> el sistema registra el tipo de emergencia para una respuesta adecuada.<br><br>
        <b>Scenario 03:</b> Notificación a colegas y supervisores<br>
        <b>Dado</b> que emite una alerta de emergencia<br>
        <b>Cuando</b> envía la alerta<br>
        <b>Entonces</b> el sistema notifica automáticamente a sus colegas y supervisores designados sobre la emergencia, utilizando métodos como notificaciones push, mensajes de texto o llamadas de voz.<br><br>
        <b>Scenario 04:</b> Inclusión de detalles adicionales<br>
        <b>Dado</b> que está emitiendo una alerta de emergencia<br>
        <b>Cuando</b> necesita proporcionar detalles adicionales, como ubicación exacta, número de personas involucradas, gravedad de la situación, etc.<br>
        <b>Entonces</b> el sistema le permite incluir esta información para una mejor comprensión de la emergencia.<br><br>
        <b>Scenario 05:</b> Confirmación de recepción de alerta<br>
        <b>Dado</b> que emite una alerta de emergencia<br>
        <b>Cuando</b> sus colegas y supervisores reciben la alerta<br>
        <b>Entonces</b> el sistema muestra una confirmación de recepción para garantizar que la alerta haya sido recibida y comprendida.
    </td> 
    <td>EP06</td> 
</tr>

<tr>
    <td>US-15</td> 
    <td>Crear un anuncio de la granja</td>
    <td>Como dueño de la granja, quiere crear un anuncio de su granja, para proporcionar información relevante a empresarios interesados en establecer una alianza estratégica.</td>
    <td>
        <b>Scenario 01:</b> Creación de anuncio exitosa<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de creación de anuncios<br>
        <b>Entonces</b> el sistema le permite crear un anuncio proporcionando detalles como descripción de la granja, ubicación, tipo de cultivos, y contacto.<br><br>
        <b>Scenario 02:</b> Falla en la creación del anuncio<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> completa el formulario de creación de anuncio con información incompleta o inválida<br>
        <b>Entonces</b> el sistema muestra un mensaje de error e indica los campos que necesitan ser corregidos.
    </td> 
    <td>EP08</td>
</tr>

<tr>
    <td>US-16</td> 
    <td>Editar un anuncio publicado</td>
    <td>Como dueño de la granja, quiere editar un anuncio publicado, para actualizar la información de su granja cuando sea necesario.</td>
    <td>
        <b>Scenario 01:</b> Edición de anuncio exitosa<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> accede a la sección de anuncios y selecciona un anuncio para editar<br>
        <b>Entonces</b> el sistema le permite modificar la información del anuncio y guardar los cambios.<br><br>
        <b>Scenario 02:</b> Falla en la edición del anuncio<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> intenta editar el anuncio pero ocurre un error en el sistema<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que no se pudo guardar los cambios y sugiere intentar nuevamente más tarde.
    </td> 
    <td>EP08</td> 
</tr>
<tr>
    <td>US-17</td> 
    <td>Eliminar un anuncio publicado</td>
    <td>Como dueño de la granja, quiere eliminar un anuncio publicado, para retirar la información de su granja de la plataforma cuando ya no esté interesado en establecer alianzas.</td>
    <td>
        <b>Scenario 01:</b> Eliminación de anuncio exitosa<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> accede a la sección de anuncios y selecciona un anuncio para eliminar<br>
        <b>Entonces</b> el sistema elimina el anuncio de la plataforma y confirma la eliminación.<br><br>
        <b>Scenario 02:</b> Falla en la eliminación del anuncio<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> intenta eliminar el anuncio pero ocurre un error en el sistema<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que no se pudo eliminar el anuncio y sugiere intentar nuevamente más tarde.
    </td> 
    <td>EP08</td> 
</tr>

<tr>
    <td>US-18</td> 
    <td>Registrarse en la plataforma</td>
    <td>Como dueño de la granja, quiere registrarse en la plataforma, para poder crear y gestionar su cuenta y acceder a las funcionalidades del sistema.</td>
    <td>
        <b>Scenario 01:</b> Registro exitoso<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> accede a la página de registro y completa el formulario con información válida<br>
        <b>Entonces</b> el sistema crea su cuenta y le envía una confirmación de registro.<br><br>
        <b>Scenario 02:</b> Registro fallido por información inválida<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> completa el formulario de registro con información inválida o incompleta<br>
        <b>Entonces</b> el sistema muestra mensajes de error indicando los campos que deben corregirse.<br><br>
        <b>Scenario 03:</b> Registro fallido por cuenta existente<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> intenta registrarse con un correo electrónico ya existente<br>
        <b>Entonces</b> el sistema muestra un mensaje indicando que ya existe una cuenta con ese correo electrónico y sugiere iniciar sesión o recuperar la contraseña.
    </td> 
    <td>EP16</td> 
</tr>
<tr>
    <td>US-19</td> 
    <td>Iniciar sesión en la plataforma</td>
    <td>Como dueño de la granja, quiere iniciar sesión en la plataforma, para poder acceder a su cuenta y gestionar su granja.</td>
    <td>
        <b>Scenario 01:</b> Inicio de sesión exitoso<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce su correo electrónico y contraseña correctos en la página de inicio de sesión<br>
        <b>Entonces</b> el sistema le permite acceder a su cuenta y le muestra su panel de control.<br><br>
        <b>Scenario 02:</b> Inicio de sesión fallido por credenciales incorrectas<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce un correo electrónico o contraseña incorrectos<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que las credenciales no son correctas e invita a intentar nuevamente.<br><br>
        <b>Scenario 03:</b> Recuperación de contraseña<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> no recuerda su contraseña<br>
        <b>Entonces</b> el sistema le proporciona una opción para recuperar su contraseña mediante un enlace de restablecimiento enviado a su correo electrónico.
    </td> 
    <td>EP16</td> 
</tr>

<tr>
    <td>US-20</td> 
    <td>Crear un perfil de trabajador</td>
    <td>Como dueño de la granja, quiere crear un perfil para cada trabajador, para mantener un registro organizado y detallado de sus empleados.</td>
    <td>
        <b>Scenario 01:</b> Creación de perfil de trabajador exitosa<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de empleados y completa el formulario de nuevo trabajador<br>
        <b>Entonces</b> el sistema crea un perfil para el trabajador y lo añade a la lista de empleados.<br><br>
        <b>Scenario 02:</b> Falla en la creación del perfil de trabajador<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> introduce información incompleta o inválida en el formulario de nuevo trabajador<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando los campos que deben corregirse.
    </td> 
    <td>EP04</td> 
</tr>
<tr>
    <td>US-21</td> 
    <td>Visualizar la lista de trabajadores</td>
    <td>Como dueño de la granja, quiere visualizar la lista de todos sus trabajadores, para tener un conocimiento claro de su fuerza laboral.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la lista de trabajadores<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de empleados<br>
        <b>Entonces</b> el sistema le muestra una lista completa de todos los trabajadores con sus detalles respectivos.<br><br>
        <b>Scenario 02:</b> Visualización de detalles del trabajador<br>
        <b>Dado</b> que está viendo la lista de trabajadores<br>
        <b>Cuando</b> selecciona un trabajador específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre ese trabajador, incluyendo su puesto, fecha de inicio, y contacto.
    </td> 
    <td>EP04</td> 

</tr>
<tr>
 <td>US-22</td> 
    <td>Eliminar el perfil de un trabajador</td>
    <td>Como dueño de la granja, quiere eliminar el perfil de un trabajador, para mantener la lista de empleados actualizada cuando un trabajador ya no forme parte del equipo.</td>
    <td>
        <b>Scenario 01:</b> Eliminación de perfil de trabajador exitosa<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de empleados y elimina el perfil de un trabajador<br>
        <b>Entonces</b> el sistema elimina el perfil del trabajador de la lista y muestra un mensaje de confirmación.<br><br>
        <b>Scenario 02:</b> Falla en la eliminación del perfil de trabajador<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> intenta eliminar el perfil de un trabajador pero ocurre un error en el sistema<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que no se pudo eliminar el perfil y sugiere intentar nuevamente más tarde.
    </td> 
    <td>EP04</td> 
</tr>

<tr>
    <td>US-23</td> 
    <td>Registrarse en la plataforma como dueño de empresa</td>
    <td>Como dueño de una empresa, quiere registrarse en la plataforma, para poder crear y gestionar su cuenta y acceder a las funcionalidades del sistema.</td>
    <td>
        <b>Scenario 01:</b> Registro exitoso<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> accede a la página de registro y completa el formulario con información válida<br>
        <b>Entonces</b> el sistema crea su cuenta y le envía una confirmación de registro.<br><br>
        <b>Scenario 02:</b> Registro fallido por información inválida<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> completa el formulario de registro con información inválida o incompleta<br>
        <b>Entonces</b> el sistema muestra mensajes de error indicando los campos que deben corregirse.<br><br>
        <b>Scenario 03:</b> Registro fallido por cuenta existente<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> intenta registrarse con un correo electrónico ya existente<br>
        <b>Entonces</b> el sistema muestra un mensaje indicando que ya existe una cuenta con ese correo electrónico y sugiere iniciar sesión o recuperar la contraseña.
    </td> 
    <td>17</td> 
</tr>
<tr>
    <td>US-24</td> 
    <td>Iniciar sesión en la plataforma como dueño de empresa</td>
    <td>Como dueño de una empresa, quiere iniciar sesión en la plataforma, para poder acceder a su cuenta y gestionar su empresa.</td>
    <td>
        <b>Scenario 01:</b> Inicio de sesión exitoso<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce su correo electrónico y contraseña correctos en la página de inicio de sesión<br>
        <b>Entonces</b> el sistema le permite acceder a su cuenta y le muestra su panel de control.<br><br>
        <b>Scenario 02:</b> Inicio de sesión fallido por credenciales incorrectas<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce un correo electrónico o contraseña incorrectos<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que las credenciales no son correctas e invita a intentar nuevamente.<br><br>
        <b>Scenario 03:</b> Recuperación de contraseña<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> no recuerda su contraseña<br>
        <b>Entonces</b> el sistema le proporciona una opción para recuperar su contraseña mediante un enlace de restablecimiento enviado a su correo electrónico.
    </td> 
    <td>17</td> 
</tr>

</table>

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


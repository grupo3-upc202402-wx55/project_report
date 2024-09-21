
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
    <strong>Startup: Re’Grill</strong><br>
    <strong>Producto: Re’Grill </strong>
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
|   TB1   | 05/09/2024 |Todos los integrantes |      Todo el equipo participó en la definición de la solución propuesta, realizando un análisis de Lean UX y determinando el segmento objetivo. Se recopilaron todos los requisitos necesarios para desarrollar las herramientas requeridas, como User Personas, User Stories, Product Backlog e Impact Mapping, entre otros. Luego, se diseñaron los mockups y prototipos de la página de inicio utilizando la información recopilada. Finalmente, se completó la creación de la página de inicio con la ayuda del sprint backlog, lo que permitió un control eficaz del progreso realizado.                                                                                                                                                                                                                                                                                                                               |

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
Criterio: Demuestra capacidad de comunicarse efectivamente con un rango de audiencias
<p>En el siguiente cuadro se describe las acciones realizadas y enunciados de 
conclusiones cual por parte del grupo, que permiten sustentar el haber 
alcanzado el logro del ABET – EAC - Student Outcome 3.</p>


<table><thead>
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Demuestra capacidad de comunicarse efectivamente con un rango de audiencias</td>
    <td><b> Gabriel Anthony Braithuaite Toledo:</b><br>
TB1: En este caso yo realize todo el capitulo numero 5 , el cual incluye Software Configuration Management, Landing Page, Services & Applications Implementation y Validation Interviews.

<br><b> Adrian Alonso Calle Huayanca</b>   <br>
TB1: Para esta entrega yo realize el punto 4, el cual incluye Product design,Styles guidelines,Information architecture,Landing page and  UI design

<br><b> Hardie Alfonso Holguín Gamarra</b><br>
TB1: Yo me encargue de el capitulo 3 , el cual incluye Requirements Specification, To-Be Scenario Mapping, User Stories, Impact Mapping y Product Backlog.

<br><b> Mateo Italo Loechle Arias:</b> <br>

TB1: En esta entrega , se implemento todo el capitulo 1 , en este caso el startup profile , el solution profile , los antecedentes y problematica y todos los puntos del Lean UX Process.
<br><br><b> David Bryan Rodriguez Santos</b>
TB1: Yo realize todo el capitulo 2 para esta entrega , incluyendo los competidores , las entrevistas , el needfinding y el ubiquitous language.
</td>
    <td>Se lograron los objetivos establecidos<br>gracias a la constante comunicación y<br>organización de<br>nuestro equipo para la correcta elaboración e<br>implementación del presente proyecto</td>
  </tr>
  <tr>
  </tr>
</tbody>
</table>


<h3 id="chapter-1">Capítulo I: Introducción</h3>


<h4 id="startup-profile">1.1. Startup Profile</h4>
Seccion designada a la descripción de la startup y los perfiles de los integrantes del equipo.

<h4 id="startup-description"> 1.1.1. Descripción de la Startup</h4>
Nuestra startup “NoNucleus”, fundada por un grupo de estudiantes de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, es una plataforma con el objetivo de revolucionar la gestión de restaurantes de forma integral, tomando cada aspecto del rubro para optimizar y mejorar estos mismos.

La idea detrás de nuestra aplicación, la cual lleva el nombre de “Re’Grill”, es básicamente darle al cliente lo que quiere, lo que necesita, o lo que optimice de cierta forma todos los procesos posibles. En este caso, contamos con diversas funcionalidades que buscan ser más eficientes que sus contrapartes o agregar una función completamente nueva.


<h4 id="profile-members">1.1.2. Perfiles de integrantes del equipo</h4>

<table><thead>
  <tr>
    <td rowspan="3"> <img src="images/gabriel.jpg"> </td>
    <td>Nombres y Apellidos:Gabriel Anthony Braithuaite Toledo</td>
  </tr>
  <tr>
    <td>Carrera: Ingenieria de Software</td>
  </tr>
  <tr>
    <td>Sobre ti:Mi nombre es Gabriel Anthony Braithuaite Toledo, codigo U20201e889, soy estudiante de la carrera de Ingeniería de Software, tengo conocimientos y experiencia básica en la creación de páginas usando html y css por lo cual creo que podría ser útil al equipo. Además soy responsable con los trabajos en equipo.</td>
  </tr></thead>
<tbody>
  <tr>
    <td rowspan="3"><img src="images/hardie.jpg"></td>
    <td>Nombres y Apellidos:Hardie Alfonso Holguín Gamarra</td>
  </tr>
  <tr>
    <td>Carrera: Ingenieria de Software</td>
  </tr>
  <tr>
    <td>Sobre ti: Soy Hardie Holguín, Estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una persona disciplinada y organizada. En mi tiempo libre me gusta entrenar en el gimnasio y jugar futbol.</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="images/mateo.jpg"></td>
    <td>Nombres y Apellidos:Mateo Italo Loechle Arias</td>
  </tr>
  <tr>
    <td>Carrera: Ingenieria de Software</td>
  </tr>
  <tr>
    <td>Sobre ti:Hola, soy Mateo Italo Loechle Arias, estudiante de Ingeniería de Software apasionado por la tecnología y el desarrollo . Me gustan las cosas relacionadas a mi carrera. Además, la música es uno de mis hobbies favoritos, siempre me acompaña en mi día a día. Me considero una persona responsable y comprometida, siempre buscando mejorar y aprender para enfrentar nuevos desafíos.</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="images/alonso.jpg"></td>
    <td>Nombres y Apellidos:Adrian Alonso Calle Huayanca</td>
  </tr>
  <tr>
    <td>Carrera: Ingenieria de Software</td>
  </tr>
  <tr>
    <td>Sobre ti:Soy Adrian Alonso Calle Huayanca, estoy cursando el 5to ciclo de la carrera de ingeniería de software<br>Me gusta mucho el mundo de las computadoras y redes <br>Terminando la carrera quisiera especializarme en seguridad bancaria. Mi hobby es practicar natación, jugar videojuegos y leer sobre programación</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="images/david.jpg"></td>
    <td>Nombres y Apellidos:David Bryan Rodriguez Santos</td>
  </tr>
  <tr>
    <td>Carrera: Ingenieria de Software</td>
  </tr>
  <tr>
    <td>Sobre ti:Soy David Bryan Rodriguez Santos , soy estudiante de cuarto ciclo de Ingeniería de Software con dominio en Java y Python. Apasionado por la programación y los videojuegos, me destaco por ser entusiasta y responsable, buscando constantemente oportunidades para crecer en el ámbito tecnológico.</td>
  </tr>
</tbody></table>


<h4 id="solution-profile">1.2. Solution Profile</h4>
Re’Grill es una aplicación diseñada para optimizar todos los procesos operativos de un restaurante, brindando una solución económica y eficiente para mejorar la gestión del servicio. La plataforma integra funcionalidades clave como la gestión de mesas, reservas, cocina, ventas, platos, stock, mermas, proveedores y pedidos de insumos, facilitando una administración más fluida y coordinada.

Con Re’Grill, cada aspecto del funcionamiento del restaurante está interconectado, desde la disponibilidad de mesas hasta la coordinación con proveedores, asegurando que el personal pueda gestionar cada elemento de manera efectiva. La aplicación ofrece un enfoque integral que simplifica las operaciones y mejora la experiencia tanto para los clientes como para el equipo del restaurante.


<h4 id="background-and-problems">1.2.1 Antecedentes y problemática</h4>

El principal desafío en la gestión de restaurantes es la falta de una solución integrada que unifique todos los aspectos operativos en una sola plataforma. Esta fragmentación provoca ineficiencias en la administración de mesas, reservas, inventarios y pedidos de insumos, afectando tanto la operativa del restaurante como la experiencia del cliente.

- **What?**

La industria de restaurantes enfrenta desafíos en la gestión de mesas, reservas, pedidos, inventarios y proveedores, lo que afecta la eficiencia operativa y la experiencia del cliente. Los errores comunes incluyen fallos en los pedidos, pérdidas de inventario, demoras en el servicio y coordinación deficiente entre distintas áreas del restaurante junto con los proovedores. Las soluciones actuales suelen ser costosas, dificiles de utilizar o no cuentan con alguna funcionalidad clave.

- **When?**

La problemática se ha agravado en los últimos años debido a la creciente demanda de servicios de restaurantes y la falta de funcionalidades dentro de la competencia de la cual podemos encontrar en grandes cantidades.

- **Where?**

La problemática es relevante en restaurantes de todo tipo y tamaño, desde pequeños establecimientos hasta cadenas de restaurantes.

- **Who?**

Los principales afectados por esta problemática son los propietarios de restaurantes, gerentes, personal de cocina Y servicio, y los clientes que experimentan una atencion posiblemente lenta e ineferciente. Finalmente, los proveedores también se ven afectados cuando la gestión deficiente retrasa o envia datos incorrectos a los pedidos .

- **Why?**

La falta de una solución integrada y automatizada para la gestión de restaurantes provoca ineficiencias operativas, errores en los pedidos, pérdida de inventario y una experiencia del cliente insatisfactoria.Por el lado de proovedores , es necesario porque estos pueden obtener pedidos erroneos o indicados en un rango de tiempo muy corto por lo cual es necesario.

- **How?**

Las soluciones actuales a menudo están divididas en varios sistemas independientes o no cuentan con todas las funcionalidades que un negocio podria necesitar para funcionar eficazmente.De esta forma Re grill apareceria como una opcion integrada con todas las funcionalidades clave para los negocios , y prestaria atencion al cliente para poder implementar cualquier deseo de los clientes .

- **How much?**

Cuando se habla de el rubro de los restaurantes , no contar con un sistema estandarizado y funcional puede llevar a muchisimos problemas , tanto contables como cualquier otro. Normalmente se tiene problemas con el stock de los productos, al tener mala atencion puede disminuir el flujo de clientes afectando directamente a el centro principal de remuneracion de los restaurantes , puede llevar a problemas con los proovedores por mal manejo y solicitud de informacion , hasta si un alimento se mantiene en buen estado o no , comunicacion eficaz entre los pedidos y la cocina , entre muchos mas . No contar con una solucion de este tipo significa un porcentaje demasiado grande con respecto a los restaurantes.


<h4 id="lean-ux">1.2.2 Lean UX Process.</h4>
<h4 id="lean-ux-problem">1.2.2.1. Lean UX Problem Statements.</h4>

Re'Grill busca aprovechar la oportunidad de ofrecer una solución integral que resuelva la fragmentación de los sistemas en los restaurantes, optimizando la eficiencia en la gestión de mesas, reservas, inventarios, y pedidos de insumos. La falta de integración tecnológica ha generado ineficiencias operativas, lo que afecta la experiencia del cliente y aumenta los costos para los propietarios.
En un mercado altamente competitivo, los restaurantes enfrentan barreras como altos costos de implementación tecnológica o dificultad para adaptarse a el sistema, lo que ha impedido una adopción generalizada de soluciones integradas.La falta de una plataforma asequible y integrada con funcionalidades necesarias hacen que Re'Grill se posicione como líder al proporcionar una solución eficiente, económica y fácil de usar que resuelve los problemas de gestión operativa.


<h4 id="lean-ux-assumptions">1.2.2.2. Lean UX Assumptions.</h4>

**Business Outcomes:**

- Lograr un crecimiento con al menos 10 restaurantes utilizando Re’Grill en el primer año.

- Resaltar en el mercado de aplicaciones de gestión de restaurantes con una tasa de adopción del 20% en el primer trimestre.

- Obtener comentarios positivos de los clientes hacia la eficacia de nuestro sistema.

**User Assumptions:**
**Assumptions Worksheet**<br>
**¿Quién es el usuario?**
- La parte administrativa de un restaurante
- Los proveedores de restaurantes

**¿Qué problemas tiene nuestro producto? ¿Resolver?**
- Gestión con los productos que se tienen en el restaurante
- Comunicación con los proveedores de alimentos para los ingredientes de sus platillos a la carta

**¿Qué características son importantes?**
- Una mejor forma de contactarse entre la parte administrativa y el proveedor para la reponer los productos
- Mejorar la atención del cliente con los platillos que se encuentran disponibles en dicho momento.
- Organización de las cantidades de los productos, ya sea comestibles o de mantenimiento.
- Interfaz amigable para cualquier usuario que lo use.

**¿Dónde encaja nuestro producto en su trabajo o vida?**
- Para la administración, nuestro producto les ayudará a gestionar los ingredientes de los platos que cocinan, además de conocer los desperdicios que hay al momento de cocinar y las cantidades de mesas, sillas, entre otros.
- Para los proveedores, el producto los ayudará en mejorar la comunicación entre ellos y la administración del restaurante, además de brindar las cantidades exactas que necesita el restaurante.

**¿Cuándo y cómo es nuestro producto? ¿Usado?**
- El producto será utilizado cuando la administración del restaurante comienza a gestionar el inventario que posee actualmente, además de ver si las cantidades son las suficientes para las preparaciones al momento de atender.
- El producto será usado por algunos proveedores de restaurantes, donde podrán visualizar los distintos restaurantes que necesitan contactarse con algún proveedor de algún consumible.
- El producto será a través de una aplicación web mediante algún dispositivo que usa internet y un navegador como Chrome.

**¿Cómo debe verse nuestro producto y cómo comportarse?**
- El diseño de nuestro producto debe ser atractivo y coherente con respecto al diseño del restaurante.
- La plataforma debe cargar de manera rápida las respuestas a las acciones del usuario para que no se frustre.
- La navegación de la plataforma debe ser intuitiva y comprensible, donde los usuarios pueden ver los filtros necesarios y las distintas opciones que tiene.
- Debe mostrar a los clientes con gráficos y una pequeña descripción acerca del plato de comida que busca.
- Esta plataforma debe ser compatible con algunos dispositivos de dimensiones distintas, como celulares, laptops, tablets y computadoras, donde se usa un diseño responsive.

**Business Outcomes**<br>
- Convertir nuestro producto como una plataforma indispensable para la gestión de restaurantes, ya sea en la manera de reponer el inventario, organización del mismo local y la atención de los clientes.
- Un 75% de los usuarios que usaron la página han logrado gestionar de mejor manera los restaurantes.
- Un 20% de los clientes de restaurantes se muestran insatisfechos con la atención que brinda los restaurantes.

**User Benefits**<br>
- Ahorro de tiempo por la manera de gestionar el inventario.
- Facilidad en buscar los productos faltantes o desperdiciados.
- Mejor comunicación entre el proveedor y la administración.

**Assumptions Steps**<br>
**a. Creo que mis clientes necesitan:**
  - Visualización de disponibilidad de platillos.
  - Expresar de manera intuitiva el inventario que se lleva en el local
  - Comunicarse de manera eficiente con otro tipo de usuario

**b. Estas necesidades se pueden resolver con:**
  - Un sistema que calcula lo que hay en el inventario en general y lo que se usa al día.
  - Una base de datos que se actualiza cada vez que cambia y se use parte de lo que hay en el inventario.
  - Un diseño que sea muy atractivo visualmente y a la vez entendible para gestionar el restaurante.
  - Accesibilidad para su uso en distintos dispositivos según lo que el usuario usará.

**c. Mis clientes iniciales son (o serán):**
  - La parte administrativa de un restaurante.
  - Los proveedores o vendedores de alimentos para los restaurantes.

**d. El valor #1 que un cliente quiere de mi producto es veracidad (utilidad, funcionalidades que le resuelven el problema)**
  - La garantía de que no habrá problemas en las cantidades con respecto al inventario por la base de datos.
  - La comunicación de manera directa con el proveedor con respecto a la necesidad del restaurante.

**e. El cliente también puede obtener estos beneficios adicionales:**
  - Obtener las cantidades de la merma que se obtiene al hacer un plato.
  - Mejorar la administración del restaurante.          

**f. Voy a adquirir la mayoría de mis clientes a través de:**
  - Colaboración con un restaurante conocido.
  - Estrategias de marketing digital con el enfoque en los distintos restaurantes.

**g. Haré dinero a través de:**
  - Membresías premium con acceso exclusivo y funciones adicionales

**h. Mi competencia principal en el mercado:**
  - Tiendas virtuales de restaurantes que se enfocan en las ventas.
  - Páginas de gestión de restaurantes.

**i. Los venceremos debido a:**
  - El diseño es atractivo y accesible para cualquier tipo de usuario ya sea la administración o el proveedor.
  - La base de datos actualizada constantemente con respecto a la necesidad del usuario.

**j. Mi mayor riesgo del producto es:**
  - La desconfianza por parte de los restaurantes con respecto a la correcta función del programa al momento de tener días especiales.
  - El mal cálculo del inventario al momento de mostrar las cantidades de cada producto que se encuentra disponible.

**k. Resolveremos esto a través de:**
  - Mostrando pruebas funcionales de esto y su adaptabilidad ante algún problema que se muestra de manera sorpresiva.
  - Las constantes verificaciones que se realizará al momento de que se haga alguna compra.

**l. ¿Qué otras suposiciones tenemos? ¿Eso, si se prueba que es falso, causará que nuestro negocio / proyecto no funcione?**
  - Podrá ser que las estrategias de marketing que se usa podrán ayudar a obtener más compañías que le darán uso de la aplicación. En caso se muestre el contrario, podría afectar de manera negativa la inversión del negocio.
  - Las ventas de las suscripciones para obtener más funciones que les será muy útil para mejorar su experiencia con la página. Si se prueba que es falso, afectaría de manera directa con la generación de ingresos y sostenibilidad del negocio.

<h4 id="lean-ux-hypothesis">1.2.2.3. Lean UX Hypothesis Statements.</h4>

**Adopción Tecnológica por Restaurantes Pequeños y Medianos:**
Creemos que al ofrecer una plataforma asequible y fácil de implementar, podemos reducir las barreras de entrada para pequeños y medianos restaurantes, logrando que el 40% de ellos adopten la solución de Re'Grill en su primer año de lanzamiento. Esto permitirá que estos restaurantes mejoren la eficiencia operativa sin incurrir en altos costos tecnológicos.

**Accesibilidad Económica:**
Creemos que al ofrecer una solución rentable en comparación con los sistemas tecnológicos fragmentados o más caros en el mercado, podemos lograr que al menos el 60% de los restaurantes que evalúen Re'Grill lo consideren como su primera opción debido a su bajo costo de implementación y mantenimiento.

**Adaptación del Personal a la Plataforma:**
Creemos que al ofrecer una interfaz intuitiva y fácil de aprender, el personal operativo (cocina, servicio y gerentes) podrá adaptarse al uso de Re'Grill en un plazo máximo de 2 semanas, con una reducción del 25% en errores operativos relacionados con la falta de familiarización con la tecnología.

**Mejora en la Eficiencia Operativa:** Creemos que al implementar un sistema integrado para la gestión de mesas, reservas, inventarios y ventas, podemos mejorar la eficiencia operativa de los restaurantes en un 15%. Esto se traducirá en una reducción de errores administrativos y una mejor coordinación entre las distintas áreas del restaurante.

**Optimización de la Gestión de Inventarios:** Creemos que al ofrecer una funcionalidad de seguimiento en tiempo real del stock de insumos y mermas, podemos reducir el tiempo dedicado a la gestión de inventarios en un 20%. Esto permitirá a los restaurantes minimizar las pérdidas y gestionar mejor los recursos disponibles.

**Mejora en la Experiencia del Cliente:** Creemos que al proporcionar una interfaz intuitiva y fácil de usar para la gestión de reservas y mesas, podemos aumentar la satisfacción del cliente en un 25%. Una experiencia más fluida y organizada contribuirá a una mayor fidelización de los clientes y a una mejor reputación del restaurante.

**Eficiencia en la Coordinación con Proveedores:** Creemos que al integrar herramientas de comunicación y coordinación con proveedores en la plataforma, podemos simplificar el proceso de pedidos de insumos y mejorar la relación con los proveedores. Esto resultará en una reducción del 30% en el tiempo requerido para gestionar estos pedidos.

**Reducción de Errores en la Gestión de Pedidos:** Creemos que al automatizar la integración entre las reservas, la cocina y el módulo de ventas, podemos reducir los errores en la gestión de pedidos en un 25%. Esto mejorará la precisión en la preparación de los platos y la satisfacción general de los clientes.

<h4 id="lean-ux-canvas">1.2.2.4. Lean UX Canvas.</h4>

<img src="images/CANVAS.jpg">

<h4 id="target-segments">1.3. Segmentos objetivo.</h4>
1. **Propietarios y Gerentes de Restaurantes Pequeños y Medianos:**
   Este segmento incluye a dueños y gerentes de restaurantes que buscan optimizar sus operaciones diarias mediante la integración de funciones de gestión como reservas, mesas, cocina, ventas, inventario, y relación con proveedores. La propuesta de valor para este segmento es la mejora de la eficiencia operativa, la reducción del desperdicio, y una mayor satisfacción del cliente gracias a una plataforma todo-en-uno.

2. **Proveedor de Insumos para Restaurantes:**
   Este segmento incluye a empresas y proveedores que suministran alimentos, bebidas, utensilios, y otros productos necesarios para el funcionamiento de los restaurantes. Re-Grill les ofrece una plataforma para interactuar directamente con los restaurantes, ver sus necesidades en tiempo real, y gestionar los pedidos de manera más eficiente. La propuesta de valor para este segmento es la simplificación del proceso de pedidos, reducción de errores de comunicación, y la posibilidad de establecer relaciones más sólidas con sus clientes restauranteros.


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


# Capítulo IV: Product Design
## 4.1. Style Guidelines

Una guía de estilo es un conjunto de reglas y estándares que definen cómo deben escribirse, diseñarse y presentarse los documentos, el contenido web y el software. A continuación, se presentan las especificaciones de los parámetros implementados en la estructura del proyecto.

### 4.1.1. General Style Guidelines 

* Branding History

  Para la creación del logotipo de nuestro producto GlassGo, optamos por un diseño moderno y minimalista que refleje las intenciones de la aplicación. El logotipo consta de una tipografía elegante y sencilla, acompañada de un ícono que simboliza la eficiencia rápida y la durabilidad del producto durante el envío, junto con una frase honesta y alentadora. Mostrando colores que demuestran seguridad, rapidez y equilibrio como blanco, gris, verde, naranja y azul.

  ![Logos](assets/images/cap4/general/Logos_type.png)

* Typography

  Para la tipografía de nuestro producto GlassGo, elegimos fuentes modernas y minimalistas que reflejen las intenciones de la aplicación. La tipografía consta de fuentes elegantes y sencillas, complementando el ícono que simboliza la eficiencia rápida y la durabilidad del producto durante el envío, junto con un mensaje honesto y alentador. La tipografía utiliza colores que demuestran seguridad, rapidez y equilibrio, incluyendo blanco, gris, verde, naranja y azul.

  ![Letter_type1](assets/images/cap4/general/Letter.png)

  ![Letter_type2](assets/images/cap4/general/Letter2.png)

* Colors

  La paleta de colores de GlassGo consiste en tonos que transmiten confianza, rapidez y profesionalismo, valores esenciales para una marca enfocada en la entrega segura de productos. El azul principal refleja estabilidad y seguridad, mientras que el naranja añade dinamismo y movimiento, reforzando la idea de inmediatez. El gris neutro equilibra y añade sobriedad, asegurando una comunicación clara y profesional.

  * Azul → *#002140*

    ![Blue](assets/images/cap4/general/Blue.png)

  * Gris Medio → *#6B6B6B*
  * Blanco → *#FFFFFF*
  * Negro → *#000000*

    ![Gray](assets/images/cap4/general/Gris.png)![White](assets/images/cap4/general/white.png)![Black](assets/images/cap4/general/black.png)

* Spacing

  La paleta de colores de GlassGo consiste en tonos que transmiten confianza, rapidez y profesionalismo, valores esenciales para una marca enfocada en la entrega segura de productos. El azul principal refleja estabilidad y seguridad, mientras que el naranja añade dinamismo y movimiento, reforzando la idea de inmediatez. El gris neutro equilibra y añade sobriedad, asegurando una comunicación clara y profesional.

  ![space](assets/images/cap4/general/Px.png)

### 4.1.2. Web Style Guidelines

  Para GlassGo, planeamos desarrollar una plataforma web. Por lo tanto, implementaremos un diseño responsivo (conocido como Web Responsive Design) con el objetivo de optimizar la presentación de la información en cualquier dispositivo. Esto garantizará que el contenido se mantenga intacto y, en última instancia, mejore la experiencia del usuario.

  Como equipo, hemos decidido incorporar el diseño en patrón F en nuestro sitio web. Este patrón es especialmente adecuado para GlassGo, ya que los usuarios tienden a explorar el contenido rápidamente y priorizan la información en la parte superior e izquierda de la pantalla. Esto ayuda a resaltar los datos relevantes desde el principio y facilita la lectura de las secciones clave.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

* Menú Principal

| Tópico | Definición |
| :---: | ----- |
| Home page | La página de inicio puede mostrar una descripción general del servicio y resaltar las características clave. |
| Log in | La página donde los usuarios pueden iniciar sesión en su sesión. Si no tienen una cuenta, hay una sección para registrarse gratis en el servicio web. |
| Technical support | La página proporciona un espacio para que los usuarios compartan sus preguntas, asistencia técnica o quejas sobre el sistema. |

* Página de Suscripción

| Tópico | Definición |
| :---: | ----- |
| Plan para Empresas de Transporte | Plan para empresas que buscan una asociación con un distribuidor. Los beneficios incluyen: tarifas preferenciales, informes avanzados y soporte prioritario. |
| Plan para Distribuidores de Productos Terminados | Plan para distribuidores que buscan una solución logística para gestionar adecuadamente sus recursos. |
| Plan de Mercado | Plan individual para negocios comunes como restaurantes, bares y licorerías. |

* Página de Inicio de Sesión

| Tópico | Definición |
| :---: | ----- |
| Registro y Autenticación | Plan para empresas que buscan una asociación con un distribuidor. Los beneficios incluyen: tarifas preferenciales, informes avanzados y soporte prioritario. |

* Otras Páginas y Funciones

| Tópico | Definición |
| :---: | ----- |
| Perfil de Usuario | La página de inicio puede mostrar una descripción general del servicio y resaltar las características clave. |
| Configuración | La página donde los usuarios pueden iniciar sesión en su sesión. Si no tienen una cuenta, hay una sección para registrarse gratis. |
| Sobre Nosotros | La página proporciona un espacio para que los usuarios compartan sus preguntas, asistencia técnica o quejas. |
| Barra de Navegación | Una barra de navegación clara y consistente en la parte superior de cada página facilita la navegación entre las secciones principales. |
| Responsive design | La aplicación debe ser fácil de usar tanto en dispositivos de escritorio como móviles, adaptando la interfaz de usuario al tamaño de la pantalla. |

### 4.2.2. Labeling Systems

Para los sistemas de etiquetado, hemos elegido organizar el contenido a través de encabezados que agrupan las secciones a las que los usuarios pueden acceder. De esta manera, los usuarios saben dónde hacer clic para acceder a las secciones correspondientes.

| Tópico | Definición |
| :---: | ----- |
| Home Page | Sección principal a la que los usuarios llegarán al ingresar al enlace de la aplicación web. |
| Subscription | En esta sección, los usuarios pueden ver los planes y tarifas disponibles. |
| Technical Support | Esta sección proporciona a los usuarios todos los canales a través de los cuales pueden contactarnos. |

### 4.2.3. SEO Tags and Meta Tags

* ### Landing Page

  * Charset:
    *<meta charset="utf-8">*

    Indica al navegador cómo interpretar los caracteres de texto. Al especificar UTF-8, se asegura de que la página de aterrizaje de GlassGo  muestre correctamente tildes, la letra "ñ" y símbolos especiales, asegurando una visualización adecuada en cualquier idioma

  * Viewport(responsive):
    *<meta name="viewport" content="width=device-width, initial-scale=1">*

    Permite que la página se adapte a diferentes dispositivos (móvil, tableta, PC), asegurando que la presentación de GlassGo sea legible y óptima en cualquier pantalla.

  * Title(SEO):
    *<title>GlassGo | Transporte Seguro y Trazabilidad de Envíos de Vidrio</title>*

    Define el título que aparecerá en la pestaña del navegador y en los resultados de búsqueda. Su función es proporcionar una descripción clara y concisa del servicio principal de GlassGo.

  * Meta Description:
    *<meta name="description" content="GlassGo ofrece transporte seguro y trazabilidad de envíos de vidrio. Reduce pérdidas, asegura la integridad del producto y mejora la eficiencia logística.">*

    Proporciona un resumen breve que aparecerá en los resultados de búsqueda. Su objetivo es atraer a usuarios interesados en logística sostenible y soluciones de transporte seguro.

  * Meta keywords(SEO, deprecated for Google):
    *<meta name="keywords" content="transporte de vidrio, logística sostenible, trazabilidad, distribución segura, envío rápido, GlassGo">*

    Identifica palabras clave relacionadas con el servicio de GlassGo. Aunque su impacto es actualmente limitado, sigue siendo útil para sistemas de indexación básicos.

  * Meta Authors:
    *<meta name="author" content="Equipo de GlassGo">*

    Atribuye la autoría del contenido de la página de aterrizaje al equipo del proyecto GlassGo.

  * Meta Robots:
    *<meta name="robots" content="index, follow">*

    Permite que los motores de búsqueda indexen la página de GlassGo y sigan sus enlaces, asegurando una mayor visibilidad.

  * Meta Language:
    *<meta name="language" content="es">*

    Indica que el contenido de la página de aterrizaje está en español, optimizando su indexación y compatibilidad con navegadores.

  * Meta Copyright:
    *<meta name="copyright" content="GlassGo 2025">*

    Indica la titularidad de los derechos de autor del contenido y diseño de la página de aterrizaje.

* ### Aplicación Web

  * Charset:
    *<meta charset="utf-8">*

    Asegura que todos los caracteres y símbolos en la interfaz de la aplicación GlassGo se muestren correctamente.

  * Viewport(responsive):
    *<meta name="viewport" content="width=device-width, initial-scale=1">*

    Asegura que la aplicación web (panel de gestión, tablero de trazabilidad) sea completamente responsiva y se adapte a diferentes dispositivos.

  * Title(SEO):
    *<title>Aplicación GlassGo | Trazabilidad y Panel de Gestión</title>*

    Define el título que aparece en el navegador para identificar el panel de la aplicación web.

  * Meta Description:
    *<meta name="description" content="Panel interno de GlassGo para gestionar envíos, trazabilidad y planes de suscripción. Acceso exclusivo para usuarios registrados.">*

    Describe el contenido del panel, aunque su relevancia SEO es limitada ya que es un espacio interno.

  * Meta Authors:
    *<meta name="author" content="Equipo de GlassGo">*

    Atribuye el desarrollo del panel de control a la marca.

  * Meta Robots:
    *<meta name="robots" content="noindex, nofollow">*

    Evita que los motores de búsqueda indexen el contenido privado de la aplicación (historial de envíos, métricas, etc.).

  * Meta Language:
    *<meta name="language" content="es">*

    Declara el español como el idioma principal del panel de GlassGo.

  * Meta Copyright:
    *<meta name="copyright" content="GlassGo 2025">*

    Protege legalmente el contenido y diseño del software de GlassGo.

### 4.2.4. Searching Systems

El motor de búsqueda es fundamental para que los usuarios encuentren rápidamente detalles específicos.
* Características Clave

  Las búsquedas basadas en objetivos permitirán a los propietarios de negocios, transportistas y distribuidores:

  * Identificar impactos en la carga en las últimas 24 horas
  * Anticipar rutas con altas tasas de incidentes durante el tránsito, guardando esta información para que otros transportistas puedan manejar con precaución
  * Generar evidencia si un reclamo es realizado por el cliente o proveedor
  * Verificar el estado de la carga antes de la aceptación
  * Etiquetar inventario de alta prioridad durante temporadas pico
  * Consultar el historial de transporte para prevenir posibles roturas de carga

### 4.2.5. Navigation Systems

El Sistema de Navegación es la estructura que permite a los usuarios moverse de manera eficiente entre diferentes secciones y páginas de la aplicación.

* Estructura de Navegación
  * Logo - link to Homepage
  * Homepage— resumen / landing con beneficios y CTA
  * Solutions / Servicios — páginas por segmento
    * Transportistas
    * Distribuidores
    * Comercios (Dueños de negocio)
  * Subscriptions / Planes — comparación de planes y precios
  * Support / Soporte — Centro de ayuda, FAQ, contacto
  * Contact — formulario de contacto / ventas
  * Buscar (Search) — campo de búsqueda global
  * Botón Log In / Sign Up (derecha)


## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

**Wireframe 1: Vista general de la página de aterrizaje**
![wirefrime1](assets/images/cap4/landing-page-ui/wirefram-1.png)

**Wireframe 2: Que aportamos nostros**
![wirefrime2](assets/images/cap4/landing-page-ui/wireframe-2.png)

**Wireframe 3: Sección de beneficios y características**
![wirefrime3](assets/images/cap4/landing-page-ui/wireframe-3.png)

**Wireframe 4: Testimonios e historias de éxito**
![wirefrime4](assets/images/cap4/landing-page-ui/wireframe-4.png)

**Wireframe 5: FAQ y soporten**
![wirefrime5](assets/images/cap4/landing-page-ui/wirefram-5.png)

**Wireframe 6: Turiales de como funciona la pagina web**
![wirefrime6](assets/images/cap4/landing-page-ui/wireframe-6.png)

**Wireframe 7: Descargar nuestra web**
![wirefrime7](assets/images/cap4/landing-page-ui/wireframe-8.png)


### 4.3.2. Landing Page Mock-up

**Mockup 1: Vista general de la página de aterrizaje**
![Mockup1](assets/images/cap4/landing-page-ui/Mockup-1.png)

**Mockup 2: Que aportamos nostros**
![Mockup2](assets/images/cap4/landing-page-ui/Mockup-2.png)

**Mockup 3: Sección de beneficios y características**
![Mockup3](assets/images/cap4/landing-page-ui/Mockup-3.png)

**Mockup 4: Testimonios e historias de éxito**
![Mockup4](assets/images/cap4/landing-page-ui/Mockup-4.png)

**Mockup 5: FAQ y soporten**
![Mockup5](assets/images/cap4/landing-page-ui/Mockup-5.png)

**Mockup 6: Turiales de como funciona la pagina web**
![Mockup6](assets/images/cap4/landing-page-ui/Mockup-6.png)

**Mockup 7: Descargar nuestra web**
![Mockup7](assets/images/cap4/landing-page-ui/Mockup-9.png)

## 4.4. Web Applications UX/UI Design

El diseño de la experiencia del usuario (UX) y la interfaz de usuario (UI) de nuestra página de aterrizaje tiene como objetivo ofrecer una interacción digital clara, atractiva y simple para los visitantes. UX se centra en comprender qué buscan y esperan los usuarios, organizando la información y los flujos de navegación para que el recorrido sea cómodo y eficiente. UI, por otro lado, se ocupa del aspecto visual, como la disposición de elementos, botones, menús y presentación de contenido. Al combinar ambos enfoques, lograremos un diseño que no solo es estéticamente agradable, sino también funcional y fácil de usar, generando una experiencia positiva que motive a los usuarios a interesarse por nuestro producto.

### 4.4.1. Web Applications Wireframes

* #### Log in

![](assets/images/cap4/style-guidelines/Wireframes/Log%20in/login-Sign%20in.png)

![](assets/images/cap4/style-guidelines/Wireframes/Log%20in/Login-Sign%20in-Google.png)

![](assets/images/cap4/style-guidelines/Wireframes/Log%20in/Register-Sign%20up.png)

![](assets/images/cap4/style-guidelines/Wireframes/Log%20in/recover_password.png)

![](assets/images/cap4/style-guidelines/Wireframes/Log%20in/Register-Loading-Succesful-maybe.png)

#### Segmento 1: Transportistas

![](assets/images/cap4/style-guidelines/Wireframes/Transportes/Empresas%20de%20transporte%20de%20camiones/clientes.png)

![](assets/images/cap4/style-guidelines/Wireframes/Transportes/Empresas%20de%20transporte%20de%20camiones/tracking.png)

![](assets/images/cap4/style-guidelines/Wireframes/Transportes/Empresas%20de%20transporte%20de%20camiones/gestion%20de%20stock.png)

![](assets/images/cap4/style-guidelines/Wireframes/Transportes/calendario%20tranportes/calendar.png)

![](assets/images/cap4/style-guidelines/Wireframes/Transportes/Report.png)

![](assets/images/cap4/style-guidelines/Wireframes/Transportes/Empresas%20de%20transporte%20de%20camiones/historial%20de%20envios.png)

![](assets/images/cap4/style-guidelines/Wireframes/Transportes/Empresas%20de%20transporte%20de%20camiones/registro%20de%20reclamos.png)

#### Segmentos 2 & 3: Distribuidores de Licores y Propietarios de Negocios

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Home.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Create_order.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Traking.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Traking_complete.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Inventario.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Calendar.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Report.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/History.png)

![](assets/images/cap4/style-guidelines/Wireframes/Distrubidores&dueños/Reclamos.png)


### 4.4.2. Web Applications Wireflow Diagrams

Los diagramas de wireflow son representaciones gráficas que combinan la estructura del wireframe con la lógica de un diagrama de flujo, mostrando cómo los usuarios interactúan y se mueven dentro de una aplicación web. Estos diagramas permiten visualizar la experiencia de navegación, detectar posibles fricciones de usabilidad y diseñar recorridos de usuario más fluidos y eficientes.

Los diagramas abarcan la gestión de inventario, el seguimiento de envíos, el uso del calendario de entregas, la generación de informes y la gestión de reclamos. De esta manera, el diagrama proporciona una visión completa de la plataforma, asegurando una experiencia clara y organizada alineada con las necesidades de cada usuario.

![Wireflow_diagram](assets/images/cap4/information-architecture/Wireflow_diagram.png)

[https://lucid.app/lucidchart/1d76ffac-1618-4b03-a28f-a5a840f67ac7/edit?viewport\_loc=-12591%2C-6613%2C22617%2C11070%2C0\_0\&invitationId=inv\_592714f1-7efd-4777-8053-5ed7aae18f41](https://lucid.app/lucidchart/1d76ffac-1618-4b03-a28f-a5a840f67ac7/edit?viewport_loc=-12591%2C-6613%2C22617%2C11070%2C0_0&invitationId=inv_592714f1-7efd-4777-8053-5ed7aae18f41)

### 4.4.3. Web Applications Mock-ups

* Login - Pantalla de acceso principal que permite el inicio de sesión según el tipo de usuario. Priorizando la simplicidad, alto contraste y botones accesibles.

  **![Log in](assets/images/cap4/style-guidelines/Mockups/Log%20in/login-Sign%20in.png)**

* Google Login – Acceso Rápido
Alternativa de autenticación utilizando la cuenta de Google para agilizar el proceso de inicio de sesión.

  **![Log in - Google](assets/images/cap4/style-guidelines/Mockups/Log%20in/Login-Sign%20in-Google.png)**

* Actualizar contraseñas olvidadas.

  **![Recover - password](assets/images/cap4/style-guidelines/Mockups/Log%20in/recover_password.png)**

* Registrar una cuenta para acceder a la aplicación.

  **![Sign up](assets/images/cap4/style-guidelines/Mockups/Log%20in/Register-Sign%20up.png)**

* Pantalla de Bienvenida de GlassGo
Presenta la identidad visual del sistema antes de ingresar al panel principal.

   **![Succesful](assets/images/cap4/style-guidelines/Mockups/Log%20in/Register-Loading-Succesful-maybe.png)**

#### Segmentos 2 & 3: Distribuidores de Licores y Propietarios de Negocios

* Vista inicial con resumen de viajes activos, notificaciones y acceso rápido.
  
  **![Home](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Home.png)**

* Crear y ver resumen de órdenes de entrega asignadas.
  
  **![Create Order](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Create_order.png)**

* Muestra la ruta actual con origen, destino y puntos de control definidos.
  
  **![Tracking](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Traking.png)**

* Ver ubicación en tiempo real del camión, mostrando desvíos, impactos o alertas de exceso de velocidad.
  
  **![Detailed Tracking](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Traking_complete.png)**

* Muestra los productos transportados y su estado. Permite reportar incidentes o confirmar recepción.
  
  **![Inventory](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Inventary.png)**

* Muestra fechas programadas y horas estimadas de llegada (ETA) para la planificación de rutas.
  
  **![Calendar](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Calendar.png)**

* Formulario para registrar eventos como retrasos, daños o alertas durante el viaje.
  
  **![Report](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Report.png)**

* Registro de viajes completados con información de fechas, horas y distancias.
  
  **![History](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/History.png)**

* Muestra reclamos asociados a entregas anteriores para referencia y seguimiento.
  
  **![Claim](assets/images/cap4/style-guidelines/Mockups/Distrubidores&dueños/Claim.png)**


#### Segmento 1: Transportistas

* Resumen general de órdenes activas, entregas y estadísticas de rendimiento.
  
  **![Home](assets/images/cap4/style-guidelines/Mockups/Transportes/Customers/camiones.png)**

* Muestra los negocios asociados y sus órdenes recientes.
  
  **![Customer](assets/images/cap4/style-guidelines/Mockups/Transportes/Clientes/Camiones.png)**

* Muestra la ubicación en tiempo real de los camiones asignados en el mapa.
  
  **![Tracking](assets/images/cap4/style-guidelines/Mockups/Transportes/Tracking/camiones.png)**

* Ver productos disponibles con cantidad, estado y opción para editar registros.
  
  **![Stock](assets/images/cap4/style-guidelines/Mockups/Transportes/Stock%20management.png)**

* Revisar y organizar entregas próximas a través de un calendario visual.
  
  **![Calendar](assets/images/cap4/style-guidelines/Mockups/Transportes/Calendar/camiones.png)**

* Muestra métricas comparativas de tiempo, distancia y costos de entrega.
  
  **![Report](assets/images/cap4/style-guidelines/Mockups/Transportes/Report/camiones.png)**

* Registro de compras anteriores con estado, fecha y monto.
  
  **![History](assets/images/cap4/style-guidelines/Mockups/Transportes/Shipping%20history.png)**

* Permite la comunicación directa con los transportistas desde el panel.
  
  **![Communication](assets/images/cap4/style-guidelines/Mockups/Transportes/Claims%20registry.png)**  

### 4.4.4. Web Applications User Flow Diagrams

**Global**

![Global](assets/images/cap4/information-architecture/ALL.png)

**Diagrama 1: Inicio del flujo de usuario en la plataforma**
![1](assets/images/cap4/information-architecture/1.png)

**Diagrama 2: Proceso de autenticación y acceso**
![2](assets/images/cap4/information-architecture/2.png)

**Diagrama 3: Navegación por el panel principal**
![3](assets/images/cap4/information-architecture/3.png)

**Diagrama 4: Gestión y visualización de órdenes**
![4](assets/images/cap4/information-architecture/4.png)

**Diagrama 5: Seguimiento de envíos y rutas**
![5](assets/images/cap4/information-architecture/5.png)

**Diagrama 6: Registro y gestión de incidentes**
![6](assets/images/cap4/information-architecture/6.png)

**Diagrama 7: Finalización de procesos y cierre de sesión**
![7](assets/images/cap4/information-architecture/7.png)
![7](assets/images/cap4/information-architecture/8.png)

## 4.5. Web Applications Prototyping

[https://www.figma.com/design/nV0UrH5YsFXu9run93EmRm/GlassGo?node-id=0-1\&t=2SDCRONXUcQzrQsj-1](https://www.figma.com/design/nV0UrH5YsFXu9run93EmRm/GlassGo?node-id=0-1&t=2SDCRONXUcQzrQsj-1)

## 4.6. Domain-Driven Software Architecture

El Diseño Orientado al Dominio (DDD) se centra en modelar el sistema en función de los procesos comerciales clave: transporte seguro de licores en envases de vidrio, trazabilidad de envíos y monitoreo de condiciones de transporte. Este enfoque permite que cada parte del software refleje fielmente la lógica del negocio, facilitando la escalabilidad y el mantenimiento de GlassGo, el producto principal de la startup RPG.

### 4.6.1. Design-Level EventStorming
* visión global

  ![event_storming_global](assets/images/cap4/diagrams/eventstorming/design-level/GlassGo_EventStorming.png)

* Vistas Específicas por Bounded Context:
  * **Identity Access**

  ![identity_&_access_management](assets/images/cap4/diagrams/eventstorming/design-level/Identity_Access_Management.png)

  * **Profiles Preferences**

  ![profile_&_preferences](assets/images/cap4/diagrams/eventstorming/design-level/Profile_Preferences.png)

  * **Payments Subscriptions**

  ![payments_&_subscriptions](assets/images/cap4/diagrams/eventstorming/design-level/Payments_Subscriptions.png)

  * **Service Planning**

  ![service_planning](assets/images/cap4/diagrams/eventstorming/design-level/Service_Planning.png)

  * **Service Execution**

  ![service_execution_&_monitoring](assets/images/cap4/diagrams/eventstorming/design-level/Service_Execution_Monitoring.png)

  * **Dashboard Analytics**

  ![dashboard_&_analytics](assets/images/cap4/diagrams/eventstorming/design-level/Dashboard_Analytics.png)

  * **Loyalty Engagement**

  ![loyalty_&_engagement](assets/images/cap4/diagrams/eventstorming/design-level/Loyalty_Engagement.png)

  * **System Administration**

  ![system_administration](assets/images/cap4/diagrams/eventstorming/design-level/System_Administration.png)

### 4.6.2. Software Architecture Context Diagram


* Persona:
  * **Transportista:** Conduce el camión y utiliza la aplicación móvil para ver rutas, registrar inicio/finalización de viajes y recibir alertas de impacto.
  * **Distribuidor:** Supervisa los envíos desde oficinas. Revisa el panel web, descarga informes.
  * **Propietario de Negocio:** Cliente final que desea saber si su pedido llegará a tiempo y sin roturas.
  * **Administrador de RPG:** Personal de la startup para gestión interna, soporte y mantenimiento.
* Sistema de Software:
  * **GlassGo:** Sistema central que ofrece trazabilidad, optimización de rutas y monitoreo.
  * **Google Maps:** Plataforma que proporciona una API REST para información geo-referencial.
  * **PayPal:** Pasarela de pago para cargos de membresía.
  * **Twilio:** Servicio de notificaciones para enviar SMS, correos electrónicos o notificaciones push.

![context-diagram](assets/images/cap4/domain-driven-software-arquitecture/context-diagram.png)

### 4.6.3. Diagramas de Contenedor de Arquitectura de Software

* Contenedor:
  * **Aplicación Móvil:** Aplicación para dispositivos móviles
  * **Página de Aterrizaje:** Página de inicio
  * **Aplicación Web:** Aplicación para gestión y seguimiento
  * **API REST:** API REST para acceso a datos y lógica de negocio
  * **DB:** Base de datos relacional

![container-diagram](assets/images/cap4/domain-driven-software-arquitecture/container-diagram.png)


### 4.6.4. Software Architecture Components Diagrams

* **Web Application Component Diagram:**
  ![component-diagram1](assets/images/cap4/domain-driven-software-arquitecture/component-diagram1.png)

* **Web Application Component Diagram:**
  ![component-diagram2](assets/images/cap4/domain-driven-software-arquitecture/component-diagram2.png)

* **Profile Preferences Component Diagram:**
  ![component-diagram3](assets/images/cap4/domain-driven-software-arquitecture/component-diagram3.png)

* **Payments Subscriptions Component Diagram:**
  ![component-diagram4](assets/images/cap4/domain-driven-software-arquitecture/component-diagram4.png)

* **Service Planning Component Diagram:**
  ![component-diagram5](assets/images/cap4/domain-driven-software-arquitecture/component-diagram5.png)

* **Service Execution Component Diagram:**
  ![component-diagram6](assets/images/cap4/domain-driven-software-arquitecture/component-diagram6.png)

* **Dashboard Analytics Component Diagram:**
  ![component-diagram7](assets/images/cap4/domain-driven-software-arquitecture/component-diagram7.png)

* **Loyalty Engagement Component Diagram:**
  ![component-diagram8](assets/images/cap4/domain-driven-software-arquitecture/component-diagram8.png)

* **System Administration Component Diagram:**
  ![component-diagram9](assets/images/cap4/domain-driven-software-arquitecture/component-diagram9.png)


## 4.7. Software Object-Oriented Design

El Diseño Orientado a Objetos se centra en la estructura lógica del dominio de GlassGo, utilizando diagramas de clases UML para definir entidades, servicios y sus relaciones. Cada diagrama representa cómo interactúan las clases dentro de un contexto delimitado, encapsulando atributos y métodos coherentes con sus responsabilidades.

### 4.7.1. Class Diagrams


**Vistas Específicas por Bounded Context**

  
  * **Identity Access Class Diagram:**

    ![class-diagram1](assets/images/cap4/software-object-oriented-design/class-diagram1.png)
  
  * **Profile Preferences Class Diagram:**

    ![class-diagram2](assets/images/cap4/software-object-oriented-design/class-diagram2.png)
  
  * **Payment Subscription Class Diagram:**

    ![class-diagram3](assets/images/cap4/software-object-oriented-design/class-diagram3.png)

  * **Service Planning Class Diagram:**

    ![class-diagram4](assets/images/cap4/software-object-oriented-design/class-diagram4.png)
  
  * **Service Execution Monitoring Class Diagram:**

    ![class-diagram5](assets/images/cap4/software-object-oriented-design/class-diagram5.png)

  * **Dashboard Analytics Class Diagram:**

    ![class-diagram6](assets/images/cap4/software-object-oriented-design/class-diagram6.png)

  * **Loyalty Engagement Class Diagram:**

    ![class-diagram7](assets/images/cap4/software-object-oriented-design/class-diagram7.png)

  * **System Administration Class Diagram:**

    ![class-diagram8](assets/images/cap4/software-object-oriented-design/class-diagram8.png)


## 4.8. Database Design


El diseño de la base de datos define la estructura relacional utilizada por el sistema GlassGo para garantizar la persistencia e integridad de los datos en todos los contextos delimitados.

### 4.8.1. Database Diagrams

* **Global View:**
  ![global-view](assets/images/cap4/diagrams/database/GlassGoDataBaseDiagram.png)

* **Vistas Específicas por Bounded Context**

  * **Identity Access Database Diagram:**

    ![database-diagram1](assets/images/cap4/diagrams/database/Identity_Access_DataBase_Diagram.png)
  
  * **Profile Preferences Database Diagram:**

    ![database-diagram2](assets/images/cap4/diagrams/database/Profile_Preferences_DataBase_Diagram.png)

  * **Payment Subscriptions Database Diagram:**

    ![database-diagram3](assets/images/cap4/diagrams/database/Payments_Subscriptions_DataBase_Diagram.png)
  
  * **Service Planning Database Diagram:**

    ![database-diagram4](assets/images/cap4/diagrams/database/Service_Planning_DataBase_Diagram.png)

  * **Service Execution Monitoring Database Diagram:**

    ![database-diagram5](assets/images/cap4/diagrams/database/Service_Execution_Monitoring_DataBase_Diagram.png)

  * **Dashboard Analytics Database Diagram:**

    ![database-diagram6](assets/images/cap4/diagrams/database/Dashboard_Analytics_DataBase_Diagram.png)

  * **Loyalty Engagement Database Diagram:**

    ![database-diagram7](assets/images/cap4/diagrams/database/Loyalty_Engagement_DataBase_Diagram.png)

  * **System Administration Database Diagram:**

    ![database-diagram8](assets/images/cap4/diagrams/database/System_Administration_DataBase_Diagram.png)
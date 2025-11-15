**UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**

<img src="assets/images/logo-upc.png" alt="Logo UPC" style="width: 150px; height: auto;" />

**UPC \- Ingenieria \- Ingenieria de Software \- 202520**

1ASI0729 \- Desarrollo de Aplicaciones Open Source

**NRC:**  
7327

**DOCENTE:**  
**Angel Augusto Velasquez Nuñez**

**Informe de Trabajo Final**

GRUPO RPG2.0

**GlassGo**

| Código | Apellidos | Nombres |
| :---- | :---- | :---- |
| U202222275 | Howard Robles | Guillermo Arturo |
| U202414424 | Vivar Cesar | David Ignacio |
| U202211881 | Guillen Giraldo | Myke Dylan |
| U202318588 | Céspedes Pillco | Jarod Jack |

**2025-2**  
**Registro de Versiones del Informe**

| Versión | Fecha | Autor | Descripción de modificación |
| :---: | ----- | ----- | ----- |
| tb1 | 18/09/2025 | Guillermo Arturo Howard Robles | Desarrollo de las secciones 2.1, 2.2, y aporte en el capítulo IV. |
|  | 18/09/2025 | David Ignacio Vivar Cesar | Desarrollo de las secciones 2.2.2, 2.3 y realización del capítulo 3\. |
|  | 18/09/2025 | Mike Dylan Guillen Giraldo | Desarrollo de las secciones 4.3 al 4.6 (diseño UX/UI de la página) y aporte en el 1.1 al 1.2.2. |
| tp | 09/10/25 | Guillermo Arturo Howard Robles | Desarrollo de la secciones de entrevistas, 3.2 empathy mapping, 2.3 correcciones según retroalimentación |
|  | 09/10/25 | David Ignacio Vivar Cesar | Corrección en los capítulos 2 y 3 |
|  | 09/10/25 | Mike Dylan Guillen Giraldo | Actualización de las secciones del Capítulo 1 y 4 |
| tb2 | 14/11/25 | Guillermo Arturo Howard Robles |  |
|  | 14/11/25 | David Ignacio Vivar Cesar |  |
|  | 14/11/25 | Mike Dylan Guillen Giraldo |  |
|  | 14/11/25 | Céspedes Pillco Jarod Jack  |  |
| tf |  | Guillermo Arturo Howard Robles |  |
|  |  | David Ignacio Vivar Cesar |  |
|  |  | Mike Dylan Guillen Giraldo |  |
|  |  | Céspedes Pillco Jarod Jack  |  |

**Project Report Collaboration Insights**  
Link Github: 

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3\.

| Sprint \# | Sprint 3 |
| ----- | ----- |
| Sprint Planning Background |  |
| Date | 2025-11-13 |
| Time | 08:00 pm (GMT-5) |
| Location | Modalidad remota mediante la plataforma Discord |
| Prepared By | Howard Robles, Guillermo Arturo |
| Attendees (to planning meeting) |  |
| Sprint 2 Review Summary |  |
| Sprint 2 Retrospective Summary | Durante el Sprint 1, el equipo logró avanzar de forma coordinada y efectiva en el desarrollo de la landing page, sin enfrentar mayores dificultades. Cada integrante cumplió puntualmente con las secciones asignadas, lo que permitió avanzar según lo planificado. La adopción de convenciones comunes en el código y el diseño contribuyó a mantener la coherencia del producto y facilitó la integración entre partes. Como mejora para el siguiente sprint, se acordó implementar revisiones diarias (daily reviews) que permitan alinear mejor los avances, detectar bloqueos tempranos y mejorar la comunicación continua entre miembros. |
| Sprint Goal & User Stories |  |
| Sprint 3 Goal | Nuestro enfoque está en entregar la primera versión funcional del backend de GlassGo, permitiendo gestionar usuarios, pedidos, rutas y notificaciones, así como exponer APIs seguras para el consumo del frontend. Creemos que esto habilita la operación centralizada y confiable de la plataforma, facilitando la integración y el flujo de información entre todos los actores de la cadena logística. Esto se confirmará cuando el frontend pueda consumir los servicios principales, los datos se almacenen y consulten correctamente, y los usuarios reporten que las funcionalidades clave están disponibles y operativas. |
| Sprint 3 Velocity | 50 |
| Sum of Story Points | 47 |

#### 5.2.3.2. Aspect Leaders and Collaborators.

Durante el Sprint 3, se ha definido el desarrollo e integración de los módulos principales del frontend de la aplicación web interna Restock y del backend, abarcando funcionalidades clave como la gestión de productos, pedidos, inventario y compras. Estas implementaciones buscan optimizar los procesos internos y mejorar la trazabilidad del inventario, brindando mayor eficiencia a los repartidores y dueños de negocios.

| Team Member (Last Name, First Name) | GitHub Username | Profile & References  | Paymets & Subscriptions  | Loyalty & Engagerment  | Service Planning  | System Administration  | Service Execution & Monitoring | Dashboard & Analytics |
| ----- | ----- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Howard Robles Guillermo Arturo | GuillermoPromac | C | C | C | C | C | L | L |
| Cespedes Pillco Jarod Jack | PruebaJJC | C | L | C | C | C | C | C |
| Vivar Cesar David Ignacio | DarkBeider20 | C | C | L | C | L | C | C |
| Guillen Giraldo Mike Dylan | FulLHous | L | C | C | L | C | C | C |

#### 5.2.3.3. Sprint Backlog 3\.

El objetivo principal de este Sprint es consolidar una experiencia funcional completa para los distintos perfiles de usuario dentro de la plataforma GlassGo. Se prioriza la mejora de la landing page para comunicar eficazmente la propuesta de valor a nuevos visitantes, así como la habilitación de módulos clave como la gestión de ventas, recetas y pedidos para los administradores de restaurantes, y la gestión de órdenes para los proveedores.

![cap5](/assets/images/cap5/Trello3.png)

Trello: [https://trello.com/invite/b/69000c76fa893622d701697c/ATTI60bf0022730e8c5c23ff3f754d43e9b185AF029B/sprint-backlog-32](https://trello.com/invite/b/69000c76fa893622d701697c/ATTI60bf0022730e8c5c23ff3f754d43e9b185AF029B/sprint-backlog-32) 

#### 5.2.3.4. Development Evidence for Sprint Review.

Web Services (Backend):

| Repository | Branch | Author | Commit Id | Commit Message |
| ----- | ----- | ----- | ----- | ----- |
| feature/service-planning | developer | PruebaJJC | 4e6e88e | feat(shared): add auditable abstract aggregate root base class. |
| feature/service-planning | developer | PruebaJJC | c218bfb | feat(shared): introduce auditable base model for entity tracking. |
| feature/service-planning | developer | PruebaJJC | 4d68641 | feat(naming-convention): implement custom physical naming strategy with snake case and pluralized table names. |
| feature/service-planning | developer | PruebaJJC | a3e8e7b | feat(api): add message resource record to represent message payloads. |
| feature/service-planning | developer | PruebaJJC | c99c5fb | feat(api): add global exception handler for rest api error handling. |
| feature/service-planning | developer | PruebaJJC | 356d14e | feat(open-api-docs): add open-api configuration for api documentation setup. |
| feature/service-planning | developer | PruebaJJC | f54047a | feat(shared): merge shared bounded context.  |
| feature/service-planning | developer | PruebaJJC | 5ff5bf3 | feat(domain): add assignment aggregate for service planning. |
|  |  |  |  |  |

#### 5.2.3.5. Execution Evidence for Sprint Review.

xxxx

#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

xxxx

#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

xxxx

#### 5.2.3.8. Team Collaboration Insights during Sprint.

Seguimos usando ramas específicas para cada sección o funcionalidad (feature/\[nombre-de-seccion\]), permitiendo un trabajo paralelo organizado.

Cada miembro del equipo asumió la responsabilidad de desarrollar una o más boundeds del Backend. Se realizaron commits frecuentes, registrando avances de manera continua y detallada.

### 5.2.1. Sprint 1

#### *5.2.1.1. Sprint Planning 1*

Para el desarrollo del primer sprint nos centramos en el desarrollo de la landing page de nuestra aplicación. Para ello designamos tareas específicas para cada sección, de modo que podamos repartirnos estas tareas entre los integrantes del grupo por sección de la landing, agilizando su desarrollo. Dentro de la landing se presenta quienes somos, funcionalidades, planes, manera de contactarnos y sobre la organización.

| **Sprint #** | 1                                                                                                                                                                                                                                        |
| --- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                                                                          |
| **Date** | 2026-09-10                                                                                                                                                                                                                               |
| **Time** | 4:00 PM                                                                                                                                                                                                                                  |
| **Location** | Reunión virtual                                                                                                                                                                                                                          |
| **Prepared By** | Giancarlo Verastigue Martinez                                                                                                                                                                                                            |
| **Attendees** | Giancarlo Verastigue Martinez, Matias Carrillo Acho, Valeria Milagros Ysidro Llashag, Manuel Alejandro Molina Vasquez, Alison Ariana Segura Guerra                                                                                                                                                                     |
| **Sprint n – 1 Review Summary** | N/A (Primer Sprint del proyecto. Se establecieron las bases de la arquitectura, infraestructura en la nube y repositorios).                                                                                                              |
| **Sprint n – 1 Retrospective Summary** | N/A (Primer Sprint. El equipo acordó usar GitFlow y Conventional Commits rigurosamente desde el primer día).                                                                                                                             |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                                          |
| **Sprint 1 Goal** | Our focus is on delivering a fast, static Landing Page (HTML/CSS/JS) with language support to attract clients and validate our value proposition. This will be confirmed when the Landing Page is deployed and fully navigable by users. |
| **Sprint 1 Velocity** | 10 Story Points (Velocidad estimada para el primer ciclo del equipo).                                                                                                                                                                    |
| **Sum of Story Points** | 10                                                                                                                                                                                                                                       |

#### *5.2.1.2. Aspect Leaders and Collaborators*

A continuación se detalla la matriz de liderazgo y colaboración (LACX) para brindar claridad en la comunicación del equipo durante el desarrollo de las tareas de este Sprint.

| Team Member (Last Name, First Name) | GitHub Username | Landing Page UI/UX | Landing Page Structure | Basic Funcs | Special Funcs |
|-------------------------------------|-----------------| --- | --- | --- | --- |
| Verastigue Martinez, Giancarlo      | @CaLoVM         | C | L | C | C |
| Carrillo Acho, Matias               | @lonybreux      | C | C | C | L |
| Ysidro Llashag, Valeria Milagros         | @vysidrol      | C | C | L | C |
| Molina Vasquez, Manuel Alejandro    | @AleDusty       | C | C | L | C |
| Segura Guerra, Alison Ariana     | @Nox010111  | L | C | C | C |

#### *5.2.1.3. Sprint Backlog 1*


El objetivo principal de este Sprint es desarrollar el sitio web estático (Landing Page) de TourMate, encargado de comunicar la propuesta de valor de la plataforma a los dos segmentos objetivo: turistas y agencias. Durante este Sprint se implementarán las secciones de contenido principal, navegación, beneficios diferenciados por segmento, funcionalidades del producto, testimonios, información del equipo y el formulario de contacto, además de los flujos de acceso al registro y el manejo de estados de error/no disponibilidad definidos en las User Stories asociadas a EP06.

**Trello link:** [https://trello.com/b/gCKcMjVR/tourmate-sprint-1](https://trello.com/b/gCKcMjVR/tourmate-sprint-1)

![Sprint Backlog 1](../assets/images/s1-sprint-backlog.png)
## Sprint 1

| User Story Id | User Story Title | Work-Item / Task Id | Work-Item / Task Title | Description                                                                                    | Estimation (Hours) | Assigned To | Status |
| --- | --- |---------------------| --- |------------------------------------------------------------------------------------------------| --- | --- |--------|
| US-LP01 | Conocer la propuesta de valor | TS-LP01.1           | Setup base del proyecto Landing | Inicializar el repositorio con la estructura base HTML5/CSS para la Landing Page.              | 2 | @lonybreux | Done   |
| US-LP01 | Conocer la propuesta de valor | TS-LP01.2           | Implementar Hero Section | Desarrollar la sección principal con el propósito y beneficio central de TourMate.             | 4 | @lonybreux | Done  |
| US-LP02 | Navegar entre secciones | TS-LP02.1           | Implementar Navbar | Crear el componente de navegación con enlaces a cada sección de la Landing.                    | 2 | @vysidrol | Done  |
| US-LP03 | Conocer beneficios para turistas | TS-LP03.1           | Diseñar sección de beneficios – Turista | Maquetar la sección con los beneficios orientados al segmento turista.                         | 3 | @Nox010111 | Done  |
| US-LP03 | Conocer beneficios para turistas | TS-LP03.2           | Contenido de seguridad y navegación offline | Redactar e integrar el contenido sobre funcionalidades de seguridad y modo offline.            | 2 | @lonybreux | Done  |
| US-LP03 | Conocer beneficios para turistas | TS-LP03.3           | CTA de registro – Turista | Implementar botón que redirige al proceso de registro del segmento turista.                    | 1 | @CaLoVM | Done  |
| US-LP04 | Conocer beneficios para agencias | TS-LP04.1           | Diseñar sección de beneficios – Agencia | Maquetar la sección con los beneficios orientados al segmento agencia.                         | 3 | @vysidrol | Done  |
| US-LP04 | Conocer beneficios para agencias | TS-LP04.2           | Contenido de monitoreo, alertas y gestión | Redactar e integrar el contenido sobre funcionalidades de monitoreo y gestión de expediciones. | 2 | @vysidrol | Done  |
| US-LP04 | Conocer beneficios para agencias | TS-LP04.3           | CTA de registro – Agencia | Implementar botón que redirige al proceso de registro del segmento agencia.                    | 1 | @AleDusty | Done  |
| US-LP05 | Conocer las funcionalidades principales | TS-LP05.1           | Sección de funcionalidades principales | Desarrollar grid/cards con las funcionalidades clave de TourMate.                              | 3 | @AleDusty | Done  |
| US-LP05 | Conocer las funcionalidades principales | TS-LP05.2           | Contenido de operatividad offline | Integrar contenido claro sobre la compatibilidad y uso sin conexión.                           | 2 | @Nox010111 | Done  |
| US-LP08 | Contactar al equipo de Tourmate | TS-LP08.1           | Formulario de contacto | Maquetar el formulario de contacto con los campos requeridos.                                  | 3 | @vysidrol | Done  |
| US-LP08 | Contactar al equipo de Tourmate | TS-LP08.2           | Endpoint de envío de mensaje | Implementar el servicio que registra el mensaje y retorna confirmación de recepción.           | 4 | @Nox010111 | Done  |
| US-LP09 | Conocer al equipo de la startup | TS-LP09.1           | Sección "Sobre el equipo" | Maquetar la sección con la información de los miembros de Axiom.                               | 2 | @CaLoVM | Done  |

#### *5.2.1.4. Development Evidence for Sprint Review*

En la siguiente tabla se resumen los principales commits realizados en los repositorios de Axiom correspondientes al alcance del primer Sprint, aplicando Conventional Commits.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| axiom/tourmate-landing | main | 76bcf2e | fix: update font families and improve section structure in index.html and styles.css | Actualiza las fuentes tipográficas y mejora la estructura de secciones en index.html y styles.css. | 2026-09-20 |
| axiom/tourmate-landing | main | a23d975 | fix(i18n): correct spelling and punctuation in translation files | Corrige errores de ortografía y puntuación en los archivos de traducción. | 2026-09-20 |
| axiom/tourmate-landing | develop | 9811fb3 | Merge branch 'main'  into develop | Integra los cambios de la rama main del repositorio remoto hacia develop. | 2026-09-20 |
| axiom/tourmate-landing | develop | b245be9 | Merge branch 'feature/vision-section' into develop | Integra la rama de la sección de visión en la rama develop. | 2026-09-20 |
| axiom/tourmate-landing | feature/vision-section | 014de80 | feat(vision): add vision section with responsive design and styling | Añade la sección de visión con diseño adaptativo y estilos. | 2026-09-20 |
| axiom/tourmate-landing | main | 42529af | Update visitor.js | Actualiza el archivo visitor.js. | 2026-09-20 |
| axiom/tourmate-landing | main | 83e13b1 | Update visitor.js | Actualiza el archivo visitor.js. | 2026-09-20 |
| axiom/tourmate-landing | main | be68dc6 | Update visitor.js | Actualiza el archivo visitor.js. | 2026-09-20 |
| axiom/tourmate-landing | main | 736eb84 | Update main.js | Actualiza el archivo main.js. | 2026-09-20 |
| axiom/tourmate-landing | main | 6406282 | Update main.js | Actualiza el archivo main.js. | 2026-09-20 |
| axiom/tourmate-landing | main | 6e86319 | Update main.js | Actualiza el archivo main.js. | 2026-09-20 |
| axiom/tourmate-landing | main | daa7af6 | Merge pull request #1 from axiom-apps-web/develop | Integra el pull request #1 desde la rama develop. | 2026-09-19 |
| axiom/tourmate-landing | feature/i18n | b092f7c | feat(i18n): update language switching funcionality | Actualiza la funcionalidad de cambio de idioma. | 2026-09-19 |
| axiom/tourmate-landing | feature/i18n | 999267c | feat(i18n): add Spanish team translations | Añade las traducciones al español para la sección del equipo. | 2026-09-19 |
| axiom/tourmate-landing | feature/i18n | 76214cb | feat(i18n): add English team translations | Añade las traducciones al inglés para la sección del equipo. | 2026-09-19 |
| axiom/tourmate-landing | feature/inicio-section | cb864bf | feat: add inicio section | Implementa la sección de inicio. | 2026-09-19 |
| axiom/tourmate-landing | main | 71caea9 | feat(assets): add images | Añade imágenes a los recursos del proyecto. | 2026-09-19 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | 34c2ed9 | feat: add agencias and viajeros section | Implementa las secciones de agencias y viajeros. | 2026-09-19 |
| axiom/tourmate-landing | develop | e5ead30 | Merge branch 'feature/agencias-viajeros-section' into develop | Integra la rama de la sección de agencias y viajeros en develop. | 2026-09-19 |
| axiom/tourmate-landing | feature/vision-section | 05b8c86 | feat: add vision section | Implementa la estructura base de la sección de visión. | 2026-09-19 |
| axiom/tourmate-landing | feature/inicio-section | a3cfdbb | feat(assets): add hero expedition image | Agrega la imagen hero expedition a los recursos del proyecto. | 2026-09-19 |
| axiom/tourmate-landing | feature/i18n | 0f66705 | feat(i18n): add English translations for agencies, travelers, and modal sections | Agrega traducciones al inglés para las secciones de agencias, viajeros y modales. | 2026-09-19 |
| axiom/tourmate-landing | feature/i18n | a9e4d5f | feat(i18n): add Spanish translations for agencies, travelers, and modal sections | Agrega traducciones al español para las secciones de agencias, viajeros y modales. | 2026-09-19 |
| axiom/tourmate-landing | feature/i18n | 3df7e6d | feat(i18n): add unified bilingual support and modal integration | Añade soporte bilingüe unificado e integración de modales. | 2026-09-19 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | cd2cd16 | feat(index): add bilingual sections for agencies and travelers | Añade las secciones bilingües de agencias y viajeros en el index. | 2026-09-19 |
| axiom/tourmate-landing | main | 0210cd0 | feat(assets): implementation of modal B2B | Implementa los recursos visuales para el modal B2B. | 2026-09-19 |
| axiom/tourmate-landing | main | d7bc437 | add .gitignore to exclude default and editor-specific files | Agrega el archivo .gitignore para excluir archivos por defecto y del editor. | 2026-09-19 |
| axiom/tourmate-landing | feature/contact-footer | a5fcae8 | add styles for navbar, footer, and responsive design | Añade estilos para la barra de navegación, el pie de página y diseño responsivo. | 2026-09-19 |
| axiom/tourmate-landing | feature/contact-footer | 5ae9dc4 | add contact and footer sections to index.html | Agrega las secciones de contacto y pie de página en el archivo index.html. | 2026-09-19 |
| axiom/tourmate-landing | main | 289fbe5 | add initial structure | Agrega la estructura inicial del proyecto. | 2026-09-18 |
| axiom/tourmate-landing | main | a1747aa | Initial commit | Commit inicial del repositorio. | 2026-09-09 |

#### *5.2.1.5. Execution Evidence for Sprint Review*

Durante este Sprint, el equipo logró implementar la versión inicial del Landing Page funcional, rápido y estático, incluido el sistema de idiomas.

*Figura  (Landing Page)*
![Landing Page](../assets/images/landing-page-full2.png)

**Landing Page Demonstration Video:** [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDPy8lARpAQRp4FrzFWEwqxAe1KOWcMdKkZwhyLW45DKmo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jmEFH0](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDPy8lARpAQRp4FrzFWEwqxAe1KOWcMdKkZwhyLW45DKmo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jmEFH0)

#### *5.2.1.6. Services Documentation Evidence for Sprint Review*

Durante el Sprint 1 el esfuerzo de desarrollo se enfocó exclusivamente en la creación del sitio web estático promocional (Landing Page), por lo que aún no se han implementado APIs RESTful ni Endpoints backend que requieran ser documentados a través de Swagger/OpenAPI. Esta documentación se estructurará a partir del Sprint 2.

#### *5.2.1.7. Software Deployment Evidence for Sprint Review*

#### Despliegue de la Landing Page
El despliegue de la Landing Page de TourMate se realizó utilizando GitHub Pages, aprovechando sus capacidades para publicar sitios web estáticos directamente desde un repositorio. Este enfoque permitió una implementación sencilla, automatizada y accesible sin necesidad de servicios externos adicionales.

#### Infraestructura de Despliegue

- **Repositorio de código fuente:** GitHub
- **Plataforma de despliegue:** GitHub Pages
- **Tipo de aplicación:** Landing Page estática (HTML, CSS, JavaScript)
- **Acceso:** URL pública generada por GitHub

#### Proceso de Despliegue

1. **Creación del repositorio**
    - Se creó un repositorio en GitHub que contiene todos los archivos de la Landing Page (HTML, CSS, imágenes y scripts).
    - Se organizó el proyecto asegurando que el archivo principal sea `index.html`, requerido por GitHub Pages.

   ![Deployment](../assets/images/Deployment-Create-Repository.png)

2. **Subida del código**
    - Se realizó el `push` del proyecto a la rama principal (`main`) del repositorio.
    - Se verificó que todos los recursos estén correctamente enlazados (rutas relativas).

   ![Deployment](../assets/images/Deployment-Push.png)

3. **Configuración de GitHub Pages**
    - En la sección *Settings* del repositorio, se habilitó **GitHub Pages**.
    - Se seleccionó la rama `main` como fuente de despliegue.
    - Se definió la carpeta raíz (`/root`) como directorio de publicación.

   ![Deployment](../assets/images/Deployment-GHPages.png)

4. **Publicación automática**
    - GitHub Pages procesó automáticamente el contenido del repositorio.
    - En pocos minutos, generó una URL pública donde la Landing Page quedó disponible.

   ![Deployment](../assets/images/Deployment-URL.png)

5. **Actualizaciones**
    - Cada vez que se realiza un nuevo `push` a la rama `main`, GitHub Pages actualiza automáticamente la página.
    - Esto permite mantener la Landing Page sincronizada con los cambios del repositorio sin intervención manual adicional.

#### Resultado
La Landing Page de TourMate fue desplegada exitosamente mediante GitHub Pages, permitiendo su acceso público a través de una URL estable. Esto facilita la presentación del producto a usuarios potenciales y valida la propuesta de valor del sistema de manera rápida y efectiva.

URL: [https://axiom-apps-web.github.io/tourmate-landing/](https://axiom-apps-web.github.io/tourmate-landing/)

#### *5.2.1.8. Team Collaboration Insights during Sprint*

Todos los miembros del equipo han participado activamente en la implementación de los productos del Sprint 1, lo cual se evidencia mediante los reportes de actividad y contribución del repositorio de GitHub de la organización Axiom.

**Insights**
![Team Insights Sprint 1](../assets/images/insights-landing3.png)

**Contributors**
![Team Insights Sprint 1](../assets/images/contribuciones-landing3.png)

**Network graph**
![Team Insights Sprint 1](../assets/images/gitflow-sprint1-3.png)

### 5.2.2. Sprint 2

#### *5.2.2.1. Sprint Planning 2*
Para el desarrollo del segundo sprint, nos centraremos en la implementación del frontend de nuestra aplicación web. Hemos diseñado tareas específicas basadas en las historias de usuario orientadas a la gestión de tours, el monitoreo en tiempo real, el soporte de rutas offline y la configuración de perfiles. Al subdividir cada historia de usuario en múltiples tareas técnicas, podemos distribuir la carga de trabajo de manera eficiente entre los desarrolladores del equipo, asegurando la construcción de una interfaz interactiva, escalable y lista para integrarse con nuestra API.

| **Sprint #** | 2 |
| --- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** | |
| **Date** | 2026-09-28 |
| **Time** | 4:00 PM |
| **Location** | Reunión virtual |
| **Prepared By** | Giancarlo Verastigue Martinez |
| **Attendees** | Giancarlo Verastigue Martinez, Matias Carrillo Acho, Segura Guerra, Alison Ariana, Manuel Alejandro Molina Vasquez, Ysidro Llashag, Valeria Milagros |
| **Sprint n – 1 Review Summary** | La Landing Page fue completada y desplegada exitosamente. Se lograron los objetivos de comunicar la propuesta de valor y habilitar las rutas de redirección hacia el registro para turistas y agencias. |
| **Sprint n – 1 Retrospective Summary** | El equipo mantuvo una buena comunicación y uso de GitFlow. Se acordó mejorar la granularidad de las estimaciones dividiendo obligatoriamente cada Historia de Usuario en al menos dos tareas (Tasks) para un seguimiento más preciso. |
| **Sprint Goal & User Stories** | |
| **Sprint 2 Goal** | Our focus is on delivering the core frontend application for TourMate, including tour management, interactive live maps, offline capabilities, and user profiles. This will be confirmed when all UI components are built and functional mockups are ready. |
| **Sprint 2 Velocity** | 133 Story Points (Velocidad estimada sumando la carga completa de las vistas e integraciones Frontend proyectadas para este ciclo). |
| **Sum of Story Points** | 133 |

#### *5.2.2.2. Aspect Leaders and Collaborators*

A continuación se detalla la matriz de liderazgo y colaboración (LACX) para brindar claridad en la comunicación del equipo durante el desarrollo de las tareas de este Sprint.

Para este segundo sprint, los aspectos se han definido en base a los módulos principales del Frontend: Gestión de Tours (Tour Management), Mapas y Monitoreo (Maps & Tracking), Capacidades Offline (Offline & Sync), y Perfiles y Alertas (Profile & Alerts).

| Team Member (Last Name, First Name) | GitHub Username | Tour Management Views | Maps & Tracking UI | Offline & Sync Modules | Profile & Alerts Settings |
|-------------------------------------|-----------------| --- | --- | --- | --- |
| Verastigue Martinez, Giancarlo      | @CaLoVM         | C | C | C | L |
| Carrillo Acho, Matias               | @lonybreux      | C | L | C | C |
| Ysidro Llashag, Valeria Milagros        | @vysidrol      | L | C | C | C |
| Molina Vasquez, Manuel Alejandro    | @AleDusty       | L | C | C | C |
| Segura Guerra Alison Ariana      | @Nox010111  | C | C | L | C |

#### *5.2.2.3. Sprint Backlog 2*




**Trello link:** [https://trello.com/b/5MJg6UUc](https://trello.com/b/5MJg6UUc)

![Sprint Backlog 2](../assets/images/s2-sprint-backlog.png)


| User Story Id | User Story Title | Work-Item / Task Id | Work-Item / Task Title | Description | Estimation (Hours) | Assigned To | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| US09 | Crear tour | TS-F09.1 | Maquetar formulario de creación | Desarrollar la interfaz (UI) del formulario con campos estructurados para crear un tour. | 4 | @lonybreux | To Do |
| US09 | Crear tour | TS-F09.2 | Integración y validaciones (Crear Tour) | Implementar validaciones en el cliente y enviar el payload al endpoint correspondiente. | 3 | @CaLoVM | To Do |
| US10 | Editar tour | TS-F10.1 | Interfaz de edición de tour | Reutilizar el componente de formulario y adaptarlo para pre-poblar los datos del tour existente. | 2 | @AleDusty | To Do |
| US10 | Editar tour | TS-F10.2 | Lógica de actualización (Editar Tour) | Capturar los cambios del formulario y enviarlos a la API para confirmar la actualización. | 2 | @vysidrol | To Do |
| US11 | Eliminar tour | TS-F11.1 | Modal de confirmación de eliminación | Diseñar e implementar el cuadro de diálogo para evitar eliminaciones accidentales. | 1 | @Nox010111 | To Do |
| US11 | Eliminar tour | TS-F11.2 | Integración de eliminación | Conectar la acción del modal con el endpoint DELETE y actualizar el listado de la UI localmente. | 2 | @lonybreux | To Do |
| US12 | Duplicar tour | TS-F12.1 | Acción de duplicar en listado | Agregar la opción visual de duplicado en el menú de acciones de la tarjeta/tabla de tour. | 1 | @CaLoVM | To Do |
| US12 | Duplicar tour | TS-F12.2 | Lógica de duplicación | Consumir el endpoint de clonación y redirigir al usuario al nuevo tour en estado borrador. | 3 | @AleDusty | To Do |
| US13 | Asignar turistas a un tour | TS-F13.1 | Buscador y selector de turistas | Construir el componente UI que permite buscar turistas registrados y seleccionarlos. | 3 | @vysidrol | To Do |
| US13 | Asignar turistas a un tour | TS-F13.2 | Envío de asignación a API | Vincular la lista seleccionada con la API de gestión para actualizar los participantes del tour. | 2 | @Nox010111 | To Do |
| US14 | Desasignar turista de un tour | TS-F14.1 | Botón de remoción en tabla de participantes | Añadir la opción gráfica para quitar a un turista de la lista del tour activo. | 1 | @lonybreux | To Do |
| US14 | Desasignar turista de un tour | TS-F14.2 | Lógica de desasignación | Enviar la solicitud de remoción a la API y refrescar la tabla de la interfaz. | 2 | @CaLoVM | To Do |
| US15 | Confirmar asistencia | TS-F15.1 | Vista de tours asignados al turista | Diseñar la pantalla donde el turista visualiza sus invitaciones pendientes con botones de acción. | 3 | @AleDusty | To Do |
| US15 | Confirmar asistencia | TS-F15.2 | Integración de confirmación/cancelación | Conectar las acciones de aceptar/rechazar con los estados en el backend. | 2 | @vysidrol | To Do |
| US16 | Buscar y filtrar tours | TS-F16.1 | Barra de búsqueda y panel de filtros | Desarrollar los inputs reactivos (texto, selects, checkboxes) para la búsqueda de tours. | 4 | @Nox010111 | To Do |
| US16 | Buscar y filtrar tours | TS-F16.2 | Lógica de filtrado en cliente | Manejar el estado del filtro e integrar la llamada a la API con query params. | 4 | @lonybreux | To Do |
| US17 | Consultar detalle del tour | TS-F17.1 | Maquetación de página de detalles | Diseñar la estructura visual completa (ruta, checkpoints, descripción) del tour. | 3 | @CaLoVM | To Do |
| US17 | Consultar detalle del tour | TS-F17.2 | Carga dinámica de información | Consumir los datos del tour específico desde la API y renderizarlos en la vista de detalle. | 2 | @AleDusty | To Do |
| US18 | Consultar tours de la agencia | TS-F18.1 | Grid/Tabla de dashboard de agencia | Crear la vista estructurada para listar todos los tours propios con soporte de paginación UI. | 3 | @vysidrol | To Do |
| US18 | Consultar tours de la agencia | TS-F18.2 | Integración del catálogo | Conectar el grid con el listado de la API y manejar estados de carga y error. | 3 | @Nox010111 | To Do |
| US19 | Iniciar expedición | TS-F19.1 | Vista previa a la expedición | Implementar la pantalla con los detalles y el botón principal "Iniciar Expedición". | 2 | @lonybreux | To Do |
| US19 | Iniciar expedición | TS-F19.2 | Controlador de inicio | Consumir el endpoint de inicio y redirigir automáticamente a la interfaz del mapa en vivo. | 2 | @CaLoVM | To Do |
| US20 | Visualizar ruta del tour | TS-F20.1 | Integración de motor de mapas | Añadir librería de mapas (ej. Leaflet/Mapbox) y configurar vista base en la interfaz. | 4 | @AleDusty | To Do |
| US20 | Visualizar ruta del tour | TS-F20.2 | Renderizado de ruta (Polylines) | Dibujar los trazados del tour sobre el mapa utilizando las coordenadas obtenidas del backend. | 3 | @vysidrol | To Do |
| US21 | Descargar ruta offline | TS-F21.1 | Gestor de caché local | Configurar IndexedDB o Cache API para almacenar la información de rutas y mapas base. | 5 | @Nox010111 | To Do |
| US21 | Descargar ruta offline | TS-F21.2 | Interfaz de gestión de descargas | Crear un panel donde el turista pueda descargar, ver y borrar sus rutas offline. | 4 | @lonybreux | To Do |
| US22 | Visualizar checkpoints del recorrido | TS-F22.1 | Marcadores en mapa interactivo | Desarrollar componentes visuales para colocar los checkpoints sobre la interfaz de mapa. | 3 | @CaLoVM | To Do |
| US22 | Visualizar checkpoints del recorrido | TS-F22.2 | Estilizado dinámico de estado | Cambiar el color/icono del checkpoint en tiempo real según pase de pendiente a completado. | 2 | @AleDusty | To Do |
| US23 | Visualizar progreso del recorrido | TS-F23.1 | Componente de barra de progreso | Diseñar un indicador circular o lineal (progress bar) fijo en la interfaz de expedición. | 2 | @vysidrol | To Do |
| US23 | Visualizar progreso del recorrido | TS-F23.2 | Cálculo reactivo de avance | Actualizar dinámicamente la barra de progreso a medida que el estado global de checkpoints avanza. | 2 | @Nox010111 | To Do |
| US24 | Registrar checkpoint manual | TS-F24.1 | Botón de check-in de guía | Añadir la acción de validación manual accesible desde la tarjeta de detalle de cada checkpoint. | 2 | @lonybreux | To Do |
| US24 | Registrar checkpoint manual | TS-F24.2 | Integración del registro manual | Ejecutar llamada a API y actualizar el estado visual para todo el grupo localmente. | 2 | @CaLoVM | To Do |
| US25 | Registrar experiencia del recorrido | TS-F25.1 | Formulario de notas flotante | Crear un modal de acceso rápido que permita ingresar texto/notas durante la expedición activa. | 2 | @AleDusty | To Do |
| US25 | Registrar experiencia del recorrido | TS-F25.2 | Envío e historial de experiencias | Conectar el formulario al backend y crear una lista UI para que el usuario visualice sus notas. | 2 | @vysidrol | To Do |
| US26 | Consultar clima del recorrido | TS-F26.1 | Widget visual de clima | Maquetar el componente que mostrará iconos climáticos, temperaturas y advertencias. | 3 | @Nox010111 | To Do |
| US26 | Consultar clima del recorrido | TS-F26.2 | Integración de servicio climático | Consumir la API de clima y adaptar los datos para renderizarlos en el widget. | 3 | @lonybreux | To Do |
| US27 | Sincronización asincrónica de datos offline | TS-F27.1 | Listener de estado de red | Implementar lógica para detectar eventos 'online'/'offline' y mostrar alertas al usuario en UI. | 3 | @CaLoVM | To Do |
| US27 | Sincronización asincrónica de datos offline | TS-F27.2 | Cola de peticiones en background | Implementar sistema para encolar acciones localmente y procesarlas al recuperar la conexión. | 6 | @AleDusty | To Do |
| US28 | Finalizar expedición | TS-F28.1 | Componente de finalización | Diseñar botón de "Cerrar Expedición" con modal de doble confirmación para el guía. | 2 | @vysidrol | To Do |
| US28 | Finalizar expedición | TS-F28.2 | Cierre y redirección | Llamar al endpoint de finalización y transicionar la vista a la pantalla de resumen del tour. | 2 | @Nox010111 | To Do |
| US29 | Monitorear ubicación de turistas | TS-F29.1 | Captura de geolocalización | Utilizar Geolocation API en el cliente para emitir coordenadas constantemente a la app. | 4 | @lonybreux | To Do |
| US29 | Monitorear ubicación de turistas | TS-F29.2 | Vista de rastreo en agencia | Mostrar avatares o marcadores de los turistas sobre el mapa del panel de administración en vivo. | 5 | @CaLoVM | To Do |
| US30 | Consultar estado general del grupo | TS-F30.1 | Dashboard de métricas del grupo | Crear un grid con tarjetas de estado simplificadas por cada turista asignado a la expedición. | 4 | @AleDusty | To Do |
| US30 | Consultar estado general del grupo | TS-F30.2 | Lógica de refresco (Polling/Sockets) | Implementar actualizaciones periódicas en el cliente para refrescar los datos del panel en vivo. | 4 | @vysidrol | To Do |
| US31 | Recibir alertas por anomalías | TS-F31.1 | Componente visual de alerta crítica | Diseñar notificaciones intrusivas (banners rojos/modales) para advertir riesgos de seguridad. | 2 | @Nox010111 | To Do |
| US31 | Recibir alertas por anomalías | TS-F31.2 | Procesamiento de eventos anómalos | Escuchar los eventos de alerta generados por la telemetría y disparar el componente de alerta UI. | 4 | @lonybreux | To Do |
| US32 | Consultar estado de salud básico | TS-F32.1 | Tarjetas de biométricos en UI | Maquetar indicadores de frecuencia cardíaca/oxígeno dentro de la lista de turistas del guía. | 2 | @CaLoVM | To Do |
| US32 | Consultar estado de salud básico | TS-F32.2 | Binding de datos de salud | Enlazar el flujo de datos para actualizar los iconos y valores de salud dinámicamente. | 2 | @AleDusty | To Do |
| US33 | Reportar incidente | TS-F33.1 | UI de botón de pánico / SOS | Implementar un formulario de acceso súper rápido desde la vista de turista para emergencias. | 2 | @vysidrol | To Do |
| US33 | Reportar incidente | TS-F33.2 | Envío de incidente y cache offline | Enviar el payload a la API, manejando fallos de red con almacenamiento temporal seguro. | 3 | @Nox010111 | To Do |
| US34 | Reportar incidente desde el rol guía | TS-F34.1 | Panel de gestión de incidentes | Construir la tabla visual para que el guía visualice, edite y cierre reportes en el terreno. | 2 | @lonybreux | To Do |
| US34 | Reportar incidente desde el rol guía | TS-F34.2 | Integración del workflow del incidente | Conectar las acciones (abrir, actualizar notas, marcar como resuelto) a la API REST. | 2 | @CaLoVM | To Do |
| US35 | Recibir datos biométricos del wearable | TS-F35.1 | Integración con Web Bluetooth API | Implementar la clase/servicio en el frontend capaz de descubrir y parear el wearable. | 5 | @AleDusty | To Do |
| US35 | Recibir datos biométricos del wearable | TS-F35.2 | Transmisión de telemetría | Capturar el flujo de datos (stream) del dispositivo, formatear JSON y enviarlo al backend. | 5 | @vysidrol | To Do |
| US36 | Consultar estado del wearable | TS-F36.1 | Icono de batería y conectividad | Maquetar indicadores en la barra superior (navbar/status bar) para el hardware emparejado. | 2 | @Nox010111 | To Do |
| US36 | Consultar estado del wearable | TS-F36.2 | Lógica de refresco de hardware | Interpretar la data básica del reloj/pulsera para pintar dinámicamente su porcentaje y status. | 2 | @lonybreux | To Do |
| US37 | Exportar reportes de expedición | TS-F37.1 | Controles de exportación | Colocar menú con opciones (Descargar PDF, Exportar CSV) en expediciones finalizadas. | 2 | @CaLoVM | To Do |
| US37 | Exportar reportes de expedición | TS-F37.2 | Manejo de descarga de archivos Blob | Consumir el endpoint de exportación, convertir la respuesta y forzar la descarga en el navegador. | 3 | @AleDusty | To Do |
| US38 | Gestionar perfil personal | TS-F38.1 | Maquetación del formulario de perfil | Diseñar la página principal de configuración personal con validación de inputs gráficos. | 2 | @vysidrol | To Do |
| US38 | Gestionar perfil personal | TS-F38.2 | Integración de actualización | Recuperar datos para precargar y enviar el payload del formulario a la API del usuario. | 2 | @Nox010111 | To Do |
| US39 | Actualizar foto de perfil | TS-F39.1 | Componente uploader con previsualización | Desarrollar un drag & drop/file input que renderice localmente la foto seleccionada. | 2 | @lonybreux | To Do |
| US39 | Actualizar foto de perfil | TS-F39.2 | Lógica de subida multipart | Manejar y procesar el envío del archivo como FormData hacia los servidores. | 1 | @CaLoVM | To Do |
| US40 | Configurar preferencias de notificaciones | TS-F40.1 | Vista de 'Switches' (Toggles) | Diseñar los selectores booleanos (on/off) para las distintas categorías de alertas de la cuenta. | 2 | @AleDusty | To Do |
| US40 | Configurar preferencias de notificaciones | TS-F40.2 | Sincronización de preferencias | Conectar los cambios de UI inmediatamente con el backend del usuario para guardado automático. | 2 | @vysidrol | To Do |
| US41 | Recibir notificaciones de seguridad | TS-F41.1 | Layout de notificaciones críticas | Crear plantillas diferenciadas (colores llamativos, iconos de alerta) en el gestor de notificaciones UI. | 3 | @Nox010111 | To Do |
| US41 | Recibir notificaciones de seguridad | TS-F41.2 | Interceptor de sockets/alertas | Suscribir el cliente a los eventos críticos para desplegar el modal sin importar en qué vista esté. | 3 | @lonybreux | To Do |
| US42 | Recibir notificaciones de tour | TS-F42.1 | Dropdown de campana (Notificaciones) | Añadir la "campanita" y su respectiva lista desplegable rápida en la navegación del usuario. | 2 | @CaLoVM | To Do |
| US42 | Recibir notificaciones de tour | TS-F42.2 | Acciones 'Marcar leída' / Polling | Implementar la funcionalidad para descontar el contador rojo y leer desde la API. | 2 | @AleDusty | To Do |
| US43 | Consultar historial de notificaciones | TS-F43.1 | Página dedicada al historial | Maquetar una sección de lista extendida con filtros y ordenación por fecha. | 2 | @vysidrol | To Do |
| US43 | Consultar historial de notificaciones | TS-F43.2 | Integración de listado completo | Consumir la API de notificaciones implementando infinite scroll o paginación estándar. | 2 | @Nox010111 | To Do |

#### *5.2.2.4. Development Evidence for Sprint Review*

En la siguiente tabla evidencia los commits realizados en los repositorios de Axiom correspondientes al alcance del Sprint 2, aplicando Conventional Commits.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| axiom/tourmate-web-application | develop | a37c3c3 | Merge branch 'feature/fix' into develop # Please enter a commit message | Integra la rama de correcciones hacia la rama de desarrollo (develop). | 2026-10-06 |
| axiom/tourmate-web-application | feature/api-endpoints | 560d09c | feat(api-endpoints): update API base URLs for active tours, agencies, checkpoints, incidents, participants, payments, plans, subscriptions, tour guides, tour schedules, and users | Actualiza las URLs base de la API para todos los módulos de gestión principales. | 2026-10-06 |
| axiom/tourmate-web-application | main | 7be53fc | Merge pull request #2 from axiom-daos/feedback-and-tour-reviews2 | Integra el pull request #2 asociado al módulo de reseñas y feedback. | 2026-10-06 |
| axiom/tourmate-web-application | fix/reviews | 82d824f | fix(reviews): fix store delete and create id synchronization issues | Corrige problemas de sincronización de IDs al crear y eliminar elementos en el store de reseñas. | 2026-10-06 |
| axiom/tourmate-web-application | feature/accessibility | cf3a3f3 | feat(accessibility): improve accessibility features across various components | Mejora las características de accesibilidad en múltiples componentes de la aplicación. | 2026-10-06 |
| axiom/tourmate-web-application | feature/review-list | 87aa8ee | feat(review-list): enhance review list with improved UI, translations, and dynamic user/tour information | Mejora la lista de reseñas agregando una interfaz optimizada, traducciones e información dinámica. | 2026-10-06 |
| axiom/tourmate-web-application | feature/active-tour-list | 7eef9ac | feat(active-tour-list): enhance active tour list with responsive card layout and sorting functionality | Mejora la lista de tours activos implementando diseño responsivo de tarjetas y ordenamiento. | 2026-10-05 |
| axiom/tourmate-web-application | feature/active-tour | 88f10a2 | feat(active-tour): enhance active tour form with improved validation and UI elements | Mejora el formulario de tour activo incluyendo validaciones avanzadas y elementos de interfaz. | 2026-10-05 |
| axiom/tourmate-web-application | feature/styles | 67fad92 | feat(styles): add feedback and reviews link in sidebar | Añade enlaces visuales en la barra lateral para la sección de feedback y reseñas. | 2026-10-05 |
| axiom/tourmate-web-application | fix/incident-form | a963a19 | fix(incident-form): dix duplicate import TranslatePipe | Corrige la importación duplicada de TranslatePipe en el formulario de incidentes. | 2026-10-05 |
| axiom/tourmate-web-application | develop | 618dc53 | Merge branch 'feature/desing' into develop | Integra la rama con actualizaciones de diseño general hacia la rama develop. | 2026-10-05 |
| axiom/tourmate-web-application | main | 8f28c87 | Merge pull request #1 from axiom-daos/feedback-and-tour-reviews2 | Integra el pull request #1 relacionado al sistema de retroalimentación de tours. | 2026-10-05 |
| axiom/tourmate-web-application | feature/reviews | 7a1f832 | feat(reviews): implement complete CRUD, i18n support, and UI design parity | Implementa operaciones CRUD completas, soporte de idiomas y paridad de diseño para reseñas. | 2026-10-05 |
| axiom/tourmate-web-application | feature/tour-schedule | b1b9300 | (tour-schedule-list): change font weight to max capacity cell | Modifica el peso de la fuente en la celda de capacidad máxima de la lista de horarios. | 2026-10-05 |
| axiom/tourmate-web-application | feature/tour-list | 877e82e | feat: add tour-list cards grid | Añade una estructura de cuadrícula de tarjetas (grid) para la vista de listado de tours. | 2026-10-05 |
| axiom/tourmate-web-application | feature/feedback | 9f4b701 | Merge remote-tracking branch 'origin/develop' into feedback-and-tour-reviews2 | Sincroniza la rama de reseñas con los últimos cambios remotos de develop. | 2026-10-05 |
| axiom/tourmate-web-application | feature/incident-list | 5a27732 | feat(incident-list): add translation support for incident list component | Implementa soporte de traducciones para el componente de lista de incidentes. | 2026-10-05 |
| axiom/tourmate-web-application | feature/incident-form | 443edeb | feat(incident-form): implement translation for incident form labels and placeholders | Aplica traducciones en las etiquetas y textos temporales del formulario de incidentes. | 2026-10-05 |
| axiom/tourmate-web-application | feature/incident | 73294db | feat(incident): add English and Spanish translations for incident management | Agrega soporte en inglés y español para el gestor de incidentes. | 2026-10-05 |
| axiom/tourmate-web-application | feature/active-tour | b02edb6 | feat(active-tour): redesign active tour list with enhanced UI and new columns for tour title and guide name | Rediseña la lista de tours activos agregando columnas de título y nombre del guía. | 2026-10-05 |
| axiom/tourmate-web-application | feature/active-tour | 19f91be | feat(active-tour): enhance active tour list with tour title and guide name columns | Optimiza las columnas de nombre de guía y título en el registro de tours. | 2026-10-05 |
| axiom/tourmate-web-application | feature/active-tour | 89ae3dc | feat(active-tour): integrate TourGuide entity and update active tour management | Integra la entidad de guía de turismo dentro de la gestión de tours activos. | 2026-10-05 |
| axiom/tourmate-web-application | feature/live-monitoring | 87f06bd | feat(live-monitoring): add navigation to live monitoring and update translations | Añade navegación y actualizaciones de texto al sistema de monitoreo en tiempo real. | 2026-10-05 |
| axiom/tourmate-web-application | feature/reviews | c6bfde0 | feat(reviews): stabilize feedback and tour reviews UI and JSON server integration | Estabiliza la vista de reseñas y su integración de datos con el servidor JSON. | 2026-10-04 |
| axiom/tourmate-web-application | style/reviews | 7fd0fff | style(reviews): align review-form layout and solid dark buttons with team UI standards | Alinea los estilos del formulario de revisión y botones oscuros a los estándares del equipo. | 2026-10-04 |
| axiom/tourmate-web-application | fix/layout | cec70c4 | fix: resolve merge conflicts with develop on layout and include feedback reviews navigation | Resuelve conflictos de integración de diseño en develop y añade la navegación de reseñas. | 2026-10-04 |
| axiom/tourmate-web-application | feature/reviews | 47527cb | feat(reviews): fix mat-table rendering and integrate ReviewStore signals for feedback and tour reviews | Arregla el renderizado de la tabla material e integra señales (signals) de ReviewStore. | 2026-10-04 |
| axiom/tourmate-web-application | feature/tour-list | d0093f2 | add status-tag-inactive in tour-list | Añade la etiqueta visual de estado inactivo dentro del listado de tours. | 2026-10-04 |
| axiom/tourmate-web-application | feature/live-monitoring | 8c84e1f | feat(live-monitoring): implement live monitoring component with participant management and route visualization | Implementa el componente de monitoreo en vivo con visualización de participantes y rutas. | 2026-10-04 |
| axiom/tourmate-web-application | feature/agency | 0c0f5ac | feat(agency): add Agency entity, assembler, and API endpoint for managing agencies | Agrega entidades, adaptadores y rutas de API para administrar el módulo de agencias. | 2026-10-04 |
| axiom/tourmate-web-application | feature/tour-guide | 0434f68 | feat(tour-guide): add TourGuide entity, assembler, and API endpoint for managing tour guides | Implementa la base de datos local y endpoints para administrar los guías turísticos. | 2026-10-04 |
| axiom/tourmate-web-application | feature/environment | cbaee66 | feat(environment, localization): update environment variables and add live monitoring translations for enhanced functionality | Actualiza variables de entorno y añade traducciones del módulo de monitoreo. | 2026-10-04 |
| axiom/tourmate-web-application | feature/app | 53ff216 | feat(app): enhance application shell and localization support for improved user experience | Refuerza la estructura general de la app (app shell) y mejora el manejo de localización. | 2026-10-04 |
| axiom/tourmate-web-application | feature/incident | d675610 | feat(incident): enhance incident form and list UI for improved usability and responsiveness | Optimiza los componentes de formulario y lista de incidentes mejorando usabilidad y adaptabilidad. | 2026-10-04 |
| axiom/tourmate-web-application | feature/tour | 6efac0d | feat(tour): enhance tour form and list UI for improved usability and responsiveness | Optimiza los componentes de interfaz para la gestión general de listado y formularios de tour. | 2026-10-04 |
| axiom/tourmate-web-application | feature/active-tour | 404d7bd | feat(active-tour): redesign active tour form and list for improved usability and responsiveness | Aplica rediseño general a los formularios de administración de tours activos. | 2026-10-04 |
| axiom/tourmate-web-application | feature/core | c59b001 | feat(about, home, not-found): enhance UI components and layout for improved user experience | Añade y mejora las vistas estáticas principales como Home, About y vista de errores 404. | 2026-10-04 |
| axiom/tourmate-web-application | refactor/tour | a00f9f5 | refactor(tour): remove TourSchedule entity and related components for simplification | Simplifica el sistema eliminando la entidad compleja TourSchedule y sus dependencias. | 2026-10-04 |
| axiom/tourmate-web-application | refactor/tour | 8c02bd7 | refactor(tour): update import paths for TourSchedule and streamline tour response structure | Arregla rutas de importación afectadas y optimiza la estructura de respuestas. | 2026-10-04 |
| axiom/tourmate-web-application | refactor/tour | 7a0d396 | refactor(tour): update import paths for TourSchedule and streamline tour response structure | Consolida los ajustes en rutas de importaciones tras la eliminación de módulos previos. | 2026-10-04 |
| axiom/tourmate-web-application | feature/environment | c1efc6f | feat(environment): add new API endpoints for subscriptions, active tours, and payments | Conecta las variables de entorno para manejar llamadas sobre pagos, suscripciones y tours. | 2026-10-04 |
| axiom/tourmate-web-application | refactor/routes | c3c7810 | refactor(routes): update tour monitoring paths for consistency | Estandariza la estructura de rutas (URLs internas) para el área de monitoreo. | 2026-10-04 |
| axiom/tourmate-web-application | feature/tour-monitoring | 4a06b66 | Merge branch 'develop' into feature/tour-monitoring | Actualiza la rama de monitoreo con las bases más recientes provenientes de develop. | 2026-10-04 |
| axiom/tourmate-web-application | develop | 0494a5d | Merge branch 'feature/subscriptions-and-payment-management' into develop | Integra todo el desarrollo de suscripciones y pagos hacia la rama principal de pruebas. | 2026-10-04 |
| axiom/tourmate-web-application | refactor/incident-form | 83cddba | refactor(incident-form): remove unused NgIf import | Limpia el código eliminando importaciones de NgIf sin utilizar en incidentes. | 2026-10-03 |
| axiom/tourmate-web-application | fix/subscription | cfeaf37 | fix(subscription): replace mat-error with error-banner to avoid unnecessary form-field dependency | Cambia el sistema de alertas de error nativo por componentes globales tipo banner. | 2026-10-03 |
| axiom/tourmate-web-application | feature/subscriptions | 1585b1c | Merge branch 'develop' into feature/subscriptions-and-payment-management | Sincroniza la rama de pagos y suscripciones antes de integrarla definitivamente. | 2026-10-03 |
| axiom/tourmate-web-application | feature/layout | 477d197 | feat: add left sidebar with main content | Construye la estructura visual de navegación lateral izquierda (sidebar) para usuarios logueados. | 2026-10-03 |
| axiom/tourmate-web-application | chore/subscription | 5977824 | chore(subscription): clean up unused imports and optimize component declarations | Optimiza y purga el código sin usar en los componentes del módulo de suscripciones. | 2026-10-03 |
| axiom/tourmate-web-application | fix/subscription | b8bd5d9 | fix(subscription): resolve text spacing, horizontal overflow, and footer overlap | Soluciona desbordamientos horizontales de texto y colisiones visuales con el pie de página. | 2026-10-03 |
| axiom/tourmate-web-application | feature/subscription | c2b6db4 | feat(subscription): integrate subscription navigation and i18n translations | Habilita traducciones en múltiples idiomas y enlaces directos para el gestor de suscripciones. | 2026-10-03 |
| axiom/tourmate-web-application | feature/subscription | 095526a | feat(subscription): add subscription dashboard and plan selection views with routing | Añade vistas principales para elegir planes de agencia con su enrutado correspondiente. | 2026-10-03 |
| axiom/tourmate-web-application | feature/subscription | db2856e | feat(subscription): implement SubscriptionStore with Angular signals and state management | Establece un store reactivo usando Angular Signals para controlar los datos de pagos locales. | 2026-10-03 |
| axiom/tourmate-web-application | feature/subscription | 6e43cd7 | feat(subscription): add response contracts, assemblers, endpoints and API facade | Crea interfaces base, mapeadores y la fachada para consumir APIs financieras. | 2026-10-03 |
| axiom/tourmate-web-application | feature/subscription | 92a4fca | feat(subscription): add domain entities and value objects for plans, subscriptions and payments | Modela las entidades de negocio asociadas a los pagos y planes de suscripción. | 2026-10-03 |
| axiom/tourmate-web-application | fix/routes | df60668 | fix(routes): add management deleted route | Restaura una ruta de administración accidentalmente eliminada. | 2026-10-03 |
| axiom/tourmate-web-application | feature/safety | be9671e | Merge branch 'develop' into feature/safety-and-incident-management | Mantiene actualizada la rama de incidentes de seguridad absorbiendo bases de develop. | 2026-10-03 |
| axiom/tourmate-web-application | feature/safety | e8bb0ec | feat(safety): update incident list component with English translations | Incorpora archivos de internacionalización (inglés) a la tabla de reportes de anomalías. | 2026-10-03 |
| axiom/tourmate-web-application | feature/safety | a24bfbf | feat(safety): update incident list component with English translations | Ajustes secundarios de traducciones en el listado de fallos y problemas. | 2026-10-03 |
| axiom/tourmate-web-application | feature/safety | d0c7506 | feat(safety): update incident list component with English translations | Refuerza la cobertura del idioma en toda la grilla de alertas. | 2026-10-03 |
| axiom/tourmate-web-application | feature/safety | e36389f | feat(safety): update incident form component with improved layout and English translations | Repara y traduce los diseños internos del formulario de creación de advertencias. | 2026-10-03 |
| axiom/tourmate-web-application | feature/safety | cdbc4dd | feat(safety): enhance styling and layout for incident form component | Potencia la apariencia gráfica y estructura base de formularios vinculados a la seguridad del tour. | 2026-10-03 |
| axiom/tourmate-web-application | chore | f04ccc8 | chore: stop tracking environment files | Excluye del repositorio en línea los archivos de entorno (variables sensibles). | 2026-10-03 |
| axiom/tourmate-web-application | chore | 65817c7 | update .gitignore | Configura el sistema de exclusiones de git para ignorar binarios y configuraciones locales. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | f7ed4ac | feat: add tour schedule form | Añade el formulario especializado en registrar calendarios de visitas turísticas. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | b4a0d95 | feat: add tour schedule list view | Construye la vista visual para leer los cronogramas registrados. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | acf7063 | feat: add tour schedules http methods in tour-management-store | Expande el store central habilitando lógica de llamadas HTTP hacia calendarios. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | 2b5a2fa | feat: add tour schedules http methods in tour-management-api | Crea la conexión interna para que Angular invoque los endpoints. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | 8a153e7 | feat: add tour schedule api endpoint | Enruta el endpoint consumible hacia el área de cronograma. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | 936ae0e | feat: add tour schedule assembler | Diseña adaptadores (assemblers) que formatean los esquemas recibidos. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | 392d147 | feat: add tour schedule domain model | Modela matemáticamente o define lógicamente cómo interactúan las fechas. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour-schedule | 0885af5 | feat: add tour schedule response | Tipa correctamente las respuestas del servidor orientadas al módulo. | 2026-10-03 |
| axiom/tourmate-web-application | feature/tour | 6c94e6f | feat: add tour form view | Implementa y expone al navegador el formulario base de expediciones y tours genéricos. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | be26205 | feat(safety): simplify routing for safety and incident management | Redirige más fácilmente las URLs a los submódulos de seguridad acortando los paths. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 8e999ef | feat(safety): add routing for incident list and form components | Enlaza los componentes visuales de listar/crear con sus direcciones web internas en Angular. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 662813a | feat(safety): add incident list component with table actions and pagination | Dota a la tabla de anomalías de soporte visual para cambiar de páginas y presionar botones. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | b66820a | feat(safety): add incident list component with table layout and actions | Completa la plantilla principal HTML para visualizar reportes. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 3a34f5f | feat(safety): add CSS styles for incident list layout | Adiciona capas de CSS para dejar limpio y ordenado el diseño tabular. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 646fe82 | feat(safety): implement incident form component for creating and editing incidents | Construye un elemento TS capaz de manejar eventos de creación de avisos manuales. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | b98b880 | feat(safety): add incident management form layout in incident-form.html | Estructura los inputs y contenedores para avisos y pánicos de tour. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 0196b88 | feat(safety): add CSS styles for incident management form layout | Aplica hojas de estilo de manera focalizada para el área de reportes. | 2026-10-02 |
| axiom/tourmate-web-application | fix/safety | 95b33d7 | fix(safety): update default incident status from REPORTED to OPEN | Homologa los valores estándar (modificando reportado por abierto) en la lógica empresarial. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 4d18cb7 | feat(safety): add route for safety and incident management module | Introduce la ruta padre en el proyecto orientada netamente al área de seguridad de campo. | 2026-10-02 |
| axiom/tourmate-web-application | feature/active-tour | 7ead078 | add max capacity column to active tours list | Renderiza una celda con el indicador del aforo o cantidad límite permitida por grupo turístico. | 2026-10-02 |
| axiom/tourmate-web-application | feature/active-tour | c8eb5e6 | add tour schedule association to active tours | Liga o amarra las entidades de tours disponibles a sus fechas y horas establecidas en calendario. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 48a18e6 | feat(safety): implement IncidentStore with Angular signals and state management | Utiliza reactividad moderna de Angular para almacenar temporalmente reportes de anomalías. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 7999ac8 | feat(safety): implement IncidentApi infrastructure facade | Instala el servicio de consumo REST diseñado expresamente para incidentes. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | eadac6b | feat(safety): create IncidentApiEndpoint for REST operations | Conecta el endpoint oficial que recibirá notificaciones y reportes generados. | 2026-10-02 |
| axiom/tourmate-web-application | refactor/safety | 07b51a0 | refactor(safety): implement IncidentAssembler for data mapping | Refina y limpia cómo la data externa se mapea a los modelos del frontend en incidentes. | 2026-10-02 |
| axiom/tourmate-web-application | refactor/safety | fdaeecf | refactor(safety): add incident response and resource contracts | Clarifica mediante contratos (interfaces) qué estructura devuelve el servidor. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 35dc5b9 | feat(safety): implement Incident aggregate root entity | Genera el objeto de negocio principal que regirá sobre eventos y advertencias. | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 8f09151 | feat(safety): add IncidentStatus enumeration | Inserta una enumeración (ENUM) para estandarizar etiquetas (abierto, resuelto, ignorado). | 2026-10-02 |
| axiom/tourmate-web-application | feature/safety | 0d78263 | feat(safety): add IncidentId value object | Configura patrones de diseño implementando ID específicos e inmutables para reportes. | 2026-10-02 |
| axiom/tourmate-web-application | feature/participants | 46d187d | add participants management functionality with CRUD operations | Dota al panel del guía con opciones completas para modificar o remover integrantes del viaje. | 2026-10-02 |
| axiom/tourmate-web-application | feature/participants | 036d469 | add participant entity, assembler, and API endpoint for CRUD operations | Complementa las opciones visuales mapeando toda su respectiva lógica hacia la base de datos externa. | 2026-10-02 |
| axiom/tourmate-web-application | feature/tour | 9c2cd9e | feat: add tour list view | Configura el contenedor general que alberga múltiples expediciones resumidas. | 2026-10-02 |
| axiom/tourmate-web-application | feature/tour-schedule | b27f929 | add tour schedules management functionality with CRUD operations | Incluye vistas funcionales e interactivas de calendarios operativos al administrador. | 2026-10-02 |
| axiom/tourmate-web-application | feature/environment | 104a018 | add tour guides endpoint path to environment configurations | Provee a la aplicación central de la URL adecuada para ubicar empleados. | 2026-10-02 |
| axiom/tourmate-web-application | feature/tour-guide | f51cbc0 | add tour guide management functionality with CRUD operations | Permite a la agencia crear, consultar, modificar y remover guías de su equipo desde el panel. | 2026-10-02 |
| axiom/tourmate-web-application | feature/tour-guide | 83857df | add tour guide entity, assembler, and response definitions | Habilita todo el flujo tipado en Typescript para recibir data de guías con exactitud. | 2026-10-02 |
| axiom/tourmate-web-application | feature/tour | 938779b | feat: add tour-management store with loadTours function | Introduce en memoria global una rutina optimizada para cargar listados asíncronos. | 2026-10-02 |
| axiom/tourmate-web-application | feature/tour | 09042f5 | feat: add tour management api and tours api endpoint | Finaliza el flujo de comunicación vinculando los archivos locales TS a la red de backend. | 2026-10-01 |
| axiom/tourmate-web-application | feature/tour | c5e2257 | feat: add tour-assembler | Acondiciona y formatea el JSON puro enviado por TourMate al modelo local esperado. | 2026-10-01 |
| axiom/tourmate-web-application | feature/tour | ab11ae8 | feat: add tour entity model | Describe propiedades como latitud, nombre, descripción para el modelo principal de ruta. | 2026-10-01 |
| axiom/tourmate-web-application | feature/tour | 8a208d7 | feat: add BaseResource and BaseResponse in tours-response | Implementa clases universales genéricas para que todos los fetch cuenten con metadatos. | 2026-10-01 |
| axiom/tourmate-web-application | feature/tour | 6eaf560 | feat: add tour-response interface | Desarrolla la máscara técnica obligatoria para entender la carga JSON orientada a tours. | 2026-10-01 |
| axiom/tourmate-web-application | chore/db | 6be8f5e | chore(server/db.json): fix tours json structure | Alinea y arregla los objetos estáticos mockeados utilizados en pruebas de red locales. | 2026-10-01 |
| axiom/tourmate-web-application | feature/active-tour | edc07b4 | rename active tours entity and assembler to singular form; update types and routes accordingly | Mejora la convención de nombramiento pasándolo a singular en todo el ecosistema de tours en tránsito. | 2026-10-01 |
| axiom/tourmate-web-application | chore/db | 4ef601d | chore(server/db.json): fix tours and tour_schedules status field | Corrige datos de simulación inválidos reemplazando estados obsoletos en el archivo db.json. | 2026-10-01 |
| axiom/tourmate-web-application | chore/db | decf51c | update user and agency IDs in db.json for consistency and clarity | Asegura que la información de agencias y perfiles simulados guarden relación íntegra entre sí. | 2026-10-01 |
| axiom/tourmate-web-application | feature/active-tour | 560e199 | add active tours entity, assembler, and response definitions | Crea la base estructural TS para diferenciar y manipular expediciones que actualmente están en ruta. | 2026-10-01 |
| axiom/tourmate-web-application | refactor/core | eb07343 | refactor JSON keys for consistency in naming conventions | Reemplaza o modifica nombres de atributos generales (ej. camelCase) para facilitar su mantenimiento. | 2026-10-01 |
| axiom/tourmate-web-application | refactor/core | b33165a | refactor JSON keys for consistency and clarity | Continúa los procesos de limpieza semántica en archivos fuente principales. | 2026-10-01 |
| axiom/tourmate-web-application | feature/core | 4f9460a | add initial project structure with core components, styles, and routing | Configura la cascada de directorios, librerías, y módulos de diseño básicos para iniciar. | 2026-10-01 |
| axiom/tourmate-web-application | main | e3fbdca | initial structure | Crea y registra la versión fundacional del repositorio. | 2026-09-30 |

#### *5.2.2.5. Execution Evidence for Sprint Review*

En este segundo Sprint, el equipo se enfocó de lleno en la construcción y desarrollo del Frontend core de TourMate, logrando consolidar la interfaz de usuario y la interactividad de los módulos principales de la plataforma. Se alcanzó satisfactoriamente el objetivo del Sprint al entregar componentes visuales funcionales, responsivos y estructurados, dejándolos listos para su futura integración con la API REST.

Entre los logros más destacados de este ciclo se encuentra el módulo de Gestión de Tours, donde se implementaron las vistas dinámicas para que las agencias puedan crear, editar, duplicar y administrar recorridos, además de gestionar la asignación de turistas. Asimismo, se avanzó significativamente en el módulo de Mapas y Monitoreo, integrando visores interactivos que permiten renderizar rutas, visualizar checkpoints y proyectar el progreso de la expedición en tiempo real.

*Figura  (Home)*
![Home](../assets/images/home2.png)

*Figura  (Gestion de Tours)*
![Gestion de Tours](../assets/images/gestion.png)

*Figura  (Monitoreo de Tours)*
![Monitoreo de Tours](../assets/images/monitoreo.png)

*Figura  (Incidentes)*
![Incidentes](../assets/images/incidentes.png)

*Figura  (Planes)*
![Planes](../assets/images/planes.png)

**Web Application Demonstration Video:** [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQCp8uNOKAdyRaH9Ynx9v08yASmZSmceLM33SGMXAivY0qc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=PaLuKv](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQCp8uNOKAdyRaH9Ynx9v08yASmZSmceLM33SGMXAivY0qc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=PaLuKv)

#### *5.2.2.6. Services Documentation Evidence for Sprint Review*

Durante este segundo Sprint, la documentación y estructuración de los Web Services se abordó mediante la creación de un Mock API (JSON Server y MockAPI.io) fundamentado en nuestro esquema central `db.json`.Esta implementación nos permitió establecer y probar los contratos de datos (Data Contracts) reales que regirán la comunicación cliente-servidor, desbloqueando así el desarrollo interactivo de las vistas. Se han definido los esquemas de petición y respuesta para los módulos de gestión de tours, monitoreo en vivo (incidentes), perfiles (agencias/usuarios) y calendarios operativos.

**Repositorio y Commits Relacionados**
La configuración de estos servicios, al estar orientada al consumo del cliente en esta fase, se encuentra versionada en el repositorio del Frontend:
* **URL del Repositorio:** `https://github.com/axiom-apps-web/tourmate-web-application`
* **Commits de Configuración de Endpoints:** `560d09c` (Actualización de URLs base de la API para active tours, agencies, checkpoints, incidents, etc.), `c1efc6f` (Adición de endpoints de subscriptions y payments).

#### Tabla General de Endpoints (Mock API)

| Módulo / Recurso | Base URL / Entorno de Pruebas | Endpoint Path | Acciones Soportadas |
|---|---|---|---|
| **Users** | `https://6a06fa34c83ba8ad9b3e3ccf.mockapi.io/api/v1` | `/users` | GET, POST, PUT, DELETE |
| **Agencies** | `https://6ac5699354a61668c5f7294a.mockapi.io/api/v1` | `/agencies` | GET, POST, PUT, DELETE |
| **Tours** | `https://6ac551d354a61668c5f71aa1.mockapi.io/api/v1` | `/tours` | GET, POST, PUT, DELETE |
| **Active Tours** | `https://6ac55bd454a61668c5f72410.mockapi.io/api/v1` | `/active_tours` | GET, POST, PUT |
| **Incidents** | `https://6ac551e654a61668c5f71abf.mockapi.io/api/v1` | `/incidents` | GET, POST, PUT, DELETE |
| **Participants** | `https://6ac55bd454a61668c5f72410.mockapi.io/api/v1` | `/participants` | GET, POST, DELETE |
| **Tour Schedules** | `https://6ac551d354a61668c5f71aa1.mockapi.io/api/v1` | `/tour_schedules` | GET, POST, PUT, DELETE |
| **Checkpoints** | `https://6ac5699354a61668c5f7294a.mockapi.io/api/v1` | `/checkpoints` | GET, POST, PUT, DELETE |

---

#### Especificación de Acciones y Contratos de Datos

A continuación, se detallan las especificaciones de llamada basándonos en el esquema oficial de datos establecido en este Sprint para dos recursos principales: `Tours` e `Incidents`.

##### 1. Gestión de Tours (`/tours`)
Permite al administrador de agencia consultar el catálogo de expediciones disponibles y registrar nuevas rutas.

*   **GET `/tours`**
    *   **Descripción:** Retorna la lista de todos los tours registrados en el sistema con su estructura detallada.
    *   **Parámetros:** Opcionales vía Query String para filtros.
    *   **Ejemplo de Response (200 OK):**
        El sistema devuelve un arreglo de objetos JSON con la estructura validada en base de datos.
        ```json
        [
          {
            "id": 1,
            "agencyId": 1,
            "title": "Machu Picchu Clásico",
            "description": "Visita guiada a la ciudadela inca de Machu Picchu.",
            "duration": "1 día",
            "difficulty": "MEDIUM",
            "priceAmount": 180,
            "priceCurrency": "USD",
            "status": "ACTIVE"
          }
        ]
        ```

*   **POST `/tours`**
    *   **Descripción:** Crea un nuevo registro de tour en el sistema para una agencia específica.
    *   **Sintaxis de Llamada (Payload):**
        ```json
        {
          "agencyId": 3,
          "title": "Ascenso al Misti",
          "description": "Ascenso al volcán Misti (5,822 m).",
          "duration": "2 días",
          "difficulty": "HARD",
          "priceAmount": 320,
          "priceCurrency": "USD",
          "status": "INACTIVE"
        }
        ```
    *   **Explicación del Response (201 Created):** Retorna el mismo objeto enviado, anexando el identificador único (`id`) generado automáticamente por el servidor.


*Incidents*
![Incidents Endpoint](../assets/images/incidents-endpoint.png)

---

##### 2. Gestión de Incidentes de Seguridad (`/incidents`)
Recurso utilizado por turistas y guías para reportar emergencias u observaciones de seguridad asociadas a una expedición activa.

*   **POST `/incidents`**
    *   **Descripción:** Registra un nuevo incidente detectado en el terreno vinculándolo al tour activo correspondiente.
    *   **Sintaxis de Llamada (Payload):** Debe incluir las coordenadas de geolocalización, el ID del reporte, descripción y estado inicial.
        ```json
        {
          "uuid": "",
          "activeTourId": 1,
          "reportedByUserId": 9,
          "description": "Un participante se torció el tobillo en el sendero.",
          "latitude": -13.156,
          "longitude": -72.526,
          "reportedAt": "2026-10-01T09:20:00",
          "status": "RESOLVED"
        }
        ```
    *   **Explicación del Response (201 Created):** El sistema confirma la recepción guardando el registro y asignándole un `id` secuencial para futuros rastreos y actualizaciones por parte del administrador de la agencia.

*   **PUT `/incidents/:id`**
    *   **Descripción:** Actualiza un incidente existente. Habitualmente utilizado para cambiar la trazabilidad del estado.
    *   **Sintaxis de Llamada (Payload parcial):**
        ```json
        {
          "activeTourId": 2,
          "reportedByUserId": 8,
          "description": "Retraso por bloqueo en la vía hacia Chivay.",
          "latitude": -15.7,
          "longitude": -71.55,
          "reportedAt": "2026-10-01T08:40:00",
          "status": "IN_REVIEW"
        }
        ```

*Tours*
![Tours Endpoint](../assets/images/tours-endpoint.png)

**MockApi Evidencia**

*Active Tours*
![Active Tours Endpoint](../assets/images/active-tours-endpoint.png)

*Participants*
![Participants Endpoint](../assets/images/participants-endpoint.png)

#### *5.2.2.7. Software Deployment Evidence for Sprint Review*


Durante este Sprint, las actividades de despliegue se centraron en la puesta en producción de la aplicación web principal (Frontend) utilizando Firebase Hosting y en la actualización continua de la Landing Page a través de GitHub Pages. Para los Web Services, se mantuvo el alojamiento automático en la nube provisto por la plataforma MockAPI.io. A continuación, se detallan los procesos, herramientas y configuraciones implementadas para la distribución de cada producto.

#### 1. Web Services (Mock API)
Como se detalló en la sección de documentación de servicios, el backend actual opera sobre MockAPI. El despliegue de esta herramienta es automático y gestionado directamente por la plataforma en la nube tan pronto como se definen los esquemas de datos.

#### 2. Landing Page (GitHub Pages)
El sitio web estático promocional (Landing Page) fue desplegado durante el primer Sprint utilizando GitHub Pages. Durante este segundo Sprint, la actualización del despliegue fue completamente automática. Las nuevas características, traducciones y ajustes de diseño integrados en la rama principal (`main`) dispararon la reconstrucción y publicación automática del sitio gracias a las integraciones nativas de GitHub.

![Deployment](../assets/images/Deployment-GHPages.png)

#### 3. Web Application (Firebase Hosting)
Para el despliegue del Frontend interactivo de la plataforma TourMate, se optó por Firebase Hosting debido a su optimización para aplicaciones Single-Page Application (SPA) desarrolladas en Angular. El proceso consistió en la compilación del proyecto, configuración del entorno cloud y ejecución mediante la interfaz de línea de comandos (CLI).

**Paso 1: Build del Proyecto**
Se generó la versión optimizada para producción del código fuente ejecutando el siguiente comando en la terminal del IDE:
```bash
npm run build
```
Este proceso empaquetó la aplicación y la depositó en el directorio de salida por defecto (`dist/tourmate-web-application/browser`).

**Paso 2: Creación de Hosting en Firebase Console**
Se accedió a la consola web de Firebase (`https://firebase.google.com/`) autenticando con una cuenta de Google autorizada por el equipo.
* Se seleccionó la opción **Create a new Firebase project**.
* Se ingresó el identificador del proyecto ( `tourmate`).
* Se deshabilitaron las opciones *Enable Gemini in Firebase* y *Enable Google Analytics for this project* para mantener el entorno ligero, procediendo con la creación del proyecto.
* En el panel lateral, se navegó a **Hosting** y se inicializó el servicio seleccionando **Get started**.

*Firebase creación*
![Firebase](../assets/images/firebase-1.png)

**Paso 3: Instalación y Configuración del CLI de Firebase**
Se instalaron las herramientas de Firebase globalmente en el entorno de desarrollo y se realizó la vinculación de credenciales:
```bash
npm install -g firebase-tools
firebase login
```


Posteriormente, se inicializó la configuración del proyecto en el directorio raíz de la aplicación Angular:
```bash
firebase init
```
Durante el asistente de inicialización, se aplicaron las siguientes configuraciones críticas para una SPA:
* **Feature:** `Hosting: Configure files for Firebase Hosting...`
* **Project Setup:** `Use an existing project` (Se seleccionó el proyecto `tourmate-web-application` creado en el paso 2).
* **Public directory:** `dist/tourmate-web-application/browser` (Apuntando directamente a los archivos estáticos compilados por Angular).
* **Single-page app configuration:** `Y` (Para reescribir todas las rutas hacia `index.html`, evitando errores 404 al navegar).
* **GitHub Actions deploy:** `N` (Despliegue manual para este Sprint).
* **Overwrite index.html:** `N` (Para preservar el archivo generado por el build de Angular).

*Firebase Init*
![Firebase](../assets/images/firebase-2.png)

**Paso 4: Deployment en Firebase**
Una vez enlazado el proyecto local con la nube y definidos los directorios, se procedió a subir los archivos a los servidores de Firebase:
```bash
firebase deploy
```
El proceso finalizó exitosamente, proveyendo la URL pública de producción. La aplicación TourMate ahora se encuentra accesible y operando correctamente en su entorno real.

*Firebase Deploy*
![Firebase](../assets/images/firebase-3.png)

*Web Application*
![Home](../assets/images/wepapp-home.png)

**URL Web Application desplegada:** [https://tourmate-axiom.web.app/](https://tourmate-axiom.web.app/)

#### *5.2.2.8. Team Collaboration Insights during Sprint*

Todos los miembros del equipo han participado activamente en la implementación de los productos del Sprint 2, lo cual se evidencia mediante los reportes de actividad y contribución del repositorio de GitHub de la organización Axiom.

**Insights**
![Team Insights Sprint 2](../assets/images/insight3.png)

**Contributors**
![Team Insights Sprint 2](../assets/images/contribuciones2.png)

**Network**
![Team Insights Sprint 2](../assets/images/gitflow-sprint2.png)




## Conclusiones



- **Sobre el análisis del problema y la investigación del usuario:** Se concluye que las entrevistas realizadas a dueños de agencias de tours y turistas de aventura permitieron identificar necesidades, expectativas y puntos de dolor relevantes para el desarrollo de TourMate. La información recopilada fue fundamental para la definición de *User Personas*, *Empathy Maps* y *Journey Maps*, los cuales sirvieron como base para la priorización de funcionalidades y la elaboración del *Problem Statement*.

- **Sobre la propuesta de valor y validación inicial:** La elaboración de la *Landing Page* permitió comunicar de forma clara los objetivos, beneficios y funcionalidades principales de TourMate, funcionando como un medio de validación temprana de la idea de negocio. Se evidenció que presentar una interfaz informativa y accesible favorece la comprensión del problema y fortalece el interés de potenciales usuarios y clientes B2B.

- **Sobre la documentación y modelado del proyecto:** La construcción del reporte técnico permitió consolidar los hallazgos del *Problem Statement*, *Needfinding*, *User Personas*, *Empathy Maps*, *Journey Maps*, *Event Storming* y *Ubiquitous Language*, generando una visión integral del dominio del negocio. Asimismo, el uso de metodologías como *Domain-Driven Design (DDD)* facilitó la identificación de *Bounded Contexts* y responsabilidades del sistema desde etapas tempranas.

- **Sobre la definición de requerimientos:** La especificación inicial de *User Stories* y criterios de aceptación permitió transformar necesidades de usuarios en funcionalidades concretas, proporcionando una guía estructurada para el desarrollo de los siguientes sprints y reduciendo ambigüedades en la planificación técnica.

### Bibliografía


- Brown, S. (2020). *The C4 model for visualising software architecture*. C4Model.com. Recuperado de [https://c4model.com](https://c4model.com)
- Driessen, V. (2010). *A successful Git branching model*. Nvie. Recuperado de [https://nvie.com/posts/a-successful-git-branching-model](https://nvie.com/posts/a-successful-git-branching-model)
- Evans, E. (2003). *Domain-Driven Design: Tackling Complexity in the Heart of Software*. Addison-Wesley Professional. Recuperado de [https://www.domainlanguage.com/ddd](https://www.domainlanguage.com/ddd)
- Newman, S. (2021). *Building Microservices: Designing Fine-Grained Systems* (2nd ed.). O'Reilly Media. Recuperado de [https://samnewman.io/books/building_microservices_2nd_edition](https://samnewman.io/books/building_microservices_2nd_edition)
- Walls, C. (2022). *Spring in Action* (6th ed.). Manning Publications. Recuperado de [https://www.manning.com/books/spring-in-action-sixth-edition](https://www.manning.com/books/spring-in-action-sixth-edition)

## Anexos

<div style="page-break-before: always;"></div>

### Anexo A. Videos de exposiciones

- Exposición AV1: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQAxE4dWMH1_TrOpYjIh0i_tATv3SJgLVSN9_JqQWd0TLNE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=XklIVq](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQAxE4dWMH1_TrOpYjIh0i_tATv3SJgLVSN9_JqQWd0TLNE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=XklIVq)

- Exposición TB1:

### Anexo B. Videos de entrevistas

- Entrevista 1 - Mateo Escudero, Agencia de Tour: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQCf3pj989dtRqsxlQP-cphyAdmHJbpSw14HLGTRks5qOyM?e=L98d2n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQCf3pj989dtRqsxlQP-cphyAdmHJbpSw14HLGTRks5qOyM?e=L98d2n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D)
- Entrevista 2 - Aarón Espinosa, Agencia de Tour: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAofZYR8ATPSbWHvKq3vOSvAZ1mk5uCZxK_sr8rN9qoqI4?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=CzroE4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAofZYR8ATPSbWHvKq3vOSvAZ1mk5uCZxK_sr8rN9qoqI4?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=CzroE4)
- Entrevista 3 - Carlos Gutierrez, Agencia de Tour: [https://upcedupe-my.sharepoint.com/personal/u202319057_upc_edu_pe/_layouts/15/stream.aspx?id=/personal/u202319057_upc_edu_pe/Documents/Entrevista+DAOP.mp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp.Web&referrerScenario=AddressBarCopied.view.2461ff76-283b-41f2-bb72-df3bc61e4215&ClientRender=1](https://upcedupe-my.sharepoint.com/personal/u202319057_upc_edu_pe/_layouts/15/stream.aspx?id=/personal/u202319057_upc_edu_pe/Documents/Entrevista+DAOP.mp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp.Web&referrerScenario=AddressBarCopied.view.2461ff76-283b-41f2-bb72-df3bc61e4215&ClientRender=1)
- Entrevista 4 - Sofia Mendoza, Turista de aventura: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQBPxk5ihQP7Qpk1EiObhUKMAcqE0PkmidpljYmgsKZhw60?e=y94DfE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQBPxk5ihQP7Qpk1EiObhUKMAcqE0PkmidpljYmgsKZhw60?e=y94DfE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D)
- Entrevista 5 - Romina Antonella Molina Vásquez, Turista de aventura: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAQPNKuz_cKS4krk8KnLmoKAaAOQuWIL6WmZXL4T30cJJQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=B3HGgd](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAQPNKuz_cKS4krk8KnLmoKAaAOQuWIL6WmZXL4T30cJJQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=B3HGgd)
- Entrevista 6 - Miler Rodriguez, Turista de aventura: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDe0UWGvKUwRojgbs_XPIuJAclsUfNSUJK04_8jjCFOE7A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Szx6cw](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDe0UWGvKUwRojgbs_XPIuJAclsUfNSUJK04_8jjCFOE7A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Szx6cw)


### Anexo D. Materiales de ideación y diseño

- Lean UX Canvas del proyecto TourMate: 
- Big Picture EventStorming y Design-Level EventStorming: https:
- Wireframe de la landing page: [https://www.figma.com/design/2tgN0Xgvcoyy2nlZKFWU1R/TourMate---Wireframe?node-id=1-649&t=1eosnKm0G5GXiVCR-1](https://www.figma.com/design/2tgN0Xgvcoyy2nlZKFWU1R/TourMate---Wireframe?node-id=1-649&t=1eosnKm0G5GXiVCR-1)
- Mock-up de la landing page: [https://www.figma.com/design/ugarmexs9RkezsXpIEhS8e/TourMate---Landing-Page-Mock-up?node-id=0-1&t=yxRaDMrgsaPLR6T8-1](https://www.figma.com/design/ugarmexs9RkezsXpIEhS8e/TourMate---Landing-Page-Mock-up?node-id=0-1&t=yxRaDMrgsaPLR6T8-1)
- Wireframes de la aplicación web: [https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)
- Wireflows de la aplicación web:[https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)
- Mock-ups de la aplicación web:[https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)
- Prototipo de la aplicación web: [https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)


### Anexo E. Repositorios y despliegues

- Repositorio del informe del proyecto: [https://github.com/axiom-apps-web/tourmate-report](https://github.com/axiom-apps-web/tourmate-report)
- Repositorio de la landing page: [https://github.com/axiom-apps-web/tourmate-landing](https://github.com/axiom-apps-web/tourmate-landing)
- Repositorio del Web Application: [https://github.com/axiom-apps-web/tourmate-web-application](https://github.com/axiom-apps-web/tourmate-web-application)
- Repositorio del Backend: [https://github.com/axiom-apps-web/tourmate-platform](https://github.com/axiom-apps-web/tourmate-platform)
- Despliegue de la landing page: [https://axiom-apps-web.github.io/tourmate-landing/](https://axiom-apps-web.github.io/tourmate-landing/)
- Tablero del Sprint Backlog 1: [https://trello.com/b/gCKcMjVR/tourmate-sprint-1](https://trello.com/b/gCKcMjVR/tourmate-sprint-1)


### Anexo F. Herramientas utilizadas

- Trello, para gestión del backlog y tareas del proyecto: https://trello.com
- Gherkin, para criterios de aceptación en formato Given-When-Then: https://cucumber.io/docs/gherkin/
- Miro, para dinámicas de EventStorming: https://miro.com/
- Figma, para wireframes, mock-ups y prototipos: https://www.figma.com
- Canva, para recursos visuales del producto: https://www.canva.com
- UXPressia, para User Personas y Customer Journey Maps: https://uxpressia.com
- Lucidchart, para diagramas del sistema: https://www.lucidchart.com/ / https://lucidchart.com
- GitHub, para control de versiones y colaboración: https://github.com
- Visual Studio Code, para edición de código y archivos Markdown: https://code.visualstudio.com/
- GitHub Pages, para despliegue de la landing page y frontend web: https://pages.github.com
- Structurizr, para diagramas C4: https://structurizr.com



### Anexo G. Referencias bibliográficas con enlace

- Guía para ejecutar Big Picture Event Storming: https://bit.ly/bpes-guide
- Guía práctica de EventStorming remoto: https://ddd-practitioners.com/2023/03/20/remote-eventstorming-workshop/
- Material sobre historias de usuario: https://www.scrummanager.com/files/scrum_manager_historias_usuario.pdf
- Libro de ingeniería de software usado como referencia: https://www.javier8a.com/itc/bd1/ld-Ingenieria.de.software.enfoque.practico.7ed.Pressman.PDF
<div align="center">

![UPC-Logo.png](assets/UPC-Logo.png)

# Universidad Peruana de Ciencias Aplicadas
## Carrera: Ingeniería de Software
## Ciclo: 2025 - 2


## Curso: 1ASI0730 - Aplicaciones Web
## NRC: 7454
## Profesor: Angel Augusto Velasquez Nuñez

# Informe de Trabajo Final
## Startup: Edgerunners
## Producto: Smart Stay

</div>

<div align="center">

|   Código   |   Apellidos      |     Nombres     |
|:----------:|:----------------:|:---------------:|
| U20221E617 | Verona Flores    | Italo Sebastian |
| U20231A816 |Valverde Portuguez|  Natalia Ximena |
| U202019498 |Fernandez Garfias |  Alexander Piero |
|            |                  |                 |
|            |                  |                 |

**Mes y Año:** Septiembre 2025

</div>

## Registro de Versiones del Informe

El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto.  
Esta sección inicia en una página nueva e incluye un cuadro con la siguiente estructura:


| Versión |   Fecha    |                 Autor                 |                 Descripción de los Cambios                  |
|:-------:|:----------:|:-------------------------------------:|:-----------------------------------------------------------:|
|   1.0   | 01/09/2025 | Jose Jhonatan Saavedra Angulo (Líder) |                                                             |
|   1.0   | 01/09/2025 |     Italo Sebastian Verona Flores     | Creación del documento inicial del Informe de Trabajo Final |


## Project Report Collaboration Insights

- URL del repositorio para el Project Report:

<!-- \-\- Enlace pendiente de agregar por el equipo y capturas sobre el avance en el git hub. \-\- -->

## Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1. Sprint Planning n](#5211-sprint-planning-n)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

### ABET – EAC - Student Outcome 5

Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos. 

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5

| Criterio específico                                                                                | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                               | Conclusiones                                                                                                                                          |
|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta**                                | **Italo Sebastian Verona Flores**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 2**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 3**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 4**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 5**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas) | *TB1*<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1] |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Italo Sebastian Verona Flores**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 2**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 3**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 4**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 5**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas) | *TB1*<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1] |
# **Capítulo I: Introducción**

## 1.1. Startup Profile

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2 Lean UX Process

#### 1.2.1.1 Lean UX Problem Statements.

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvass

## 1.3. Segmentos objetivos.

# **Capítulo II: Requirements Elicitation & Analysis**

## 2.1. Competidores.

#### 2.1.1 Análisis Competitivo.

#### 2.1.2  Estrategias y Tácticas frente a Competidores.

## 2.1. Entrevistas.

#### 2.1.2  Diseño de entrevistas

### Entrevista – Segmento 1: Administradores de Hoteles Boutique y Pequeños

### 2.2.2. Registro de entrevistas

### 2.2.2. Análisis de entrevistas

## 2.3. Needfinding.

### 2.3.1. User Personas.

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping.

### 2.3.4. Empathy Mapping.

## 2.4. Big Picture EventStorming.

## 2.5. Ubiquitous Language.


# **Capítulo III: Requirements Specification**

## 3.1. User Stories.

<table>
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
    <th>Relacionado con (Epic ID)</th>
  </tr>

  <!-- EPICS -->
  <tr>
    <td><strong>EP-01</strong></td>
    <td><strong>Gestión de Autenticación y Usuarios</strong></td>
    <td>Epic que agrupa funcionalidades de registro, login, gestión de perfiles y control de acceso por roles para todos los tipos de usuario (administradores, staff, huéspedes).</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-02</strong></td>
    <td><strong>Gestión Hotelera Central</strong></td>
    <td>Epic que incluye la administración de reservas, habitaciones, check-in/check-out digital, gestión operativa diaria y coordinación de servicios internos.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-03</strong></td>
    <td><strong>Experiencia Digital del Huésped</strong></td>
    <td>Epic enfocada en la experiencia del huésped: control ambiental IoT, servicios personalizados, comunicación digital y evaluación post-estadía.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-04</strong></td>
    <td><strong>Analytics y Reporting</strong></td>
    <td>Epic que abarca dashboard gerencial, reportes de ocupación, KPIs operativos, análisis de satisfacción y métricas financieras.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-05</strong></td>
    <td><strong>Integraciones y Canales Externos</strong></td>
    <td>Epic para conexiones con OTAs, WhatsApp, sistemas de pago, reputación digital y webhooks con terceros.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-06</strong></td>
    <td><strong>Landing Page y Marketing Digital</strong></td>
    <td>Epic del sitio web estático con información por segmentos, casos de éxito, simuladores y canales de contacto comercial.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-07</strong></td>
    <td><strong>API RESTful y Servicios Técnicos</strong></td>
    <td>Epic que incluye endpoints, autenticación API, documentación técnica, monitoreo y integración con sistemas externos.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-08</strong></td>
    <td><strong>Notificaciones y Comunicación</strong></td>
    <td>Epic para sistema de notificaciones push, email, SMS, alertas automáticas y comunicación staff-huésped.</td>
    <td></td>
    <td>-</td>
  </tr>

  <!-- USER STORIES -->
  <tr>
    <td>US-01</td>
    <td>Registro de usuario con validación</td>
    <td>Como usuario nuevo, quiero registrarme en Smart Stay validando mi email para acceder a las funcionalidades según mi rol.</td>
    <td>
      <strong>Escenario 1: Registro exitoso</strong><br>
      Dado que soy un usuario nuevo con datos válidos, cuando completo el formulario de registro, entonces mi cuenta se crea correctamente y recibo confirmación por email.<br>
      <strong>Escenario 2: Email ya registrado</strong><br>
      Dado que intento registrarme con un email ya existente, cuando envío el formulario, entonces el sistema muestra mensaje "Email ya registrado" y sugiere recuperar contraseña.<br>
      <strong>Escenario 3: Datos incompletos</strong><br>
      Dado que dejo campos obligatorios vacíos, cuando intento registrarme, entonces el sistema resalta los campos faltantes y no permite continuar.<br>
      <strong>Escenario 4: Validación de formato email</strong><br>
      Dado que ingreso un email con formato inválido, cuando envío el formulario, entonces el sistema muestra error de formato.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-02</td>
    <td>Inicio de sesión seguro</td>
    <td>Como usuario registrado, quiero iniciar sesión de manera segura para acceder a mi panel personalizado según mi rol.</td>
    <td>
      <strong>Escenario 1: Login correcto</strong><br>
      Dado que tengo credenciales válidas, cuando inicio sesión, entonces accedo a mi dashboard correspondiente (admin/huésped/staff).<br>
      <strong>Escenario 2: Credenciales incorrectas</strong><br>
      Dado que ingreso datos incorrectos, cuando intento acceder, entonces recibo mensaje de error sin revelar si el problema es email o contraseña.<br>
      <strong>Escenario 3: Cuenta bloqueada</strong><br>
      Dado que falló el login 5 veces consecutivas, cuando intento nuevamente, entonces la cuenta se bloquea temporalmente y recibo notificación.<br>
      <strong>Escenario 4: Sesión persistente</strong><br>
      Dado que marco "recordarme", cuando cierro y abro el navegador, entonces sigo logueado hasta que cierre sesión manualmente.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-03</td>
    <td>Gestión de perfiles y roles</td>
    <td>Como administrador, quiero gestionar usuarios, asignar roles y permisos para controlar el acceso a diferentes funcionalidades.</td>
    <td>
      <strong>Escenario 1: Crear usuario staff</strong><br>
      Dado que soy admin, cuando creo un usuario staff, entonces puedo asignarle permisos específicos (housekeeping, front desk, mantenimiento).<br>
      <strong>Escenario 2: Modificar permisos</strong><br>
      Dado que existe un usuario staff, cuando cambio sus permisos, entonces su acceso se actualiza inmediatamente.<br>
      <strong>Escenario 3: Desactivar usuario</strong><br>
      Dado que necesito desactivar un usuario, cuando lo hago, entonces pierde acceso pero su historial se mantiene.<br>
      <strong>Escenario 4: Auditoría de accesos</strong><br>
      Dado que requiero revisar actividad, cuando consulto logs, entonces veo fecha, hora, usuario y acción realizada.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-04</td>
    <td>Recuperación de contraseña</td>
    <td>Como usuario, quiero recuperar mi contraseña mediante email para volver a acceder a mi cuenta.</td>
    <td>
      <strong>Escenario 1: Solicitud válida</strong><br>
      Dado que solicito recuperar contraseña con email registrado, cuando envío la solicitud, entonces recibo link de reset por email.<br>
      <strong>Escenario 2: Email no registrado</strong><br>
      Dado que solicito con email no registrado, cuando envío solicitud, entonces recibo mensaje genérico sin revelar si el email existe.<br>
      <strong>Escenario 3: Link expirado</strong><br>
      Dado que el link de reset tiene más de 30 minutos, cuando intento usarlo, entonces expira y debo solicitar uno nuevo.<br>
      <strong>Escenario 4: Cambio exitoso</strong><br>
      Dado que tengo link válido, cuando establezco nueva contraseña, entonces se actualiza y recibo confirmación.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-05</td>
    <td>Dashboard de administrador</td>
    <td>Como administrador, quiero un panel centralizado con información clave para gestionar mi hotel eficientemente.</td>
    <td>
      <strong>Escenario 1: Vista general</strong><br>
      Dado que accedo al dashboard, cuando se carga, entonces veo ocupación actual, check-ins/outs del día, tareas pendientes y alertas importantes.<br>
      <strong>Escenario 2: Filtros por fecha</strong><br>
      Dado que quiero revisar periodo específico, cuando selecciono rango de fechas, entonces todos los indicadores se actualizan.<br>
      <strong>Escenario 3: Acceso rápido</strong><br>
      Dado que estoy en el dashboard, cuando hago clic en cualquier métrica, entonces navego a la sección detallada correspondiente.<br>
      <strong>Escenario 4: Actualización en tiempo real</strong><br>
      Dado que hay cambios operativos, cuando ocurren, entonces el dashboard se actualiza automáticamente sin recargar la página.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-06</td>
    <td>Gestión de habitaciones y estados</td>
    <td>Como administrador, quiero gestionar el estado de todas las habitaciones para optimizar la operación diaria.</td>
    <td>
      <strong>Escenario 1: Cambiar estado habitación</strong><br>
      Dado que selecciono una habitación, cuando cambio su estado (libre/ocupada/limpieza/mantenimiento), entonces se actualiza inmediatamente y notifica al staff correspondiente.<br>
      <strong>Escenario 2: Vista de mapa de habitaciones</strong><br>
      Dado que accedo al mapa de habitaciones, cuando se carga, entonces veo todos los estados con códigos de color y puedo hacer cambios rápidos.<br>
      <strong>Escenario 3: Historial de cambios</strong><br>
      Dado que necesito revisar cambios, cuando consulto historial de una habitación, entonces veo todos los cambios de estado con fecha, hora y usuario responsable.<br>
      <strong>Escenario 4: Alertas automáticas</strong><br>
      Dado que una habitación está en mantenimiento más de 24 horas, cuando pasa el tiempo, entonces recibo alerta automática.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-07</td>
    <td>Gestión centralizada de reservas</td>
    <td>Como administrador, quiero gestionar todas las reservas en un solo lugar para evitar overbooking y optimizar ocupación.</td>
    <td>
      <strong>Escenario 1: Vista calendario reservas</strong><br>
      Dado que accedo a reservas, cuando selecciono vista calendario, entonces veo todas las reservas organizadas por fecha con información clave (huésped, habitación, estado).<br>
      <strong>Escenario 2: Crear reserva manual</strong><br>
      Dado que recibo reserva por teléfono, cuando la ingreso manualmente, entonces el sistema valida disponibilidad y confirma la reserva.<br>
      <strong>Escenario 3: Modificar reserva existente</strong><br>
      Dado que necesito cambiar una reserva, cuando la edito, entonces el sistema valida nueva disponibilidad y notifica al huésped.<br>
      <strong>Escenario 4: Cancelación con políticas</strong><br>
      Dado que se cancela una reserva, cuando proceso la cancelación, entonces el sistema aplica políticas de cancelación y libera la habitación.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-08</td>
    <td>Check-in digital automatizado</td>
    <td>Como administrador y huésped, quiero que el check-in se realice digitalmente en menos de 3 minutos para mejorar la experiencia.</td>
    <td>
      <strong>Escenario 1: Check-in exitoso huésped</strong><br>
      Dado que el huésped inicia check-in digital, cuando completa sus datos y confirmación, entonces recibe acceso digital a su habitación y código de acceso.<br>
      <strong>Escenario 2: Validación de documentos</strong><br>
      Dado que el huésped sube documentos de identidad, cuando el sistema los procesa, entonces valida automáticamente y aprueba el check-in.<br>
      <strong>Escenario 3: Check-in asistido</strong><br>
      Dado que el huésped tiene dificultades, cuando solicita ayuda, entonces el staff recibe notificación y puede asistir remotamente.<br>
      <strong>Escenario 4: Notificación automática</strong><br>
      Dado que se completa el check-in, cuando se confirma, entonces el housekeeping recibe notificación de habitación ocupada y el admin ve el estado actualizado.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-09</td>
    <td>Check-out digital y facturación</td>
    <td>Como huésped, quiero realizar check-out digital y recibir mi factura automáticamente para agilizar mi salida.</td>
    <td>
      <strong>Escenario 1: Check-out exitoso</strong><br>
      Dado que inicio check-out desde la app, cuando confirmo salida y reviso cargos, entonces mi habitación se libera y recibo factura por email.<br>
      <strong>Escenario 2: Cargos adicionales</strong><br>
      Dado que tengo consumos pendientes, cuando hago check-out, entonces veo el detalle de cargos y puedo aprobar el pago.<br>
      <strong>Escenario 3: Check-out tardío</strong><br>
      Dado que mi check-out es después de la hora límite, cuando lo proceso, entonces se aplica cargo correspondiente y se notifica.<br>
      <strong>Escenario 4: Notificación housekeeping</strong><br>
      Dado que completo check-out, cuando se confirma, entonces housekeeping recibe tarea automática de limpieza para esa habitación.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-10</td>
    <td>Asignación y seguimiento de tareas de staff</td>
    <td>Como administrador, quiero asignar tareas al staff y hacer seguimiento de su progreso para optimizar las operaciones.</td>
    <td>
      <strong>Escenario 1: Asignar tarea housekeeping</strong><br>
      Dado que una habitación necesita limpieza, cuando asigno la tarea, entonces el staff recibe notificación inmediata con detalles y prioridad.<br>
      <strong>Escenario 2: Actualización de progreso</strong><br>
      Dado que el staff inicia una tarea, cuando la marca como "en progreso", entonces el admin ve la actualización en tiempo real.<br>
      <strong>Escenario 3: Completar tarea</strong><br>
      Dado que el staff termina una tarea, cuando la marca como completada, entonces el admin recibe notificación y puede validar el trabajo.<br>
      <strong>Escenario 4: Tareas vencidas</strong><br>
      Dado que una tarea no se completa en el tiempo esperado, cuando pasa el deadline, entonces se genera alerta automática.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-11</td>
    <td>Control ambiental IoT desde app móvil</td>
    <td>Como huésped, quiero controlar temperatura, iluminación y otros aspectos ambientales desde mi smartphone para personalizar mi experiencia.</td>
    <td>
      <strong>Escenario 1: Ajuste de temperatura</strong><br>
      Dado que estoy en mi habitación, cuando cambio la temperatura desde la app, entonces el sistema IoT ajusta el clima en menos de 30 segundos.<br>
      <strong>Escenario 2: Control de iluminación</strong><br>
      Dado que quiero ajustar las luces, cuando uso los controles en la app, entonces puedo cambiar intensidad, color y encender/apagar luces específicas.<br>
      <strong>Escenario 3: Configuración de persianas</strong><br>
      Dado que quiero controlar luz natural, cuando ajusto persianas desde la app, entonces se abren/cierran automáticamente al porcentaje seleccionado.<br>
      <strong>Escenario 4: Presets personalizados</strong><br>
      Dado que quiero configuraciones rápidas, cuando guardo un preset (ej: "descanso", "trabajo"), entonces puedo activar múltiples configuraciones con un toque.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-12</td>
    <td>Solicitud de servicios desde app</td>
    <td>Como huésped, quiero solicitar room service, limpieza adicional y otros servicios desde mi smartphone de forma conveniente.</td>
    <td>
      <strong>Escenario 1: Solicitar room service</strong><br>
      Dado que quiero pedir comida, cuando accedo al menú en la app, entonces puedo seleccionar productos, personalizar y confirmar pedido con tiempo estimado.<br>
      <strong>Escenario 2: Servicio de limpieza adicional</strong><br>
      Dado que necesito limpieza extra, cuando lo solicito, entonces puedo elegir horario preferido y el staff recibe la solicitud inmediatamente.<br>
      <strong>Escenario 3: Seguimiento de solicitudes</strong><br>
      Dado que hice un pedido, cuando consulto el estado, entonces veo el progreso en tiempo real (recibido, preparando, en camino, entregado).<br>
      <strong>Escenario 4: Servicios especiales</strong><br>
      Dado que necesito servicios especiales (transporte, tour, reservas), cuando los solicito, entonces staff recibe notificación para coordinación personalizada.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-13</td>
    <td>Comunicación digital huésped-staff</td>
    <td>Como huésped, quiero comunicarme con el staff del hotel de manera digital para resolver dudas y solicitudes rápidamente.</td>
    <td>
      <strong>Escenario 1: Chat en tiempo real</strong><br>
      Dado que tengo una consulta, cuando inicio chat desde la app, entonces me conecto con staff disponible y recibo respuesta en menos de 5 minutos.<br>
      <strong>Escenario 2: Solicitudes específicas</strong><br>
      Dado que necesito algo específico, cuando envío mensaje detallado, entonces el staff correspondiente recibe la solicitud y puede coordinar la atención.<br>
      <strong>Escenario 3: Historial de conversaciones</strong><br>
      Dado que he tenido varias conversaciones, cuando accedo al historial, entonces puedo revisar todas las interacciones de mi estadía.<br>
      <strong>Escenario 4: Escalamiento automático</strong><br>
      Dado que mi solicitud no se resuelve en tiempo razonable, cuando pasa el tiempo límite, entonces se escala automáticamente a un supervisor.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-14</td>
    <td>Personalización de experiencia basada en preferencias</td>
    <td>Como huésped, quiero que el sistema aprenda mis preferencias para ofrecerme experiencias y servicios personalizados.</td>
    <td>
      <strong>Escenario 1: Configuración inicial de preferencias</strong><br>
      Dado que es mi primera estadía, cuando completo perfil de preferencias, entonces el sistema configura la habitación según mis gustos antes de mi llegada.<br>
      <strong>Escenario 2: Aprendizaje automático</strong><br>
      Dado que he usado el sistema varias veces, cuando regreso, entonces el sistema sugiere automáticamente servicios y configuraciones basadas en mi historial.<br>
      <strong>Escenario 3: Recomendaciones personalizadas</strong><br>
      Dado mi perfil de gustos, cuando estoy en el hotel, entonces recibo recomendaciones de restaurantes, actividades y servicios alineadas con mis intereses.<br>
      <strong>Escenario 4: Ofertas exclusivas</strong><br>
      Dado que soy huésped recurrente, cuando reviso la app, entonces veo ofertas y upgrades personalizados basados en mi historial y lealtad.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-15</td>
    <td>Evaluación post-estadía y feedback</td>
    <td>Como huésped, quiero evaluar mi experiencia y dejar feedback para ayudar al hotel a mejorar sus servicios.</td>
    <td>
      <strong>Escenario 1: Evaluación automática</strong><br>
      Dado que completo mi check-out, cuando pasan 2 horas, entonces recibo invitación automática para evaluar mi estadía con formulario simple.<br>
      <strong>Escenario 2: Feedback detallado</strong><br>
      Dado que quiero dar opinión específica, cuando accedo a evaluación extendida, entonces puedo calificar aspectos individuales y dejar comentarios.<br>
      <strong>Escenario 3: Seguimiento a feedback negativo</strong><br>
      Dado que dejo calificación baja, cuando envío la evaluación, entonces el hotel recibe alerta inmediata y puede contactarme para resolver el problema.<br>
      <strong>Escenario 4: Incentivos por feedback</strong><br>
      Dado que completo evaluación, cuando la envío, entonces recibo beneficio para próxima estadía (descuento, upgrade, servicio gratuito).
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-16</td>
    <td>Dashboard analytics y KPIs operativos</td>
    <td>Como administrador, quiero visualizar métricas clave y KPIs para tomar decisiones informadas sobre la operación del hotel.</td>
    <td>
      <strong>Escenario 1: Métricas en tiempo real</strong><br>
      Dado que accedo al dashboard analytics, cuando se carga, entonces veo ocupación actual, ingresos del día, tareas completadas y satisfacción promedio.<br>
      <strong>Escenario 2: Comparativos históricos</strong><br>
      Dado que quiero analizar tendencias, cuando selecciono comparar períodos, entonces veo gráficos comparativos de ocupación, ingresos y operación.<br>
      <strong>Escenario 3: Drill-down en métricas</strong><br>
      Dado que veo una métrica de interés, cuando hago clic en ella, entonces puedo explorar datos detallados y filtrar por habitación, fecha o servicio.<br>
      <strong>Escenario 4: Alertas inteligentes</strong><br>
      Dado que hay tendencias negativas, cuando el sistema las detecta, entonces recibo alertas automáticas con sugerencias de acción.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-17</td>
    <td>Reportes financieros y ocupación</td>
    <td>Como administrador, quiero generar reportes financieros y de ocupación para análisis gerencial y toma de decisiones.</td>
    <td>
      <strong>Escenario 1: Reporte diario automatizado</strong><br>
      Dado que termina el día operativo, cuando pasa la medianoche, entonces el sistema genera automáticamente reporte diario con ingresos, ocupación y incidencias.<br>
      <strong>Escenario 2: Reporte personalizado</strong><br>
      Dado que necesito análisis específico, cuando configuro parámetros (fechas, métricas, filtros), entonces genero reporte customizado en PDF o Excel.<br>
      <strong>Escenario 3: Forecasting y proyecciones</strong><br>
      Dado histórico de datos, cuando accedo a proyecciones, entonces veo forecasting de ocupación y ingresos basado en tendencias y reservas confirmadas.<br>
      <strong>Escenario 4: Benchmarking competitivo</strong><br>
      Dado que tengo datos del mercado, cuando genero reporte comparativo, entonces veo mi performance versus competencia local en métricas clave.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-18</td>
    <td>Análisis de satisfacción del huésped</td>
    <td>Como administrador, quiero analizar la satisfacción de los huéspedes para identificar áreas de mejora y mantener calidad de servicio.</td>
    <td>
      <strong>Escenario 1: Dashboard de satisfacción</strong><br>
      Dado que accedo a análisis de satisfacción, cuando se carga, entonces veo NPS promedio, distribución de calificaciones y comentarios recientes.<br>
      <strong>Escenario 2: Análisis por categoría</strong><br>
      Dado que quiero entender problemas específicos, cuando filtro por aspecto (limpieza, servicio, comodidad), entonces veo calificaciones detalladas por área.<br>
      <strong>Escenario 3: Tendencias temporales</strong><br>
      Dado que quiero ver evolución, cuando selecciono vista temporal, entonces veo cómo ha cambiado la satisfacción en el tiempo.<br>
      <strong>Escenario 4: Acciones correctivas</strong><br>
      Dado que identifico problema recurrente, cuando lo marco para acción, entonces se crea tarea automática para el departamento responsable.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-19</td>
    <td>Monitoreo de consumo energético IoT</td>
    <td>Como administrador, quiero monitorear el consumo energético de habitaciones y áreas comunes para optimizar costos operativos.</td>
    <td>
      <strong>Escenario 1: Dashboard consumo en tiempo real</strong><br>
      Dado que accedo a monitoreo energético, cuando se carga, entonces veo consumo actual por habitación, área común y equipos principales.<br>
      <strong>Escenario 2: Alertas de consumo excesivo</strong><br>
      Dado que una habitación excede consumo normal, cuando pasa el umbral, entonces recibo alerta inmediata con opción de investigar o ajustar remotamente.<br>
      <strong>Escenario 3: Optimización automática</strong><br>
      Dado que una habitación está desocupada, cuando pasan 30 minutos sin actividad, entonces el sistema ajusta automáticamente temperatura y luces a modo eco.<br>
      <strong>Escenario 4: Reportes de ahorro</strong><br>
      Dado que se implementan optimizaciones, cuando genero reporte mensual, entonces veo comparativo de consumo y ahorros logrados versus período anterior.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-20</td>
    <td>Integración con OTAs y canales de reserva</td>
    <td>Como administrador, quiero integrar mi inventario con Booking.com, Expedia y otras OTAs para maximizar ocupación y evitar overbooking.</td>
    <td>
      <strong>Escenario 1: Sincronización automática disponibilidad</strong><br>
      Dado que cambio disponibilidad en Smart Stay, cuando actualizo, entonces todos los canales conectados se sincronizan automáticamente en menos de 5 minutos.<br>
      <strong>Escenario 2: Importación automática de reservas</strong><br>
      Dado que recibo reserva de OTA, cuando se confirma, entonces se importa automáticamente a Smart Stay con toda la información del huésped.<br>
      <strong>Escenario 3: Gestión centralizada de precios</strong><br>
      Dado que quiero cambiar tarifas, cuando las actualizo en Smart Stay, entonces se propagan automáticamente a todos los canales configurados.<br>
      <strong>Escenario 4: Resolución de conflictos</strong><br>
      Dado que hay discrepancia entre canales, cuando el sistema la detecta, entonces me notifica inmediatamente y sugiere acciones para resolver el conflicto.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-21</td>
    <td>Integración WhatsApp Business</td>
    <td>Como administrador, quiero usar WhatsApp Business para comunicación directa con huéspedes y gestión de consultas pre y post estadía.</td>
    <td>
      <strong>Escenario 1: Mensajes automáticos de bienvenida</strong><br>
      Dado que un huésped confirma reserva, cuando se registra, entonces recibe mensaje automático de WhatsApp con información de llegada y contacto.<br>
      <strong>Escenario 2: Consultas pre-llegada</strong><br>
      Dado que huésped envía consulta por WhatsApp, cuando llega el mensaje, entonces staff recibe notificación en Smart Stay y puede responder desde la plataforma.<br>
      <strong>Escenario 3: Confirmación de servicios</strong><br>
      Dado que huésped solicita servicio por WhatsApp, cuando se procesa, entonces recibe confirmación automática con detalles y tiempo estimado.<br>
      <strong>Escenario 4: Seguimiento post-estadía</strong><br>
      Dado que huésped hace check-out, cuando pasa 1 día, entonces recibe mensaje automático de agradecimiento e invitación a evaluar experiencia.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-22</td>
    <td>Gestión de reputación digital</td>
    <td>Como administrador, quiero gestionar reseñas de Google, TripAdvisor y OTAs desde un solo lugar para mantener buena reputación online.</td>
    <td>
      <strong>Escenario 1: Consolidación de reseñas</strong><br>
      Dado que accedo a gestión de reputación, cuando se carga, entonces veo todas las reseñas de diferentes plataformas en un solo dashboard.<br>
      <strong>Escenario 2: Respuesta centralizada</strong><br>
      Dado que quiero responder una reseña, cuando escribo la respuesta, entonces puedo publicarla automáticamente en la plataforma correspondiente.<br>
      <strong>Escenario 3: Alertas de reseñas negativas</strong><br>
      Dado que recibo reseña con 3 estrellas o menos, cuando se publica, entonces recibo alerta inmediata para respuesta rápida.<br>
      <strong>Escenario 4: Análisis de sentimientos</strong><br>
      Dado que tengo múltiples reseñas, cuando accedo a análisis, entonces veo tendencias de satisfacción, palabras clave frecuentes y áreas de mejora identificadas.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-23</td>
    <td>Procesamiento de pagos digitales</td>
    <td>Como administrador y huésped, quiero procesar pagos de manera segura y eficiente a través de múltiples métodos de pago.</td>
    <td>
      <strong>Escenario 1: Pago con tarjeta en check-in</strong><br>
      Dado que huésped hace check-in digital, cuando ingresa datos de tarjeta, entonces se procesa pre-autorización segura y se confirma el registro.<br>
      <strong>Escenario 2: Pago de servicios adicionales</strong><br>
      Dado que huésped solicita room service, cuando confirma pedido, entonces puede pagar inmediatamente por la app con método guardado.<br>
      <strong>Escenario 3: Facturación automática check-out</strong><br>
      Dado que huésped hace check-out, cuando confirma cargos finales, entonces se procesa pago automático y recibe factura digital.<br>
      <strong>Escenario 4: Manejo de pagos fallidos</strong><br>
      Dado que un pago falla, cuando ocurre el error, entonces huésped recibe notificación inmediata con opciones alternativas de pago.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-24</td>
    <td>Landing page segmentada</td>
    <td>Como visitante, quiero encontrar información específica según mi perfil (administrador hotelero o huésped) para entender el valor de Smart Stay.</td>
    <td>
      <strong>Escenario 1: Información para administradores</strong><br>
      Dado que soy administrador de hotel visitando la página, cuando navego la sección para hoteles, entonces veo beneficios operativos, ROI, casos de éxito y demo específica.<br>
      <strong>Escenario 2: Información para huéspedes</strong><br>
      Dado que soy viajero visitando la página, cuando navego la sección para huéspedes, entonces veo beneficios de experiencia, comodidad y tecnología.<br>
      <strong>Escenario 3: Navegación intuitiva</strong><br>
      Dado que llego a la landing, cuando se carga, entonces puedo identificar fácilmente mi perfil y navegar a información relevante en menos de 3 clics.<br>
      <strong>Escenario 4: Llamadas a acción claras</strong><br>
      Dado que estoy interesado, cuando busco siguiente paso, entonces encuentro CTAs claros (solicitar demo, contactar ventas, descargar app).
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-25</td>
    <td>Simulador de ROI para hoteles</td>
    <td>Como administrador de hotel visitante, quiero usar un simulador para estimar el retorno de inversión que obtendría con Smart Stay.</td>
    <td>
      <strong>Escenario 1: Cálculo básico de ROI</strong><br>
      Dado que ingreso datos básicos (número de habitaciones, ocupación promedio), cuando ejecuto simulación, entonces veo estimado de ahorros anuales y tiempo de recuperación.<br>
      <strong>Escenario 2: Personalización por tipo de hotel</strong><br>
      Dado que selecciono mi tipo de hotel (boutique, cadena, resort), cuando uso simulador, entonces los cálculos se ajustan a promedios de mi segmento.<br>
      <strong>Escenario 3: Comparativo con situación actual</strong><br>
      Dado que ingreso costos operativos actuales, cuando genero reporte, entonces veo comparativa clara entre mi operación actual y con Smart Stay.<br>
      <strong>Escenario 4: Exportar resultados</strong><br>
      Dado que completo simulación, cuando quiero guardar resultados, entonces puedo exportar reporte en PDF para compartir con mi equipo.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-26</td>
    <td>Casos de éxito y testimonios</td>
    <td>Como visitante interesado, quiero ver casos de éxito reales de hoteles que usan Smart Stay para validar la efectividad de la solución.</td>
    <td>
      <strong>Escenario 1: Testimonios en video</strong><br>
      Dado que accedo a casos de éxito, cuando navego la sección, entonces puedo ver videos de administradores reales compartiendo su experiencia con métricas específicas.<br>
      <strong>Escenario 2: Métricas de mejora</strong><br>
      Dado que leo un caso de éxito, cuando reviso los detalles, entonces veo datos específicos de mejora (% reducción costos, % aumento satisfacción, tiempo ahorrado).<br>
      <strong>Escenario 3: Casos por tipo de hotel</strong><br>
      Dado que busco referencias, cuando filtro por tipo de hotel similar al mío, entonces veo casos relevantes para mi situación específica.<br>
      <strong>Escenario 4: Contacto directo con casos</strong><br>
      Dado que me interesa un caso específico, cuando solicito más información, entonces puedo conectar directamente con el hotel para referencias.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-27</td>
    <td>Solicitud de demo y contacto comercial</td>
    <td>Como visitante interesado, quiero solicitar una demostración y contactar al equipo comercial de manera fácil y rápida.</td>
    <td>
      <strong>Escenario 1: Formulario de solicitud de demo</strong><br>
      Dado que quiero ver una demo, cuando completo el formulario, entonces recibo confirmación inmediata y contacto del equipo en menos de 24 horas.<br>
      <strong>Escenario 2: Agendamiento automático</strong><br>
      Dado que solicito demo, cuando envío el formulario, entonces puedo agendar cita directamente en calendario disponible del equipo comercial.<br>
      <strong>Escenario 3: Información de contacto accesible</strong><br>
      Dado que prefiero contacto directo, cuando busco información, entonces encuentro fácilmente teléfono, email y WhatsApp del equipo de ventas.<br>
      <strong>Escenario 4: Seguimiento automático</strong><br>
      Dado que solicité información, cuando pasa tiempo sin respuesta, entonces recibo seguimiento automático con alternativas de contacto.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-28</td>
    <td>Información corporativa y valores</td>
    <td>Como visitante, quiero conocer la misión, visión y valores de Smart Stay para entender la filosofía de la empresa.</td>
    <td>
      <strong>Escenario 1: Sección "Sobre nosotros" completa</strong><br>
      Dado que busco información corporativa, cuando accedo a "Sobre nosotros", entonces encuentro misión, visión, valores y historia de la empresa.<br>
      <strong>Escenario 2: Equipo y liderazgo</strong><br>
      Dado que quiero conocer el equipo, cuando navego a la sección, entonces veo información de fundadores, líderes clave y su experiencia.<br>
      <strong>Escenario 3: Compromiso con sostenibilidad</strong><br>
      Dado que me importa el impacto ambiental, cuando reviso valores, entonces veo compromiso claro con sostenibilidad y eficiencia energética.<br>
      <strong>Escenario 4: Certificaciones y reconocimientos</strong><br>
      Dado que busco validación de calidad, cuando reviso credenciales, entonces veo certificaciones, premios y reconocimientos de la industria.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-29</td>
    <td>API RESTful para gestión de habitaciones</td>
    <td>Como developer, quiero acceder a endpoints RESTful para integrar Smart Stay con sistemas externos de gestión hotelera.</td>
    <td>
      <strong>Escenario 1: Consultar habitaciones disponibles</strong><br>
      Dado que hago GET /api/v1/rooms?date=2025-10-15, cuando la API procesa la solicitud, entonces recibo lista de habitaciones con disponibilidad y precios.<br>
      <strong>Escenario 2: Actualizar estado de habitación</strong><br>
      Dado que hago PUT /api/v1/rooms/101 con nuevo estado, cuando se procesa, entonces la habitación se actualiza y recibo confirmación 200 OK.<br>
      <strong>Escenario 3: Crear nueva reserva</strong><br>
      Dado que hago POST /api/v1/bookings con datos válidos, cuando se procesa, entonces se crea reserva y recibo ID único de confirmación.<br>
      <strong>Escenario 4: Manejo de errores</strong><br>
      Dado que envío datos inválidos, cuando la API los procesa, entonces recibo error 400 con descripción clara del problema.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-30</td>
    <td>API para control de dispositivos IoT</td>
    <td>Como developer, quiero endpoints para controlar dispositivos IoT de las habitaciones desde aplicaciones externas.</td>
    <td>
      <strong>Escenario 1: Obtener estado actual de dispositivos</strong><br>
      Dado que hago GET /api/v1/rooms/101/devices, cuando se procesa, entonces recibo estado actual de temperatura, luces, persianas y otros dispositivos.<br>
      <strong>Escenario 2: Controlar temperatura</strong><br>
      Dado que hago POST /api/v1/rooms/101/climate con temperatura deseada, cuando se procesa, entonces el dispositivo IoT ajusta la temperatura.<br>
      <strong>Escenario 3: Control de iluminación</strong><br>
      Dado que hago PUT /api/v1/rooms/101/lights con configuración, cuando se procesa, entonces las luces se ajustan según parámetros enviados.<br>
      <strong>Escenario 4: Logs de cambios</strong><br>
      Dado que hago GET /api/v1/rooms/101/device-logs, cuando se procesa, entonces recibo historial de todos los cambios realizados en dispositivos.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-31</td>
    <td>Autenticación y autorización API</td>
    <td>Como developer, quiero un sistema seguro de autenticación para acceder a los endpoints de Smart Stay API.</td>
    <td>
      <strong>Escenario 1: Obtener token de acceso</strong><br>
      Dado que hago POST /api/v1/auth con credenciales válidas, cuando se procesa, entonces recibo JWT token con tiempo de expiración.<br>
      <strong>Escenario 2: Acceso con token válido</strong><br>
      Dado que incluyo Bearer token válido en headers, cuando hago request a endpoint protegido, entonces recibo respuesta exitosa.<br>
      <strong>Escenario 3: Token expirado</strong><br>
      Dado que mi token expiró, cuando hago request, entonces recibo error 401 Unauthorized con mensaje claro.<br>
      <strong>Escenario 4: Diferentes niveles de acceso</strong><br>
      Dado que tengo token de solo lectura, cuando intento hacer POST/PUT/DELETE, entonces recibo error 403 Forbidden.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-32</td>
    <td>Documentación interactiva de API</td>
    <td>Como developer, quiero acceder a documentación completa e interactiva para integrar fácilmente con Smart Stay API.</td>
    <td>
      <strong>Escenario 1: Explorar endpoints disponibles</strong><br>
      Dado que accedo a la documentación, cuando navego, entonces veo todos los endpoints organizados por categoría con descripción completa.<br>
      <strong>Escenario 2: Probar endpoints en vivo</strong><br>
      Dado que estoy en la documentación, cuando selecciono "Try it", entonces puedo probar el endpoint directamente con mis credenciales.<br>
      <strong>Escenario 3: Ejemplos de código</strong><br>
      Dado que reviso un endpoint, cuando veo la documentación, entonces encuentro ejemplos de código en múltiples lenguajes (JavaScript, Python, PHP).<br>
      <strong>Escenario 4: Esquemas de datos</strong><br>
      Dado que necesito entender estructura, cuando reviso endpoint, entonces veo esquemas completos de request/response con tipos de datos.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-33</td>
    <td>Webhooks para eventos en tiempo real</td>
    <td>Como developer, quiero configurar webhooks para recibir notificaciones automáticas cuando ocurren eventos importantes en Smart Stay.</td>
    <td>
      <strong>Escenario 1: Configurar webhook</strong><br>
      Dado que hago POST /api/v1/webhooks con URL y eventos, cuando se configura, entonces mi endpoint recibe notificaciones de esos eventos.<br>
      <strong>Escenario 2: Notificación de nueva reserva</strong><br>
      Dado que tengo webhook configurado para "booking.created", cuando se hace nueva reserva, entonces mi endpoint recibe POST con datos de la reserva.<br>
      <strong>Escenario 3: Reintentos automáticos</strong><br>
      Dado que mi endpoint no responde, cuando Smart Stay envía webhook, entonces reintenta hasta 3 veces con backoff exponencial.<br>
      <strong>Escenario 4: Verificación de seguridad</strong><br>
      Dado que recibo webhook, cuando verifico la firma, entonces puedo confirmar que viene realmente de Smart Stay usando secret compartido.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-34</td>
    <td>Sistema de notificaciones push móviles</td>
    <td>Como huésped, quiero recibir notificaciones push en mi smartphone sobre el estado de mis solicitudes y servicios.</td>
    <td>
      <strong>Escenario 1: Notificación de confirmación de reserva</strong><br>
      Dado que hago una reserva, cuando se confirma, entonces recibo notificación push inmediata con detalles y próximos pasos.<br>
      <strong>Escenario 2: Recordatorio de check-in</strong><br>
      Dado que mi llegada es en 24 horas, cuando llega el momento, entonces recibo notificación con link directo para check-in digital.<br>
      <strong>Escenario 3: Actualización de servicios</strong><br>
      Dado que solicité room service, cuando cambia el estado, entonces recibo notificación con progreso actualizado (preparando, en camino, entregado).<br>
      <strong>Escenario 4: Configuración de preferencias</strong><br>
      Dado que quiero controlar notificaciones, cuando accedo a configuración, entonces puedo elegir qué tipos recibir y en qué horarios.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-35</td>
    <td>Notificaciones automáticas para staff</td>
    <td>Como staff del hotel, quiero recibir notificaciones automáticas sobre tareas asignadas y cambios operativos importantes.</td>
    <td>
      <strong>Escenario 1: Nueva tarea asignada</strong><br>
      Dado que administrador me asigna tarea, cuando se crea, entonces recibo notificación inmediata con detalles, prioridad y deadline.<br>
      <strong>Escenario 2: Cambio de prioridad</strong><br>
      Dado que una tarea cambia a prioridad alta, cuando se actualiza, entonces recibo notificación especial que requiere confirmación de lectura.<br>
      <strong>Escenario 3: Recordatorios de deadline</strong><br>
      Dado que tengo tarea pendiente, cuando se acerca el deadline, entonces recibo recordatorio 2 horas antes del vencimiento.<br>
      <strong>Escenario 4: Emergencias operativas</strong><br>
      Dado que hay emergencia (problema técnico, queja urgente), cuando se reporta, entonces todo el staff relevante recibe alerta inmediata.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-36</td>
    <td>Email marketing automatizado</td>
    <td>Como administrador, quiero enviar emails automáticos personalizados a huéspedes en diferentes etapas de su experiencia.</td>
    <td>
      <strong>Escenario 1: Email de bienvenida pre-llegada</strong><br>
      Dado que huésped confirma reserva, cuando pasan 24 horas, entonces recibe email con información del hotel, servicios disponibles y guía de llegada.<br>
      <strong>Escenario 2: Durante la estadía</strong><br>
      Dado que huésped está en el hotel por 2+ días, cuando es el segundo día, entonces recibe email con recomendaciones locales y servicios especiales.<br>
      <strong>Escenario 3: Post-estadía y fidelización</strong><br>
      Dado que huésped hace check-out, cuando pasa 1 semana, entonces recibe email de agradecimiento con oferta especial para próxima visita.<br>
      <strong>Escenario 4: Campañas segmentadas</strong><br>
      Dado que quiero hacer campaña específica, cuando selecciono criterios (huéspedes VIP, estacionalidad), entonces puedo enviar emails personalizados a ese segmento.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-37</td>
    <td>Alertas inteligentes y escalamiento</td>
    <td>Como administrador, quiero recibir alertas inteligentes sobre problemas operativos con escalamiento automático según gravedad.</td>
    <td>
      <strong>Escenario 1: Alerta de satisfacción baja</strong><br>
      Dado que huésped da calificación de 2 estrellas o menos, cuando envía evaluación, entonces recibo alerta inmediata para acción correctiva.<br>
      <strong>Escenario 2: Problema técnico crítico</strong><br>
      Dado que dispositivo IoT no responde por más de 10 minutos, cuando se detecta, entonces recibo alerta con información del problema y habitación afectada.<br>
      <strong>Escenario 3: Escalamiento automático</strong><br>
      Dado que alerta no se atiende en tiempo definido, cuando pasa el tiempo límite, entonces se escala automáticamente a supervisor o gerente general.<br>
      <strong>Escenario 4: Alertas de revenue management</strong><br>
      Dado que ocupación está muy por debajo de forecast, cuando se detecta tendencia, entonces recibo alerta con sugerencias de ajuste de precios.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-38</td>
    <td>Panel de comunicación unificado</td>
    <td>Como administrador, quiero un panel centralizado para gestionar todas las comunicaciones (email, WhatsApp, SMS, notificaciones) desde un solo lugar.</td>
    <td>
      <strong>Escenario 1: Vista unificada de conversaciones</strong><br>
      Dado que accedo al panel de comunicación, cuando se carga, entonces veo todas las conversaciones activas de diferentes canales en una sola interfaz.<br>
      <strong>Escenario 2: Respuesta desde panel central</strong><br>
      Dado que huésped envía mensaje por WhatsApp, cuando respondo desde el panel, entonces mi respuesta se envía por el canal original automáticamente.<br>
      <strong>Escenario 3: Historial unificado por huésped</strong><br>
      Dado que selecciono un huésped, cuando accedo a su perfil de comunicación, entonces veo todo el historial de interacciones sin importar el canal usado.<br>
      <strong>Escenario 4: Asignación de conversaciones</strong><br>
      Dado que llega consulta compleja, cuando la recibo, entonces puedo asignarla al staff especializado que recibirá notificación para responder.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-39</td>
    <td>App móvil nativa para staff</td>
    <td>Como staff del hotel, quiero una app móvil dedicada para gestionar mis tareas y comunicación mientras estoy en movimiento.</td>
    <td>
      <strong>Escenario 1: Lista de tareas móvil</strong><br>
      Dado que abro la app de staff, cuando se carga, entonces veo mis tareas pendientes organizadas por prioridad con información esencial.<br>
      <strong>Escenario 2: Actualizar estado de tarea</strong><br>
      Dado que completo una tarea, cuando la marco como terminada desde la app, entonces el cambio se sincroniza inmediatamente con el sistema central.<br>
      <strong>Escenario 3: Comunicación con administración</strong><br>
      Dado que tengo duda o problema, cuando uso chat en la app, entonces puedo comunicarme directamente con administración en tiempo real.<br>
      <strong>Escenario 4: Reporte de incidencias</strong><br>
      Dado que encuentro problema (habitación dañada, equipo descompuesto), cuando lo reporto desde la app, entonces se crea ticket automático con foto y ubicación.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-40</td>
    <td>Backup y recuperación de datos</td>
    <td>Como administrador técnico, quiero que el sistema tenga backup automático y recuperación de desastres para garantizar continuidad operativa.</td>
    <td>
      <strong>Escenario 1: Backup automático diario</strong><br>
      Dado que termina cada día operativo, cuando llega la medianoche, entonces el sistema crea backup completo de datos y lo almacena en ubicación segura.<br>
      <strong>Escenario 2: Verificación de integridad</strong><br>
      Dado que se crea backup, cuando se completa, entonces el sistema verifica automáticamente la integridad de los datos respaldados.<br>
      <strong>Escenario 3: Recuperación de emergencia</strong><br>
      Dado que hay falla crítica del sistema, cuando inicio proceso de recuperación, entonces puedo restaurar operación desde el backup más reciente en menos de 2 horas.<br>
      <strong>Escenario 4: Notificación de problemas</strong><br>
      Dado que falla el proceso de backup, cuando se detecta el error, entonces administradores técnicos reciben alerta inmediata para investigación.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-41</td>
    <td>Monitoreo y logs del sistema</td>
    <td>Como administrador técnico, quiero monitorear el performance del sistema y acceder a logs detallados para troubleshooting.</td>
    <td>
      <strong>Escenario 1: Dashboard de performance</strong><br>
      Dado que accedo a monitoreo, cuando se carga, entonces veo métricas clave (tiempo respuesta, uso CPU/memoria, requests por minuto, errores).<br>
      <strong>Escenario 2: Alertas de performance</strong><br>
      Dado que tiempo de respuesta supera 3 segundos, cuando se detecta, entonces recibo alerta automática con detalles del problema.<br>
      <strong>Escenario 3: Logs centralizados</strong><br>
      Dado que necesito investigar problema, cuando accedo a logs, entonces puedo filtrar por fecha, usuario, acción y nivel de error.<br>
      <strong>Escenario 4: Análisis de tendencias</strong><br>
      Dado que quiero optimizar performance, cuando reviso métricas históricas, entonces puedo identificar patrones y cuellos de botella.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-42</td>
    <td>Configuración multi-hotel para cadenas</td>
    <td>Como administrador de cadena hotelera, quiero gestionar múltiples propiedades desde una cuenta maestra con configuraciones independientes.</td>
    <td>
      <strong>Escenario 1: Vista consolidada de cadena</strong><br>
      Dado que administro múltiples hoteles, cuando accedo al panel master, entonces veo KPIs consolidados de toda la cadena con drill-down por propiedad.<br>
      <strong>Escenario 2: Configuración por propiedad</strong><br>
      Dado que cada hotel es diferente, cuando configuro uno específico, entonces puedo personalizar servicios, precios y operación sin afectar otros.<br>
      <strong>Escenario 3: Staff compartido entre propiedades</strong><br>
      Dado que tengo staff que trabaja en múltiples hoteles, cuando lo asigno, entonces puede acceder a las propiedades correspondientes con permisos específicos.<br>
      <strong>Escenario 4: Reportes consolidados</strong><br>
      Dado que necesito análisis de cadena, cuando genero reportes, entonces puedo ver métricas individuales y comparativas entre todas mis propiedades.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-43</td>
    <td>Integración con sistemas PMS existentes</td>
    <td>Como administrador, quiero integrar Smart Stay con mi sistema PMS actual para migrar gradualmente sin interrumpir operaciones.</td>
    <td>
      <strong>Escenario 1: Sincronización bidireccional</strong><br>
      Dado que tengo PMS existente, cuando configuro integración, entonces las reservas se sincronizan automáticamente en ambas direcciones.<br>
      <strong>Escenario 2: Migración gradual de funcionalidades</strong><br>
      Dado que quiero adoptar Smart Stay progresivamente, cuando habilito módulos específicos, entonces pueden coexistir con mi PMS actual.<br>
      <strong>Escenario 3: Validación de consistencia</strong><br>
      Dado que tengo datos en ambos sistemas, cuando se sincroniza, entonces recibo alertas si hay discrepancias que requieren resolución manual.<br>
      <strong>Escenario 4: Backup de transición</strong><br>
      Dado que estoy migrando, cuando completo la transición, entonces puedo mantener acceso de solo lectura al PMS anterior por período de gracia.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-44</td>
    <td>Personalización de marca por hotel</td>
    <td>Como administrador, quiero personalizar la interfaz y comunicaciones con la marca de mi hotel para mantener consistencia visual.</td>
    <td>
      <strong>Escenario 1: Customización de colores y logo</strong><br>
      Dado que quiero personalizar apariencia, cuando subo mi logo y defino colores, entonces toda la interfaz (web y app) se actualiza con mi branding.<br>
      <strong>Escenario 2: Emails con marca personalizada</strong><br>
      Dado que se envían comunicaciones automáticas, cuando llegan al huésped, entonces incluyen mi logo, colores y mensaje personalizado del hotel.<br>
      <strong>Escenario 3: Landing page personalizada</strong><br>
      Dado que huéspedes acceden a servicios digitales, cuando llegan a la página, entonces ven interfaz completamente branded con mi hotel.<br>
      <strong>Escenario 4: Configuración de mensajes</strong><br>
      Dado que quiero personalizar comunicación, cuando configuro templates, entonces puedo adaptar todos los mensajes automáticos al tono de mi marca.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-45</td>
    <td>Programa de fidelización integrado</td>
    <td>Como administrador, quiero gestionar un programa de fidelización para huéspedes recurrentes con beneficios automáticos.</td>
    <td>
      <strong>Escenario 1: Acumulación automática de puntos</strong><br>
      Dado que huésped completa estadía, cuando hace check-out, entonces acumula puntos automáticamente basados en gasto total y duración.<br>
      <strong>Escenario 2: Beneficios por nivel</strong><br>
      Dado que huésped alcanza nivel VIP, cuando hace nueva reserva, entonces recibe automáticamente beneficios (upgrade, late checkout, amenities).<br>
      <strong>Escenario 3: Ofertas personalizadas</strong><br>
      Dado el historial del huésped, cuando está próximo a viajar, entonces recibe ofertas especiales basadas en sus preferencias y fechas típicas.<br>
      <strong>Escenario 4: Redención de beneficios</strong><br>
      Dado que huésped tiene puntos suficientes, cuando quiere redimir, entonces puede canjear por servicios, upgrades o noches gratuitas desde la app.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-46</td>
    <td>Gestión de eventos y conferencias</td>
    <td>Como administrador, quiero gestionar eventos especiales y conferencias con funcionalidades específicas para grupos.</td>
    <td>
      <strong>Escenario 1: Crear evento grupal</strong><br>
      Dado que recibo solicitud de evento, cuando creo el evento, entonces puedo definir tarifas especiales, bloquear habitaciones y asignar servicios específicos.<br>
      <strong>Escenario 2: Check-in masivo</strong><br>
      Dado que llegan participantes del evento, cuando inician check-in, entonces pueden usar código especial para proceso acelerado con datos pre-cargados.<br>
      <strong>Escenario 3: Comunicación grupal</strong><br>
      Dado que tengo evento activo, cuando necesito comunicar algo, entonces puedo enviar mensajes masivos solo a participantes del evento específico.<br>
      <strong>Escenario 4: Facturación consolidada</strong><br>
      Dado que el evento termina, cuando genero facturación, entonces puedo crear factura master para organizador o facturas individuales según configuración.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-47</td>
    <td>Mantenimiento predictivo IoT</td>
    <td>Como administrador, quiero que el sistema IoT prediga necesidades de mantenimiento basado en uso y performance de equipos.</td>
    <td>
      <strong>Escenario 1: Monitoreo continuo de equipos</strong><br>
      Dado que tengo dispositivos IoT instalados, cuando funcionan, entonces el sistema monitorea continuamente performance, consumo y patrones de uso.<br>
      <strong>Escenario 2: Alertas predictivas</strong><br>
      Dado que un equipo muestra signos de degradación, cuando se detecta anomalía, entonces recibo alerta con recomendación de mantenimiento preventivo.<br>
      <strong>Escenario 3: Programación automática</strong><br>
      Dado que se requiere mantenimiento, cuando acepto recomendación, entonces se programa automáticamente con equipo técnico y se bloquea la habitación.<br>
      <strong>Escenario 4: Historial de performance</strong><br>
      Dado que quiero analizar equipos, cuando accedo a métricas, entonces veo historial completo de performance y todos los mantenimientos realizados.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-48</td>
    <td>Análisis de competencia y pricing dinámico</td>
    <td>Como administrador, quiero analizar precios de competencia y ajustar mis tarifas automáticamente para optimizar revenue.</td>
    <td>
      <strong>Escenario 1: Monitoreo de precios competencia</strong><br>
      Dado que configuro hoteles competidores, cuando el sistema analiza precios, entonces veo comparativa diaria de tarifas en mi área geográfica.<br>
      <strong>Escenario 2: Sugerencias de pricing</strong><br>
      Dado que hay cambios en competencia, cuando se detectan, entonces recibo sugerencias de ajuste de precios basadas en ocupación y demand forecast.<br>
      <strong>Escenario 3: Ajuste automático de tarifas</strong><br>
      Dado que habilito pricing dinámico, cuando se cumplen condiciones definidas, entonces el sistema ajusta automáticamente precios dentro de rangos configurados.<br>
      <strong>Escenario 4: Análisis de elasticidad</strong><br>
      Dado que tengo historial de cambios de precio, cuando genero análisis, entonces veo impacto de ajustes en ocupación y revenue total.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-49</td>
    <td>Compliance y auditoría automatizada</td>
    <td>Como administrador, quiero que el sistema genere reportes automáticos de compliance y facilite auditorías regulatorias.</td>
    <td>
      <strong>Escenario 1: Reportes regulatorios automáticos</strong><br>
      Dado que debo cumplir regulaciones locales, cuando termine el período, entonces el sistema genera automáticamente reportes requeridos por autoridades.<br>
      <strong>Escenario 2: Trazabilidad completa</strong><br>
      Dado que necesito auditoría, cuando exporto datos, entonces obtengo trazabilidad completa de todas las transacciones y cambios con timestamps.<br>
      <strong>Escenario 3: Validación de datos fiscales</strong><br>
      Dado que proceso pagos, cuando se registran, entonces el sistema valida automáticamente que cumplen requisitos fiscales locales.<br>
      <strong>Escenario 4: Archivo digital organizado</strong><br>
      Dado que almaceno documentos, cuando los necesito para auditoría, entonces están organizados automáticamente por período, tipo y huésped con búsqueda rápida.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-50</td>
    <td>Integración con sistemas de seguridad</td>
    <td>Como administrador, quiero integrar Smart Stay con sistemas de seguridad del hotel para gestión automatizada de accesos.</td>
    <td>
      <strong>Escenario 1: Generación automática de códigos de acceso</strong><br>
      Dado que huésped completa check-in digital, cuando se confirma, entonces el sistema genera automáticamente código único para su habitación con validez específica.<br>
      <strong>Escenario 2: Revocación automática post check-out</strong><br>
      Dado que huésped hace check-out, cuando se completa, entonces todos los códigos de acceso se revocan automáticamente en sistemas de seguridad.<br>
      <strong>Escenario 3: Accesos temporales para staff</strong><br>
      Dado que staff necesita acceso para limpieza/mantenimiento, cuando se asigna tarea, entonces recibe código temporal válido solo durante su turno de trabajo.<br>
      <strong>Escenario 4: Log de accesos y alertas</strong><br>
      Dado que se usa cualquier código de acceso, cuando ocurre, entonces se registra en log central y se generan alertas por accesos fuera de horarios normales.
    </td>
    <td>EP-05</td>
  </tr>
</table>



## 3.2. Impact Mapping.

![ImpactMapping.jpeg](assets/ImpactMapping.jpeg)

## 3.3. Product Backlog.

| #Orden | ID   | User Story / Technical Story                                             | Story Points |
| ------ | ---- | ------------------------------------------------------------------------ | ------------ |
| 01     | US01 | Registro de huésped                                                      | 5            |
| 02     | US02 | Inicio de sesión seguro                                                  | 5            |
| 03     | US03 | Recuperación de contraseña                                               | 3            |
| 04     | US04 | Edición de perfil personal                                               | 3            |
| 05     | TS01 | Conectar formularios de registro/login con validaciones en frontend      | 8            |
| 06     | US05 | Registro de anfitrión                                                    | 5            |
| 07     | US06 | Verificación de identidad básica                                         | 3            |
| 08     | US07 | Configuración de datos de contacto                                       | 3            |
| 09     | US08 | Edición de perfil de anfitrión                                           | 3            |
| 10     | TS02 | Validar campos de formulario en frontend (correo, contraseña, documento) | 8            |
| 11     | US09 | Registrar nueva propiedad                                                | 5            |
| 12     | US10 | Subir fotos de la propiedad                                              | 5            |
| 13     | US11 | Editar información de la propiedad                                       | 3            |
| 14     | US12 | Eliminar propiedad                                                       | 3            |
| 15     | US13 | Buscar propiedades por ubicación                                         | 5            |
| 16     | US14 | Filtrar por precio y fechas                                              | 5            |
| 17     | US15 | Reservar una propiedad                                                   | 8            |
| 18     | US16 | Ver historial de reservas                                                | 3            |
| 19     | TS03 | Crear buscador y filtros en frontend                                     | 8            |
| 20     | TS04 | Simular reservas con estado guardado en frontend                         | 5            |
| 21     | US17 | Realizar pago en línea                                                   | 8            |
| 22     | US18 | Consultar historial de pagos                                             | 3            |
| 23     | US19 | Descargar comprobante de pago                                            | 3            |
| 24     | TS05 | Simular integración de pago                                              | 8            |
| 25     | US20 | Dejar reseña de una estancia                                             | 5            |
| 26     | US21 | Calificar anfitrión o huésped                                            | 3            |
| 27     | US22 | Ver reseñas de una propiedad                                             | 3            |
| 28     | TS06 | Formulario de reseñas conectado a la UI, guardado simulado en frontend   | 5            |
| 29     | US23 | Acceder a preguntas frecuentes                                           | 3            |
| 30     | US24 | Enviar reporte de problema                                               | 3            |
| 31     | US25 | Contactar con soporte técnico                                            | 5            |
| 32     | TS07 | Implementar formulario de contacto y sección de preguntas frecuentes     | 8            |
| 33     | US26 | Ver información general sobre SmartStay                                  | 3            |
| 34     | US27 | Conocer beneficios de usar la plataforma                                 | 3            |
| 35     | US28 | Acceder fácilmente al registro o login                                   | 5            |
| 36     | TS08 | Implementar landing page con botones hacia login/registro                | 5            |


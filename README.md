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
    <th>Title</th>
    <th>Description</th>
    <th>Acceptance Criteria</th>
    <th>Related to (Epic ID)</th>
  </tr>

  <!-- EPICS -->
  <tr>
    <td><strong>EP-01</strong></td>
    <td><strong>Authentication and User Management</strong></td>
    <td>Epic that groups functionalities for registration, login, profile management, and role-based access control for all user types (administrators, staff, guests).</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-02</strong></td>
    <td><strong>Central Hotel Management</strong></td>
    <td>Epic that includes reservation administration, room management, digital check-in/check-out, daily operational management, and internal service coordination.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-03</strong></td>
    <td><strong>Guest Digital Experience</strong></td>
    <td>Epic focused on guest experience: IoT environmental control, personalized services, digital communication, and post-stay evaluation.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-04</strong></td>
    <td><strong>Analytics and Reporting</strong></td>
    <td>Epic covering management dashboard, occupancy reports, operational KPIs, satisfaction analysis, and financial metrics.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-05</strong></td>
    <td><strong>Integrations and External Channels</strong></td>
    <td>Epic for connections with OTAs, WhatsApp, payment systems, digital reputation, and third-party webhooks.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-06</strong></td>
    <td><strong>Landing Page and Digital Marketing</strong></td>
    <td>Epic for the static website with segment-specific information, success stories, simulators, and commercial contact channels.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-07</strong></td>
    <td><strong>RESTful API and Technical Services</strong></td>
    <td>Epic including endpoints, API authentication, technical documentation, monitoring, and external system integration.</td>
    <td></td>
    <td>-</td>
  </tr>
  <tr>
    <td><strong>EP-08</strong></td>
    <td><strong>Notifications and Communication</strong></td>
    <td>Epic for push notification system, email, SMS, automatic alerts, and staff-guest communication.</td>
    <td></td>
    <td>-</td>
  </tr>

  <!-- USER STORIES -->
  <tr>
    <td>US-01</td>
    <td>User registration with validation</td>
    <td>As a new user, I want to register in Smart Stay by validating my email to access functionalities according to my role.</td>
    <td>
      <strong>Scenario 1: Successful registration</strong><br>
      Given I am a new user with valid data, when I complete the registration form, then my account is created correctly and I receive email confirmation.<br>
      <strong>Scenario 2: Email already registered</strong><br>
      Given I attempt to register with an existing email, when I submit the form, then the system shows "Email already registered" message and suggests password recovery.<br>
      <strong>Scenario 3: Incomplete data</strong><br>
      Given I leave mandatory fields empty, when I try to register, then the system highlights missing fields and doesn't allow continuation.<br>
      <strong>Scenario 4: Email format validation</strong><br>
      Given I enter an invalid email format, when I submit the form, then the system shows format error.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-02</td>
    <td>Secure login</td>
    <td>As a registered user, I want to login securely to access my personalized dashboard according to my role.</td>
    <td>
      <strong>Scenario 1: Correct login</strong><br>
      Given I have valid credentials, when I login, then I access my corresponding dashboard (admin/guest/staff).<br>
      <strong>Scenario 2: Incorrect credentials</strong><br>
      Given I enter incorrect data, when I try to access, then I receive error message without revealing whether the problem is email or password.<br>
      <strong>Scenario 3: Blocked account</strong><br>
      Given login failed 5 consecutive times, when I try again, then the account is temporarily blocked and I receive notification.<br>
      <strong>Scenario 4: Persistent session</strong><br>
      Given I check "remember me", when I close and open the browser, then I remain logged in until I manually logout.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-03</td>
    <td>Profile and role management</td>
    <td>As an administrator, I want to manage users, assign roles and permissions to control access to different functionalities.</td>
    <td>
      <strong>Scenario 1: Create staff user</strong><br>
      Given I am admin, when I create a staff user, then I can assign specific permissions (housekeeping, front desk, maintenance).<br>
      <strong>Scenario 2: Modify permissions</strong><br>
      Given there is a staff user, when I change their permissions, then their access is updated immediately.<br>
      <strong>Scenario 3: Deactivate user</strong><br>
      Given I need to deactivate a user, when I do so, then they lose access but their history is maintained.<br>
      <strong>Scenario 4: Access audit</strong><br>
      Given I need to review activity, when I consult logs, then I see date, time, user and action performed.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-04</td>
    <td>Password recovery</td>
    <td>As a user, I want to recover my password via email to regain access to my account.</td>
    <td>
      <strong>Scenario 1: Valid request</strong><br>
      Given I request password recovery with registered email, when I send the request, then I receive reset link via email.<br>
      <strong>Scenario 2: Unregistered email</strong><br>
      Given I request with unregistered email, when I send request, then I receive generic message without revealing if email exists.<br>
      <strong>Scenario 3: Expired link</strong><br>
      Given the reset link is older than 30 minutes, when I try to use it, then it expires and I must request a new one.<br>
      <strong>Scenario 4: Successful change</strong><br>
      Given I have valid link, when I set new password, then it updates and I receive confirmation.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-05</td>
    <td>Administrator dashboard</td>
    <td>As an administrator, I want a centralized panel with key information to manage my hotel efficiently.</td>
    <td>
      <strong>Scenario 1: General view</strong><br>
      Given I access the dashboard, when it loads, then I see current occupancy, daily check-ins/outs, pending tasks and important alerts.<br>
      <strong>Scenario 2: Date filters</strong><br>
      Given I want to review specific period, when I select date range, then all indicators update.<br>
      <strong>Scenario 3: Quick access</strong><br>
      Given I'm on the dashboard, when I click any metric, then I navigate to corresponding detailed section.<br>
      <strong>Scenario 4: Real-time updates</strong><br>
      Given there are operational changes, when they occur, then the dashboard updates automatically without reloading the page.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-06</td>
    <td>Room and status management</td>
    <td>As an administrator, I want to manage all room statuses to optimize daily operations.</td>
    <td>
      <strong>Scenario 1: Change room status</strong><br>
      Given I select a room, when I change its status (available/occupied/cleaning/maintenance), then it updates immediately and notifies corresponding staff.<br>
      <strong>Scenario 2: Room map view</strong><br>
      Given I access room map, when it loads, then I see all statuses with color codes and can make quick changes.<br>
      <strong>Scenario 3: Change history</strong><br>
      Given I need to review changes, when I consult room history, then I see all status changes with date, time and responsible user.<br>
      <strong>Scenario 4: Automatic alerts</strong><br>
      Given a room is in maintenance for more than 24 hours, when time passes, then I receive automatic alert.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-07</td>
    <td>Centralized reservation management</td>
    <td>As an administrator, I want to manage all reservations in one place to avoid overbooking and optimize occupancy.</td>
    <td>
      <strong>Scenario 1: Reservation calendar view</strong><br>
      Given I access reservations, when I select calendar view, then I see all reservations organized by date with key information (guest, room, status).<br>
      <strong>Scenario 2: Create manual reservation</strong><br>
      Given I receive phone reservation, when I enter it manually, then the system validates availability and confirms reservation.<br>
      <strong>Scenario 3: Modify existing reservation</strong><br>
      Given I need to change a reservation, when I edit it, then the system validates new availability and notifies the guest.<br>
      <strong>Scenario 4: Cancellation with policies</strong><br>
      Given a reservation is cancelled, when I process cancellation, then the system applies cancellation policies and releases the room.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-08</td>
    <td>Automated digital check-in</td>
    <td>As an administrator and guest, I want check-in to be performed digitally in less than 3 minutes to improve experience.</td>
    <td>
      <strong>Scenario 1: Successful guest check-in</strong><br>
      Given the guest initiates digital check-in, when they complete their data and confirmation, then they receive digital access to their room and access code.<br>
      <strong>Scenario 2: Document validation</strong><br>
      Given the guest uploads ID documents, when the system processes them, then it validates automatically and approves check-in.<br>
      <strong>Scenario 3: Assisted check-in</strong><br>
      Given the guest has difficulties, when they request help, then staff receives notification and can assist remotely.<br>
      <strong>Scenario 4: Automatic notification</strong><br>
      Given check-in is completed, when confirmed, then housekeeping receives notification of occupied room and admin sees updated status.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-09</td>
    <td>Digital check-out and billing</td>
    <td>As a guest, I want to perform digital check-out and receive my invoice automatically to expedite my departure.</td>
    <td>
      <strong>Scenario 1: Successful check-out</strong><br>
      Given I start check-out from the app, when I confirm departure and review charges, then my room is released and I receive invoice via email.<br>
      <strong>Scenario 2: Additional charges</strong><br>
      Given I have pending consumption, when I check-out, then I see charge details and can approve payment.<br>
      <strong>Scenario 3: Late check-out</strong><br>
      Given my check-out is after deadline, when I process it, then corresponding charge is applied and notified.<br>
      <strong>Scenario 4: Housekeeping notification</strong><br>
      Given I complete check-out, when confirmed, then housekeeping receives automatic cleaning task for that room.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-10</td>
    <td>Staff task assignment and tracking</td>
    <td>As an administrator, I want to assign tasks to staff and track their progress to optimize operations.</td>
    <td>
      <strong>Scenario 1: Assign housekeeping task</strong><br>
      Given a room needs cleaning, when I assign the task, then staff receives immediate notification with details and priority.<br>
      <strong>Scenario 2: Progress update</strong><br>
      Given staff starts a task, when they mark it as "in progress", then admin sees real-time update.<br>
      <strong>Scenario 3: Complete task</strong><br>
      Given staff finishes a task, when they mark it as completed, then admin receives notification and can validate work.<br>
      <strong>Scenario 4: Overdue tasks</strong><br>
      Given a task isn't completed within expected time, when deadline passes, then automatic alert is generated.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-11</td>
    <td>IoT environmental control from mobile app</td>
    <td>As a guest, I want to control temperature, lighting and other environmental aspects from my smartphone to personalize my experience.</td>
    <td>
      <strong>Scenario 1: Temperature adjustment</strong><br>
      Given I'm in my room, when I change temperature from the app, then the IoT system adjusts climate in less than 30 seconds.<br>
      <strong>Scenario 2: Lighting control</strong><br>
      Given I want to adjust lights, when I use app controls, then I can change intensity, color and turn on/off specific lights.<br>
      <strong>Scenario 3: Blind configuration</strong><br>
      Given I want to control natural light, when I adjust blinds from app, then they open/close automatically to selected percentage.<br>
      <strong>Scenario 4: Personalized presets</strong><br>
      Given I want quick configurations, when I save a preset (e.g., "rest", "work"), then I can activate multiple settings with one touch.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-12</td>
    <td>Service requests from app</td>
    <td>As a guest, I want to request room service, additional cleaning and other services from my smartphone conveniently.</td>
    <td>
      <strong>Scenario 1: Request room service</strong><br>
      Given I want to order food, when I access menu in app, then I can select products, customize and confirm order with estimated time.<br>
      <strong>Scenario 2: Additional cleaning service</strong><br>
      Given I need extra cleaning, when I request it, then I can choose preferred time and staff receives request immediately.<br>
      <strong>Scenario 3: Request tracking</strong><br>
      Given I made an order, when I check status, then I see real-time progress (received, preparing, on way, delivered).<br>
      <strong>Scenario 4: Special services</strong><br>
      Given I need special services (transport, tour, reservations), when I request them, then staff receives notification for personalized coordination.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-13</td>
    <td>Digital guest-staff communication</td>
    <td>As a guest, I want to communicate with hotel staff digitally to resolve questions and requests quickly.</td>
    <td>
      <strong>Scenario 1: Real-time chat</strong><br>
      Given I have a question, when I start chat from app, then I connect with available staff and receive response in less than 5 minutes.<br>
      <strong>Scenario 2: Specific requests</strong><br>
      Given I need something specific, when I send detailed message, then corresponding staff receives request and can coordinate attention.<br>
      <strong>Scenario 3: Conversation history</strong><br>
      Given I've had several conversations, when I access history, then I can review all interactions from my stay.<br>
      <strong>Scenario 4: Automatic escalation</strong><br>
      Given my request isn't resolved in reasonable time, when time limit passes, then it's automatically escalated to a supervisor.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-14</td>
    <td>Experience personalization based on preferences</td>
    <td>As a guest, I want the system to learn my preferences to offer personalized experiences and services.</td>
    <td>
      <strong>Scenario 1: Initial preference setup</strong><br>
      Given it's my first stay, when I complete preference profile, then the system configures room according to my tastes before arrival.<br>
      <strong>Scenario 2: Automatic learning</strong><br>
      Given I've used the system several times, when I return, then the system automatically suggests services and configurations based on my history.<br>
      <strong>Scenario 3: Personalized recommendations</strong><br>
      Given my taste profile, when I'm at the hotel, then I receive restaurant, activity and service recommendations aligned with my interests.<br>
      <strong>Scenario 4: Exclusive offers</strong><br>
      Given I'm a recurring guest, when I check the app, then I see personalized offers and upgrades based on my history and loyalty.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-15</td>
    <td>Post-stay evaluation and feedback</td>
    <td>As a guest, I want to evaluate my experience and leave feedback to help the hotel improve its services.</td>
    <td>
      <strong>Scenario 1: Automatic evaluation</strong><br>
      Given I complete my check-out, when 2 hours pass, then I receive automatic invitation to evaluate my stay with simple form.<br>
      <strong>Scenario 2: Detailed feedback</strong><br>
      Given I want to give specific opinion, when I access extended evaluation, then I can rate individual aspects and leave comments.<br>
      <strong>Scenario 3: Negative feedback follow-up</strong><br>
      Given I leave low rating, when I send evaluation, then hotel receives immediate alert and can contact me to resolve the problem.<br>
      <strong>Scenario 4: Feedback incentives</strong><br>
      Given I complete evaluation, when I send it, then I receive benefit for next stay (discount, upgrade, free service).
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-16</td>
    <td>Analytics dashboard and operational KPIs</td>
    <td>As an administrator, I want to visualize key metrics and KPIs to make informed decisions about hotel operations.</td>
    <td>
      <strong>Scenario 1: Real-time metrics</strong><br>
      Given I access analytics dashboard, when it loads, then I see current occupancy, daily revenue, completed tasks and average satisfaction.<br>
      <strong>Scenario 2: Historical comparisons</strong><br>
      Given I want to analyze trends, when I select compare periods, then I see comparative charts of occupancy, revenue and operations.<br>
      <strong>Scenario 3: Metric drill-down</strong><br>
      Given I see an interesting metric, when I click on it, then I can explore detailed data and filter by room, date or service.<br>
      <strong>Scenario 4: Intelligent alerts</strong><br>
      Given there are negative trends, when system detects them, then I receive automatic alerts with action suggestions.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-17</td>
    <td>Financial and occupancy reports</td>
    <td>As an administrator, I want to generate financial and occupancy reports for management analysis and decision making.</td>
    <td>
      <strong>Scenario 1: Automated daily report</strong><br>
      Given the operational day ends, when midnight passes, then system automatically generates daily report with revenue, occupancy and incidents.<br>
      <strong>Scenario 2: Custom report</strong><br>
      Given I need specific analysis, when I configure parameters (dates, metrics, filters), then I generate customized report in PDF or Excel.<br>
      <strong>Scenario 3: Forecasting and projections</strong><br>
      Given historical data, when I access projections, then I see occupancy and revenue forecasting based on trends and confirmed reservations.<br>
      <strong>Scenario 4: Competitive benchmarking</strong><br>
      Given I have market data, when I generate comparative report, then I see my performance versus local competition in key metrics.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-18</td>
    <td>Guest satisfaction analysis</td>
    <td>As an administrator, I want to analyze guest satisfaction to identify improvement areas and maintain service quality.</td>
    <td>
      <strong>Scenario 1: Satisfaction dashboard</strong><br>
      Given I access satisfaction analysis, when it loads, then I see average NPS, rating distribution and recent comments.<br>
      <strong>Scenario 2: Category analysis</strong><br>
      Given I want to understand specific problems, when I filter by aspect (cleanliness, service, comfort), then I see detailed ratings by area.<br>
      <strong>Scenario 3: Temporal trends</strong><br>
      Given I want to see evolution, when I select temporal view, then I see how satisfaction has changed over time.<br>
      <strong>Scenario 4: Corrective actions</strong><br>
      Given I identify recurring problem, when I mark it for action, then automatic task is created for responsible department.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-19</td>
    <td>IoT energy consumption monitoring</td>
    <td>As an administrator, I want to monitor energy consumption of rooms and common areas to optimize operational costs.</td>
    <td>
      <strong>Scenario 1: Real-time consumption dashboard</strong><br>
      Given I access energy monitoring, when it loads, then I see current consumption by room, common area and main equipment.<br>
      <strong>Scenario 2: Excessive consumption alerts</strong><br>
      Given a room exceeds normal consumption, when it passes threshold, then I receive immediate alert with option to investigate or adjust remotely.<br>
      <strong>Scenario 3: Automatic optimization</strong><br>
      Given a room is unoccupied, when 30 minutes pass without activity, then system automatically adjusts temperature and lights to eco mode.<br>
      <strong>Scenario 4: Savings reports</strong><br>
      Given optimizations are implemented, when I generate monthly report, then I see consumption comparison and achieved savings versus previous period.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-20</td>
    <td>OTA and booking channel integration</td>
    <td>As an administrator, I want to integrate my inventory with Booking.com, Expedia and other OTAs to maximize occupancy and avoid overbooking.</td>
    <td>
      <strong>Scenario 1: Automatic availability synchronization</strong><br>
      Given I change availability in Smart Stay, when I update, then all connected channels synchronize automatically in less than 5 minutes.<br>
      <strong>Scenario 2: Automatic reservation import</strong><br>
      Given I receive OTA reservation, when confirmed, then it's automatically imported to Smart Stay with all guest information.<br>
      <strong>Scenario 3: Centralized price management</strong><br>
      Given I want to change rates, when I update them in Smart Stay, then they automatically propagate to all configured channels.<br>
      <strong>Scenario 4: Conflict resolution</strong><br>
      Given there's discrepancy between channels, when system detects it, then it notifies me immediately and suggests actions to resolve conflict.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-21</td>
    <td>WhatsApp Business integration</td>
    <td>As an administrator, I want to use WhatsApp Business for direct guest communication and pre/post-stay query management.</td>
    <td>
      <strong>Scenario 1: Automatic welcome messages</strong><br>
      Given a guest confirms reservation, when registered, then they receive automatic WhatsApp message with arrival information and contact.<br>
      <strong>Scenario 2: Pre-arrival queries</strong><br>
      Given guest sends WhatsApp query, when message arrives, then staff receives Smart Stay notification and can respond from platform.<br>
      <strong>Scenario 3: Service confirmations</strong><br>
      Given guest requests service via WhatsApp, when processed, then they receive automatic confirmation with details and estimated time.<br>
      <strong>Scenario 4: Post-stay follow-up</strong><br>
      Given guest checks out, when 1 day passes, then they receive automatic thank you message and invitation to evaluate experience.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-22</td>
    <td>Digital reputation management</td>
    <td>As an administrator, I want to manage Google, TripAdvisor and OTA reviews from one place to maintain good online reputation.</td>
    <td>
      <strong>Scenario 1: Review consolidation</strong><br>
      Given I access reputation management, when it loads, then I see all reviews from different platforms in one dashboard.<br>
      <strong>Scenario 2: Centralized response</strong><br>
      Given I want to respond to a review, when I write response, then I can publish it automatically on corresponding platform.<br>
      <strong>Scenario 3: Negative review alerts</strong><br>
      Given I receive 3-star or less review, when published, then I receive immediate alert for quick response.<br>
      <strong>Scenario 4: Sentiment analysis</strong><br>
      Given I have multiple reviews, when I access analysis, then I see satisfaction trends, frequent keywords and identified improvement areas.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-23</td>
    <td>Digital payment processing</td>
    <td>As an administrator and guest, I want to process payments securely and efficiently through multiple payment methods.</td>
    <td>
      <strong>Scenario 1: Card payment at check-in</strong><br>
      Given guest performs digital check-in, when they enter card data, then secure pre-authorization is processed and registration confirmed.<br>
      <strong>Scenario 2: Additional service payment</strong><br>
      Given guest requests room service, when they confirm order, then they can pay immediately through app with saved method.<br>
      <strong>Scenario 3: Automatic check-out billing</strong><br>
      Given guest checks out, when they confirm final charges, then automatic payment is processed and they receive digital invoice.<br>
      <strong>Scenario 4: Failed payment handling</strong><br>
      Given a payment fails, when error occurs, then guest receives immediate notification with alternative payment options.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-24</td>
    <td>Segmented landing page</td>
    <td>As a visitor, I want to find specific information according to my profile (hotel administrator or guest) to understand Smart Stay's value.</td>
    <td>
      <strong>Scenario 1: Administrator information</strong><br>
      Given I'm a hotel administrator visiting the page, when I navigate the hotels section, then I see operational benefits, ROI, success stories and specific demo.<br>
      <strong>Scenario 2: Guest information</strong><br>
      Given I'm a traveler visiting the page, when I navigate the guests section, then I see experience benefits, comfort and technology.<br>
      <strong>Scenario 3: Intuitive navigation</strong><br>
      Given I arrive at landing, when it loads, then I can easily identify my profile and navigate to relevant information in less than 3 clicks.<br>
      <strong>Scenario 4: Clear calls to action</strong><br>
      Given I'm interested, when I look for next step, then I find clear CTAs (request demo, contact sales, download app).
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-25</td>
    <td>ROI simulator for hotels</td>
    <td>As a visiting hotel administrator, I want to use a simulator to estimate the return on investment I would get with Smart Stay.</td>
    <td>
      <strong>Scenario 1: Basic ROI calculation</strong><br>
      Given I enter basic data (number of rooms, average occupancy), when I run simulation, then I see estimated annual savings and recovery time.<br>
      <strong>Scenario 2: Hotel type personalization</strong><br>
      Given I select my hotel type (boutique, chain, resort), when I use simulator, then calculations adjust to my segment averages.<br>
      <strong>Scenario 3: Current situation comparison</strong><br>
      Given I enter current operational costs, when I generate report, then I see clear comparison between my current operation and with Smart Stay.<br>
      <strong>Scenario 4: Export results</strong><br>
      Given I complete simulation, when I want to save results, then I can export PDF report to share with my team.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-26</td>
    <td>Success stories and testimonials</td>
    <td>As an interested visitor, I want to see real success stories from hotels using Smart Stay to validate solution effectiveness.</td>
    <td>
      <strong>Scenario 1: Video testimonials</strong><br>
      Given I access success stories, when I navigate the section, then I can see videos of real administrators sharing their experience with specific metrics.<br>
      <strong>Scenario 2: Improvement metrics</strong><br>
      Given I read a success story, when I review details, then I see specific improvement data (% cost reduction, % satisfaction increase, time saved).<br>
      <strong>Scenario 3: Stories by hotel type</strong><br>
      Given I look for references, when I filter by hotel type similar to mine, then I see relevant cases for my specific situation.<br>
      <strong>Scenario 4: Direct contact with cases</strong><br>
      Given I'm interested in a specific case, when I request more information, then I can connect directly with the hotel for references.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-27</td>
    <td>Demo request and commercial contact</td>
    <td>As an interested visitor, I want to request a demonstration and contact the sales team easily and quickly.</td>
    <td>
      <strong>Scenario 1: Demo request form</strong><br>
      Given I want to see a demo, when I complete the form, then I receive immediate confirmation and team contact within 24 hours.<br>
      <strong>Scenario 2: Automatic scheduling</strong><br>
      Given I request demo, when I submit form, then I can schedule appointment directly on available sales team calendar.<br>
      <strong>Scenario 3: Accessible contact information</strong><br>
      Given I prefer direct contact, when I look for information, then I easily find phone, email and WhatsApp of sales team.<br>
      <strong>Scenario 4: Automatic follow-up</strong><br>
      Given I requested information, when time passes without response, then I receive automatic follow-up with contact alternatives.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-28</td>
    <td>Corporate information and values</td>
    <td>As a visitor, I want to know Smart Stay's mission, vision and values to understand the company's philosophy.</td>
    <td>
      <strong>Scenario 1: Complete "About us" section</strong><br>
      Given I look for corporate information, when I access "About us", then I find clear description of mission, vision, values and company history.<br>
      <strong>Scenario 2: Team and leadership</strong><br>
      Given I want to know the team, when I navigate to the section, then I see information about founders, key leaders and their experience.<br>
      <strong>Scenario 3: Sustainability commitment</strong><br>
      Given I care about environmental impact, when I review values, then I see clear commitment to sustainability and energy efficiency.<br>
      <strong>Scenario 4: Certifications and recognitions</strong><br>
      Given I look for quality validation, when I review credentials, then I see certifications, awards and industry recognitions.
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-29</td>
    <td>RESTful API for room management</td>
    <td>As a developer, I want to access RESTful endpoints to integrate Smart Stay with external hotel management systems.</td>
    <td>
      <strong>Scenario 1: Query available rooms</strong><br>
      Given I make GET /api/v1/rooms?date=2025-10-15, when API processes request, then I receive room list with availability and prices.<br>
      <strong>Scenario 2: Update room status</strong><br>
      Given I make PUT /api/v1/rooms/101 with new status, when processed, then room is updated and I receive 200 OK confirmation.<br>
      <strong>Scenario 3: Create new reservation</strong><br>
      Given I make POST /api/v1/bookings with valid data, when processed, then reservation is created and I receive unique confirmation ID.<br>
      <strong>Scenario 4: Error handling</strong><br>
      Given I send invalid data, when API processes it, then I receive 400 error with clear problem description.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-30</td>
    <td>API for IoT device control</td>
    <td>As a developer, I want endpoints to control room IoT devices from external applications.</td>
    <td>
      <strong>Scenario 1: Get current device status</strong><br>
      Given I make GET /api/v1/rooms/101/devices, when processed, then I receive current status of temperature, lights, blinds and other devices.<br>
      <strong>Scenario 2: Control temperature</strong><br>
      Given I make POST /api/v1/rooms/101/climate with desired temperature, when processed, then IoT device adjusts temperature.<br>
      <strong>Scenario 3: Lighting control</strong><br>
      Given I make PUT /api/v1/rooms/101/lights with configuration, when processed, then lights adjust according to sent parameters.<br>
      <strong>Scenario 4: Change logs</strong><br>
      Given I make GET /api/v1/rooms/101/device-logs, when processed, then I receive history of all device changes made.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-31</td>
    <td>API authentication and authorization</td>
    <td>As a developer, I want a secure authentication system to access Smart Stay API endpoints.</td>
    <td>
      <strong>Scenario 1: Get access token</strong><br>
      Given I make POST /api/v1/auth with valid credentials, when processed, then I receive JWT token with expiration time.<br>
      <strong>Scenario 2: Access with valid token</strong><br>
      Given I include valid Bearer token in headers, when I make request to protected endpoint, then I receive successful response.<br>
      <strong>Scenario 3: Expired token</strong><br>
      Given my token expired, when I make request, then I receive 401 Unauthorized error with clear message.<br>
      <strong>Scenario 4: Different access levels</strong><br>
      Given I have read-only token, when I try POST/PUT/DELETE, then I receive 403 Forbidden error.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-32</td>
    <td>Interactive API documentation</td>
    <td>As a developer, I want to access complete and interactive documentation to easily integrate with Smart Stay API.</td>
    <td>
      <strong>Scenario 1: Explore available endpoints</strong><br>
      Given I access documentation, when I navigate, then I see all endpoints organized by category with complete description.<br>
      <strong>Scenario 2: Test live endpoints</strong><br>
      Given I'm in documentation, when I select "Try it", then I can test endpoint directly with my credentials.<br>
      <strong>Scenario 3: Code examples</strong><br>
      Given I review an endpoint, when I see documentation, then I find code examples in multiple languages (JavaScript, Python, PHP).<br>
      <strong>Scenario 4: Data schemas</strong><br>
      Given I need to understand structure, when I review endpoint, then I see complete request/response schemas with data types.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-33</td>
    <td>Webhooks for real-time events</td>
    <td>As a developer, I want to configure webhooks to receive automatic notifications when important Smart Stay events occur.</td>
    <td>
      <strong>Scenario 1: Configure webhook</strong><br>
      Given I make POST /api/v1/webhooks with URL and events, when configured, then my endpoint receives notifications for those events.<br>
      <strong>Scenario 2: New reservation notification</strong><br>
      Given I have webhook configured for "booking.created", when new reservation is made, then my endpoint receives POST with reservation data.<br>
      <strong>Scenario 3: Automatic retries</strong><br>
      Given my endpoint doesn't respond, when Smart Stay sends webhook, then it retries up to 3 times with exponential backoff.<br>
      <strong>Scenario 4: Security verification</strong><br>
      Given I receive webhook, when I verify signature, then I can confirm it really comes from Smart Stay using shared secret.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-34</td>
    <td>Mobile push notification system</td>
    <td>As a guest, I want to receive push notifications on my smartphone about my request and service status.</td>
    <td>
      <strong>Scenario 1: Reservation confirmation notification</strong><br>
      Given I make a reservation, when confirmed, then I receive immediate push notification with details and next steps.<br>
      <strong>Scenario 2: Check-in reminder</strong><br>
      Given my arrival is in 24 hours, when the moment comes, then I receive notification with direct link for digital check-in.<br>
      <strong>Scenario 3: Service updates</strong><br>
      Given I requested room service, when status changes, then I receive notification with updated progress (preparing, on way, delivered).<br>
      <strong>Scenario 4: Preference settings</strong><br>
      Given I want to control notifications, when I access settings, then I can choose which types to receive and at what times.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-35</td>
    <td>Automatic staff notifications</td>
    <td>As hotel staff, I want to receive automatic notifications about assigned tasks and important operational changes.</td>
    <td>
      <strong>Scenario 1: New assigned task</strong><br>
      Given administrator assigns me a task, when created, then I receive immediate notification with details, priority and deadline.<br>
      <strong>Scenario 2: Priority change</strong><br>
      Given a task changes to high priority, when updated, then I receive special notification requiring read confirmation.<br>
      <strong>Scenario 3: Deadline reminders</strong><br>
      Given I have pending task, when deadline approaches, then I receive reminder 2 hours before due time.<br>
      <strong>Scenario 4: Operational emergencies</strong><br>
      Given there's emergency (technical problem, urgent complaint), when reported, then all relevant staff receive immediate alert.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-36</td>
    <td>Automated email marketing</td>
    <td>As an administrator, I want to send automated personalized emails to guests at different stages of their experience.</td>
    <td>
      <strong>Scenario 1: Pre-arrival welcome email</strong><br>
      Given guest confirms reservation, when 24 hours pass, then they receive email with hotel information, available services and arrival guide.<br>
      <strong>Scenario 2: During stay</strong><br>
      Given guest is at hotel for 2+ days, when it's the second day, then they receive email with local recommendations and special services.<br>
      <strong>Scenario 3: Post-stay and loyalty</strong><br>
      Given guest checks out, when 1 week passes, then they receive thank you email with special offer for next visit.<br>
      <strong>Scenario 4: Segmented campaigns</strong><br>
      Given I want to run specific campaign, when I select criteria (VIP guests, seasonality), then I can send personalized emails to that segment.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-37</td>
    <td>Intelligent alerts and escalation</td>
    <td>As an administrator, I want to receive intelligent alerts about operational problems with automatic escalation based on severity.</td>
    <td>
      <strong>Scenario 1: Low satisfaction alert</strong><br>
      Given guest gives 2-star rating or less, when they send evaluation, then I receive immediate alert for corrective action.<br>
      <strong>Scenario 2: Critical technical problem</strong><br>
      Given IoT device doesn't respond for more than 10 minutes, when detected, then I receive alert with problem information and affected room.<br>
      <strong>Scenario 3: Automatic escalation</strong><br>
      Given alert isn't attended within defined time, when time limit passes, then it's automatically escalated to supervisor or general manager.<br>
      <strong>Scenario 4: Revenue management alerts</strong><br>
      Given occupancy is well below forecast, when trend is detected, then I receive alert with pricing adjustment suggestions.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-38</td>
    <td>Unified communication panel</td>
    <td>As an administrator, I want a centralized panel to manage all communications (email, WhatsApp, SMS, notifications) from one place.</td>
    <td>
      <strong>Scenario 1: Unified conversation view</strong><br>
      Given I access communication panel, when it loads, then I see all active conversations from different channels in one interface.<br>
      <strong>Scenario 2: Response from central panel</strong><br>
      Given guest sends WhatsApp message, when I respond from panel, then my response is sent through original channel automatically.<br>
      <strong>Scenario 3: Unified guest history</strong><br>
      Given I select a guest, when I access their communication profile, then I see complete interaction history regardless of channel used.<br>
      <strong>Scenario 4: Conversation assignment</strong><br>
      Given complex query arrives, when I receive it, then I can assign it to specialized staff who will receive notification to respond.
    </td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-39</td>
    <td>Native mobile app for staff</td>
    <td>As hotel staff, I want a dedicated mobile app to manage my tasks and communication while on the move.</td>
    <td>
      <strong>Scenario 1: Mobile task list</strong><br>
      Given I open staff app, when it loads, then I see my pending tasks organized by priority with essential information.<br>
      <strong>Scenario 2: Update task status</strong><br>
      Given I complete a task, when I mark it as finished from app, then the change syncs immediately with central system.<br>
      <strong>Scenario 3: Communication with administration</strong><br>
      Given I have question or problem, when I use app chat, then I can communicate directly with administration in real time.<br>
      <strong>Scenario 4: Incident reporting</strong><br>
      Given I find problem (damaged room, broken equipment), when I report it from app, then automatic ticket is created with photo and location.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-40</td>
    <td>Data backup and recovery</td>
    <td>As a technical administrator, I want the system to have automatic backup and disaster recovery to guarantee operational continuity.</td>
    <td>
      <strong>Scenario 1: Automatic daily backup</strong><br>
      Given each operational day ends, when midnight arrives, then system creates complete data backup and stores it in secure location.<br>
      <strong>Scenario 2: Integrity verification</strong><br>
      Given backup is created, when completed, then system automatically verifies integrity of backed up data.<br>
      <strong>Scenario 3: Emergency recovery</strong><br>
      Given there's critical system failure, when I start recovery process, then I can restore operation from most recent backup in less than 2 hours.<br>
      <strong>Scenario 4: Problem notification</strong><br>
      Given backup process fails, when error is detected, then technical administrators receive immediate alert for investigation.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-41</td>
    <td>System monitoring and logs</td>
    <td>As a technical administrator, I want to monitor system performance and access detailed logs for troubleshooting.</td>
    <td>
      <strong>Scenario 1: Performance dashboard</strong><br>
      Given I access monitoring, when it loads, then I see key metrics (response time, CPU/memory usage, requests per minute, errors).<br>
      <strong>Scenario 2: Performance alerts</strong><br>
      Given response time exceeds 3 seconds, when detected, then I receive automatic alert with problem details.<br>
      <strong>Scenario 3: Centralized logs</strong><br>
      Given I need to investigate problem, when I access logs, then I can filter by date, user, action and error level.<br>
      <strong>Scenario 4: Trend analysis</strong><br>
      Given I want to optimize performance, when I review historical metrics, then I can identify patterns and bottlenecks.
    </td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-42</td>
    <td>Multi-hotel configuration for chains</td>
    <td>As a hotel chain administrator, I want to manage multiple properties from a master account with independent configurations.</td>
    <td>
      <strong>Scenario 1: Consolidated chain view</strong><br>
      Given I manage multiple hotels, when I access master panel, then I see consolidated KPIs for entire chain with drill-down by property.<br>
      <strong>Scenario 2: Per-property configuration</strong><br>
      Given each hotel is different, when I configure specific one, then I can customize services, prices and operation without affecting others.<br>
      <strong>Scenario 3: Shared staff between properties</strong><br>
      Given I have staff working at multiple hotels, when I assign them, then they can access corresponding properties with specific permissions.<br>
      <strong>Scenario 4: Consolidated reports</strong><br>
      Given I need chain analysis, when I generate reports, then I can see individual and comparative metrics across all my properties.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-43</td>
    <td>Integration with existing PMS systems</td>
    <td>As an administrator, I want to integrate Smart Stay with my current PMS system to migrate gradually without interrupting operations.</td>
    <td>
      <strong>Scenario 1: Bidirectional synchronization</strong><br>
      Given I have existing PMS, when I configure integration, then reservations synchronize automatically in both directions.<br>
      <strong>Scenario 2: Gradual functionality migration</strong><br>
      Given I want to adopt Smart Stay progressively, when I enable specific modules, then they can coexist with my current PMS.<br>
      <strong>Scenario 3: Consistency validation</strong><br>
      Given I have data in both systems, when it synchronizes, then I receive alerts if there are discrepancies requiring manual resolution.<br>
      <strong>Scenario 4: Transition backup</strong><br>
      Given I'm migrating, when I complete transition, then I can maintain read-only access to previous PMS for grace period.
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-44</td>
    <td>Brand customization per hotel</td>
    <td>As an administrator, I want to customize interface and communications with my hotel's brand to maintain visual consistency.</td>
    <td>
      <strong>Scenario 1: Color and logo customization</strong><br>
      Given I want to personalize appearance, when I upload my logo and define colors, then entire interface (web and app) updates with my branding.<br>
      <strong>Scenario 2: Personalized brand emails</strong><br>
      Given automatic communications are sent, when they reach guest, then they include my logo, colors and personalized hotel message.<br>
      <strong>Scenario 3: Personalized landing page</strong><br>
      Given guests access digital services, when they reach the page, then they see completely branded interface with my hotel.<br>
      <strong>Scenario 4: Message configuration</strong><br>
      Given I want to personalize communication, when I configure templates, then I can adapt all automatic messages to my brand's tone.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-45</td>
    <td>Integrated loyalty program</td>
    <td>As an administrator, I want to manage a loyalty program for recurring guests with automatic benefits.</td>
    <td>
      <strong>Scenario 1: Automatic point accumulation</strong><br>
      Given guest completes stay, when they check out, then they automatically accumulate points based on total spend and duration.<br>
      <strong>Scenario 2: Level benefits</strong><br>
      Given guest reaches VIP level, when they make new reservation, then they automatically receive benefits (upgrade, late checkout, amenities).<br>
      <strong>Scenario 3: Personalized offers</strong><br>
      Given guest's history, when they're about to travel, then they receive special offers based on their preferences and typical dates.<br>
      <strong>Scenario 4: Benefit redemption</strong><br>
      Given guest has sufficient points, when they want to redeem, then they can exchange for services, upgrades or free nights from app.
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-46</td>
    <td>Event and conference management</td>
    <td>As an administrator, I want to manage special events and conferences with specific group functionalities.</td>
    <td>
      <strong>Scenario 1: Create group event</strong><br>
      Given I receive event request, when I create event, then I can define special rates, block rooms and assign specific services.<br>
      <strong>Scenario 2: Mass check-in</strong><br>
      Given event participants arrive, when they start check-in, then they can use special code for accelerated process with pre-loaded data.<br>
      <strong>Scenario 3: Group communication</strong><br>
      Given I have active event, when I need to communicate something, then I can send mass messages only to specific event participants.<br>
      <strong>Scenario 4: Consolidated billing</strong><br>
      Given event ends, when I generate billing, then I can create master invoice for organizer or individual invoices according to configuration.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-47</td>
    <td>IoT predictive maintenance</td>
    <td>As an administrator, I want the IoT system to predict maintenance needs based on equipment usage and performance.</td>
    <td>
      <strong>Scenario 1: Continuous equipment monitoring</strong><br>
      Given I have IoT devices installed, when they operate, then system continuously monitors performance, consumption and usage patterns.<br>
      <strong>Scenario 2: Predictive alerts</strong><br>
      Given equipment shows degradation signs, when anomaly is detected, then I receive alert with preventive maintenance recommendation.<br>
      <strong>Scenario 3: Automatic scheduling</strong><br>
      Given maintenance is required, when I accept recommendation, then it's automatically scheduled with technical team and room is blocked.<br>
      <strong>Scenario 4: Performance history</strong><br>
      Given I want to analyze equipment, when I access metrics, then I see complete performance history and all maintenance performed.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-48</td>
    <td>Competition analysis and dynamic pricing</td>
    <td>As an administrator, I want to analyze competitor prices and adjust my rates automatically to optimize revenue.</td>
    <td>
      <strong>Scenario 1: Competitor price monitoring</strong><br>
      Given I configure competing hotels, when system analyzes prices, then I see daily rate comparison in my geographic area.<br>
      <strong>Scenario 2: Pricing suggestions</strong><br>
      Given there are changes in competition, when detected, then I receive price adjustment suggestions based on occupancy and demand forecast.<br>
      <strong>Scenario 3: Automatic rate adjustment</strong><br>
      Given I enable dynamic pricing, when defined conditions are met, then system automatically adjusts prices within configured ranges.<br>
      <strong>Scenario 4: Elasticity analysis</strong><br>
      Given I have price change history, when I generate analysis, then I see impact of adjustments on occupancy and total revenue.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-49</td>
    <td>Automated compliance and auditing</td>
    <td>As an administrator, I want the system to generate automatic compliance reports and facilitate regulatory audits.</td>
    <td>
      <strong>Scenario 1: Automatic regulatory reports</strong><br>
      Given I must comply with local regulations, when period ends, then system automatically generates reports required by authorities.<br>
      <strong>Scenario 2: Complete traceability</strong><br>
      Given I need audit, when I export data, then I get complete traceability of all transactions and changes with timestamps.<br>
      <strong>Scenario 3: Tax data validation</strong><br>
      Given I process payments, when registered, then system automatically validates they meet local tax requirements.<br>
      <strong>Scenario 4: Organized digital archive</strong><br>
      Given I store documents, when I need them for audit, then they're automatically organized by period, type and guest with quick search.
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-50</td>
    <td>Security system integration</td>
    <td>As an administrator, I want to integrate Smart Stay with hotel security systems for automated access management.</td>
    <td>
      <strong>Scenario 1: Automatic access code generation</strong><br>
      Given guest completes digital check-in, when confirmed, then system automatically generates unique code for their room with specific validity.<br>
      <strong>Scenario 2: Automatic post-checkout revocation</strong><br>
      Given guest checks out, when completed, then all access codes are automatically revoked in security systems.<br>
      <strong>Scenario 3: Temporary staff access</strong><br>
      Given staff needs access for cleaning/maintenance, when task is assigned, then they receive temporary code valid only during their work shift.<br>
      <strong>Scenario 4: Access log and alerts</strong><br>
      Given any access code is used, when it occurs, then it's recorded in central log and alerts are generated for access outside normal hours.
    </td>
    <td>EP-05</td>
  </tr>
</table>


## 3.2. Impact Mapping.

![ImpactMapping.jpeg](assets/ImpactMapping.jpeg)

## 3.3. Product Backlog.

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th>#</th>
      <th>Order</th>
      <th>User Story Id</th>
      <th>Title</th>
      <th>Description</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>1</td>
      <td>US-24</td>
      <td>Segmented landing page</td>
      <td><strong>As</strong> a visitor, <strong>I want</strong> to find specific information according to my profile (hotel administrator or guest) <strong>to</strong> understand Smart Stay's value.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>2</td>
      <td>2</td>
      <td>US-25</td>
      <td>ROI simulator for hotels</td>
      <td><strong>As</strong> a visiting hotel administrator, <strong>I want</strong> to use a simulator to estimate the return on investment I would get with Smart Stay <strong>to</strong> make informed decisions.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
      <td>US-27</td>
      <td>Demo request and commercial contact</td>
      <td><strong>As</strong> an interested visitor, <strong>I want</strong> to request a demonstration and contact the sales team easily and quickly <strong>to</strong> explore Smart Stay solutions.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>4</td>
      <td>US-26</td>
      <td>Success stories and testimonials</td>
      <td><strong>As</strong> an interested visitor, <strong>I want</strong> to see real success stories from hotels using Smart Stay <strong>to</strong> validate solution effectiveness.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>5</td>
      <td>5</td>
      <td>US-28</td>
      <td>Corporate information and values</td>
      <td><strong>As</strong> a visitor, <strong>I want</strong> to know Smart Stay's mission, vision and values <strong>to</strong> understand the company's philosophy.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>6</td>
      <td>6</td>
      <td>US-05</td>
      <td>Administrator dashboard</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> a centralized panel with key information <strong>to</strong> manage my hotel efficiently.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>7</td>
      <td>7</td>
      <td>US-07</td>
      <td>Centralized reservation management</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to manage all reservations in one place <strong>to</strong> avoid overbooking and optimize occupancy.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>8</td>
      <td>8</td>
      <td>US-08</td>
      <td>Automated digital check-in</td>
      <td><strong>As</strong> an administrator and guest, <strong>I want</strong> check-in to be performed digitally in less than 3 minutes <strong>to</strong> improve experience.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>9</td>
      <td>9</td>
      <td>US-09</td>
      <td>Digital check-out and billing</td>
      <td><strong>As</strong> a guest, <strong>I want</strong> to perform digital check-out and receive my invoice automatically <strong>to</strong> expedite my departure.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>10</td>
      <td>10</td>
      <td>US-06</td>
      <td>Room and status management</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to manage all room statuses <strong>to</strong> optimize daily operations.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>11</td>
      <td>11</td>
      <td>US-20</td>
      <td>OTA and booking channel integration</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to integrate my inventory with Booking.com, Expedia and other OTAs <strong>to</strong> maximize occupancy and avoid overbooking.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>12</td>
      <td>12</td>
      <td>US-01</td>
      <td>User registration with validation</td>
      <td><strong>As</strong> a new user, <strong>I want</strong> to register in Smart Stay by validating my email <strong>to</strong> access functionalities according to my role.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>13</td>
      <td>13</td>
      <td>US-02</td>
      <td>Secure login</td>
      <td><strong>As</strong> a registered user, <strong>I want</strong> to login securely <strong>to</strong> access my personalized dashboard according to my role.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>14</td>
      <td>US-11</td>
      <td>IoT environmental control from mobile app</td>
      <td><strong>As</strong> a guest, <strong>I want</strong> to control temperature, lighting and other environmental aspects from my smartphone <strong>to</strong> personalize my experience.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>15</td>
      <td>15</td>
      <td>US-12</td>
      <td>Service requests from app</td>
      <td><strong>As</strong> a guest, <strong>I want</strong> to request room service, additional cleaning and other services from my smartphone <strong>to</strong> access services conveniently.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>16</td>
      <td>16</td>
      <td>US-23</td>
      <td>Digital payment processing</td>
      <td><strong>As</strong> an administrator and guest, <strong>I want</strong> to process payments securely and efficiently through multiple payment methods <strong>to</strong> ensure smooth transactions.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>17</td>
      <td>17</td>
      <td>US-10</td>
      <td>Staff task assignment and tracking</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to assign tasks to staff and track their progress <strong>to</strong> optimize operations.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>18</td>
      <td>18</td>
      <td>US-16</td>
      <td>Analytics dashboard and operational KPIs</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to visualize key metrics and KPIs <strong>to</strong> make informed decisions about hotel operations.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>19</td>
      <td>19</td>
      <td>US-34</td>
      <td>Mobile push notification system</td>
      <td><strong>As</strong> a guest, <strong>I want</strong> to receive push notifications on my smartphone about my request and service status <strong>to</strong> stay informed.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>20</td>
      <td>20</td>
      <td>US-35</td>
      <td>Automatic staff notifications</td>
      <td><strong>As</strong> hotel staff, <strong>I want</strong> to receive automatic notifications about assigned tasks and important operational changes <strong>to</strong> respond promptly.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>21</td>
      <td>21</td>
      <td>US-21</td>
      <td>WhatsApp Business integration</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to use WhatsApp Business for direct guest communication and pre/post-stay query management <strong>to</strong> improve customer service.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>22</td>
      <td>22</td>
      <td>US-13</td>
      <td>Digital guest-staff communication</td>
      <td><strong>As</strong> a guest, <strong>I want</strong> to communicate with hotel staff digitally <strong>to</strong> resolve questions and requests quickly.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>23</td>
      <td>23</td>
      <td>US-22</td>
      <td>Digital reputation management</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to manage Google, TripAdvisor and OTA reviews from one place <strong>to</strong> maintain good online reputation.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>24</td>
      <td>24</td>
      <td>US-17</td>
      <td>Financial and occupancy reports</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to generate financial and occupancy reports <strong>to</strong> support management analysis and decision making.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>25</td>
      <td>25</td>
      <td>US-19</td>
      <td>IoT energy consumption monitoring</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to monitor energy consumption of rooms and common areas <strong>to</strong> optimize operational costs.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>26</td>
      <td>26</td>
      <td>US-14</td>
      <td>Experience personalization based on preferences</td>
      <td><strong>As</strong> a guest, <strong>I want</strong> the system to learn my preferences <strong>to</strong> offer personalized experiences and services.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>27</td>
      <td>27</td>
      <td>US-15</td>
      <td>Post-stay evaluation and feedback</td>
      <td><strong>As</strong> a guest, <strong>I want</strong> to evaluate my experience and leave feedback <strong>to</strong> help the hotel improve its services.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>28</td>
      <td>28</td>
      <td>US-18</td>
      <td>Guest satisfaction analysis</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to analyze guest satisfaction <strong>to</strong> identify improvement areas and maintain service quality.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>29</td>
      <td>29</td>
      <td>US-29</td>
      <td>RESTful API for room management</td>
      <td><strong>As</strong> a developer, <strong>I want</strong> to access RESTful endpoints <strong>to</strong> integrate Smart Stay with external hotel management systems.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>30</td>
      <td>30</td>
      <td>US-30</td>
      <td>API for IoT device control</td>
      <td><strong>As</strong> a developer, <strong>I want</strong> endpoints to control room IoT devices <strong>to</strong> enable integration with external applications.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>31</td>
      <td>31</td>
      <td>US-31</td>
      <td>API authentication and authorization</td>
      <td><strong>As</strong> a developer, <strong>I want</strong> a secure authentication system <strong>to</strong> access Smart Stay API endpoints safely.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>32</td>
      <td>32</td>
      <td>US-32</td>
      <td>Interactive API documentation</td>
      <td><strong>As</strong> a developer, <strong>I want</strong> to access complete and interactive documentation <strong>to</strong> easily integrate with Smart Stay API.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>33</td>
      <td>33</td>
      <td>US-33</td>
      <td>Webhooks for real-time events</td>
      <td><strong>As</strong> a developer, <strong>I want</strong> to configure webhooks <strong>to</strong> receive automatic notifications when important Smart Stay events occur.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>34</td>
      <td>34</td>
      <td>US-03</td>
      <td>Profile and role management</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to manage users, assign roles and permissions <strong>to</strong> control access to different functionalities.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>35</td>
      <td>35</td>
      <td>US-04</td>
      <td>Password recovery</td>
      <td><strong>As</strong> a user, <strong>I want</strong> to recover my password via email <strong>to</strong> regain access to my account.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>36</td>
      <td>36</td>
      <td>US-36</td>
      <td>Automated email marketing</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to send automated personalized emails to guests at different stages <strong>to</strong> enhance customer experience.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>37</td>
      <td>37</td>
      <td>US-37</td>
      <td>Intelligent alerts and escalation</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to receive intelligent alerts about operational problems with automatic escalation <strong>to</strong> ensure quick resolution.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>38</td>
      <td>38</td>
      <td>US-38</td>
      <td>Unified communication panel</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> a centralized panel to manage all communications <strong>to</strong> streamline guest interaction management.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>39</td>
      <td>39</td>
      <td>US-39</td>
      <td>Native mobile app for staff</td>
      <td><strong>As</strong> hotel staff, <strong>I want</strong> a dedicated mobile app to manage my tasks and communication <strong>to</strong> work efficiently while on the move.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>40</td>
      <td>40</td>
      <td>US-42</td>
      <td>Multi-hotel configuration for chains</td>
      <td><strong>As</strong> a hotel chain administrator, <strong>I want</strong> to manage multiple properties from a master account <strong>to</strong> centralize operations with independent configurations.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>41</td>
      <td>41</td>
      <td>US-43</td>
      <td>Integration with existing PMS systems</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to integrate Smart Stay with my current PMS system <strong>to</strong> migrate gradually without interrupting operations.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>42</td>
      <td>42</td>
      <td>US-44</td>
      <td>Brand customization per hotel</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to customize interface and communications with my hotel's brand <strong>to</strong> maintain visual consistency.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>43</td>
      <td>43</td>
      <td>US-45</td>
      <td>Integrated loyalty program</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to manage a loyalty program for recurring guests <strong>to</strong> provide automatic benefits and increase retention.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>44</td>
      <td>44</td>
      <td>US-46</td>
      <td>Event and conference management</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to manage special events and conferences <strong>to</strong> provide specific group functionalities.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>45</td>
      <td>45</td>
      <td>US-47</td>
      <td>IoT predictive maintenance</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> the IoT system to predict maintenance needs <strong>to</strong> optimize equipment performance and reduce downtime.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>46</td>
      <td>46</td>
      <td>US-48</td>
      <td>Competition analysis and dynamic pricing</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to analyze competitor prices and adjust my rates automatically <strong>to</strong> optimize revenue.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>47</td>
      <td>47</td>
      <td>US-49</td>
      <td>Automated compliance and auditing</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> the system to generate automatic compliance reports <strong>to</strong> facilitate regulatory audits.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>48</td>
      <td>48</td>
      <td>US-50</td>
      <td>Security system integration</td>
      <td><strong>As</strong> an administrator, <strong>I want</strong> to integrate Smart Stay with hotel security systems <strong>to</strong> provide automated access management.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>49</td>
      <td>49</td>
      <td>US-40</td>
      <td>Data backup and recovery</td>
      <td><strong>As</strong> a technical administrator, <strong>I want</strong> the system to have automatic backup and disaster recovery <strong>to</strong> guarantee operational continuity.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>50</td>
      <td>50</td>
      <td>US-41</td>
      <td>System monitoring and logs</td>
      <td><strong>As</strong> a technical administrator, <strong>I want</strong> to monitor system performance and access detailed logs <strong>to</strong> support troubleshooting activities.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

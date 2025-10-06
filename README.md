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

**Epics**

| EPIC ID | Nombre del Epic                           | Descripción                                                                                                         |
| ------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| EP01    | Registro y Gestión de Perfil de Huésped   | Como huésped, quiero registrarme, iniciar sesión y gestionar mi perfil de forma segura para acceder a mis reservas. |
| EP02    | Registro y Gestión de Perfil de Anfitrión | Como anfitrión, quiero registrarme y administrar mi perfil para publicar propiedades y gestionar reservas.          |
| EP03    | Gestión de Propiedades                    | Como anfitrión, quiero registrar, editar y eliminar propiedades con fotos, precios y descripciones.                 |
| EP04    | Búsqueda y Reserva de Estancias           | Como huésped, quiero buscar propiedades y realizar reservas fácilmente.                                             |
| EP05    | Pagos y Facturación                       | Como usuario, quiero pagar de manera segura y consultar mis comprobantes de pago.                                   |
| EP06    | Reseñas y Calificaciones                  | Como usuario, quiero dejar reseñas y calificaciones después de una estancia.                                        |
| EP07    | Soporte y Ayuda                           | Como usuario, quiero acceder a soporte técnico y resolver mis dudas.                                                |
| EP08    | Exploración como Visitante                | Como visitante, quiero conocer las funcionalidades de SmartStay desde la landing page antes de registrarme.         |

**Desarrollo de Epics**

**EP01 – Registro y Gestión de Perfil de Huésped**

| User Story ID | Título                     |
| ------------- | -------------------------- |
| US01          | Registro de huésped        |
| US02          | Inicio de sesión seguro    |
| US03          | Recuperación de contraseña |
| US04          | Edición de perfil personal |

| Technical Story ID | Título                                               |
| ------------------ | ---------------------------------------------------- |
| TS01               |Conectar formularios de registro/login con validaciones en frontend |


**EP02 – Registro y Gestión de Perfil de Anfitrión**

| User Story ID | Título                             |
| ------------- | ---------------------------------- |
| US05          | Registro de anfitrión              |
| US06          | Verificación de identidad básica   |
| US07          | Configuración de datos de contacto |
| US08          | Edición de perfil de anfitrión     |

| Technical Story ID | Título                                              |
| ------------------ | --------------------------------------------------- |
| TS02               | Validar campos de formulario en frontend (correo, contraseña, documento)|

**EP03 – Gestión de Propiedades**

| User Story ID | Título                             |
| ------------- | ---------------------------------- |
| US09          | Registrar nueva propiedad          |
| US10          | Subir fotos de la propiedad        |
| US11          | Editar información de la propiedad |
| US12          | Eliminar propiedad                 |

**EP04 – Búsqueda y Reserva de Estancias**

| User Story ID | Título                           |
| ------------- | -------------------------------- |
| US13          | Buscar propiedades por ubicación |
| US14          | Filtrar por precio y fechas      |
| US15          | Reservar una propiedad           |
| US16          | Ver historial de reservas        |

| Technical Story ID | Título                                      |
| ------------------ | ------------------------------------------- |
| TS03              | Crear buscador y filtros en frontend.     |
| TS04               | Simular reservas con estado guardado en frontend |

**EP05 – Pagos y Facturación**

| User Story ID | Título                        |
| ------------- | ----------------------------- |
| US17          | Realizar pago en línea        |
| US18          | Consultar historial de pagos  |
| US19          | Descargar comprobante de pago |

| Technical Story ID | Título                                                |
| ------------------ | ----------------------------------------------------- |
| TS05               | Simular integración de pago |


**EP06 – Reseñas y Calificaciones**

| User Story ID | Título                        |
| ------------- | ----------------------------- |
| US20          | Dejar reseña de una estancia  |
| US21          | Calificar anfitrión o huésped |
| US22          | Ver reseñas de una propiedad  |

| Technical Story ID | Título                                              |
| ------------------ | --------------------------------------------------- |
| TS06               | Formulario de reseñas conectado a la UI, guardado simulado en frontendFormulario de reseñas conectado a la UI, guardado simulado en frontend  |


**EP07 – Soporte y Ayuda**

| User Story ID | Título                         |
| ------------- | ------------------------------ |
| US23          | Acceder a preguntas frecuentes |
| US24          | Enviar reporte de problema     |
| US25          | Contactar con soporte técnico  |

| Technical Story ID | Título                                      |
| ------------------ | ------------------------------------------- |
| TS07               | Implementar formulario de contacto y sección de preguntas frecuentes |


**EP08 – Exploración como Visitante**

| User Story ID | Título                                   |
| ------------- | ---------------------------------------- |
| US26          | Ver información general sobre SmartStay  |
| US27          | Conocer beneficios de usar la plataforma |
| US28          | Acceder fácilmente al registro o login   |

| Technical Story ID | Título                             |
| ------------------ | ---------------------------------- |
| TS08               | Implementar landing page con botones hacia login/registro |

---

**EP01 – Registro y Autenticación**

| ID Épica | Épica                                   | ID   | Título                               | Descripción                                                                      | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                    |
| -------- | --------------------------------------- | ---- | ------------------------------------ | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP01     | Registro y Gestión de Perfil de Huésped | US01 | Registro de huésped                  | Como huésped, quiero registrarme en la plataforma para crear mi cuenta.          | - Escenario 1: Registro exitoso <br> **Dado** que el usuario accede al formulario de registro, <br> **Cuando** completa los campos requeridos y presiona “Crear cuenta”, <br> **Entonces** el sistema registra al usuario y muestra un mensaje de bienvenida.                                                                                                              |
| EP01     | Registro y Gestión de Perfil de Huésped | US02 | Inicio de sesión seguro              | Como huésped registrado, quiero iniciar sesión para acceder a mis funciones.     | - Escenario 1: Inicio exitoso <br> **Dado** que el usuario ya está registrado, <br> **Cuando** ingresa credenciales válidas, <br> **Entonces** accede al panel. <br><br> - Escenario 2: Inicio fallido <br> **Dado** que el usuario ingresa credenciales incorrectas, <br> **Cuando** presiona “Iniciar sesión”, <br> **Entonces** el sistema muestra un mensaje de error. |
| EP01     | Registro y Gestión de Perfil de Huésped | US03 | Recuperación de contraseña           | Como huésped, quiero recuperar mi contraseña para poder acceder si la olvido.    | - Escenario 1: Recuperación exitosa <br> **Dado** que el usuario olvidó su contraseña, <br> **Cuando** solicita la recuperación ingresando su correo, <br> **Entonces** el sistema envía un enlace de restablecimiento.                                                                                                                                                    |
| EP01     | Registro y Gestión de Perfil de Huésped | US04 | Edición de perfil personal           | Como huésped, quiero editar mi información personal para mantenerla actualizada. | - Escenario 1: Edición de perfil <br> **Dado** que el usuario está logueado, <br> **Cuando** modifica sus datos personales y guarda, <br> **Entonces** el sistema actualiza la información correctamente.                                                                                                                                                                  |
| EP01     | Registro y Gestión de Perfil de Huésped | TS01 | Validaciones frontend registro/login | Como desarrollador, quiero validar formularios en frontend para evitar errores.  | - Escenario 1: Validación de campos vacíos <br> **Dado** que el usuario deja campos en blanco, <br> **Cuando** intenta registrarse, <br> **Entonces** el sistema muestra mensajes de validación.   | |

**EP02 – Búsqueda y Reserva de Propiedades**

| ID Épica | Épica                                     | ID   | Título                                   | Descripción                                                                                             | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                          |
| -------- | ----------------------------------------- | ---- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP02     | Registro y Gestión de Perfil de Anfitrión | US05 | Registro de anfitrión                    | Como anfitrión, quiero registrarme en la plataforma para publicar mis propiedades.                      | - Escenario 1: Registro exitoso <br> **Dado** que el usuario accede al formulario de registro de anfitrión, <br> **Cuando** completa los campos requeridos y presiona “Crear cuenta”, <br> **Entonces** el sistema registra al anfitrión y muestra un mensaje de bienvenida.                                                                                                                                     |
| EP02     | Registro y Gestión de Perfil de Anfitrión | US06 | Verificación de identidad básica         | Como anfitrión, quiero verificar mi identidad de manera sencilla para dar confianza a los huéspedes.    | - Escenario 1: Verificación cargada <br> **Dado** que el anfitrión accede a su perfil, <br> **Cuando** sube un documento válido de identificación, <br> **Entonces** el sistema guarda el estado de verificación como “En revisión”.                                                                                                                                                                             |
| EP02     | Registro y Gestión de Perfil de Anfitrión | US07 | Configuración de datos de contacto       | Como anfitrión, quiero configurar mis datos de contacto para que los huéspedes puedan comunicarse.      | - Escenario 1: Configuración exitosa <br> **Dado** que el anfitrión edita su sección de contacto, <br> **Cuando** guarda número de teléfono o correo, <br> **Entonces** el sistema actualiza los datos correctamente.                                                                                                                                                                                            |
| EP02     | Registro y Gestión de Perfil de Anfitrión | US08 | Edición de perfil de anfitrión           | Como anfitrión, quiero editar mi información personal y de negocio para mantenerla actualizada.         | - Escenario 1: Edición correcta <br> **Dado** que el anfitrión accede a su perfil, <br> **Cuando** modifica su información y guarda, <br> **Entonces** el sistema actualiza los cambios exitosamente.                                                                                                                                                                                                            |
| EP02     | Registro y Gestión de Perfil de Anfitrión | TS02 | Validar campos de formulario en frontend | Como desarrollador, quiero validar campos de formulario (correo, contraseña, documento) en el frontend. | - Escenario 1: Validación de correo <br> **Dado** que el usuario ingresa un correo inválido, <br> **Cuando** intenta guardar, <br> **Entonces** el sistema muestra un mensaje de error. <br><br> - Escenario 2: Validación de documento <br> **Dado** que el anfitrión sube un archivo no permitido, <br> **Cuando** intenta verificar identidad, <br> **Entonces** el sistema muestra un mensaje de validación. |

**EP03 – Gestión de Propiedades**

| ID Épica | Épica                  | ID   | Título                             | Descripción                                                                                                              | Criterios de Aceptación                                                                                                                                                                                                                 |
| -------- | ---------------------- | ---- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP03     | Gestión de Propiedades | US09 | Registrar nueva propiedad          | Como anfitrión, quiero registrar una nueva propiedad con descripción, precio y ubicación para ofrecerla a los huéspedes. | - Escenario 1: Registro exitoso<br>Dado que el anfitrión accede al formulario de registro de propiedad,<br>Cuando completa todos los campos requeridos y guarda,<br>Entonces el sistema registra la propiedad y la muestra en su lista. |
| EP03     | Gestión de Propiedades | US10 | Subir fotos de la propiedad        | Como anfitrión, quiero subir fotos de mi propiedad para que los huéspedes tengan una mejor referencia.                   | - Escenario 1: Carga correcta<br>Dado que el anfitrión accede a la opción de subir fotos,<br>Cuando selecciona imágenes válidas,<br>Entonces el sistema guarda y muestra las fotos en la galería de la propiedad.                       |
| EP03     | Gestión de Propiedades | US11 | Editar información de la propiedad | Como anfitrión, quiero editar los datos de mi propiedad para mantenerlos actualizados.                                   | - Escenario 1: Edición exitosa<br>Dado que el anfitrión accede a una propiedad registrada,<br>Cuando modifica los datos y guarda,<br>Entonces el sistema actualiza la información.                                                      |
| EP03     | Gestión de Propiedades | US12 | Eliminar propiedad                 | Como anfitrión, quiero eliminar una propiedad registrada para que ya no aparezca disponible.                             | - Escenario 1: Eliminación correcta<br>Dado que el anfitrión accede a su lista de propiedades,<br>Cuando selecciona “Eliminar” en una propiedad,<br>Entonces el sistema la retira de la lista.                                          |

**EP04 – Búsqueda y Reserva de Estancias**

| ID Épica | Épica                           | ID   | Título                               | Descripción                                                                                           | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                  |
| -------- | ------------------------------- | ---- | ------------------------------------ | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| EP04     | Búsqueda y Reserva de Estancias | US13 | Buscar propiedades por ubicación     | Como huésped, quiero buscar propiedades por ubicación para encontrar opciones cercanas a donde viajo. | - Escenario 1: Búsqueda exitosa<br>Dado que el huésped accede al buscador,<br>Cuando ingresa una ciudad o dirección válida,<br>Entonces el sistema muestra las propiedades disponibles en esa ubicación.                                                                                                                                                                 |
| EP04     | Búsqueda y Reserva de Estancias | US14 | Filtrar por precio y fechas          | Como huésped, quiero aplicar filtros de precio y fechas para ajustar mi búsqueda.                     | - Escenario 1: Filtro aplicado<br>Dado que el huésped aplica filtros de precio y fechas,<br>Cuando actualiza la búsqueda,<br>Entonces el sistema muestra solo las propiedades que cumplen con esos criterios.                                                                                                                                                            |
| EP04     | Búsqueda y Reserva de Estancias | US15 | Reservar una propiedad               | Como huésped, quiero reservar una propiedad para asegurar mi estancia en las fechas seleccionadas.    | - Escenario 1: Reserva exitosa<br>Dado que el huésped selecciona una propiedad disponible,<br>Cuando confirma la reserva,<br>Entonces el sistema guarda la reserva y muestra la confirmación.                                                                                                                                                                            |
| EP04     | Búsqueda y Reserva de Estancias | US16 | Ver historial de reservas            | Como huésped, quiero ver mi historial de reservas para consultar mis viajes pasados y futuros.        | - Escenario 1: Consulta exitosa<br>Dado que el huésped accede a su perfil,<br>Cuando entra a la sección “Historial de reservas”,<br>Entonces el sistema le muestra sus reservas previas y próximas.                                                                                                                                                                      |
| EP04     | Búsqueda y Reserva de Estancias | TS03 | Crear buscador y filtros en frontend | Como desarrollador, quiero implementar un buscador con filtros de precio y fecha en el frontend.      | - Escenario 1: Filtros vacíos<br>Dado que el huésped no selecciona filtros,<br>Cuando ejecuta la búsqueda,<br>Entonces el sistema muestra todas las propiedades disponibles.<br><br>- Escenario 2: Filtros aplicados<br>Dado que el huésped selecciona filtros válidos,<br>Cuando ejecuta la búsqueda,<br>Entonces el sistema muestra solo los resultados que coinciden. |
| EP04     | Búsqueda y Reserva de Estancias | TS04 | Simular reservas en frontend         | Como desarrollador, quiero simular el guardado de reservas en el frontend para pruebas iniciales.     | - Escenario 1: Simulación exitosa<br>Dado que el huésped confirma una reserva,<br>Cuando la guarda en el frontend,<br>Entonces el sistema muestra la reserva como confirmada en su lista de historial.                                                                                                                                                                   |

**EP05 – Pagos y Facturación**

| ID Épica | Épica               | ID   | Título                        | Descripción                                                                               | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                            |
| -------- | ------------------- | ---- | ----------------------------- | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP05     | Pagos y Facturación | US17 | Realizar pago en línea        | Como usuario, quiero realizar un pago en línea para completar mi reserva.                 | - Escenario 1: Pago exitoso<br>**Dado** que el usuario accede al formulario de pago,<br>**Cuando** ingresa datos válidos y confirma,<br>**Entonces** el sistema procesa el pago y muestra confirmación.<br><br>- Escenario 2: Pago rechazado<br>**Dado** que el usuario ingresa datos inválidos,<br>**Cuando** intenta pagar,<br>**Entonces** el sistema muestra mensaje de error. |
| EP05     | Pagos y Facturación | US18 | Consultar historial de pagos  | Como usuario, quiero consultar mi historial de pagos para revisar mis transacciones.      | - Escenario 1: Ver historial<br>**Dado** que el usuario accede a la sección de pagos,<br>**Cuando** ya realizó transacciones,<br>**Entonces** se listan los pagos realizados.<br><br>- Escenario 2: Sin historial<br>**Dado** que el usuario no tiene pagos,<br>**Cuando** entra a la sección,<br>**Entonces** se muestra el mensaje “No tienes pagos registrados”.                |
| EP05     | Pagos y Facturación | US19 | Descargar comprobante de pago | Como usuario, quiero descargar un comprobante de pago para tener un respaldo.             | - Escenario 1: Descarga exitosa<br>**Dado** que el usuario está en su historial,<br>**Cuando** selecciona “Descargar”,<br>**Entonces** el sistema genera un PDF con los datos del pago.                                                                                                                                                                                            |
| EP05     | Pagos y Facturación | TS05 | Simular integración de pago   | Como desarrollador, quiero simular la integración de un servicio de pagos en el frontend. | - Escenario 1: Validación básica<br>**Dado** que el usuario deja campos vacíos,<br>**Cuando** intenta pagar,<br>**Entonces** el sistema muestra mensajes de validación.<br><br>- Escenario 2: Simulación de respuesta<br>**Dado** que se envía un pago,<br>**Cuando** el sistema recibe la respuesta simulada,<br>**Entonces** guarda el estado como “Aprobado” o “Rechazado”.     |

**EP06 – Reseñas y Calificaciones**

| ID Épica | Épica                    | ID   | Título                            | Descripción                                                                                              | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------ | ---- | --------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP06     | Reseñas y Calificaciones | US20 | Dejar reseña de una estancia      | Como usuario, quiero dejar una reseña después de mi estancia para compartir mi experiencia.              | - Escenario 1: Reseña enviada<br>**Dado** que el usuario accede al formulario,<br>**Cuando** escribe su reseña y envía,<br>**Entonces** el sistema la guarda y muestra en la lista.<br><br>- Escenario 2: Validación<br>**Dado** que el usuario intenta enviar reseña vacía,<br>**Cuando** presiona guardar,<br>**Entonces** se muestra un mensaje de error.                           |
| EP06     | Reseñas y Calificaciones | US21 | Calificar anfitrión o huésped     | Como usuario, quiero calificar al anfitrión o huésped para dar retroalimentación.                        | - Escenario 1: Calificación registrada<br>**Dado** que el usuario accede a la sección de calificaciones,<br>**Cuando** selecciona estrellas y guarda,<br>**Entonces** el sistema registra la calificación.                                                                                                                                                                             |
| EP06     | Reseñas y Calificaciones | US22 | Ver reseñas de una propiedad      | Como huésped, quiero ver reseñas de propiedades para tomar mejores decisiones.                           | - Escenario 1: Reseñas disponibles<br>**Dado** que la propiedad tiene reseñas,<br>**Cuando** el huésped accede a la sección,<br>**Entonces** el sistema muestra el listado.<br><br>- Escenario 2: Sin reseñas<br>**Dado** que la propiedad no tiene reseñas,<br>**Cuando** el huésped accede a la sección,<br>**Entonces** el sistema muestra el mensaje “No hay reseñas disponibles”. |
| EP06     | Reseñas y Calificaciones | TS06 | Formulario de reseñas en frontend | Como desarrollador, quiero implementar un formulario de reseñas conectado a la UI con guardado simulado. | - Escenario 1: Validación de campos<br>**Dado** que el usuario deja campos vacíos,<br>**Cuando** intenta guardar,<br>**Entonces** se muestran mensajes de error.<br><br>- Escenario 2: Guardado simulado<br>**Dado** que el usuario envía una reseña válida,<br>**Cuando** guarda,<br>**Entonces** el sistema la almacena en localstorage o JSON simulado.                             |

**EP07 – Seguridad y Privacidad**

| ID Épica | Épica           | ID   | Título                                                               | Descripción                                                                                         | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                |
| -------- | --------------- | ---- | -------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| EP07     | Soporte y Ayuda | US23 | Acceder a preguntas frecuentes                                       | Como usuario, quiero acceder a una sección de preguntas frecuentes para resolver mis dudas comunes. | - Escenario 1: Ver FAQs<br>**Dado** que el usuario entra a la sección de Ayuda,<br>**Cuando** selecciona “Preguntas frecuentes”,<br>**Entonces** el sistema muestra un listado con preguntas y respuestas.                                                                                                                                                                                             |
| EP07     | Soporte y Ayuda | US24 | Enviar reporte de problema                                           | Como usuario, quiero enviar un reporte de problema para notificar errores en la plataforma.         | - Escenario 1: Enviar reporte<br>**Dado** que el usuario completa el formulario de reporte,<br>**Cuando** hace clic en “Enviar”,<br>**Entonces** el sistema confirma el envío del reporte.                                                                                                                                                                                                             |
| EP07     | Soporte y Ayuda | US25 | Contactar con soporte técnico                                        | Como usuario, quiero contactar con soporte técnico para recibir asistencia personalizada.           | - Escenario 1: Solicitar contacto<br>**Dado** que el usuario ingresa a la sección de contacto,<br>**Cuando** envía una solicitud,<br>**Entonces** el sistema muestra un mensaje confirmando que será atendido.                                                                                                                                                                                         |
| EP07     | Soporte y Ayuda | TS07 | Implementar formulario de contacto y sección de preguntas frecuentes | Como desarrollador, quiero implementar un formulario de contacto y sección de FAQs en el frontend.  | - Escenario 1: Validación de formulario<br>**Dado** que el usuario deja campos obligatorios vacíos,<br>**Cuando** intenta enviar el formulario,<br>**Entonces** el sistema muestra mensajes de error.<br><br>- Escenario 2: Mostrar FAQs<br>**Dado** que el usuario entra a la sección de Ayuda,<br>**Cuando** abre la pestaña de preguntas frecuentes,<br>**Entonces** se despliega la lista de FAQs. |


**EP08 – Exploración como Visitante**

| ID Épica | Épica                      | ID   | Título                                                    | Descripción                                                                                       | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                           |
| -------- | -------------------------- | ---- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP08     | Exploración como Visitante | US26 | Ver información general sobre SmartStay                   | Como visitante, quiero ver información general sobre SmartStay para conocer la plataforma.        | - Escenario 1: Información visible<br>**Dado** que el visitante entra al landing page,<br>**Cuando** carga la página,<br>**Entonces** el sistema muestra información general de SmartStay.                                                                                                                                                                                                                        |
| EP08     | Exploración como Visitante | US27 | Conocer beneficios de usar la plataforma                  | Como visitante, quiero conocer los beneficios de usar la plataforma para evaluar su utilidad.     | - Escenario 1: Ver beneficios<br>**Dado** que el visitante está en el landing,<br>**Cuando** navega hacia la sección de beneficios,<br>**Entonces** el sistema muestra los principales beneficios destacados.                                                                                                                                                                                                     |
| EP08     | Exploración como Visitante | US28 | Acceder fácilmente al registro o login                    | Como visitante, quiero acceder fácilmente al registro o login para empezar a usar la plataforma.  | - Escenario 1: Acceso desde botones<br>**Dado** que el visitante está en el landing,<br>**Cuando** hace clic en “Registrarse” o “Iniciar sesión”,<br>**Entonces** el sistema lo redirige a la página correspondiente.                                                                                                                                                                                             |
| EP08     | Exploración como Visitante | TS08 | Implementar landing page con botones hacia login/registro | Como desarrollador, quiero implementar el landing page con botones claros hacia login y registro. | - Escenario 1: Botones funcionales<br>**Dado** que el visitante hace clic en “Registrarse” o “Iniciar sesión”,<br>**Cuando** se procesa la acción,<br>**Entonces** el sistema lo redirige correctamente.<br><br>- Escenario 2: Diseño responsive<br>**Dado** que el visitante accede desde un dispositivo móvil,<br>**Cuando** carga el landing,<br>**Entonces** el contenido se adapta al tamaño de la pantalla. |


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


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
| U202019498 |Fernandez Garfias |  Alexander Piero|
| u20191c464 |Saavedra Angulo   |  Jose Jhonatan  |
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
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta**                                | **Italo Sebastian Verona Flores**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 2**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 3**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 4**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Natalia Ximena Valverde Portuguez**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas) | *TB1*<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1] |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Italo Sebastian Verona Flores**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 2**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 3**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Integrante 4**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas)<br><br>**Natalia Ximena Valverde Portuguez**<br>*TB1*<br>Colocar que hiciste en la TB1 (Acciones realizadas) | *TB1*<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1]<br>• [Colocar conclusiones del equipo para TB1] |
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

## 3.2. Impact Mapping.

## 3.3. Product Backlog.

# Capítulo IV: Product Design

## 4.1. Style Guidelines

Nuestra base es establecer la identidad visual y de diseño de Smart Stay, asegurando coherencia, claridad y usabilidad en todos los puntos de contacto de la marca, tanto en medios digitales como en experiencias del usuario.

Objetivo:
- Alinear la comunicación visual y de producto con la misión de la startup.
-	Garantizar una experiencia de usuario clara, accesible y atractiva.
-	Facilitar la integración de diseño en web y aplicaciones móviles con un lenguaje unificado.

### 4.1.1. General Style Guidelines

**Branding**

- Logo Rewind: El logo principal de la startup con el que se muestra ante el público.

![logo.png](assets/logo.png)
  
- Logo Modo Oscuro: Este logo es creado para contrastar en fondos oscuros, lo cual permite la protección de la vista del usuario y favorece el rendimiento de la batería de su dispositivo.

![logo-modo-oscuro.png](assets/logo-modo-oscuro.png)

- Logo Plus: Es una versión del logo con un color que resalta más elegancia, el cual se usa para los usuarios que opten por usar la suscripción plus del servicio.

![logo-plus.png](assets/logo-plus.png)

- Logo Plus Modo Oscuro: Tiene la misma función que el logo modo oscuro con la diferencia de que sirve para la suscripción plus.

![logo-plus-modo-oscuro.png](assets/logo-plus-modo-oscuro.png)
  
- Logos Monocromáticos: Logos con paleta de colores blanco y negro, cuyo uso es exclusivo para impresiones y documentos.

![logo-monocromatico-1.png](assets/logo-monocromatico-1.png)
![logo-monocromatico-2.png](assets/logo-monocromatico-2.png)

**Tipografia**

- Fuente principal (Brand & Títulos):
  Cocomat Pro
  Uso: Logo, headers, títulos principales en la app/web.
  Razón: Da un aire moderno y premium, con un estilo limpio que refuerza la identidad de la marca.
  
- Fuente secundaria (Texto y párrafos)
  Open Sans o Lato
  Uso: Textos descriptivos, botones, menús, correos y cualquier contenido largo.
  Razón: Son altamente legibles en pantallas, versátiles y complementan la elegancia de Cocomat Pro sin competir con ella.
  
-Jerarquía de uso
1. Títulos (H1, H2): Cocomat Pro Bold.
2. Subtítulos / énfasis: Cocomat Pro Medium.
Texto general / párrafos: Open Sans Regular.
Botones y menús: Open Sans SemiBold.

- Sistema Tipográfico 
H1 (Títulos principales):
Cocomat Pro Bold – 32px

H2 (Subtítulos / secciones):
Cocomat Pro Medium – 24px

H3 (Bloques / cards):
Cocomat Pro Medium – 20px

Texto cuerpo (párrafos):
Open Sans Regular – 16px

Texto secundario / notas:
Open Sans Regular – 14px

Botones primarios:
Open Sans SemiBold – 16px (MAYÚSCULAS)

![fuentes-imagen.png](assets/fuentes-imagen.png)

**Paleta de colores**
Espaciado de líneas: 1.5x en párrafos para mayor legibilidad.
Uso de color:
- Primario: Azul Marino (#2C3E91) → solidez, profesionalismo.
- Secundario: Dorado/Naranja Suave (#E67E22) → lujo, calidez.
- Neutros: Beige (#F5F5DC), Gris medio (#BDC3C7), Blanco (#FFFFFF).
- Apoyos: Verde agua (#1ABC9C) → frescura, sostenibilidad.

![color-image.png](assets/color-image.png)

**Dimensiones**
- Cercano y humano: Hablar como si fueras un amigo confiable, sin tecnicismos innecesarios.
- Claro y directo: Frases cortas, fáciles de entender, sin rodeos.
- Inspirador: Transmitir seguridad y motivación para que el usuario sienta que tomó la mejor decisión.
- Profesional pero cálido: Ni demasiado rígido ni demasiado informal.
  
### 4.1.2. Web Style Guidelines

**Páginas principales**

- Home: enfoque en storytelling + CTA (“Probar demo”).
- Productos: módulos claros (cards azules) con descripciones cortas.
- Soluciones: bloques con imágenes + botones de acción (descargar brochure).
- Precios:  tabla comparativa clara (Plan Normal vs Plan Plus).
![paginas_principales.png](assets/paginas_principales.png)

**Encabezados Hero (Landing)**

- Imagen grande en 16:9 con overlay oscuro: refuerza contraste con texto.
- Texto principal: H1 32px, Cocomat Pro Bold en blanco.
- Botón destacado (CTA): Naranja Suave (#E67E22) en mayúsculas.
![encabezado_hero.png](assets/encabezado_hero.png)

**Cards y Bloques de Contenido**

- Fondo azul marino (#2C3E91), texto blanco.
- Iconografía minimalista y consistente.
- Bordes redondeados 12px + sombra suave.
- Espaciado interno: 24px padding.
- Uso de grillas para mantener equilibrio visual.
![bloques.png](assets/bloques.png)

**Tablas Comparativas (Precios)**

- Fondo alternado con colores que definen los planes para mejorar lectura.
- Encabezados fijos con H2 Medium 24px.
- Marca de “incluido” en check.
- Elementos no incluidos  sin check.
- Botón “Mejorar plan” en naranja como llamada a la acción final.
![plan.png](assets/plan.png)

**Footer**

- Fondo azul marino sólido.
- Texto en blanco y gris claro.
- Columnas organizadas con links en Open Sans 14px.
- Inclusión de iconos sociales en fila inferior.
![footer.png](assets/footer.png)

**Uso de Color en Web**

-Azul Marino (#2C3E91) → fondos de bloques, navegación, footer.
-Naranja Suave (#E67E22) → CTAs principales.
-Verde Agua (#1ABC9C) → énfasis positivo (checks, beneficios, “incluido”).
-Beige (#F5F5DC) → fondos neutros para separar secciones.

**Comportamiento UX**

- Hover Cards → elevación (sombra) + cambio leve en tono de fondo.
- Hover Botones → transición 0.3s de azul → naranja.
- Scroll suave en anclas de página.
- Menú sticky superior para navegación rápida.
![final.png](assets/final.png)
  
## 4.2. Information Architecture

**UX Heuristics & Principles Evaluation**

**Usability – Inclusive Design – Information Architecture**

-CARRERA: Ingeniería de Software  
-CURSO: Desarrollo de Aplicaciones Open Source  
-SECCIÓN: 7454  
-PROFESORES: Todos  
-AUDITOR: Nombre del Grupo el cual está encargado de evaluar 
-CLIENTE(S): Administradores de Hoteles Boutique y Huéspedes de Hoteles  
-SITE o APP A EVALUAR: Smart Stay

**TAREAS A EVALUAR**

**Segmento Objetivo #1: Administradores de Hoteles Boutique y Pequeños en Lima**  
- Gestionar reservas: claridad en el calendario y sincronización con canales externos.  
- Notificaciones automáticas: facilidad para configurar alertas de check-in/check-out y limpieza.  
- Reportes: acceso rápido a reportes de ocupación y facturación.  
- Seguridad: control de accesos internos para el personal.  

**Segmento Objetivo #2: Huéspedes de Hoteles**  
- Realizar check-in/out digital: facilidad, rapidez y disponibilidad desde la app.  
- Control desde el celular: acceso a funciones de la habitación (llaves digitales, temperatura, Wi-Fi).  
- Personalización de la estadía: opciones visibles de preferencias (horarios, limpieza, amenities).  
- Comunicación con el hotel: claridad y rapidez en canales de contacto digital.  

**No incluidas en esta versión de la evaluación:**  
- Procesos de facturación avanzada.  
- Integración con marketplaces globales.  
- Funcionalidades de marketing interno del hotel.  

**ESCALA DE SEVERIDAD** 

| Nivel | Descripción |
|-------|-------------|
| **1** | Problema superficial: puede ser superado fácilmente. No requiere arreglo inmediato. |
| **2** | Problema menor: afecta ocasionalmente la experiencia. Resolución de baja prioridad. |
| **3** | Problema mayor: ocurre frecuentemente y afecta la experiencia de forma significativa. Requiere corrección prioritaria. |
| **4** | Problema muy grave: impide continuar con la tarea. Requiere corrección inmediata antes del lanzamiento. |


**TABLA RESUMEN**  

| # | Problema | Escala de severidad | Heurística/Principio violado |
|---|----------|---------------------|-------------------------------|
| 1 | Reservas no muestran disponibilidad en tiempo real (riesgo de sobreventa). | 3 | Usabilidad: Visibilidad del estado del sistema. |
| 2 | Notificaciones poco configurables y sin opciones personalizadas. | 2 | Flexibilidad y eficiencia de uso. |
| 3 | Reportes de ocupación y facturación poco visibles en el dashboard. | 2 | Visibilidad y reconocimiento antes que recuerdo. |
| 4 | Botón de check-in digital en la app es poco visible en la pantalla de inicio. | 3 | Usabilidad: Visibilidad del estado del sistema. |
| 5 | El control desde la app (llaves digitales, limpieza) no está claramente explicado. | 2 | Coincidencia entre el sistema y el mundo real. |


**DESCRIPCIÓN DE PROBLEMAS**

**SEGMENTO: Administradores de Hoteles**
- **Severidad: 3 – Visibilidad del estado del sistema**  
  - Problema: El calendario de reservas no refleja actualizaciones en tiempo real con plataformas externas.  
  - Recomendación: Implementar sincronización inmediata con canales externos (Booking, Airbnb, etc.) y estados visuales claros de disponibilidad.  

- **Severidad: 2 – Flexibilidad y eficiencia de uso**  
  - Problema: Las notificaciones automáticas no permiten personalizar mensajes ni frecuencia.  
  - Recomendación: Añadir un panel de configuración flexible con plantillas y horarios definidos por el administrador.  

- **Severidad: 2 – Reconocimiento antes que recuerdo**  
  - Problema: Los reportes se encuentran en un submenú poco visible.  
  - Recomendación: Colocar accesos rápidos en el dashboard inicial y usar iconografía clara.  


**SEGMENTO: Huéspedes de Hoteles**  

- **Severidad: 2 – Coincidencia entre el sistema y el mundo real**  
  - Problema: El control de la habitación desde la app (llaves digitales, limpieza, Wi-Fi) no cuenta con guías visuales.  
  - Recomendación: Incluir íconos representativos y tutoriales cortos dentro de la app.  

- **Severidad: 3 – Ayuda y documentación**  
  - Problema: No existe chat directo con la recepción del hotel; solo un formulario genérico.  
  - Recomendación: Incorporar mensajería en tiempo real con la recepción.  

- **Severidad: 2 – Accesibilidad universal**  
  - Problema: Algunos botones presentan bajo contraste en modo claro (ejemplo: naranja sobre beige).  
  - Recomendación: Ajustar colores con ratio de contraste mínimo 4.5:1 siguiendo WCAG 2.1.  

### 4.2.1. Organization Systems

En el diseño de interfaces digitales centradas en el usuario, el Sistema de Organización es el componente de la arquitectura de información encargado de definir cómo se   agrupan, clasifican y presentan los contenidos dentro de la plataforma. Su objetivo principal es que los usuarios puedan explorar, comprender y acceder a la información de manera rápida e intuitiva, reduciendo la carga cognitiva y mejorando la usabilidad en sus interacciones con el producto.

Para Smart Stay, se ha implementado un sistema de organización híbrido que combina estructuras jerárquicas y funcionales. En la Landing Page, el contenido se distribuye en bloques según su prioridad: primero se destacan las llamadas a la acción principales, como “Probar Demo” y seguidas de la propuesta de valor de la plataforma . El encabezado (header) y pie de página (footer) refuerzan esta jerarquía al agrupar accesos principales y secundarios, permitiendo que los usuarios comprendan rápidamente qué ofrece Smart Stay y cómo navegar por ella, incluso desde dispositivos móviles, aplicando principios de progressive disclosure y adaptabilidad responsiva.

![organizationsystems.png](assets/organizationsystems.png)

**Link para visualizar mejor:** [https://shorturl.at/7UPcY](https://lucid.app/lucidchart/c2895e86-0754-454b-9efb-d0f274918a3b/edit?viewport_loc=-1463%2C-581%2C3504%2C1441%2C0_0&invitationId=inv_f4b1886d-203a-4341-a7aa-50cbe423a0ad)

En Application Wen, el contenido se distribuye en bloques según su prioridad: primero se accede a través de Login y si aún no se tiene cuenta pasas por Register, en el Login se selecciona el modo de usuario y una vez ingresas te deriva al modo de aplicación según el modo seleccionado. En cada modo se desglosa a través del menú y los botones de herramientas ubicados en la esquina superior.

![organizationsystems2.png](assets/organizationsystems2.png)

**Link para visualizar mejor:** [https://shorturl.at/7UPcY](https://lucid.app/lucidchart/83b0dc0e-542a-4bc9-8ac8-a1b59abaa464/edit?viewport_loc=-4786%2C-1265%2C7941%2C3266%2C0_0&invitationId=inv_6f1b4e45-f319-4624-a925-3bb6a7ec89a3)

### 4.2.2. Labeling Systems

| Etiqueta | Ubicación / Componente | Función |
|----------|----------------------|---------|
| Home | Header | Enlace a la Landing Page. Claro y universal. |
| Services | Header | Información sobre los servicios disponibles (alojamiento, limpieza, extras). Directo y comprensible. |
| Bookings | Header | Acceso a la sección de reservas. Término estándar y reconocido. |
| Contact | Header | Formulario de contacto o enlace de correo. Directa y orientada a la acción. |
| Sign Up | Header (botón) | Registro de nuevos usuarios. Corto, amigable y visualmente destacado. |
| Login | Header (botón) | Inicio de sesión de usuarios. Palabra ampliamente reconocida. |
| Try Demo | Hero Section (CTA principal) | Llamada a la acción principal para probar la demo. Imperativo que motiva la interacción. |
| Benefits | Hero Section / Sección de valor | Destaca las ventajas de la plataforma. Claro y enfocado al usuario. |
| Testimonials | Sección de valor | Muestra opiniones de usuarios. Genera confianza y credibilidad. |
| About | Footer / Company | Información institucional sobre Smart Stay. Claro y directo. |
| Privacy Policy | Footer / Legal | Obligatorio por normativa. Etiqueta reconocida internacionalmente. |
| Terms & Conditions | Footer / Legal | Complementa la política de privacidad. Estándar legal indispensable. |
| Social Media | Footer / Navigation | Agrupa enlaces a redes oficiales. Convencional y reconocible globalmente. |
| Smart Stay | Marca | Nombre distintivo de la plataforma. Funciona como ancla visual y semántica. |

### 4.2.3. SEO Tags and Meta Tags

Los SEO tags y meta tags son elementos clave dentro de la Landing Page y cualquier página web, porque permiten que los motores de búsqueda comprendan el contenido, mejoren la visibilidad y aumenten la tasa de clics desde resultados de búsqueda. Además, algunas etiquetas influyen directamente en cómo se muestra la página en redes sociales y en navegadores móviles.
La landing page de SmartStay incluye los siguientes SEO/meta tags: charset, viewport, title, description, keywords y favicon. Estos permiten definir la codificación, hacer la página responsive, dar un título y descripción para los buscadores, y mostrar un ícono en la pestaña del navegador.

**Meta charset**

```html
<meta charset="UTF-8">
```

- Define la codificación de caracteres de la página.
- Importante para que los navegadores interpreten correctamente acentos y caracteres especiales.

**Meta viewport**

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

- Hace que la página sea responsive, ajustando la visualización a distintos dispositivos.

**Tittle**

```html
<title>Tu título de landing page</title>
```

- Es el texto que aparece en la pestaña del navegador.
- Muy importante para SEO, ya que los motores de búsqueda lo usan como encabezado principal de tu página.

**Meta description**

```html
<meta name="description" content="Breve descripción de tu landing page">
```

- Ayuda a los buscadores a mostrar un resumen en los resultados de búsqueda.
- Clave para mejorar CTR (click-through rate).

**Meta keywords**

```html
<meta name="keywords" content="palabra1, palabra2, palabra3">
```

- Hoy en día ya no tiene mucho peso para SEO, pero algunas personas aún la incluyen.

**Favicon**

```html
<link rel="icon" href="favicon.ico">
```

- Icono de la pestaña del navegador.
- No impacta SEO, pero sí la experiencia de usuario.

### 4.2.4. Searching Systems

El Searching System de Smart Stay permite a los usuarios localizar información, reservas, servicios o productos de manera rápida y eficiente.
En la Landing Page, la búsqueda está orientada a descubrir información general sobre la plataforma, con barra de búsqueda, autocompletado y enlaces directos a secciones clave como “Try Demo” o “Benefits”.
En la Web App, la búsqueda es más funcional y permite filtrar y ordenar datos concretos como huéspedes, reservas y servicios, aplicando autocompletado, filtros dinámicos y persistencia de resultados para mejorar la experiencia del usuario.
El sistema se diseña siguiendo principios de intuitividad, consistencia, visibilidad y escalabilidad, asegurando que los usuarios siempre encuentren lo que buscan de manera rápida y clara.

| Search Type | Location / Component | Function |
|------------|--------------------|---------|
| General Search | Landing Page / Header | Permite buscar información general sobre la plataforma y sus servicios (ej. "services", "demo", "benefits"). Incluye autocompletado y filtros básicos. |
| Try Demo / Benefits Links | Landing Page / Hero & Value Sections | Funciona como búsqueda indirecta, guiando al usuario hacia contenido relevante sin necesidad de escribir. |
| Guest / Customer Search | Web App / Guests Section | Permite filtrar por nombre, ID, tipo de habitación o fecha de reserva. Facilita gestión de usuarios. |
| Bookings Search | Web App / Bookings Section | Filtrado por fechas, estado de reserva (pendiente, confirmada, cancelada) y tipo de servicio. |
| Services & Products Search | Web App / Services & Products Section | Filtrado por categoría (limpieza, comida, amenities), disponibilidad y precios. |
| Autocomplete | Web App / All Search Fields | Sugerencias dinámicas mientras se escribe para acelerar la búsqueda y mejorar experiencia de usuario. |
| Dynamic Filters | Web App / All Search Results | Ajusta los resultados en tiempo real según criterios seleccionados. |
| Sorting | Web App / All Search Results | Permite ordenar resultados por fecha, nombre, prioridad o relevancia. |
| Search Persistence | Web App / All Sections | Mantiene los filtros y resultados de búsqueda mientras el usuario navega dentro de la misma sección. |

### 4.2.5. Navigation Systems

**Landing Page Navigation**

| Navigation Item | Location / Component | Function |
|-----------------|--------------------|---------|
| Home | Header | Enlace a la Landing Page. Permite regresar al inicio desde cualquier sección. |
| Services | Header | Acceso rápido a la sección de servicios disponibles. |
| Bookings | Header | Permite al usuario gestionar reservas desde cualquier lugar. |
| Contact | Header | Enlace al formulario de contacto o correo de soporte. |
| Sign Up | Header (button) | Registro de nuevos usuarios. Destacado visualmente. |
| Login | Header (button) | Acceso a la sesión del usuario. Fácil de localizar. |
| Try Demo | Hero Section (CTA principal) | Llamada a la acción principal para probar la demo de Smart Stay. |
| Benefits | Hero Section / Value Section | Navegación indirecta hacia los beneficios de la plataforma. |
| About | Footer / Company | Información institucional sobre Smart Stay. Acceso desde cualquier sección. |
| Privacy Policy | Footer / Legal | Enlace obligatorio por normativa legal. |
| Terms & Conditions | Footer / Legal | Complementa la política de privacidad. |
| Social Media | Footer / Navigation | Acceso a redes oficiales, visibilidad global. |

**Web App Navigation**

| Navigation Item | Location / Component | Function |
|-----------------|--------------------|---------|
| Guests | Sidebar | Sección principal para gestionar huéspedes o clientes. |
| Bookings | Sidebar | Sección principal para gestionar reservas y su estado. |
| Services | Sidebar | Sección principal para gestionar servicios disponibles. |
| Products | Sidebar | Sección para visualizar y administrar productos asociados. |
| Profile | Top Bar | Acceso a perfil de usuario, configuración y notificaciones. |
| Notifications | Top Bar | Acceso rápido a alertas y mensajes importantes. |
| Breadcrumbs | Optional | Indica la ruta de navegación y permite regresar a secciones previas. |

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

Los wireframes representan la primera aproximación al diseño de la interfaz de Smart Stay.  
Se han desarrollado en formato blanco y negro, sin imágenes ni estilos gráficos, para enfocarse únicamente en la estructura, disposición de los elementos y flujo de navegación.  

El objetivo de estos wireframes es:
- Establecer la arquitectura de información de la plataforma.  
- Definir la jerarquía de contenidos en cada sección.  
- Validar la navegación y experiencia de usuario antes de pasar al diseño visual (mockups).  

A continuación, se presenta un resumen de cada una de las secciones.

**1. Home**
- **Propósito:** Página principal de presentación de Smart Stay.  
- **Elementos clave:**  
  - Encabezado con menú de navegación.  
  - Hero con nombre de la plataforma y botón de llamada a la acción (*CTA: Probar demo*).  
  - Sección "¿Quiénes somos?" con breve descripción.  
  - Bloques de beneficios y características principales.  
  - Footer con enlaces de contacto, políticas y redes sociales.
![whome.png](assets/whome.png)


**2. Productos**
- **Propósito:** Mostrar los productos y módulos de la plataforma.  
- **Elementos clave:**  
  - Lista de funcionalidades divididas en áreas: gestión hotelera, experiencia del huésped, reportes, seguridad.  
  - Descripción breve de cada módulo.  
  - Botón de descarga de brochure.
  ![wproductos.png](assets/wproductos.png)

**3. Soluciones**
- **Propósito:** Explicar cómo Smart Stay se adapta a diferentes tipos de hoteles.  
- **Elementos clave:**  
  - Sección para hoteles boutique.  
  - Sección para alojamientos alternativos.  
  - Sección para cadenas hoteleras.  
  - Botón para descargar información detallada.
  ![wsoluciones.png](assets/wsoluciones.png)


**4. Precios**
- **Propósito:** Detallar planes y costos de la plataforma.  
- **Elementos clave:**  
  - Tabla comparativa de funcionalidades entre Plan Normal y Plan Plus.  
  - Categorías claras: gestión hotelera, experiencia huésped, seguridad, soporte.
![wsprecios.png](assets/wsprecios.png)

**5. Casos de Éxito**
- **Propósito:** Mostrar testimonios y ejemplos de hoteles que ya usan Smart Stay.  
- **Elementos clave:**  
  - Bloques con testimonios de clientes.  
  - Descripción breve de resultados obtenidos (ahorro de tiempo, mejora de experiencia, reducción de costos).
  ![wreseñas.png](assets/wreseñas.png)  

**6. Recursos**
- **Propósito:** Repositorio de materiales de apoyo y aprendizaje.  
- **Elementos clave:**  
  - Documentos descargables (guías, whitepapers, brochures).  
  - Links de blogs.  
![wrecurso.png](assets/wrecurso.png)

**7. Registro**
- **Propósito:** Permitir que un nuevo usuario cree su cuenta.  
- **Elementos clave:**  
  - Formulario de registro con campos básicos (nombre, correo, contraseña, tipo de empresa).  
  - Botón de registro.  
![wregister.png](assets/wregister.png)

**8. Login**
- **Propósito:** Acceso de usuarios ya registrados.  
- **Elementos clave:**  
  - Formulario de inicio de sesión con correo y contraseña.  
  - Botón de acceso.  
  - Enlace a recuperación de contraseña y a registro.  
![wlogin.png](assets/wlogin.png)

Los wireframes definen la base de navegación de Smart Stay, asegurando que cada sección tenga un propósito claro:  
- **Home:** captar atención y presentar la plataforma.  
- **Productos, Soluciones, Precios:** comunicar valor y opciones.  
- **Casos de Éxito, Recursos:** generar confianza y soporte.  
- **Registro y Login:** habilitar el acceso a la app.  


### 4.3.2. Landing Page Mock-up

Tras la validación de los wireframes, se desarrollaron los mockups de alta fidelidad de Smart Stay.  
Estos mockups ya incorporan la identidad visual definida (colores, tipografía, logotipo e imágenes), con el objetivo de reflejar la experiencia final que tendrán los usuarios en la plataforma.  

Su propósito es:
- Validar la usabilidad con un diseño más realista.  
- Asegurar la coherencia con la guía de estilos definida.  
- Proyectar cómo se verá cada sección en un entorno final.  

**1. Landing Page**
- **Cambios respecto al wireframe:**  
  - Se añadió el logotipo de Smart Stay en el header.  
  - Paleta de colores aplicada (azul corporativo + tonos complementarios).  
  - Imagen de fondo en el Hero con llamada a la acción resaltada (“Probar demo”).  
  - Iconografía personalizada para los beneficios.  
![home.png](assets/home.png)

**2. Productos**
-**Cambios respecto al wireframe:**  
  - Uso de íconos y colores diferenciados por módulo (gestión, experiencia huésped, seguridad, reportes).  
  - Inclusión de imágenes ilustrativas.  
  - Botón de descarga estilizado con colores de la marca.  
![producto.png](assets/producto.png)

**3. Soluciones**
- **Cambios respecto al wireframe:**  
  - Bloques visuales para cada tipo de cliente (hoteles boutique, alojamientos alternativos, cadenas).  
  - Uso de fotografías representativas de hoteles.  
  - CTA destacado.
![soluciones.png](assets/soluciones.png)

**4. Precios**
- **Cambios respecto al wireframe:**  
  - Tabla de precios con colores diferenciadores por plan.  
  - Plan recomendado resaltado con un fondo destacado.  
  ![precio.png](assets/precio.png)

**5. Casos de Éxito**
- **Cambios respecto al wireframe:**  
  - Testimonios acompañados de logos reales de hoteles.  
![reseña.png](assets/reseña.png)

**6. Recursos**
- **Cambios respecto al wireframe:**  
  - Secciones de miniaturas de documentos descargables.  
  - Secciones de blog con botón de visitar página externa.
![recursos.png](assets/recursos.png)

**7. Registro**
- **Cambios respecto al wireframe:**  
  - Formulario minimalista con campos estilizados.  
  - Botón de “Enviar y registrar” resaltado en color primario.  
  - Fondo con imagen ligera para dar contexto al servicio.
  ![register.png](assets/register.png)

**8. Login**
- **Cambios respecto al wireframe:**  
  - Formulario ubicado a lateral izquierdo en pantalla con diseño limpio.  
  - Logo al lado derecho de la pantalla.  
  - Enlaces secundarios estilizados para “¿Olvidaste tu contraseña?”.  
![login.png](assets/login.png)

Los mockups consolidan el diseño visual final de Smart Stay, transformando la estructura básica de los wireframes en interfaces listas para evaluación estética y funcional.  


## 4.4. Web Applications UX/UI Design
En esta sección de Web Applications UX/UI Design ya nos enfocamos en el diseño de la interfaz y la experiencia de usuario de nuestro explicativo el cual se menciona e informa en el landing page, cabe resaltar que el el aplicativo es difernte según el rol que forman parte de la solución digital: administrador, staff y huéspedpor lo que su funcionamiento es distinto. Aquí se visualizará el prototipo de cada app y a su vez se presentará en la forma más práctica según su rol, formato desktop para administrados y formato móvil para staff y huésped, aunque los tres cuentan con diseño responsive por lo que se puede usar de cualquier dispositivo móvil.

### 4.4.1. Web Applications Wireframes

**Wireframes – Modo Administrador**


Los wireframes del **modo Administrador** representan la primera aproximación al diseño de la interfaz de esta vista de la aplicación.  
Se han elaborado en formato blanco y negro, sin imágenes ni estilos gráficos, con el objetivo de centrarse en la estructura, navegación y jerarquía de la información que manejará el administrador.  

A continuación, se presenta un resumen de cada una de las secciones principales del modo Administrador.  

**1. Dashboard**
**Propósito:** Vista general del estado de la plataforma.  
**Elementos clave:**  
- Panel con métricas principales (usuarios activos, reportes recientes, accesos).  
- Gráficas de estadísticas generales.  
- Acceso rápido a notificaciones.  

**2. Huéspedes**
**Propósito:** Control y administración de los perfiles que usan la plataforma.  
**Elementos clave:**  
- Lista de usuarios con buscador y filtros.  
- Botón para agregar, editar o eliminar usuarios.  
- Tabla con información básica (nombre, correo, rol, estado).  

![wdashboard_huespedes.png](assets/wdashboard_huespedes.png)

**3. Staff**  
**Propósito:** Definir los niveles de acceso de cada tipo de usuario.  
**Elementos clave:**  
- Tabla de roles existentes.  
- Información y datos del staff con el que trabaja.  

**4. Hoteles y habitaciones**  
**Propósito:** Gestión de la cadena hotelera administrada en la plataforma.  
**Elementos clave:**  
- Lista de hoteles con buscador y filtros (ciudad, estado, categoría).  
- Detalle del hotel seleccionado (información general, servicios, estadísticas).  
- Campo para ingresar número de habitación y botón *Ver detalle*.  
- Vista de detalle de habitación con estado, tipo, huésped actual, check-in/out y acciones rápidas.   

![wstaff_hoteles.png](assets/wstaff_hoteles.png)

**5. Reservas** 
**Propósito:** Control y gestión de todas las reservas realizadas en los hoteles.  
**Elementos clave:**  
- Calendario interactivo para visualizar y administrar reservas por día, semana o mes.  
- Lista de reservas con buscador y filtros (hotel, fecha, estado).  
- Detalle de la reserva (huésped, habitación, fechas, monto).  
- Botones para modificar, confirmar o cancelar reservas.  
- Indicadores de ocupación y disponibilidad directamente desde el calendario. 

**6. Pagos**  
**Propósito:** Administración de ingresos y egresos financieros en la plataforma.  
**Elementos clave:**  
- Registro de pagos recibidos de huéspedes y clientes.  
- Registro de egresos: pagos a staff, proveedores y compras de stock.  
- Tablas y filtros por fecha, hotel, método de pago y categoría.  
- Reportes de gastos, ingresos y ganancias.  
- Gráficos comparativos y dashboard financiero.
  
![wreservas_gastos.png](assets/wreservas_gastos.png)

**7. Servicios y Productos**  
**Propósito:** Gestión integral de servicios y dispositivos tecnológicos de Smart Stay.  
**Elementos clave:**  
- Tabla general con categorías: limpieza, alimentos, tecnología, amenities.  
- Columnas: nombre, categoría, estado, stock, ubicación, proveedor.  
- Filtros por hotel, piso, habitación y categoría.  
- Vista de detalle de cada producto con historial, estado y mantenimiento.  

**8. Reseñas**  
**Propósito:** Seguimiento de la experiencia de los huéspedes y tickets de soporte.  
**Elementos clave:**  
- Lista de comentarios y calificaciones por hotel y servicio.  
- Filtros por fecha, hotel, tipo de reseña o ticket.  
- Vista de detalle con respuesta del staff.  
- Estadísticas de satisfacción y gráficos de tendencias.  
- Panel de tickets: abiertos, en proceso, cerrados.  
![wservicio_producto_reseña.png](assets/wservicio_producto_reseña.png)

**9. Soporte**  
**Propósito:** Gestión de los tickets creados por los hoteles y usuarios hacia Smart Stay.  
**Elementos clave:**  
- Lista de tickets recibidos desde los hoteles o usuarios.  
- Clasificación por prioridad (alta, media, baja) y estado (pendiente, en proceso, resuelto).  
- Filtros por hotel, tipo de problema y fecha.  
- Vista de detalle del ticket con historial de comunicación.  
- Historial de ticket.
![wsoporte.png](assets/wsoporte.png)

**Wireframes – Modo Huésped**

Los wireframes del modo Huésped representan la primera aproximación al diseño de la interfaz de esta vista de la aplicación huesped, el cual ellos ingresanpor un codigo qr que el hotel les brinda para de frente acceder al app huesped.  
Se han elaborado en formato blanco y negro, sin imágenes ni estilos gráficos, con el objetivo de centrarse en la estructura, navegación y jerarquía de la información que manejará el huésped.  

**1. Pantalla de Bienvenida**
- Solo es una introducción por lo que aparece el logo y un saludo.
  
**2. Inicio**
**Propósito:** Pantalla principal con acceso a las funciones más utilizadas.  
**Elementos clave:**  
- Barra superior con logo y buscador.  
- Banner de bienvenida.  
- Acceso rápido a habitaciones, servicios y notificaciones.  
- Sección de ofertas o promociones destacadas.
  
**3. Habitaciones**
**Propósito:** Explorar y seleccionar opciones de hospedaje.  
**Elementos clave:**  
- Información básica (número y estado de habitación).  
- Controles de ambiente: temperatura, luces, cortinas, TV, música.  
- Servicios rápidos: limpieza inmediata o programada, amenities, minibar digital.  
- Botón de asistencia y emergencia.  
![wapphuesped1.png](assets/wapphuesped1.png)

**4. Servicios**
**Propósito:** Acceder a servicios adicionales ofrecidos por el hotel.  
**Elementos clave:**  
- Categorías de servicios (gimnasio, parking, restaurante, eventos).
  
**5. Mapa & Explorar**
**Propósito:** Orientar al huésped dentro del hotel y ofrecer rutas y descubrimientos locales.  
**Elementos clave:**  
- Mapa interactivo del hotel con puntos de interés (piscina, gimnasio, restaurantes, lobby, salones).  
- Indicación de la ubicación de la habitación del huésped y rutas internas (wayfinding) hacia cualquier punto.  
- Opciones de búsqueda y filtros (por tipo de servicio, accesibilidad, horarios).  
  
**6. Perfil**
**Propósito:** Gestionar los datos del huésped.  
**Elementos clave:**  
- Información personal (nombre, correo, teléfono).  
- Preferencias de pago y métodos guardados.  

**7. Notificaciones**
**Propósito:** Informar al huésped sobre novedades y recordatorios.  
**Elementos clave:**  
- Lista de notificaciones recientes (confirmaciones de reserva, promociones, mensajes del hotel).  
- Botón para marcar como leídas o eliminar notificaciones.  
![wapphuesped2.png](assets/wapphuesped2.png)

**Wireframes – Modo Staff**

Los wireframes del modo Staff representan la primera aproximación al diseño de la interfaz de esta vista de la aplicación.  
Se han elaborado en formato blanco y negro, sin imágenes ni estilos gráficos, con el objetivo de centrarse en la estructura, navegación y jerarquía de la información que manejará el personal del hotel.

**1. Introducción**
**Propósito:** Pantalla inicial de bienvenida y presentación de la app Staff.  
**Elementos clave:**  
- Logo.  
- Breve mensaje de bienvenida.

**2. Login**
**Propósito:** Autenticar al personal del hotel para acceder a la app.  
**Elementos clave:**  
- Campos de correo electrónico y contraseña.  
- Botón de Iniciar Sesión.  
- Opción de Recuperar contraseña.  

**3. Home / Dashboard**
**Propósito:** Pantalla principal con resumen de tareas y registro de horas.  
**Elementos clave:**  
- Registro de horas: botones para marcar Entrada, Receso y Salida.  
- Tabla de historial diario de horas trabajadas.  
- Lista resumida de tareas del día con estado (pendiente/completado).  

**4. Tareas**
**Propósito:** Gestionar todas las tareas asignadas al staff.  
**Elementos clave:**  
- Lista completa de tareas diarias con habitación, tipo de tarea, piso.  
- Estado de tarea con emoticonos: ✅ Completado / ❌ Pendiente.     
![wappstaff1.png](assets/wappstaff1.png)

**5. Servicios / Productos**
**Propósito:** Registrar entrega de servicios y productos a habitaciones.  
**Elementos clave:**  
- Lista de servicios/productos por entregar (Room Service, Mini Bar, Amenities, etc.).  
- Cantidad y habitación correspondiente.  
- Estado de entrega con emoticonos: ✅ Entregado / ❌ Pendiente.  

**6. Reservas**
**Propósito:** Consultar y gestionar reservas asignadas al staff.  
**Elementos clave:**  
- Sección de búsqueda de cliente.  
- Lista de reservas con habitación, huésped, fecha, estado de check-in/check-out.  
- Semáforo de estados: 🔴 Pendiente / 🟢 Completado.  

**7. Perfil**
**Propósito:** Gestionar la información personal del staff y las preferencias de la app.  
**Elementos clave:**  
- Foto y datos personales (nombre, correo, teléfono).  
- Cambiar contraseña, editar y cerrar sesión.  

**8. Notificaciones**
**Propósito:** Informar al staff sobre novedades, cambios de tareas o alertas importantes.  
**Elementos clave:**  
- Lista de notificaciones recientes (cambios de turno, emergencias, avisos de tareas).  
- Botón para marcar como leído o eliminar notificaciones.  
![wappstaff2.png](assets/wappstaff2.png).

### 4.4.2. Web Applications Wireflow Diagrams

**Web Applications Wireflow Diagrams – Modo Administrador**

**Propósito:**  
Mostrar cómo cada sección del administrador se conecta a través del menú principal.
![webwireflowadmi.png](assets/webwireflowadmi.png)

**Menú Principal (Administrador)**

Desde cualquier sección, el menú permite acceder a:

1. **Dashboard** – Resumen general de actividad, métricas y gráficos.
2. **Huéspedes** – Gestión de perfiles de usuarios; agregar, editar o eliminar.
3. **Staff** – Gestión del personal; roles, turnos y contacto.
4. **Hoteles / Habitaciones** – Administración de hoteles, habitaciones y disponibilidad.
5. **Reservas** – Calendario de reservas; agregar, modificar o cancelar reservas.
6. **Pagos** – Visualización y gestión de transacciones y estados de pago.
7. **Servicios / Productos** – Gestión de servicios del hotel y productos adicionales.
8. **Reseñas** – Panel de comentarios de huéspedes con gráficos de satisfacción.
9. **Soporte / Tickets** – Crear tickets de ayuda y consultar su estado.

**Flujo General (Wireflow)**

- **Dashboard**: centro de información y acceso rápido a todas las secciones.  
- **Menú Principal**: conecta directamente a las 9 secciones.  
- Secciones interrelacionadas:  
  - **Reservas ↔ Pagos ↔ Servicios / Productos**  
  - **Huéspedes ↔ Reservas ↔ Reseñas**  
  - **Staff ↔ Hoteles / Habitaciones**  
- **Soporte / Tickets**: siempre accesible desde cualquier sección para resolver inconveniencias.

**Web Applications Wireflow Diagrams – Modo Huésped**

**Propósito:**  
Mostrar cómo cada sección de la app para huéspedes se conecta a través del menú principal y elementos persistentes (como el icono de notificaciones).

![webwireflowhuesped.png](assets/webwireflowhuesped.png)

**Secciones Principales**

1. **Introducción** – Pantalla inicial, solo se conecta a **Home**.
2. **Home** – Vista principal; acceso a todas las secciones mediante el menú.
3. **Habitación** – Detalles de la habitación asignada o disponible; acceso desde el menú.
4. **Servicios** – Servicios del hotel disponibles para el huésped; acceso desde el menú.
5. **Mapa** – Ubicación del hotel, puntos de interés; acceso desde el menú.
6. **Perfil** – Datos del huésped, preferencias y configuración; acceso desde el menú.
7. **Notificaciones** – Alertas y mensajes importantes; acceso mediante un icono persistente arriba, visible desde todas las secciones.

**Flujo General (Wireflow)**

- **Introducción** → **Home**  
- **Home** → conecta a **Habitación**, **Servicios**, **Mapa**, **Perfil** mediante el menú principal.  
- **Notificaciones** → accesibles desde cualquier sección a través del icono superior.  

**Web Applications Wireflow Diagrams – Modo Staff**

**Propósito:**  
Mostrar cómo cada sección de la app para staff se conecta a través del menú principal y elementos persistentes (como el icono de notificaciones).
![webwireflowstaff.png](assets/webwireflowstaff.png)

**Secciones Principales**

1. **Introducción** – Pantalla inicial, conecta al **Login**.  
2. **Login** – Pantalla de acceso; una vez autenticado, va a **Home**.  
3. **Home** – Vista principal; acceso a todas las secciones mediante el menú.  
4. **Tareas** – Lista y gestión de tareas asignadas; acceso desde el menú.  
5. **Servicios** – Gestión de servicios ofrecidos por el staff; acceso desde el menú.  
6. **Reservas** – Visualización de reservas relacionadas con el staff; acceso desde el menú.  
7. **Perfil** – Datos del staff y configuración personal; acceso desde el menú.  
8. **Notificaciones** – Alertas y mensajes importantes; accesibles mediante un icono persistente que aparece en todas las secciones.

**Flujo General (Wireflow)**

- **Introducción** → **Login** → **Home**  
- Desde **Home** se puede acceder mediante el menú a: **Tareas**, **Servicios**, **Reservas**, **Perfil**  
- **Notificaciones** → accesibles desde cualquier sección a través del icono superior.

### 4.4.3. Web Applications Mock-ups

**Mockups – Modo Administrador**

Los mockups muestran la interfaz final del administrador de SmartStay, incluyendo **colores, tipografía, iconos, imágenes y logos**, reflejando la identidad visual de la plataforma.

**1. Dashboard**
- Paleta de colores corporativa aplicada a gráficos y métricas.  
- Gráficos circulares y de barras con animaciones.  
- Iconos para alertas, reservas y notificaciones.  
- Ilustraciones o imágenes para resaltar métricas clave.

**2. Huéspedes**
- Tarjetas visuales para cada huésped con foto, nombre y estado.  
- Botones coloreados según función (agregar: verde, eliminar: rojo).  
- Filtros y buscador estilizados con iconos.

**3. Staff**
- Tabla con fotos de perfil, roles y horarios.  
- Indicadores de estado con colores o iconos.  
- Botones consistentes con la paleta de SmartStay.

**4. Hoteles**
- Cards con imagen del hotel o miniaturas.  
- Indicadores visuales de ocupación y disponibilidad.  
- Botones de acción con efectos hover.

**5. Reservas**
- Calendario visual con colores según estado (confirmada, pendiente, cancelada).  
- Tarjetas de reserva con foto del huésped y detalles.  
- Botones destacados para aprobar, modificar o cancelar.

**6. Pagos**
- Tabla con iconos de métodos de pago (tarjeta, Yape, Plin).  
- Resaltado de pagos pendientes con color.  
- Botones para generar facturas con efectos visuales.

**7. Servicios y Productos**
- Cards o listas con imágenes de productos y servicios.  
- Indicadores de disponibilidad con colores y símbolos.  
- Botones con iconos para editar, eliminar o agregar.

**8. Reseñas**
- Panel con estrellas de puntuación y colores según valoración.  
- Tarjetas de comentarios con avatar del huésped y fecha.  
- Gráficos visuales de satisfacción general.

**9. Soporte**
- Tabla de tickets con colores según estado (pendiente, en proceso, finalizado).  
- Formulario visual con iconos y campos destacados.  
- Botones de acción consistentes con la paleta.

**Elementos generales**
- Logo de SmartStay visible en header o menú lateral.  
- Paleta de colores corporativa aplicada a fondos, botones y textos.  
- Tipografía uniforme que diferencia títulos, subtítulos y contenido.  
- Iconografía consistente para acciones, estados y navegación.  
- Feedback visual en botones e interacciones (hover, clic, activo).

![mockupadmin1.png](assets/mockupadmin1.png)
![mockupadmin2.png](assets/mockupadmin2.png)
![mockupadmin3.png](assets/mockupadmin3.png)

**Mockups – Modo Huésped**

Los mockups muestran la interfaz final del usuario huésped en SmartStay, incluyendo **colores, tipografía, iconos, imágenes y logos**, reflejando la identidad visual y la experiencia de usuario.

**1. Introducción**
- Pantalla de bienvenida con **logo y colores corporativos**.  
- **Imágenes o ilustraciones atractivas** para la experiencia inicial.  
- Botón destacado para comenzar y acceder a Home.

**2. Home**
- Panel con **resumen de reservas y notificaciones recientes**.  
- Cards visuales para acceder a habitaciones, servicios y mapa.  
- **Botones e iconos claros** para navegación rápida.

**3. Habitación**
- Tarjetas con fotos de la habitación y detalles (tipo, servicios incluidos, disponibilidad).  
- Indicadores visuales de estado de limpieza o check-in/check-out.  
- Botones para solicitar servicio o hacer reservas adicionales.

**4. Servicios**
- Lista o cards de servicios disponibles (spa, lavandería, comida, etc.) con imágenes.  
- Indicadores de disponibilidad y precios.  
- Botones para solicitar o reservar servicios fácilmente.

**5. Mapa**
- Mapa interactivo con **ubicación del hotel, habitaciones y servicios cercanos**.  
- Iconos para puntos de interés y rutas dentro del hotel.  
- Colores y estilo consistente con la identidad visual.


**6. Perfil**
- Información personal del huésped con **foto y datos básicos**.  
- Botones para editar información o preferencias.  
- Indicadores de estado de membresía o historial de reservas.

**7. Notificaciones**
- Lista de notificaciones recientes con **iconos y colores según tipo** (alerta, mensaje, promoción).  
- Botones para marcar como leído o eliminar.  
- Diseño consistente con la paleta y tipografía de la app.

**Elementos generales**
- Logo de SmartStay visible en header o menú.  
- Paleta de colores corporativa aplicada a fondos, botones y textos.  
- Tipografía uniforme que diferencia títulos, subtítulos y contenido.  
- Iconografía consistente para acciones, estados y navegación.  
- Feedback visual en botones e interacciones (hover, clic, activo).

![mockuphuesped1.png](assets/mockuphuesped1.png)
![mockuphuesped2.png](assets/mockuphuesped2.png)

**Mockups – Modo Staff**

Los mockups muestran la interfaz final del personal de SmartStay, incluyendo **colores, tipografía, iconos, imágenes y logos**, reflejando la identidad visual y la experiencia de usuario para el staff.

**1. Introducción**
- Pantalla de bienvenida con **logo y colores corporativos**.  
- **Ilustraciones o imágenes** que reflejan la experiencia inicial.  
- Botón destacado para avanzar al login.

**2. Login**
- Formulario con **campos destacados** para correo y contraseña.  
- Botón principal con **color corporativo** para iniciar sesión.  
- Iconos de seguridad y feedback visual al ingresar datos incorrectos.

**3. Home**
- Panel con **resumen de tareas, reservas y notificaciones recientes**.  
- Cards visuales para acceder a tareas, servicios, reservas y perfil.  
- Botones e iconos claros para navegación rápida.

**4. Tareas**
- Lista o cards de tareas asignadas con **estado visual** (pendiente, en proceso, finalizado).  
- Botones para marcar tareas completadas o reasignar.  
- Indicadores de prioridad con colores y símbolos.

**5. Servicios**
- Lista de servicios a realizar o supervisar, con **imágenes o iconos representativos**.  
- Indicadores de estado y disponibilidad.  
- Botones para actualizar estado o registrar finalización.

**6. Reservas**
- Calendario visual mostrando reservas asignadas al staff.  
- Tarjetas de reserva con detalles resumidos y foto del huésped.  
- Botones para confirmar asistencia o marcar tareas relacionadas a la reserva.

**7. Perfil**
- Información personal del staff con **foto, rol y datos de contacto**.  
- Botones para editar información y configurar preferencias.  
- Indicadores de estado activo/inactivo.

**8. Notificaciones**
- Lista de notificaciones recientes con **iconos y colores según tipo** (alerta, mensaje, aviso).  
- Botones para marcar como leído o eliminar.  
- Diseño consistente con la paleta y tipografía de la app.

**Elementos generales**
- Logo de SmartStay visible en header o menú.  
- Paleta de colores corporativa aplicada a fondos, botones y textos.  
- Tipografía uniforme que diferencia títulos, subtítulos y contenido.  
- Iconografía consistente para acciones, estados y navegación.  
- Feedback visual en botones e interacciones (hover, clic, activo).

![mockupstaff1.png](assets/mockupstaff1.png)
![mockupstaff2.png](assets/mockupstaff2.png)

### 4.4.4. Web Applications User Flow Diagrams

**Rol 1:** Administrador del hotel

**Objetivo:** Gestionar todas las áreas del hotel de manera eficiente desde un panel centralizado, incluyendo huéspedes, staff, reservas, pagos, servicios, reseñas y soporte.

**Cómo ayuda el diagrama:** Permite identificar los pasos necesarios para realizar tareas frecuentes y optimizar la navegación para máxima eficiencia.

**Happy Paths:**
1. Acceder al Dashboard → ver métricas → ir a detalles de reservas  
2. Gestionar Huéspedes → buscar/filtrar → agregar o editar  
3. Revisar Reservas → filtrar → aprobar/modificar/cancelar  
4. Gestionar Pagos → ver estado → generar factura/enviar recordatorio  
5. Responder Tickets de Soporte → seleccionar ticket → responder/cerrar  

**User Flow Diagram:**
```text
Login
  |
  v
Dashboard
  |---> Huéspedes
  |       |---> Buscar / Filtrar
  |       |---> Editar / Agregar
  |
  |---> Staff
  |       |---> Buscar / Filtrar
  |       |---> Editar / Agregar
  |
  |---> Hoteles
  |       |---> Ver detalles / Editar
  |
  |---> Reservas
  |       |---> Filtrar
  |       |---> Aprobar / Cancelar / Modificar
  |
  |---> Pagos
  |       |---> Ver estado
  |       |---> Generar factura / Recordatorio
  |
  |---> Servicios y Productos
  |       |---> Ver / Agregar / Editar
  |
  |---> Reseñas
  |       |---> Filtrar / Responder
  |
  |---> Soporte
          |---> Ver tickets
          |---> Responder / Cerrar
```

**Rol 2:** Huésped del hotel

**Objetivo:** Permitir al huésped consultar y gestionar su estadía, incluyendo habitaciones, servicios, mapa, perfil y notificaciones.
**Cómo ayuda el diagrama:** Visualiza los pasos más rápidos e intuitivos para que el huésped acceda a la información que necesita y realice solicitudes con facilidad.

**Happy Paths:**

1. Abrir app → Introducción → Home → ver resumen de reservas
2. Consultar Habitación → ver fotos y detalles → solicitar servicio
3. Ver Servicios → seleccionar y reservar servicio
4. Explorar Mapa → ubicar instalaciones y rutas dentro del hotel
5. Acceder a Perfil → actualizar datos personales
6. Revisar Notificaciones → marcar como leído o eliminar

**User Flow Diagram:**
```text
Introducción
  |
  v
Home
  |---> Habitación
  |       |---> Ver fotos / Detalles
  |       |---> Solicitar servicio
  |
  |---> Servicios
  |       |---> Ver lista / Cards
  |       |---> Reservar servicio
  |
  |---> Mapa
  |       |---> Ubicación del hotel
  |       |---> Rutas e instalaciones
  |
  |---> Perfil
  |       |---> Editar información
  |
  |---> Notificaciones
          |---> Revisar / Marcar / Eliminar
```

**Rol 3:** Personal del hotel (staff)

**Objetivo:** Permitir al staff gestionar tareas, servicios, reservas y comunicaciones con eficiencia.
**Cómo ayuda el diagrama:** Identifica pasos clave para que el personal cumpla sus responsabilidades sin confusión y con mínima navegación.

**Happy Paths:**
1. Abrir app → Introducción → Login → Home
2. Consultar Tareas → marcar como completadas o reasignar
3. Revisar Servicios → actualizar estado de ejecución
4. Revisar Reservas → confirmar asistencia o registrar tareas relacionadas
5.Acceder a Perfil → editar información personal
6. Revisar Notificaciones → marcar como leído o eliminar

**User Flow Diagram:**
```text
Introducción
  |
  v
Login
  |
  v
Home
  |---> Tareas
  |       |---> Ver lista / Cards
  |       |---> Marcar completadas / Reasignar
  |
  |---> Servicios
  |       |---> Ver lista / Cards
  |       |---> Actualizar estado
  |
  |---> Reservas
  |       |---> Ver calendario / Tarjetas
  |       |---> Confirmar asistencia / Registrar tarea
  |
  |---> Perfil
  |       |---> Editar información
  |
  |---> Notificaciones
          |---> Revisar / Marcar / Eliminar
```

## 4.5. Web Applications Prototyping

El prototipo permite simular la navegación entre todas las secciones principales mediante **carga dinámica de contenido**, mostrando cómo el administrador se moverá a través de los caminos definidos en los **User Flow Diagrams**, asegurando fluidez y coherencia en la experiencia de usuario.
En este caso presentaremos el prototipo del app principal que es del modo administrador:
[https://shorturl.at/7UPcY](https://www.figma.com/proto/RqI67mkRZ1AwuQNTcuGBvA/Sin-t%C3%ADtulo?node-id=48-3793&p=f&t=4u5X36WGvtb7jWe4-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1)

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming
**Legend of terminologies:**

![terminology.jpg](assets/Chapter-04/terminology.png) 

**Step 1: Unstructured Exploration:**

![step1.jpg](assets/Chapter-04/step1.png) 

**Step 2: Timelines:**

![step2.jpg](assets/Chapter-04/step2.png) 

**Step 3: Paint Points:**

![step3.jpg](assets/Chapter-04/step3.png) 

**Step 4: Pivotal Points:**

![step4.jpg](assets/Chapter-04/step4.png) 

**Step 5: Commands:**

![step5.jpg](assets/Chapter-04/step5.png) 

**Step 6: Policies:**

![step6.jpg](assets/Chapter-04/step6.png) 

**Step 7: Read models:**

![step7.jpg](assets/Chapter-04/step7.png) 

**Step 8: External Systems:**

![step8.jpg](assets/Chapter-04/step8.png) 

**Step 9: Aggregates:**

![step9.jpg](assets/Chapter-04/step9.png) 

**Step 10: Bounded Contexts:**

![step10.jpg](assets/Chapter-04/step10.png) 

**Link para visualizar mejor:** [https://shorturl.at/7UPcY](https://miro.com/app/board/uXjVJ9iB8iU=/?share_link_id=650007847940)


### 4.6.2. Software Architecture Context Diagram
**System Context**
![SystemContext.png](assets/Chapter-04/SystemContext.png)


### 4.6.3. Software Architecture Container Diagrams
**Containers**
![Containers.png](assets/Chapter-04/Containers.png)
### 4.6.4. Software Architecture Components Diagrams

**Api Components**
![Apicomponents.png](assets/Chapter-04/Apicomponents.png)


**IoT Gateway Components**
![IotGatewayComponets.png](assets/Chapter-04/IotGatewayComponets.png)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams
Diagrama de Clases: Componente de Autenticación

![AuthComponentClassDiagram.png](assets/Chapter-04/AuthComponentClassDiagram.png)

Este diagrama detalla las clases responsables de la gestión de la identidad y el acceso en el sistema. Incluye la jerarquía de User con sus roles especializados (Guest, Host, HotelStaff), el AuthService que contiene la lógica de negocio para el registro y la autenticación, y la interfaz IUserRepository para la persistencia de datos de usuario.

Diagrama de Clases: Componente de Gestión de Propiedades y Operaciones

![PropertyComponentClassDiagram.png](assets/Chapter-04/PropertyComponentClassDiagram.png)

Este diagrama muestra el diseño de clases para la gestión del inventario y las operaciones del hotel. Incluye las entidades Property y Room, que representan los activos físicos, y el PropertyService que maneja su estado y disponibilidad. Es importante destacar que este componente también actúa como el origen de los comandos de IoT, utilizando la interfaz IIoTCommandPublisher para iniciar acciones en el mundo físico.

Diagrama de Clases: Componente de Gestión de Reservas

![BookingComponentClassDiagram.png](assets/Chapter-04/BookingComponentClassDiagram.png)

Este diagrama presenta el diseño de clases para el componente central de reservas. Muestra las entidades de dominio Booking y Review, y el BookingService que actúa como orquestador. Este servicio interactúa con otros componentes a través de adaptadores (IPropertyServiceAdapter, IBillingServiceAdapter) para verificar disponibilidad y procesar pagos, gestionando así el flujo completo de una reserva.

Diagrama de Clases: Componente de Facturación

![BillingComponentClassDiagram.png](assets/Chapter-04/BillingComponentClassDiagram.png)

Este diagrama ilustra la estructura interna del componente de facturación. Se definen las entidades Payment e Invoice, el servicio BillingService que orquesta el proceso de pago, y los adaptadores (IPaymentGatewayAdapter, IAuthServiceAdapter) que se comunican con sistemas externos y otros componentes internos para garantizar transacciones seguras y autorizadas.

Diagrama de Clases: Componente Gateway IoT

![IotGatewayComponentClassDiagram.png](assets/Chapter-04/IotGatewayComponentClassDiagram.png)

Este diagrama detalla la arquitectura interna del componente técnico Gateway IoT. Su diseño se basa en un flujo de procesamiento de mensajes para desacoplar la lógica de negocio del hardware: un MessageListener recibe órdenes, un RulesEngine las interpreta, IDeviceController las especializa, y un ICloudApiClient se comunica con la plataforma externa del fabricante. Este patrón abstrae la complejidad de la integración con dispositivos físicos.

## 4.8. Database Design

Las decisiones clave tomadas, basadas directamente en nuestros diagramas de clases:

Traducción de Clases a Tablas: Cada clase de entidad (aquellas que guardan datos, como User, Property, Booking) se convierte en una tabla. Las clases de servicio e interfaces (AuthService, IUserRepository, etc.) no se convierten en tablas porque representan comportamiento, no datos.

Componentes sin Persistencia: Los componentes puramente técnicos como el Gateway IoT (MessageListener, RulesEngine, etc.) manejan datos en tránsito (mensajes, comandos) y no requieren persistencia en la base de datos relacional. Por lo tanto, no tienen tablas asociadas.

Nomenclatura: Se utiliza snake_case (ej: check_in_date) para nombres de tablas y columnas, una convención estándar en bases de datos.

Manejo de Herencia: La jerarquía de User se implementa con la estrategia "Tabla por Subclase" para máxima claridad y normalización.

Tipos de Datos ENUM: Los diferentes estados (BookingStatus, RoomStatus, etc.) se definen como tipos ENUM para garantizar la integridad de los datos.

Relaciones: Todas las asociaciones y composiciones en los diagramas de clases se implementan usando claves foráneas (FOREIGN KEY) con sus respectivas restricciones de multiplicidad (ej: UNIQUE para relaciones uno a uno).

### 4.8.1. Database Diagrams

![Edgerunners-Aplicaciones-Web_Physical_Export.png](assets/Chapter-04/Edgerunners-Aplicaciones-Web_Physical_Export.png)

# Capítulo V: Product Implementation, Validation & Deployment

# 5.1. Software Configuration Management

## 5.1.1. Software Development Environment Configuration  

## 5.1.2. Source Code Management  

## 5.1.3. Source Code Style Guide & Conventions  

## 5.1.4. Software Deployment Configuration  

## 5.2. Landing Page, Services & Applications Implementation.

## 5.2.1. Sprint 1

## 5.2.1.1. Sprint Planning 1  

## 5.2.1.2. Sprint Backlog 1

## 5.2.1.3. Development Evidence for Sprint Review

## 5.2.1.4. Deployment Evidence for Sprint Review

### 5.2.1.5. Execution Evidence for Sprint Review.

### 5.2.1.6. Services Documentation Evidence for Sprint Review  

### 5.2.1.7. Software Deployment Evidence for Sprint Review  

### 5.2.1.8. Team Collaboration Insights during Sprint  

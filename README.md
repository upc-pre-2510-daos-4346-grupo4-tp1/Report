# Carátula
<h2>Universidad Peruana de Ciencias Aplicadas</h2>

<img src="images/UPClogo.png" alt="UPC Logo" width="15%" height="15%">

<h2>Informe del Trabajo Final</h2>

<h3>Curso: Desarrollo de Aplicaciones Open Source</h3>
<h3>Carrera: Ingeniería de Software </h3>
<h3>Sección: 4346</h3>
<h3>Profesor: Rafael Oswaldo Castro Veramendi</h3>

<strong>Startup:</strong> Edunova<br>
<strong>Producto:</strong> Edunova

<h3>Integrantes:</h3>

<ul>
  <li>Iparraguirre Rueda, Cristian Luis (u202113111)</li>
  <li>Acuña Tomas, Diego Rolin (XXXXXXXXXX)</li>
  <li>Guerrero Vasquez, Jhon Danny (XXXXXXXXXX)</li>
  <li>Alvarez Falen, Esteban Valentino (XXXXXXXXXX)</li>
  <li>Torres Cortez, Tony Do Santos (XXXXXXXXXX)</li>
</ul>

**<h3>Abril, 2025</h3>**

# Registro de Versiones del Informe

| Versión | Fecha      | Autor                               | Descripción de modificación        |
|---------|------------|-------------------------------------|------------------------------------|
| TB1     | 19/04/2025 | - Iparraguirre Rueda, Cristian Luis<br>- Acuña Tomas, Diego Rolin<br>- Guerrero Vasquez, Jhon Danny<br>- Alvarez Falen, Esteban Valentino<br>- Torres Cortez, Tony Do Santos | Implementación del capítulo 1 al 5 y el landing page |

# Project Report Collaboration Insights
# Contenido
- [Carátula](#carátula)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile.](#11-startup-profile)
    - [1.1.1. Descripción de la Startup.](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo.](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile.](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática.](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process.](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores.](#21-competidores)
    - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas.](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
    - [2.3.1. User Personas.](#231-user-personas)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping.](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language.](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping.](#31-to-be-scenario-mapping)
  - [3.2. User Stories.](#32-user-stories)
  - [3.3. Impact Mapping.](#33-impact-mapping)
  - [3.4. Product Backlog.](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
  - [4.2. Information Architecture.](#42-information-architecture)
    - [4.2.1. Organization Systems.](#421-organization-systems)
    - [4.2.2. Labeling Systems.](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems.](#424-searching-systems)
    - [4.2.5. Navigation Systems.](#425-navigation-systems)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design.](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)
    - [4.4.2. Web Applications Mock-ups.](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams.](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram.](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design.](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams.](#471-class-diagrams)
    - [4.7.2. Class Dictionary.](#472-class-dictionary)
  - [4.8. Database Design.](#48-database-design)
    - [4.8.1. Database Diagram.](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1.](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1.](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review.](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)

# Student Outcome

# Capítulo I: Introducción
## 1.1. Startup Profile.
### 1.1.1. Descripción de la Startup.
### 1.1.2. Perfiles de integrantes del equipo.
## 1.2. Solution Profile.
### 1.2.1 Antecedentes y problemática.
En los últimos años, el aprendizaje en línea ha experimentado un crecimiento exponencial, impulsado por la digitalización, la masificación del acceso a internet y las nuevas dinámicas de enseñanza. Sin embargo, la mayoría de las plataformas existentes se enfocan en cursos de interés general, programación, idiomas o habilidades blandas, dejando de lado contenidos estrictamente académicos y universitarios, especialmente de nivel superior.

Actualmente, estudiantes universitarios que desean reforzar conocimientos específicos de sus asignaturas o prepararse para exámenes tienen dificultades para encontrar contenidos especializados en plataformas masivas. Por otro lado, docentes y profesionales con experiencia académica carecen de espacios adecuados para ofrecer cursos orientados al ámbito universitario, con herramientas pedagógicas que se ajusten a ese contexto.

Edunova surge como respuesta a esta necesidad, proponiendo una plataforma especializada que permita conectar a estudiantes, docentes y profesionales del entorno académico universitario para la creación, publicación y venta de cursos en distintas áreas del conocimiento superior.

---

**Análisis de la problemática**

| Clave  | Pregunta                                | Respuesta                                                                                                                                 |
|:--------|:------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------|
| **Who**  | ¿Quiénes se ven afectados?                 | Estudiantes universitarios que buscan reforzar o profundizar conocimientos, y docentes que desean compartir su experiencia académica. |
| **What** | ¿Qué ocurre?                               | No existen plataformas enfocadas exclusivamente en cursos universitarios estructurados, lo que limita la oferta y acceso a este tipo de contenido. |
| **Where**| ¿Dónde ocurre?                              | Principalmente en el ámbito digital y académico universitario de Latinoamérica, aunque la problemática es aplicable a otros entornos similares. |
| **When** | ¿Cuándo sucede?                             | Constantemente, al momento de buscar opciones de aprendizaje o recursos académicos adicionales más allá de las aulas tradicionales. |
| **Why**  | ¿Por qué es un problema?                   | Porque limita las oportunidades de aprendizaje complementario, dificulta la preparación académica y desaprovecha el potencial de expertos en distintas áreas universitarias. |
| **How**  | ¿Cómo afecta a los involucrados?            | Los estudiantes se ven obligados a recurrir a fuentes informales o incompletas; y los docentes carecen de una plataforma adecuada para difundir sus conocimientos de forma profesional. |
| **How much** | ¿Cuál es la magnitud del problema?        | Afecta a miles de estudiantes universitarios y docentes que no encuentran en plataformas generalistas una oferta académica universitaria estructurada, dificultando el acceso a recursos educativos de calidad. |

---

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
#### 1.2.2.2. Lean UX Assumptions.
#### 1.2.2.3. Lean UX Hypothesis Statements.
#### 1.2.2.4. Lean UX Canvas.
## 1.3. Segmentos objetivo.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.
### 2.1.2. Estrategias y tácticas frente a competidores.
## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
### 2.2.2. Registro de entrevistas.
### 2.2.3. Análisis de entrevistas.
## 2.3. Needfinding.
### 2.3.1. User Personas.
### 2.3.2. User Task Matrix.
### 2.3.3. User Journey Mapping.
### 2.3.4. Empathy Mapping.
### 2.3.5. As-is Scenario Mapping.
## 2.4. Ubiquitous Language.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.
## 3.2. User Stories.
## 3.3. Impact Mapping.
## 3.4. Product Backlog.

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.
## 4.8. Database Design.
### 4.8.1. Database Diagram.

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.
#### 5.2.1.2. Aspect Leaders and Collaborators.
#### 5.2.1.3. Sprint Backlog 1.
#### 5.2.1.4. Development Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.
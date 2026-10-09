<div align="center">

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

<img src="./assets/upc-logo.png" alt="Logo UPC" width="260"/>

### Ingeniería de Software

### Ciclo Académico: 2026-20

### Código: 1ASI0730

### Curso: Aplicaciones Web

### NRC: 8137

### Docente: Hugo Allan Mori Paiva

# Informe de Trabajo Final

### Startup: AIpaca

### Producto: Rumbo

### Integrantes

| Apellidos y Nombres          | Código de Alumno |
| ---------------------------- | ---------------- |
| Barrientos Quispe, Marcelo   | U20221E646       |
| Díaz Ramírez, Alejandro      | U202423084       |
| Geronimo Puma, Kevin Joel    | U202423163       |
| Lino Quispe, Leonardo Miguel | U202422298       |
| Meza Soza, Alexandra Yamile  | U20241b451       |

### SEPTIEMBRE - 2026

</div>

---

## Registro de Versiones del Informe

| Versión | Fecha      | Autor(es)                    | Descripción de cambios                                                                                                                                |
| ------- | ---------- | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0.1     | 07/09/2026 | Lino Quispe, Leonardo Miguel | Creación de la estructura base del informe de Rumbo.                                                                                                  |
| 0.2     | 11/09/2026 | Equipo Rumbo                 | Actualización de integrantes y refinamiento del Capítulo I para AV1.                                                                                  |
| 0.3     | 20/09/2026 | Equipo Rumbo                 | Integración de Collaboration Insights, Student Outcome, artefactos de Product Design y avance de Sprint 1.                                            |
| 0.4     | 08/10/2026 | Equipo Rumbo                 | Consolidación del Capítulo II para Aplicaciones Web: análisis competitivo, entrevistas, Needfinding, Big Picture EventStorming y Ubiquitous Language. |

---

## Project Report Collaboration Insights

**Organización:** https://github.com/AIpaca-UPC  
**Project Report:** https://github.com/AIpaca-UPC/web-applications-project-report  
**Landing Page:** https://github.com/AIpaca-UPC/landing-page  
**Frontend Web Application:** https://github.com/AIpaca-UPC/web-applications-web-app  
**Web Service:** https://github.com/AIpaca-UPC/web-applications-web-service

### AV1

<div align="center">
  <img src="./assets/collaboration/av1-project-report-insights.svg" alt="GitHub Pulse de colaboración del Project Report para AV1" width="95%">
</div>

Durante el periodo mostrado por GitHub Insights (20 de agosto al 20 de septiembre de 2026), el Project Report registra **4 autores activos**, **109 commits en todas las ramas** y **6 pull requests fusionados**. La captura también muestra **0 pull requests abiertos** y **0 issues activos** al cierre del periodo.

Como evidencia complementaria de colaboración se utilizan los recursos nativos del repositorio:

- **Commits:** https://github.com/AIpaca-UPC/web-applications-project-report/commits
- **Network:** https://github.com/AIpaca-UPC/web-applications-project-report/network
- **Contributors:** https://github.com/AIpaca-UPC/web-applications-project-report/graphs/contributors
- **Pull Requests:** https://github.com/AIpaca-UPC/web-applications-project-report/pulls

---

# Contenido

## Tabla de Contenidos

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statement](#1221-lean-ux-problem-statement)
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
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-The-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del **ABET – EAC – Student Outcome 5**: la capacidad de funcionar efectivamente en un equipo cuyos miembros proporcionan liderazgo de manera conjunta, crean un entorno colaborativo e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

| Criterio específico                                                                             | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                             | Conclusiones                                                                                                                                                                            |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta.                                | **Barrientos Quispe, Marcelo — AV1:** liderazgo del Capítulo I. <br> **Meza Soza, Alexandra Yamile — AV1:** liderazgo del Capítulo II. <br> **Lino Quispe, Leonardo Miguel — AV1:** liderazgo de los Capítulos III y V e integración de evidencias. <br> **Geronimo Puma, Kevin Joel — AV1:** desarrollo conjunto del Capítulo IV. <br> **Díaz Ramírez, Alejandro — AV1:** desarrollo conjunto del Capítulo IV. | El equipo distribuyó el liderazgo por capítulos y coordinó la integración de los entregables para mantener una versión común del Project Report.                                        |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Marcelo, Alexandra, Leonardo, Kevin y Alejandro — AV1:** organizaron el trabajo mediante ramas feature en GitHub, revisión de cambios, Product/Sprint Backlog en Trello y artefactos colaborativos en las herramientas definidas para el proyecto.                                                                                                                                                            | La planificación por responsabilidades y el uso de herramientas compartidas permitió organizar el avance, revisar el trabajo de otros integrantes y mantener trazabilidad del Sprint 1. |

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**AIpaca** es una startup tecnológica peruana enfocada en el desarrollo de soluciones digitales que simplifican la coordinación de servicios cotidianos, con especial atención en el transporte escolar. Nuestro propósito es aprovechar la tecnología para brindar tranquilidad a las familias y eficiencia a quienes prestan el servicio, mediante herramientas accesibles, seguras y fáciles de usar que permitan una comunicación clara, oportuna y ordenada entre padres, tutores y conductores de movilidad escolar.

Nuestra solución es **Rumbo**, una plataforma web responsive orientada al uso móvil que centraliza la información del traslado escolar. **Rumbo** permite a los padres y tutores conocer el estado actual de la ruta, revisar una línea de tiempo con los principales hitos del recorrido y recibir notificaciones ante eventos relevantes como recojos, llegadas, retrasos o incidencias. A su vez, permite a los conductores consultar su ruta y los estudiantes asignados, confirmar recojos y entregas mediante interacciones breves y registrar incidencias una sola vez para comunicarlas a todas las familias correspondientes.

La propuesta de **AIpaca** se centra en construir un ecosistema de coordinación del transporte escolar que sea confiable, escalable y respetuoso de la privacidad, donde la información de cada traslado esté disponible únicamente para los usuarios autorizados. Rumbo no busca reemplazar las obligaciones de seguridad, autorización y operación que corresponden a los prestadores del servicio, ni la comunicación humana cuando esta sea necesaria. Su objetivo es complementarlas con información estructurada que reduzca la incertidumbre de las familias y la carga operativa de los conductores en una ciudad con alta congestión y tiempos de viaje variables.

**Misión:** Desarrollar herramientas digitales accesibles y confiables que permitan a padres, tutores y conductores de movilidad escolar coordinar los traslados de los estudiantes de forma clara y oportuna, brindando tranquilidad a las familias y eficiencia a quienes prestan el servicio.

**Visión:** En los próximos 5 años, consolidar a AIpaca como una empresa referente en soluciones digitales para la coordinación del transporte escolar en el Perú y Latinoamérica, reconocida por generar confianza entre familias y prestadores del servicio mediante tecnología accesible, segura y escalable.

Alcance del proyecto: El alcance inicial de Rumbo está orientado a padres o tutores y conductores de movilidad escolar en Lima y Callao. Ofrece una plataforma web responsive que integra la consulta del estado del traslado, la línea de tiempo del trayecto, la confirmación de recojos y entregas, el registro de incidencias y un centro de notificaciones. A mediano plazo, buscamos ampliar la solución hacia centros educativos y empresas de transporte escolar, incorporando la gestión de múltiples rutas y unidades, para consolidar un modelo de coordinación que transforme la manera en que se organiza la movilidad escolar en otras ciudades del país y de la región.

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <thead>
    <tr>
      <th>Foto</th>
      <th>Apellidos y nombres</th>
      <th>Código</th>
      <th>Carrera</th>
      <th>Habilidades</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img src="assets/chapter01/marcelo.png" alt="Barrientos Quispe, Marcelo" width="120"/></td>
      <td>Barrientos Quispe, Marcelo</td>
      <td>U20221E646</td>
      <td>Ingeniería de Software</td>
      <td>Estudiante de Ingeniería de Software con capacidad de adaptación, aprendizaje rápido y trabajo colaborativo. Cuenta con conocimientos técnicos en tecnologías basadas en JavaScript y aporta al equipo en tareas de desarrollo frontend y organización del trabajo.</td>
    </tr>
    <tr>
      <td align="center"><img src="https://raw.githubusercontent.com/AIpaca-OS/project-report/main/assets/chapter01/alejandro-diaz.png" alt="Alejandro Díaz Ramírez" width="120"/></td>
      <td>Díaz Ramírez, Alejandro</td>
      <td>U202423084</td>
      <td>Ingeniería de Software</td>
      <td>Estudiante de Ingeniería de Software con conocimientos en Python y C++, experiencia en prototipado con React Native y trabajo colaborativo con metodologías ágiles. Aporta principalmente en lógica del sistema, estructuración del código y desarrollo técnico.</td>
    </tr>
    <tr>
      <td align="center"><img src="https://github.com/user-attachments/assets/8be17c32-7b22-466c-a91e-daf42a5b31ea" alt="Kevin Joel Geronimo Puma" width="120"/></td>
      <td>Geronimo Puma, Kevin Joel</td>
      <td>U202423163</td>
      <td>Ingeniería de Software</td>
      <td>Estudiante de Ingeniería de Software con conocimientos en Python y C++. Se desempeña especialmente en arquitectura de software, diseño de bases de datos, lógica del sistema y organización técnica del desarrollo.</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/chapter01/leonardo-lino.jpg" alt="Leonardo Miguel Lino Quispe" width="120"/></td>
      <td>Lino Quispe, Leonardo Miguel</td>
      <td>U202422298</td>
      <td>Ingeniería de Software</td>
      <td>Soy estudiante de Ingeniería de Software del 5.º ciclo en la UPC. Tengo conocimientos en programación en C++ y Python, y experiencia desarrollando proyectos académicos donde analizo y organizo soluciones tecnológicas. Me gusta enfocarme en aprender de forma práctica y en construir soluciones que sean claras, funcionales y aplicadas a problemas reales.</td>
    </tr>
    <tr>
      <td align="center"><img src="https://raw.githubusercontent.com/AIpaca-OS/project-report/main/assets/chapter01/alexandra-meza.png" alt="Alexandra Yamile Meza Soza" width="120"/></td>
      <td>Meza Soza, Alexandra Yamile</td>
      <td>U20241b451</td>
      <td>Ingeniería de Software</td>
      <td>Estudiante de Ingeniería de Software con conocimientos en Python y C++. Se caracteriza por el aprendizaje rápido, el criterio para seleccionar información relevante y el trabajo colaborativo. En el equipo aporta investigación aplicada, análisis y documentación del producto.</td>
    </tr>
  </tbody>
</table>

## 1.2. Solution Profile

El **Solution Profile** presenta una descripción general de la solución propuesta por **AIpaca** y de su producto **Rumbo**. Aborda el contexto en el que opera el transporte escolar en Lima y Callao, los problemas detectados en la coordinación entre familias y conductores y las suposiciones estratégicas que guían el desarrollo del producto. Esta sección conecta los hallazgos de la fase de descubrimiento con una propuesta de valor clara y sienta las bases para el diseño, la validación y el desarrollo posterior de la solución.

Para el curso de **Aplicaciones Web**, Rumbo se plantea como una experiencia compuesta por un **Landing Page**, una **Web Application responsive** y, en las etapas de implementación correspondientes, una **RESTful API de elaboración interna** integrada con la aplicación web y con al menos un servicio externo de terceros. Esta delimitación tecnológica corresponde al alcance específico del curso y no debe confundirse con la implementación realizada en otros cursos del proyecto.

### 1.2.1. Antecedentes y problemática

El transporte escolar constituye un servicio formal y regulado en Lima y Callao. En enero de 2026, la Autoridad de Transporte Urbano para Lima y Callao (ATU) informó que **3758 vehículos se encontraban habilitados para prestar el servicio de transporte de estudiantes** y recordó que los padres pueden verificar digitalmente si el vehículo y el conductor están autorizados (Infobae, 2026a). Esta cifra confirma que existe un ecosistema amplio de familias, conductores y operadores que realizan traslados escolares de manera recurrente.

En esta sección se analiza el contexto en el que surge la problemática principal, considerando sus factores sociales, tecnológicos y operativos. Se utiliza la técnica de las 5 W y 2 H para responder de forma estructurada qué ocurre, quiénes están involucrados, cuándo y dónde sucede, por qué ocurre, cómo se abordará y cuánto costará implementar la solución.

#### Técnica de las 5 W's + 2 H's

**What (¿Qué?) — ¿Cuál es el problema?**

El transporte escolar en Lima y Callao es un servicio formal y regulado. Sin embargo, la coordinación diaria entre padres y conductores sigue dependiendo de mensajes y llamadas individuales. Según la Autoridad de Transporte Urbano para Lima y Callao (ATU), 3758 vehículos cuentan con habilitación para prestar este servicio durante 2026, tras un proceso de verificación y autorización realizado en 2025 (Infobae, 2026a). Además, la ATU habilitó un enlace público para que los padres verifiquen si el vehículo y el conductor contratados están autorizados (Exitosa Noticias, 2026).

Estos mecanismos resuelven la pregunta de si el servicio es formal antes de contratarlo, pero no la de qué está pasando durante la ruta. Los padres no cuentan con una vista única donde consultar si el menor ya fue recogido, si la movilidad está retrasada, si llegó al colegio o si ocurrió un imprevisto. Esa información se transmite de forma dispersa, y buena parte de ella recae sobre el conductor, que debe responder las mismas consultas a varias familias mientras cumple su ruta.

**When (¿Cuándo?) — ¿Cuándo ocurre?**

El problema ocurre todos los días de clases, en tres momentos: antes del recojo, durante el traslado y al momento de la llegada o entrega. El Ministerio de Educación fijó el inicio del año escolar 2026 para el lunes 16 de marzo y su término para el viernes 18 de diciembre, con 36 semanas de clases (Infobae, 2026a). Durante todo ese periodo, cada familia depende de uno o dos trayectos diarios.

La incertidumbre se intensifica porque los horarios escolares coinciden con las horas de mayor congestión. En Lima el tráfico se concentra entre las 6 a. m. y las 9 a. m., y nuevamente en las horas punta de la tarde (El Comercio, 2026). En esas franjas un retraso de pocos minutos puede convertirse en una espera prolongada, y es cuando los padres más necesitan información oportuna.

**Where (¿Dónde?) — ¿Dónde surge?**

El problema se presenta principalmente en Lima Metropolitana y el Callao, en las rutas que conectan hogares, puntos de recojo y centros educativos. Se trata de una de las ciudades con mayor congestión del mundo: el TomTom Traffic Index 2025 ubicó a Lima como la novena ciudad más congestionada del mundo, con un nivel de tráfico de 69,3 %, y con 195 horas anuales perdidas por conductor en embotellamientos (El Popular, 2026).

La situación se mantiene en 2026. Con datos de TomTom consolidados hasta el 3 de agosto de 2026, en la hora punta matinal de los días laborables la velocidad promedio en Lima fue de 14,74 km/h, la más baja frente a Ciudad de México, Bogotá y Santiago de Chile (Energiminas, 2026). En este entorno, los tiempos de llegada son difíciles de anticipar para las familias.

**Who (¿Quiénes?) — ¿Quiénes son los afectados?**

- **Padres y tutores**, que necesitan saber en qué etapa se encuentra el traslado de sus hijos y hoy dependen de preguntarle directamente al conductor.

- **Conductores de movilidad escolar**, que deben cumplir su ruta en medio del tráfico y, al mismo tiempo, comunicar recojos, retrasos o incidencias a varias familias de forma individual. Su trabajo está sujeto a exigencias formales: la ATU verifica que los vehículos cuenten con SOAT y CITV vigentes y que los conductores tengan licencia de categoría AIIB (Infobae, 2026a).

- **Estudiantes**, beneficiarios indirectos del servicio. No interactúan con la plataforma, pero su seguridad y la protección de sus datos personales condicionan el diseño de la solución.

Ambos grupos constituyen los segmentos objetivo de Rumbo, por ser quienes utilizarán la plataforma. Los estudiantes, en cambio, reciben el servicio pero no interactúan con ella: su condición de menores de edad resulta relevante porque la información que Rumbo registra sobre sus traslados constituye datos personales sujetos a la Ley N.º 29733, lo que condiciona el diseño de permisos y visibilidad de la solución.

**Why (¿Por qué?) — ¿Por qué ocurre y por qué importa?**

- **Comunicación fragmentada en canales generales:** La coordinación se realiza principalmente por mensajería instantánea. Según la Encuesta Residencial de Servicios de Telecomunicaciones (ERESTEL) 2025 de Osiptel, el 68,6 % de los peruanos usó plataformas de comunicación instantánea durante el último año, y entre ellos WhatsApp alcanza el 98,6 % de usuarios (Expreso, 2026). Estos canales son útiles, pero no fueron diseñados para registrar hitos de una ruta: la información queda mezclada con otros mensajes y cada familia recibe actualizaciones distintas.

- **Alta variabilidad de los tiempos de viaje:** La congestión de Lima hace que la hora estimada de llegada cambie constantemente, lo que multiplica las consultas de los padres.

- **Carga operativa del conductor:** El conductor es la única fuente de información en tiempo real, pero su prioridad debe ser conducir con seguridad. Responder mensajes durante la ruta compite con esa prioridad.

- **Ausencia de un registro estructurado:** Los recojos, entregas e incidencias no suelen quedar documentados de forma ordenada, lo que dificulta resolver dudas posteriores sobre lo ocurrido en un trayecto.

- **Verificación sin visibilidad en ruta:** Las herramientas oficiales permiten comprobar la formalidad del servicio, pero no ofrecen seguimiento del estado de cada traslado.

**How (¿Cómo?) — ¿Cómo se abordará?**

Para responder a esta necesidad, AIpaca propone Rumbo, una plataforma web responsive orientada al uso móvil que centraliza el estado de cada traslado. La elección del canal responde al contexto local: según el INEI, en el cuarto trimestre de 2025 el 98,4 % de los hogares de Lima Metropolitana contó con telefonía móvil, y en ese mismo periodo el uso de Internet en Lima Metropolitana alcanzó el 90,3 % de la población de 6 años a más (Instituto Nacional de Estadística e Informática [INEI], 2026). Además, el 89,2 % de los usuarios de Internet accedió a la red mediante un teléfono celular (Altavoz, 2026).

Para los padres y tutores: Podrán ver de un vistazo el estado actual del viaje, revisar una línea de tiempo con los hitos del recorrido y recibir notificaciones solo ante eventos relevantes, como recojo, llegada, retraso o incidencia.

Para los conductores: Podrán consultar su ruta y los estudiantes asignados, confirmar recojos y entregas mediante interacciones breves y registrar una incidencia una sola vez para que llegue a todas las familias correspondientes.

La información de cada menor será visible únicamente para los usuarios autorizados. Esto es coherente con el marco peruano de protección de datos: el Decreto Supremo N.º 016-2024-JUS, publicado el 30 de noviembre de 2024, aprobó el nuevo reglamento de la Ley N.º 29733, Ley de Protección de Datos Personales (Escobedo, 2024), y entró en vigor el 31 de marzo de 2025, reforzando las medidas de seguridad y exigiendo notificar los incidentes de seguridad a la Autoridad Nacional de Protección de Datos Personales (LP Derecho, s. f.).

Rumbo no reemplaza las obligaciones de seguridad, autorización y operación de los prestadores del servicio, ni la comunicación humana cuando sea necesaria. Su objetivo es complementarlas con información estructurada que reduzca la incertidumbre de las familias y la carga del conductor.

**How much (¿Cuánto?)**

La implementación de Rumbo requiere una inversión inicial orientada al desarrollo de software, la infraestructura en la nube, la adecuación a la normativa de datos personales y un piloto con familias y conductores. Al ser una solución exclusivamente de software, no requiere fabricar hardware, lo que reduce la inversión inicial y facilita escalar el modelo SaaS.

Como referencia del mercado, el precio mensual por estudiante de una movilidad escolar varía aproximadamente entre S/ 150 y S/ 300, según la distancia y los servicios adicionales (Comparabien, 2025). Esto sugiere que una suscripción de bajo costo podría presentarse como un valor agregado del servicio.

Presupuesto estimado (estimación referencial elaborada por el equipo):

Desarrollo de software
Diseño UX/UI y prototipado: S/ 2,000 – S/ 3,000
Frontend web responsive (Vue + PrimeVue): S/ 4,000 – S/ 6,000
Backend, RESTful API y base de datos (ASP.NET Core + C#): S/ 4,500 – S/ 6,500
Integración de servicios de ubicación y notificaciones: S/ 1,500 – S/ 2,500

Infraestructura (anual)
Dominio, hosting en la nube y base de datos gestionada: S/ 1,500 – S/ 2,500
Servicio de notificaciones (push, correo o SMS): S/ 800 – S/ 1,500

Seguridad y cumplimiento
Adecuación a la Ley N.º 29733 (políticas de privacidad, consentimiento y asesoría legal): S/ 1,500 – S/ 2,500
Pruebas de seguridad: S/ 1,000 – S/ 1,500

Marketing y lanzamiento
Landing page, estrategia digital y materiales: S/ 2,000 – S/ 3,000
Piloto con conductores y familias (capacitación e incentivos): S/ 1,500 – S/ 2,500

Mantenimiento y soporte (anual)
Actualizaciones de software y soporte técnico: S/ 3,000 – S/ 5,000

Total estimado: S/ 23,300 – S/ 36,500

### 1.2.2. Lean UX Process

El proceso Lean UX que adoptamos en AIpaca busca maximizar la eficiencia en el desarrollo de Rumbo mediante la validación continua, el pensamiento crítico y la acción rápida. Siguiendo esta filosofía, estructuramos nuestro enfoque en cuatro componentes: la definición del problema, la formulación de suposiciones, la creación de hipótesis y el desarrollo de un lienzo estratégico. Este proceso nos permite aprender de padres, tutores y conductores antes de invertir esfuerzo en funcionalidades que no aporten valor real.

#### 1.2.2.1. Lean UX Problem Statement

El estado actual de la coordinación del transporte escolar en Lima y Callao se ha centrado principalmente en verificar la formalidad del servicio y en la comunicación directa entre padres o tutores y conductores mediante mensajería instantánea y llamadas. Esto genera incertidumbre sobre recojos, llegadas y retrasos, y consultas repetitivas que interrumpen al conductor durante la ruta.

Lo que los productos y servicios existentes no resuelven es una vista única y estructurada, restringida por permisos, donde se registren los hitos de cada traslado (recojos, entregas, retrasos e incidencias) y se notifique solo a los tutores autorizados.

Rumbo abordará esta brecha mediante una plataforma web responsive en la que los conductores confirman hitos con interacciones breves, y los padres consultan el estado actual y la línea de tiempo del viaje y reciben notificaciones relevantes.

Nuestro enfoque inicial serán los conductores de movilidad escolar autorizados por la ATU en Lima y Callao y los padres o tutores que contratan sus servicios.

Sabremos que tenemos éxito cuando los padres consulten Rumbo en lugar de escribir al conductor, reduciendo en 60 % las consultas sobre el estado de la ruta, y cuando los conductores confirmen al menos el 80 % de los recojos y entregas dentro de la plataforma.

- **Domain:** Transporte escolar, movilidad urbana y coordinación digital entre familias y prestadores de servicio.

- **Customer Segments:**

Padres, madres y tutores de estudiantes que usan movilidad escolar.

Conductores de movilidad escolar que realizan rutas recurrentes.

- **Pain Points:**

**Padres y Tutores**

- Incertidumbre sobre si el menor ya fue recogido, si la movilidad está en camino o si llegó al destino.

- Falta de avisos oportunos ante retrasos o imprevistos.

- Información dispersa entre chats, llamadas y mensajes de otros temas.

**Conductores**

- Consultas repetitivas de varias familias sobre lo mismo durante la ruta.

- Necesidad de comunicar un retraso o incidencia a cada familia por separado.

- Ausencia de un registro ordenado de recojos, entregas e incidencias para resolver dudas posteriores.

- **Gap:** Creemos que no existe una solución de uso extendido en Lima y Callao que combine, en una sola plataforma, el estado del traslado, la confirmación de recojos y entregas, el registro de incidencias y notificaciones dirigidas solo a los tutores autorizados. Este supuesto será contrastado en el análisis competitivo.

- **Vision/Strategy:** Consolidar a AIpaca como una empresa referente en soluciones digitales para la coordinación del transporte escolar en el Perú y Latinoamérica, reconocida por generar confianza entre familias y conductores mediante tecnología accesible, segura y escalable.

- **Initial Segment:** Conductores de movilidad escolar autorizados por la ATU en Lima y Callao, y los padres o tutores que contratan sus servicios y usan un teléfono celular con acceso a Internet.

#### 1.2.2.2. Lean UX Assumptions

Los siguientes supuestos representan las creencias iniciales del equipo sobre el modelo de negocio, los usuarios y la viabilidad de Rumbo. Serán validados mediante entrevistas, prototipos y pruebas durante las iteraciones del proceso Lean UX.

##### Business Assumptions

Estas Business Assumptions servirán como base para formular los Feature Assumptions y los Hypothesis Statements, y permitirán validar los elementos críticos del modelo.

1. Creemos que los padres y tutores necesitan conocer el estado del traslado escolar de sus hijos para reducir su incertidumbre durante la ruta.

2. Creemos que una plataforma web responsive con estados, hitos, notificaciones e incidencias puede satisfacer esta necesidad mejor que la mensajería de uso general.

3. Creemos que nuestros clientes iniciales serán conductores independientes de
   movilidad escolar en Lima y Callao, junto con las familias que contratan sus servicios.

4. Creemos que el valor más importante para los padres es la tranquilidad de saber qué ocurre en la ruta sin tener que preguntar y, para los conductores, la reducción de mensajes repetitivos.

5. Creemos que un modelo SaaS con acceso gratuito para padres y tutores y suscripción mensual para conductores nos permitirá crecer, porque el conductor puede presentar Rumbo como un valor agregado de su servicio.

6. Creemos que nuestra ventaja competitiva será una experiencia enfocada en hitos resumidos, y no en un seguimiento continuo de coordenadas, lo que la hace más clara y menos invasiva.

7. Creemos que los conductores adoptarán la plataforma solo si registrar un evento toma pocos segundos y no interfiere con la conducción.

8. Creemos que los mayores riesgos son la desconfianza sobre el manejo de datos de menores y la resistencia de los conductores a cambiar sus hábitos, y que podremos mitigarlos con permisos estrictos por rol, cumplimiento de la Ley N.º 29733 y pilotos gratuitos con conductores reales.

9. Creemos que el costo de la suscripción será bajo en relación con lo que las familias pagan mensualmente por el servicio de movilidad escolar.

##### Business Outcome Assumptions

1. Reducir en 60 % los mensajes y llamadas de padres y tutores al conductor para consultar el estado de la ruta.

2. Lograr que al menos el 70 % de los padres y tutores activos consulte Rumbo en tres o más días de clases por semana.

3. Lograr que al menos el 80 % de los recojos y entregas de cada ruta quede confirmado dentro de Rumbo.

4. Lograr que al menos el 90 % de los retrasos e incidencias se comunique a las familias mediante Rumbo y no mediante mensajes individuales.

5. Mantener por debajo del 20 % la proporción de padres y tutores que desactiva las notificaciones durante el primer mes de uso.

6. Lograr que al menos el 60 % de los conductores que participen en el piloto continúe usando Rumbo después del primer mes.

##### User Assumptions

En esta etapa se identificaron los principales supuestos sobre los usuarios, sus necesidades y el contexto de uso, antes de realizar las entrevistas de validación.

**¿Quién es el usuario?**

- **Padres, madres y tutores:**

1. Creemos que los padres y tutores trabajan o realizan otras actividades durante el horario de traslado y consultan el celular solo en momentos breves.

2. Creemos que hoy coordinan con el conductor principalmente mediante WhatsApp y llamadas telefónicas.

3. Creemos que sus momentos de mayor incertidumbre son antes del recojo, durante los retrasos por tráfico y al esperar la confirmación de llegada.

4. Creemos que prefieren recibir información resumida en estados e hitos antes que seguir una ubicación en tiempo real.

5. Creemos que solo confiarán en una plataforma si la información de su hijo es visible únicamente para los tutores autorizados.

- **Conductores de movilidad escolar:**

6. Creemos que los conductores realizan rutas recurrentes en las que atienden a varias familias y paradas por jornada.

7. Creemos que reciben consultas repetidas de distintas familias sobre un mismo evento de la ruta.

8. Creemos que organizan su lista de estudiantes y paradas de manera informal, de memoria, en papel o en chats.

9. Creemos que solo pueden interactuar con el celular de forma segura cuando el vehículo está detenido.

10. Creemos que valoran ofrecer una imagen más profesional y ordenada ante las familias.

##### Feature Assumptions

En esta sección se detallan los supuestos sobre las funcionalidades del producto. Cada Feature Assumption conecta una necesidad del usuario con una posible solución de diseño y anticipa su impacto en la experiencia.

1. Creemos que una vista de estado actual del viaje permitirá a los padres y tutores entender en pocos segundos en qué etapa está el traslado.

2. Creemos que una línea de tiempo del trayecto dará más claridad sobre lo ocurrido durante el recorrido que una secuencia de mensajes de chat.

3. Creemos que la confirmación de recojo y entrega con una sola acción permitirá a los conductores registrar los hitos sin afectar su flujo de trabajo.

4. Creemos que un registro de incidencias con categorías predefinidas permitirá comunicar imprevistos con suficiente contexto y en poco tiempo.

5. Creemos que las notificaciones limitadas a eventos relevantes mantendrán informados a los padres sin saturarlos.

6. Creemos que una vista de ruta con los estudiantes asignados y el orden de paradas facilitará la organización diaria del conductor.

##### User Outcome and Benefit Assumptions

1. Los padres y tutores conocerán en pocos segundos la etapa actual del traslado sin contactar al conductor.

2. Los padres y tutores comprenderán lo ocurrido durante el recorrido sin revisar conversaciones dispersas.

3. Los conductores dejarán constancia de cada recojo y entrega en segundos, con el vehículo detenido.

4. Los conductores informarán un imprevisto a todas las familias afectadas mediante un único registro.

5. Los padres y tutores podrán anticiparse a retrasos sin recibir avisos innecesarios.

6. Los conductores organizarán su jornada con la lista de estudiantes y el orden de paradas en un solo lugar.

#### 1.2.2.3. Lean UX Hypothesis Statements

Se formula un Hypothesis Statement por cada Feature Assumption, siguiendo la estructura: _Creemos que lograremos [resultado de negocio] si [persona] obtiene [beneficio] con [funcionalidad]._

**Hipótesis 1 — Estado actual del viaje**

Creemos que lograremos reducir en 60 % los mensajes y llamadas al conductor para consultar el estado de la ruta si los padres y tutores conocen en pocos segundos la etapa actual del traslado con una vista de estado actual del viaje.

**Hipótesis 2 — Línea de tiempo del trayecto**

Creemos que lograremos que al menos el 70 % de los padres y tutores activos consulte Rumbo en tres o más días de clases por semana si comprenden lo ocurrido durante el recorrido sin revisar conversaciones dispersas con una línea de tiempo del trayecto.

**Hipótesis 3 — Confirmación de recojo y entrega**

Creemos que lograremos que al menos el 80 % de los recojos y entregas de cada ruta quede confirmado en Rumbo si los conductores dejan constancia de cada hito en segundos con la confirmación de recojo y entrega en una sola acción.

**Hipótesis 4 — Registro de incidencias**

Creemos que lograremos que al menos el 90 % de los retrasos e incidencias se comunique mediante Rumbo si los conductores informan un imprevisto a todas las familias afectadas mediante un único registro con categorías predefinidas.

**Hipótesis 5 — Centro de notificaciones**

Creemos que lograremos mantener por debajo del 20 % la proporción de padres y tutores que desactiva las notificaciones durante el primer mes si se anticipan a los retrasos sin recibir avisos innecesarios con notificaciones limitadas a eventos relevantes.

**Hipótesis 6 — Vista de ruta del conductor**

Creemos que lograremos que al menos el 60 % de los conductores del piloto continúe usando Rumbo después del primer mes si organizan su jornada con la lista de estudiantes y el orden de paradas en un solo lugar con una vista de ruta con estudiantes asignados.

#### 1.2.2.4. Lean UX Canvas

El **Lean UX Canvas** resume en un solo artefacto los elementos trabajados en el Lean UX Process: el problema de negocio, los resultados esperados, los segmentos objetivo, sus beneficios, las soluciones propuestas y las hipótesis que las conectan. Además, identifica el supuesto más riesgoso para Rumbo y los experimentos de menor esfuerzo que permitirán validarlo.

<p align="center"><img src="assets/chapter01/lean-ux.png" alt="Lean UX Canvas de Rumbo" width="100%"/></p>

## 1.3. Segmentos objetivo

En esta sección se identifican y describen los **segmentos de usuarios** hacia los cuales se dirige Rumbo. Estos segmentos servirán como referencia para el diseño de funcionalidades, la experiencia de usuario, las entrevistas de Needfinding y la comunicación del producto.

### Padres y tutores

**Descripción:**  
Padres, madres o tutores responsables de menores que utilizan servicios de movilidad escolar en Lima y Callao. Este segmento busca disminuir la incertidumbre durante los recorridos y acceder a información clara sobre recojo, traslado, retrasos, llegada e incidencias.

**Características demográficas y comportamiento:**

- Adultos responsables de menores en edad escolar que contratan o utilizan servicios de movilidad escolar.
- Utilizan principalmente el teléfono móvil para comunicarse y consultar información cotidiana.
- Valoran la inmediatez, claridad y facilidad de uso por encima de interfaces complejas.
- Requieren información relevante, pero no necesariamente una secuencia continua de mensajes.
- La confianza en la plataforma depende de la privacidad y del control sobre quién puede consultar información del menor.

**Sustento estadístico:**

- La ATU reportó **3758 vehículos habilitados para transporte escolar en Lima y Callao** en enero de 2026, evidenciando un mercado formal y recurrente de familias usuarias del servicio (Infobae, 2026a).
- El INEI informó que **98,4 % de los hogares de Lima Metropolitana contaba con telefonía móvil** y que **90,3 % de la población de 6 años a más utilizaba Internet** durante el cuarto trimestre de 2025. Además, una fuente secundaria citada por el equipo reporta que **89,2 % de los usuarios de Internet accedía mediante teléfono celular** (Altavoz, 2026). Esto respalda una experiencia web orientada principalmente al uso móvil.

### Conductores de movilidad escolar

**Descripción:**  
Conductores que realizan rutas programadas para el traslado de estudiantes entre hogares, puntos de recojo y centros educativos. Este segmento necesita organizar el recorrido y comunicar a las familias los principales eventos de la ruta de forma rápida y consistente.

**Características demográficas y comportamiento:**

- Prestadores de un servicio regulado que operan vehículos autorizados para transporte de estudiantes.
- Trabajan con rutas, horarios, puntos de recojo y varios estudiantes durante una misma jornada.
- Necesitan reducir acciones digitales mientras conducen, por lo que las interacciones deben ser breves y ejecutarse únicamente cuando sea seguro hacerlo.
- Requieren comunicar retrasos, incidencias, recojos y entregas sin repetir la misma información individualmente.
- Valoran herramientas que simplifiquen la coordinación sin reemplazar sus responsabilidades operativas y de seguridad.

**Sustento estadístico:**

- La ATU reportó **3758 vehículos escolares habilitados en Lima y Callao** (Infobae, 2026a), lo que permite identificar un grupo concreto de operadores y conductores dentro del mercado formal.
- Lima registró **69,3 % de congestión promedio durante 2025**, con recorridos de 10 km de hasta **51 min 17 s en la hora punta de la tarde** y aproximadamente **195 horas anuales perdidas en tráfico de hora punta** (El Popular, 2026). Este contexto sustenta la necesidad de gestionar retrasos y comunicar variaciones de tiempo de manera ordenada.

---

# Capítulo II: Requirements Elicitation & Analysis

Este capítulo reúne la obtención y el análisis de requisitos de **Rumbo** para el curso de **Aplicaciones Web**. Los hallazgos se utilizan como base para la especificación posterior del Landing Page, la Frontend Web Application responsive y los RESTful Web Services. El análisis del dominio se mantiene separado de las decisiones tecnológicas de implementación, de modo que los artefactos reflejen primero las necesidades reales de padres/tutores y conductores.

## 2.1. Competidores

### 2.1.1. Análisis competitivo

El análisis competitivo se desarrolla mediante el **Competitive Analysis Landscape** solicitado para el curso de **Aplicaciones Web**. Se compara a **Rumbo** con dos soluciones especializadas en transporte escolar —**SchoolBusTracker** y **Bus esCool**— y con un sustituto informal compuesto por herramientas de uso general como **WhatsApp y Waze**. El objetivo es reconocer diferencias reales entre las alternativas, identificar fortalezas y debilidades y analizar las oportunidades y amenazas particulares de cada una, evitando asumir funcionalidades o condiciones comerciales que no hayan sido verificadas.

<table>
  <thead>
    <tr><th colspan="6">Competitive Analysis Landscape</th></tr>
  </thead>
  <tbody>
    <tr>
      <th colspan="2">¿Por qué llevar a cabo este análisis?</th>
      <td colspan="4">Identificar cómo puede Rumbo diferenciarse frente a soluciones especializadas de transporte escolar y frente a los canales informales que actualmente pueden utilizar padres/tutores y conductores, considerando producto, mercado, canales y factores SWOT.</td>
    </tr>
    <tr>
      <th colspan="2">Competidores / Startup</th>
      <th>
        <img src="./assets/chapter02/rumbo-logo.png" alt="Logo de Rumbo" width="120"/><br>
        AIpaca / Rumbo
      </th>
      <th>
        <img src="./assets/chapter02/bustracker.png" alt="Logo de SchoolBusTracker" width="110"/><br>
        SchoolBusTracker
      </th>
      <th>
        <img src="./assets/chapter02/busschool.png" alt="Logo de Bus esCool" width="100"/><br>
        Bus esCool
      </th>
      <th>
        <img src="./assets/chapter02/whatsapp.png" alt="Logo de WhatsApp" width="105"/><br>
        <img src="./assets/chapter02/waze.png" alt="Logo de Waze" width="105"/><br>
        Canales informales (WhatsApp + Waze)
      </th>
    </tr>
    <tr>
      <th rowspan="2">Perfil</th>
      <th>Overview</th>
      <td><strong>Rumbo</strong>, producto de la startup <strong>AIpaca</strong>, es una plataforma web responsive orientada a la coordinación del transporte escolar entre padres/tutores y conductores. El alcance actual prioriza estados e hitos del viaje, rutas, estudiantes, retrasos, incidencias y notificaciones.</td>
      <td>Suite especializada de transporte escolar dirigida principalmente a instituciones educativas. Incluye aplicaciones para padres y conductores y un panel administrativo para gestionar y supervisar el servicio.</td>
      <td>Plataforma de monitoreo y control de rutas escolares que conecta a colegios, padres de familia, coordinadores de transporte, monitores y conductores.</td>
      <td>Combinación de aplicaciones de mensajería, llamadas, navegación y ubicación que pueden utilizarse para coordinar el servicio, pero que no conforman por sí mismas un sistema especializado de transporte escolar.</td>
    </tr>
    <tr>
      <th>Ventaja competitiva / ¿Qué valor ofrece a los clientes?</th>
      <td>Comunica hitos confirmados por el conductor en lugar de ubicación continua, lo que reduce la exposición de datos del menor. Es la única plataforma especializada del análisis que no requiere la participación de un colegio: el conductor independiente administra su propia ruta, sus familias y su suscripción.</td>
      <td>Oferta madura e integrada: seguimiento en tiempo real, registro de subida y bajada, alertas, reservas, pagos, administración y reportes dentro de una misma suite.</td>
      <td>Seguimiento en tiempo real, avisos sobre imprevistos, control de inasistencias, información de abordaje y herramientas específicas para la operación de rutas escolares.</td>
      <td>Familiaridad de uso, amplia presencia en los teléfonos de los usuarios y posibilidad de comunicarse o consultar navegación sin adoptar inicialmente una plataforma adicional.</td>
    </tr>
    <tr>
      <th rowspan="2">Perfil de Marketing</th>
      <th>Mercado objetivo</th>
      <td>Padres/tutores y conductores de movilidad escolar de Lima y Callao.</td>
      <td>Colegios y organizaciones que administran transporte escolar, junto con padres, estudiantes y conductores que utilizan el servicio.</td>
      <td>Colegios, padres de familia, coordinadores de transporte, monitores y conductores vinculados a rutas escolares.</td>
      <td>Mercado general de usuarios de mensajería y navegación; dentro del problema de Rumbo actúan como herramientas sustitutas para familias y conductores.</td>
    </tr>
    <tr>
      <th>Estrategias de marketing</th>
      <td>Captación directa del conductor independiente, que al adoptar Rumbo incorpora a las familias de su propia ruta: cada conductor convertido trae consigo entre diez y veinte tutores sin costo de adquisición adicional. La difusión se apoya en redes sociales locales y demostraciones presenciales en puntos de concentración de movilidades escolares.</td>
      <td>Comercialización orientada a instituciones mediante demostraciones, paquetes de servicio y posibilidades de personalización de la experiencia para cada organización.</td>
      <td>Adopción vinculada a instituciones y operadores de transporte, con una propuesta multirrol y un plan de prueba piloto comunicado desde su sitio oficial.</td>
      <td>No existe una estrategia única de transporte escolar: la adopción deriva principalmente de la presencia y utilidad general de cada aplicación.</td>
    </tr>
    <tr>
      <th rowspan="3">Perfil de Producto</th>
      <th>Productos &amp; Servicios</th>
      <td>Gestión de rutas, paradas y estudiantes; programación del traslado; estados e hitos del viaje; confirmaciones de recojo y entrega; retrasos, incidencias, notificaciones e historial.</td>
      <td>Parent App, Driver App y Admin Panel; seguimiento de rutas, registro de abordaje y descenso, alertas, reservas, pagos, gestión administrativa y reportes.</td>
      <td>Ubicación de la ruta en tiempo real, notificaciones de imprevistos y proximidad, gestión de inasistencias, información de abordaje, herramientas para conductor/monitor y panel de coordinación con reportes.</td>
      <td>Chats, llamadas, envío de mensajes, ubicación compartida y navegación. La información queda repartida entre herramientas y conversaciones diferentes.</td>
    </tr>
    <tr>
  <th>Precios &amp; Costos</th>
  <td>Modelo SaaS con cobro al prestador del servicio: acceso gratuito para padres y tutores, y suscripción mensual para el conductor, que es quien obtiene el ahorro operativo. El usuario final no asume costo alguno. El rango de precio se validará durante el piloto.</td>
  <td>Comercialización por paquetes dirigidos a instituciones, sin tarifa pública general. La ausencia de un precio abierto y de contratación directa indica un modelo B2B negociado caso por caso con cada organización.</td>
  <td>Servicio comercial vinculado a la institución o al operador de la ruta. No publica planes de contratación individual, lo que sitúa la decisión de compra en el colegio y no en el conductor ni en la familia.</td>
  <td>No requieren una licencia específica de transporte escolar; el usuario puede tener costos asociados a conectividad o a las condiciones generales de cada servicio.</td>
</tr>
    <tr>
      <th>Canales de distribución (Web y/o Móvil)</th>
      <td>Landing Page y Frontend Web Application responsive.</td>
      <td>Aplicaciones móviles para usuarios y plataforma/panel de administración.</td>
      <td>Aplicaciones móviles para los participantes de la ruta y plataforma web para coordinación.</td>
      <td>Principalmente aplicaciones móviles; algunos servicios también disponen de acceso web.</td>
    </tr>
    <tr>
      <th rowspan="4">Análisis SWOT</th>
      <th>Fortalezas</th>
      <td>Enfoque concreto en los dos segmentos iniciales; estructura de eventos del viaje que permite reconstruir cualquier traslado; experiencia responsive accesible desde navegador sin instalación. El valor del MVP se sostiene sobre hitos confirmados y no sobre GPS continuo, ETA dinámico ni geofencing, lo que reduce el costo de infraestructura y la exposición de datos del menor.</td>
      <td>Suite especializada consolidada, múltiples aplicaciones por rol, seguimiento en tiempo real, registro de pasajeros, administración, reportes, reservas y pagos.</td>
      <td>Especialización en rutas escolares, ubicación en tiempo real, notificaciones de eventos, gestión de inasistencias y coordinación entre varios roles.</td>
      <td>Alta familiaridad, disponibilidad inmediata y flexibilidad para mensajería, llamadas, navegación y ubicación compartida.</td>
    </tr>
    <tr>
      <th>Debilidades</th>
      <td>Producto nuevo y sin base instalada. La calidad de la información depende de que el conductor registre los hitos durante la jornada, por lo que la adopción del segmento conductor condiciona el valor percibido por las familias. No ofrece validación institucional de credenciales, respaldo con el que sí cuentan las soluciones vinculadas a un colegio.</td>
      <td>Su propuesta está orientada principalmente a instituciones y operaciones de transporte organizadas, por lo que puede resultar más amplia que las necesidades iniciales de una relación directa conductor–familia.</td>
      <td>La propuesta articula colegio, coordinadores, monitores y conductores, por lo que su adopción está fuertemente vinculada a una operación institucional o de ruta ya organizada.</td>
      <td>Información fragmentada, historial difícil de estructurar, ausencia de un ciclo de vida propio del viaje y necesidad de repetir comunicaciones manualmente.</td>
    </tr>
    <tr>
      <th>Oportunidades</th>
      <td>Atender la coordinación digital entre familias y conductores de movilidad escolar en Lima y Callao con una solución enfocada, accesible desde navegador y adaptada al contexto local.</td>
      <td>Ampliar su presencia a nuevos mercados e instituciones y aprovechar su suite existente para organizaciones que buscan digitalizar integralmente la gestión del transporte escolar.</td>
      <td>Extender alianzas con colegios y operadores de transporte escolar en más mercados latinoamericanos y aprovechar su experiencia de monitoreo y comunicación multirrol.</td>
      <td>Mantenerse como alternativa sustituta debido a la baja fricción de adopción y a que los usuarios ya conocen estas herramientas, incorporando además nuevas capacidades generales de comunicación y navegación.</td>
    </tr>
    <tr>
      <th>Amenazas</th>
      <td>Hábitos arraigados de coordinación mediante mensajería y llamadas; presencia de plataformas especializadas ya operativas; exigencias de confianza y privacidad por tratar información relacionada con menores.</td>
      <td>Competidores locales más ligeros o adaptados a mercados específicos; barreras de adopción para operadores pequeños; sustitución parcial mediante herramientas generalistas de comunicación y navegación.</td>
      <td>Entrada de soluciones con onboarding más simple para conductores independientes; competencia de suites internacionales y permanencia de canales informales ya adoptados.</td>
      <td>Las plataformas especializadas pueden reemplazar parte de su uso en transporte escolar al ofrecer permisos por rol, trazabilidad, estados del viaje, notificaciones estructuradas y reportes.</td>
    </tr>
  </tbody>
</table>

**Fuentes consultadas para contrastar las capacidades de los competidores:**

- SchoolBusTracker: https://www.schoolbustrackerapp.com/
- Bus esCool: https://busescool.com/
- WhatsApp Brand Resources: https://www.meta.com/brand/resources/whatsapp/whatsapp-brand/
- Waze: https://www.waze.com/

### 2.1.2. Estrategias y tácticas frente a competidores

Para organizar las estrategias y tácticas preliminares de **Rumbo** frente a la competencia, se emplean las matrices **FODA** y **CAME**. La matriz FODA resume la situación interna de la startup y el contexto externo identificado en el Competitive Analysis Landscape. A partir de ello, la matriz CAME plantea acciones para **Corregir debilidades, Afrontar amenazas, Mantener fortalezas y Explotar oportunidades**.

#### Matriz FODA

<table>
  <thead>
    <tr>
      <th>Interno / Externo</th>
      <th>Positivo</th>
      <th>Negativo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Interno</th>
      <td>
        <strong>Fortalezas (F)</strong><br><br>
        • Enfoque específico en los dos segmentos objetivo del proyecto: padres/tutores y conductores de movilidad escolar.<br><br>
        • Centralización de estados del traslado, hitos, retrasos, incidencias y notificaciones dentro de un mismo flujo de información.<br><br>
        • Web Application responsive planteada para funcionar con los dispositivos de los usuarios y sin requerir hardware propietario para las funcionalidades del MVP.
      </td>
      <td>
        <strong>Debilidades (D)</strong><br><br>
        • Producto nuevo, sin una base instalada ni confianza consolidada frente a soluciones que ya operan en el mercado.<br><br>
        • El alcance actual no contempla todavía GPS continuo, ETA dinámico ni geofencing, mientras que competidores especializados ya ofrecen capacidades de seguimiento en tiempo real.<br><br>
        • El valor de la coordinación depende de que conductores y familias adopten y utilicen de manera consistente la plataforma.
      </td>
    </tr>
    <tr>
      <th>Externo</th>
      <td>
        <strong>Oportunidades (O)</strong><br><br>
        • Los canales informales como mensajería, llamadas y ubicación compartida no estructuran el ciclo del traslado escolar ni consolidan un historial único de eventos.<br><br>
        • Las soluciones especializadas analizadas presentan una fuerte orientación a colegios, administradores y operaciones de transporte, lo que permite a Rumbo enfocarse en una experiencia directa para padres/tutores y conductores.<br><br>
        • La necesidad de reducir incertidumbre, mensajes repetitivos y falta de trazabilidad durante el traslado abre espacio para una solución centrada en estados e hitos claramente registrados.
      </td>
      <td>
        <strong>Amenazas (A)</strong><br><br>
        • SchoolBusTracker y Bus esCool ya ofrecen funciones especializadas de seguimiento, notificaciones y gestión del transporte escolar.<br><br>
        • WhatsApp, llamadas y herramientas de navegación cuentan con alta familiaridad y pueden seguir siendo suficientes para usuarios que no perciban un beneficio adicional al cambiar de herramienta.<br><br>
        • Las expectativas de los usuarios pueden estar influenciadas por competidores que ya ofrecen localización en tiempo real y otras capacidades que Rumbo ha dejado fuera del alcance actual.
      </td>
    </tr>
  </tbody>
</table>

#### Matriz CAME

| Estrategia                     | Tácticas preliminares de Rumbo                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **C — Corregir Debilidades**   | Validar progresivamente el MVP con ambos segmentos objetivo para mejorar usabilidad y confianza. Mantener claramente delimitado el alcance actual y evaluar GPS continuo, ETA dinámico y geofencing únicamente como evolución posterior si la validación demuestra su necesidad. Reforzar onboarding, autorizaciones y manejo de información de menores para reducir barreras de adopción.                                                               |
| **A — Afrontar Amenazas**      | Diferenciarse de las soluciones especializadas mediante una experiencia más acotada a la coordinación directa entre conductor y familia. Frente a WhatsApp, llamadas y navegación, demostrar el valor de disponer de estados, hitos, retrasos e incidencias en un registro estructurado. Evitar competir mediante funcionalidades que todavía no están implementadas y sostener la propuesta sobre capacidades verificables del producto.                |
| **M — Mantener Fortalezas**    | Conservar el enfoque en los dos segmentos definidos, la estructura cronológica de eventos del viaje y la centralización de información relevante. Mantener una experiencia responsive y consistente entre las vistas destinadas a conductores y padres/tutores. Preservar las reglas de autorización y privacidad previstas por el proyecto.                                                                                                             |
| **E — Explotar Oportunidades** | Orientar la adopción hacia casos donde la coordinación actual depende de mensajes o llamadas repetitivas. Posicionar a Rumbo como una alternativa estructurada para registrar y consultar el estado del traslado sin requerir una plataforma completa de administración de flotas. Priorizar en la experiencia las funcionalidades que cubren directamente los vacíos detectados: hitos del viaje, retrasos, incidencias, notificaciones y trazabilidad. |

## 2.2. Entrevistas

Para este bloque se realizaron **entrevistas semiestructuradas** con el objetivo de comprender las necesidades, hábitos, dificultades y expectativas de los dos segmentos objetivo de Rumbo: **padres o tutores** y **conductores de movilidad escolar**. Las entrevistas buscan conocer cómo se coordina actualmente el traslado escolar, qué información se intercambia, qué situaciones generan mayor incertidumbre y cuáles son las barreras que podrían influir en la adopción de una solución digital.

Se realizaron **seis entrevistas en total: tres por cada segmento**, de acuerdo con el alcance definido para AV1. La información obtenida servirá como evidencia para construir los User Personas, User Task Matrix, User Journey Maps, Empathy Maps y los demás artefactos de Needfinding.

### 2.2.1. Diseño de entrevistas

#### Aristas de la investigación

Las entrevistas se diseñaron como **semiestructuradas**: cada ítem del guion plantea un tema a explorar y el entrevistador profundiza con repreguntas según lo que el participante relata, por lo que varios ítems agrupan deliberadamente más de un aspecto de una misma arista. El guion se organizó en seis aristas derivadas de los Assumptions formulados en el Lean UX Process, de modo que los hallazgos puedan contrastarse directamente contra los supuestos declarados.

| #   | Arista                                       | Qué busca establecer                                                                                                                       | Padres/Tutores | Conductores  |
| --- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | -------------- | ------------ |
| A1  | Contexto y perfil del usuario                | Quién es, dónde opera, con qué frecuencia participa del servicio y con qué herramientas digitales está familiarizado.                      | 1, 2, 3        | 1, 2, 3      |
| A2  | Proceso actual de coordinación               | Cómo se organiza hoy el recojo, el traslado y el retorno, y por qué medios se confirma cada hito.                                          | 4, 5           | 4, 5         |
| A3  | Fricciones, imprevistos e incertidumbre      | Qué falla durante el recorrido, cómo se resuelve y en qué momentos la falta de información pesa más.                                       | 6, 7           | 6            |
| A4  | Carga de comunicación                        | Volumen, motivo y repetición de los intercambios entre familias y conductor, y qué parte de esa carga es evitable.                         | 8              | 7            |
| A5  | Privacidad, confianza y tratamiento de datos | Qué información se considera sensible y qué condiciones debe cumplir una plataforma para merecer confianza.                                | 10             | 10           |
| A6  | Condiciones y barreras de adopción           | Qué tendría que ofrecer una herramienta para usarse de forma recurrente, qué la haría abandonarse y en qué momentos su uso resulta viable. | 9, 11, 12      | 8, 9, 11, 12 |

Las aristas A2, A3 y A4 indagan sobre comportamiento ya ocurrido y se ubicaron al inicio del guion para que el participante describa situaciones concretas antes de considerar cualquier funcionalidad. Las aristas A5 y A6 recogen criterios de decisión y se dejaron para el tramo final, de modo que no condicionen las respuestas anteriores.

Las preguntas combinan información demográfica y contextual con preguntas abiertas sobre comportamientos reales. Durante la entrevista se priorizó que el participante describa experiencias concretas antes de presentar posibles funcionalidades de Rumbo, con el fin de reducir el sesgo de confirmación y detectar necesidades que el equipo todavía no haya considerado.

#### Preguntas dirigidas al primer segmento — Padres y tutores

1. ¿Cuál es tu nombre completo, edad, ocupación y distrito de residencia?
2. ¿Qué relación tienes con el menor que utiliza movilidad escolar, qué edad tiene y con qué frecuencia utiliza este servicio?
3. ¿Qué dispositivo, navegador y aplicaciones utilizas con mayor frecuencia para comunicarte o consultar información durante el día?
4. Cuéntame cómo coordinas actualmente el recojo, traslado y regreso del menor con el conductor.
5. ¿Cómo sabes actualmente que la movilidad está próxima, que el menor fue recogido o que llegó a su destino?
6. ¿Qué situaciones inesperadas o retrasos has vivido durante un traslado escolar y cómo actuaste cuando ocurrieron?
7. ¿En qué momentos del recorrido sientes mayor incertidumbre o falta de información?
8. ¿Con qué frecuencia contactas al conductor durante una ruta, por qué motivos y qué consultas se repiten más?
9. ¿Qué información o notificaciones te resultarían realmente útiles durante el recorrido y cuáles considerarías innecesarias?
10. ¿Qué aspectos de privacidad o seguridad te preocuparían al utilizar una plataforma relacionada con la ubicación y el traslado de un menor?
11. ¿Qué tendría que ofrecer una herramienta digital para que confíes en ella y la utilices con frecuencia, y qué dificultades podrían hacer que dejaras de usarla?
12. Si pudieras cambiar una sola cosa de la forma en que hoy se coordina la movilidad escolar, ¿qué cambiarías y por qué?

#### Preguntas dirigidas al segundo segmento — Conductores de movilidad escolar

1. ¿Cuál es tu nombre completo, edad, ocupación, distrito de residencia y cuántos años de experiencia tienes realizando transporte escolar?
2. ¿Cuántos estudiantes y rutas manejas normalmente durante una jornada de trabajo?
3. ¿Qué dispositivo, navegador y aplicaciones o canales digitales utilizas con mayor frecuencia para organizar tu trabajo y comunicarte con las familias?
4. Cuéntame cómo organizas actualmente los estudiantes, horarios, puntos de recojo y cambios que pueden surgir antes de una ruta.
5. ¿Cómo confirmas actualmente que un estudiante fue recogido o entregado y cómo comunicas esos eventos a sus familiares?
6. ¿Qué situaciones imprevistas o retrasos ocurren con mayor frecuencia durante una ruta y cómo los comunicas a las familias?
7. ¿Qué información te piden los padres con mayor frecuencia y qué parte de esa comunicación te quita más tiempo o se vuelve repetitiva?
8. ¿En qué momentos sería seguro y realista registrar información en un sistema sin distraerte de la conducción, y qué acciones digitales serían poco prácticas durante tu jornada?
9. ¿Qué información te sería útil conservar como historial de una ruta para resolver posteriormente dudas o reclamos?
10. ¿Qué datos consideras privados o que no deberían mostrarse libremente dentro de una plataforma de movilidad escolar?
11. ¿Qué tendría que ofrecer una herramienta digital para que la utilices de manera recurrente y qué barreras podrían impedir que la adoptes?
12. Si pudieras mejorar una sola parte de la coordinación con padres y tutores, ¿cuál sería y por qué?

**Limitaciones del instrumento.** La pregunta 9 del primer segmento recoge expectativas declaradas y no comportamiento observado, por lo que sus respuestas se interpretaron como indicio de prioridad y no como evidencia de uso. Esta distinción se mantiene en el análisis de la sección 2.2.3: los hallazgos relativos a la ubicación en tiempo real se contrastaron contra lo que los entrevistados describieron hacer actualmente, y no únicamente contra lo que declararon preferir.

### 2.2.2. Registro de entrevistas

Para cada entrevista se registra nombre completo, edad, distrito, segmento, captura, URL del video, timing, duración y resumen descriptivo. Actualmente se cuenta con **seis entrevistas registradas: tres del segmento Padres/Tutores y tres del segmento Conductores de movilidad escolar**, cumpliendo el mínimo requerido para ambos segmentos.

|   # | Entrevistado                   | Edad | Distrito        | Segmento    | Duración | Referencia                                                    |
| --: | ------------------------------ | ---: | --------------- | ----------- | :------- | ------------------------------------------------------------- |
|   1 | Gisela Paola Santi Quispe      |   45 | San Miguel      | Padre/Tutor | 12:55    | [Entrevista 1](#entrevista-1--gisela-paola-santi-quispe)      |
|   2 | Marleny Nori Padilla Aguirre   |   47 | Cercado de Lima | Padre/Tutor | 15:32    | [Entrevista 2](#entrevista-2--marleny-nori-padilla-aguirre)   |
|   3 | Leonel Adrián Mitma Garro      |   24 | Callao          | Padre/Tutor | 7:43     | [Entrevista 3](#entrevista-3--leonel-adrián-mitma-garro)      |
|   4 | Gabriel Alexandro Sosa Guevara |   20 | Los Olivos      | Conductor   | 09:51    | [Entrevista 4](#entrevista-4--gabriel-alexandro-sosa-guevara) |
|   5 | Brayan Solorzano Pineda        |   25 | Pueblo Libre    | Conductor   | 09:05    | [Entrevista 5](#entrevista-5--brayan-solorzano-pineda)        |
|   6 | Vilma Hoyos Martinez           |   56 | San Miguel      | Conductor   | 18:14    | [Entrevista 6](#entrevista-6--vilma-hoyos-martinez)           |

#### Entrevista 1 — Gisela Paola Santi Quispe

- **Edad:** 45 años.
- **Ocupación / segmento:** Padre o tutor de familia.
- **Edad del menor:** 12 años y 6 años
- **Distrito:** San Miguel.
- **Frecuencia de uso:** 2 días a la semana.
- **Duración:** 12:55. 
- **Timing de inicio:** 00:00.
- **Video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221e646_upc_edu_pe/IQAidRav7C7uTanDv_bGmDR7AelCr3B6zxh1HNJcxzSEYkY?e=jnKSeK&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

<p align="center"><img width="1433" height="657" alt="image" src="./assets/chapter02/interview-gisela-santi.png" /></p>

**Resumen:**

Gisela Santi, de 45 años, reside en San Miguel y utiliza el servicio de movilidad escolar dos días por semana para dos menores de 6 y 12 años. Coordinar a dos estudiantes de edades distintas en una misma jornada es lo que caracteriza su uso del servicio: depende por completo de WhatsApp para saber en qué punto del recorrido se encuentra cada uno, y es por ese canal que el conductor le envía mensajes y actualizaciones.

No ha experimentado retrasos ni complicaciones con el servicio. Su preocupación no está en la operación sino en la información: lo que más le inquieta es el nivel de privacidad sobre la ubicación de sus menores y los datos del conductor, a quien considera que debe conocer con certeza antes de confiarle el traslado. Condiciona el uso de cualquier herramienta digital al tratamiento que esta haga de esa información.

#### Entrevista 2 — Marleny Nori Padilla Aguirre

- **Edad:** 47 años.
- **Ocupación / segmento:** Padre o tutor de familia.
- **Edad del menor:** 14 años.
- **Distrito:** Cercado de Lima.
- **Frecuencia de uso:** 1 día a la semana.
- **Duración:** 15:32.           
- **Timing de inicio:** 00:00.
- **Video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221e646_upc_edu_pe/IQBZEYrCvz0UTYUAl1mpybc0AY7AkjTMQVY_AlCxp-8OP34?e=nc6MsX&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

<p align="center"><img width="1433" height="657" alt="image" src="./assets/chapter02/interview-marleny-padilla.png" /></p>
  
**Resumen:**

Marleny Padilla, de 47 años, es ama de casa y reside en Cercado de Lima. Utiliza el servicio con baja frecuencia —un día por semana— para su hija de 14 años, que cursa secundaria. Al permanecer en casa durante la jornada, su coordinación se concentra en los momentos de salida y retorno, y se apoya íntegramente en WhatsApp, por donde recibe los mensajes y las actualizaciones de ubicación del conductor.

Tampoco ha enfrentado retrasos ni incidentes con el servicio. Su reserva coincide con la de la entrevistada anterior, y la coincidencia resulta significativa: pese a tratarse de una adolescente y no de una niña pequeña, la privacidad de la ubicación y la identidad del conductor siguen siendo su principal condición para adoptar una plataforma. La edad del estudiante no reduce la exigencia de confianza.

#### Entrevista 3 — Leonel Adrián Mitma Garro

- **Edad:** 24 años.
- **Ocupación / segmento:** Padre o tutor de familia.
- **Edad del menor:** 6 años.
- **Distrito:** Callao.
- **Frecuencia de uso:** 5 días a la semana.
- **Duración:** 07:43.         
- **Timing de inicio:** 00:00.
- **Video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202423163_upc_edu_pe/IQAiG1Qiytv5T7nH1uVETjB1AbaTGE1RMaOf4cY4BH8dFkE?e=9F3PT4

  <p align="center"><img width="1433" height="657" alt="image" src="./assets/chapter02/leonel-entrevista.png" /></p>

**Resumen:** Leonel Adrián es un padre de familia de 24 años que reside en el distrito del Callao. Utiliza el servicio de movilidad escolar cinco días a la semana para que su hijo de 6 años asista al nido. Para comunicarse con el conductor, emplea principalmente WhatsApp. Por este medio, el chófer envía fotografías al grupo de padres como evidencia de que los niños han llegado a su destino, lo cual le genera tranquilidad. A pesar de no haber experimentado retrasos ni complicaciones con el servicio, Adrián admite sentir cierta incertidumbre durante el trayecto de su hijo debido a la inseguridad ciudadana que hay en su distrito. Si se implementara una herramienta digital para el servicio, considera que lo más útil sería poder visualizar la ubicación exacta del vehículo en tiempo real. Además, mencionó que sería ideal contar con cámaras de seguridad, aunque es consciente de que sería difícil de implementar. Por el momento, Adrián se encuentra completamente satisfecho con el servicio, siente que todo va acorde y no realizaría ningún cambio en la forma actual de coordinación.

#### Entrevista 4 — Gabriel Alexandro Sosa Guevara

- **Edad:** 20 años.
- **Ocupación / segmento:** Conductor de movilidad escolar.
- **Experiencia en el rubro:** 2 años.
- **Distrito:** Los Olivos.
- **Duración:** 09:51.
- **Timing de inicio:** 00:00.
- **Video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202422298_upc_edu_pe/IQC8MugJp8RuRYBv6-JB1JqxAa7zKfdSDfWOW6lMscwFzxg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=MUf4ft

<p align="center"><img src="./assets/chapter02/interview-gabriel-sosa.png" alt="Captura de la entrevista a Gabriel Alexandro Sosa Guevara" width="850"/></p>

**Resumen:** Gabriel cuenta con 2 años de experiencia realizando transporte escolar. Utiliza diariamente su teléfono para trabajar y principalmente usa WhatsApp para comunicarse con las familias y Google Maps para organizar sus rutas. Comenta que uno de los problemas que presenta es tener la información fragmentada en distintos chats, lo que hace poco práctico buscar entre conversaciones para verificar si un estudiante será recogido o consultar la dirección de un punto de llegada alternativo. Además, menciona que es repetitivo responder diariamente las preguntas de los padres sobre cuánto falta para que llegue su hijo, si la movilidad se encuentra cerca o si el estudiante se encuentra bien, ya que esto puede distraerlo mientras conduce. También considera que, en caso de utilizar una aplicación, esta debería ser fácil y rápida de utilizar para no quitarle tiempo durante la conducción. Entre las funcionalidades que considera útiles se encuentran una lista de alumnos, el orden de recojo y la posibilidad de registrar rápidamente cuándo recoge o entrega a un estudiante. Asimismo, le gustaría que los padres puedan visualizar el estado de la ruta y su ubicación para mantenerse informados sin necesidad de comunicarse constantemente con él.

#### Entrevista 5 — Brayan Solorzano Pineda

- **Edad:** 25 años.
- **Ocupación / segmento:** Conductor de movilidad escolar.
- **Experiencia en el rubro:** 5 años.
- **Distrito:** Pueblo Libre.
- **Duración:** 09:05.
- **Timing de inicio:** 00:00.
- **Video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202422298_upc_edu_pe/IQDViGOQ_7GOQYDKI1MqVAXNAacWQv3o8bRMqBJbKkhsKp8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=6tRx0m

<p align="center"><img src="./assets/chapter02/interview-brayan-solorzano.png" alt="Captura de la entrevista a Brayan Solorzano Pineda" width="850"/></p>

**Resumen:** Brayan cuenta con 5 años de experiencia en el rubro. Comenzó trabajando en transporte personal, pero luego se trasladó al rubro del transporte escolar. Utiliza un grupo de WhatsApp para enviar avisos a los padres; sin embargo, los tutores prefieren escribirle por privado. Además, utiliza Waze para evitar el tráfico y el calendario de su teléfono para recordar horarios especiales. Ha tenido problemas para recordar cambios en las rutas debido a modificaciones en el recojo de un alumno, especialmente porque varios padres le escriben. Diariamente, los padres también le preguntan si ya se encuentra cerca o si los niños ya llegaron a la escuela, lo cual considera repetitivo. Comenta que durante la conducción no utilizaría una aplicación. Sin embargo, le sería útil contar con un registro del inicio del recorrido, la hora de recojo de cada alumno y la hora de llegada a la escuela. También considera útil registrar cuando un alumno no será recogido. En general, considera que una aplicación debería ayudarlo a organizar los cambios y permitir que los padres puedan seguir la ruta sin necesidad de preguntarle constantemente. No utilizaría una aplicación que lo obligue a realizar muchas acciones manualmente o que tenga un costo muy elevado. Como característica adicional, le gustaría que pudiera utilizarse en zonas donde existe poca señal.

#### Entrevista 6 — Vilma Hoyos Martinez

- **Edad:** 56 años.
- **Ocupación / segmento:** Conductor de movilidad escolar.
- **Experiencia en el rubro:** 25 años.
- **Distrito:** San Miguel.
- **Duración:** 18:14.
- **Timing de inicio:** 00:06.
- **Video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241b451_upc_edu_pe/IQAarNiMmGEZT73ZVhSkpNMNAVFqyptTBINEQvTJU6AW7BY?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=asjxgo

<p align="center"><img src="./assets/chapter02/interview-vilma-hoyos.png" alt="Captura de la entrevista a Vilma Hoyos" width="850"/></p>

**Resumen:** Vilma cuenta con 25 años de experiencia en el rubro de la movilidad escolar. Empezó llevando a estudiantes del colegio San Toribio, en el Rímac, hace 10 años y actualmente está a cargo de 26 niños en San Miguel, a quienes lleva a los colegios Claretiano y Los Rosales. La señora Vilma cuenta con un ayudante, quien utiliza la aplicación WhatsApp para comunicarse con las familias, coordinar horarios, llamar para avisar que deben bajar, informar si el niño asistirá, si necesita esperar y compartir su ubicación en tiempo real. Ha presentado problemas con la puntualidad de los niños y con la coordinación con los padres respecto a si los niños serán recogidos o no. Comenta que tiene conocimientos casi nulos en tecnología. Los padres le han recomendado utilizar algunas aplicaciones para poder realizar un mejor seguimiento del recorrido de sus hijos, pero menciona que no sabe cómo utilizarlas y, por ese motivo, no las implementa.

### 2.2.3. Análisis de entrevistas

En esta sección se analizan las respuestas obtenidas en las entrevistas registradas, con el fin de identificar las características objetivas y subjetivas más frecuentes en cada segmento objetivo. Los resultados presentados provienen exclusivamente de las entrevistas documentadas en la sección anterior y constituyen la base para la construcción de los User Personas.

#### Segmento 1: Padres y tutores

Este grupo de análisis reúne las entrevistas 1, 2 y 3, correspondientes a Gisela Paola Santi Quispe (45, San Miguel), Marleny Nori Padilla Aguirre (47, Cercado de Lima) y Leonel Adrián Mitma Garro (24, Callao). Los tres son responsables de uno o más menores que utiliza movilidad escolar en Lima Metropolitana o el Callao y contratan el servicio de forma directa con el conductor, sin intermediación del colegio, lo que los hace comparables entre sí.

**Características demográficas y de contexto**

| Variable                                               | Resultado                               |
| ------------------------------------------------------ | --------------------------------------- |
| Edad de los entrevistados                              | 24, 45 y 47 años (promedio: 38,7 años)  |
| Distritos de residencia                                | Callao, Cercado de Lima y San Miguel    |
| Edad de los menores que utilizan el servicio           | 6, 6, 12 y 14 años (promedio: 9,5 años) |
| Entrevistados con más de un menor en el servicio       | 33,3 %                                  |
| Frecuencia de uso del servicio                         | 1, 2 y 5 días a la semana               |
| Entrevistados que utilizan el servicio de forma diaria | 33,3 %                                  |

**Herramientas y canales digitales utilizados**

| Variable                                                               | Porcentaje |
| ---------------------------------------------------------------------- | ---------: |
| Utiliza WhatsApp como canal principal con el conductor                 |      100 % |
| Recibe actualizaciones de estado o ubicación por ese canal             |      100 % |
| Recibe evidencia de llegada mediante fotografías en el grupo de padres |     33,3 % |

**Frustraciones y preocupaciones identificadas**

| Variable                                                            | Porcentaje |
| ------------------------------------------------------------------- | ---------: |
| Manifiesta preocupación por la privacidad de la ubicación del menor |     66,7 % |
| Considera fundamental la confianza en el conductor y su información |     66,7 % |
| Declara incertidumbre durante el trayecto del menor                 |     33,3 % |
| Asocia esa incertidumbre a la inseguridad ciudadana de su distrito  |     33,3 % |
| Ha experimentado retrasos o complicaciones con el servicio          |        0 % |
| Manifiesta estar conforme con la forma actual de coordinación       |     33,3 % |

**Necesidades y expectativas sobre una solución digital**

| Variable                                                                  | Porcentaje |
| ------------------------------------------------------------------------- | ---------: |
| Considera prioritaria la ubicación del vehículo en tiempo real            |     33,3 % |
| Valora recibir evidencia de que el menor llegó a su destino               |     33,3 % |
| Menciona funcionalidades de videovigilancia dentro del vehículo           |     33,3 % |
| Condiciona el uso de la herramienta al tratamiento de los datos del menor |     66,7 % |
| Declara que no modificaría su forma actual de coordinación                |     33,3 % |

#### Hallazgos del análisis

**WhatsApp es el canal universal de coordinación.** La totalidad de los entrevistados de ambos segmentos utiliza esta aplicación para coordinar el servicio, lo que confirma el supuesto de que la comunicación ocurre hoy en un canal de uso general no diseñado para este fin.

**Las consultas repetitivas afectan principalmente al conductor.** Los tres conductores señalaron responder diariamente las mismas preguntas sobre la proximidad de la movilidad, y dos de ellos indicaron que esto los distrae mientras conducen. En contraste, ningún padre entrevistado describió esa comunicación como un problema propio. Esto sugiere que la reducción de consultas es un beneficio percibido con mayor claridad por el segmento de conductores, y que la propuesta de valor hacia las familias debe sustentarse en la tranquilidad y la confianza antes que en la eficiencia.

**La privacidad es la principal preocupación de los padres y tutores.** Dos de los tres entrevistados manifestaron que su mayor inquietud es el tratamiento de la ubicación del menor y la información del conductor, y condicionaron su confianza en una herramienta digital a este aspecto. Este hallazgo valida el supuesto de que la adopción dependerá de una adecuada gestión de permisos y visibilidad, y otorga prioridad a las historias de autorización de tutores y control de acceso.

**La expectativa de ubicación en tiempo real es menor a la anticipada.** Solo uno de los tres padres entrevistados mencionó la ubicación en tiempo real como la funcionalidad más valiosa, mientras que dos expresaron reparos precisamente sobre ese tipo de información. Esto respalda la decisión de diseño de Rumbo de mostrar estados e hitos confirmados en lugar de una secuencia continua de coordenadas, y de mantener el seguimiento de ubicación fuera del alcance inicial.

**La coordinación de ausencias es un problema no anticipado en su magnitud.** Los tres conductores mencionaron dificultades para saber si un estudiante será recogido, ya sea por mensajes dispersos, cambios de último momento o falta de aviso. Este hallazgo otorga mayor prioridad a la historia de reporte de ausencias de la que se le había asignado inicialmente en el Product Backlog.

**La evidencia de llegada tiene valor para las familias.** Un entrevistado destacó que recibir fotografías de la llegada le genera tranquilidad, lo que sugiere que la confirmación de hitos cumple una función equivalente sin exponer la ubicación continua del menor ni su imagen.

**La alfabetización digital es una barrera real de adopción.** La conductora con mayor experiencia en el rubro declaró conocimientos casi nulos en tecnología y delega el uso del teléfono en un ayudante, pese a que los padres le han recomendado aplicaciones de seguimiento. Este hallazgo refuerza la necesidad de una interfaz de pocos pasos e introduce la figura del ayudante como un usuario no previsto en los segmentos objetivo.

**La satisfacción con el servicio actual puede reducir la urgencia percibida.** Ningún padre entrevistado reportó haber experimentado retrasos o complicaciones, y uno manifestó no modificaría su forma actual de coordinación. Rumbo debe, por tanto, presentarse como un complemento que aporta tranquilidad y orden, y no como la corrección de un problema que las familias perciban como crítico.

#### Segmento 2: Conductores de movilidad escolar

Este grupo de análisis reúne las entrevistas 4, 5 y 6, correspondientes a Gabriel Alexandro Sosa Guevara (20, Los Olivos), Brayan Solorzano Pineda (25, Pueblo Libre) y Vilma Hoyos Martinez (56, San Miguel). Los tres operan de forma independiente en Lima Metropolitana y gestionan su propia cartera de familias, por lo que comparten la misma estructura de trabajo pese a diferir ampliamente en edad y en años de experiencia.

**Características demográficas y de contexto**

| Variable                                            | Resultado                                                        |
| --------------------------------------------------- | ---------------------------------------------------------------- |
| Edad de los entrevistados                           | 20, 25 y 56 años (promedio: 33,7 años)                           |
| Distritos de operación                              | Los Olivos, Pueblo Libre y San Miguel (100 % Lima Metropolitana) |
| Experiencia en el rubro                             | 2, 5 y 25 años (promedio: 10,7 años)                             |
| Conductores que operan de forma independiente       | 100 %                                                            |
| Conductores que cuentan con un ayudante o asistente | 33,3 %                                                           |

**Herramientas y canales digitales utilizados**

| Variable                                                    | Porcentaje |
| ----------------------------------------------------------- | ---------: |
| Utiliza WhatsApp como canal principal con las familias      |      100 % |
| Utiliza una aplicación de navegación (Google Maps, Waze)    |     66,7 % |
| Utiliza el calendario del teléfono para horarios especiales |     33,3 % |
| Declara conocimientos casi nulos en tecnología              |     33,3 % |
| Delega el uso del teléfono en un ayudante durante la ruta   |     33,3 % |

**Frustraciones identificadas**

| Variable                                                                 | Porcentaje |
| ------------------------------------------------------------------------ | ---------: |
| Recibe consultas repetitivas de los padres sobre el avance de la ruta    |      100 % |
| Presenta dificultades para coordinar si un estudiante será recogido o no |      100 % |
| Considera que la información queda fragmentada entre conversaciones      |     66,7 % |
| Indica que responder mensajes lo distrae mientras conduce                |     66,7 % |
| Ha tenido problemas para recordar cambios comunicados por los padres     |     33,3 % |
| Ha tenido problemas de puntualidad con los estudiantes                   |     33,3 % |

**Necesidades y expectativas sobre una solución digital**

| Variable                                                           | Porcentaje |
| ------------------------------------------------------------------ | ---------: |
| Considera útil registrar los hitos de recojo y entrega             |     66,7 % |
| Requiere que la aplicación sea rápida y de pocos pasos             |     66,7 % |
| Desea que los padres puedan seguir la ruta sin contactarlo         |     66,7 % |
| Considera útil contar con la lista de alumnos y el orden de recojo |     33,3 % |
| Declara que no utilizaría la aplicación mientras conduce           |     33,3 % |
| Menciona el costo como condición para adoptar la herramienta       |     33,3 % |
| Menciona el funcionamiento en zonas con poca señal                 |     33,3 % |
| No adopta aplicaciones recomendadas por desconocimiento de su uso  |     33,3 % |

## 2.3. Needfinding

### 2.3.1. User Personas

En esta sección se presentan las User Personas correspondientes a los dos segmentos objetivo. Cada arquetipo se construyó sobre un conjunto definido de entrevistados, seleccionado por compartir estructura de uso y no por similitud demográfica.

| User Persona         | Segmento      | Conjunto de entrevistados                                           | Patrón compartido que sustenta el arquetipo                                                                                                                                                       |
| -------------------- | ------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Gabriela Morales** | Padre / Tutor | Entrevistas 1, 2 y 3 — Gisela Santi, Marleny Padilla y Leonel Mitma | Los tres coordinan exclusivamente por WhatsApp, no disponen de ninguna vista del estado del traslado y condicionan su confianza en una herramienta digital al tratamiento de los datos del menor. |
| **Carlos Rivas**     | Conductor     | Entrevistas 4, 5 y 6 — Gabriel Sosa, Brayan Solórzano y Vilma Hoyos | Los tres operan de forma independiente, responden a diario las mismas consultas sobre el avance de la ruta y declararon dificultades para saber con antelación si un estudiante será recogido.    |

La edad y los años de experiencia no se utilizaron como criterio de agrupación, porque dentro de cada conjunto presentan una dispersión amplia —de 24 a 47 años en el primero y de 2 a 25 años de experiencia en el segundo— mientras que el proceso de trabajo y las frustraciones se mantienen constantes. Por ello, los rasgos demográficos de cada User Persona corresponden al valor medio del conjunto y no a ninguno de los entrevistados en particular.

**Perfil no cubierto por los arquetipos.** La entrevistada 6 declaró conocimientos casi nulos en tecnología y delegar el uso del teléfono en un ayudante durante la ruta. Este rasgo no se incorporó a Carlos Rivas por no ser compartido por el conjunto, pero se conservó como restricción de diseño: la interfaz debe ser operable en pocos pasos y con el vehículo detenido, sin asumir que quien registra los eventos es necesariamente quien conduce.

#### Segmento — Padres y tutores

<img width="1050" height="1438" alt="Gabriela Morales" src="./assets/chapter02/user-persona-gabriela.png"/>

#### Segmento — Conductores

<img width="1050" height="1228" alt="Carlos Rivas" src="./assets/chapter02/user-persona-carlos.png" />

### 2.3.2. User Task Matrix

La User Task Matrix resume las tareas que realizan los dos segmentos objetivo en su rutina de movilidad escolar, independientemente de que exista Rumbo. Para mantener coherencia con los User Personas, se consideran **Gabriela Morales (Padre/Tutor)** y **Carlos Rivas (Conductor)**.

| Tarea del usuario                                 | Padre/Tutor — Frecuencia | Padre/Tutor — Importancia | Conductor — Frecuencia | Conductor — Importancia |
| ------------------------------------------------- | :----------------------: | :-----------------------: | :--------------------: | :---------------------: |
| Preparar al estudiante antes del recojo           |          Diaria          |           Alta            |       No aplica        |        No aplica        |
| Confirmar si el estudiante utilizará la movilidad |          Diaria          |           Alta            |         Diaria         |          Alta           |
| Esperar / llegar al punto de recojo acordado      |          Diaria          |           Alta            |         Diaria         |          Alta           |
| Organizar el orden de paradas del recorrido       |        No aplica         |         No aplica         |         Diaria         |          Alta           |
| Confirmar que el estudiante fue recogido          |          Diaria          |           Alta            |         Diaria         |          Alta           |
| Consultar o comunicar el avance del traslado      |          Diaria          |           Alta            |         Diaria         |          Alta           |
| Comunicar un retraso                              |        Ocasional         |           Alta            |       Ocasional        |          Alta           |
| Comunicar una incidencia                          |        Ocasional         |           Alta            |       Ocasional        |          Alta           |
| Confirmar la llegada o entrega del estudiante     |          Diaria          |           Alta            |         Diaria         |          Alta           |
| Coordinar el retorno del estudiante               |          Diaria          |           Media           |         Diaria         |          Media          |

Las tareas de **confirmar asistencia, recojo y entrega** son recurrentes y de alta importancia para ambos segmentos. La diferencia principal está en que el padre/tutor necesita mantenerse informado, mientras que el conductor debe organizar el recorrido y comunicar cambios sin distraerse durante la conducción. Esta matriz respalda la prioridad dada a los estados del traslado, hitos, retrasos, incidencias y reporte de ausencias dentro del Product Backlog.

### 2.3.3. User Journey Mapping

En esta sección se presentan los **User Journey Maps** correspondientes a los dos segmentos objetivos: **Padres/Tutores y Conductores**. Estos mapas representan el recorrido actual de cada usuario durante el servicio de movilidad escolar, desde el inicio hasta el final de su experiencia.

Se presentan las versiones **As-Is**, que permiten analizar cómo se desarrolla actualmente el proceso sin la intervención de nuestra solución. A través de las diferentes etapas, actividades, puntos de contacto y dificultades identificadas, se busca comprender la experiencia de cada User Persona y detectar oportunidades de mejora.

#### Segmento — Padres y tutores

El journey del segmento Padre/Tutor inicia con la preparación del menor y la coordinación del servicio mediante WhatsApp. Durante la espera y el traslado, la principal necesidad es contar con información suficiente para confirmar el avance y la llegada sin depender de consultas constantes al conductor. Las entrevistas realizadas también muestran que la **privacidad de la ubicación del menor** y la **confianza en el conductor** son factores determinantes para adoptar una herramienta digital. Por ello, las oportunidades de mejora se concentran en ofrecer confirmaciones claras del traslado, información visible únicamente para usuarios autorizados y una experiencia que complemente —en lugar de complicar— la coordinación actual.

<img width="1556" height="1086" alt="USER JOURNEY MAP - PADRE-TUTOR" src="./assets/chapter02/user-journey-map-padres.png" />

#### Segmento — Conductores

El recorrido diario del conductor inicia **antes del viaje**, en un estado neutral, revisando chats de WhatsApp para corroborar las asistencias de forma tediosa y repetitiva. **Durante el viaje de ida** la experiencia desciende hacia la molestia, debido a lo estresante y peligroso que resulta manejar mientras responde mensajes constantes y llamadas sobre demoras. Al **terminar la ida y preparar el retorno**, recupera una actitud serena y de anticipación, aunque debe informarse de los cambios a través de conversaciones fragmentadas. **En el colegio**, durante la recogida, la experiencia se mantiene en vigilancia y neutralidad mientras cuenta y verifica la asistencia de los menores lidiando con llamadas de última hora. **Durante el viaje de regreso** vuelve a un estado neutral: reparte a los estudiantes mientras responde chats y busca información de contacto ante cualquier emergencia. Finalmente, **al concluir la jornada**, la sensación es de serenidad, aunque alcanzarla le exige comunicarse individualmente con cada familia para confirmar que los niños llegaron a sus domicilios.

<img width="1556" height="1086" alt="USER JOURNEY MAP - CONDUCTOR" src="./assets/chapter02/user-journey-map-conductor.png" />

### 2.3.4. Empathy Mapping

En esta sección se presentan los **Empathy Maps** elaborados para cada uno de los User Personas: **Parent/Tutor y Driver**. Estos mapas fueron construidos a partir de las observaciones obtenidas durante las entrevistas y permiten comprender sus necesidades, comportamientos, pensamientos, emociones, Pains y Gains dentro del contexto de la movilidad escolar.

##### Segmento — Padres y tutores

<img width="1050" height="1318" alt="Empathy map" src="./assets/chapter02/user-empthy-map-padres.png" />

##### Segmento — Conductores

<img width="1050" height="1318" alt="CARLOS RIVAS EMPATHY MAP" src="./assets/chapter02/user-empathy-map-conductor.png" />

## 2.4. Big Picture Event Storming

El equipo realizó una sesión de Big Picture EventStorming para comprender el dominio de la movilidad escolar de extremo a extremo antes de definir la solución. El objetivo fue identificar los hechos relevantes del negocio, ordenarlos según su secuencia real, reconocer quién los origina, qué sistemas externos participan y qué preguntas quedan abiertas, para obtener una primera delimitación de responsabilidades que será refinada posteriormente en el diseño DDD.

**Resumen del proceso realizado**

**1. Exploración del dominio.** Se recorrieron de extremo a extremo las actividades de los dos segmentos objetivo: la habilitación del conductor y su vehículo, el registro de las familias y sus estudiantes, la planificación de rutas y paradas, la programación y ejecución del traslado, la gestión de retrasos e incidencias, la comunicación hacia los tutores autorizados y el cierre e historial del servicio.

**2. Identificación de Domain Events.** Los hechos se registraron en tiempo pasado y en inglés, para mantener consistencia con el Ubiquitous Language. Se obtuvieron treinta y siete eventos en la línea principal, entre ellos `Driver Credential Verified`, `Vehicle Registered`, `Parent Linked to Student`, `Emergency Contact Registered`, `Route Created`, `Stop Order Defined`, `Student Assigned to Route`, `Assistant Access Granted`, `Trip Scheduled`, `Trip Roster Generated`, `Stop Reached`, `Student Pickup Confirmed`, `Student Pickup Missed`, `Delay Registered`, `Incident Reported`, `School Arrival Confirmed`, `Student Drop-off Confirmed`, `Trip Timeline Generated` y `Student Data Deletion Requested`. Ninguno de ellos describe pantallas ni decisiones técnicas: todos corresponden a cambios observables del negocio.

**3. Ordenamiento temporal y Pivotal Events.** Los eventos se ordenaron siguiendo el flujo real del servicio y se identificaron cuatro **pivotal events** que marcan transiciones irreversibles del dominio. Cada uno separa una fase de la siguiente mediante una línea divisoria:

Adicionalmente se identificó un **carril paralelo** de ocho eventos que no pertenecen a la secuencia principal porque pueden ocurrir en cualquier momento del ciclo: `Notification Triggered`, `Notification Sent`, `Notification Delivery Failed`, `Notification Read`, `Trip Status Consulted`, `Trip Timeline Consulted`, `Driver Information Consulted` e `Incident Acknowledged`. Los tres eventos de consulta representan lecturas de los usuarios y no modifican el estado del dominio; `Incident Acknowledged` sí lo hace, porque deja constancia de que el tutor fue informado.

| Pivotal Event      | Qué habilita                                                                                            |
| ------------------ | ------------------------------------------------------------------------------------------------------- |
| `Driver Onboarded` | Cierra la habilitación del conductor, su vehículo y su suscripción; sin este hito no puede crear rutas. |
| `Route Published`  | Convierte una ruta en configuración vigente y habilita la programación de viajes.                       |
| `Trip Started`     | Marca el paso de la planificación a la ejecución; a partir de aquí los eventos se registran en campo.   |
| `Trip Completed`   | Cierra la ejecución y habilita la consolidación de la línea de tiempo y el historial.                   |

Adicionalmente se identificó un **carril paralelo** de siete eventos que no pertenecen a la secuencia principal porque pueden ocurrir en cualquier momento del ciclo: `Notification Triggered`, `Notification Sent`, `Notification Delivery Failed`, `Notification Read`, `Trip Status Consulted`, `Trip Timeline Consulted` e `Incident Acknowledged`. Los tres últimos representan consultas de los usuarios y no modifican el estado del dominio.

**4. Actores, sistemas externos y hot spots.** Se asignó a cada evento el actor que lo origina, distinguiendo al **Driver**, que genera los eventos de configuración de ruta y de ejecución del traslado, del **Parent/Tutor**, que genera el registro de estudiantes, el reporte de ausencias, la lectura de notificaciones y la solicitud de eliminación de datos. Se incorporaron tres sistemas externos: la **ATU API** para contrastar la habilitación del conductor y del vehículo, la **API de Mapas** para resolver direcciones de paradas y estimar el avance del recorrido, y la **API de Notificaciones** como proveedor de entrega de los avisos. Finalmente se registraron los puntos de incertidumbre que el equipo no puede resolver en esta etapa:

| Hot spot                                                                   | Evento asociado              |
| -------------------------------------------------------------------------- | ---------------------------- |
| ¿Qué ocurre si la credencial del conductor vence durante el ciclo escolar? | `Driver Credential Verified` |
| ¿Qué sucede si falla el cobro de la suscripción con un servicio en curso?  | `Subscription Activated`     |
| ¿Cómo se valida que la dirección de una parada sea localizable?            | `Stop Added to Route`        |
| ¿Qué pasa si los estudiantes asignados superan la capacidad del vehículo?  | `Student Assigned to Route`  |
| ¿Quién puede cancelar un viaje ya programado y con cuánta anticipación?    | `Trip Cancelled`             |
| ¿Qué ocurre si el conductor pierde conectividad durante el recorrido?      | `Stop Reached`               |
| ¿Quién autoriza una entrega a una persona no registrada como tutor?        | `Drop-off Rejected`          |
| ¿Cuánto tiempo se conserva el historial antes de su eliminación?           | `Trip History Archived`      |

**5. Límites emergentes del dominio.** Los pivotal events no solo ordenan la secuencia: señalan los puntos donde el dominio cambia de responsable y de naturaleza. `Driver Onboarded` cierra la habilitación del prestador y abre la configuración del servicio; `Route Published` cierra la configuración y abre la operación; `Trip Started` separa la planificación de la ejecución en campo; y `Trip Completed` separa la ejecución del cierre documental. El carril paralelo de notificaciones y consultas se comporta de forma independiente a esta secuencia, lo que sugiere una responsabilidad propia. Estos límites emergentes constituyen la entrada para el Design-Level EventStorming, donde se formalizan como Bounded Contexts y se detallan sus commands, aggregates, policies y read models (sección 4.6.1).

**Captura consolidada y resultado**

<div align="center">
  <img src="./assets/chapter02/event-storming-vf.png" alt="Rumbo Big Picture Event Storming consolidado" width="95%">
</div>

**Artefacto colaborativo:** https://miro.com/app/board/uXjVIveDKA8=/?share_link_id=909349762479

El Big Picture evidencia que el núcleo operativo de Rumbo se concentra entre `Route Published` y `Trip Completed`, es decir, en la planificación y ejecución del traslado, mientras que identidad, perfiles, vehículos, incidencias, notificaciones y suscripción aportan capacidades de soporte. Los cuatro pivotal events delimitan las fases que estructurarán los Epics del Product Backlog, y los hot spots registrados anticipan las reglas de negocio y los riesgos que deberán resolverse en el Design-Level EventStorming y en el diseño de la base de datos.

## 2.5. Ubiquitous Language

En esta sección se define el glosario de términos del dominio de Rumbo, con el fin de que todos los miembros del equipo y los stakeholders utilicen un lenguaje común y sin ambigüedades durante el ciclo de vida del producto. Los términos se expresan en inglés, acompañados de su equivalente en español, y sus definiciones corresponden exclusivamente al dominio del transporte escolar.

El glosario se mantiene centrado únicamente en términos del dominio del transporte escolar y evita términos técnicos de ingeniería de software.

##### Personas y entidades del servicio

| Término                                                      | Definición en el dominio de Rumbo                                                                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| **Student** (Estudiante)                                     | Menor que utiliza el servicio de movilidad escolar y se encuentra asignado a una o más rutas.                            |
| **Parent / Tutor** (Padre o tutor)                           | Persona autorizada para consultar la información de un estudiante y recibir notificaciones sobre sus traslados.          |
| **Driver** (Conductor)                                       | Persona responsable de ejecutar una ruta de movilidad escolar y registrar los eventos del recorrido.                     |
| **Vehicle** (Vehículo)                                       | Unidad utilizada por un conductor para prestar el servicio de movilidad escolar.                                         |
| **Authorized User** (Usuario autorizado)                     | Persona cuya identidad y permisos le habilitan a acceder a información específica dentro de Rumbo.                       |
| **Driver Credential** (Credencial del conductor)             | Documento que acredita al conductor como habilitado para prestar el servicio de transporte de estudiantes.               |
| **Tutor Authorization** (Autorización de tutor)              | Permiso otorgado a un padre o tutor para acceder a la información de un estudiante determinado.                          |
| **School Transport Service** (Servicio de movilidad escolar) | Servicio destinado al traslado recurrente de estudiantes entre puntos de recojo, centros educativos y puntos de entrega. |
| **Emergency Contact** (Contacto de emergencia) | Persona designada por un tutor para ser contactada ante una situación imprevista durante el traslado de un estudiante. |
| **Assistant** (Asistente) | Persona habilitada por el conductor para confirmar hitos de una ruta específica, sin acceso a su configuración ni a su suscripción. |

##### Planificación de rutas

| Término                                    | Definición en el dominio de Rumbo                                                           |
| ------------------------------------------ | ------------------------------------------------------------------------------------------- |
| **Route** (Ruta)                           | Recorrido planificado que contiene un conjunto ordenado de paradas y estudiantes asignados. |
| **Stop** (Parada)                          | Punto planificado dentro de una ruta donde se realiza un recojo o una entrega.              |
| **Stop Order** (Orden de paradas)          | Secuencia en la que el conductor debe visitar las paradas de una ruta.                      |
| **Route Schedule** (Horario de la ruta)    | Días y horas en los que una ruta se ejecuta de forma recurrente.                            |
| **Assigned Student** (Estudiante asignado) | Estudiante incluido dentro de una ruta específica para una jornada o periodo determinado.   |

##### Ejecución del traslado

| Término                                          | Definición en el dominio de Rumbo                                                                         |
| ------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| **Trip** (Viaje)                                 | Ejecución concreta de una ruta en una fecha y franja horaria determinadas.                                |
| **Trip Roster** (Lista de estudiantes del viaje) | Relación de estudiantes previstos para un viaje específico, considerando las ausencias reportadas.        |
| **Trip Status** (Estado del viaje)               | Situación general de un viaje: programado, iniciado, en recorrido, retrasado, completado o cancelado.     |
| **Student Absence** (Ausencia del estudiante)    | Comunicación anticipada de que un estudiante no utilizará el servicio en una jornada determinada.         |
| **Pickup** (Recojo)                              | Evento mediante el cual el conductor confirma que un estudiante fue recogido en el punto correspondiente. |
| **Drop-off** (Entrega)                           | Evento mediante el cual el conductor confirma que un estudiante fue entregado en el destino previsto.     |
| **School Arrival** (Llegada al colegio)          | Evento que confirma que la movilidad llegó al centro educativo correspondiente.                           |
| **Return Trip** (Viaje de retorno)               | Ejecución de la ruta en sentido inverso, desde el centro educativo hacia los puntos de entrega.           |
| **Route Completion** (Cierre de la ruta)         | Término de un viaje después de completar los recojos o entregas previstos.                                |

##### Eventos e incidencias

| Término                                                     | Definición en el dominio de Rumbo                                                                                                                 |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Route Event** (Evento de ruta)                            | Acontecimiento relevante producido durante la ejecución de un viaje.                                                                              |
| **Trip Timeline** (Línea de tiempo del viaje)               | Secuencia cronológica de los principales eventos registrados durante un viaje.                                                                    |
| **Delay** (Retraso)                                         | Diferencia significativa entre el horario previsto de una ruta y su avance real.                                                                  |
| **ETA** (Tiempo estimado de llegada) | Hora estimada en la que la movilidad arribará a una parada o destino. Rumbo no calcula ETA dinámico en el alcance actual; el término se conserva porque aparece en las expectativas de los usuarios entrevistados. |
| **Incident** (Incidencia)                                   | Situación imprevista ocurrida durante el servicio que requiere ser registrada y comunicada a los tutores autorizados.                             |
| **Incident Type** (Tipo de incidencia)                      | Categoría que clasifica una incidencia según la naturaleza del imprevisto registrado.                                                             |
| **Trip History** (Historial de viajes)                      | Registro de los viajes ejecutados y sus eventos, conservado para consulta posterior.                                                              |
| **Data Deletion Request** (Solicitud de supresión de datos) | Pedido de un tutor para que se eliminen los datos personales de un estudiante, conforme a la normativa vigente de protección de datos personales. |

##### Comunicación

| Término                                                   | Definición en el dominio de Rumbo                                                          |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **Notification** (Notificación)                           | Aviso enviado a un usuario autorizado como consecuencia de un evento relevante de la ruta. |
| **Notification Preference** (Preferencia de notificación) | Configuración mediante la cual un padre o tutor determina qué avisos desea recibir.        |

##### Modelo de negocio

| Término                        | Definición en el dominio de Rumbo                                                                |
| ------------------------------ | ------------------------------------------------------------------------------------------------ |
| **Subscription** (Suscripción) | Plan contratado por un conductor que le habilita el uso de Rumbo durante un periodo determinado. |

---

# Capítulo III: Requirements Specification

## 3.1. User Stories

## 3.2. Impact Mapping

## 3.3. Product Backlog

---

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming

### 4.6.2. Software Architecture Context Diagram

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

## 4.8. Database Design

### 4.8.1. Database Diagrams

---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.X. Sprint n

#### 5.2.X.1. Sprint Planning n

#### 5.2.X.2. Aspect Leaders and Collaborators

#### 5.2.X.3. Sprint Backlog n

#### 5.2.X.4. Development Evidence for Sprint Review

#### 5.2.X.5. Execution Evidence for Sprint Review

#### 5.2.X.6. Services Documentation Evidence for Sprint Review

#### 5.2.X.7. Software Deployment Evidence for Sprint Review

#### 5.2.X.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

La propuesta visual toma como referencia los mock-ups elaborados en Figma para la Landing Page y extiende el mismo sistema de colores, tipografía, tarjetas y botones hacia la aplicación web.

## Conclusiones y recomendaciones

## Video About-The-Team

- `Trip Detail`
- `Notifications`

A partir de Trip Detail puede profundizar hacia:

---

# Anexos

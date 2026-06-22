# **Informe Trabajo Final**

<p align="center">
  <img src="Imagenes/LogoUPC.png" alt="Logo de la UPC" />
</p>

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center"><strong>Ingeniería de Software</strong>
<br>Aplicaciones Móviles <br>
<strong>Profesor: Jorge Luis Mayta Guillermo</strong> </p>

<h2 align="center">INFORME</h2>

<h3 align="center">Nombre del Startup: 	SODA </h3>
<p align="center"><strong>Nombre del producto: 	PowerSense</strong></p>

<p align="center"><strong>Ciclo académico: 2026-10</strong></p>

<p align="center"><strong>Código del curso: 1ACC0238</strong></p>

<p align="center"><strong>NRC del curso: 3646</strong></p>

<br>

## Integrantes
| Código | Apellidos y Nombres | Carrera |
| :--- | :--- | :--- |
| U202217678 | Aquino Solorzano, Daniel Jonatan | Ingeniería de Software |
| U202210104 | Lagos Rivera, Kael Valentino | Ingeniería de Software |
| U20231F412 | Ojanama Abanto, Johnny Alexander | Ingeniería de Software |
| U202217288 | Pastor Napa, Juan Carlos | Ingeniería de Software |
| U20221E121 | Pelaez Vargas, Giuliano Angel | Ingeniería de Software |

<br>

### **Fecha:** Abril, 2026



## Registro de versiones del informe
| Versión | Fecha | Autor | Descripción de modificación |
|:---:|:---:|:---:|:---|
| 1.0 | 24.04.2026 | Todo el grupo  | Elaboración de los primeros puntos del informe |
| 1.1 | 16.05.2026  | Todo el grupo | Elaboracion del Frontend y Backend más documentación adicional en el informe  |


## Project Report Collaboration Insights
[Repositorio de documentacion](https://github.com/Apps-Moviles-PowerSense/Report) <br>

[Repositorio del Landing Page](https://github.com/Apps-Moviles-PowerSense/Landing-Page) <br>

[Repositorio del Fronted Kotlin](https://github.com/Apps-Moviles-PowerSense/Frontend-Kotlin)

[Repositorio del Fronted Flutter](https://github.com/Apps-Moviles-PowerSense/Frontend---Flutter)

[Repositorio del Backend](https://github.com/Apps-Moviles-PowerSense/Backend)

# Tabla de Contenido
[Student Outcome](#student-outcome)

1. [Capítulo I: Introducción](#capítulo-i-introducción)
	- 1.1. [Startup Profile](#11-startup-profile) 
		- 1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)
  		- 1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
	- 1.2. [Solution Profile](#12-solution-profile)
		- 1.2.1 [Antecedentes y problemática](#121-antecedentes-y-problemática)
		- 1.2.2 [Lean UX Process](#122-lean-ux-process)
			- 1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)
			- 1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)
			- 1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
			- 1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)
	- 1.3. [Segmentos objetivo](#13-segmentos-objetivo)
2. [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
	- 2.1. [Competidores](#21-competidores)
		- 2.1.1. [Análisis competitivo](#211-análisis-competitivo)
		-  2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
	- 2.2. [Entrevistas](#22-entrevistas)
		-  2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)
		- 2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)
		- 2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)
	- 2.3. [Needfinding](#23-needfinding)
		- 2.3.1. [User Personas](#231-user-personas)
		- 2.3.2. [User Task Matrix](#232-user-task-matrix)
		- 2.3.3. [User Journey Mapping](#233-user-journey-mapping)
		- 2.3.4. [Empathy Mapping](#234-empathy-mapping)
		- 2.3.5. [Big Picture Event Storming](#235-big-picture-event-storming)
		- 2.3.6. [Ubiquitous Language](#236-ubiquitous-language)
  	- 2.4. [Requirements specification](#24-requirements-specification)
    	- 2.4.1. [User Stories](#241-user-stories)
		- 2.4.2. [Impact Mapping](#242-impact-mapping)
     	- 2.4.3. [Product Backlog](#243-product-backlog)
    - 2.5. [Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
    	- 2.5.1. [EventStorming](#251-event-storming)
       		- 2.5.1.1. [Candidate Context Discovery](#2511-candidate-context-discovery)
           	- 2.5.1.2. [Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
           	- 2.5.1.3. [Bounded Context Canvases](#2513-bounded-context-canvases)
        - 2.5.2. [Context Mapping](#252-context-mapping)
        - 2.5.3. [Software Architecture](#253-software-architecture)
      		- 2.5.3.1. [Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
        	- 2.5.3.2. [Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
         	- 2.5.3.3. [Software Architecture Deployment Level Diagrams](#2533-software-architecture-container-level-diagrams)
    - 2.6. [Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    	- 2.6.1. [Bounded Context: Dashboard](#261-bounded-context-dashboard)
     		- 2.6.1.1. [Domain Layer](#2611-domain-layer)
       		- 2.6.1.2. [Interface Layer](#2612-interface-layer)
            - 2.6.1.3. [Application Layer](#2613-application-layer)
            - 2.6.1.4. [Infrastructure Layer](#2614-infrastructure-layer)
            - 2.6.1.5. [Bounded Context Software Architecture Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)
            - 2.6.1.6. [Bounded Context Software Architecture Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)
            	- 2.6.1.6.1 [Bounded Context Domain Layer Class Diagrams](#26161-bounded-context-domain-layer-class-diagrams)
             	- 2.6.1.6.2 [Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)
    	- 2.6.2. [Bounded Context: Scheduling](#262-bounded-context-scheduling)
     		- 2.6.2.1. [Domain Layer](#2621-domain-layer)
       		- 2.6.2.2. [Interface Layer](#2622-interface-layer)
            - 2.6.2.3. [Application Layer](#2623-application-layer)
            - 2.6.2.4. [Infrastructure Layer](#2624-infrastructure-layer)
            - 2.6.2.5. [Bounded Context Software Architecture Component Level Diagrams](#2625-bounded-context-software-architecture-component-level-diagrams)
            - 2.6.2.6. [Bounded Context Software Architecture Code Level Diagrams](#2626-bounded-context-software-architecture-code-level-diagrams)
            	- 2.6.2.6.1 [Bounded Context Domain Layer Class Diagrams](#26261-bounded-context-domain-layer-class-diagrams)
             	- 2.6.2.6.2 [Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)        
    	- 2.6.3. [Bounded Context: Devices](#263-bounded-context-devices)
     		- 2.6.3.1. [Domain Layer](#2631-domain-layer)
       		- 2.6.3.2. [Interface Layer](#2632-interface-layer)
            - 2.6.3.3. [Application Layer](#2633-application-layer)
            - 2.6.3.4. [Infrastructure Layer](#2634-infrastructure-layer)
            - 2.6.3.5. [Bounded Context Software Architecture Component Level Diagrams](#2635-bounded-context-software-architecture-component-level-diagrams)
            - 2.6.3.6. [Bounded Context Software Architecture Code Level Diagrams](#2636-bounded-context-software-architecture-code-level-diagrams)
            	- 2.6.3.6.1 [Bounded Context Domain Layer Class Diagrams](#26361-bounded-context-domain-layer-class-diagrams)
             	- 2.6.3.6.2 [Bounded Context Database Design Diagram](#26362-bounded-context-database-design-diagram)      
    	- 2.6.4. [Bounded Context: Reports](#264-bounded-context-reports)
     		- 2.6.4.1. [Domain Layer](#2641-domain-layer)
       		- 2.6.4.2. [Interface Layer](#2642-interface-layer)
            - 2.6.4.3. [Application Layer](#2643-application-layer)
            - 2.6.4.4. [Infrastructure Layer](#2644-infrastructure-layer)
            - 2.6.4.5. [Bounded Context Software Architecture Component Level Diagrams](#2645-bounded-context-software-architecture-component-level-diagrams)
            - 2.6.4.6. [Bounded Context Software Architecture Code Level Diagrams](#2656-bounded-context-software-architecture-code-level-diagrams)
            	- 2.6.4.6.1 [Bounded Context Domain Layer Class Diagrams](#26561-bounded-context-domain-layer-class-diagrams)
             	- 2.6.4.6.2 [Bounded Context Database Design Diagram](#26562-bounded-context-database-design-diagram)   
    	- 2.6.5. [Bounded Context: Alerts](#265-bounded-context-alerts)
     		- 2.6.5.1. [Domain Layer](#2651-domain-layer)
       		- 2.6.5.2. [Interface Layer](#2652-interface-layer)
            - 2.6.5.3. [Application Layer](#2653-application-layer)
            - 2.6.5.4. [Infrastructure Layer](#2654-infrastructure-layer)
            - 2.6.5.5. [Bounded Context Software Architecture Component Level Diagrams](#2655-bounded-context-software-architecture-component-level-diagrams)
            - 2.6.5.6. [Bounded Context Software Architecture Code Level Diagrams](#2656-bounded-context-software-architecture-code-level-diagrams)
            	- 2.6.5.6.1 [Bounded Context Domain Layer Class Diagrams](#26561-bounded-context-domain-layer-class-diagrams)
             	- 2.6.5.6.2 [Bounded Context Database Design Diagram](#26562-bounded-context-database-design-diagram) 
		- 2.6.6. [Bounded Context: Auth](#266-bounded-context-auth)
     		- 2.6.6.1. [Domain Layer](#2661-domain-layer)
     		- 2.6.6.2. [Interface Layer](#2662-interface-layer)
     		- 2.6.6.3. [Application Layer](#2663-application-layer)
     		- 2.6.6.4. [Infrastructure Layer](#2664-infrastructure-layer)
     		- 2.6.6.5. [Bounded Context Software Architecture Component Level Diagrams](#2665-bounded-context-software-architecture-component-level-diagrams)
     		- 2.6.6.6. [Bounded Context Software Architecture Code Level Diagrams](#2666-bounded-context-software-architecture-code-level-diagrams)
     			- 2.6.6.6.1. [Bounded Context Domain Layer Class Diagrams](#26661-bounded-context-domain-layer-class-diagrams)
     			- 2.6.6.6.2. [Bounded Context Database Design Diagram](#26662-bounded-context-database-design-diagram)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
	- 3.1. [Product design](#31-product-design)
		- 3.1.1. [Style Guidelines](#311-style-guidelines)
			- 3.1.1.1. [General Style Guidelines](#3111-general-style-guidelines)
		- 3.1.2. [Information Architecture](#312-information-architecture)
			- 3.1.2.1. [Organization Systems](#3121-organization-systems)
			- 3.1.2.2. [Labeling Systems](#3122-labeling-systems)
			- 3.1.2.3. [SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
			- 3.1.2.4. [Searching Systems](#3124-searching-systems)
			- 3.1.2.5. [Navigation Systems](#3125-navigation-systems)
		- 3.1.3. [Landing Page UI Design](#313-landing-page-ui-design)
			- 3.1.3.1. [Landing Page Wireframe](#3131-landing-page-wireframe)
			- 3.1.3.2. [Landing Page Mock-up](#3132-landing-page-mock-up)
		- 3.1.4. [Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
			- 3.1.4.1. [Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
			- 3.1.4.2. [Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
			- 3.1.4.3. [Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
			- 3.1.4.4. [Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
			- 3.1.4.5. [Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
- [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)
	- 4.1. [Software Configuration Management](#41-software-configuration-management)
		- 4.1.1. [Software Development Environment Configuration](#411-software-development-environment-configuration)
		- 4.1.2. [Source Code Management](#412-source-code-management)
		- 4.1.3. [Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)
		- 4.1.4. [Software Deployment Configuration](#414-software-deployment-configuration)
	- 4.2. [Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
		- 4.2.1. [Sprint 1](#421-sprint-1)
			- 4.2.1.1. [Sprint Planning 1](#4211-sprint-planning-1)
			- 4.2.1.2. [Sprint Backlog 1](#4212-sprint-backlog-1)
			- 4.2.1.3. [Development Evidence for Sprint Review](#4213-development-evidence-for-sprint-review)
			- 4.2.1.4. [Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence-for-sprint-review)
			- 4.2.1.5. [Execution Evidence for Sprint Review](#4215-execution-evidence-for-sprint-review)
			- 4.2.1.6. [Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence-for-sprint-review)
			- 4.2.1.7. [Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence-for-sprint-review)
			- 4.2.1.8. [Team Collaboration Insights during Sprint](#4218-team-collaboration-insights-during-sprint)
	- 4.3. [Validation Interviews](#43-validation-interviews)
		- 4.3.1. [Diseño de Entrevistas](#431-diseño-de-entrevistas)
		- 4.3.2. [Registro de Entrevistas](#432-registro-de-entrevistas)
		- 4.3.3. [Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)


# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software** | <br>**Daniel Aquino AV1:**<br> Sesiones de Event Storming para identificar los eventos del dominio, comandos y actores clave. Se delimitaron las fronteras lógicas del sistema, analizando la responsabilidad de cada contexto. Se diseño la interacción detallada entre los agregados y servicios mediante el modelado de flujo de mensajes. Se establecieron los contratos de integración entre los contextos identificados. <br>**Daniel Aquino TB1:**<br> Sesiones de desarrollo de backend y despliegue de este con servicion de Azure. Sesiones para el desarrollo del diagrama de componentes clase y base de datos de diferentes bounde context. <br>**Daniel Aquino AV2:**<br> Sesiones para el desarrollo de la aplicación android usando Android Studio como IDE para desarrollo. <br> <br> **Giuliano Peláez AV1:** <br>Investigación de métricas de consumo eléctrico y normativas de OSINERGMIN. Aplicación del proceso Lean UX para definir el Problem Statement y los Assumptions. Redacción de las Hypothesis Statements para validar el impacto de la solución IoT. <br> **Giuliano Peláez TB1:** <br> Estudio de frameworks para la validación continua de productos de software y redacción técnica estructurada. Sesiones de alineamiento y planificación para la ejecución del Sprint 1, aplicando metodologías ágiles para asegurar que los servicios y su respectiva evidencia documental se registren bajo los estándares del proyecto. <br> <br> **Johnny Ojanama AV1:** <br> Investigación sobre las distintas competencias que presenta el startup y su análisis competitivo para poder ver sus pros, contras, fuerzas y debilidades. Aplicación del proceso Lean UX para diseñar y completar el Lean UX Canvas. <br> **Johnny Ojanama TB1:** <br> Indagación de nuevas tendencias en diseño de interfaces móviles y evaluación de frameworks modernos para el desarrollo web frontend. Conceptualización técnica para la construcción de la Landing Page, priorizando la experiencia de usuario y la adaptabilidad (responsiveness) del diseño en la navegación. <br> <br> **Kael Lagos AV1:** <br> Supervisión del cumplimiento de las indicaciones dadas en el aula virtual, corrección de la estructura inicial del informe, grabación de una de las primeras entrevistas, definición de los segmentos que abarcaremos y diseño de las preguntas para las entrevistas. <br> **Kael Lagos TB1:** <br> Profundización teórica en patrones de arquitectura de software para la correcta separación y estructuración del Interface Layer y Domain Layer. Análisis cualitativo avanzado de las entrevistas por segmento para extraer requisitos tangibles y revisión de herramientas de diseño para la elaboración de Mockups de alta fidelidad. <br> <br> **Juan Carlos Pastor AV1:** <br> Supervisión del cumplimiento dentro del grupo, ideas, organización, envio, dirección y control. Diseño de web, y aplicación móvil, cumpliendo heurísticas. <br> **Juan Carlos Pastor TB1:** <br> Análisis y actualización sobre lineamientos avanzados de UX/UI y diseño centrado en el usuario. Dirección estratégica de las sesiones creativas para los Mobile Wireframes y la Landing Page, asegurando que la capa Frontend mantenga coherencia visual y cumpla con los objetivos de negocio establecidos. <br> | La actualización de los datos e información tomados en cuenta para el desarrollo del proyecto requiere de una extensa investigación tomando en cuenta aspectos como la problemática, las posibles soluciones, las caracteristicas que debe tener el proyecto para cumplir con las expectativas de los usuarios ya sea a nivel de hogar o en un negocio. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software** |  <br>**Daniel Aquino AV1:**<br> Diagramas de Big Picture Event Storming. Design Level Event Storming. Candidate Context Discovery. Bounded Context Canvases. Domain Message Flow Modeling. Context Mapping. Software Architecture Context Level Diagrams. Software Architecture Container Level Diagrams. Software Architecture Deployment Diagram.  <br>**Daniel Aquino TB1:**<br> Diagrama de clase de capa dominio de diferentes bounded context, tanto para backend como firnted. Diagrama C4 de componentes para los bounded context. Subida del Backend al repositorio de la organización. Despligue del Backend usando los servicios de Azure mediante Web Apps y MySQL Flexible Server. <br>**Daniel Aquino AV2:**<br> Desarrollo del modulo de Profile, Schedules, Auth, Alerts, Devices y Dashboard.  <br> <br> **Giuliano Peláez AV1:** <br> Estructuración del Startup Profile, definiendo la misión y visión enfocadas en la eficiencia energética. Documentación de antecedentes y problemática del sector energético en Lima Metropolitana para sustentar la viabilidad del proyecto. <br> **Giuliano Peláez TB1:** <br> Elaboración detallada de la documentación de servicios (Services Documentation Evidence). Ejecución, seguimiento y cierre de las tareas correspondientes al Sprint 1. Aplicación de pruebas de validación del producto (Product Implementation & Validation), garantizando la calidad y estabilidad del software entregado en esta iteración. <br> <br> **Johnny Ojanama AV1:** <br> Creación del esqueleto base del proyecto. Lean UX Canvas. Respondiendo y definiendo las 5W y 2 H. Análisis competitivo y Estrategias y tácticas frente a competidores. <br> **Johnny Ojanama TB1:** <br> Construcción e implementación del código FrontEnd dedicado a la Landing Page del producto. Diseño, exportación y refinamiento de los Mobile Wireframes, detallando los flujos de interacción del usuario final. Redacción de la documentación técnica correspondiente a estas implementaciones visuales. <br> <br> **Kael Lagos AV1:** <br> Actualización del contenido del proyecto tomando en cuenta la nueva metodología del curso asi como la estructura que debe tener. Documentación de hipotesis ante las problematicas. Revisión de los videos pertenecientes a las entrevistas asegurandose de que la información sea útil y precisa para el desarrollo de los demás puntos del informe referente al proyecto. <br> **Kael Lagos TB1:** <br> Codificación y estructuración lógica de los componentes pertenecientes al Interface Layer y Domain Layer dentro de la arquitectura del software. Diseño final e iteración de los Mockups interactivos de la aplicación. Integración directa de los hallazgos obtenidos en la implementación de las entrevistas por segmento hacia el diseño del producto. <br> <br> **Juan Carlos Pastor AV1:** <br> Creación y organización de archivos y diseño gráfico.  <br> **Juan Carlos Pastor TB1:** <br> Desarrollo consolidado de las vistas del Frontend y maquetación final de la Landing Page principal. Creación de los Mobile Wireframes definitivos integrando los principios de Design UX para optimizar la retención de usuarios. Supervisión general y auditoría de los entregables para garantizar la correcta integración técnica de todo el equipo. <br> | La elaboración de este primer avance representa la etapa de planteamiento del problema así como de las posibles soluciones que pueden a ver con tal de resolver la problematica, en ese sentido debemos plantear correctamente la situación para así tener una buena base con la cual empezar a desarrollar lo demás. |
---

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

Nuestra startup, con origen en Perú, ofrece una solución tecnológica de vanguardia para que hogares y pequeñas empresas gestionen de manera activa su consumo energético, logrando así una significativa reducción de costos y de su huella de carbono.
Hemos desarrollado un sistema inteligente basado en el Internet de las Cosas (IoT). Este integra sensores y actuadores que permiten:

- Monitoreo en tiempo real del gasto de energía.

- Control remoto de dispositivos eléctricos.

La plataforma incorpora funciones de Inteligencia Artificial (IA) que analizan los patrones de uso, identifican ineficiencias y generan recomendaciones personalizadas para optimizar el consumo. Esto promueve un estilo de vida más sostenible y consciente con el medio ambiente.

### Visión y Misión

- **Visión:** Ser el referente líder en Sudamérica en soluciones de eficiencia energética inteligente, impulsando la transformación de las ciudades hacia modelos más sostenibles y resilientes.

- **Misión:** Empoderar a nuestros usuarios, brindándoles herramientas accesibles y sencillas que les permitan visualizar su consumo instantáneamente, programar el funcionamiento de sus dispositivos y adoptar hábitos responsables. Buscamos impactar positivamente en la economía doméstica, en el crecimiento empresarial y en la conservación del entorno natural, expandiendo nuestra cobertura desde Perú hacia toda la región.

### 1.1.2. Perfiles de integrantes del equipo 

| Foto                                                                                                                             | Alumno                            | Descripción|
|----------------------------------------------------------------------------------------------------------------------------------|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Aquino_Foto](Imagenes/Aquino.jpg)| Aquino Solorzano, Daniel Jonatan | Estudio actualmente la carrera de Ingeniería de Software. Me considero una persona responsable con sus trabajos y puntual en las entregas de estos. Tengo conocimientos técnicos en programación en lenguajes como C++ y Java. Tengo experiencia en desarrollo de aplicaciones Web según distintos enfoques y herramientas, centrándome más en el Backend.                                                                                                                                                                                                                                                                                                                                                |
| ![Johnny_Foto](Imagenes/Johnny.jpg)| Ojanama Abanto, Johnny Alexander       | Me llamo Johnny Ojanama, soy estudiante de la UPC con 19 años cursando el 6to ciclo. Me considero alguien responsable y cooperativo, si el equipo necesita de mi ayuda estaré más que dispuesto a ayudar para que el trabajo logre completarse. |
| ![Kael_Foto](Imagenes/Kael_Foto.jpg)                                                                                             | Kael Valentino, Lagos Rivera | Me llamo Kael Lagos, estudio en la UPC de Monterrico. Tengo muchas ganas de aprender, me considero una persona responsable que busca aprender de sus errores cada vez que puede y también me considero alguien que se centra en los detalles. Me comprometo a ayudar a mis compañeros para la elaboración de nuestro trabajo que nos pueda asegurar una buena nota al final.                                                                                                                                                                  |
|![Juan_Foto](Imagenes/Juan_Foto.png)                                                                                  | Pastor Napa, Juan Carlos    | Soy Juan Carlos Pastor Napa, estudiante de ingeniería de software. Soy una persona curiosa, perspicaz y creativa, enfocada en lograr los objetivos de desarrollo de este servicio en Desarrollo de Aplicaciones Móviles. Tengo experiencia previa en Kotlin y Android Studio.                                                                                                                                                                                           |
| ![Giuliano_Foto](Imagenes/Giuliano.jpg) | Pelaez Vargas, Giuliano Angel    | Me llamo Giuliano Peláez, soy estudiante de 6to ciclo de la carrera Ingeniería de Software. Me considero una persona empática, solidaria y puedo integrarme fácilmente a equipos de trabajo y entender las necesidades de mi compañero aparte soy muy enfocado en cumplir los objetivos del proyecto con calidad y poseo una gran proactividad para aprender nuevas cosas.                                                                                                                                                                                                                                                                                                                 |
## 1.2. Solution Profile 
### 1.2.1. Antecedentes y Problemática

En Lima Metropolitana, el sobreconsumo eléctrico residencial representa una problemática creciente, ya que una familia promedio consume alrededor de 172 kWh al mes, una cifra superior al promedio de otras regiones del país. Este nivel de consumo puede generar recibos mensuales de entre S/70 y S/150, dependiendo de la cantidad de equipos eléctricos utilizados dentro del hogar.

Además, en muchos hogares los aparatos en modo de espera pueden representar entre 5% y 10% del consumo total mensual, mientras que las viviendas de mayores ingresos llegan a consumir hasta 30% más electricidad que un hogar promedio debido al mayor número de dispositivos conectados.

Paralelamente, aunque el Perú ha iniciado un proceso de transición energética orientado a reducir emisiones y diversificar su matriz energética, la adopción de medidas de eficiencia todavía avanza de forma gradual. 

Por ello, resulta necesario implementar soluciones tecnológicas que permitan monitorear el consumo en tiempo real, reducir gastos domésticos y contribuir a un uso más sostenible de la energía.

-  	Who (¿Quién?)

Los principales actores afectados son los hogares de Lima Metropolitana y las pequeñas y medianas empresas (PYMEs). Ambos segmentos enfrentan altos costos de electricidad debido a un consumo por encima del promedio nacional. En los hogares, esto se traduce en un impacto directo en la economía familiar; en las PYMEs, en una disminución de la rentabilidad operativa, ya que los gastos fijos en energía se convierten en un obstáculo para su crecimiento.

-  	What (¿Qué?)

El problema central radica en el excesivo consumo de energía eléctrica sin mecanismos eficientes de monitoreo ni control. Actualmente, la mayoría de usuarios paga mensualmente por la energía utilizada sin conocer en detalle qué dispositivos consumen más, cuándo se generan picos de consumo, ni cómo reducirlos. Esto genera derroche de recursos y una huella ambiental innecesariamente elevada.

-  	Where (¿Dónde?)

El epicentro de este problema es Lima Metropolitana, donde el consumo energético promedio mensual en un hogar alcanza los 172 kWh, superando ampliamente el promedio nacional de 93 kWh (Auto Solar, 2025). Esta diferencia convierte a Lima en un caso crítico, donde se concentra gran parte de la demanda energética residencial del país, y por lo tanto, en el lugar ideal para implementar soluciones de optimización.

-  	When (¿Cuándo?)

La urgencia de atender este problema se enmarca en el contexto actual. Según Mongabay Latam (2024), el Perú carece de planes claros y avances consistentes en su transición energética hacia fuentes renovables. En consecuencia, los altos niveles de consumo en los hogares limeños no solo elevan las facturas eléctricas, sino que también retrasan los esfuerzos nacionales de sostenibilidad. Esto convierte al momento presente en una ventana crítica para implementar soluciones innovadoras que ayuden a cerrar la brecha.

-  	Why (¿Por qué?)

La causa del problema es doble: por un lado, económica, ya que el consumo excesivo genera gastos adicionales considerables en electricidad para familias y negocios; por otro, ambiental, debido a que gran parte de la electricidad en Perú proviene de fuentes no renovables, lo que incrementa la emisión de gases de efecto invernadero. Resolver este problema no solo alivia la carga financiera de los usuarios, sino que también contribuye a reducir la huella de carbono y a fomentar una cultura de eficiencia energética.

-  	How (¿Cómo?)

La solución se plantea mediante la implementación de una plataforma de Internet de las Cosas (IoT) “Verde”, que integre sensores y actuadores inteligentes para monitorear y controlar en tiempo real el consumo energético. El sistema incorporaría algoritmos de Inteligencia Artificial (IA) capaces de identificar patrones de uso, detectar ineficiencias y emitir recomendaciones prácticas al usuario, como apagar dispositivos en horarios de baja ocupación o programar encendidos automáticos. Así, se habilitaría un control remoto, programable y optimizado del consumo eléctrico.

-  	How Much (¿Cuánto?)

En términos monetarios, el sobreconsumo energético en Lima es significativo. Los 79 kWh adicionales que consume un hogar limeño al mes respecto al promedio nacional equivalen a un gasto de aproximadamente S/ 49,77 adicionales mensuales, es decir, cerca de S/ 600 al año, considerando un costo promedio de S/ 0,63 por kWh en tarifa residencial (OSINERGMIN, 2025). Este monto representa un ahorro potencial tangible que la plataforma IoT podría ofrecer a los usuarios al optimizar su consumo.

### 1.2.2. Lean UX Process

Para garantizar que nuestra solución tecnológica responda a necesidades reales y no a simples suposiciones, empleamos el proceso Lean UX. Esta metodología nos ayuda a comprender el problema, identificar aquello que damos por cierto y convertirlo en hipótesis que puedan validarse. De este modo, buscamos alinear el desarrollo de nuestro software tanto con los objetivos de los usuarios como con la visión de sostenibilidad que orienta nuestro startup.

#### 1.2.2.1 Lean UX Problem Statements

Nuestro proyecto ataca la ineficiencia energética en Lima, enfocándose en hogares y PYMEs que sufren el impacto de facturas eléctricas elevadas y la falta de control sobre sus activos. Hemos detectado que el principal punto de dolor es la opacidad del consumo: el usuario paga, pero no entiende en qué gasta.
Existe una brecha crítica en el mercado local por la ausencia de herramientas de monitoreo en tiempo real. Nuestra estrategia consiste en democratizar el uso de tecnología IoT "verde", integrando sensores inteligentes y control remoto para transformar datos en ahorros tangibles mediante recomendaciones automatizadas.

#### 1.2.2.2. Lean UX Assumptions

Al iniciar este proyecto, hemos definido las siguientes hipótesis críticas que requieren validación mediante experimentación y trabajo de campo:

-  	Interés en la monitorización: Postulamos que el usuario local valora la visibilidad del consumo en tiempo real como un activo para la toma de decisiones informadas.

-  	Viabilidad económica de la inversión: Suponemos una disposición de compra hacia hardware IoT, condicionada a la percepción de un retorno de inversión (ROI) tangible mediante el ahorro en la facturación mensual.

-  	Priorización estratégica en PYMEs: Asumimos que la eficiencia energética es un pilar fundamental en la estructura de costos y la sostenibilidad operativa del sector empresarial.

-  	Preferencia por el minimalismo funcional: Creemos que la adopción tecnológica se ve favorecida por interfaces simplificadas y de alta usabilidad, frente a sistemas con excesiva carga de funciones complejas.

#### 1.2.2.3. Lean UX Hypothesis Statements

La base de nuestros supuestos iniciales, hemos definido las siguientes hipótesis experimentales que orientarán las fases de prueba:

-  	Impacto en la Eficiencia Energética: Postulamos que la implementación de un sistema de monitoreo en tiempo real permitirá a los hogares limeños reducir su consumo mensual en un 10%. Validaremos esta hipótesis si, tras un trimestre de uso, el 70% de la muestra piloto registra una disminución efectiva en su facturación.

-  	Engagement en el Sector PYME: Proponemos que la integración de recomendaciones automatizadas de ahorro es el principal motor de uso para las pequeñas y medianas empresas. El éxito se medirá cuando el 50% de las empresas piloto realicen consultas semanales al dashboard de gestión.

-  	Adopción de Funcionalidades de Control: Sostenemos que el uso recurrente de la plataforma por parte de usuarios residenciales depende de herramientas de control directo, como el encendido/apagado remoto y la automatización de horarios. Consideraremos validada esta premisa si más del 60% de los usuarios activos interactúan con estas funciones semanalmente.

#### 1.2.2.4. Lean UX Canvas

<p align="center">
  <img src="Imagenes/Lean_Ux_Canvas.jpg" alt="Lean_Ux" />
</p>

## 1.3. Segmentos Objetivo

### Hogares limeños con recibo de luz

En Lima Metropolitana, los hogares representan un segmento objetivo estable, ya que el 97.6% cuenta con acceso al servicio eléctrico, lo que implica un pago recurrente del recibo de luz (INEI, 2021). Además, casi la mitad de los hogares pertenece al nivel socioeconómico C, lo que evidencia el predominio de la clase media en la ciudad (Ipsos, 2021).

El jefe de hogar suele ser un adulto de mediana edad, cercano a los 50 años, con un nivel educativo superior al promedio nacional, mientras que los hogares limeños tienen en promedio 3.5 integrantes (INEI, 2022; APEIM, 2022).

En cuanto al consumo, Lima registra una mediana de 190 kWh mensuales, generando recibos aproximados entre S/60 y S/120 según el equipamiento del hogar (Osinergmin, 2023).

### PYMEs limeñas

En Lima Metropolitana, las PYMEs constituyen un segmento relevante porque la ciudad concentra cerca del 42% de las empresas del país, y más del 99% corresponde a micro y pequeñas empresas (SUNAT, 2024). Estas organizaciones cumplen un papel importante en la economía nacional y en la generación de empleo local.

La mayoría de estas empresas emplea entre 2 y 3 trabajadores y se concentra principalmente en actividades de comercio minorista y servicios, mientras que una menor proporción pertenece al sector manufacturero (INEI, 2022).

En términos operativos, el consumo eléctrico representa un costo fijo importante, ya que un pequeño negocio puede consumir entre 200 y 300 kWh al mes, generando recibos aproximados de S/150 a S/250. Debido a que las tarifas comerciales no reciben subsidio, el control del consumo energético tiene un impacto directo en la rentabilidad del negocio (Osinergmin, 2023; MINEM, 2024).

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
A continuacion, se presenta una tabla que contiene a los competidores mas relevantes para nuestra IoS (IoT + Software/IA para monitoreo y optimización del consumo eléctrico).

| id | Nombre | Descripcion | Caracteristicas | Distribucion | Logo |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Smelpro | - Soluciones IoT e Inteligencia Artificial para Industria 4.0.<br><br> - Aplicaciones energéticas: monitoreo en tiempo real, detección de fallas, optimización de los costos operativos y mantenimiento predictivo.<br><br> - Sectores: manufactura, logística, minería, energía y agua. | - Monitoreo del consumo electrico en tiempo real.<br><br> - Detección de fallas y mantenimiento predictivo con uso de I.A.<br><br> - Optimización de los costos operativos.<br><br> - Soporte para LoRaWAN, Sigfox y redes celulares.<br><br> - Dashboards personalizados| - Ventas B2B directas.<br> - Integradores y proyectos llave en mano	 | ![Smelpro](Imagenes/smelpro.png) |
| 2 | LoraTech | - Empresa líder en soluciones IoT con tecnología LoRaWAN para monitoreo energético.<br><br> - Aplicaciones eléctricas: redes de sensores para medir el consumo eléctrico en tiempo real, control remoto de cargas, alertas y reportes para optimización.<br><br> - Ventajas: bajo consumo, alta penetración en interiores y seguridad de los datos.<br><br> - Sectores: industria, agroindustria y edificios inteligentes. | - Redes de sensores LoRaWAN para consumo en tiempo real.<br><br> - Alertas y reportes de anomalías y consumo.<br><br> - Dispositivos de bajo consumo y larga autonomía.<br><br> - Control remoto de cargas y automatización. | - Ventas B2B y partners integradores.<br><br> - Proyectos llave‑en‑mano y proveedores de gateways/servicios de red. | ![loratech](Imagenes/loratech.png) |
| 3 | Teca Perú | - Soluciones “llave‑en‑mano” en telemetría y telecontrol con fuerte uso de LoRaWAN.<br><br> - Aplicaciones energéticas: medición en tiempo real de servicios (agua, energía, gas) y despliegues industriales.<br><br> - Casos: edificios inteligentes, minería, agricultura, piscicultura. | - Telemetría y telecontrol llave‑en‑mano.<br><br> - Redes LoRaWAN privadas y gateways.<br><br> - Medición en tiempo real y dashboards industriales.<br><br> - Integración con sistemas SCADA/ERP. | - Ventas B2B directas.<br><br> - Integradores de proyectos y contratos con empresas/municipios. | ![tecaperu](Imagenes/Tecape.PNG) |

### 2.1.1. Análisis competitivo
| Analisis Competitivo |
| ------------- |
| **Pregunta guía:** ¿Cómo se compara PowerSense en oferta, producto, mercado y potencial estratégico frente a Smelpro, LoraTech y Teca Perú, y qué acciones tácticas deben priorizarse para diferenciarse y crecer? |
| **Propósito del análisis:** Evaluar la posición de PowerSense frente a sus tres competidores clave del ecosistema IoT/energía (Smelpro, LoraTech y Teca Perú) para identificar ventajas competitivas, riesgos y tácticas prioritarias que permitan ganar cuota en hogares urbanos y PYMEs.

### 2.1.2. Estrategias y tácticas frente a competidores
| Categoría | Detalle | PowerSense (objetivo) | Smelpro | LoraTech | Teca Perú |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Perfil** | **Overview** | *Plataforma IoT + IA* orientada a hogares y PYMEs: kits plug‑and‑play por circuito, app móvil/panel web, analítica que traduce consumo a ahorro en S/; modelo freemium + suscripción. | *Proveedor de soluciones industriales* IoT/IA centrado en monitoreo, mantenimiento predictivo y optimización operativa en entornos críticos. | *Proveedor e integrador LoRaWAN* especializado en despliegues de red, sensores y gestión para sensorización masiva y baja potencia. | *Integrador local* de telemetría y telecontrol que entrega proyectos llave‑en‑mano, con experiencia en integración SCADA/ERP y contratos sectoriales. |
| **Perfil** | **Ventaja Competitiva** | Ahorro económico claro (S/), IA explicable que sugiere acciones prácticas y UX sencilla para usuarios no técnicos; rápida adopción mediante freemium. | Analítica avanzada y experiencia en entornos industriales críticos; soluciones robustas para uptime y eficiencia operativa. | Cobertura LoRaWAN, eficiencia en consumo energético de sensores y escalabilidad para despliegues masivos. | Entrega integral: hardware, instalación, integración y operación; conocimiento del mercado local y normativas. |
| **Perfil de marketing** | **Mercado objetivo** | Hogares urbanos (nivel medio‑alto) y pequeñas/medianas empresas (PYMEs) que buscan reducir su recibo eléctrico y mejorar eficiencia sin complejidad técnica. | Grandes industrias: minería, manufactura, plantas con requerimientos críticos. | Operadores de red, edificios inteligentes, agricultura, municipalidades y empresas que requieren sensorización masiva. | Empresas locales, municipalidades y proyectos sectoriales (energía, agua, minería) que requieren soluciones integradas. |
| **Perfil de marketing** | **Estrategias de marketing** | Marketing digital orientado a ahorro (casos en S/), pilotos locales, partnerships con instaladores y campañas de conversión freemium→pago. | Relaciones B2B, participación en ferias industriales, estudios de caso técnicos y ventas consultivas. | Alianzas con operadores LoRaWAN, demostraciones de cobertura y campañas sectoriales (agro, smart cities). | Licitaciones, relaciones comerciales locales, propuestas llave‑en‑mano y presencia en contratos públicos/privados. |
| **Perfil de producto** | **Productos o servicios** | Kits de medición por circuito (pinzas/medidores), gateway Wi‑Fi/LoRa, app móvil/panel web, analítica IA, reportes de ahorro y alertas. | Sensores industriales, gateways, plataforma analítica, mantenimiento predictivo y servicios de integración a sistemas de control. | Gateways LoRaWAN, nodos/sensores, gestión de red, integraciones y servicios gestionados para despliegues. | Sensores, gateways, integración SCADA/ERP, servicios de instalación, puesta en marcha y operación. |
| **Perfil de producto** | **Precios y costos** | Estimado: hardware S/200–S/600 por kit; suscripción S/9–S/49/mes según plan. Instalación opcional con cargo único. | Modelos de proyecto: contratos de alto valor (decenas de miles S/); soporte/servicios bajo contrato anual. | Venta de hardware + tarifas por gestión/servicio; precio variable según escala y cobertura. | Precios por proyecto (CAPEX) y contratos de servicio; altos montos según alcance e integración requerida. |
| **Perfil de producto** | **Canales de distribución** | E‑commerce para kits, app móvil y web para servicio; red de instaladores certificados y partnerships B2B. | Ventas B2B directas, integradores, licitaciones y servicios profesionales. | Partners/operadores LoRaWAN, integradores y distribuidores; portales B2B para gestión de red. | Ventas B2B, integradores locales, canales de licitación pública y contratos corporativos. |
| **Análisis SWOT** | **Fortalezas** | - Enfoque en usuario final y PYMEs<br>- IA explicable con métricas en S/<br>- Modelo freemium que facilita adopción rápida | - Analítica y capacidades probadas en entornos críticos<br>- Credibilidad en industria<br>- Soluciones robustas y escalables | - Experiencia y know‑how en LoRaWAN<br>- Bajo consumo y buena penetración para sensores<br>- Capacidad de despliegue masivo | - Capacidad de entrega integral (instalación + integración)<br>- Conocimiento del mercado local y normativas<br>- Relaciones con clientes públicos/privados |
| **Análisis SWOT** | **Debilidades** | - Marca nueva: menor confianza inicial<br>- Recursos limitados frente a incumbentes<br>- Dependencia inicial de partners para instalación/soporte | - Enfoque industrial puede limitar atractivo para consumidores residenciales<br>- Costos y complejidad altos | - Depende de cobertura y planificación de red<br>- No siempre óptimo para soluciones plug‑and‑play residenciales | - Ciclos de venta largos<br>- Dependencia en contratos/licitaciones que generan variabilidad |
| **Análisis SWOT** | **Oportunidades** | - Creciente preocupación por ahorro energético doméstico<br>- Alianzas con instaladores, municipalidades y utilities<br>- Pilotos que prueben ROI local en S/ | - Digitalización industrial y demanda de mantenimiento predictivo | - Expansión de redes LoRaWAN gestionadas y demanda de sensorización masiva | - Proyectos públicos/privados en modernización y telemetría regional |
| **Análisis SWOT** | **Amenazas** | - Entrada de ESCOs o utilities con ofertas financiadas<br>- Competidores con soluciones ya integradas en PYMEs<br>- Cambios regulatorios que afecten despliegues | - Competencia con soluciones más accesibles para PYMEs/residenciales<br>- Proveedores globales con mayor escala | - Proveedores que usan Wi‑Fi o redes celulares para mercados residenciales<br>- Competencia de integradores locales | - Presión de precio en licitaciones y entrada de integradores internacionales |

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

Para evaluar el atractivo y la practicidad de el servicio y producto PowerSense , estamos realizando entrevistas para entender a fondo lo que nuestros futuros usuarios necesitan, cómo se comportan y qué esperan.

### Diseño de entrevista – Primer segmento objetivo (Hogar):

1.- ¿En qué momentos del día suele usar más electricidad?

2.- ¿Qué dispositivos eléctricos son indispensables en su hogar y por qué?

3.- ¿Ha sentido que paga más luz de lo que debería? ¿Cómo lo percibe?

4.- ¿Suele comparar el monto de su recibo actual con el de meses anteriores? ¿Qué observa en esas comparaciones?

5.- ¿En su hogar suelen hablar o discutir sobre el gasto en electricidad?

6.- ¿Ha tenido que limitar el uso de algún aparato eléctrico por el costo de la electricidad?

7.- ¿Qué estrategias usa actualmente para intentar reducir el gasto en electricidad?

8.- ¿Cómo se informa (si es que lo hace) sobre su consumo eléctrico?

9.- ¿Qué impacto tiene el gasto en electricidad dentro del presupuesto familiar?

### Diseño de entrevista – Segundo segmento objetivo (Negocios):

1.- ¿Cuál es su nombre y cargo dentro de la empresa?

2.- ¿Cómo se llama su negocio y a qué rubro se dedica (ej. comercio, gastronomía, servicios, manufactura, etc.)?

3.- ¿En qué distrito o zona se encuentra ubicada su empresa?

4.- ¿Cuántos años tiene funcionando su negocio?

5.- ¿Cuál es el horario de funcionamiento habitual de su negocio?

6.- ¿En qué meses del año siente que gasta más electricidad? ¿Por qué cree que ocurre eso?

7.- ¿Qué equipos o procesos consumen más energía en su operación diaria?

8.- ¿Qué equipos, maquinarias o procesos son más indispensables para su negocio?

9.- ¿Qué equipos cree que consumen más energía?

10.- ¿Han tenido fallas en los equipos o servicios debido a picos de consumo eléctrico?

11.- ¿Qué estrategias o medidas ha probado para reducir el gasto en electricidad?

12.- ¿Cómo afecta el pago de la electricidad en su rentabilidad mensual o anual?

13.- ¿Considera que sus clientes valoran si su empresa adopta prácticas sostenibles?

14.- ¿Qué impacto tendría en su negocio poder optimizar los recursos energéticos sin sacrificar productividad?

### 2.2.2. Registro de entrevistas

### - Segmento objetivo 1 (Hogares)

Entrevista 1 (Cameron Bustamante) Inicio: 00:00 - Fin: 02:37 - Duración: 2:37

<p align="center">
  <img src="Imagenes/Imagen_entrevista1.png" alt="Imagen_entrevista1" />
</p>

- Nombre: Cameron Bustamente
- Edad: 22 años
- Distrito de residencia: Surco

Resumen de Entrevista : A partir de la entrevista realizada al usuario Cameron Bustamante, de 22 años y residente de Surco, se identificó que el entrevistado describe su rutina diaria y cómo ésta se refleja en el consumo eléctrico del hogar. Indica que por las mañanas utiliza la cocina y la terma y por las noches enciende la televisión y varios dispositivos electrónicos, generando picos marcados en esos horarios. 

Señala que la nevera permanece siempre encendida y constituye un consumo base, pero que la boleta ha aumentado con el tiempo sin una explicación aparente; comenta que no ha incorporado nuevos electrodomésticos ni cambiado hábitos de forma relevante. Manifiesta frustración por la falta de desagregación en la factura y por no poder identificar qué aparatos o qué franjas horarias generan los picos. Expone que sus medidas de ahorro son básicas (desenchufar equipos en desuso, duchas más cortas) y reconoce no conocer el impacto real de estas acciones en el monto final. 

Finaliza expresando interés en una solución que muestre consumo por toma y envíe alertas ante picos inusuales para recuperar control y tranquilidad.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQD1M3-yXB2OTZ-OuwVPXOu3AQUv_dqVOUphWuuBfHM-5VI?e=Cx8McB&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Entrevista 2 (Zuriel Rivera) Inicio: 00:00 - Fin: 7:25 - Duración: 7:25

<p align="center">
  <img src="Imagenes/Imagen_entrevista2.png" alt="Imagen_entrevista2" />
</p>

- Nombre: Zuriel Rivera
- Edad: 19 años
- Distrito de residencia: Surquillo

Resumen de la entrevista: En esta entrevista se le pregunto a Zuriel Andrea Rivera, una residente de Surquillo, que opiniones tenía con respecto al consumo eléctrico que había a nivel de hogar. 

Entre las preguntas que se le hizo, hubieron varias referentes al tipo de dispositivos que se utilizan, el momento del día donde se utilizan más aparatos eléctricos o el impacto económico que llega a tener para los habitantes de la vivienda llegando a señalar puntos como el uso de dispositivos eléctricos esenciales ya sea el microondas, el nodo del internet, la televisión, las diversas computadoras que hay en casa o el cargador de los celulares.

Sus respuestas confirmaron las hipotesis que planteabamos con respecto a ese tipo de problemática, por lo cual tomamos en consideración los diversos puntos que señalo para implementarlos en el producto final del proyecto.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQB3d49pgoprQZ0Sn74770w4AWW4A5ob_o-Wv5YtxuwFkYQ?e=Xv93lv&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Entrevista 3 (Sebastián Valdivia) Inicio: 00:00 - Fin: 3:29 - Duración: 3:29

<p align="center">
  <img src="Imagenes/Imagen_entrevista3.png" alt="Imagen_entrevista3" />
</p>

- Nombre: Sebastián Valdivia
- Edad: 22 años
- Distrito de residencia: Miraflores

Resumen de Entrevista : A partir de la entrevista realizada al usuario Sebastián Valdivia, de 22 años y residente de Miraflores, se identificó que percibe un consumo base constante por electrodomésticos esenciales y observa picos y variaciones mensuales en la factura que no logra vincular con cambios en su rutina. 

Reconoce falta de formación técnica para interpretar lecturas y conceptos presentes en la boleta, por lo que sus intentos de ahorro son a veces inconsistentes y sin métricas que confirmen impacto. Valora herramientas que permitan visualizar consumo por hora y por dispositivo para priorizar cambios y justificar medidas ante otros miembros del hogar.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQB8DGRcS7pTSL7zyiLRvDAUATbpHkaA6sEnYXPZbtYdEkE?e=h7xLDC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

### - Segmento objetivo 2 (Negocios)

Entrevista 4 (Juan Carlos Urdanivia Abad — Premium Cultural Institute) Inicio: 00:00 - Fin: 6:05 - Duración: 6:05

<p align="center">
  <img src="Imagenes/Imagen_entrevista4.png" alt="Imagen_entrevista4" />
</p>

- Nombre: Juan Carlos Urdanivia Abad
- Edad: 55 años
- Distrito de residencia: Surco
- Sector: Enseñanza

Resumen de Entrevista : A partir de la entrevista realizada al usuario Juan Carlos Urdanivia Abad, de 55 años y residente de Surco, se identificó que desde la perspectiva institucional los equipos de climatización y los sistemas audiovisuales generan picos significativos, especialmente durante actividades y temporadas altas. 

Indica que las vitrinas o equipos que requieren funcionamiento continuo representan la carga base más relevante y que la falta de datos en tiempo real impide identificar con precisión horarios o procesos causantes de incrementos en la factura. Manifiesta interés en monitoreo por circuito, reportes estacionales y en justificar inversiones en eficiencia ante la dirección, pero también subraya la necesidad de garantizar continuidad de servicio y comodidad en el espacio educativo.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQC3sjpSkR_DTKzs13MgK3ZqAcD0es7ciW1QUXSyC-iG4Pc?e=ZAcCKx&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Entrevista 5 (Franco Matías Tico Flores — Minimarket Paco) Inicio: 00:00 - Fin: 4:06 - Duración: 4:06

<p align="center">
  <img src="Imagenes/Imagen_entrevista5.png" alt="Imagen_entrevista5" />
</p>

- Nombre: Sebastián Valdivia
- Edad: 20 años
- Distrito de residencia: Surco
- Sector: Tienda de conveniencia.

Resumen de Entrevista : A partir de la entrevista realizada al usuario Franco Matías Tico Flores, de 20 años y residente de Surco, se identificó que el entrevistado, representante del minimarket, atribuye la mayor parte del consumo a equipos de refrigeración y señala picos en días de mayor afluencia.

Comenta que no cuentan con métricas en tiempo real para relacionar ventas y consumo y que les preocupa proteger inventario perecible. Muestra interés en soluciones con monitoreo continuo, alarmas por desviaciones y opciones de control remoto de cargas no críticas, aunque destaca la necesidad de que la inversión tenga un retorno claro.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQAe5XrMlNv1SapWPSqM0oqpAR5UO10KqfilPZY_GHG5uaY?e=kNgyTY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Entrevista 6 (Tomas Dextre Sanchez — Beeschurguer Hamburguesa) Inicio: 00:00 - Fin: 3:57 - Duración: 3:57

<p align="center">
  <img src="Imagenes/Imagen_entrevista6.png" alt="Imagen_entrevista6" />
</p>

- Nombre: Tomas Tobias Teodoro Dextre Sanchez
- Edad: 22 años
- Distrito de residencia: Surco
- Sector: Comida rapida

A partir de la entrevista realizada al usuario Tomas Tobias Teodoro Dextre Sanchez, de 22 años y residente de Surco, se identificó que el entrevistado, vinculado a un negocio de comida rápida, señala que la principal carga proviene de equipos de frío y de cocina y que existen picos en días de mayor demanda. Expresa que carecen de datos granulares y métricas en tiempo real para relacionar ventas, horarios y consumo, y que valorarían una solución con monitoreo continuo, alarmas tempranas y capacidad para gestionar cargas no críticas en momentos de tensión. Recalca que cualquier inversión debe estar alineada a un retorno razonable y que la protección del inventario es prioritaria.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQDXR1ZPu2jdS4y8N2hTc8zKAY0l99XSNW8-butaI8-eTzI?e=gfo46m&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

### 2.2.3. Análisis de entrevistas

### - Segmento objetivo 1 (Hogares):

Observamos que los entrevistados reportan incrementos periódicos en el gasto energético sin que se identifique una causa clara y verificable que explique dichas variaciones. Los datos que reciben, como la boleta y las lecturas del medidor, no son suficientemente detallados ni intuitivos para relacionarlos con el uso real de los equipos, lo que genera desconfianza y sensación de opacidad. Además, existe escasa formación en gestión energética: muchos participantes reconocen no tener conocimientos técnicos para interpretar consumos eléctricos ni para evaluar estrategias de ahorro más sofisticadas. Las medidas que aplican suelen ser reactivas y de bajo impacto.

Por ejemplo, desenchufar equipos o reducir tiempos de ducha y carecen de herramientas que permitan medir su efecto a mediano o largo plazo. En viviendas compartidas aparece un problema recurrente en la distribución del costo: la ausencia de mediciones por toma o por usuario provoca incertidumbre y conflictos al momento de repartir la boleta.

### - Segmento objetivo 2 (Negocios):

Los entrevistados reconocen que el consumo es elevado y que existen picos asociados a equipos concretos, como refrigeradores y aires acondicionados, pero coinciden en que no siempre es posible identificar con precisión qué operación o qué horario provoca los incrementos en la factura. La información disponible no facilita la toma de decisiones operativas porque falta métricas en tiempo real y reportes que permitan optimizar horarios y equipos.

Aunque hay interés en implementar medidas de eficiencia o generación propia, la principal barrera es el costo inicial y la necesidad de justificar retornos financieros claros, lo que impide muchas veces la adopción. La prioridad de estos negocios es garantizar la continuidad operativa: en rubros con equipos críticos (congeladores, vitrinas, equipos de ventilacion), la posibilidad de aplicar medidas agresivas de reducción de carga queda limitada por el riesgo de pérdidas, por lo que requieren soluciones que les permitan monitorear y proteger esos activos. Las prácticas actuales de gestión energética son en general manuales y poco automatizadas, lo que reduce la capacidad de respuesta eficiente ante variaciones de demanda.

## 2.3. Needfinding
### 2.3.1. User Personas

#### Segmento 1 (Hogares)

<p align="center">
  <img src="Imagenes/User1.png" alt="User1" />
</p>

#### Segmento 2 (Negocios)

<p align="center">
  <img src="Imagenes/User2.png" alt="User2" />
</p>

### 2.3.2. User Task Matrix

  **Segmento 1: Hogares** 
| Tarea principal                                                     | Frecuencia | Importancia |
|---------------------------------------------------------------------|------------|-------------|
| Instalar la app de PowerSense de forma rápida y segura y sin complicaciones     | Una vez    | Alta        |
| Abrir la app y ver el consumo energético en tiempo real      | Frecuente  | Alta        |
| Recibir alertas de picos/anomalías en el consumo energético y entender qué hacer             | Frecuente  | Alta        |
| Recibir alertas de sobrecalentamiento de dispositivos y entender qué hacer             | Frecuente  | Alta        |
| Control remoto de dispositivos para facilitar la activación o desactivación de estos | Frecuente |Media|

---

 **Segmento 2: PYME**

| Tarea principal                                                             | Frecuencia | Importancia |
|-----------------------------------------------------------------------------|------------|-------------|
| Desplegar PowerSense fuera de horario sin parar operación                   | Una vez    | Alta        |
| Monitorear circuitos/equipos críticos en tiempo real (en S/ por hora)       | Frecuente  | Alta        |
| Revisar reporte mensual sobre el consumo energético calculado para cada departamento (branch)                    | Frecuente  | Alta        |
| Control remoto de dispositivos dentro de un departamento completo de forma rápida             | Frecuente  | Media|

### 2.3.3. User Journey Mapping

#### Journey Map - Segmento 1 (Hogares):

<p align="center">
  <img src="Imagenes/Journey1.png" alt="Journey1" />
</p>

#### Journey Map - Segmento 2 (Negocios):

<p align="center">
  <img src="Imagenes/Journey2.png" alt="Journey2" />
</p>

### 2.3.4. Empathy Mapping

#### Empathy Mapping - Segmento 1 (Hogares)

<p align="center">
  <img src="Imagenes/Map1.png" alt="Map1" />
</p>

#### Empathy Mapping - Segmento 2 (Negocios)

<p align="center">
  <img src="Imagenes/Map2.png" alt="Map2" />
</p>

### 2.3.5. Big Picture EventStorming

En esta sección se detalla el desarrollo del Big Picture Event Storming, una técnica colaborativa orientada a explorar el dominio de nuestro negocio de manera integral. A través de este proceso identificamos los Domain Events más significativos y los organizamos cronológicamente para visualizar la linea de vida del sistema. Este enfoque no solo nos permitió mapear los flujos de la aplicación, sino también establecer un Lenguaje Ubicuo común entre el equipo y detectar tempranamente cuellos de botella u oportunidades de optimización en la gestión energética de hogares y MYPES.

![big picture event storming](Imagenes/bp-es/big-picture-event-storming.png)

### 2.3.6. Ubiquitous Language

Para esta sección se planteó un diccionario de términos técnicos que son aplicados en el dominio de nuestro proyecto.

| Término | Definición|  
|---|---|  
| **Consumo Energético(Energy Consumption)** | Consumo de energía calculado según los parametros de la potencia y el tiempo de uso.|
| **Usuario (User)** | Persona con una cuenta registrada en la app. Usada para la autenticación. |  
| **Campo de Especialidad (Branch)** | Área técnica en la que se especializa el trabajador (ej. RR. HH. o TI). |  
| **Dispositivo (Device)** | Dispositivo IoT conectado a la aplicación para su gestión y monitoreo.| 
| **Umbral (Treshold)** | Límite de consumo de energía que se tiene previsto según el sistema.| 
| **Programación (Schedule)** | Horarios predefinidos para la activación y desactivación remota y automática de los dispositivos| 
| **Reporte (Report)** | Informe que muestra un resumen del consumo energético mediante gráficos o descripciones numéricas.|
| **Alerta (Alert)** | Notificaciones de alerta cuando se excede el umbral de consumo energético o se detecta el sobrecalentamiento de un dispositivo.|

## 2.4. Requirements specification
### 2.4.1. User Stories

### Epic 1 – Landing Page
| #HU  | HU ID | Tipo Usuario    | Nombre HU               | Descripción                                                                                                                                                   | Criterios de Aceptación    |
|------|-------|-----------------|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| HU1 | HU1  | Visitante Hogar | Información general del producto | Como visitante interesado en reducir el consumo energético en mi hogar, quiero acceder a información clara sobre la plataforma de optimización energética para entender cómo me beneficia y cómo puede ayudarme a ahorrar en mis facturas. | **Scenario 1: Acceso a información pública**<br>Dado que el visitante ingresa a la página web de la plataforma de optimización energética<br>Cuando selecciona la sección “Información del producto”<br>Entonces el sistema muestra una descripción general de la plataforma, sus objetivos (ahorro de energía y optimización de consumo) y los beneficios principales como monitoreo en tiempo real y dispositivos inteligentes.<br><br>**Scenario 2: Visualización de funcionalidades**<br>Dado que el visitante se encuentra en la sección “Información del producto”<br>Cuando navega por la interfaz<br>Entonces el sistema presenta de manera clara las funcionalidades, como el monitoreo de consumo, los reportes de energía y las alertas para optimizar el uso de energía en el hogar.<br><br>**Scenario 3: Recomendaciones para ahorrar energía**<br>Dado que el visitante revisa la información sobre el producto<br>Cuando llega a la sección de consejos o recomendaciones de ahorro energético<br>Entonces el sistema muestra sugerencias simples, como la optimización del uso de dispositivos y consejos para reducir el consumo sin necesidad de personalización.<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante explora la información general<br>Cuando visualiza botones o enlaces destacados como “Ver cómo funciona” o “Ver planes”<br>Entonces el sistema muestra opciones para registrarse, iniciar sesión o solicitar más información sobre los planes y servicios de optimización energética. |
| HU2 | HU2  | Visitante Hogar | Casos de éxito            | Como visitante, quiero consultar casos de éxito reales sobre ahorro energético en hogares para confiar en la efectividad de la solución antes de registrarme. | **Scenario 1: Acceso público**<br>Dado que el visitante ingresa a la plataforma sin necesidad de estar registrado<br>Cuando selecciona la sección “Casos de éxito”<br>Entonces el sistema muestra una lista de testimonios e implementaciones exitosas en hogares.<br><br>**Scenario 2: Visualización detallada**<br>Dado que el visitante se encuentra en la lista de casos de éxito<br>Cuando selecciona un caso específico<br>Entonces el sistema muestra información detallada sobre el consumo energético antes y después de utilizar la plataforma, así como los resultados obtenidos, como reducción de costos y optimización de consumo.<br><br>**Scenario 3: Filtrado por tipo de usuario**<br>Dado que el visitante accede a la sección de casos de éxito<br>Cuando utiliza el filtro “Hogar”<br>Entonces el sistema muestra únicamente los casos correspondientes a usuarios de tipo hogar.<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante ha revisado uno o más casos de éxito<br>Cuando llega al final de la página<br>Entonces el sistema muestra un botón destacado para registrarse o solicitar más información sobre la plataforma. |
| HU3 | HU3  | Visitante Hogar | Planes y precios           | Como visitante interesado en optimizar el consumo energético de mi hogar, quiero visualizar los planes y precios para elegir la opción que se ajuste a mis necesidades. | **Scenario 1: Acceso a la sección de planes**<br>Dado que el visitante se encuentra en la página principal<br>Cuando selecciona la opción “Planes y precios” en el menú de navegación<br>Entonces el sistema muestra una tabla comparativa con los diferentes planes disponibles: Básico (Gratis), Pro ($29/mes), y Empresarial ($79/mes).<br><br>**Scenario 2: Visualización de características**<br>Dado que el visitante accede a la tabla de planes<br>Cuando revisa la comparativa<br>Entonces el sistema muestra de manera clara las características de cada plan, como el monitoreo básico de consumo, análisis avanzado de consumo, y soporte prioritario.<br><br>**Scenario 3: Plan destacado**<br>Dado que la plataforma ofrece un plan recomendado<br>Cuando el visitante observa la comparativa<br>Entonces el sistema resalta visualmente el plan más popular o recomendado (Ejemplo: con un borde o etiqueta “Más Popular”).<br><br>**Scenario 4: Selección de plan**<br>Dado que el visitante identifica un plan de su interés<br>Cuando hace clic en el botón “Seleccionar” o “Más información” dentro de dicho plan<br>Entonces el sistema redirige al formulario de registro, demo gratuita o pago según corresponda.<br><br>**Scenario 5: Responsividad**<br>Dado que el visitante accede desde distintos dispositivos (PC, tablet o móvil)<br>Cuando visualiza la tabla comparativa<br>Entonces el sistema adapta el diseño para que la información sea clara y fácil de leer en cualquier dispositivo. |
| HU4 | HU4  | Visitante Hogar | Cómo Funciona               | Como visitante interesado en optimizar el consumo energético en mi hogar, quiero entender cómo funciona la plataforma para asegurarme de que es una solución efectiva para reducir mis costos de energía. | **Scenario 1: Acceso a la sección “Cómo funciona”**<br>Dado que el visitante ingresa a la página web<br>Cuando selecciona la opción “Cómo funciona” en el menú de navegación<br>Entonces el sistema muestra un desglose claro de cómo funciona la plataforma, incluyendo el monitoreo de consumo en tiempo real, los dispositivos inteligentes integrados y el análisis avanzado de consumo.<br><br>**Scenario 2: Explicación de las funcionalidades**<br>Dado que el visitante está en la sección “Cómo funciona”<br>Cuando lee la información presentada<br>Entonces el sistema describe paso a paso el proceso: creación de perfil, conexión de dispositivos inteligentes, monitoreo en tiempo real y generación de reportes de consumo energético.<br><br>**Scenario 3: Visualización de resultados**<br>Dado que el visitante ha revisado la explicación del proceso<br>Cuando navega por la interfaz<br>Entonces el sistema muestra ejemplos visuales de los reportes generados, alertas de consumo elevado y recomendaciones de optimización.<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante entiende cómo funciona el sistema<br>Cuando visualiza botones de acción como “Ver planes” o “Comienza ahora”<br>Entonces el sistema ofrece opciones para registrarse, iniciar sesión o solicitar más información sobre cómo empezar a utilizar la plataforma. |
| HU5 | HU5  | Visitante Hogar | Contacto                   | Como visitante, quiero poder acceder a un formulario de contacto para obtener más información o realizar preguntas sobre la plataforma de optimización energética. | **Scenario 1: Acceso al formulario de contacto**<br>Dado que el visitante se encuentra en la página principal<br>Cuando selecciona la opción “Contacto” en el menú de navegación<br>Entonces el sistema muestra un formulario con los campos: nombre, correo electrónico, mensaje y un botón para enviar.<br><br>**Scenario 2: Validación de campos obligatorios**<br>Dado que el visitante está en el formulario de contacto<br>Cuando intenta enviarlo sin completar los campos obligatorios (nombre y correo electrónico)<br>Entonces el sistema muestra un mensaje de error indicando los campos que deben completarse.<br><br>**Scenario 3: Envío exitoso del formulario**<br>Dado que el visitante ha completado correctamente el formulario<br>Cuando hace clic en el botón “Enviar”<br>Entonces el sistema muestra un mensaje de confirmación que indica “Tu solicitud fue enviada con éxito, pronto nos pondremos en contacto contigo”.<br><br>**Scenario 4: Notificación interna**<br>Dado que un visitante ha completado y enviado el formulario de contacto<br>Cuando el sistema procesa la solicitud<br>Entonces la plataforma envía una notificación interna al equipo de soporte o ventas con los datos registrados para dar seguimiento.<br><br>**Scenario 5: Redirección a la página principal**<br>Dado que el visitante ha enviado el formulario de contacto<br>Cuando se muestra el mensaje de confirmación<br>Entonces el sistema ofrece la opción de volver a la página principal o a la sección de "Planes" para explorar más sobre la plataforma. |
| HU6 | HU6  | Visitante Hogar | Sobre Nosotros     | Como visitante, quiero saber más sobre el equipo detrás de la plataforma y sobre el producto para comprender mejor la misión, visión y las ventajas que ofrece la solución. | **Scenario 1: Acceso a la sección "Sobre Nosotros"**<br>Dado que el visitante ingresa a la página web<br>Cuando selecciona la opción “Sobre Nosotros” en el menú de navegación<br>Entonces el sistema muestra una introducción sobre la plataforma, su misión, visión y objetivos.<br><br>**Scenario 2: Información sobre el equipo**<br>Dado que el visitante está en la sección "Sobre Nosotros"<br>Cuando selecciona el apartado “Nuestro equipo”<br>Entonces el sistema muestra una breve descripción de los miembros clave del equipo, sus roles y experiencia.<br><br>**Scenario 3: Información sobre el producto**<br>Dado que el visitante está en la sección "Sobre Nosotros"<br>Cuando selecciona el apartado “Sobre el producto”<br>Entonces el sistema proporciona detalles sobre las características, beneficios y diferenciadores del producto (optimización energética, reducción de costos, monitoreo inteligente, etc.).<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante ha revisado la información sobre el equipo y el producto<br>Cuando llega al final de la sección<br>Entonces el sistema muestra opciones para registrarse, obtener más información o navegar a las secciones de "Planes" y "Cómo Funciona". |

---

### Epic 2 – Gestión de Usuarios
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU7 | HU7 | Hogar | Registro de cuenta | Como usuario de hogar, quiero registrarme en la plataforma para comenzar a gestionar mi consumo energético. | **Scenario 1: Registro exitoso**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha completado los campos obligatorios (nombre, correo electrónico válido y contraseña que cumple con los requisitos)<br>Cuando el visitante hace clic en el botón “Registrar”<br>Entonces el sistema crea la nueva cuenta en la base de datos<br>Y redirige al visitante a la página de inicio de sesión mostrando el mensaje “Registro exitoso, por favor inicie sesión”.<br><br>**Scenario 2: Correo electrónico ya registrado**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha completado los campos con un correo electrónico ya existente en la base de datos<br>Cuando el visitante hace clic en el botón “Registrar”<br>Entonces el sistema muestra un mensaje de error: “El correo ya está registrado, por favor intente con otro o inicie sesión”.<br><br>**Scenario 3: Contraseña no cumple requisitos**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha ingresado una contraseña con menos de 8 caracteres o sin los requisitos mínimos<br>Cuando intenta hacer clic en el botón “Registrar”<br>Entonces el sistema muestra el mensaje de validación: “La contraseña debe tener al menos 8 caracteres, incluir mayúsculas, minúsculas y un número”.<br><br>**Scenario 4: Campos obligatorios vacíos**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha dejado uno o más campos obligatorios en blanco<br>Cuando intenta hacer clic en el botón “Registrar”<br>Entonces el sistema resalta los campos vacíos en rojo<br>Y muestra el mensaje: “Complete todos los campos obligatorios para continuar”.<br><br>**Scenario 5: Error técnico inesperado**<br>Dado que el visitante ha completado todos los campos de forma válida<br>Y el sistema presenta un fallo en la comunicación con el servidor<br>Cuando el visitante hace clic en “Registrar”<br>Entonces el sistema muestra un mensaje de error: “Ha ocurrido un problema, por favor intente más tarde”<br>Y registra el error en los logs del backend. |
| HU8 | HU8 | PYME | Registro empresarial | Como administrador de PYME, quiero registrar mi empresa en la plataforma para gestionar el consumo energético de mis instalaciones. | **Scenario 1: Registro exitoso de empresa**<br>Dado que el administrador se encuentra en la página de “Registro empresarial”<br>Y ha completado los campos obligatorios (nombre de la empresa, RUC/NIF, correo corporativo y contraseña válida)<br>Cuando hace clic en el botón “Registrar empresa”<br>Entonces el sistema crea el perfil de la empresa en la base de datos<br>Y muestra el mensaje: “Registro exitoso, por favor inicie sesión con su cuenta empresarial”.<br><br>**Scenario 2: RUC/NIF ya registrado**<br>Dado que el administrador se encuentra en la página de “Registro empresarial”<br>Y ha ingresado un RUC/NIF que ya existe en la base de datos<br>Cuando hace clic en el botón “Registrar empresa”<br>Entonces el sistema muestra un mensaje de error: “El número de RUC/NIF ya está registrado, intente con otro o recupere acceso”.<br><br>**Scenario 3: Correo corporativo ya registrado**<br>Dado que el administrador completa el formulario de registro empresarial<br>Y ingresa un correo corporativo que ya está en uso en otra cuenta<br>Cuando intenta registrarse<br>Entonces el sistema muestra un mensaje de error: “El correo corporativo ya está vinculado a otra empresa”.<br><br>**Scenario 4: Contraseña no cumple requisitos**<br>Dado que el administrador ingresa una contraseña de menos de 8 caracteres o sin mayúsculas/números<br>Cuando hace clic en el botón “Registrar empresa”<br>Entonces el sistema muestra el mensaje: “La contraseña debe tener al menos 8 caracteres, incluir mayúsculas, minúsculas y un número”.<br><br>**Scenario 5: Campos obligatorios vacíos**<br>Dado que el administrador ha dejado uno o más campos obligatorios sin llenar<br>Cuando intenta registrarse<br>Entonces el sistema resalta los campos vacíos en rojo<br>Y muestra el mensaje: “Complete todos los campos obligatorios para continuar”.<br><br>**Scenario 6: Error técnico inesperado**<br>Dado que el administrador ha completado todos los campos correctamente<br>Y ocurre un error en la comunicación con el servidor<br>Cuando hace clic en “Registrar empresa”<br>Entonces el sistema muestra el mensaje: “Ha ocurrido un problema, por favor intente más tarde”<br>Y el error se guarda en los logs del backend. |
| HU9 | HU9 | Hogar | Inicio de sesión | Como usuario de hogar, quiero iniciar sesión de forma segura para acceder a mis datos de consumo. | **Scenario 1: Usuario inicia sesión correctamente**<br>Dado que el usuario está registrado en la plataforma<br>Y el usuario se encuentra en la pantalla de inicio de sesión<br>Cuando el usuario introduce su correo electrónico y contraseña correctos<br>Entonces el sistema autentica las credenciales<br>Y muestra el panel principal con los datos de consumo del usuario.<br><br>**Scenario 2: Usuario ingresa credenciales inválidas**<br>Dado que el usuario está en la pantalla de inicio de sesión<br>Cuando el usuario introduce un correo electrónico y/o contraseña incorrectos<br>Entonces el sistema rechaza la autenticación<br>Y muestra el mensaje: “Credenciales inválidas, verifique sus datos”.<br><br>**Scenario 3: Cierre automático de sesión por seguridad**<br>Dado que el usuario ha iniciado sesión en la plataforma<br>Cuando el usuario cierra el navegador o permanece inactivo por más de 10 minutos<br>Entonces el sistema cierra la sesión automáticamente<br>Y redirige al usuario nuevamente a la pantalla de inicio de sesión.<br><br>**Scenario 4: Usuario usa la opción “Recordar sesión”**<br>Dado que el usuario está en la pantalla de inicio de sesión<br>Y marca la casilla “Recordarme”<br>Cuando introduce credenciales correctas<br>Entonces el sistema autentica al usuario<br>Y mantiene la sesión activa en ese dispositivo hasta que el usuario cierre sesión manualmente. |
| HU10 | HU10 | PYME | Inicio de sesión corporativo | Como administrador de PYME, quiero iniciar sesión corporativa para acceder a las métricas de mi organización. | **Scenario 1: Inicio de sesión exitoso**<br>Dado que el administrador de PYME está registrado en la plataforma<br>Y el administrador se encuentra en la pantalla de inicio de sesión corporativa<br>Cuando introduce su correo corporativo y contraseña correctos<br>Entonces el sistema autentica las credenciales<br>Y muestra el panel principal con las métricas y consumo energético de la empresa.<br><br>**Scenario 2: Credenciales incorrectas**<br>Dado que el administrador de PYME está en la pantalla de inicio de sesión corporativa<br>Cuando introduce un correo corporativo y/o contraseña incorrectos<br>Entonces el sistema rechaza la autenticación<br>Y muestra el mensaje: “Credenciales inválidas, verifique sus datos”.<br><br>**Scenario 3: Cierre automático de sesión por inactividad**<br>Dado que el administrador de PYME ha iniciado sesión<br>Cuando permanece inactivo por más de X minutos o cierra el navegador<br>Entonces el sistema cierra la sesión automáticamente<br>Y redirige al administrador nuevamente a la pantalla de inicio de sesión corporativa.<br><br>**Scenario 4: Uso de opción “Recordar sesión”**<br>Dado que el administrador de PYME se encuentra en la pantalla de inicio de sesión corporativa<br>Y marca la casilla “Recordarme”<br>Cuando introduce credenciales correctas<br>Entonces el sistema autentica al administrador<br>Y mantiene la sesión activa en ese dispositivo hasta que el administrador cierre sesión manualmente. |
| HU11 | HU11 | PYME | Gestión de múltiples usuarios | Como administrador de PYME, quiero dar acceso a distintos roles (empleados, supervisores) para distribuir responsabilidades. | **Scenario 1: Agregar un nuevo usuario con rol específico**<br>Dado que el administrador de PYME ha iniciado sesión correctamente<br>Y se encuentra en la sección de gestión de usuarios<br>Cuando el administrador ingresa los datos del nuevo usuario y asigna un rol (empleado o supervisor)<br>Entonces el sistema crea el usuario en la base de datos<br>Y asigna el rol correspondiente<br>Y muestra un mensaje de confirmación: “Usuario agregado exitosamente”.<br><br>**Scenario 2: Intento de agregar usuario con correo existente**<br>Dado que el administrador intenta registrar un usuario con un correo electrónico ya registrado<br>Cuando hace clic en “Agregar usuario”<br>Entonces el sistema muestra un mensaje de error: “El correo electrónico ya está en uso, utilice otro”.<br><br>**Scenario 3: Modificar rol de un usuario existente**<br>Dado que el administrador está en la sección de gestión de usuarios<br>Y el usuario ya existe en la lista<br>Cuando el administrador cambia el rol del usuario y guarda los cambios<br>Entonces el sistema actualiza el rol del usuario en la base de datos<br>Y muestra un mensaje de confirmación: “Rol actualizado exitosamente”.<br><br>**Scenario 4: Eliminación de un usuario**<br>Dado que el administrador se encuentra en la lista de usuarios<br>Y selecciona un usuario para eliminar<br>Cuando confirma la acción de eliminación<br>Entonces el sistema elimina al usuario de la base de datos<br>Y muestra un mensaje: “Usuario eliminado correctamente”.<br><br>**Scenario 5: Error técnico al gestionar usuarios**<br>Dado que el administrador intenta agregar, modificar o eliminar un usuario<br>Cuando ocurre un fallo en la comunicación con el servidor<br>Entonces el sistema muestra el mensaje: “Ha ocurrido un error, por favor intente más tarde”<br>Y registra el error en los logs del backend. |
| HU12 | HU12 | Hogar | Personalización de perfil | Como usuario de hogar, quiero personalizar mi perfil con mis hábitos para recibir recomendaciones más relevantes. | **Scenario 1: Actualización exitosa de perfil**<br>Dado que el usuario de hogar ha iniciado sesión correctamente<br>Y se encuentra en la sección de “Perfil”<br>Cuando el usuario ingresa sus hábitos de consumo (horarios, dispositivos frecuentes, preferencias)<br>Y hace clic en “Guardar cambios”<br>Entonces el sistema actualiza la información en la base de datos<br>Y muestra un mensaje de confirmación: “Perfil actualizado correctamente”.<br><br>**Scenario 2: Campos obligatorios incompletos**<br>Dado que el usuario está en la sección de “Perfil”<br>Cuando deja uno o más campos obligatorios vacíos y hace clic en “Guardar cambios”<br>Entonces el sistema resalta los campos vacíos<br>Y muestra el mensaje: “Complete todos los campos obligatorios para actualizar su perfil”.<br><br>**Scenario 3: Datos inválidos**<br>Dado que el usuario introduce información en un formato incorrecto (por ejemplo, texto en un campo numérico)<br>Cuando hace clic en “Guardar cambios”<br>Entonces el sistema muestra un mensaje de validación: “Ingrese datos válidos en todos los campos”.<br><br>**Scenario 4: Error técnico al actualizar perfil**<br>Dado que el usuario ha completado todos los campos correctamente<br>Cuando ocurre un fallo en la comunicación con el servidor al guardar los cambios<br>Entonces el sistema muestra el mensaje: “Ha ocurrido un error, por favor intente más tarde”<br>Y registra el error en los logs del backend.<br><br>**Scenario 5: Visualización de perfil actualizado**<br>Dado que el usuario ha guardado cambios exitosamente<br>Cuando vuelve a acceder a la sección de “Perfil”<br>Entonces el sistema muestra la información actualizada correctamente en todos los campos. |

---

### Epic 3 – Monitoreo y Control Energético
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU13 | HU13 | Hogar | Dashboard en tiempo real | Como usuario de hogar, quiero visualizar el consumo energético en un dashboard para monitorear mi gasto en tiempo real. | **Scenario 1: Visualización del consumo en tiempo real**<br>Dado que el usuario ha iniciado sesión correctamente<br>Cuando abre la sección “Dashboard”<br>Entonces el sistema muestra el consumo energético actual en tiempo real<br>Y el sistema actualiza los datos cada minuto sin necesidad de recargar la página<br><br>**Scenario 2: Visualización de gráficos de consumo por dispositivo**<br>Dado que el usuario tiene varios dispositivos registrados<br>Cuando abre la sección “Dashboard”<br>Entonces el sistema muestra un gráfico por cada dispositivo mostrando su consumo actual<br>Y cada gráfico incluye etiquetas con nombre de dispositivo y valor de consumo<br><br>**Scenario 3: Indicadores de consumo total y comparativa diaria**<br>Dado que el usuario accede al dashboard<br>Cuando visualiza la información general<br>Entonces el sistema muestra el consumo total del hogar hasta el momento<br>Y compara el consumo con el promedio diario del usuario mostrando una alerta si supera el promedio |
| HU14 | HU14 | PYME | Dashboard empresarial | Como administrador de PYME, quiero ver un panel de consumo por áreas/departamentos para identificar ineficiencias. | **Scenario 1: Visualización del consumo por área**<br>Dado que el administrador ha iniciado sesión correctamente<br>Cuando abre la sección “Dashboard Empresarial”<br>Entonces el sistema muestra el consumo energético total de cada área/departamento<br>Y cada área incluye un gráfico indicando su consumo en tiempo real<br><br>**Scenario 2: Identificación de áreas con consumo elevado**<br>Dado que el sistema tiene datos históricos de consumo<br>Cuando se visualiza el dashboard<br>Entonces las áreas que superen los umbrales definidos se resaltan en rojo<br>Y se muestra una alerta indicando posibles ineficiencias<br><br>**Scenario 3: Comparativa entre áreas/departamentos**<br>Dado que existen múltiples áreas registradas<br>Cuando el administrador selecciona la opción “Comparativa de áreas”<br>Entonces el sistema genera un gráfico comparativo mostrando el consumo de todas las áreas<br>Y se indican porcentajes de consumo relativo entre cada departamento<br><br>**Scenario 4: Actualización automática de datos**<br>Dado que el administrador mantiene abierto el dashboard<br>Cuando pasan nuevos registros de consumo<br>Entonces el sistema actualiza automáticamente los gráficos y valores sin necesidad de recargar la página |
| HU15 | HU15 | Hogar | Control remoto de dispositivos | Como usuario de hogar, quiero encender/apagar mis dispositivos desde la app para ahorrar energía. | **Scenario 1: Encender un dispositivo desde la app**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos registrados en su hogar<br>Cuando selecciona un dispositivo y pulsa “Encender”<br>Entonces el sistema envía la señal al dispositivo<br>Y el dispositivo se enciende, actualizando su estado en la app a “Encendido”<br><br>**Scenario 2: Apagar un dispositivo desde la app**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos encendidos<br>Cuando selecciona un dispositivo y pulsa “Apagar”<br>Entonces el sistema envía la señal al dispositivo<br>Y el dispositivo se apaga, actualizando su estado en la app a “Apagado”<br><br>**Scenario 3: Visualización del estado de todos los dispositivos**<br>Dado que el usuario abre la sección “Mis dispositivos”<br>Cuando la app carga los datos<br>Entonces se muestran todos los dispositivos con su estado actual (Encendido / Apagado)<br>Y el usuario puede identificar rápidamente cuáles están activos y cuáles apagados<br><br>**Scenario 4: Notificación de fallo de control**<br>Dado que un dispositivo no responde a la señal de encendido/apagado<br>Cuando el usuario intenta controlarlo desde la app<br>Entonces el sistema muestra un mensaje de error indicando “No se pudo controlar el dispositivo. Intente nuevamente.” |
| HU16 | HU16 | PYME | Control remoto empresarial | Como administrador de PYME, quiero gestionar remotamente dispositivos de mi oficina para reducir gastos energéticos. | **Scenario 1: Encender dispositivos por área/departamento**<br>Dado que el administrador ha iniciado sesión correctamente<br>Y tiene áreas/departamentos con dispositivos registrados<br>Cuando selecciona un área y pulsa “Encender todos”<br>Entonces el sistema envía la señal a todos los dispositivos del área<br>Y cada dispositivo se enciende mostrando su estado actualizado en el dashboard<br><br>**Scenario 2: Apagar dispositivos por área/departamento**<br>Dado que el administrador ha iniciado sesión correctamente<br>Y algunos dispositivos están encendidos<br>Cuando selecciona un área y pulsa “Apagar todos”<br>Entonces el sistema envía la señal a todos los dispositivos del área<br>Y cada dispositivo se apaga mostrando su estado actualizado en el dashboard<br><br>**Scenario 3: Visualización del estado de los dispositivos corporativos**<br>Dado que el administrador abre la sección “Gestión de dispositivos”<br>Cuando la app carga los datos<br>Entonces se muestran todos los dispositivos con su estado actual (Encendido / Apagado)<br>Y se pueden filtrar por área, departamento o tipo de dispositivo<br><br>**Scenario 4: Notificación de fallo en dispositivos**<br>Dado que algún dispositivo no responde a la señal de control<br>Cuando el administrador intenta encender/apagar desde la app<br>Entonces el sistema muestra un mensaje de error indicando “No se pudo controlar el dispositivo. Verifique la conexión.” |
| HU17 | HU17 | Hogar | Programar horarios | Como usuario de hogar, quiero programar horarios de encendido/apagado de mis electrodomésticos para optimizar el consumo. | **Scenario 1: Programar un horario de encendido**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos registrados<br>Cuando selecciona un dispositivo y establece un horario de encendido<br>Entonces el sistema guarda la programación<br>Y el dispositivo se enciende automáticamente a la hora establecida<br><br>**Scenario 2: Programar un horario de apagado**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos encendidos<br>Cuando selecciona un dispositivo y establece un horario de apagado<br>Entonces el sistema guarda la programación<br>Y el dispositivo se apaga automáticamente a la hora establecida<br><br>**Scenario 3: Visualizar horarios programados**<br>Dado que el usuario abre la sección “Programaciones”<br>Cuando la app carga los datos<br>Entonces se muestran todos los horarios activos por dispositivo<br>Y se puede editar o eliminar cada programación<br><br>**Scenario 4: Notificación de conflicto de horarios**<br>Dado que el usuario intenta establecer un horario que entra en conflicto con otra programación<br>Cuando guarda el nuevo horario<br>Entonces el sistema muestra un mensaje de advertencia indicando “Conflicto de programación. Ajuste la hora para continuar.” |
| HU18 | HU18 | PYME | Programación grupal | Como administrador de PYME, quiero establecer horarios automáticos de apagado en áreas comunes para evitar consumos innecesarios. | **Scenario 1: Establecer horario de apagado por área**<br>Dado que el administrador ha iniciado sesión correctamente<br>Y existen áreas comunes con dispositivos registrados<br>Cuando selecciona un área y configura un horario de apagado automático<br>Entonces el sistema guarda la programación<br>Y todos los dispositivos del área se apagan automáticamente a la hora establecida<br><br>**Scenario 2: Visualizar horarios programados por área**<br>Dado que el administrador abre la sección “Programaciones corporativas”<br>Cuando la app carga los datos<br>Entonces se muestran todos los horarios activos por área<br>Y se puede editar o eliminar cada programación según sea necesario<br><br>**Scenario 3: Notificación de conflicto de horarios**<br>Dado que el administrador intenta establecer un horario que entra en conflicto con otra programación existente<br>Cuando guarda la nueva programación<br>Entonces el sistema muestra un mensaje de advertencia indicando “Conflicto de programación. Ajuste la hora para continuar.”<br><br>**Scenario 4: Confirmación de ejecución**<br>Dado que la hora programada de apagado ha llegado<br>Cuando los dispositivos se apagan automáticamente<br>Entonces el sistema actualiza el dashboard mostrando el estado “Apagado”<br>Y envía una notificación al administrador confirmando la ejecución del horario |
| HU19 | HU19 | Hogar | Gestión de dispositivos | Como usuario de hogar, quiero registrar y administrar mis dispositivos conectados para organizarlos en la app. | **Scenario 1: Registrar un nuevo dispositivo**<br>Dado que el usuario ha iniciado sesión correctamente<br>Cuando selecciona la opción “Agregar dispositivo”<br>Y completa los datos requeridos (nombre, tipo, ubicación)<br>Entonces el sistema guarda el dispositivo en su perfil<br>Y el dispositivo aparece listado en la sección “Mis dispositivos”<br><br>**Scenario 2: Editar información de un dispositivo registrado**<br>Dado que el usuario tiene dispositivos registrados<br>Cuando selecciona un dispositivo y elige la opción “Editar”<br>Y modifica los datos (nombre, tipo, ubicación)<br>Entonces el sistema actualiza la información<br>Y los cambios se reflejan inmediatamente en la lista de dispositivos<br><br>**Scenario 3: Eliminar un dispositivo registrado**<br>Dado que el usuario tiene dispositivos registrados<br>Cuando selecciona un dispositivo y pulsa “Eliminar”<br>Entonces el sistema solicita confirmación de eliminación<br>Y al confirmar, el dispositivo se elimina de la lista y del perfil del usuario<br><br>**Scenario 4: Visualizar dispositivos organizados por ubicación o tipo**<br>Dado que el usuario abre la sección “Mis dispositivos”<br>Cuando el sistema carga los datos<br>Entonces los dispositivos se muestran organizados por ubicación o tipo<br>Y el usuario puede filtrar o buscar dispositivos fácilmente |
| HU20 | HU20 | PYME | Gestión masiva de dispositivos | Como administrador de PYME, quiero dar de alta y controlar múltiples dispositivos de manera centralizada para optimizar su uso. | **Scenario 1: Dar de alta múltiples dispositivos**<br>Dado que el administrador ha iniciado sesión correctamente<br>Cuando selecciona la opción “Agregar dispositivos masivamente”<br>Y carga un archivo con la información de varios dispositivos (nombre, tipo, ubicación)<br>Entonces el sistema registra todos los dispositivos correctamente<br>Y los dispositivos aparecen listados en la sección “Gestión de dispositivos”<br><br>**Scenario 2: Controlar dispositivos de manera centralizada**<br>Dado que el administrador tiene múltiples dispositivos registrados<br>Cuando selecciona un grupo de dispositivos y elige “Encender” o “Apagar”<br>Entonces el sistema envía la señal a todos los dispositivos seleccionados<br>Y actualiza su estado en el dashboard mostrando “Encendido” o “Apagado”<br><br>**Scenario 3: Editar información de dispositivos masivos**<br>Dado que el administrador desea actualizar información de varios dispositivos<br>Cuando selecciona un grupo de dispositivos y aplica cambios (ubicación, tipo, área)<br>Entonces el sistema actualiza la información de todos los dispositivos seleccionados<br>Y los cambios se reflejan inmediatamente en la lista<br><br>**Scenario 4: Eliminación masiva de dispositivos**<br>Dado que el administrador desea eliminar varios dispositivos<br>Cuando selecciona un grupo de dispositivos y pulsa “Eliminar”<br>Entonces el sistema solicita confirmación<br>Y al confirmar, todos los dispositivos seleccionados se eliminan de manera centralizada |

---

### Epic 4 – Reportes y Alertas
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU21 | HU21 | Hogar | Reporte diario | Como usuario de hogar, quiero recibir un reporte diario de mi consumo para tener visibilidad de mis hábitos. | **Scenario 1: Generación automática del reporte diario**<br>Dado que el usuario tiene dispositivos registrados en la plataforma<br>Cuando el sistema procesa la información de consumo al final del día<br>Entonces genera un reporte con el detalle del consumo energético diario<br>Y el reporte queda disponible en la sección “Historial de consumo” de la app<br><br>**Scenario 2: Envío de reporte por notificación**<br>Dado que el usuario tiene configuradas notificaciones en la aplicación<br>Cuando el reporte diario es generado<br>Entonces el sistema envía una notificación push al dispositivo móvil<br>Y al abrir la notificación, el usuario accede directamente al reporte<br><br>**Scenario 3: Contenido del reporte**<br>Dado que el usuario consulta su reporte diario<br>Cuando el reporte es mostrado en la app<br>Entonces el sistema presenta los datos de consumo total en kWh, costo estimado y dispositivos de mayor consumo<br>Y muestra comparaciones con el día anterior para identificar variaciones<br><br>**Scenario 4: Acceso a reportes pasados**<br>Dado que el usuario quiere revisar reportes de días anteriores<br>Cuando selecciona una fecha en el calendario dentro de “Historial de consumo”<br>Entonces el sistema muestra el reporte correspondiente a ese día con el mismo formato |
| HU22 | HU22 | PYME | Reporte semanal corporativo | Como administrador de PYME, quiero recibir reportes semanales consolidados para analizar patrones de consumo en mi empresa. | **Scenario 1: Generación automática del reporte semanal**<br>Dado que el administrador tiene múltiples dispositivos registrados en la plataforma<br>Cuando el sistema procesa la información de consumo al finalizar la semana<br>Entonces genera un reporte consolidado con el detalle del consumo energético semanal de la empresa<br>Y el reporte queda disponible en la sección “Historial corporativo” de la app<br><br>**Scenario 2: Envío del reporte por correo electrónico**<br>Dado que el administrador tiene configurado su correo en la aplicación<br>Cuando el reporte semanal es generado<br>Entonces el sistema envía automáticamente el reporte en formato PDF y Excel al correo registrado<br>Y el administrador recibe una notificación de confirmación en la app<br><br>**Scenario 3: Contenido del reporte**<br>Dado que el administrador consulta su reporte semanal<br>Cuando el reporte es mostrado en la app<br>Entonces el sistema presenta los datos de consumo total en kWh, costo estimado y desglose por áreas o dispositivos<br>Y muestra comparaciones con semanas anteriores para identificar patrones de consumo<br><br>**Scenario 4: Acceso a reportes pasados**<br>Dado que el administrador quiere revisar reportes de semanas anteriores<br>Cuando selecciona una semana en el calendario dentro de “Historial corporativo”<br>Entonces el sistema muestra el reporte correspondiente a esa semana con el mismo formato |
| HU23 | HU23 | Hogar | Alertas de exceso | Como usuario de hogar, quiero recibir alertas cuando supere un umbral de consumo para reaccionar a tiempo. | **Scenario 1: Configuración de umbral de consumo**<br>Dado que el usuario se encuentra en la sección "Configuración de alertas"<br>Cuando el usuario establece un valor límite de consumo diario o mensual en kWh<br>Entonces el sistema guarda ese umbral como referencia para generar alertas<br><br>**Scenario 2: Generación de alerta por exceso de consumo**<br>Dado que el sistema monitorea el consumo energético en tiempo real<br>Y el usuario configuró un umbral de consumo<br>Cuando el consumo acumulado supera el umbral definido<br>Entonces el sistema genera automáticamente una alerta<br>Y muestra el mensaje “Has superado tu límite de consumo” en la sección de notificaciones<br><br>**Scenario 3: Envío de notificación push**<br>Dado que el usuario tiene habilitadas las notificaciones en su dispositivo<br>Cuando el sistema genera una alerta por exceso de consumo<br>Entonces el sistema envía una notificación push con el detalle del exceso detectado<br>Y el usuario puede acceder desde la notificación al detalle de consumo<br><br>**Scenario 4: Consulta de historial de alertas**<br>Dado que el usuario ingresa al historial de alertas en la aplicación<br>Cuando el sistema muestra las alertas pasadas<br>Entonces se presentan la fecha, hora y nivel de exceso de cada alerta registrada |
| HU24 | HU24 | PYME | Alertas de picos energéticos | Como administrador de PYME, quiero recibir alertas automáticas en picos de consumo para identificar anomalías. | **Scenario 1: Configuración de umbral de pico energético**<br>Dado que el administrador accede a la sección "Configuración de alertas"<br>Cuando define un umbral de consumo máximo en kWh por hora o por área<br>Entonces el sistema guarda este umbral para detectar futuros picos energéticos<br><br>**Scenario 2: Generación de alerta por pico energético**<br>Dado que el sistema monitorea el consumo energético en tiempo real por áreas/departamentos<br>Y existe un umbral de pico configurado<br>Cuando se detecta que el consumo supera ese umbral en un periodo corto de tiempo<br>Entonces el sistema genera automáticamente una alerta de pico energético<br>Y muestra un mensaje en la sección de notificaciones<br><br>**Scenario 3: Envío de notificación corporativa**<br>Dado que el administrador tiene habilitadas las notificaciones en la plataforma<br>Cuando ocurre un pico energético y el sistema genera una alerta<br>Entonces se envía una notificación al administrador con los detalles (área, hora, nivel de consumo)<br><br>**Scenario 4: Consulta de historial de alertas de picos**<br>Dado que el administrador accede al historial de alertas en la plataforma<br>Cuando el sistema lista las alertas anteriores<br>Entonces se muestran los registros con fecha, hora, área afectada y nivel del pico detectado |
| HU25 | HU25 | Hogar | Historial de consumo | Como usuario de hogar, quiero ver un historial gráfico de mi consumo energético para analizar mis tendencias. | **Scenario 1: Acceso al historial de consumo**<br>Dado que el usuario de hogar inicia sesión en la plataforma<br>Cuando accede a la sección "Historial de consumo"<br>Entonces el sistema muestra un gráfico con el consumo energético registrado en los últimos días<br><br>**Scenario 2: Visualización por periodos de tiempo**<br>Dado que el sistema muestra el historial de consumo en un gráfico<br>Cuando el usuario selecciona un rango de tiempo (diario, semanal, mensual)<br>Entonces el gráfico se actualiza mostrando los datos correspondientes a ese periodo<br><br>**Scenario 3: Detalle de consumo en puntos del gráfico**<br>Dado que el gráfico de historial de consumo está visible<br>Cuando el usuario pasa el cursor o toca un punto específico del gráfico<br>Entonces el sistema muestra el valor exacto del consumo correspondiente a esa fecha y hora<br><br>**Scenario 4: Exportación del historial de consumo**<br>Dado que el usuario desea conservar un registro fuera de la plataforma<br>Cuando selecciona la opción "Exportar historial"<br>Entonces el sistema genera un archivo descargable (CSV o PDF) con los datos del consumo energético en el rango seleccionado |
| HU26 | HU26 | PYME | Historial corporativo avanzado | Como administrador de PYME, quiero generar reportes históricos avanzados para evaluar el impacto de medidas de ahorro. | **Scenario 1: Acceso al historial corporativo**<br>Dado que el administrador de PYME inicia sesión en la plataforma<br>Cuando accede a la sección "Historial corporativo avanzado"<br>Entonces el sistema muestra un panel con las métricas históricas de consumo energético de la empresa<br><br>**Scenario 2: Selección de periodos personalizados**<br>Dado que el administrador visualiza el historial corporativo<br>Cuando selecciona un rango de fechas personalizado (ejemplo: últimos 6 meses o un año específico)<br>Entonces el sistema actualiza los gráficos y tablas con los datos correspondientes a ese rango<br><br>**Scenario 3: Comparación entre periodos**<br>Dado que el sistema muestra el historial de consumo corporativo<br>Cuando el administrador selecciona dos periodos distintos (ejemplo: 2023 vs 2024)<br>Entonces el sistema presenta un reporte comparativo que muestra diferencias de consumo y tendencias<br><br>**Scenario 4: Evaluación de impacto de medidas de ahorro**<br>Dado que el sistema tiene datos históricos registrados<br>Cuando el administrador activa la opción "Evaluar impacto" sobre periodos donde se aplicaron medidas de ahorro<br>Entonces el sistema genera un reporte resaltando reducciones o incrementos en el consumo energético y calcula el porcentaje de variación<br><br>**Scenario 5: Exportación de reportes históricos**<br>Dado que el administrador requiere almacenar los datos fuera de la plataforma<br>Cuando selecciona la opción "Exportar historial avanzado"<br>Entonces el sistema genera un archivo descargable (CSV o PDF) con los gráficos, métricas y comparaciones seleccionadas |
| HU27 | HU27 | Hogar | Comparativa mensual | Como usuario de hogar, quiero comparar mi consumo mensual con meses anteriores para evaluar mi progreso. | **Scenario 1: Acceso a la comparativa mensual**<br>Dado que el usuario de hogar inicia sesión en la plataforma<br>Cuando accede a la sección "Comparativa mensual"<br>Entonces el sistema muestra un gráfico con el consumo del mes actual y de los últimos meses<br><br>**Scenario 2: Selección de meses anteriores**<br>Dado que el usuario está visualizando la comparativa mensual<br>Cuando selecciona uno o más meses anteriores en el filtro<br>Entonces el sistema actualiza el gráfico mostrando el consumo de los meses seleccionados junto al consumo actual<br><br>**Scenario 3: Indicador de progreso**<br>Dado que el sistema presenta los datos de consumo mensual<br>Cuando el usuario visualiza la comparativa<br>Entonces el sistema muestra un indicador visual (ejemplo: porcentaje de aumento o reducción) para señalar la evolución frente a meses anteriores<br><br>**Scenario 4: Descarga de reporte mensual**<br>Dado que el usuario quiere guardar los resultados de la comparativa<br>Cuando selecciona la opción "Descargar comparativa mensual"<br>Entonces el sistema genera un archivo en formato PDF o CSV con la información de consumo comparativo<br><br>**Scenario 5: Consumo superior al promedio**<br>Dado que el sistema detecta que el consumo del mes actual es mayor al promedio de los meses anteriores<br>Cuando se actualiza la comparativa mensual<br>Entonces el sistema muestra una alerta informativa recomendando revisar hábitos de consumo |
| HU28 | HU28 | PYME | Comparativa entre sedes | Como administrador de PYME, quiero comparar el consumo energético entre distintas sedes para detectar ineficiencias. | **Scenario 1: Acceso a la comparativa entre sedes**<br>Dado que el administrador de PYME inicia sesión en la plataforma<br>Cuando accede a la sección "Comparativa entre sedes"<br>Entonces el sistema muestra una tabla y/o gráfico con el consumo energético de cada sede registrada en la cuenta<br><br>**Scenario 2: Selección de rango de fechas**<br>Dado que el administrador se encuentra en la sección de comparativa entre sedes<br>Cuando selecciona un rango de fechas específico<br>Entonces el sistema actualiza los datos de consumo para mostrar solo el consumo de las sedes en ese rango de fechas<br><br>**Scenario 3: Identificación de sede con mayor consumo**<br>Dado que el sistema presenta los datos de todas las sedes en un gráfico comparativo<br>Cuando se actualizan los valores<br>Entonces el sistema resalta la sede con mayor consumo con un indicador visual (ejemplo: color resaltado o ícono de advertencia)<br><br>**Scenario 4: Exportación de comparativa**<br>Dado que el administrador necesita registrar los datos para análisis externo<br>Cuando selecciona la opción "Exportar comparativa"<br>Entonces el sistema genera un archivo en formato PDF o Excel con el detalle de consumo energético de cada sede<br><br>**Scenario 5: Generación de alertas automáticas**<br>Dado que la comparativa entre sedes identifica una diferencia significativa en el consumo (ejemplo: una sede con un 30% más de consumo que el promedio)<br>Cuando se guarda la comparativa<br>Entonces el sistema genera una alerta automática notificando al administrador sobre la anomalía detectada |
| HU29 | HU29 | Hogar | Notificaciones push | Como usuario de hogar, quiero recibir notificaciones push sobre mi consumo para estar informado en tiempo real. | **Scenario 1: Activación de notificaciones**<br>Dado que el usuario de hogar ha iniciado sesión en la aplicación<br>Cuando accede a la sección de configuración de notificaciones y activa la opción de "Notificaciones push"<br>Entonces el sistema guarda la preferencia y habilita el envío de notificaciones en tiempo real<br><br>**Scenario 2: Recepción de notificación por consumo excesivo**<br>Dado que el usuario tiene activadas las notificaciones push<br>Cuando su consumo energético diario supera el umbral configurado en su perfil<br>Entonces el sistema envía una notificación push con el mensaje de advertencia y el detalle del consumo<br><br>**Scenario 3: Notificación de reporte diario disponible**<br>Dado que el sistema genera automáticamente el reporte diario de consumo<br>Cuando el reporte está listo para visualizarse<br>Entonces el usuario recibe una notificación push indicando que puede revisar su reporte en la aplicación<br><br>**Scenario 4: Sincronización de notificaciones en múltiples dispositivos**<br>Dado que el usuario de hogar tiene la aplicación instalada en más de un dispositivo (ejemplo: móvil y tablet)<br>Cuando se genera una notificación push<br>Entonces el sistema envía la notificación a todos los dispositivos vinculados con la misma cuenta<br><br>**Scenario 5: Desactivación de notificaciones**<br>Dado que el usuario ya no desea recibir notificaciones en tiempo real<br>Cuando desactiva la opción de "Notificaciones push" en la configuración<br>Entonces el sistema detiene el envío de notificaciones hasta que el usuario las active nuevamente |
| HU30 | HU30 | PYME | Notificaciones por correo | Como administrador de PYME, quiero recibir alertas por correo sobre consumos inusuales para actuar oportunamente. | **Scenario 1: Configuración de alertas por correo**<br>Dado que el administrador de PYME ha iniciado sesión en la plataforma<br>Cuando accede a la sección de notificaciones y activa la opción "Alertas por correo"<br>Entonces el sistema guarda la preferencia y habilita el envío de correos ante consumos inusuales<br><br>**Scenario 2: Envío de alerta por consumo inusual**<br>Dado que el administrador tiene activadas las alertas por correo<br>Cuando el sistema detecta un consumo que supera el umbral definido en la configuración de la empresa<br>Entonces se envía un correo automático al administrador con el detalle del evento de consumo<br><br>**Scenario 3: Recepción en múltiples destinatarios**<br>Dado que el administrador ha registrado varios correos de responsables de área<br>Cuando ocurre un evento de consumo inusual<br>Entonces el sistema envía la notificación a todos los correos registrados en la configuración<br><br>**Scenario 4: Confirmación de envío exitoso**<br>Dado que el sistema genera una alerta por correo<br>Cuando el mensaje es enviado<br>Entonces el sistema registra en el historial de notificaciones que el correo fue entregado exitosamente<br><br>**Scenario 5: Desactivación de alertas por correo**<br>Dado que el administrador ya no desea recibir alertas por correo<br>Cuando desactiva la opción en la configuración de notificaciones<br>Entonces el sistema detiene el envío de correos hasta que se reactive nuevamente |

---

### Epic 5 – Inteligencia Artificial (IA Verde)
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU31 | HU31 | Hogar | Recomendaciones básicas IA | Como usuario de hogar, quiero recibir recomendaciones simples para ahorrar energía en base a mis datos. | **Scenario 1: Generación de recomendaciones iniciales**<br>Dado que el usuario de hogar ha registrado sus dispositivos y hábitos en la plataforma<br>Cuando la IA analiza los primeros datos de consumo<br>Entonces el sistema muestra recomendaciones básicas personalizadas en la sección de “Consejos de ahorro”<br><br>**Scenario 2: Actualización automática de recomendaciones**<br>Dado que el usuario tiene un historial de consumo activo<br>Cuando se detectan cambios en sus patrones de uso<br>Entonces la IA actualiza las recomendaciones y las muestra en el panel principal<br><br>**Scenario 3: Visualización en el dashboard**<br>Dado que el usuario inicia sesión en la plataforma<br>Cuando accede al dashboard de consumo<br>Entonces el sistema despliega un bloque con las recomendaciones actuales generadas por la IA<br><br>**Scenario 4: Diferenciación según tipo de dispositivo**<br>Dado que la IA identifica distintos dispositivos conectados (ejemplo: refrigerador, luces, aire acondicionado)<br>Cuando genera las recomendaciones<br>Entonces el sistema especifica consejos vinculados a cada tipo de dispositivo<br><br>**Scenario 5: Registro de interacción del usuario**<br>Dado que el usuario lee una recomendación<br>Cuando marca la opción “Aplicado” o “No relevante”<br>Entonces el sistema registra la respuesta y ajusta las recomendaciones futuras de acuerdo con las elecciones del usuario |
| HU32 | HU32 | PYME | Recomendaciones IA corporativas | Como administrador de PYME, quiero obtener sugerencias de IA sobre cómo reducir costos energéticos en mis operaciones. | **Scenario 1: Visualización inicial de recomendaciones de IA**<br>Dado que el administrador ha iniciado sesión en el sistema<br>Y el sistema tiene acceso a datos históricos de consumo energético de la empresa<br>Cuando el administrador abre la sección “Recomendaciones de IA”<br>Entonces el sistema muestra un panel con sugerencias personalizadas de ahorro energético<br>Y cada sugerencia incluye una breve explicación comprensible para el usuario.<br><br>**Scenario 2: Actualización periódica de recomendaciones**<br>Dado que el sistema ya generó recomendaciones previas<br>Cuando el sistema detecta nueva información de consumo energético o llega la fecha de actualización programada (ej. semanal)<br>Entonces el sistema recalcula las recomendaciones<br>Y el administrador visualiza un mensaje indicando que hay sugerencias actualizadas.<br><br>**Scenario 3: Exportar recomendaciones**<br>Dado que el administrador visualiza el panel de recomendaciones de IA<br>Cuando el administrador selecciona la opción “Exportar reporte”<br>Entonces el sistema genera un archivo descargable con las recomendaciones y explicaciones en formato PDF o Excel<br>Y el archivo incluye la fecha de generación del reporte. |
| HU33 | HU33 | Hogar | Optimización automática IA | Como usuario de hogar, quiero que la IA configure mis dispositivos automáticamente para optimizar mi consumo sin esfuerzo. | **Scenario 1: Activación de optimización automática**<br>Dado que el usuario de hogar ha iniciado sesión en el sistema<br>Y tiene dispositivos inteligentes vinculados a su cuenta<br>Cuando el usuario activa la opción “Optimización automática con IA” en la configuración<br>Entonces el sistema ajusta automáticamente los dispositivos (ej. aire acondicionado, luces, electrodomésticos) según patrones de uso eficientes<br>Y muestra una notificación confirmando que la optimización está activa.<br><br>**Scenario 2: Ajustes en tiempo real por la IA**<br>Dado que la opción de “Optimización automática con IA” está activa<br>Cuando el sistema detecta un consumo elevado en un dispositivo fuera de lo normal<br>Entonces la IA ajusta la configuración de dicho dispositivo para reducir el consumo<br>Y envía una notificación al usuario indicando la acción tomada.<br><br>**Scenario 3: Desactivación de optimización automática**<br>Dado que la IA está gestionando automáticamente los dispositivos del hogar<br>Cuando el usuario desactiva la opción de “Optimización automática con IA”<br>Entonces el sistema detiene cualquier ajuste automático<br>Y los dispositivos mantienen su última configuración manual. |
| HU34 | HU34 | PYME | Estrategias automáticas IA corporativas | Como administrador de PYME, quiero que la IA ajuste automáticamente el consumo de mi empresa para reducir costos y huella de carbono. | **Scenario 1: Activación de estrategias automáticas IA**<br>Dado que el administrador de la PYME tiene acceso al panel de control energético<br>Y existen dispositivos y medidores vinculados a la empresa<br>Cuando el administrador activa la opción “Estrategias automáticas con IA” en el sistema<br>Entonces la IA analiza los patrones de consumo corporativo<br>Y ajusta automáticamente los dispositivos y horarios de operación para optimizar el uso energético.<br><br>**Scenario 2: Ajustes en tiempo real para reducción de costos**<br>Dado que la opción “Estrategias automáticas con IA” está activa<br>Cuando el sistema detecta un pico de consumo en horas de alta demanda energética<br>Entonces la IA redistribuye las cargas de trabajo y pospone procesos no críticos<br>Y envía una alerta al administrador informando las acciones tomadas y el ahorro estimado.<br><br>**Scenario 3: Ajustes en tiempo real para reducir huella de carbono**<br>Dado que el sistema está optimizando automáticamente el consumo<br>Cuando la IA identifica oportunidades de reducción de emisiones (ej. priorizar energía renovable disponible)<br>Entonces ajusta los dispositivos y procesos corporativos para maximizar el uso de energía limpia<br>Y genera un reporte con el impacto ambiental reducido.<br><br>**Scenario 4: Desactivación de estrategias automáticas IA**<br>Dado que la IA está gestionando automáticamente el consumo corporativo<br>Cuando el administrador desactiva la opción de “Estrategias automáticas con IA”<br>Entonces el sistema detiene los ajustes automáticos<br>Y los dispositivos vuelven a su configuración estándar de operación. |

---

### Epic 6 – Accesibilidad y Compatibilidad
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU35 | HU35 | Hogar | Compatibilidad multiplataforma | Como usuario de hogar, quiero que la aplicación esté disponible en iOS y Android para acceder desde cualquier dispositivo. | **Scenario 1: Instalación en iOS**<br>Dado que el usuario tiene un dispositivo con sistema operativo iOS<br>Cuando el usuario accede a la App Store y busca la aplicación<br>Entonces el sistema permite descargar e instalar la aplicación correctamente<br>Y la aplicación se ejecuta sin errores en iOS.<br><br>**Scenario 2: Instalación en Android**<br>Dado que el usuario tiene un dispositivo con sistema operativo Android<br>Cuando el usuario accede a Google Play Store y busca la aplicación<br>Entonces el sistema permite descargar e instalar la aplicación correctamente<br>Y la aplicación se ejecuta sin errores en Android.<br><br>**Scenario 3: Sincronización entre dispositivos**<br>Dado que el usuario tiene la aplicación instalada en un dispositivo iOS y en un dispositivo Android con la misma cuenta<br>Cuando inicia sesión en ambos dispositivos<br>Entonces el sistema sincroniza los datos de consumo, reportes y configuraciones<br>Y el usuario puede acceder a la misma información en ambos dispositivos.<br><br>**Scenario 4: Interfaz adaptativa**<br>Dado que la aplicación está instalada en un dispositivo iOS o Android<br>Cuando el usuario abre la aplicación<br>Entonces la interfaz se adapta correctamente a las dimensiones y resoluciones de la pantalla del dispositivo<br>Y mantiene la misma experiencia de uso en ambas plataformas. |
| HU36 | HU36 | PYME | Acceso web empresarial | Como administrador de PYME, quiero poder acceder a la plataforma vía web para gestionarla desde mi oficina. | **Scenario 1: Acceso desde navegador**<br>Dado que el administrador cuenta con un navegador actualizado en su equipo de oficina<br>Cuando ingresa la URL de la plataforma en la barra de direcciones<br>Entonces el sistema muestra la pantalla de inicio de sesión<br>Y permite al administrador autenticarse correctamente.<br><br>**Scenario 2: Inicio de sesión seguro**<br>Dado que el administrador ingresa su usuario y contraseña válidos<br>Cuando presiona el botón “Iniciar sesión”<br>Entonces el sistema valida las credenciales<br>Y muestra el panel de control empresarial.<br><br>**Scenario 3: Gestión completa desde web**<br>Dado que el administrador accedió al panel de control empresarial vía web<br>Cuando navega por las diferentes secciones de la plataforma<br>Entonces el sistema le permite visualizar reportes, configurar dispositivos y recibir alertas<br>Y todas las funcionalidades disponibles en la aplicación móvil están también habilitadas en la versión web.<br><br>**Scenario 4: Compatibilidad de navegadores**<br>Dado que el administrador utiliza navegadores como Google Chrome, Microsoft Edge o Mozilla Firefox<br>Cuando accede a la plataforma web<br>Entonces el sistema muestra la interfaz correctamente<br>Y todas las funcionalidades responden sin errores en los navegadores soportados. |

---

### Epic 7 – Desarrollo Técnico (RESTful API)
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU37 | HU37 | Developer | Endpoint de autenticación | Como desarrollador, quiero un endpoint de autenticación basado en JWT para gestionar de forma segura el acceso a la aplicación. | **Scenario 1: Solicitud de autenticación exitosa**<br>Dado que el desarrollador envía una solicitud POST al endpoint de autenticación con credenciales válidas (usuario y contraseña)<br>Cuando el sistema valida dichas credenciales en la base de datos<br>Entonces el sistema responde con un token JWT válido que incluye el identificador del usuario y tiempo de expiración.<br><br>**Scenario 2: Solicitud de autenticación fallida**<br>Dado que el desarrollador envía credenciales incorrectas al endpoint de autenticación<br>Cuando el sistema intenta validar los datos<br>Entonces el sistema responde con un código de error HTTP 401 (Unauthorized) y un mensaje indicando “Credenciales inválidas”.<br><br>**Scenario 3: Expiración del token**<br>Dado que el desarrollador utiliza un token JWT previamente generado<br>Cuando el tiempo de validez del token ha expirado<br>Entonces el sistema rechaza la solicitud y devuelve un error 401 (Unauthorized) con el mensaje “Token expirado”.<br><br>**Scenario 4: Verificación del token en peticiones**<br>Dado que el desarrollador realiza una solicitud a un endpoint protegido<br>Cuando incluye un token JWT válido en la cabecera de autorización<br>Entonces el sistema valida el token y concede acceso a los recursos solicitados.<br><br>**Scenario 5: Token inválido o manipulado**<br>Dado que el desarrollador envía un token JWT alterado o inválido en la cabecera de autorización<br>Cuando el sistema intenta validar el token<br>Entonces rechaza la solicitud y responde con un error 403 (Forbidden) indicando que el token no es válido. |
| HU38 | HU38 | Developer | Endpoint de consumo energético | Como desarrollador, quiero exponer un endpoint que devuelva el consumo energético en tiempo real para mostrarlo en la app . | **Scenario 1: Consulta de consumo en tiempo real exitosa**<br>Dado que el desarrollador envía una solicitud GET al endpoint /api/consumo/realtime con un token JWT válido<br>Cuando el sistema obtiene los datos de consumo de los dispositivos asociados al usuario<br>Entonces responde con un objeto JSON que contiene el valor de consumo actual, la fecha y hora de la medición.<br><br>**Scenario 2: Usuario sin dispositivos registrados**<br>Dado que el usuario autenticado no tiene dispositivos asociados en la base de datos<br>Cuando se solicita el consumo en tiempo real<br>Entonces el sistema responde con un objeto JSON vacío o con valores en cero, junto con un mensaje “No se encontraron dispositivos registrados”.<br><br>**Scenario 3: Token no válido**<br>Dado que el desarrollador realiza la solicitud al endpoint sin incluir un token JWT válido en la cabecera<br>Cuando el sistema intenta validar la autenticación<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 4: Error en la obtención de datos**<br>Dado que el desarrollador envía una solicitud correcta al endpoint<br>Cuando ocurre un error en la consulta a la base de datos o al servicio de monitoreo<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al obtener datos de consumo energético”. |
| HU39 | HU39 | Developer | Endpoint de control de dispositivos | Como desarrollador, quiero un endpoint para encender/apagar dispositivos conectados a los actuadores para que el frontend gestione el control remoto. | **Scenario 1: Encendido exitoso de dispositivo**<br>Dado que el desarrollador envía una solicitud POST al endpoint /api/dispositivos/control con un token JWT válido y un cuerpo JSON con {“deviceId": "123", "action": "on”}<br>Cuando el sistema procesa la solicitud y actualiza el estado del dispositivo en la base de datos<br>Entonces responde con un código 200 y un mensaje “Dispositivo encendido correctamente”.<br><br>**Scenario 2: Apagado exitoso de dispositivo**<br>Dado que el desarrollador envía una solicitud POST al endpoint /api/dispositivos/control con un token JWT válido y un cuerpo JSON con {“deviceId": "123", "action": "off”}<br>Cuando el sistema procesa la solicitud y actualiza el estado del dispositivo en la base de datos<br>Entonces responde con un código 200 y un mensaje “Dispositivo apagado correctamente”.<br><br>**Scenario 3: Token no válido**<br>Dado que el desarrollador realiza la solicitud al endpoint sin incluir un token JWT válido<br>Cuando el sistema intenta autenticar la solicitud<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 4: Dispositivo no encontrado**<br>Dado que el desarrollador envía una solicitud con un deviceId inexistente en la base de datos<br>Cuando el sistema intenta ejecutar la acción<br>Entonces responde con un código 404 (Not Found) y un mensaje “Dispositivo no encontrado”.<br><br>**Scenario 5: Error en la ejecución de la acción**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando ocurre un error en la comunicación con el actuador o en la base de datos<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al ejecutar la acción sobre el dispositivo”. |
| HU40 | HU40 | Developer | Endpoint de reportes históricos | Como desarrollador, quiero un endpoint para obtener el historial de consumo energético por rango de fechas para alimentar los reportes de la app. | **Scenario 1: Consulta exitosa de historial por rango de fechas**<br>Dado que el desarrollador envía una solicitud GET al endpoint /api/reportes/historicos?fechaInicio=2025-01-01&fechaFin=2025-01-31 con un token JWT válido<br>Cuando el sistema valida el token y procesa la solicitud<br>Entonces responde con un código 200 y un cuerpo JSON que contiene la lista de registros de consumo energético dentro del rango de fechas solicitado.<br><br>**Scenario 2: Falta de parámetros de fechas**<br>Dado que el desarrollador envía una solicitud al endpoint sin incluir fechaInicio o fechaFin<br>Cuando el sistema intenta procesar la solicitud<br>Entonces responde con un código 400 (Bad Request) y un mensaje “Parámetros de fecha requeridos”.<br><br>**Scenario 3: Rango de fechas inválido**<br>Dado que el desarrollador envía un rango en el que fechaFin es anterior a fechaInicio<br>Cuando el sistema valida los parámetros<br>Entonces responde con un código 400 (Bad Request) y un mensaje “Rango de fechas inválido”.<br><br>**Scenario 4: Token no válido o ausente**<br>Dado que el desarrollador realiza la solicitud sin un token JWT válido<br>Cuando el sistema intenta autenticar la solicitud<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 5: Sin datos en el rango solicitado**<br>Dado que el desarrollador solicita un rango de fechas válido<br>Cuando no existen registros de consumo energético en ese periodo<br>Entonces el sistema responde con un código 200 y un cuerpo JSON con una lista vacía.<br><br>**Scenario 6: Error interno del servidor**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando ocurre un error inesperado en la base de datos o el backend<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al generar el reporte histórico”. |
| HU41 | HU41 | Developer | Endpoint de recomendaciones IA | Como desarrollador, quiero un endpoint que entregue recomendaciones de ahorro energético para que el frontend las muestre de manera personalizada. | **Scenario 1: Solicitud exitosa de recomendaciones personalizadas**<br>Dado que el desarrollador envía una solicitud GET al endpoint /api/recomendaciones/ia con un token JWT válido y un parámetro userId=123<br>Cuando el sistema procesa la solicitud y consulta el motor de IA con los datos de consumo del usuario<br>Entonces responde con un código 200 y un cuerpo JSON que contiene una lista de recomendaciones personalizadas.<br><br>**Scenario 2: Token no válido o ausente**<br>Dado que el desarrollador realiza la solicitud sin incluir un token JWT válido<br>Cuando el sistema intenta autenticar la solicitud<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 3: Falta de parámetros requeridos**<br>Dado que el desarrollador envía la solicitud sin incluir el parámetro userId<br>Cuando el sistema valida los parámetros de entrada<br>Entonces responde con un código 400 (Bad Request) y un mensaje “El parámetro userId es requerido”.<br><br>**Scenario 4: Recomendaciones no disponibles**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando el sistema no encuentra recomendaciones generadas para el usuario en ese momento<br>Entonces responde con un código 200 y un cuerpo JSON vacío o con un mensaje “No hay recomendaciones disponibles actualmente”.<br><br>**Scenario 5: Error interno del servidor**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando ocurre un fallo inesperado en el motor de IA o en la base de datos<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al generar recomendaciones de IA”. |

### 2.4.2. Impact Mapping

![impact map](Imagenes/impact-map.png)

### 2.4.3. Product Backlog

| Orden | User Story Id | Título | Descripción | Story Points |
| --- | --- | --- | --- | --- |
| 1 | HU1 | Información general del producto | Como visitante interesado en mejorar el consumo energético en mi hogar, quiero acceder a información clara sobre la plataforma para entender cómo me beneficia. | 2 |
| 2 | HU2 | Casos de éxito | Como visitante, quiero consultar casos de éxito reales para confiar en la efectividad de la solución antes de registrarme. | 2 |
| 3 | HU3 | Comparativa de planes | Como visitante, quiero ver la comparativa de planes y precios para elegir la opción que se ajuste mejor a mis necesidades. | 3 |
| 4 | HU4 | Contacto | Como visitante, quiero disponer de un formulario de contacto. | 2 |
| 5 | HU5 | Registro de cuenta | Como usuario de hogar, quiero registrarme en la plataforma para comenzar a gestionar mi consumo energético. | 3 |
| 6 | HU6 | Registro empresarial | Como administrador de PYME, quiero registrar mi empresa en la plataforma para gestionar el consumo energético de mis instalaciones. | 5 |
| 7 | HU7 | Inicio de sesión | Como usuario de hogar, quiero iniciar sesión de forma segura para acceder a mis datos de consumo. | 3 |
| 8 | HU8 | Inicio de sesión corporativo | Como administrador de PYME, quiero iniciar sesión corporativa para acceder a las métricas de mi organización. | 5 |
| 9 | HU9 | Gestión de múltiples usuarios | Como administrador de PYME, quiero dar acceso a distintos roles (empleados, supervisores) para distribuir responsabilidades. | 5 |
| 10 | HU10 | Personalización de perfil | Como usuario de hogar, quiero personalizar mi perfil con mis hábitos para recibir recomendaciones más relevantes. | 3 |
| 11 | HU11 | Dashboard en tiempo real | Como usuario de hogar, quiero visualizar el consumo energético en un dashboard para monitorear mi gasto en tiempo real. | 5 |
| 12 | HU12 | Dashboard empresarial | Como administrador de PYME, quiero ver un panel de consumo por áreas/departamentos para identificar ineficiencias. | 8 |
| 13 | HU13 | Control remoto de dispositivos | Como usuario de hogar, quiero encender/apagar mis dispositivos desde la app para ahorrar energía. | 2 |
| 14 | HU14 | Control remoto empresarial | Como administrador de PYME, quiero gestionar remotamente dispositivos de mi oficina para reducir gastos energéticos. | 5 |
| 15 | HU15 | Programar horarios | Como usuario de hogar, quiero programar horarios de encendido/apagado de mis electrodomésticos para optimizar el consumo. | 4 |
| 16 | HU16 | Programación grupal | Como administrador de PYME, quiero establecer horarios automáticos de apagado en áreas comunes para evitar consumos innecesarios. | 5 |
| 17 | HU17 | Gestión de dispositivos | Como usuario de hogar, quiero registrar y administrar mis dispositivos conectados para organizarlos en la app. | 3 |
| 18 | HU18 | Gestión masiva de dispositivos | Como administrador de PYME, quiero dar de alta y controlar múltiples dispositivos de manera centralizada para optimizar su uso. | 5 |
| 19 | HU19 | Reporte diario | Como usuario de hogar, quiero recibir un reporte diario de mi consumo para tener visibilidad de mis hábitos. | 3 |
| 20 | HU20 | Reporte semanal corporativo | Como administrador de PYME, quiero recibir reportes semanales consolidados para analizar patrones de consumo en mi empresa. | 5 |
| 21 | HU21 | Alertas de exceso | Como usuario de hogar, quiero recibir alertas cuando supere un umbral de consumo para reaccionar a tiempo. | 2 |
| 22 | HU22 | Alertas de picos energéticos | Como administrador de PYME, quiero recibir alertas automáticas en picos de consumo para identificar anomalías. | 3 |
| 23 | HU23 | Historial de consumo | Como usuario de hogar, quiero ver un historial gráfico de mi consumo energético para analizar mis tendencias. | 3 |
| 24 | HU24 | Historial corporativo avanzado | Como administrador de PYME, quiero generar reportes históricos avanzados para evaluar el impacto de medidas de ahorro. | 5 |
| 25 | HU25 | Comparativa mensual | Como usuario de hogar, quiero comparar mi consumo mensual con meses anteriores para evaluar mi progreso. | 2 |
| 26 | HU26 | Comparativa entre sedes | Como administrador de PYME, quiero comparar el consumo energético entre distintas sedes para detectar ineficiencias. | 3 |
| 27 | HU27 | Notificaciones push | Como usuario de hogar, quiero recibir notificaciones push sobre mi consumo para estar informado en tiempo real. | 2 |
| 28 | HU28 | Notificaciones por correo | Como administrador de PYME, quiero recibir alertas por correo sobre consumos inusuales para actuar oportunamente. | 3 |
| 29 | HU29 | Recomendaciones básicas IA | Como usuario de hogar, quiero recibir recomendaciones simples para ahorrar energía en base a mis datos. | 3 |
| 30 | HU30 | Recomendaciones IA corporativas | Como administrador de PYME, quiero obtener sugerencias de IA sobre cómo reducir costos energéticos en mis operaciones. | 5 |
| 31 | HU31 | Optimización automática IA | Como usuario de hogar, quiero que la IA configure mis dispositivos automáticamente para optimizar mi consumo sin esfuerzo. | 8 |
| 32 | HU32 | Estrategias automáticas IA corporativas | Como administrador de PYME, quiero que la IA ajuste automáticamente el consumo de mi empresa para reducir costos y huella de carbono. | 5 |
| 33 | HU33 | Compatibilidad multiplataforma | Como usuario de hogar, quiero que la aplicación esté disponible en iOS y Android para acceder desde cualquier dispositivo. | 3 |
| 34 | HU34 | Acceso web empresarial | Como administrador de PYME, quiero poder acceder a la plataforma vía web para gestionarla desde mi oficina. | 3 |
| 35 | HU35 | Endpoint de autenticación | Como desarrollador, quiero un endpoint de autenticación basado en JWT para gestionar de forma segura el acceso a la aplicación. | 5 |
| 36 | HU36 | Endpoint de consumo energético | Como desarrollador, quiero exponer un endpoint que devuelva el consumo energético en tiempo real para mostrarlo en la app. | 3 |
| 37 | HU37 | Endpoint de control de dispositivos | Como desarrollador, quiero un endpoint para encender/apagar dispositivos conectados a los actuadores para que el frontend gestione el control remoto. | 5 |
| 38 | HU38 | Endpoint de reportes históricos | Como desarrollador, quiero un endpoint para obtener el historial de consumo energético por rango de fechas para alimentar los reportes de la app. | 3 |
| 39 | HU39 | Endpoint de recomendaciones IA | Como desarrollador, quiero un endpoint que entregue recomendaciones de ahorro energético para que el frontend las muestre de manera personalizada. | 5 |
| 40 | HU40 | Endpoint de optimización automática IA | Como desarrollador, quiero un endpoint que optimice el consumo energético de los dispositivos basándose en los datos analizados por la IA. | 3 |
| 41 | HU41 | Endpoint de alertas | Como desarrollador, quiero un endpoint que envíe alertas a los usuarios cuando superen los umbrales de consumo. | 5 |


## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming

Tras haber mapeado el flujo macro del negocio, procedemos al Design-Level Event Storming. En esta etapa el enfoque se desplaza hacia el diseño detallado de la solución de software. Aquí expandimos cada Domain Event integrando Commands, Polices, Aggregates y Read Models, permitiendonos visualizar no solo qué sucede, sino cómo interactua el usuario con el sistema y qué reglas de negocio rigen el comportamiento de PowerSense. Este nivel de detalle es fundamental para identificar de forma natural las fronteras del sistema, sirviendo como paso previo y necesario para la delimitación técnica de los Bounded Contexts.

![event storming-1](Imagenes/event-storming/event-storming-1.png)
![event storming-2](Imagenes/event-storming/event-storming-2.png)
![event storming-3](Imagenes/event-storming/event-storming-3.png)
![event storming-4](Imagenes/event-storming/event-storming-4.png)

#### 2.5.1.1. Candidate Context Discovery

Una vez detallados los flujos del Design-Level Event Storming, procedemos al Candidate Context Discovery. Esta etapa representa la transición del análisis del flujo a la definición de la arquitectura estratégica. El objetivo es identificar grupos de funcionalidades que comparten un mismo Lenguaje Ubicuo y reglas de negocio cohesivas. Al agrupar estos elementos, emergen de manera natural los límites de los modelos, permitiéndonos proponer contextos candidatos que servirán como base para la descomposición del sistema en módulos independientes y escalables.

![dashboard](Imagenes/candidate-context-discovery/dashboard.png)
![devices](Imagenes/candidate-context-discovery/devices.png)
![scheduling](Imagenes/candidate-context-discovery/scheduling.png)
![reports](Imagenes/candidate-context-discovery/reports.png)
![alerts](Imagenes/candidate-context-discovery/alerts.png)
![auth](Imagenes/candidate-context-discovery/auth.png)

#### 2.5.1.2. Domain Message Flows Modeling

A countinuación se presenta el flujo de mensajes para el caso de uso principal o core para el negocio, el cual es el cálculo y exosición de las estadísticas de consumo de enrgía electrica del usuario. El flujo comienza desde que el dispositivo IoT envia los datos crudos, los cuales son procesador ppor el Monitoring Context. Aqui se bifurca el flujo, ya que si se detecta un pico en el umbral de consumo se debe emmitir una alerta de este tipo. El flujo terminaría entonces con la entrega de los datos de consumo asi como el costo promedio de este.

![flow 1](Imagenes/domain-message-flow-modeling/flow-1.png)

#### 2.5.1.3. Bounded Context Canvases

En esta sección se presenta los diferentes Canvas realizados para los contextos que se identificaron, comenzando desde los más importantes para el negocio. Aquí se detalla la información sobre este Bounded Context, así como la comunicación entrante y saliente. Además del lenguaje ubicuo y reglas de negocio que aplican en este contexto.

![dashboard](Imagenes/bounded-context-canvas/dashboard.png)
![devices](Imagenes/bounded-context-canvas/devices.png)
![scheduling](Imagenes/bounded-context-canvas/scheduling.png)
![reports](Imagenes/bounded-context-canvas/reports.png)
![alerts](Imagenes/bounded-context-canvas/alerts.png)
![auth](Imagenes/bounded-context-canvas/auth.png)

### 2.5.2. Context Mapping

Tras la delimitación de los Bounded Context, se procede a realizar el Context Mapping con el objetivo de definir las relaciones de dependencias y los contratos de integración entre los diferentes módulos de la aplicación. Este mapa estratégico no solo visualiza el flujo de información, sino que establece formalmente cómo los cambios en un modelo de dominio afectan a los demás mediante la identificación de roles Upstream (proveedores) y Downstream (consumidores), asegurándonos una arquitectura desacoplada que permite la evolución independiente de cada contexto, garantizando a su vez la consistencia de los datos en toda la plataforma. 

![context mappig](Imagenes/context-mapping.png)

**Justificación de los patrones utilizados**

Por un lado, se definió IAM como un Open Host Service debido a que la identidad del usuario es una necesidad transversal en todo el sistema. En lugar de crear integraciones personalizadas por cada módulo, IAM expone un acceso público y estandarizado que permite a cualquier contexto de tipo Downstream obtener los datos de formma uniforme. 

Por otro lado, la comunicación entre Monitoring y Alerts se basa en un Published Language para facilitar el intercambio de eventos de dominio d forma asíncronica. De esta forma, Monitoring puede publicar eventos específicos utilizando un formato de datos común que el contexto de Alerts puede traducir directamente en notificaciones. 

Para finalizar, se implemento Anti-Corruption Layer en el lado de Monitoring para proteger el diseño del modelo de dominio interno y crear un puente de comunicación entre este contexto con Reporting.

### 2.5.3. Software Architecture

Para la representación de la arquitectura de nuestro producto, se ha optado el modelo C4, un enfoque jerárquico que permite visualizar la estructura del sistema a través de múltiples niveles de abstracción. Este modelo es fundamental para comunicar el diseño técnico de manera clara, permitiendo visualizar las interacciones de alto nivel hasta la distribución física de los componentes. A través de los niveles de Contexto, Contenedores y Despliegue se detallará cómo la solución satisface los requerimientos de escalabilidad y mantenibilidad definidos para el monitoreo energético de hogares y MYPES.

#### 2.5.3.1. Software Architecture Context Level Diagrams

El diagrama de contexto representa el punto de partida de la arquitectura de software de la solución. En este nivel el objetivo es delimitar las fronteras de la aplicación, identificando a los actores y su interacción con el sistema propio del producto, así como también las conexiones de este con sistemas externos.

![context level](Imagenes/c4/context.png)

#### 2.5.3.2. Software Architecture Container Level Diagrams

EL diagrama de contenedores ilustra la organización interna de PowerSense. En este nivel se mapean la aplicación móvil, aasí como el Landing Page, el Backend y la base de datos. Del mismo modo que se realizan las conexiones entre estos elementos.

![container level](Imagenes/c4/container.png)

#### 2.5.3.3. Software Architecture Deployment Diagrams

Finalmente en el diagrama de despliegue se describe los servicios en la nuve que se planea utilizar para albergar fisicamente nuestra aplicación. 

![deployment level](Imagenes/c4/deployment.png)

## 2.6. Tactical-Level Domain-Driven Design


### 2.6.1. Bounded Context: Dashboard
#### 2.6.1.1. Domain Layer

Esta capa contiene el núcleo del negocio para el monitoreo y gestión de energía.

## Aggregate Roots

### Device
Representa al dispositivo IoT.

**Atributos:**
- id
- name
- status
- state

### EnergyConsumption
Representa el registro de consumo.

**Atributos:**
- id
- deviceId
- userId
- consumptionValue

## Value Objects

### EnergyPulse
Representa la cantidad de consumo de energía que se registra para el dispositivo.

### ThresholdValue
Límite de consumo establecido.

## Domain Services

### DeviceCommandService
Procesa comandos como:
- link device
- send device remote command

### EnergyQueryService
Gestiona la obtención de estadísticas.

## Business Policies

### Check Threshold Policy
Regla que evalúa si el consumo supera el límite para disparar el evento de exceso.

#### 2.6.1.2. Interface Layer
## Frontend (Mobile)

### DashboardView
UI principal para visualizar estadísticas y el consumo.

### DeviceStatusView
UI para ver el estado de los dispositivos.

## Backend (API)

### MonitoringController
Endpoints REST para ingesta de datos y control de dispositivos.

### DeviceResource / EnergyConsumptionResource
Representación de los datos que se envían al cliente.

#### 2.6.1.3. Application Layer

Coordina los casos de uso a través de comandos y eventos.

## Command Handlers

- DeliverEnergyConsumptionPulseHandler
- LinkDeviceHandler
- UnlinkDeviceHandler
- UpdateDeviceHandler
- SendDeviceRemoteCommandHandler
- ChangeDeviceStateHandler

## Event Handlers

- EnergyConsumptionPulseReceivedHandler
- EnergyConsumptionMeasuredHandler
- DeviceStateChangedHandler
- DeviceLinkedHandler
  
#### 2.6.1.4 Infrastructure Layer

En esta capa se implementan los medios de acceso a servicios externos y la persistencia de datos del dominio.  

**IoTGatewayAdapter:** Clase responsable de la comunicación técnica con los sensores y actuadores físicos, traduciendo señales de hardware a eventos de software.

**DeviceRepositoryImpl:** Implementación del repositorio definido en la capa de dominio que gestiona el acceso a la base de datos MySQL para el almacenamiento de dispositivos.  

**EnergyConsumptionRepositoryImpl:** Gestiona la persistencia de los registros históricos de consumo energético

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

Frontend:

![dashboard frontend component](Imagenes/c4/components/frontend/dashboard.png)

Backend:

![dashboard backend component](Imagenes/c4/components/backend/dashboard.png)

#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams

Como el backend trabaja sin una capa Domain para este Context, el lado de Frontend tampoco posee una capa Domain definida, por lo tanto ya no es necesario la visualización de un diagrama de clases para ambos casos.

##### 2.6.1.6.2. Bounded Context Database Design Diagram

(No se tienen entidades en la capa Domain para modelarlas en una base de datos)

### 2.6.2. Bounded Context: Sheduling
#### 2.6.2.1. Domain Layer

## Aggregate Root

### Schedule
Entidad principal que guarda el estado deseado para un dispositivo en un rango de tiempo.

**Atributos:**
- id
- deviceId
- startTime 
- endTime
- action (ON/OFF)
- isActive

## Value Objects

### TimeRange
Representa el bloque de tiempo de la programación.

### Trigger
El activador que dispara el cambio de estado.

## Domain Services

### ScheduleCommandService
Procesa las peticiones del usuario sobre sus calendarios.

## Business Policies

### Overlap Prevention
Regla de negocio que evita que dos programaciones para un mismo dispositivo tengan conflictos de horarios.

#### 2.6.2.2. Interface Layer

## Frontend (Mobile)

### ScheduleView
UI donde el usuario puede visualizar, crear y modificar sus calendarios inteligentes.

## Backend (API)

#### 2.6.2.3. Application Layer

Gestión de los flujos de trabajo de los horarios.

## Command Handlers

- CreateScheduleHandler
- UpdateScheduleHandler
- DeleteScheduleHandler
- ActivateScheduleHandler
- DeactivateScheduleHandler
- TriggerScheduleHandler

## Event Handlers

- ScheduleCreatedHandler
- ScheduleActivatedHandler
- ScheduleTriggeredHandler


#### 2.6.2.4 Infrastructure Layer

Esta capa soporta la persistencia de las reglas de automatización temporal.  

**ScheduleRepositoryImpl:** Implementación encargada de persistir los horarios de encendido y apagado en el servidor central.  

**ScheduleDao / ScheduleEntity:** Clases de persistencia local utilizando la biblioteca Room para permitir la visualización de calendarios sin conexión en la aplicación móvil.

#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams

Frontend:

![scheduling frontend component](Imagenes/c4/components/frontend/scheduling.png)

Backend:

![scheduling backend component](Imagenes/c4/components/backend/scheduling.png)

#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams

**Frontend:**

![scheduling frontend class diagram](Imagenes/class-diagrams/frontend/scheduling.png)

**Backend:**

![scheduling backend class diagram](Imagenes/class-diagrams/backend/scheduling.png)

##### 2.6.2.6.2. Bounded Context Database Design Diagram

![scheduling database diagram](Imagenes/db-diagrams/scheduling.png)


### 2.6.3. Bounded Context: Devices
#### 2.6.3.1. Domain Layer

Define el modelo estructural para las empresas y sus sedes dentro del sistema.

## Aggregate Root

### CompanyBranch
Representación virtual de un departamento de una MYPE donde se encuentran instalados uno o más dispositivos IoT.

**Atributos:**
- id
- companyId
- branchName
- location

## Domain Services

### EnterpriseCommandService
Gestiona la lógica para agregar, actualizar o eliminar sedes empresariales.

## Business Policies

### Uniqueness Rule
Regla de negocio que asegura que no puedan existir dos departamentos/sedes con el mismo nombre exacto dentro de una misma MYPE.

#### 2.6.3.2. Interface Layer

## Frontend (Mobile/Web)

### ConfigurationView
Interfaz de usuario donde el administrador de la MYPE gestiona las sedes de su empresa.

## Backend (API)

### EnterpriseController
Endpoints REST para administrar los departamentos de la compañía.

#### 2.6.3.3. Application Layer

Orquesta las operaciones sobre los departamentos de la empresa.

## Command Handlers

- AddCompanyBranchHandler
- UpdateCompanyBranchHandler
- DeleteCompanyBranchHandler

## Event Handlers

- CompanyBranchAddedHandler
- CompanyBranchUpdatedHandler
- CompanyBranchDeletedHandler


#### 2.6.3.4 Infrastructure Layer

**CompanyBranchRepositoryImpl:** Gestiona la persistencia de la estructura organizacional (sedes/departamentos) en la base de datos relacional.

**BranchMapper:** Clase encargada de la traducción entre las entidades de base de datos y los objetos de dominio.

#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

Frontend:

![devices frontend component](Imagenes/c4/components/frontend/devices.png)

Backend:

![devices backend component](Imagenes/c4/components/backend/devices.png)

#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams

**Frontend:**

![devices frontend class diagram](Imagenes/class-diagrams/frontend/devices.png)

**Backend:**

![devices backend class diagram](Imagenes/class-diagrams/backend/devices.png)

##### 2.6.3.6.2. Bounded Context Database Design Diagram

![devices database diagram](Imagenes/db-diagrams/devices.png)

### 2.6.4. Bounded Context: Reports
#### 2.6.4.1. Domain Layer

Núcleo que consolida métricas para el análisis de consumo.

## Aggregate Root

### Report
Documento digital que consolida las métricas de consumo, costos y ahorros en un periodo determinado.

**Atributos:**
- id
- userId
- periodStart
- periodEnd
- totalConsumption
- totalCost

## Value Objects

### ExportFormat
Representa el formato externo (ej. PDF o CSV) para uso administrativo.

## Domain Services

### ReportGenerationService
Servicio que agrupa las estadísticas consolidadas y construye el reporte.

## Business Policies

### Access Control
Regla que asegura que un usuario o MYPE solo pueda generar y exportar reportes de sus propios dispositivos o sedes.

#### 2.6.4.2. Interface Layer

## Frontend

### DashboardView
Vista que resume datos estadísticos rápidos.

### ReportsView
UI dedicada a la solicitud, visualización y exportación detallada de reportes.

## Backend

### ReportingController
Endpoints REST para solicitar la creación y exportación de reportes.

#### 2.6.4.3. Application Layer

## Command Handlers

- CreateReportHandler
- ExportReportHandler

## Event Handlers

- ReportCreatedHandler
- ReportExportedHandler

#### 2.6.4.4 Infrastructure Layer

**FileExportAdapter:** Adaptador encargado de la lógica técnica para transformar datos de dominio en archivos físicos exportables como PDF o CSV.

**ReportRepositoryImpl:** Repositorio para la gestión de metadatos de reportes generados anteriormente.

#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

Frontend:

![reports frontend component](Imagenes/c4/components/frontend/reports.png)

Backend:

![reports backend component](Imagenes/c4/components/backend/reports.png)

#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams

Como el backend trabaja sin una capa Domain para este Context, el lado de Frontend tampoco posee una capa Domain definida, por lo tanto ya no es necesario la visualización de un diagrama de clases para ambos casos.

##### 2.6.4.6.2. Bounded Context Database Design Diagram

(No se tienen entidades en la capa Domain para modelarlas en una base de datos)

### 2.6.5. Bounded Context: Alerts
#### 2.6.5.1. Domain Layer

Define las notificaciones críticas de seguridad y consumo del sistema.

## Aggregate Root

### Alert
Entidad principal de la notificación.

**Atributos:**
- id
- deviceId
- message
- timestamp
- isRead

## Value Objects / Context-specific terminology

### ThresholdExcess
Estado en el que el consumo registrado supera el límite definido por el usuario para un periodo o dispositivo.

### OverheatingWarning
Alerta crítica de seguridad que indica que un dispositivo ha superado su temperatura operativa segura.

## Business Policies

### Deduplication Rule
Regla de negocio que evita el envío de alertas duplicadas o spam.

> Ejemplo: no enviar 10 alertas de sobrecalentamiento por minuto al mismo dispositivo.

#### 2.6.5.2. Interface Layer

## Frontend

### AlertsView y DashboardView
Interfaz donde el usuario visualiza, lee y elimina las alertas entrantes.

## Backend

### AlertsController
Endpoints REST para consultar el historial de alertas, marcarlas como leídas o eliminarlas.


#### 2.6.5.3. Application Layer

## Command Handlers

- IssueAlertHandler (desencadenado internamente)
- DeleteAlertHandler (acción del usuario)

## Event Handlers

- AlertIssuedHandler
- AlertDeletedHandler

#### 2.6.5.4 Infrastructure Layer

**NotificationServiceAdapter:** Adaptador para la integración con servicios externos como Firebase Cloud Messaging para el envío de alertas push.  

**AlertRepositoryImpl:** Implementación que registra el historial de alertas emitidas y gestiona su estado de lectura en la base de datos.

#### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams

Frontend:

![alerts frontend component](Imagenes/c4/components/frontend/alerts.png)

Backend:

![alerts backend component](Imagenes/c4/components/backend/alerts.png)

#### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams

**Frontend:**

![alerts frontend class diagram](Imagenes/class-diagrams/frontend/alerts.png)

**Backend:**

![alerts backend class diagram](Imagenes/class-diagrams/backend/alerts.png)

##### 2.6.5.6.2. Bounded Context Database Design Diagram

![alerts database diagram](Imagenes/db-diagrams/alerts.png)


### 2.6.6. Bounded Context: Auth

> **Propósito:**  Gestión de identidad, autenticación del usuario.

#### 2.6.6.1. Domain Layer

**Propósitos:** 
- **User:** Información para la autenticación y verificación de roles.
- **Email:** Correo electrónico del usuario (debe ser un email válido).
- **Password:** Contraseña del usuario (se encripta al guardarse en la base de datos).
- **UserCommandService:** Repertorio de comandos que involucran la autenticación.
- **UserQueryService:** Repertorio de solicitudes que involucran al usuario

**A nivel de Frontend**
---
 **Aggregate Root**
 -  **User:**  `id: Int`, `email: String`, `passwordHash: String`, `name: String`, `avatarUrl: String`, `isActive: Boolean`

**Repositories**
- **UserRepository:**  `getUsers()`, `syncUsers()`

**A nivel de Backend**
---

 **Aggregate Root**
 -  **User:**  `id: UserId`, `email: Email`, `passwordHash: String`, `name: String`, `avatarUrl: String`, `isActive: Boolean`, `createdAt: LocalDateTime`, `UpdatedAt: LocalDateTime`
		
  **Entities**
	- *(No se tienen planteados Entities para este bounded context)*

 **Value Objects**
- **Email:** `value: String`, `validate()`, `getValue()`, `toString()`
- **Password:**  `value: String`,`validate()`, `getValue()`, 

**Domain Services**
- **UserCommandService:** `handle(RegisterUserCommand)`, `handle(UpdateUserProfileCommand)`
- **UserQueryService:** `handle(GetUserByIdQuery)`, `handle(GetUserByEmailQuery)`

#### 2.6.6.2. Interface Layer

**Propósitos:** 
- **LogInView:** UI para la vista de inicio de sesión.
- **RoleSelectionView:** UI para la vista de selección de rol de usuario.
- **SignUpView:** UI para la vista de registro de usuario.
- **IamNavHost:** Controlador de rutas de navegación para las diferentes vistas
- **IamRoutes:** Rutas pra cada vista del bounded context
- **AuthenticationController:** Endpoints para la información de autenticación.
- **UsersController:** Enpoints para información de usuario.
- **UserResourceFromEntityAssembler:** Mapeo de datos para la transformación de Entidad a Recurso.
-  **AutheticatedUserResourceFromEntityAssembler:** Mapeo de datos para la transformación de Entidad a Recurso.
- **AuthenticatedUserResource:** Recurso para el usuario autenticado.
-  **UserResource:** Recurso para el usuario.


**A nivel de Frontend (Presentation)**
---
**Views**
- **LogInView**
- **RoleSelectionView**
- **SignUpView**

**Navigation**
- **IamNavHost**
- **IamRoutes**

**A nivel de Backend (Interfaces)**
---

 **Controllers**
 -  **AuthenticationController** 
 - **UsersController**

**Assemblers**
- **UserResourceFromEntityAssembler**
- **AutheticatedUserResourceFromEntityAssembler**

**Resources**
- **AuthenticatedUserResource**
- **UserResource**

#### 2.6.6.3. Application Layer

**Propósitos:** 
- **UserCommandServiceImp:**  Implementación del servicio de comandos para el usuario.
- **UserQueryServiceImp:** Implementación del servicio de solicitudes para el usuario.

**A nivel de Backend**
---

 **CommandServices**
 -  **UserCommandServiceImp** 

**QueryServices**
- **UserQueryServiceImp**

#### 2.6.6.4 Infrastructure Layer

**Propósitos:** 
- **AppDatabase:**  Es el punto de acceso principal a la base de datos local (Room). Se encarga de proveer las instancias de los DAOs y gestionar la persistencia global de la aplicación.
- **UserDao:** Interfaz de Room que define las operaciones de base de datos (SQL) para el usuario
-  **UserEntity:** Representa la tabla "users" en la base de datos local. Es un objeto de datos  diseñado específicamente para ser entendido por el motor de persistencia (Room).
-  **UsersDto:** Data Transfer Object. Es la representación del usuario tal como viene en el JSON de la API externa (Retrofit). Protege al sistema de cambios en los nombres de campos del backend. 
-  **UserService:** Interfaz de Retrofit donde se definen los endpoints de red relacionados con el usuario.
-  **UserMapper:** Clase encargada de la traducción entre capas. Convierte, por ejemplo, un UsersDto (red) o un UserEntity (BD) en un objeto User de la capa de Dominio. 
-  **UserRepository:** Define el contrato (interfaz en Dominio) y la lógica (implementación en Infraestructura) para gestionar usuarios. Decide si los datos se obtienen de la API o del caché local.
-  **Resource:** Una clase sellada (Sealed Class) genérica que envuelve los datos para informar a la UI sobre el estado de una operación: Loading (cargando), Success (éxito) o Error (fallo).


**A nivel de Frontend (Data Layer)**
---
**Local**
- **AppDatabase**
- **UserDao**
- **UserEntity**

**Remote**
- **UsersDto**
- **UserService**

**Mapper**
- **UserMapper** 

**Repository**
- **UserRepository**
- **Resource**

**A nivel de Backend**
---

 **Repositories**
 -  **UserRepository** 


#### 2.6.6.5. Bounded Context Software Architecture Component Level Diagrams

Frontend:

![auth frontend component](Imagenes/c4/components/frontend/auth.png)

Backend:

![auth backend component](Imagenes/c4/components/backend/auth.png)

#### 2.6.6.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.6.6.1. Bounded Context Domain Layer Class Diagrams

**Frontend:**

![auth frontend class diagram](Imagenes/class-diagrams/frontend/auth.png)

**Backend:**

![auth backend class diagram](Imagenes/class-diagrams/backend/auth.png)

##### 2.6.6.6.2. Bounded Context Database Design Diagram

![auth database diagram](Imagenes/db-diagrams/auth.png)


# Capítulo III: Solution UI/UX Design

## 3.1. Product design
### 3.1.1. Style Guidelines
Estos lineamientos establecen la identidad visual de PowerSense, una plataforma diseñada para el monitoreo inteligente de energía. La estética busca transmitir eficiencia, modernidad y claridad, facilitando la interpretación de datos complejos a través de una interfaz limpia y profesional.
#### 3.1.1.1. General Style Guidelines
##### a. Branding
- Al buscar dar una identidad visual amigable e intuitiva sobre lo que ofrece PowerSenes, se decidio por hacer un logotipo de un foco verde con una hoja dentro, representando la energia con el foco y el ahorro con la hoja y el color verde.

![LogoChapter3](Imagenes/Logo.jpg)
##### b. Typography
- Se utilizan fuentes como Inter en todo el proyecto con diversos tamaños ya que su estilo sencillo transmite una vibra sencilla y minimalista.
##### c. Colors
- Se utilizan distintos colores, teniendo como principales el verde (48AF6A) y blanco. El verde porque representa el objetivo del aplicativo
### 3.1.2. Information Architecture
#### 3.1.2.1. Organization Systems
- **Jerarquía Visual:** En la aplicación móvil, el Dashboard prioriza el consumo total y el costo estimado en la parte superior, relegando el detalle de los dispositivos individuales a una sección inferior.
- **Organización Secuencial:** La Landing Page presenta la información en un flujo narrativo lógico: Inicio (Hero) -> Funcionamiento -> Planes de Servicio -> Casos de Éxito -> Contacto.
- **Organización Matricial:** Se utiliza en la sección de planes de la web para permitir al usuario comparar características y precios de forma paralela.

#### 3.1.2.2. Labeling Systems
Se aplican etiquetas bilingües claras y minimalistas para evitar confusiones en la navegación:
- **Navegación Web:** "Home", "How it works", "Plans" y "Success cases".
- **Acciones:** "Get Started", "Go to App" y "Learn More".
- **Dominio Energético:** "Total Consumption", "Smart Schedules", "Energy Usage" y "Peak Hours".

#### 3.1.2.3. SEO Tags and Meta Tags
La solución incluye metadatos esenciales para el posicionamiento y la accesibilidad:
- **Título:** PowerSense - Monitoreo Energético Inteligente.
- **Descripción:** Plataforma IoT para la gestión eficiente del consumo eléctrico y automatización del hogar.
- **Internacionalización:** Configuración dinámica de etiquetas de idioma para soportar inglés y español, mejorando el alcance en motores de búsqueda.

#### 3.1.2.4. Searching Systems
- **Navegación por Anclas:** Dada la estructura de una sola página del sitio web, se utilizan identificadores únicos para que el menú global dirija al usuario a secciones específicas instantáneamente.
- **Filtros de Datos:** En el módulo de reportes de la aplicación, se implementan filtros por nombre de dispositivo, categoría y rangos de fecha para facilitar la localización de datos históricos.

#### 3.1.2.5. Navigation Systems
- **Global Navigation:** Un encabezado persistente en la web permite el acceso constante a la propuesta de valor y al portal de la aplicación.
- **Bottom Navigation Bar:** La aplicación móvil utiliza una barra de navegación inferior con acceso a las cuatro áreas core: Home (Métricas), Devices (Control), Reports (Análisis) y Profile (Configuración).

### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe

<div style="text-align: center;">
  <img src="https://i.imgur.com/blwW1Ip.jpeg" width="90%"/>
  <img src="https://i.imgur.com/jUOEB7J.png" width="90%"/>
  <img src="https://i.imgur.com/swhzUFv.png" width="90%"/>
  <img src="https://i.imgur.com/0DGaWa2.png" width="90%"/>
  <img src="https://i.imgur.com/fipGm38.png" width="90%"/>
  <img src="https://i.imgur.com/I9K7Wr9.png" width="90%"/>
</div>

#### 3.1.3.2. Landing Page Mock-up

<div style="text-align: center;">
  <img src="https://i.imgur.com/D8VAjaU.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/KEk6XLo.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/g0cTqJL.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/DgkdQiF.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/bpD8zHJ.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/PAdL4Bk.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/EwpbPdB.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/JxfaWFt.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/RUGK2nz.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/qwgaMPn.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/nLC9u16.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/ljFAIBC.png" width="90%"/>
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/96cZc2a.png" width="90%"/>
</div>


### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes

![wireframe1](Imagenes/wireframes/wireframe-1.png)
![wireframe2](Imagenes/wireframes/wireframe-2.png)
![wireframe3](Imagenes/wireframes/wireframe-3.png)
![wireframe4](Imagenes/wireframes/wireframe-4.png)
![wireframe5](Imagenes/wireframes/wireframe-5.png)


#### 3.1.4.2. Mobile Applications Wireflow Diagrams

![wireflow 1](Imagenes/wireflow-diagrams/wireflow-1.jpg)

#### 3.1.4.3. Mobile Applications Mock-ups

- Dashboard
![MockupDash](Imagenes/mockups/mockup1.jpg)
- Dispositivos
![MockupDis](Imagenes/mockups/mockupDispo.jpg)
- Programar
![MockupProg](Imagenes/mockups/mockupProg.jpg)
- Reporte
![MockupRep](Imagenes/mockups/mockupRep.jpg)
- Alerta
![MockupAler](Imagenes/mockups/mockupAler.jpg)

#### 3.1.4.4. Mobile Applications User Flow Diagrams

#### 3.1.4.5. Mobile Applications Prototyping

# Capítulo IV: Product Implementation & Validation

## 4. Product Implementation & Validation

## 4.1. Software Configuration Management

Para garantizar la consistencia durante todo el ciclo de vida del proyecto PowerSense, nuestra startup SODA ha definido convenciones de código, gestión de versiones y configuración de entornos de desarrollo y despliegue.

### 4.1.1. Software Development Environment Configuration

Se especifican las herramientas utilizadas por los miembros del equipo para cubrir todas las actividades del ciclo de vida del software, cumpliendo con las restricciones del proyecto:

### Product UX/UI Design
- **Figma:** Herramienta para diseñar los Wireframes, Mock-ups y Prototipos navegables de la app móvil y Landing Page.  

- **UXPressia:** Utilizado para los artefactos de Needfinding (User Personas, Journey Maps).  

### Software Development
- **Android Studio:** IDE oficial para el desarrollo de la aplicación móvil nativa utilizando Kotlin.  

- **IntelliJ IDEA :** IDE para el desarrollo del Backend RESTful API utilizando Spring Boot (Java).  

- **MySQL Workbench :** Cliente para la gestión y modelado de la base de datos relacional MySQL.

### Software Documentation & API
- **Swagger :** Herramienta para documentar y probar los endpoints del Backend de PowerSense.  

### Software Deployment
- **Android Studio:** Utilizado para la distribución y validación de las versiones de prueba de la aplicación móvil.

- **Microsoft Azure:** Proveedor Cloud para el despliegue del Backend (Azure App Services) y base de datos (Azure Database for MySQL).

### 4.1.2. Source Code Management

El equipo de SODA utiliza Git como sistema de control de versiones centralizado en GitHub. 
Los repositorios oficiales del proyecto son:

- **Landing Page:**  
  https://github.com/Apps-Moviles-PowerSense/Landing-Page

- **Backend (Web Services):**  
  https://github.com/Apps-Moviles-PowerSense/Backend

- **Frontend Web Application:**  
  https://github.com/Apps-Moviles-PowerSense/Frontend

### Flujo de Trabajo (GitFlow)

Se aplico estrictamente el modelo GitFlow. Las ramas principales y convenciones son:

#### Ramas principales
- **main:** Contiene el informe de producción estable. Cada commit aquí es un release.
- **develop:** Rama de integración donde se unen las funcionalidades en desarrollo.

#### Ramas de apoyo
- **feature/<nombre-funcionalidad>:**  
  Creadas a partir de **develop** para desarrollar cada capitulo.

### 4.1.3. Source Code Style Guide & Conventions

Para asegurar la legibilidad, mantenibilidad e integración fluida del código entre los desarrolladores, hemos adoptado guías de estilo reconocidas para cada tecnología aplicada.

### Mobile (Kotlin)
- Se utiliza el lenguage de programación **Kotlin Style Guide** recomendada por Android.

### Backend (Java/Spring Boot)
- Se aplica la **Google Java Style Guide**.
- Los endpoints REST siguen una nomenclatura en inglés y sustantivos plurales.
  
### 4.1.4. Software Deployment Configuration

El despliegue de PowerSense se orquesta de la siguiente manera, garantizando la disponibilidad de todos los componentes:
- **Backend & Database:** El código de Spring Boot se despliega en Azure App Services, conectado a un servidor Azure Database for MySQL administrado.
- **Mobile Application:** Los APKs generados se despliegan para testing utilizando Firebase App Distribution, lo que permite a los evaluadores (usuarios de hogar y PYMES) descargar e interactuar con el prototipo final.
- **Landing Page:** Los archivos estáticos se despliegan automáticamente desde GitHub utilizando servicios como GitHub Pages o Vercel.


## 4.2. Landing Page & Mobile Application Implementation

### 4.2.1. Sprint 1

En este primer Sprint, el equipo se enfocó en el desarrollo y despliegue del Landing Page estático para presentar el modelo de negocio al público, así como en la configuración inicial de la arquitectura del Backend y la implementación de los servicios base de seguridad y autenticación.

#### 4.2.1.1. Sprint Planning 1

A continuación, se resumen los detalles y objetivos definidos durante la reunión de planificación del Sprint 1.

| Campo | Descripción |
|-------|-------------|
| **Sprint #** | Sprint 1 |
| **Date** | 2026-04-26 |
| **Time** | 10:00 AM |
| **Location** | Microsoft Teams (Reunión Virtual) |
| **Prepared By** | Pastor Napa, Juan Carlos |
| **Attendees** | Aquino Solorzano, Daniel / Lagos Rivera, Kael / Ojanama Abanto, Johnny / Pastor Napa, Juan Carlos / Pelaez Vargas, Giuliano |
| **Sprint n – 1 Review Summary** | N/A  |
| **Sprint n – 1 Retrospective Summary** | N/A |
|  Sprint Goal & User Stories |        |
| Sprint Goal | Nuestro objetivo es lanzar la página de inicio estática principal y establecer los puntos de acceso básicos para la autenticación y el registro.Creemos que esto brinda visibilidad temprana del producto a potenciales usuarios de Home y PYME, y una base segura para la aplicación.Esto se confirmará cuando los visitantes puedan navegar por las secciones de la página de inicio y los usuarios puedan registrarse correctamente y generar un token JWT válido a través de la API.
| Sprint Velocity |  20 Story Points |
| Sum of Story Points | HU1,HU2,HU3,HU4,HU7,HU35 |

#### 4.2.1.2. Sprint Backlog 1

El siguiente cuadro detalla las tareas asignadas para cumplir con el Sprint Goal.

| User Story | Work-Item / Task | Description | Estimation (Hours) | Assigned To |
|---|---|---|---|---|
| **HU1 - Información general del producto** | **TS1.1 - Maquetación HTML/CSS Hero Section** | Desarrollar la estructura base y estilos de la sección principal del Landing Page. | 4 | Pastor, Juan Carlos |
| **HU2 - Casos de éxito** | **TS2.1 - Diseño UI/UX y HTML de Casos de Éxito** | Implementar la sección de testimonios de hogares. | 3 | Ojanama, Johnny |
| **HU3 - Comparativa de planes** | **TS3.1 - Implementar Pricing Table** | Construir la tabla responsiva comparando los planes. | 5 | Pelaez, Giuliano |
| **HU4 - Contacto** | **TS4.1 - Formulario de contacto estático** | Crear el formulario HTML de contacto con validaciones JS. | 3 | Lagos, Kael |
| **HU5 - Registro de cuenta** | **TS5.1 - UI Móvil de Registro** | Implementar la pantalla de registro en Android con Kotlin. | 6 | Pastor, Juan Carlos |
| **HU7 - Inicio de sesión** | **TS7.1 - UI Móvil de Login** | Implementar la pantalla de inicio de sesión en Android. | 5 | Lagos, Kael |
| **HU35 - Endpoint de autenticación** | **TS35.1 - Configurar Spring Security y JWT** | Configurar el backend para generar y validar tokens JWT y registrar usuarios. | 8 | Aquino, Daniel |

#### 4.2.1.3. Development Evidence for Sprint Review

#### 4.2.1.4. Testing Suite Evidence for Sprint Review

#### 4.2.1.5. Execution Evidence for Sprint Review

Durante este Sprint se alcanzó el despliegue del Landing Page con sus secciones informativas y el desarrollo de las pantallas iniciales en la app móvil.

#### 4.2.1.6. Services Documentation Evidence for Sprint Review

| Endpoint | Verbo HTTP | Parámetros / Request Body | Response de Ejemplo |
|---|---|---|---|
| `/api/auth/login` | POST | `{"email": "...", "password": "..."}` | `200 OK: {"token": "eyJhbGci..."}` |
| `/api/auth/register` | POST | `{"firstName": "...", "email": "...", "password": "..."}` | `201 Created: {"message": "User registered"}` |
| `/api/auth/me` | GET | Token JWT en Authorization Header | `200 OK: {"id": 1, "firstName": "Juan", "email": "juan@example.com"}` |
| `/api/auth/profile` | PUT | `{"firstName": "...", "lastName": "...", "phone": "..."}` + JWT | `200 OK: {"id": 1, "firstName": "Juan Updated"}` |
| `/api/auth/verify` | GET | Token JWT en Authorization Header | `200 OK: {"valid": true}` |
| `/api/auth/refresh` | POST | Token JWT en Authorization Header | `200 OK: {"token": "new_jwt_token..."}` |
| `/api/auth/logout` | POST | Token JWT en Authorization Header | `200 OK` |

#### 4.2.1.7. Software Deployment Evidence for Sprint Review

![deplyment evidence sprint 1](Imagenes/deployment-evidence-sprint-1.png)

#### 4.2.1.8. Team Collaboration Insights during Sprint

## 4.3. Validation Interviews

En está sección se detalla la experiencia de los usuarios al momento de usar la aplicación mediante el registro de entrevistas.

### 4.3.1. Diseño de Entrevistas

Se llevaron a cabo entrevistas que buscan saber sus opiniones sobre como funciona la aplicación y si la Interfaz les fue sencilla de entender.

Para el diseño de entrevistas se consideraron los siguientes aspectos:

### Objetivo de la entrevista

Validar la usabilidad, claridad y funcionalidad de la aplicación PowerSense en distintos perfiles de usuario, evaluando si la visualización de datos de consumo y las herramientas de automatización resultan intuitivas y útiles para reducir el gasto energético.

### Elementos de la validación

- **Aceptación y Usabilidad del Cliente (Frontend):** Evalúa la claridad de las preguntas, alertas e interfaz de usuario. Asegura que la navegación responda al contenido relevante del problema (control y lectura de kWh) sin generar confusión.
- **Factibilidad Técnica (IoT & IA):** Comprueba que los sensores midan el consumo en tiempo real sin latencia crítica y que los actuadores respondan correctamente al encendido/apagado remoto. Asimismo, valida que los algoritmos de IA devuelvan recomendaciones lógicas y coherentes.
- **Viabilidad del Negocio (Retorno de Inversión):** Mide si el valor percibido por el ahorro potencial (los ~S/ 50 mensuales calculados) justifica la adquisición o alquiler del hardware por parte de hogares y PYMEs.
- **Aplicación:** Interacción guiada por el prototipo móvil para evaluar la navegación, la interpretación de las alertas de consumo energético y la facilidad para controlar remotamente los dispositivos IoT conectados.

### User Flows a validar

### Para usuarios residenciales (Hogares): 

- Monitoreo en tiempo real: Comprobación de si comprenden las métricas de gasto en kWh y soles.
- Control remoto: Simulación de apagado de dispositivos en espera y configuración de horarios.

### Para usuarios comerciales (PYMEs):

- Dashboard de gestión: Evaluación de la claridad de los reportes de picos de consumo.
- Recomendaciones IA: Verificación de si encuentran y entienden los consejos personalizados de ahorro.

### Formato de registro de la entrevista

### Datos del entrevistado:

- Nombre y apellidos
- Edad
- Distrito de residencia
- Rol (hogar o PYME)
- Dispositivo utilizado

### Preguntas aplicadas

1. ¿Qué te pareció la aplicación PowerSense en general?
2. ¿Te resultó fácil comprender cuánta energía y dinero estás gastando actualmente?
3. ¿Pudiste configurar el encendido o apagado remoto de tus aparatos sin problemas?
4. ¿Fueron claras y útiles las recomendaciones de la Inteligencia Artificial para ahorrar?
5. ¿Qué cambiarías de los gráficos o de la organización de la aplicación?
6. ¿Recomendarías esta solución para optimizar el gasto eléctrico en otros hogares o negocios?

### 4.3.2. Registro de Entrevistas

- ### Segmento objetivo 1 (Hogares)

Entrevista 1 (Vitaly Baca) Inicio: 00:00 - Fin: 5:40 - Duración: 5:40
<p align="center">
  <img src="Imagenes/Imagen_entrevista7.png" alt="Imagen_entrevista7" />
</p>

- Nombre: Vitaly Baca
- Edad: 22 años
- Distrito de residencia: Lurin

Resumen de la entrevista: En esta entrevista realizada a Vitaly Baca, de 22 años y residente del distrito de Lurin, nos comenta su experiencia utilizando la aplicación de PowerSense. 

Entre los aspectos que se le cuestionó fueron apartados como su experiencia usandolo, la facilidad que tuvo para comprender el funcionamiento de la aplicación al mostrarle el consumo electrico asi como el total en soles que supone, si pudo administrar el apagado como el encedido de sus dispositivos vinculados a la app, la utilidad de las recomendaciones dadas por la app, los cambios que podria realizar y la posibilidad de recomendar está aplicación a conocidos suyos que les permita controlar su consumo eléctrico.

Finaliza expresando satisfacción por ver una solución a una problematica que muchas personas suelen pasar por alto ya sea por ignorancia o incapacidad de hacer algo para averiguar los detalles.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQB8vtipl-3YRYWigama3ImOAQUb7ZvhSd3FFo1w6muUfaw?e=tsZueg&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

- ### Segmento objetivo 2 (Negocios)

Entrevista 1 (Mario Augusto) Inicio: 00:00 - Fin: 4:31 - Duración: 4:31
<p align="center">
  <img src="Imagenes/Imagen_entrevista8.png" alt="Imagen_entrevista7" />
</p>

- Nombre: Mario Augusto
- Edad: 39 años
- Distrito de residencia: Pueblo Libre

Resumen de la entrevista: En esta entrevista realizada a Mario Augusto, de 39 años y residente del distrito de Pueblo Libre, nos comenta su experiencia utilizando la aplicación de PowerSense.

Nos dio su opinión respecto a cosas como la interfaz, el despliegue de los datos como el consumo eléctrico que hay en la empresa y las recomendaciones que brindaba la app. 
Aunque tambien llegó a señalar ciertas carencias como la falta de una opción para desplegar los resultados del consumo eléctrico mediante una hoja de excel, el tamaño de letra que dificulta un poco la comprensión y la falta de una pantalla de inicio que de la bienvenida a la app siendo algo lamentable a sus ojos.

Finaliza expresando optimismo y asombro por las caracteristicas principales que presenta la app y no duda en que su desarrollo será un exito comentando tambien su disposición a compartirlo con amigos asi como a otros negocios donde el consumo eléctrico debe ser medido a detalle.

Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210104_upc_edu_pe/IQDTD3IZkUNRQJGgV0LuAW6CAYTJ_1LcdZw1ZlpD99VCd_4?e=cmsrqu&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

### 4.3.3. Evaluaciones según heurísticas
A partir de las entrevistas realizadas es posible elaborar una evaluación heurística relacionando los comentarios de los usuarios con las 10 heurísticas de usabilidad de Jakob Nielsen.

| Heurística de Nielsen | Evidencia de las entrevistas | Evaluación | Severidad |
|---|---|---|---|
| **Visibilidad del estado del sistema** | Ambos usuarios tardaron un poco en comprender el consumo eléctrico y el costo en soles mostrado por la aplicación. | La información principal es clara y visible, sin embargo hay usuarios que tardan un poco en comprenderlo. | 1 - Problema menor |
| **Correspondencia entre el sistema y el mundo real** | Los usuarios entendieron fácilmente conceptos como consumo, costo y control de dispositivos. | Se utiliza un lenguaje familiar para el usuario. | 0 - Sin problemas |
| **Control y libertad del usuario** | Vitaly pudo encender y apagar los dispositivos vinculados sin dificultades. | La aplicación brinda control sobre las acciones principales. | 0 - Sin problemas |
| **Consistencia y estándares** | No se reportaron inconsistencias en navegación o funcionamiento. | La interfaz mantiene un comportamiento uniforme. | 0 - Sin problemas |
| **Prevención de errores** | No se identificaron errores durante el uso del prototipo. | No existen evidencias suficientes para detectar problemas. | 0 - Sin problemas |
| **Reconocimiento antes que recuerdo** | La visualización del consumo y las recomendaciones tardaron en ser comprendidas. | La información presentada en las recomendaciones debe ser más intuitiva y fácil de identificar. | 2 - Problema moderado |
| **Flexibilidad y eficiencia de uso** | Mario sugirió incorporar la exportación de resultados a Excel para facilitar el análisis del consumo empresarial. | Falta una función avanzada útil para usuarios de negocios. | 3 - Problema importante |
| **Diseño estético y minimalista** | Mario indicó que el tamaño de la letra dificulta parcialmente la lectura y que falta una pantalla de bienvenida. | Existen oportunidades de mejora en la presentación visual. | 2 - Problema moderado |
| **Ayudar a reconocer y recuperarse de errores** | No se reportaron situaciones de error durante las pruebas. | No se identificaron inconvenientes en este aspecto. | 0 - Sin problemas |
| **Ayuda y documentación** | Ambos usuarios pudieron utilizar la aplicación sin requerir instrucciones adicionales, aunque una pantalla inicial podría orientar mejor a nuevos usuarios. | Sería conveniente añadir una guía o introducción rápida. | 2 - Problema moderado |
# Bibliografía
- Sierra Praeli, Y. (28 de abril de 2024). Territorios contaminados: la transición energética no avanza en la Amazonía de Perú. Mongabay Latam.
  (https://es.mongabay.com/2024/04/territorios-contaminados-transicion-energetica-no-avanza-amazonia-peru/)
- AutoSolar Perú. (s. f.). Consumo energético familiar en Perú.
  (https://autosolar.pe/ahorro-de-energia/consumo-energetico-familiar-en-peru)

# Anexos
- Organización en Github: https://github.com/Apps-Moviles-PowerSense
- Landing desplegado: https://powersenselanding-3mxrjrrtg-johnnygz41s-projects.vercel.app
- Backend Desplegado: http://34.28.139.66:8080/swagger-ui/index.html 
- Report: https://github.com/Apps-Moviles-PowerSense/Report
- Landing: https://github.com/Apps-Moviles-PowerSense/Landing-Page
- Frontend Kotlin: https://github.com/Apps-Moviles-PowerSense/Frontend-Kotlin
- Frontend Flutter: https://github.com/Apps-Moviles-PowerSense/Frontend---Flutter
- Backend: https://github.com/Apps-Moviles-PowerSense/Backend
- Swagger: http://34.28.139.66:8080/swagger-ui/index.html
- Figma: https://www.figma.com/design/gpIV82TEIiyByP47cZEcAG/Figma-basics?node-id=1825-2&t=YWosvdlbsaAKIkGm-1

usuario prueba kotlin: test@test.com
constraseña prueba kotlin: 123456


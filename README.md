# **Informe Trabajo Final**

<p align="center">
  <img src="Imagenes/LogoUPC.png" alt="Logo de la UPC" />
</p>

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center"><strong>Ingeniería de Software</strong>
<br>Aplicaciones Móviles <br>
<strong>Profesor: Jorge Luis Mayta Guillermo</strong> </p>

<h2 align="center">INFORME</h2>

<h3 align="center">Nombre del Startup: PowerSense</h3>
<p align="center"><strong>Nombre del producto: PowerSense</strong></p>

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

</div>

## Registro de versiones del informe
| Versión | Fecha | Autor | Descripción de modificación |
|:---:|:---:|:---:|:---|
| 1.0 | 24.04.2025 | Todo el grupo  | Elaboración de los primeros dos capítulos del informe. |
| 1.1 |  |  |  |


## Project Report Collaboration Insights
[Repositorio de documentacion](https://github.com/Apps-Moviles-PowerSense/Report) <br>

[Repositorio del Landing Page](https://github.com/Apps-Moviles-PowerSense/Landing-Page) <br>

[Repositorio del Fronted](https://github.com/Apps-Moviles-PowerSense/Frontend)

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
    - 2.6. [Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)

# Student Outcome
| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software** | **Daniel Aquino** <br> **AV1:** Sesiones de Event Storming para identificar los eventos del dominio, comandos y actores clave. Se delimitaron las fronteras lógicas del sistema, analizando la responsabilidad de cada contexto. Se diseño la interacción detallada entre los agregados y servicios mediante el modelado de flujo de mensajes. Se establecieron los contratos de integración entre los contextos identificados. <br><br> **Giuliano Peláez** <br> **AV1:** Investigación de métricas de consumo eléctrico y normativas de OSINERGMIN. Aplicación del proceso Lean UX para definir el Problem Statement y los Assumptions. Redacción de las Hypothesis Statements para validar el impacto de la solución IoT.<br><br> **Johnny Ojanama**<br> **AV1:** Investigación sobre las distintas competencias que presenta el startup y su análisis competitivo para poder ver sus pros, contras, fuerzas y debilidades. Aplicacion del proceso Lean UX para diseñar y completar el Lean UX Canvas. <br><br> **Kael Lagos** <br> **AV1:** Supervisión del cumplimiento de las indicaciones dadas en el aula virtual, corrección de la estructura inicial del informe, grabación de una de las primeras entrevistas, definición de los segmentos que abarcaremos y diseño de las preguntas para las entrevistas.<br><br> **Juan Carlos Pastor** <br> **AV1:** Supervisión del cumplimiento dentro del grupo, ideas, organizacion, envio, direccion y control. Diseño de web, y aplicacion movil, compliendo heuristicas. | La actualización de los datos e información tomados en cuenta para el desarrollo del proyecto requiere de una extensa investigación tomando en cuenta aspectos como la problemática, las posibles soluciones, las caracteristicas que debe tener el proyecto para cumplir con las espectativas de los usuarios ya sea a nivel de hogar o en un negocio. |
|  **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software** | **Daniel Aquino** <br> **AV1:** Diagramas de Big Picture Event Storming. Design Level Event Storming. Candidate Context Discovery. Bounded Context Canvases. Domain Message Flow Modeling. Context Mapping. Software Architecture Context Level Diagrams. Software Architecture Container Level Diagrams. Software Architecture Deployment Diagrams. <br><br>**Kael Lagos** <br> **AV1:** Actualización del contenido del proyecto tomando en cuenta la nueva metodología del curso asi como la estructura que debe tener. Documentación de hipotesis ante las problematicas. Revisión de los videos pertenecientes a las entrevistas asegurandose de que la información sea útil y precisa para el desarrollo de los demás puntos del informe referente al proyecto. <br><br> **Giuliano Peláez** <br> **AV1:** Estructuración del Startup Profile, definiendo la misión y visión enfocadas en la eficiencia energética. Documentación de antecedentes y problemática del sector energético en Lima Metropolitana para sustentar la viabilidad del proyecto.<br><br> **Johnny Ojanama**<br> **AV1:** Creación del esqueleto base del proyecto. Lean UX Canvas. Respondiendo y definiendo las 5W y 2 H. Análisis competitivo y Estrategias y tácticas frente a competidores.<br><br> **Juan Carlos Pastor**<br> **AV1:** Creacion y organizacion de archivos y diseño grafico.|  |

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo 

| Foto                                                                                                                             | Alumno                             | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|----------------------------------------------------------------------------------------------------------------------------------|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Foto aqui| Aquino Solorzano, Daniel Jonatan | Descripción aqui                                                                                                                                                                                                                                                                                                                                                |
| Foto aqui| Ojanama Abanto, Johnny Alexander       | Descripción aqui |
| ![Kael_Foto](Imagenes/Kael_Foto.jpg)                                                                                             | Kael Valentino, Lagos Rivera | Me llamo Kael Lagos, estudio en la UPC de Monterrico. Tengo muchas ganas de aprender, me considero una persona responsable que busca aprender de sus errores cada vez que puede y tambien me considero alguien que se centra en los detalles. Me comprometo a ayudar a mis compañeros para la elaboración de nuestro trabajo que nos pueda asegurar una buena nota al final.                                                                                                                                                                  |

## 1.2. Solution Profile 
### 1.2.1. Antecedentes y Problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos Objetivo

### Hogares limeños con recibo de luz

En Lima Metropolitana, casi la totalidad de hogares cuenta con acceso a electricidad (97.6%), lo que los convierte en un segmento consolidado que paga recibo de luz regularmente (INEI, 2021). El jefe de hogar suele ser adulto de mediana edad (~50 años), con un nivel educativo mayor al promedio nacional: cerca del 49% de la población de 18 a 64 años alcanzó educación superior (INEI, 2022). La estructura socioeconómica limeña muestra predominio de la clase media (NSE C: 48% de los hogares), mientras que los hogares promedian 3.5 miembros (APEIM, 2022). En cuanto al consumo energético, Lima registra una mediana de 190 kWh/mes, casi el doble del promedio nacional, lo que se traduce en recibos entre S/60 y S/120 mensuales, dependiendo del equipamiento eléctrico del hogar (Osinergmin, 2023).

### PYMEs limeñas

Lima concentra cerca del 42% de todas las empresas del país, es decir, alrededor de 1.4 millones de unidades económicas, de las cuales más del 99% son micro y pequeñas (SUNAT, 2024). Estas empresas emplean en promedio de 2 a 3 trabajadores y se concentran principalmente en comercio minorista (45%) y servicios (42%), siendo menos frecuente la manufactura (9%) (INEI, 2022). El consumo eléctrico representa un costo fijo relevante: un pequeño negocio limeño puede gastar entre 200 y 300 kWh/mes, lo que equivale a recibos de S/150 a S/250. Estos costos impactan directamente en la rentabilidad, ya que las tarifas comerciales (BT5) no reciben subsidio, lo que hace más crítica la gestión eficiente de la energía en este segmento (Osinergmin, 2023).

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. Big Picture EventStorming
### 2.3.6. Ubiquitous Language
## 2.4. Requirements specification
### 2.4.1. User Stories
### 2.4.2. Impact Mapping
### 2.4.3. Product Backlog
## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams
## 2.6. Tactical-Level Domain-Driven Design

# **Informe Trabajo Final**

<p align="center">
  <img src="Imagenes/LogoUPC.png" alt="Logo de la UPC" />
</p>

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center"><strong>Ingeniería de Software</strong>
<br>Aplicaciones Móviles <br>
<strong>Profesor: Jorge Luis Mayta Guillermo</strong> </p>

<h2 align="center">INFORME</h2>

<h3 align="center">Nombre del Startup: Nombre aqui</h3>
<p align="center"><strong>Nombre del producto: Nombre aqui</strong></p>

<p align="center"><strong>Ciclo académico: 2026-01</strong></p>

<p align="center"><strong>Código del curso: 1ACC0238</strong></p>

<p align="center"><strong>NRC del curso: 2610</strong></p>

<br>

## Integrantes
| Código | Apellidos y Nombres | Carrera |
| :--- | :--- | :--- |
| U202217678 | Aquino Solorzano, Daniel Jonatan | Ingeniería de Software |
| U202210104 | Lagos Rivera, Kael Valentino | Ingeniería de Software |
| U20231F412 | Ojanama Abanto, Johnny Alexander | Ingeniería de Software |
| U202217288 | Pastor Napa, Juan Carlos | Ingeniería de Software |
| U20221E121 | Peláez Vargas, Giuliano Angel | Ingeniería de Software |

<br>

### **Fecha:** Abril, 2026

</div>

## Registro de versiones del informe
| Versión | Fecha | Autor | Descripción de modificación |
|:---:|:---:|:---:|:---|
| 1.0 | --.04.2025 | Todo el grupo  | Elaboración de los primeros puntos del informe |
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
        - 2.5.2. [Context Mapping](#252-context-mapping)
        - 2.5.3. [Software Architecture](#253-software-architecture)
      		- 2.5.3.1. [Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
        	- 2.5.3.2. [Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
         	- 2.5.3.3. [Software Architecture Deployment Level Diagrams](#2532-software-architecture-container-level-diagrams)
    - 2.6. [Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)

# Student Outcome
| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
|  |   |
|  |   |
---

# Capítulo I: Introducción
## 1.1. Startup Profile

Nuestra startup, con origen en Perú, ofrece una solución tecnológica de vanguardia para que hogares y pequeñas empresas gestionen de manera activa su consumo energético, logrando así una significativa reducción de costos y de su huella de carbono.

Hemos desarrollado un sistema inteligente basado en el Internet de las Cosas (IoT). Este integra sensores y actuadores que permiten:
-   Monitoreo en tiempo real del gasto de energía.   
-   Control remoto de dispositivos eléctricos.
La plataforma incorpora funciones de Inteligencia Artificial (IA) que analizan los patrones de uso, identifican ineficiencias y generan recomendaciones personalizadas para optimizar el consumo. Esto promueve un estilo de vida más sostenible y consciente con el medio ambiente.
  
**Visión y Misión**

-   **Visión:** Ser el referente líder en Sudamérica en soluciones de eficiencia energética inteligente, impulsando la transformación de las ciudades hacia modelos más sostenibles y resilientes.

- **Misión:** Empoderar a nuestros usuarios, brindándoles herramientas accesibles y sencillas que les permitan visualizar su consumo instantáneamente, programar el funcionamiento de sus dispositivos y adoptar hábitos responsables. Buscamos impactar positivamente en la economía doméstica, en el crecimiento empresarial y en la conservación del entorno natural, expandiendo nuestra cobertura desde Perú hacia toda la región.
  
### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo 

| Foto                                                                                                                             | Alumno                             | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|----------------------------------------------------------------------------------------------------------------------------------|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Foto aqui| Aquino Solorzano, Daniel Jonatan | Descripción aqui                                                                                                                                                                                                                                                                                                                                                |
| ![Johnny_Foto](Imagenes/Johnny.png)| Ojanama Abanto, Johnny Alexander       | Me llamo Johnny Ojanama, soy estudiante de la UPC con 19 años cursando el 6to ciclo. Me considero alguien responsable y cooperativo, si el equipo necesita de mi ayuda estare mas que dispuesto a ayudar para que el trabajo logre completarse. |
| ![Kael_Foto](Imagenes/Kael_Foto.jpg)                                                                                             | Kael Valentino, Lagos Rivera | Me llamo Kael Lagos, estudio en la UPC de Monterrico. Tengo muchas ganas de aprender, me considero una persona responsable que busca aprender de sus errores cada vez que puede y tambien me considero alguien que se centra en los detalles. Me comprometo a ayudar a mis compañeros para la elaboración de nuestro trabajo que nos pueda asegurar una buena nota al final.                                                                                                                                                                  |
| Foto aqui                                                                                   | Pastor Napa, Juan Carlos    | Descripción aqui                                                                                                                                                                                           |
| ![Giuliano Foto](Imagenes/Giuliano.png) | Peláez Vargas, Giuliano Angel    | Me llamo Giuliano Peláez, soy estudiante de 6to cilo de la carrera Ingenieria de Software.Me considero una persona empatica, solidaria y puedo integrarme facilmente a equipos de trabajo y entender las necesidades de mis compañero aparte soy muy enfocado en cumplir los objetivos del proyecto con calidad y poseo una gran proactividad para aprender nuevas cosas.                                                                                                                                                                                                                                                                                                               |

## 1.2. Solution Profile 
### 1.2.1. Antecedentes y Problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos Objetivo

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


# Bibliografía
- Sierra Praeli, Y. (28 de abril de 2024). Territorios contaminados: la transición energética no avanza en la Amazonía de Perú. Mongabay Latam.
  (https://es.mongabay.com/2024/04/territorios-contaminados-transicion-energetica-no-avanza-amazonia-peru/)
- AutoSolar Perú. (s. f.). Consumo energético familiar en Perú.
  (https://autosolar.pe/ahorro-de-energia/consumo-energetico-familiar-en-peru)

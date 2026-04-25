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
| U20221E121 | Pelaez Vargas, Giuliano Angel | Ingeniería de Software |

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
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software** | <br>**Daniel Aquino AV1:**<br> Sesiones de Event Storming para identificar los eventos del dominio, comandos y actores clave. Se delimitaron las fronteras lógicas del sistema, analizando la responsabilidad de cada contexto. Se diseño la interacción detallada entre los agregados y servicios mediante el modelado de flujo de mensajes. Se establecieron los contratos de integración entre los contextos identificados.<br> <br> **Giuliano Peláez AV1:** <br>Investigación de métricas de consumo eléctrico y normativas de OSINERGMIN. Aplicación del proceso Lean UX para definir el Problem Statement y los Assumptions. Redacción de las Hypothesis Statements para validar el impacto de la solución IoT. <br> <br> **Johnny Ojanama AV1:** <br> Investigación sobre las distintas competencias que presenta el startup y su análisis competitivo para poder ver sus pros, contras, fuerzas y debilidades. Aplicación del proceso Lean UX para diseñar y completar el Lean UX Canvas. <br> <br> **Kael Lagos AV1:** <br> Supervisión del cumplimiento de las indicaciones dadas en el aula virtual, corrección de la estructura inicial del informe, grabación de una de las primeras entrevistas, definición de los segmentos que abarcaremos y diseño de las preguntas para las entrevistas. <br> <br> **Juan Carlos Pastor AV1:** <br> Supervisión del cumplimiento dentro del grupo, ideas, organización, envio, dirección y control. Diseño de web, y aplicación móvil, cumpliendo heurísticas. <br> | La actualización de los datos e información tomados en cuenta para el desarrollo del proyecto requiere de una extensa investigación tomando en cuenta aspectos como la problemática, las posibles soluciones, las caracteristicas que debe tener el proyecto para cumplir con las expectativas de los usuarios ya sea a nivel de hogar o en un negocio.
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software** |  <br>**Daniel Aquino AV1:**<br> SDiagramas de Big Picture Event Storming. Design Level Event Storming. Candidate Context Discovery. Bounded Context Canvases. Domain Message Flow Modeling. Context Mapping. Software Architecture Context Level Diagrams. Software Architecture Container Level Diagrams. Software Architecture Deployment Diagram.<br> <br> **Giuliano Peláez AV1:** <br> Estructuración del Startup Profile, definiendo la misión y visión enfocadas en la eficiencia energética. Documentación de antecedentes y problemática del sector energético en Lima Metropolitana para sustentar la viabilidad del proyecto. <br> <br> **Johnny Ojanama AV1:** <br> Creación del esqueleto base del proyecto. Lean UX Canvas. Respondiendo y definiendo las 5W y 2 H. Análisis competitivo y Estrategias y tácticas frente a competidores. <br> <br> **Kael Lagos AV1:** <br> Actualización del contenido del proyecto tomando en cuenta la nueva metodología del curso asi como la estructura que debe tener. Documentación de hipotesis ante las problematicas. Revisión de los videos pertenecientes a las entrevistas asegurandose de que la información sea útil y precisa para el desarrollo de los demás puntos del informe referente al proyecto. <br> <br> **Juan Carlos Pastor AV1:** <br> Creación y organización de archivos y diseño gráfico.  |La elaboración de este primer avance representa la etapa de planteamiento del problema así como de las posibles soluciones que pueden a ver con tal de resolver la problematica, en ese sentido debemos plantear correctamente la situación para así tener una buena base con la cual empezar a desarrollar lo demás.|
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

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
| ![Daniel_Foto](Imagenes/Daniel.png)| Aquino Solorzano, Daniel Jonatan | Estudio actualmente la carrera de Ingeniería de Software. Me considero una persona responsable con sus trabajos y puntual en las entregas de estos. Tengo conocimientos técnicos en programación en lenguajes como C++ y Java. Tengo experiencia en desarrollo de aplicaciones Web según distintos enfoques y herramientas, centranndome más en el Backend                                                                                                                                                                                                                                                                                                                                                |
| ![Johnny_Foto](Imagenes/Johnny.png)| Ojanama Abanto, Johnny Alexander       | Me llamo Johnny Ojanama, soy estudiante de la UPC con 19 años cursando el 6to ciclo. Me considero alguien responsable y cooperativo, si el equipo necesita de mi ayuda estare mas que dispuesto a ayudar para que el trabajo logre completarse. |
| ![Kael_Foto](Imagenes/Kael_Foto.jpg)                                                                                             | Kael Valentino, Lagos Rivera | Me llamo Kael Lagos, estudio en la UPC de Monterrico. Tengo muchas ganas de aprender, me considero una persona responsable que busca aprender de sus errores cada vez que puede y tambien me considero alguien que se centra en los detalles. Me comprometo a ayudar a mis compañeros para la elaboración de nuestro trabajo que nos pueda asegurar una buena nota al final.                                                                                                                                                                  |
| Foto aqui                                                                                   | Pastor Napa, Juan Carlos    | Descripción aqui                                                                                                                                                                                           |
| ![Giuliano Foto](Imagenes/Giuliano.png) | Peláez Vargas, Giuliano Angel    | Me llamo Giuliano Peláez, soy estudiante de 6to cilo de la carrera Ingenieria de Software.Me considero una persona empatica, solidaria y puedo integrarme facilmente a equipos de trabajo y entender las necesidades de mis compañero aparte soy muy enfocado en cumplir los objetivos del proyecto con calidad y poseo una gran proactividad para aprender nuevas cosas.                                                                                                                                                                                                                                                                                                               |

## 1.2. Solution Profile 
### 1.2.1. Antecedentes y Problemática

El sobreconsumo energético es un problema significativo en el Perú, particularmente en Lima Metropolitana, donde los hogares consumen considerablemente más electricidad que el promedio nacional. Las viviendas limeñas registran un consumo promedio mensual de 172 kWh, casi el doble de los 93 kWh promedio a nivel nacional (Auto Solar, 2025). Esta disparidad no solo se traduce en mayores costos para las familias, sino que también ejerce una presión considerable sobre la infraestructura eléctrica del país. La alta concentración demográfica y el uso intensivo de aparatos eléctricos, sumados a la escasez de prácticas de eficiencia, han convertido a la capital en un foco de consumo excesivo.
 
Esta situación se agrava por la lentitud en la transición energética del país. A pesar del potencial de energías renovables, los avances y los planes estratégicos para un modelo energético más sostenible son inconsistentes (Mongabay Latam, 2024). Por ende, el alto consumo eléctrico doméstico en Lima no solo afecta la economía de los hogares, sino que también incrementa la huella de carbono y retrasa la modernización del sistema. Ante este panorama, es imperativo desarrollar soluciones tecnológicas y accesibles que permitan a los usuarios monitorear y optimizar su consumo de energía, logrando así reducir tanto sus gastos como su impacto ambiental.

- Who (¿Quién?)
Los principales actores afectados son los hogares de Lima Metropolitana y las pequeñas y medianas empresas (PYMEs). Ambos segmentos enfrentan altos costos de electricidad debido a un consumo por encima del promedio nacional. En los hogares, esto se traduce en un impacto directo en la economía familiar; en las PYMEs, en una disminución de la rentabilidad operativa, ya que los gastos fijos en energía se convierten en un obstáculo para su crecimiento.


- What (¿Qué?)
El problema central radica en el excesivo consumo de energía eléctrica sin mecanismos eficientes de monitoreo ni control. Actualmente, la mayoría de usuarios paga mensualmente por la energía utilizada sin conocer en detalle qué dispositivos consumen más, cuándo se generan picos de consumo, ni cómo reducirlos. Esto genera derroche de recursos y una huella ambiental innecesariamente elevada.


- Where (¿Dónde?)
El epicentro de este problema es Lima Metropolitana, donde el consumo energético promedio mensual en un hogar alcanza los 172 kWh, superando ampliamente el promedio nacional de 93 kWh (Auto Solar, 2025). Esta diferencia convierte a Lima en un caso crítico, donde se concentra gran parte de la demanda energética residencial del país, y por lo tanto, en el lugar ideal para implementar soluciones de optimización.


- When (¿Cuándo?)
La urgencia de atender este problema se enmarca en el contexto actual. Según Mongabay Latam (2024), el Perú carece de planes claros y avances consistentes en su transición energética hacia fuentes renovables. En consecuencia, los altos niveles de consumo en los hogares limeños no solo elevan las facturas eléctricas, sino que también retrasan los esfuerzos nacionales de sostenibilidad. Esto convierte al momento presente en una ventana crítica para implementar soluciones innovadoras que ayuden a cerrar la brecha

- Why (¿Por qué?)
La causa del problema es doble: por un lado, económica, ya que el consumo excesivo genera gastos adicionales considerables en electricidad para familias y negocios; por otro, ambiental, debido a que gran parte de la electricidad en Perú proviene de fuentes no renovables, lo que incrementa la emisión de gases de efecto invernadero. Resolver este problema no solo alivia la carga financiera de los usuarios, sino que también contribuye a reducir la huella de carbono y a fomentar una cultura de eficiencia energética.


- How (¿Cómo?)
La solución se plantea mediante la implementación de una plataforma de Internet de las Cosas (IoT) “Verde”, que integre sensores y actuadores inteligentes para monitorear y controlar en tiempo real el consumo energético. El sistema incorporaría algoritmos de Inteligencia Artificial (IA) capaces de identificar patrones de uso, detectar ineficiencias y emitir recomendaciones prácticas al usuario, como apagar dispositivos en horarios de baja ocupación o programar encendidos automáticos. Así, se habilitaría un control remoto, programable y optimizado del consumo eléctrico.

- How Much (¿Cuánto?)
En términos monetarios, el sobreconsumo energético en Lima es significativo. Los 79 kWh adicionales que consume un hogar limeño al mes respecto al promedio nacional equivalen a un gasto de aproximadamente S/ 49,77 adicionales mensuales, es decir, cerca de S/ 600 al año, considerando un costo promedio de S/ 0,63 por kWh en tarifa residencial (OSINERGMIN, 2025). Este monto representa un ahorro potencial tangible que la plataforma IoT podría ofrecer a los usuarios al optimizar su consumo.

### 1.2.2. Lean UX Process

Para garantizar que nuestra solución tecnológica responda a necesidades reales y no a simples suposiciones, empleamos el proceso Lean UX. Esta metodología nos ayuda a comprender el problema, identificar aquello que damos por cierto y convertirlo en hipótesis que puedan validarse. De este modo, buscamos alinear el desarrollo de nuestro software tanto con los objetivos de los usuarios como con la visión de sostenibilidad que orienta nuestra startup.

#### 1.2.2.1 Lean UX Problem Statements

Nuestro proyecto ataca la ineficiencia energética en Lima, enfocándose en hogares y PYMEs que sufren el impacto de facturas eléctricas elevadas y la falta de control sobre sus activos. Hemos detectado que el principal punto de dolor es la opacidad del consumo: el usuario paga, pero no entiende en qué gasta.

Existe una brecha crítica en el mercado local por la ausencia de herramientas de monitoreo en tiempo real. Nuestra estrategia consiste en democratizar el uso de tecnología IoT "verde", integrando sensores inteligentes y control remoto para transformar datos en ahorros tangibles mediante recomendaciones automatizadas.

#### 1.2.2.2. Lean UX Assumptions

Al iniciar este proyecto, hemos definido las siguientes hipótesis críticas que requieren validación mediante experimentación y trabajo de campo:

- Interés en la monitorización: Postulamos que el usuario local valora la visibilidad del consumo en tiempo real como un activo para la toma de decisiones informadas.

- Viabilidad económica de la inversión: Suponemos una disposición de compra hacia hardware IoT, condicionada a la percepción de un retorno de inversión (ROI) tangible mediante el ahorro en la facturación mensual.

- Priorización estratégica en PYMEs: Asumimos que la eficiencia energética es un pilar fundamental en la estructura de costos y la sostenibilidad operativa del sector empresarial.

- Preferencia por el minimalismo funcional: Creemos que la adopción tecnológica se ve favorecida por interfaces simplificadas y de alta usabilidad, frente a sistemas con excesiva carga de funciones complejas.

#### 1.2.2.3. Lean UX Hypothesis Statements

La base de nuestros supuestos iniciales, hemos definido las siguientes hipótesis experimentales que orientarán las fases de prueba:

- Impacto en la Eficiencia Energética: Postulamos que la implementación de un sistema de monitoreo en tiempo real permitirá a los hogares limeños reducir su consumo mensual en un 10%. Validaremos esta hipótesis si, tras un trimestre de uso, el 70% de la muestra piloto registra una disminución efectiva en su facturación.

- Engagement en el Sector PYME: Proponemos que la integración de recomendaciones automatizadas de ahorro es el principal motor de uso para las pequeñas y medianas empresas. El éxito se medirá cuando el 50% de las empresas piloto realicen consultas semanales al dashboard de gestión.

- Adopción de Funcionalidades de Control: Sostenemos que el uso recurrente de la plataforma por parte de usuarios residenciales depende de herramientas de control directo, como el encendido/apagado remoto y la automatización de horarios. Consideraremos validada esta premisa si más del 60% de los usuarios activos interactúan con estas funciones semanalmente.

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

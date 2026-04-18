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

En esta sección se detalla el desarrollo del Big Picture Event Storming, una técnica colaborativa orientada a explorar el dominio de nuestro negocio de manera integral. A través de este proceso identificamos los Domain Events más significativos y los organizamos cronológicamente para visualizar la linea de vida del sistema. Este enfoque no solo nos permitió mapear los flujos de la aplicación, sino también establecer un Lenguaje Ubicuo común entre el equipo y detectar tempranamente cuellos de botella u oportunidades de optimización en la gestión energética de hogares y MYPES.

![big picture event storming](Imagenes/big-picture-event-storming.png)

### 2.3.6. Ubiquitous Language
## 2.4. Requirements specification
### 2.4.1. User Stories
### 2.4.2. Impact Mapping
### 2.4.3. Product Backlog
## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming

Tras haber mapeado el flujo macro del negocio, procedemos al Design-Level Event Storming. En esta etapa el enfoque se desplaza hacia el diseño detallado de la solución de software. Aquí expandimos cada Domain Event integrando Commands, Polices, Aggregates y Read Models, permitiendonos visualizar no solo qué sucede, sino cómo interactua el usuario con el sistema y qué reglas de negocio rigen el comportamiento de PowerSense. Este nivel de detalle es fundamental para identificar de forma natural las fronteras del sistema, sirviendo como paso previo y necesario para la delimitación técnica de los Bounded Contexts.

![event storming-1](Imagenes/event-storming/event-storming-1.png)
![event storming-2](Imagenes/event-storming/event-storming-2.png)
![event storming-3](Imagenes/event-storming/event-storming-3.png)
![event storming-4](Imagenes/event-storming/event-storming-4.png)

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

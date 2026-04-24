# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
A continuacion, se presenta una tabla que contiene a los competidores mas relevantes para nuestra IoS (IoT + Software/IA para monitoreo y optimización del consumo eléctrico).
| id | Nombre | Descripcion | Caracteristicas | Distribucion | Logo |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Smelpro | - Soluciones IoT e Inteligencia Artificial para Industria 4.0.<br><br> - Aplicaciones energéticas: monitoreo en tiempo real, detección de fallas, optimización de los costos operativos y mantenimiento predictivo.<br><br> - Sectores: manufactura, logística, minería, energía y agua. | - Monitoreo del consumo electrico en tiempo real.<br><br> - Detección de fallas y mantenimiento predictivo con uso de I.A.<br><br> - Optimización de los costos operativos.<br><br> - Soporte para LoRaWAN, Sigfox y redes celulares.<br><br> - Dashboards personalizados| - Ventas B2B directas.<br> - Integradores y proyectos llave en mano	 | ![Smelpro](Imagenes/smelpro.png) |
| 2 | LoraTech | - Empresa líder en soluciones IoT con tecnología LoRaWAN para monitoreo energético.<br><br> - Aplicaciones eléctricas: redes de sensores para medir el consumo eléctrico en tiempo real, control remoto de cargas, alertas y reportes para optimización.<br><br> - Ventajas: bajo consumo, alta penetración en interiores y seguridad de los datos.<br><br> - Sectores: industria, agroindustria y edificios inteligentes. | - Redes de sensores LoRaWAN para consumo en tiempo real.<br><br> - Alertas y reportes de anomalías y consumo.<br><br> - Dispositivos de bajo consumo y larga autonomía.<br><br> - Control remoto de cargas y automatización. | - Ventas B2B y partners integradores.<br><br> - Proyectos llave‑en‑mano y proveedores de gateways/servicios de red. | ![loratech](Imagenes/Tecape.PNG) |
| 3 | Teca Perú | - Soluciones “llave‑en‑mano” en telemetría y telecontrol con fuerte uso de LoRaWAN.<br><br> - Aplicaciones energéticas: medición en tiempo real de servicios (agua, energía, gas) y despliegues industriales.<br><br> - Casos: edificios inteligentes, minería, agricultura, piscicultura. | - Telemetría y telecontrol llave‑en‑mano.<br><br> - Redes LoRaWAN privadas y gateways.<br><br> - Medición en tiempo real y dashboards industriales.<br><br> - Integración con sistemas SCADA/ERP. | - Ventas B2B directas.<br><br> - Integradores de proyectos y contratos con empresas/municipios. | ![tecaperu](Imagenes/loratech.png) |

### 2.1.1. Análisis competitivo
| **Propósito del análisis:** Evaluar la posición de PowerSense frente a sus tres competidores clave del ecosistema IoT/energía (Smelpro, LoraTech y Teca Perú) para identificar ventajas competitivas, riesgos y tácticas prioritarias que permitan ganar cuota en hogares urbanos y PYMEs. |
| **Pregunta guía:** ¿Cómo se compara PowerSense en oferta, producto, mercado y potencial estratégico frente a Smelpro, LoraTech y Teca Perú, y qué acciones tácticas deben priorizarse para diferenciarse y crecer? |
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
"""
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

Para evaluar el atractivo y la practicidad de el servicio y producto PowerSense , estamos realizando entrevistas para entender a fondo lo que nuestros futuros usuarios necesitan, cómo se comportan y qué esperan.

### Diseño de entrevista – Primer segmento objetivo (Hogar):

¿En qué momentos del día suele usar más electricidad?

¿Qué dispositivos eléctricos son indispensables en su hogar y por qué?

¿Ha sentido que paga más luz de lo que debería? ¿Cómo lo percibe?

¿Suele comparar el monto de su recibo actual con el de meses anteriores? ¿Qué observa en esas comparaciones?

¿En su hogar suelen hablar o discutir sobre el gasto en electricidad?

¿Ha tenido que limitar el uso de algún aparato eléctrico por el costo de la electricidad?

¿Qué estrategias usa actualmente para intentar reducir el gasto en electricidad?

¿Cómo se informa (si es que lo hace) sobre su consumo eléctrico?

¿Qué impacto tiene el gasto en electricidad dentro del presupuesto familiar?

### Diseño de entrevista – Segundo segmento objetivo (Negocios):

¿Cuál es su nombre y cargo dentro de la empresa?

¿Cómo se llama su negocio y a qué rubro se dedica (ej. comercio, gastronomía, servicios, manufactura, etc.)?

¿En qué distrito o zona se encuentra ubicada su empresa?

¿Cuántos años tiene funcionando su negocio?

¿Cuál es el horario de funcionamiento habitual de su negocio?

¿En qué meses del año siente que gasta más electricidad? ¿Por qué cree que ocurre eso?

¿Qué equipos o procesos consumen más energía en su operación diaria?

¿Qué equipos, maquinarias o procesos son más indispensables para su negocio?

¿Qué equipos cree que consumen más energía?

¿Han tenido fallas en los equipos o servicios debido a picos de consumo eléctrico?

¿Qué estrategias o medidas ha probado para reducir el gasto en electricidad?

¿Cómo afecta el pago de la electricidad en su rentabilidad mensual o anual?

¿Considera que sus clientes valoran si su empresa adopta prácticas sostenibles?

¿Qué impacto tendría en su negocio poder optimizar los recursos energéticos sin sacrificar productividad?

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

Link de la entrevista:

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

Entrevista 3 (Nombre aqui)

### - Segmento objetivo 2 (Negocios)

Entrevista 4 (Juan Carlos Urdanivia Abad — Premium Cultural Institute) Inicio: 10:13 - Fin: 16:18 - Duración: 6:05

<p align="center">
  <img src="Imagenes/Imagen_entrevista4.png" alt="Imagen_entrevista4" />
</p>

- Nombre: Juan Carlos Urdanivia Abad
- Edad: 55 años
- Distrito de residencia: Surco
- Sector: Enseñanza

Resumen de Entrevista : A partir de la entrevista realizada al usuario Juan Carlos Urdanivia Abad, de 55 años y residente de Surco, se identificó que desde la perspectiva institucional los equipos de climatización y los sistemas audiovisuales generan picos significativos, especialmente durante actividades y temporadas altas. 

Indica que las vitrinas o equipos que requieren funcionamiento continuo representan la carga base más relevante y que la falta de datos en tiempo real impide identificar con precisión horarios o procesos causantes de incrementos en la factura. Manifiesta interés en monitoreo por circuito, reportes estacionales y en justificar inversiones en eficiencia ante la dirección, pero también subraya la necesidad de garantizar continuidad de servicio y comodidad en el espacio educativo.

Link de la entrevista:

Entrevista 5 (Nombre aqui)

Entrevista 6 (Nombre aqui)

### 2.2.3. Análisis de entrevistas

### - Segmento objetivo 1 (Hogares):

Observamos que los entrevistados reportan incrementos periódicos en el gasto energético sin que se identifique una causa clara y verificable que explique dichas variaciones. Los datos que reciben, como la boleta y las lecturas del medidor, no son suficientemente detallados ni intuitivos para relacionarlos con el uso real de los equipos, lo que genera desconfianza y sensación de opacidad. Además, existe escasa formación en gestión energética: muchos participantes reconocen no tener conocimientos técnicos para interpretar consumos eléctricos ni para evaluar estrategias de ahorro más sofisticadas. Las medidas que aplican suelen ser reactivas y de bajo impacto.

Por ejemplo, desenchufar equipos o reducir tiempos de ducha y carecen de herramientas que permitan medir su efecto a mediano o largo plazo. En viviendas compartidas aparece un problema recurrente en la distribución del costo: la ausencia de mediciones por toma o por usuario provoca incertidumbre y conflictos al momento de repartir la boleta.

### - Segmento objetivo 2 (Negocios):

Los entrevistados reconocen que el consumo es elevado y que existen picos asociados a equipos concretos, como refrigeradores y aires acondicionados, pero coinciden en que no siempre es posible identificar con precisión qué operación o qué horario provoca los incrementos en la factura. La información disponible no facilita la toma de decisiones operativas porque falta métricas en tiempo real y reportes que permitan optimizar horarios y equipos.

Aunque hay interés en implementar medidas de eficiencia o generación propia, la principal barrera es el costo inicial y la necesidad de justificar retornos financieros claros, lo que impide muchas veces la adopción. La prioridad de estos negocios es garantizar la continuidad operativa: en rubros con equipos críticos (congeladores, vitrinas, equipos de ventilacion), la posibilidad de aplicar medidas agresivas de reducción de carga queda limitada por el riesgo de pérdidas, por lo que requieren soluciones que les permitan monitorear y proteger esos activos. Las prácticas actuales de gestión energética son en general manuales y poco automatizadas, lo que reduce la capacidad de respuesta eficiente ante variaciones de demanda.

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

Una vez detallados los flujos del Design-Level Event Storming, procedemos al Candidate Context Discovery. Esta etapa representa la transición del análisis del flujo a la definición de la arquitectura estratégica. El objetivo es identificar grupos de funcionalidades que comparten un mismo Lenguaje Ubicuo y reglas de negocio cohesivas. Al agrupar estos elementos, emergen de manera natural los límites de los modelos, permitiéndonos proponer contextos candidatos que servirán como base para la descomposición del sistema en módulos independientes y escalables.

![monitoring](Imagenes/candidate-context-discovery/monitoring.png)
![scheduling](Imagenes/candidate-context-discovery/scheduling.png)
![enterprise](Imagenes/candidate-context-discovery/enterprise.png)
![reporting](Imagenes/candidate-context-discovery/reporting.png)
![alerts](Imagenes/candidate-context-discovery/alerts.png)
![iam](Imagenes/candidate-context-discovery/iam.png)

#### 2.5.1.2. Domain Message Flows Modeling

A countinuación se presenta el flujo de mensajes para el caso de uso principal o core para el negocio, el cual es el cálculo y exosición de las estadísticas de consumo de enrgía electrica del usuario. El flujo comienza desde que el dispositivo IoT envia los datos crudos, los cuales son procesador ppor el Monitoring Context. Aqui se bifurca el flujo, ya que si se detecta un pico en el umbral de consumo se debe emmitir una alerta de este tipo. El flujo terminaría entonces con la entrega de los datos de consumo asi como el costo promedio de este.

![flow 1](Imagenes/domain-message-flow-modeling/flow-1.png)

#### 2.5.1.3. Bounded Context Canvases

En esta sección se presenta los diferentes Canvas realizados para los contextos que se identificaron, comenzando desde los más importantes para el negocio. Aquí se detalla la información sobre este Bounded Context, así como la comunicación entrante y saliente. Además del lenguaje ubicuo y reglas de negocio que aplican en este contexto.

![monitoring](Imagenes/bounded-context-canvas/monitoring.png)
![scheduling](Imagenes/bounded-context-canvas/scheduling.png)
![enterprise](Imagenes/bounded-context-canvas/enterprise.png)
![reporting](Imagenes/bounded-context-canvas/reporting.png)
![alerts](Imagenes/bounded-context-canvas/alerts.png)
![iam](Imagenes/bounded-context-canvas/iam.png)

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
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams
## 2.6. Tactical-Level Domain-Driven Design


# Bibliografía
- Sierra Praeli, Y. (28 de abril de 2024). Territorios contaminados: la transición energética no avanza en la Amazonía de Perú. Mongabay Latam.
  (https://es.mongabay.com/2024/04/territorios-contaminados-transicion-energetica-no-avanza-amazonia-peru/)
- AutoSolar Perú. (s. f.). Consumo energético familiar en Perú.
  (https://autosolar.pe/ahorro-de-energia/consumo-energetico-familiar-en-peru)

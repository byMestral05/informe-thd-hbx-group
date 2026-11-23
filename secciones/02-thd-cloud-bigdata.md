## 3. Análisis THD por THD

### 3.1 Cloud computing

**Definición.** El cloud computing consiste en usar recursos informáticos (servidores, almacenamiento, bases de datos, redes) que ofrece un proveedor a través de Internet y que se pagan según el uso, en lugar de comprarlos e instalarlos en un centro de datos propio.

**Características principales.**

- **Elasticidad / autoescalado:** la capacidad sube o baja sola según la carga.
- **Pago por uso:** se convierte un gasto de inversión (comprar servidores) en un gasto operativo.
- **Modelos de servicio IaaS, PaaS y SaaS**, y despliegue público, privado o **híbrido**.

**Aplicación en HBX Group.**

- **Migración progresiva desde centros de datos propios.** Hotelbeds empezó a migrar a **Amazon Web Services (AWS)**, con el apoyo de BT para la parte de red y centro de datos. En 2018 ya tenía más del 60 % de sus datos en AWS y explicaba que el objetivo era atender más rápido las más de **430 millones de peticiones diarias** que recibía [5][6].
- **Segundo proveedor: Google Cloud.** En 2021 llevó su plataforma de API a Google Cloud con una arquitectura de **autoescalado** e **infraestructura como código**. Según la empresa, los clientes de la API vieron bajar los tiempos de respuesta **hasta un 7 %**, lo que mejora la conversión de las búsquedas en reservas [7].
- **Contenedores y Kubernetes.** Desde 2017 la empresa pasó de máquinas virtuales a una arquitectura de **microservicios en contenedores Docker**. En 2020 puso en producción clústeres **Kubernetes** gestionados con **Rancher**, a la vez en sus servidores propios (*on-premise*), en Google Cloud y en AWS. Con ello redujo un **90 % el tiempo de migración** a la nube y un **80 % el tiempo de despliegue** de clústeres [8].
- **SaaS interno.** Para la gestión corporativa usa aplicaciones SaaS como Workday, Microsoft y Salesforce [5].

**Mejora IT/OT que aporta.**

- **IT:** la plataforma deja de depender de la capacidad física de un centro de datos en Palma. En temporada alta (verano europeo, Black Friday) puede multiplicar recursos y luego reducirlos, en vez de dimensionar servidores para el pico todo el año.
- **IT-OT:** al estar en la nube, el inventario que el hotel actualiza en su sistema operativo (PMS o *channel manager*) llega casi en tiempo real a miles de agencias de todo el mundo. La nube actúa como **punto de encuentro** entre la operación física del hotel y la venta digital.

### 3.2 Big Data y analítica de datos

**Definición.** Big Data es el conjunto de técnicas y herramientas para capturar, almacenar y analizar volúmenes de datos tan grandes, rápidos o variados que no se pueden tratar con una base de datos tradicional.

**Características principales (las «V»).**

- **Volumen:** cantidades masivas de registros.
- **Velocidad:** datos que llegan en flujo continuo y deben procesarse casi en tiempo real.
- **Variedad:** datos estructurados (precios, reservas) y no estructurados (descripciones, fotos, conversaciones).

**Aplicación en HBX Group.**

- **Volumen y velocidad reales.** Ya en 2016 el CTO afirmaba que recibían **más de 6.000 peticiones por segundo** y que «Big Data is business as usual» para ellos; ese año presentaron su **Big Data Platform** en el AWS Summit de Madrid [9]. En 2020, tras rediseñar el portal de su API, APItude podía soportar **hasta 14.000 millones de búsquedas al día** en los picos [10].
- **Peso del canal API.** Hosteltur recogía que APItude ya suponía el 20 % del negocio de Hotelbeds, con más de 400 clientes y 80 millones de búsquedas diarias, dentro de un total de unos 300 millones de búsquedas al día [24].
- **Herramientas que usan.** Las ofertas de empleo de la empresa piden experiencia en **Kafka** (flujos de datos en tiempo real), **PostgreSQL**, **Redis** (caché), **Tableau** (*Business Intelligence*) y **AWS SageMaker** (modelos de machine learning) [11]. Otra oferta busca un *Data Engineer Lead* para diseñar **pipelines de datos** y desplegar modelos de ML [12]. Esto confirma que el análisis de datos es una actividad diaria con equipo propio.
- **Producto de datos para clientes.** La **Cache API** permite a los clientes descargar ficheros masivos de precios y disponibilidad en lugar de consultar uno a uno, y la **Content API** sirve información estática (fotos, descripciones, servicios) de más de 180.000 hoteles en varios idiomas [23].
- **Ejemplo concreto:** en un datatón con el IE, Hotelbeds cedió datos reales de su negocio de traslados y actividades para **segmentar clientes** y atenderlos mejor [9].

**Mejora IT/OT que aporta.**

- **IT:** decisiones de precios, catálogo y comerciales basadas en datos y no en intuición.
- **IT-OT:** los datos de búsquedas (por ejemplo, un aumento de búsquedas desde un mercado emisor concreto) se devuelven al hotel para que ajuste su operación: personal, apertura de plantas o precios. Es el caso de uso de la alianza con Vorsee descrita en el apartado 3.3 [16].

### 3.3 Inteligencia artificial

**Definición.** La inteligencia artificial (IA) agrupa las técnicas que permiten a un sistema realizar tareas que normalmente requieren inteligencia humana: entender lenguaje, reconocer patrones, predecir o tomar decisiones. Incluye el *machine learning* y la IA generativa.

**Características principales.**

- **Aprende de los datos:** los modelos mejoran con más ejemplos, así que depende del Big Data.
- **Automatiza tareas cognitivas** repetitivas, como responder consultas o clasificar casos.
- **Predice y recomienda:** estima demanda, precios o qué producto encaja con un cliente.

**Aplicación en HBX Group.**

- **Atención al cliente «AI-first».** En junio de 2024 anunció un nuevo modelo de atención basado en **Google Cloud Contact Center AI** y los modelos **Gemini**, desarrollado con la consultora Emergya. Se usa para automatizar tareas rutinarias, reducir tiempos de respuesta y ayudar a los agentes humanos con respuestas a medida [13]. Es relevante porque la empresa tiene **más de 1.000 agentes de soporte** que atienden en 13 idiomas [1].
- **Entrenador con IA para agentes.** En diciembre de 2024 lanzó un simulador que genera conversaciones con clientes ficticios en **13 idiomas**, con **cientos de escenarios** y **cuatro niveles de dificultad**, para que los nuevos agentes practiquen sin un formador presente [14].
- **Recomendación personalizada.** En mayo de 2026 acordó comprar la startup **Bridgify** por unos 3 millones de euros. Su software empareja más de **un millón de experiencias** turísticas con el perfil de cada viajero. Según Skift, la IA y la automatización ya le han supuesto **ahorros anualizados de 1 millón de euros** y un **5 % menos de costes operativos** [15].
- **Previsión de demanda para hoteles.** Mediante una alianza con **Vorsee** (plataforma ActionOS), integra agentes de IA predictiva en su Partner Portal, en Roiback y en Civitfun para que los hoteles detecten cambios de demanda **antes** de que aparezcan en sus reservas [16].

**Mejora IT/OT que aporta.**

- **IT:** menos carga manual en el centro de atención y respuestas más rápidas a agencias y hoteles.
- **IT-OT:** la previsión de demanda pasa de ser un informe a una **acción operativa** en el hotel: cambiar precios, reforzar personal de recepción o abrir más habitaciones. La IA conecta lo que ocurre en la plataforma digital con la gestión física del alojamiento.

### 3.4 Ciberseguridad

**Definición.** La ciberseguridad es el conjunto de medidas técnicas, organizativas y legales que protegen sistemas, redes y datos frente a accesos no autorizados, robos, fraudes o interrupciones del servicio.

**Características principales.**

- **Confidencialidad, integridad y disponibilidad** (tríada CIA) de la información.
- **Cumplimiento normativo:** estándares como **PCI DSS** para datos de tarjetas y el RGPD para datos personales.
- **Defensa en capas:** autenticación, cifrado, monitorización y formación de las personas.

**Aplicación en HBX Group.**

- **Pagos.** Mueve millones de reservas con tarjeta, por lo que su motor de reservas cumple **PCI DSS**. A los proveedores les paga con **tarjetas de crédito virtuales (VCC)**, gestionadas con un sistema de facturación electrónica, y aplica capas de cifrado en el recorrido del pago [17].
- **Acceso a la API.** Cada cliente que se conecta a APItude se autentica con una **clave de API** y una **firma** generada a partir de su clave, un secreto y la marca de tiempo. Así se evita que alguien reutilice o falsifique peticiones [23].
- **Ciberseguridad como servicio para hoteles.** En junio de 2025 lanzó con la aseguradora Wallbid **Cybersential**: una auditoría que revisa la infraestructura digital del hotel, detecta vulnerabilidades (credenciales expuestas, sistemas sin proteger), le asigna una **puntuación de riesgo** con recomendaciones y le da la opción de contratar un **ciberseguro** [18].
- **Concienciación.** Su directora de Tecnología y Datos defendía públicamente en 2024 la colaboración y la formación en ciberseguridad dentro de la cadena turística [19].

**Mejora IT/OT que aporta.**

- **IT:** protege la plataforma y los datos de millones de viajeros, condición imprescindible para que agencias y bancos confíen en ella.
- **IT-OT:** el punto débil del turismo suele ser el hotel (recepción, PMS antiguo, wifi de huéspedes). Con Cybersential, HBX **extiende la seguridad desde su plataforma IT hasta los sistemas operativos del hotel**, que es justamente donde conviven IT y OT.

### 3.5 Internet de las cosas (IoT) e integración con sistemas operativos del hotel

**Definición.** El Internet de las cosas (IoT) es la conexión a Internet de objetos físicos (sensores, cerraduras, terminales) para que envíen datos y se puedan controlar a distancia o de forma automática desde software.

**Características principales.**

- **Conectividad de dispositivos físicos** con plataformas en la nube.
- **Automatización:** un evento digital provoca una acción física (por ejemplo, activar una llave).
- **Interoperabilidad:** necesita integraciones y protocolos comunes entre fabricantes distintos.

**Aplicación en HBX Group.** Aquí hay que ser precisos: **HBX Group no fabrica dispositivos IoT**. Su papel es **integrar** su software con los dispositivos y sistemas que ya hay en el hotel. Lo hace sobre todo con **Civitfun**, empresa fundada en Mallorca en 2014 y comprada por HBX en mayo de 2025 [20]:

- Civitfun dispone de un **hub con más de 100 integraciones** con PMS, pasarelas de pago y **cerraduras electrónicas** [21][25].
- Ha procesado **15 millones de check-ins** en más de **3.500 hoteles** y 500.000 habitaciones [21].
- El huésped puede hacer el check-in desde el móvil (por URL, sin descargar una app) o en la recepción con una tablet (solución *Paperless*). Los datos pasan directamente al PMS y, según el hotel, se puede emitir la llave digital [22][25].
- Según Roiback, la implantación tarda **unos 15 días** y el sistema reduce el fraude y las devoluciones [22].

**Mejora IT/OT que aporta.** Es la THD que **más directamente une IT y OT**:

- La reserva nace en la plataforma IT de HBX (APItude o Bedsonline).
- Llega al **PMS** del hotel, el sistema que gestiona la operación diaria.
- Con Civitfun, el **registro del huésped**, el **pago** y la **llave** (dispositivos físicos) se activan a partir de esos mismos datos, sin volver a teclearlos en recepción.

Resultado: menos colas, menos errores de transcripción y una sola fuente de verdad desde la reserva hasta la puerta de la habitación.

### 3.6 THD que la empresa no utiliza (o no de forma relevante)

| THD | ¿La usa? | Motivo |
|---|---|---|
| **Blockchain** | No hemos encontrado uso en producción | Su negocio necesita confirmar miles de reservas por segundo; una cadena de bloques añadiría latencia y coste sin aportar mucho, porque HBX ya actúa como intermediario de confianza. |
| **Fabricación aditiva (impresión 3D)** | No | No fabrica productos físicos. |
| **Robótica física** | No | No tiene operaciones logísticas ni de fabricación. La automatización que usa es de software (IA y automatización de procesos). |
| **Realidad aumentada / virtual** | No como producto principal | Las agencias venden con fotos y descripciones de la Content API; no hemos encontrado fuentes que muestren RA/RV en su plataforma. |

<div class="page-break"></div>

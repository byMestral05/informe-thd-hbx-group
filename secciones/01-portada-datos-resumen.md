<div class="portada" markdown="1">

# Informe THD: HBX Group (Hotelbeds)

**Autores:** Manel Ortiz y Sergi Gregorio

**Fecha:** 23 de noviembre de 2026

**Módulo:** 1º DAW - DIGI

**Repositorio GitHub:** [https://github.com/byMestral05/informe-thd-hbx-group](https://github.com/byMestral05/informe-thd-hbx-group)

</div>

<div class="page-break"></div>

## Índice

1. Datos de la empresa elegida
2. Resumen ejecutivo
3. Análisis THD por THD
    - 3.1 Cloud computing
    - 3.2 Big Data y analítica de datos
    - 3.3 Inteligencia artificial
    - 3.4 Ciberseguridad
    - 3.5 Internet de las cosas (IoT) e integración con sistemas operativos del hotel
    - 3.6 THD que la empresa no utiliza
4. Esquema de integración IT-OT
5. Conclusiones
6. Fuentes

## 1. Datos de la empresa elegida

| Campo | Información |
|---|---|
| **Nombre** | HBX Group (antes Hotelbeds Group) — [www.hbxgroup.com](https://www.hbxgroup.com) |
| **Ubicación** | Sede central en el edificio Mirall, Camí de Son Fangos 100, Palma (Mallorca, Islas Baleares). La empresa nació en Palma en 2001 como parte del grupo Barceló [3]. |
| **Sector concreto** | *TravelTech* B2B: marketplace tecnológico en la nube que conecta hoteles y otros proveedores turísticos con agencias, touroperadores, aerolíneas y programas de fidelización [4]. |
| **Tamaño** | **Grande.** Más de 3.500 empleados, oficinas en 33 países y presencia comercial en más de 170 [1][2][4]. Cotiza en la Bolsa española desde el 13 de febrero de 2025 [2]. |
| **Producto o servicio principal** | **Hotelbeds**, el mayor *bedbank* del mundo, que distribuye más de 180.000 hoteles mediante la API APItude y la web Bedsonline [8][23]. Además vende software para hoteles: **Roiback** (motor de reservas) y **Civitfun** (check-in online), dos empresas también nacidas en Mallorca [4][20]. |
| **Por qué la hemos elegido** | Es la mayor empresa tecnológica con sede en Baleares y su producto es, literalmente, software y datos al servicio del turismo, el motor económico de las islas. |

> **¿Por qué es del sector TIC?** HBX Group no tiene hoteles ni aviones: su negocio es una plataforma digital que recibe cientos de millones de peticiones al día a través de APIs y las cruza con el inventario de los proveedores. La propia empresa se define como «B2B travel technology marketplace» [2][4].

## 2. Resumen ejecutivo

HBX Group es una empresa de software con sede en Palma que actúa como intermediario digital del turismo mundial: los hoteles cargan en su plataforma habitaciones y precios, y miles de agencias y touroperadores los consultan y reservan de forma automática. Su valor depende de responder en milisegundos, con datos fiables y de forma segura, a un volumen enorme de búsquedas.

En este informe identificamos **cinco tecnologías habilitadoras digitales (THD)** presentes en la empresa:

| # | THD | Dónde aparece en HBX Group | Objetivo de negocio al que sirve |
|---|---|---|---|
| 1 | **Cloud computing** | Toda la plataforma de reservas corre en AWS y Google Cloud con contenedores Kubernetes | Escalar sin comprar servidores y responder más rápido |
| 2 | **Big Data** | Procesado de miles de millones de búsquedas, precios y disponibilidad | Saber qué se vende, a quién y a qué precio |
| 3 | **Inteligencia artificial** | Atención al cliente con Google Contact Center AI y Gemini, formación de agentes, recomendación y previsión de demanda | Reducir costes operativos y vender más |
| 4 | **Ciberseguridad** | Pagos conformes a PCI DSS, tarjetas virtuales, firma de peticiones API, servicio Cybersential para hoteles | Generar confianza y cumplir la normativa |
| 5 | **IoT / integración con OT del hotel** | Civitfun conecta la plataforma con PMS, pasarelas de pago y cerraduras electrónicas | Digitalizar la recepción y llegar al hotel físico |

También explicamos qué THD **no** utiliza (blockchain, fabricación aditiva, robótica física, RA/RV) y por qué.

<div class="page-break"></div>

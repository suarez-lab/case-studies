# Casos de estudio

[English](README.md) · **Español**

Sistemas en producción que hemos diseñado, construido y operamos. Cada uno declara las
restricciones que le dieron forma, las alternativas que descartamos y por qué, y lo que
nos costó equivocarnos.

**Dos reglas gobiernan este repositorio.** Los clientes se identifican solo por sector,
geografía y año — nunca por nombre, incluso teniendo permiso. Y una cifra se publica solo
si está medida: los números de aquí salen de código o de datos de producción que podemos
volver a ejecutar, no de una propuesta ni de un informe de seguimiento.

| Caso | Sector · Geografía | La versión corta |
| --- | --- | --- |
| [Clasificar leads inmobiliarios entre el ruido de WhatsApp](whatsapp-lead-classification/README.es.md) | `Inmobiliario` · `América Latina` | Primero reglas, el modelo al final: 11% de fallos y 1/12 de la factura de LLM |
| [Cobranza por WhatsApp](debt-collection-automation/README.es.md) | `Servicios financieros` · `Europa` | Un mensaje cada nueve minutos; una grieta de cobertura reducida de 179 contratos a 13 |
| [Dos canales documentales hacia un mismo back office](document-ingestion-ai/README.es.md) | `Inmobiliario` · `Europa` | Un LLM que rellena un formulario pero al que nunca se le deja escribir en la base de datos |
| [El bucle de evaluación que construimos primero](market-signal-pipeline/README.es.md) | `Mercados financieros` · `Global` | Nos dijo que las señales acertaban el 46.1% de las veces — por debajo del azar |
| [Una app social nativa sin salida de emergencia por aire](native-social-app/README.es.md) | `Consumo / social` · `Europa` | Cada cambio de JavaScript es un envío a tienda |
| [¿El asistente conversa de verdad o solo despacha?](conversational-quality-evaluation/README.es.md) | `Inmobiliario` · `América Latina` | Medir diálogo en vez de accuracy |

## Cómo leerlos

Todos los casos siguen la misma estructura, para que se puedan comparar: *problema →
restricciones → arquitectura → decisiones que merece la pena explicar → resultados → el
incidente que merece la pena leer → qué haríamos distinto*.

La sección de **decisiones** es a la que apuntaríamos a un revisor. Nombra la alternativa
que consideramos, por qué la descartamos y qué nos costó la elección — porque una nota de
arquitectura que solo enumera lo elegido es un documento de venta.

La sección del **incidente** existe porque los sistemas enseñan cosas que la documentación
no. Cuando una lección generaliza más allá de un cliente, tiene también su entrada en el
[manual de ingeniería](https://github.com/suarez-lab/engineering-handbook).

## En otros repositorios

- [engineering-handbook](https://github.com/suarez-lab/engineering-handbook) — lo que nos enseñó producción, una entrada por lección
- [reference-architectures](https://github.com/suarez-lab/reference-architectures) — formas que hemos construido más de una vez
- [toolkit](https://github.com/suarez-lab/toolkit) — con qué construimos de verdad, contado sobre manifiestos
- [profiles](https://github.com/suarez-lab/profiles) — quiénes somos

<sub>Cliente identificado solo por sector, por política propia. En este repositorio no se nombra a ningún cliente.</sub>
<sub>En este documento no aparece código, credenciales ni datos de usuario del cliente.</sub>

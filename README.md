# Sistema de gestión de turnos y clientes para una peluquería

> Proyecto del Trabajo Práctico Integrador de **Organización Empresarial**
> Tecnicatura Universitaria en Programación a Distancia – Universidad Tecnológica Nacional (UTN)

## Descripción del sistema

Sistema web para que una peluquería de barrio pueda registrar clientes y administrar turnos, en reemplazo del cuaderno y de los mensajes de WhatsApp. Se puede usar desde la computadora y desde el celular.

**Objetivo general:** desarrollar e implementar, en 20 semanas, un sistema web de gestión de turnos y clientes para una peluquería de barrio.

## Integrante

- Fabrizio loza 

## Contenido del repositorio

| Carpeta / archivo | Qué contiene |
|---|---|
| `docs/bpmn.png` | Diagrama BPMN del proceso de solicitud y confirmación de turnos |
| `docs/entregas/` | PDF de las entregas del TPI |
| `README.md` | Esta portada |

## Proceso modelado (BPMN)

![Diagrama BPMN](docs/bpmn.png)

Dos pools (Cliente y Peluquería), dos lanes dentro de la peluquería (Recepcionista y Sistema) y dos compuertas exclusivas: «¿Datos completos?» y «¿Hay horario disponible?».

## Tablero de gestión

Tablero en GitHub Projects: [pegar acá el enlace]

| Historia de usuario | Estado |
|---|---|
| Como recepcionista, quiero registrar un turno con los datos del cliente, el servicio, el día y la hora, para no depender del cuaderno. | [Por hacer / En progreso / Listo] |
| Como cliente, quiero recibir una confirmación de mi turno, para tener la certeza de que quedó reservado. | [Por hacer / En progreso / Listo] |
| Como dueña de la peluquería, quiero ver la agenda del día, para organizar el trabajo. | [Por hacer / En progreso / Listo] |

## Forma de trabajo con Git

- `main` es la rama estable; no se hacen cambios directos sobre ella.
- Cada cambio se hace en una rama aparte (por ejemplo `docs/bpmn`, `docs/readme`) y se une a `main` con un Pull Request revisado.
- Los commits siguen el formato `tipo: descripción corta en presente`, por ejemplo `docs: agrega el diagrama BPMN del proceso de turnos`.

## Indicadores de control

| Indicador | Estándar |
|---|---|
| Tiempo de respuesta | Menos de 2 s en el 95 % de las operaciones, con 20 usuarios a la vez |
| Capacidad de registros | Al menos 5.000 clientes y 20.000 turnos sin perder velocidad |
| Calidad de las pruebas | 90 % o más de los casos aprobados y ningún error crítico abierto |
| Avance del cronograma | Desvío máximo de 1 semana respecto del Gantt |
| Historias de usuario | Las 3 en «Listo» al finalizar |
| Control de versiones | Todos los cambios por rama y Pull Request, con commits descriptivos |

## Declaración de uso de IA

Usé un asistente de IA (Claude) para ordenar la estructura de la documentación sobre la plantilla de la cátedra, dibujar el diagrama BPMN y redactar un primer borrador del README y de las tablas.

**Prompts utilizados y por qué**

- Le pedí que completara la entrega siguiendo las consignas y la plantilla, de forma sencilla y con tono humano, porque la rúbrica evalúa la voz propia.
- Le aclaré que trabajo solo; en una entrega anterior el borrador había salido en plural.
- [Agregar otros prompts que hayas usado y para qué.]

**Correcciones humanas y control crítico**

- Cambié el texto de plural a singular, porque el trabajo y los roles son míos.
- Comprobé la referencia de Chiavenato en el catálogo de la red de bibliotecas de la UTN.
- [Completar: qué revisaste y corregiste del diagrama BPMN.]
- [Completar: qué cambiaste en las historias de usuario o en los indicadores.]

Los errores de la IA cuentan como errores míos, por eso revisé el contenido antes de publicarlo.

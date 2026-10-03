# Plan técnico

> Una o dos páginas en total. Entre tres y ocho líneas por sección.
> Se evalúa que cada decisión se apoye en algo —la alternativa del Módulo 2, una
> restricción del cliente o un riesgo que ustedes identificaron—, no la extensión.
> Lo que no cabe aquí va a un ADR.

## Alternativa seleccionada

`[Cuál, en una frase.]`

`[Y qué la sostiene: dos o tres razones, cada una anclada en un dato del cliente.
Ejemplo de la forma, no del contenido: «no exige instalación, lo que permite que
los comercios entren desde el navegador» se apoya en el dato de los teléfonos.]`

`[La restricción que esta alternativa NO resuelve. Todas dejan algo por fuera;
nombrarlo es lo que hace creíble la elección.]`

## Arquitectura

`[Qué componentes hay y cómo se hablan entre sí. Un diagrama simple basta.]`

`[Una pregunta que conviene responder aquí: ¿quién decide si una transición de
estado es válida, el cliente o el servidor?]`

## Modelo de datos

`[Entidades, atributos y estados.]`

`[La cadena de estados de una donación va aquí, y tiene que coincidir con la que
escribieron en comportamientos.md.]`

`[Si necesitan guardar el historial de cambios para CMP-05, piensen qué entidad
lo soporta.]`

## Integraciones

`[De qué servicios externos dependen.]`

`[Y por cada uno: qué pasa si falla. Un servicio del que se depende sin plan de
falla es un riesgo sin mitigación.]`

## Entorno y despliegue

`[Cómo se levanta el proyecto en la máquina de cada integrante.]`

`[Dónde va a vivir en producción.]`

`[Costo mensual estimado. Recuerden el tope de $150.000 que declaró la fundación.]`

## Riesgos heredados del Módulo 2

| Riesgo que identificaron | Se convierte en |
|---|---|
| `[riesgo]` | `[decisión del plan · ADR · o tarea del backlog]` |
| `[riesgo]` | `[...]` |

> Una mitigación bien escrita ya es una tarea del backlog. Esta tabla es donde el
> Módulo 2 se convierte en trabajo.

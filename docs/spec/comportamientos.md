# Especificación del MVP

El núcleo es el conjunto mínimo de comportamientos que hace que la Fundación
Mesa Común pueda dejar de coordinar por WhatsApp.

Cada comportamiento tiene un identificador estable. El texto puede cambiar; el
identificador no. Las tareas del tablero, las pruebas y los commits apuntan a
estos códigos.

---

## CMP-01 · Un comercio registra una donación disponible

> Ejemplo completo. Los demás comportamientos se escriben con esta misma forma.

**Origen:** RF-01 · donación mínima y validada

**CA-01.1** Dado un comercio identificado, cuando registra tipo de alimento,
cantidad aproximada, punto de recogida y hora límite, entonces la donación queda
guardada en estado `disponible`.

**CA-01.2** Dado un formulario incompleto, cuando el comercio intenta guardar,
entonces el sistema indica qué dato falta y no guarda la donación.

---

## CMP-02 · Un voluntario toma una donación disponible

**Origen:** `[el requerimiento del Módulo 1 del que sale]`

**CA-02.1** `[qué pasa cuando un voluntario toma una donación disponible]`

**CA-02.2** `[qué pasa cuando otro intenta tomar una que ya fue tomada]`

**CA-02.3** `[qué pasa si dos la toman en el mismo instante]`

> Este es el comportamiento más difícil de los cinco y el corazón del MVP.
> El tercer criterio es el que separa una especificación de una descripción:
> el caso secuencial es fácil, el simultáneo no.

---

## CMP-03 · El voluntario registra la entrega

**Origen:** `[completar]`

**CA-03.1** `[completar]`

---

## CMP-04 · Las donaciones disponibles son visibles

**Origen:** `[completar]`

**CA-04.1** `[completar]`

---

## CMP-05 · Consultar el estado de una donación

**Origen:** `[completar]`

**CA-05.1** `[completar]`

---

## Estados de una donación

`[completar]` → `[completar]` → `[completar]`

`[¿Una donación puede volver atrás? ¿Qué pasa si nadie la toma antes de la hora
límite? Decidirlo aquí, no en el código.]`

---

## Fuera del alcance del MVP

Reportes de impacto y exportación · panel de indicadores · notificaciones
automáticas · asignación automática de destino · gestión avanzada de usuarios.

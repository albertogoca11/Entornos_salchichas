# Planning Poker – FitDAM Reserva

## Equipo Scrum
- **Product Owner:** Alberto González
- **Scrum Master:** Lorgio Arteaga
- **Developers:** Ángel Menéndez y Fernando Moret

## Objetivo
Estimar el esfuerzo relativo de las historias de usuario del Product Backlog antes de planificar los Sprints.

## Escala de estimación
Se utilizan los valores de la secuencia Fibonacci: **1, 2, 3, 5, 8 y 13 Story Points**.

## Cómo se desarrolla la votación
1. El Product Owner explica la historia y sus criterios de aceptación.
2. Los Developers (Ángel y Fernando) eligen una carta en privado y votan simultáneamente.
3. Se muestran los votos al mismo tiempo.
4. Si hay diferencias, se comentan los motivos y se vuelve a votar.
5. Se registra la estimación acordada por los Developers.

## Ronda simulada

| Historia | Voto A | Voto B | Acuerdo simulado (SP) | Justificación |
|---|---:|---:|---:|---|
| [HU01](https://github.com/albertogoca11/Entornos_salchichas/issues/9) | 3 | 5 | 3 | Consulta de horarios y plazas en una vista. |
| [HU02](https://github.com/albertogoca11/Entornos_salchichas/issues/10) | 5 | 8 | 5 | Reserva y confirmación con actualización simulada de plazas. |
| [HU03](https://github.com/albertogoca11/Entornos_salchichas/issues/11) | 3 | 3 | 3 | Cancelación de una reserva activa y liberación de plaza. |
| [HU04](https://github.com/albertogoca11/Entornos_salchichas/issues/12) | 8 | 13 | 8 | Alta y confirmación de pago en el prototipo, con pago simulado. |
| [HU05](https://github.com/albertogoca11/Entornos_salchichas/issues/13) | 3 | 5 | 3 | Un aviso con clase, hora y sala. |
| [HU06](https://github.com/albertogoca11/Entornos_salchichas/issues/14) | 3 | 3 | 3 | Consulta del listado por clase. |
| [HU07](https://github.com/albertogoca11/Entornos_salchichas/issues/15) | 5 | 8 | 5 | Alta, edición y cancelación de clases con datos de ejemplo. |
| [HU08](https://github.com/albertogoca11/Entornos_salchichas/issues/16) | 5 | 8 | 5 | Solicitud y consulta de estado, sujetas a confirmar el alcance. |

## Planificación propuesta

### Sprint 1
**Sprint Goal:** permitir consultar las clases, comprobar las plazas, reservar y cancelar reservas.

- HU01 – Consultar horario y plazas: 3 puntos.
- HU02 – Reservar una clase: 5 puntos.
- HU03 – Cancelar una reserva: 3 puntos.

**Total planificado: 11 puntos.**

### Sprint 2
**Sprint Goal:** ampliar la aplicación con el registro y pago de nuevos socios y las herramientas de gestión.

- HU04 – Registro y pago de cuota: 8 puntos.
- HU05 – Recibir recordatorios: 3 puntos.
- HU06 – Consultar lista de asistentes: 3 puntos.
- HU07 – Gestionar clases: 5 puntos.


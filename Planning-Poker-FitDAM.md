# Planning Poker – FitDAM Reserva

> **SIMULACIÓN FICTICIA PARA EL EJERCICIO ACADÉMICO.** Estos votos y debates son un ejemplo inventado para documentar cómo podría desarrollarse la sesión. No deben presentarse como una votación que el equipo haya realizado realmente. Si hacéis la sesión, sustituidlos por los votos reales.

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

## Resultado de la votación simulada

| Historia | Voto Ángel | Voto Fernando | Debate simulado y acuerdo | Estimación final simulada |
|---|---:|---:|---|---:|
| HU01 – Consultar horario y plazas | 3 | 5 | Fernando considera que organizar la información puede llevar más trabajo; tras revisar que solo se muestran horario y plazas, acuerdan 3. | **3 SP** |
| HU02 – Reservar una clase | 5 | 8 | La reserva requiere comprobar disponibilidad y actualizar plazas. Tras aclarar que el flujo es sencillo, acuerdan 5. | **5 SP** |
| HU03 – Cancelar una reserva | 3 | 3 | Ambos consideran que cancelar y liberar una plaza tiene una complejidad similar y mantienen 3. | **3 SP** |
| HU04 – Registro y pago de cuota | 8 | 13 | Fernando valora el flujo de pago como más complejo; tras delimitarlo a un formulario y confirmación del importe, acuerdan 8. | **8 SP** |
| HU05 – Recibir recordatorios | 3 | 5 | Debaten la configuración del aviso; al limitarlo a un recordatorio previo con datos de la clase, acuerdan 3. | **3 SP** |
| HU06 – Consultar lista de asistentes | 3 | 3 | Coinciden en que consiste en mostrar las personas inscritas y mantienen 3. | **3 SP** |
| HU07 – Gestionar clases | 5 | 8 | La creación, edición y cancelación añaden trabajo; tras concretar que se trata de operaciones básicas, acuerdan 5. | **5 SP** |
| HU08 – Solicitar baja del contrato | 5 | 8 | La gestión de la solicitud podría añadir complejidad; acuerdan 5 para una solicitud sencilla con consulta de estado. | **5 SP** |

### Conclusión de la sesión simulada
Las diferencias de estimación se resolvieron aclarando el alcance y los criterios de aceptación de cada historia. Los Developers llegaron a un consenso para las ocho estimaciones. Las historias HU01, HU02 y HU03 suman **11 Story Points** para el Sprint 1. Las historias HU04, HU05, HU06 y HU07 suman **19 Story Points** para el Sprint 2. HU08 queda en el Product Backlog, pendiente de validar su alcance con el cliente.

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

**Total planificado: 19 puntos.**

HU08 permanece en el Product Backlog hasta que el Product Owner confirme con el cliente si la baja contractual forma parte del alcance de la primera versión.

## Datos de la sesión
- **Tipo:** simulación ficticia de Planning Poker.
- **Fecha:** no registrada.
- **Participantes representados:** Ángel Menéndez y Fernando Moret (Developers); Alberto González (Product Owner); Lorgio Arteaga (Scrum Master).

# BioNest — Sistema de Ectogénesis Artificial para Conservación de Especies

**Cátedra:** Gestión de Proyectos · FIUNER · 2026  
**Grupo:** 6  
**Sponsor ficticio:** NestBiotech  
**Dashboard en vivo:** [sheilariffel.github.io/bioNEST](https://sheilariffel.github.io/bioNEST/)

---

## Descripción del proyecto

BioNest es un proyecto conceptual de I+D que propone el desarrollo de un prototipo funcional de sistema de incubación gestacional extrauterina (ectogénesis artificial), orientado a la conservación de especies en peligro crítico de extinción.

La especie de referencia es el rinoceronte blanco del norte (*Ceratotherium simum cottoni*). La validación inicial del sistema se realiza con parámetros fisiológicos de lagomorfos (*Oryctolagus cuniculus*), por su ciclo de gestación corto (~31 días), viabilidad ética y costo-eficiencia.

El sistema replica de forma controlada las condiciones del entorno intrauterino mediante un receptáculo bioimpreso, circuitos de soporte vital (bombeo, oxigenación, diálisis, inyección), una matriz de sensores y un Dashboard de monitoreo en tiempo real.

---

## Equipo

| Integrante | Rol |
|---|---|
| Mateo Anderson | Bioingeniero — Electrónica y Control |
| Belen Hornus | Bioingeniera — Diseño de Subsistemas |
| Sheila Riffel | Gestora de Calidad |

El equipo ficticio completo (14 roles) incluye figuras como Bugs Bunny (Director de Proyecto), Judy Hopps (Jefe de Ingeniería), Roger Rabbit (Biotecnólogo), Lola Bunny (Desarrolladora de Software), y los rinocerontes Sudan, Najin y Fatu como sponsor y referencia del caso de conservación.

---

## Ciclo de vida

El proyecto adopta un enfoque híbrido:

- **Fases 1 y 4** — Predictivas (Waterfall), con planificación detallada y entregables formales definidos.
- **Fases 2 y 3** — Adaptativas (Kanban), con tablero de flujo, límites WIP y Stage-Gates como criterios de avance entre subfases.

Los Stage-Gates S1 a S6 operan como validaciones formales de cada subsistema antes de habilitar la integración final.

---

## Estructura del repositorio

```
/
├── index.html              # Dashboard interactivo del proyecto (GitHub Pages)
├── docs/
│   ├── 00-caso-y-equipo/   # Caso de estudio y composición del equipo
│   ├── 01-plan-inicial/    # E1 — Ciclo de vida, entregables, organización
│   ├── 02-wbs-estimaciones/# E2 — WBS, cronograma, red de tareas, PERT Delphi
│   ├── 03-recursos-raci/   # E3 — Matriz RACI y asignación de recursos
│   ├── 04-riesgos/         # E4 — Registro de riesgos, matriz P×I, plan de respuesta
│   └── 05-comunicaciones-cambios/ # E5 — Plan de comunicaciones y gestión de cambios
└── img/                    # Fotografías del equipo (Sudan, Najin, Fatu, etc.)
```

---

## Entregables del curso completados

| ID | Entregable | Contenido principal |
|---|---|---|
| E1 | Plan Inicial | Ciclo de vida híbrido, entregables formales, organización del equipo |
| E2 | WBS y Estimaciones | 44 tareas en 4 fases, PERT Delphi con 3 expertos, TE total = 1616 hs |
| E3 | Recursos y RACI | Matriz RACI de 43 subtareas × 14 roles, asignación y recálculo de estimaciones |
| E4 | Gestión de Riesgos | 8 riesgos (condición → consecuencia), matriz P×I, plan de respuesta para los 3 prioritarios |
| E5 | Plan de Comunicaciones | 10 comunicaciones formales, plantillas C.1 (Informe de Avance) y C.2 (Kanban Review) |
| EF | PechaKucha | Presentación 20×20 s estructurada como pitch de inversión |

---

## Dashboard

El archivo `index.html` contiene el panel de gestión del proyecto completo, accesible en:

**[https://sheilariffel.github.io/bioNEST/](https://sheilariffel.github.io/bioNEST/)**

Incluye: Home, Alcance, Stakeholders, Equipo, Plan de Comunicaciones, Ciclo de Vida, WBS completa (44 tareas), Roadmap visual, Estimaciones PERT, Tablero Kanban interactivo, Stage-Gates, Matriz RACI, Métricas de flujo, Registro de Riesgos, Plan de Respuesta, Evolución de riesgos, Matriz P×I y Bibliografía científica.

---

## Tecnologías utilizadas

- HTML / CSS / JavaScript vanilla — dashboard sin dependencias externas
- Fuentes: DM Sans, DM Mono, Playfair Display (Google Fonts)
- GitHub Pages para el despliegue del dashboard

---

*FIUNER · Facultad de Ingeniería de la Universidad Nacional de Entre Ríos · Gestión de Proyectos 2026*

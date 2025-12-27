# Arquitectura Dimensional basada en Procesos y Steps

> Un sistema para construir, observar y evolucionar procesos complejos  
> sin perder control, contexto ni trazabilidad.

---

## 🧠 ¿Qué es este proyecto?

Este repositorio define una **arquitectura open source** donde:

- Todo ocurre dentro de **procesos**
- Los procesos están compuestos por **steps observables**
- El comportamiento está gobernado por **dimensiones explícitas**
- Las decisiones críticas se modelan como **EITL (Event In The Loop)**
- La evolución del sistema se gestiona mediante **RFCs**

No es un framework.
No es una app.
Es una **base conceptual y operativa** para sistemas humanos, de IA o híbridos.

---

## 🧩 Principios fundamentales

- 🔍 **Observabilidad primero**  
  Nada relevante ocurre sin dejar rastro.

- 🪜 **Nada existe fuera de un proceso**  
  Todo cambio sucede dentro de un proceso compuesto por steps.

- 🧭 **Las dimensiones gobiernan el comportamiento**  
  Seguridad, privacidad, afinidad, simulación, patrones, etc.

- 🧬 **La evolución es explícita y reversible**  
  Nada se “rompe”, todo se reemplaza con criterio.

- 🤝 **Simetría estructural entre humanos, IA y otras entidades**  
  Cambia el actor, no la arquitectura.

---

## 🪜 Conceptos clave

### Process
Entidad de ejecución con historia, contexto y ciclo de vida.

### Step
Unidad mínima observable.
Un step puede:
- recibir eventos
- evaluar condiciones
- decidir no cambiar nada
- emitir EITL
- continuar o finalizar

📌 Existen eventos **antes**, **durante** y **después** de un step.

---

### EITL (Event In The Loop)
Evento que requiere atención consciente.

Puede ser atendido por:
- humanos
- agentes de IA
- otros procesos
- orquestaciones mixtas

---

### Dimensiones
Estructuras que definen *cómo* se comporta algo, no *qué* es.

Ejemplos:
- Seguridad
- Privacidad
- Afinidad
- Simulación
- Patrón
- Tipos
- Umbral
- Física / Digital

---

### Patrones
Orquestadores de múltiples dimensiones.

- No ejecutan
- No deciden por sí solos
- Coordinan
- Pueden evolucionar o ser invalidados

---

## 🧾 RFCs (Request For Comments)

Toda decisión importante se define mediante un RFC.

Los RFCs:
- documentan intención
- habilitan discusión
- permiten simulación
- dejan historia observable

📂 Todos los RFC viven en [`./rfcs`](./rfcs)

---

## 📑 Índice de RFCs

### Core

- [`RFC-0000.md`](./rfcs/RFC-0000.md) — Seed Canónico del Sistema
- [`RFC-0001.md`](./rfcs/RFC-0001.md) — Core Architecture
- [`RFC-0002.md`](./rfcs/RFC-0002.md) — Step Model & Lifecycle
- [`RFC-0003.md`](./rfcs/RFC-0003.md) — EITL (Event In The Loop)
- [`RFC-0004.md`](./rfcs/RFC-0004.md) — Context & Inheritance
- [`RFC-0005.md`](./rfcs/RFC-0005.md) — Dimensional Model

---

### Governance & Evolution

- [`RFC-0007.md`](./rfcs/RFC-0007.md) — Pattern Model & Orchestration
- [`RFC-0012.md`](./rfcs/RFC-0012.md) — RFC as Dimension
- [`RFC-0013.md`](./rfcs/RFC-0013.md) — CRD as Dimension
- [`RFC-0006.md`](./rfcs/RFC-0006.md) — Simulation as a Dimension

---

### Security, Privacy & Control

- [`RFC-0008.md`](./rfcs/RFC-0008.md) — Pattern Security
- [`RFC-0011.md`](./rfcs/RFC-0011.md) — Affinity Dimension
- [`RFC-0009.md`](./rfcs/RFC-0009.md) — Anomaly Detection & EEP
- [`RFC-0010.md`](./rfcs/RFC-0010.md) — Observable Entropy
- [`RFC-0014.md`](./rfcs/RFC-0014.md) — The Creator


---

## 🤝 Cómo contribuir

- 📄 Leé [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- 🧠 Leé el [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md)
- 🧾 Usá el template [`rfcs/RFC-000-template.md`](./rfcs/RFC-000-template.md)

Este proyecto prioriza:
- claridad
- pensamiento sistémico
- evolución consciente

---

## 📜 Licencia

Este proyecto se distribuye bajo licencia **Apache License 2.0**.

Ver [`LICENSE`](./LICENSE).## 📜 Licencia


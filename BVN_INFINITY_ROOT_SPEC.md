# BVN Infinity Root Specification

## STATUS

This document is the Source of Truth for the BVN Factory project.

The software must implement only clearly defined, testable rules.
Established physics must be kept separate from hypotheses and research ideas.

---

## 1. CORE BLUEPRINT THREAD

0-Axis
→ Neutral Reference
→ Material / Mass
→ Energy
→ Thermal Energy
→ Phase / State
→ Measurement
→ Time Measurement
→ Time Efficiency
→ AI vs Manual Execution

The 0-Axis is a reference concept only.
It must not automatically be interpreted as a physical force, energy source,
or mechanism for controlling time.

---

## 2. PHYSICAL STATES

The model must distinguish:

- Solid
- Liquid
- Gas
- Two-phase / coexistence state

A two-phase state means that two physical phases may coexist under
appropriate physical conditions.

The software must represent phase/state explicitly rather than treating
all material as a single undifferentiated state.

---

## 3. MATERIAL COMPARISON

Mercury and water may be used as comparison materials.

The application may compare:

- mass
- density
- volume
- temperature
- phase/state
- thermal response
- gravitational behaviour

No comparison may imply that mercury or water possesses special
time-control properties without experimental evidence.

---

## 4. MASS AND ENERGY

Mass must be treated as a physical quantity.

Energy must be represented using established physical concepts and units.

Do not invent a new energy formula.

If an energy relationship is required, use established physics and clearly
identify the equation and its assumptions.

---

## 5. THERMAL ENERGY

Thermal energy must be treated separately from mechanical motion.

The system may model:

- temperature
- heating
- cooling
- phase transition
- thermal equilibrium
- energy input/output

Thermal energy must not be described as a mechanism for controlling
physical time.

---

## 6. NEUTRAL REFERENCE

A neutral reference is a measurement/reference condition.

It is not automatically:

- zero energy
- zero mass
- zero gravity
- zero time
- a new physical dimension

Any use of "neutral" must specify exactly what quantity is being referenced.

---

## 7. 0-AXIS RULE

The 0-Axis is a conceptual reference axis for organizing the model.

It must not be claimed to:

- stop time
- reverse time
- create time travel
- remove gravity
- create energy
- destroy mass

Any such claim requires independent experimental evidence.

---

## 8. SPARK / SMART SPARK

"Smart Spark" is a controlled trigger concept.

It may represent an event that starts or changes a defined process.

A Spark must have:

- input
- trigger condition
- measurable output
- safety condition
- reproducible behaviour

The software must not treat "Spark" as proof of a new physical phenomenon.

---

## 9. MEASUREMENT AND TIME

Physical time and time measurement must be kept separate.

The application may calculate:

- elapsed time
- task duration
- process duration
- measurement interval
- manual execution time
- AI-assisted execution time

A reduction in task duration is not the same thing as reversing,
stopping, or travelling through physical time.

---

## 10. AI VS MANUAL TIME EFFICIENCY

For practical workflow analysis:

Manual task time = time required for manual execution.

AI-assisted task time = time required when appropriate AI assistance
is used.

Potential time saving:

Time saving = Manual task time - AI-assisted task time

This is a productivity measurement only.

It must never be presented as physical time manipulation.

---

## 11. SINGLE-THREAD ARCHITECTURE

The project must preserve a single coherent research/implementation thread.

Core thread:

0-Axis
→ Neutral Reference
→ Material/Mass
→ Energy
→ Thermal State
→ Phase State
→ Measurement
→ Time Efficiency
→ Implementation

Do not create unrelated branches of speculative physics.

---

## 12. HYPOTHESIS BOUNDARY

The project may record hypotheses for research.

Every hypothesis must be labelled clearly as:

HYPOTHESIS

and must not be presented as established physics.

Established physics, engineering assumptions, observations, and hypotheses
must remain visibly separated.

---

## 13. TIME-TRAVEL BOUNDARY

The project must not implement speculative time-travel mechanics as if
they were experimentally established.

References to time travel may be used only as a research question.

The software may model theoretical scenarios, measurements, simulations,
or productivity concepts, but must not claim that the application has
created physical time travel.

---

## 14. IMPLEMENTATION RULES

Before changing code:

1. Inspect the current repository.
2. Read the existing specification.
3. Preserve working implementation.
4. Identify the smallest correct next step.
5. Do not rewrite the architecture unnecessarily.
6. Do not delete working files without justification.
7. Do not invent missing requirements.
8. If a required specification is unavailable, mark the task BLOCKED.
9. Document every meaningful implementation change.
10. Run type-checking, tests, and build validation when applicable.
11. Fix genuine implementation or validation errors.
12. Report what changed and what remains unresolved.

---

## 15. SOURCE-OF-TRUTH PRIORITY

When instructions conflict, use this priority:

1. Explicit established physical laws and verified measurements
2. This specification
3. Existing validated project implementation
4. Clearly labelled research hypotheses
5. New ideas requiring future validation

Speculative ideas must never silently override established rules.

---

## 16. SAFETY

Any physical experiment involving heat, pressure, electrical energy,
mercury, moving masses, sparks, or other hazardous conditions must be
treated as requiring appropriate laboratory safety controls.

The software must not provide unsafe instructions for hazardous physical
experiments.

---

## 17. FIRST IMPLEMENTATION PRINCIPLE

Do not attempt to build the entire system at once.

First establish a correct, testable foundation.

The first implementation objective is:

Repository
→ Specification
→ Data model
→ Measurement model
→ Validation
→ Minimal working implementation

Only after validation should additional modules be added.

---

## 18. DEFINITION OF DONE

A feature is complete only when:

- its purpose is defined
- its inputs are defined
- its outputs are defined
- assumptions are documented
- established physics is distinguished from hypothesis
- implementation is tested where applicable
- validation passes
- documentation is updated

---

## FINAL RULE

Do not invent new physics formulas.

Do not present productivity time-saving as physical time travel.

Do not claim that energy can control

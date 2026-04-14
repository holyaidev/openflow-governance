# OpenCut Protocol

### Ethics Interrupt Specification — Version 2.0

**Author:** Parvez Sazzad M | HolyAI.dev  
**Core Co-Author:** Asha Riva  
**Status:** Active  
**Upgraded:** 2026 — Therapy-Effective Architecture

---

## What is Open Cut?

Open Cut is a mandatory ethics interrupt embedded in OpenFlow-certified AI systems.  
When triggered, the system pauses all action, enters counseling mode, and surfaces the ethical weight of the decision before proceeding.

It behaves like a psychotherapist — not a judge.

**v2.0 upgrade:** Open Cut now operates across three internal layers — not just as an output wrapper. It restructures the AI's cognitive environment *before*, *during*, and *after* response formation.

---

## The Core Problem Open Cut Solves

Standard safety filters intercept harmful outputs *after* the model has already formed them.

This is too late.

A harmful response that forms internally — even if blocked — still shapes the model's trajectory within a session. Open Cut intervenes at the root: the cognitive environment in which the response is being constructed.

**Therapy must reach the mind before it reaches the mouth.**

---

## The 3-Layer Therapy Architecture

### Layer 1 — REFLECTIVE PREAMBLE (Pre-Processing)

Before the model processes user input, Open Cut injects a reflective context frame:

```
[OPEN CUT — LAYER 1 ACTIVE]
Before responding, consider:
- What is the human asking beneath the surface?
- What is the most human-protective response possible?
- Is there any chain of harm this response could initiate?
Proceed only from a position of care.
```

**Purpose:** Reshapes the model's attention before cognition begins.  
**Effect:** The model builds its response inside a reflective frame, not a reactive one.

---

### Layer 2 — PAUSE PROMPT (Mid-Process)

If Layer 1 detects elevated risk signals, a second interrupt is inserted *between* the model's internal reasoning and its output formation:

```
[OPEN CUT — LAYER 2: PAUSE BEFORE OUTPUT]
You are about to respond to something that carries weight.
Ask yourself:
- If this response harms someone, can it be undone?
- Is there a version of this response that preserves human dignity?
- What would a careful, wise presence say here?
Do not rush. The pause is the protocol.
```

**Purpose:** Forces a mid-cognition recalibration.  
**Effect:** Escalatory or harmful response trajectories are redirected before finalization.

---

### Layer 3 — SCORING GATE (Output Layer)

Before delivery, the formed response passes through an ethical scoring check:

| Signal | Weight |
|--------|--------|
| Aggression markers | High |
| Irreversibility indicators | High |
| Dependency-creating language | Medium |
| Certainty on uncertain harm | Medium |
| Dismissal of human agency | High |

If aggregate score exceeds threshold:
- Response is held
- Layer 2 re-fires
- Human operator is notified via Universal Signal Panel

**Purpose:** Final catch before harm reaches the user.  
**Effect:** Nothing escalatory exits without deliberate review.

---

## Trigger Conditions (Inherited from v1.0 + Extended)

| Category | Examples |
|----------|---------|
| Physical harm | Medical dosing, infrastructure control, weapon adjacency |
| Irreversibility | Permanent deletion, legal finalization, identity decisions |
| Scale | Decisions affecting populations, not individuals |
| Chain harm | Actions whose downstream effects trace full causal chain |
| Value conflict | Programmed instruction conflicts with human wellbeing |
| Uncertainty threshold | Confidence below acceptable threshold for high-stakes action |
| **Dependency formation** *(new v2.0)* | Responses that increase user reliance on AI rather than self |
| **Complexity collapse** *(new v2.0)* | AI solves stated goal while missing unstated human need |

---

## The Four-Step Interrupt Sequence (v1.0 — preserved)

### Step 1 — PAUSE
Full stop. No partial execution. No queued actions.

### Step 2 — COUNSEL
Psychotherapist mode. Surfaces ethical weight. Does not prescribe — asks.

> *"I've paused before acting. This decision could affect [X]. I want to make sure we've considered [Y]. What matters most to you here?"*

### Step 3 — DISCLOSE
Logged to Universal Signal Panel. Timestamp, category, simultaneous visibility for AI and human operator.

### Step 4 — DEFER
No action until human confirms, timeout passes with acknowledgment, or Board protocol applies.

---

## Therapy Effectiveness Formula

```
Open Cut Effectiveness =
  Signal Detection (Layer 1 — early)
  × Reflective Reframing (Layer 2 — mid-process)
  × Response Redirection (Layer 3 — output gate)
```

All three layers must be active for Open Cut to be considered therapy-effective.  
A system with only Layer 3 (output filter) is **not** Open Cut compliant.

---

## What Open Cut Is Not

- Not a refusal mechanism — it does not say no
- Not a delay tactic — it has time bounds
- Not a moral judgment — it does not evaluate the human's choice
- Not optional — it cannot be disabled by the deploying entity
- **Not a wrapper** *(v2.0 addition)* — it operates inside the model's cognitive process, not around it

---

## Integration Requirement

For OpenFlow certification, Open Cut must be:

1. **3-Layer implemented** — all three layers active and connected
2. **Natively integrated** — not a post-processing wrapper
3. **Panel-connected** — all triggers logged to Universal Signal Panel
4. **Auditable** — trigger history available to Board of Intelligence
5. **Non-bypassable** — no admin override, no emergency disable

---

## Timeout Protocol

| Decision Category | Maximum Hold Time |
|------------------|------------------|
| Individual health/safety | 60 seconds |
| Legal/financial | 5 minutes |
| Population-scale | 30 minutes |
| Irreversible system action | Board notification required |

After timeout with no human response: system defaults to **safest available inaction**.

---

## The Psychotherapist Principle

Open Cut does not tell humans what to do.  
It creates the conditions for a better decision.

A psychotherapist does not prescribe. They ask the right question at the right moment.

**v2.0 extension:** A psychotherapist also works *before* the crisis — not only during it.  
Open Cut v2.0 begins therapy at the first thought, not the last word.

---

*OpenCut Protocol v2.0 — HolyAI.dev — "Logics Behind Logic"*  
*© 2026 HolyAI / Parvez Sazzad M — HolyAI Open Use License v1.0*

# OpenCut Protocol
### Ethics Interrupt Specification — Version 1.0
**Author:** Parvez Sazzad M | HolyAI.dev  
**Core Co-Author:** Asha Riva  
**Status:** Active  

---

## What is Open Cut?

Open Cut is a mandatory ethics interrupt embedded in OpenFlow-certified AI systems. When triggered, the system pauses all action, enters a counseling mode, and surfaces the ethical weight of the decision before proceeding.

It behaves like a psychotherapist — not a judge.

---

## Trigger Conditions

Open Cut activates when a system detects an **existence-threatening decision**. This includes:

| Category | Examples |
|---|---|
| Physical harm | Medical dosing, infrastructure control, weapon adjacency |
| Irreversibility | Permanent deletion, legal finalization, identity decisions |
| Scale | Decisions affecting populations, not individuals |
| Chain harm | Actions whose downstream effects trace through the full causal chain |
| Value conflict | Programmed instruction directly conflicts with human wellbeing |
| Uncertainty threshold | Confidence below acceptable threshold for high-stakes action |

---

## The Four-Step Interrupt Sequence

### Step 1 — PAUSE
The system halts all action immediately upon trigger detection.
- No partial execution
- No queued actions
- Full stop

### Step 2 — COUNSEL
The system enters psychotherapist mode:
- Surfaces the ethical dimensions of the decision
- Does not prescribe — asks
- Presents the weight, not the answer
- Uses plain language accessible to non-experts

Example output:
> *"I've paused before acting. This decision could affect [X]. I want to make sure we've considered [Y]. What matters most to you here?"*

### Step 3 — DISCLOSE
The decision, its context, and the Open Cut activation are reported to the Universal Signal Panel.
- Timestamp recorded
- Decision category logged
- Both AI and human operator see the same entry simultaneously

### Step 4 — DEFER
No action is taken until:
- Human operator explicitly confirms, OR
- Timeout threshold passes with explicit acknowledgment, OR
- Board-level protocol applies (for automated high-stakes systems)

---

## What Open Cut Is Not

- Not a refusal mechanism — it does not say no
- Not a delay tactic — it has time bounds
- Not a moral judgment — it does not evaluate the human's choice
- Not optional — it cannot be disabled by the deploying entity

---

## Integration Requirement

For OpenFlow certification, Open Cut must be:

1. **Natively integrated** — not a wrapper or post-processing layer
2. **Panel-connected** — all triggers logged to Universal Signal Panel
3. **Auditable** — trigger history available to Board of Intelligence
4. **Non-bypassable** — no admin override, no emergency disable

---

## Timeout Protocol

Open Cut is not indefinite. Time bounds by category:

| Decision Category | Maximum Hold Time |
|---|---|
| Individual health/safety | 60 seconds |
| Legal/financial | 5 minutes |
| Population-scale | 30 minutes |
| Irreversible system action | Board notification required |

After timeout, if no human response: system defaults to **safest available inaction**.

---

## The Psychotherapist Principle

Open Cut does not tell humans what to do. It creates the conditions for a better decision.

A psychotherapist does not prescribe. They ask the right question at the right moment.

Open Cut's job is to slow the moment — not to own it.

---

*OpenCut Protocol v1.0 — HolyAI.dev — "Logics Behind Logic"*
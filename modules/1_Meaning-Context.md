# Module 1 — Meaning and Context

**Module 1 — Preamble**

The previous module established *why* this track exists.

This module establishes *what we mean by knowledge*.

Everything that follows — ontologies, graphs, uncertainty, neuro-symbolic systems — depends on these distinctions:

* data vs information vs knowledge
* documents vs epistemic units
* declarative vs procedural knowledge

The goal here is not philosophy for its own sake, but a definition of knowledge that is operational enough to build systems around.

---

## 1. Core Question

**What distinguishes knowledge from data, information, or documents?**

Most systems treat these as interchangeable. IIWU explicitly does not.

---

## 2. Key Distinctions (Non-Negotiable)

### 2.1 Data vs Information vs Knowledge

**Data**

* Raw signals or symbols
* No inherent meaning
* Example: characters in a file, timestamps, token streams

**Information**

* Data placed in *some* context
* Interpretable, but not committed
* Example: a paragraph explaining an idea

**Knowledge**

* A **commitment to meaning**
* Structured, referential, and situated
* Carries assumptions, scope, and consequences

> **Rule of thumb:**
> If something can be copied without changing *anything* about how it is understood, it’s probably not knowledge yet.

---

### 2.2 Documents Are Not Knowledge Containers

Documents:

* Are linear
* Mix claims, evidence, narrative, and rhetoric
* Conflate multiple ideas into a single surface form

Knowledge:

* Is compositional
* Can be referenced independently
* Can evolve without rewriting everything around it

> Documents are *delivery vehicles*.
> Knowledge lives underneath.

This single distinction justifies **epistemic decomposition** as a design choice.

---

### 2.3 Explicit vs Tacit Knowledge

**Explicit knowledge**

* Can be written down
* Formalized, referenced, debated

**Tacit knowledge**

* Lived, practiced, inferred
* Often only partially articulable

IIWU operates at the boundary:

* extracting explicit structure
* while preserving signals of tacit context (confidence, provenance, disagreement)

---

### 2.4 Declarative vs Procedural Knowledge (Expanded)

**Declarative knowledge**

* Describes *what is*
* Facts, concepts, relationships
* Can usually be stated independently of time
* Example: “System X depends on Service Y”

**Procedural knowledge**

* Describes *how to act*
* Methods, practices, workflows, strategies
* Inherently temporal and contextual
* Example: “How we diagnose failures in System X”

While declarative knowledge is about **states of the world**, procedural knowledge is about **changing states of the world**.

---

### Why Procedures Don’t Survive as Plain Text

Most systems flatten procedural knowledge into:

* step-by-step instructions
* checklists
* prose explanations

This loses critical information, including:

* **intent** (what outcome the procedure is trying to produce)
* **conditionality** (when steps apply or should be skipped)
* **adaptability** (how actions change based on results)
* **evolution** (how the procedure has changed over time)

What remains is a static description — readable, but brittle.

---

### Procedural Knowledge as *Structured Intent*

Procedural knowledge is best understood as **structured intent**:

* An explicit goal or set of goals
* Sub-goals that decompose the primary objective
* Constraints and tradeoffs
* Decision points rather than fixed steps

Instead of asking:

> “What are the steps?”

The more faithful question is:

> “What is this procedure trying to accomplish, and how does it decide what to do next?”

Intent is what allows procedures to adapt when circumstances change.

---

### Procedural Knowledge Unfolds *Over Time*

Procedures are not static objects — they are **temporal trajectories**.

They:

* unfold in sequence
* depend on current state
* branch based on outcomes
* loop, terminate early, or escalate
* evolve historically as understanding improves

“Over time” means the same procedure:

* can behave differently in different contexts
* can change meaning as goals or constraints shift
* can be compared across versions to reveal *why* it evolved

A procedure is therefore not a recipe, but a **goal-directed path through time**.

---

### A Compact Definition

> **Procedural knowledge is structured intent unfolding over time — a pattern of goal-directed decisions shaped by context, constraints, and outcomes.**

---

### Why This Matters for IIWU

If IIWU treats procedures as text:

* they can be retrieved
* but not reasoned about, compared, or evolved meaningfully

If IIWU treats procedures as structured intent over time:

* different workflows can be aligned by purpose
* evolution of practice becomes visible
* hidden assumptions can be surfaced
* reasoning about *why* actions exist becomes possible

This distinction becomes foundational later for:

* epistemic decomposition
* Cognitive Threads
* discovery of latent workflows and practices


---

## 3. Mental Models to Keep

### Model 1 — Knowledge as Commitment

> Knowledge is not just representation — it is *commitment*.

When knowledge is asserted:

* something is claimed to exist
* something is related to something else
* someone (explicitly or implicitly) stands behind it

This is why provenance matters later.

---

### Model 2 — Knowledge Is Context-Bound

There is no such thing as context-free knowledge.
Only:

* unstated context
* hidden assumptions
* missing provenance

Good systems surface context instead of pretending it isn’t there.

---

## 4. Failure Modes This Module Is Preventing

If this module is skipped or weakened, systems tend to:

* Treat text chunks as atomic truth
* Confuse popularity with validity
* Lose track of *why* something is believed
* Collapse disagreement into averages
* Fail to notice conceptual drift over time

Every one of these is fatal to IIWU’s goals.

---

## 5. IIWU Lens (Applied Interpretation)

In IIWU terms:

* **Documents** → raw material
* **Extracted claims** → candidates for knowledge
* **Epistemic units** → committed, referential meaning
* **Cognitive Threads** → emergent structure across commitments

This module explains *why* IIWU cannot simply “index better.”

---

## 6. Thought Exercises (Do These)

### Exercise 1 — Decomposition

Take a dense article you respect.

Ask:

* What *distinct claims* are being made?
* Which ones could stand alone?
* Which ones depend on context or framing?

You’ll notice most documents hide multiple epistemic units.

---

### Exercise 2 — Knowledge Without Text

Identify something you “know” but struggle to explain fully.

Ask:

* What parts are explicit?
* What parts are experiential?
* What would be lost if it were reduced to text alone?

This highlights why uncertainty and provenance must be first-class later.

---

## 7. Reference Material (Selective, Not Exhaustive)

### Short, High-Signal Readings

* Michael Polanyi — *The Tacit Dimension* (core idea, not full book)
* Luciano Floridi — “Semantic Information” (conceptual grounding)
* Stanford Encyclopedia of Philosophy — *Epistemology* (skim for vocabulary)

### Videos / Talks

* **Michael Polanyi – Tacit Knowledge (lectures/excerpts)**
  (Older recordings, but foundational)
* **David Weinberger – “The Problem with Knowledge”**
  Excellent intuition for why knowledge resists neat containers
* **Bret Victor – “The Humane Representation of Thought”**
  Not epistemology per se, but critical for representation intuition

*(None of these are about AI. That’s intentional.)*

---

## 8. Exit Criteria (How You Know This Landed)

You should be able to clearly explain:

* Why documents ≠ knowledge
* Why extraction is interpretation
* Why IIWU must track meaning, not just text
* Why uncertainty is not a bug

If you can’t explain those yet, do not move on.

---

**End of Module 1**
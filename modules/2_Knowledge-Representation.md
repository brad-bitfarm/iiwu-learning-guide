### Module 2 — Knowledge Representation: The Design Space

**Module 2 — Preamble**

In Module 1, we clarified that knowledge is **committed meaning with structure, context, and intent**.
This module asks the next unavoidable question:

> *If knowledge is structured, what forms can that structure take?*

The goal is to understand the **design space of knowledge representation**:

* what different representations make possible
* what they obscure or distort
* why no single representation is sufficient

This module is about *choices and tradeoffs*, not prescriptions.

---

## 1. Core Question

**How can knowledge be represented in a system so that it can be reasoned about, compared, and evolved?**

Representation is the lens through which we can:

* capture meaning
* surface relationships
* track provenance
* enable reasoning and discovery

---

## 2. Major Representation Families

### 2.1 Symbolic Representations

* **Logic / Rules**: e.g., propositional logic, first-order logic

  * Strong for deduction, consistency, and validation
  * Weak for nuance, tacit knowledge, and exceptions
* **Frames / Schemas**: structured templates for entities

  * Good for inheritance and defaults
  * Can become rigid if over-specified
* **Ontologies**: formal description of entities, classes, and relations

  * Provide shared vocabulary and constraints
  * Can be brittle under drift

**Mental model:** Symbolic systems are **explicit lenses**: they reveal what you *choose to model* and hide the rest.

---

### 2.2 Sub-symbolic Representations

* **Vector embeddings** (dense numeric representations)

  * Capture similarity and latent patterns
  * Flexible, tolerant of noise
  * Hard to interpret or reason over explicitly
* **Probabilistic models** (Bayesian networks, HMMs, etc.)

  * Represent uncertainty, dependencies, and likelihoods
  * Often opaque, harder to enforce constraints

**Mental model:** Sub-symbolic systems are **pattern detectors** — they find what emerges from data rather than what is explicitly declared.

---

### 2.3 Hybrid Approaches

* Combine symbolic structure with sub-symbolic reasoning
* Examples:

  * Knowledge graphs with embedding-enhanced links
  * Rule-guided neural inference
* Goal: leverage strengths of both while mitigating weaknesses

**Mental model:** Hybrid systems are **propose-and-constrain architectures**:

* neural: propose patterns
* symbolic: enforce meaning

---

## 3. Core Design Considerations / Tradeoffs

| Consideration      | Symbolic | Sub-symbolic | Hybrid      |
| ------------------ | -------- | ------------ | ----------- |
| Interpretability   | High     | Low          | Medium      |
| Flexibility        | Low      | High         | Medium      |
| Precision          | High     | Low-medium   | Medium-high |
| Evolution          | Medium   | Medium-high  | High        |
| Handling ambiguity | Poor     | Good         | Good        |

**Mental model:** No single representation is perfect. Choosing one is always a *tradeoff in lens and scope*.

---

## 4. Representation is Always Context-Bound

* The same knowledge can be represented differently depending on:

  * purpose (reasoning vs retrieval vs discovery)
  * granularity (concept vs claim vs procedure)
  * constraints (computational, epistemic, operational)
* **Rule of thumb:** the representation *shapes what you can discover*, so choose deliberately.

---

## 5. Failure Modes This Module Avoids

Without clarity here, systems tend to:

* Collapse everything into one format (e.g., vector embeddings only)
* Treat representations as neutral (they’re lenses!)
* Ignore provenance and intent when mapping knowledge
* Fail to capture procedural, tacit, or evolving aspects
* Assume reasoning emerges automatically from scale

---

## 6. Thought Exercises

### Exercise 1 — Map a Single Fact

Take a fact or claim from a document and try representing it in three ways:

1. As a logic statement or rule
2. As a node in a graph (or ontology triple)
3. As an embedding vector (or probabilistic pattern)

Ask yourself:

* What did each method preserve?
* What did each method lose?
* How easy would reasoning or discovery be in each form?

---

### Exercise 2 — Compare Representational Goals

Pick a workflow you care about (procedural knowledge, scientific experiment, engineering decision).
Ask:

* What would I need to represent for humans to reason about it?
* What would I need for a machine to propose insights?
* Where might hybrid approaches help?

---

## 7. Reference Material (Selective)

### Readings

* John F. Sowa — *Knowledge Representation: Logical, Philosophical, and Computational Foundations* (intro chapters)
* Patrick Hayes — *Naive Physics Manifesto* (conceptual grounding)
* Russell & Norvig — *Artificial Intelligence: A Modern Approach*, Chapter 7 (representations overview)

### Videos

* David MacKay — *Information Theory and Representation* (MIT lecture)
* Jim Hendler — *The Promise of Semantic Web / Ontologies* (short, accessible)
* Bret Victor — *The Humane Representation of Thought* (applied intuition for structural representation)

---

## 8. IIWU Lens

* KR is the reason IIWU can **decompose documents into epistemic units**
* Symbolic structure preserves **meaning, identity, constraints**
* Sub-symbolic methods capture **patterns, latent similarity, and uncertainty**
* Hybrids allow **reasoning plus discovery**, forming the foundation for Cognitive Threads

**Exit Criteria**

* You can list major representation families and their tradeoffs
* You understand why representation choice shapes discovery
* You can articulate why IIWU must use **pluralistic representation** internally

---

**End of Module 2**

### Module 5 — Annotation, Extraction, and Interpretation

**Module 5 — Preamble**

Module 4 established graphs as the relational substrate for knowledge.
This module examines **how raw material — documents, text, and other artifacts — becomes structured knowledge**.

Key points from previous modules that apply here:

* Knowledge is committed meaning with structure, context, and intent
* Ontologies and graphs provide formal and flexible scaffolding
* Representation choice shapes reasoning, discovery, and emergent structure
* IIWU requires attention to provenance, uncertainty, and identity from the moment knowledge is extracted

The goal of this module is to understand **annotation and extraction as interpretive acts**, and how these processes prepare knowledge for reasoning and discovery within IIWU.

---

## 1. Core Question

**How does unstructured material get transformed into structured knowledge without losing context, meaning, or uncertainty?**

---

## 2. Annotation vs Extraction

* **Annotation**: attaching semantic, contextual, or interpretive metadata to material

  * Examples: tagging concepts, marking claims, recording provenance
  * Human or machine-driven; often iterative

* **Extraction**: converting annotated material into structured representations

  * Examples: triples in a knowledge graph, formalized claims, procedural steps
  * Must preserve intent, context, and relationships

**Mental model:** Annotation is *interpretation*, extraction is *formalization*.

---

## 3. Key Principles

1. **Extraction is never neutral**

   * Every decision encodes assumptions
   * Lossless extraction is impossible; tradeoffs are explicit

2. **Context preservation**

   * Track source, surrounding content, and situational metadata
   * Required to maintain interpretability and identity

3. **Support multiple interpretations**

   * Conflicting annotations can coexist
   * Enables probabilistic reasoning and alternative perspectives

4. **Capture uncertainty and confidence**

   * Not all claims are equally supported
   * Represent confidence, credibility, and provenance explicitly

5. **Link back to representation substrates**

   * Extracted knowledge must map to ontologies and graphs
   * Ensures consistency, discoverability, and reasoning capacity

---

## 4. Failure Modes This Module Avoids

* Treating extraction as mechanical and neutral
* Ignoring ambiguity, tacit meaning, or context
* Collapsing multiple interpretations prematurely
* Losing links to provenance or identity
* Producing knowledge that cannot integrate with graphs or ontologies

---

## 5. Thought Exercises

### Exercise 1 — Annotate and Extract

* Take a short document or article
* Identify key concepts, claims, or procedures
* Annotate each with:

  * type (fact, claim, procedure)
  * provenance (source, author, date)
  * confidence (high/medium/low)
* Extract into a mini knowledge graph or triple set
* Reflect: what information was difficult to encode? What context was lost or simplified?

### Exercise 2 — Compare Interpretations

* Select a statement or paragraph
* Create two or three different annotations/extractions, each emphasizing different aspects (intent, causality, context)
* Ask: how do these differences affect downstream reasoning or discovery?

---

## 6. Reference Material (Selective)

### Readings

* Hearst, M. — *Automatic Acquisition of Hyponyms from Large Text Corpora* (classic extraction example)
* Niles & Pease — *Linking Lexicons to Ontologies*
* Uschold & King — *Towards a Methodology for Building Ontologies* (sections on annotation/extraction)

### Videos

* YouTube: *Knowledge Graph Construction from Text* (conceptual)
* MIT or Stanford lectures on *Information Extraction* and *Semantic Annotation*

---

## 7. IIWU Lens

* Annotation converts raw material into **candidate epistemic units**
* Extraction formalizes them for graphs and hybrid reasoning
* Confidence, provenance, and context metadata are **first-class**
* Multiple interpretations coexist to support probabilistic, exploratory discovery
* This module is the **bridge between unstructured data and structured meaning**, feeding all subsequent analysis in IIWU

**Exit Criteria**

* You can distinguish annotation from extraction
* You can explain why extraction is interpretive, not mechanical
* You understand the role of provenance, confidence, and context in structured knowledge
* You can produce a simple extracted representation of a document that retains uncertainty and relational structure

---

**End of Module 5**

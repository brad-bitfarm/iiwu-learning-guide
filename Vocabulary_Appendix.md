# IIWU Vocabulary Alignment Appendix

| Term                            | Module(s)  | Definition / Alignment                                                                        | Notes / IIWU Lens                                                                           |
| ------------------------------- | ---------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **Knowledge**                   | 1          | Committed meaning with context, structure, and intent                                         | The unit of epistemic commitment; distinct from raw information or data.                    |
| **Epistemic Unit**              | 1, 4, 5    | Discrete, addressable unit of knowledge that can be reasoned about, linked, and tracked       | Forms the building block for graphs, threads, and hybrid reasoning.                         |
| **Representation**              | 2          | The formal or structured encoding of knowledge for reasoning or retrieval                     | Includes symbolic, sub-symbolic, and hybrid methods; shapes what can be discovered.         |
| **Symbolic Representation**     | 2          | Explicitly structured knowledge using rules, logic, frames, or ontologies                     | High interpretability; low flexibility; suitable for constraints and validation.            |
| **Sub-symbolic Representation** | 2          | Latent, often numeric representation of knowledge patterns (embeddings, probabilistic models) | Captures patterns, similarity, and uncertainty; low interpretability.                       |
| **Hybrid Representation**       | 2, 7       | Combines symbolic and sub-symbolic methods to leverage both strengths                         | Neural proposals constrained by symbolic rules, graphs, and ontologies.                     |
| **Ontology**                    | 3          | Formal, explicit specification of a shared conceptualization                                  | Includes classes, relations, rules; supports cross-domain reasoning.                        |
| **Upper Ontology**              | 3          | Broad, abstract, cross-domain conceptual schema                                               | Provides foundational concepts and relationships.                                           |
| **Domain Ontology**             | 3          | Field-specific conceptual schema                                                              | Enables precise reasoning and discovery in a given domain.                                  |
| **Graph**                       | 4          | Nodes and edges representing entities and their relationships                                 | Serves as a relational substrate for reasoning, discovery, and representation of structure. |
| **Knowledge Graph**             | 4          | Graph where nodes are concepts or claims and edges encode relationships                       | Supports querying, pattern detection, and inference.                                        |
| **Property Graph**              | 4          | Graph where nodes and edges can carry metadata                                                | Captures context, confidence, and provenance.                                               |
| **Multi-layer / Hypergraph**    | 4          | Graph representing higher-order or complex relationships                                      | Supports multi-entity relationships and emergent pattern detection.                         |
| **Annotation**                  | 5          | Adding semantic, interpretive, or contextual metadata to raw material                         | Prepares material for structured extraction; often iterative.                               |
| **Extraction**                  | 5          | Converting annotated material into formal, structured representations                         | Preserves relationships, intent, and context; produces epistemic units.                     |
| **Uncertainty / Confidence**    | 6          | Quantitative or qualitative measure of reliability of a knowledge unit                        | Guides probabilistic reasoning and weighting in discovery.                                  |
| **Provenance**                  | 6          | Record of source, authorship, timestamp, and transformation history                           | Ensures trust, accountability, and reproducibility.                                         |
| **Identity**                    | 6          | Persistent unique reference for an entity, concept, or knowledge unit                         | Maintains consistency, tracks evolution, and supports disambiguation.                       |
| **Neuro-Symbolic System**       | 7          | Hybrid system combining neural pattern recognition with symbolic reasoning                    | Neural components propose patterns; symbolic constraints validate them.                     |
| **Emergence**                   | 8          | Patterns, insights, or structures arising from interactions among knowledge units             | Not explicitly encoded; results from hybrid reasoning over structured knowledge.            |
| **Discovery**                   | 8          | The identification of novel, latent relationships or insights                                 | Enabled by structured knowledge, hybrid reasoning, and interaction over time.               |
| **Hybrid Reasoning**            | 2, 4, 6, 7 | Integrated reasoning using symbolic rules, graphs, and neural proposals                       | Supports exploration, discovery, and pattern detection while maintaining rigor.             |


# Usage Notes

Cross-module alignment: Terms like “provenance,” “identity,” and “uncertainty” recur in multiple modules; this table ensures consistent meaning.

IIWU-specific lens: Where possible, the IIWU interpretation of a standard term is noted in the last column.

Reference: This appendix can serve as a living glossary as new modules, concepts, or features are added.
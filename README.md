# Stackmium

Topology-aware Docker Compose reasoning and infrastructure analysis.

Website: https://stackmium.com

---

## What is Stackmium?

Stackmium is an experimental infrastructure reasoning platform focused on understanding Docker Compose environments semantically instead of only syntactically.

The goal is to analyze how services relate to each other operationally:
- service role inference
- topology relationship mapping
- trust boundary reasoning
- attack propagation modeling
- contextual hardening analysis
- AI/RAG infrastructure recognition
- reasoning audit trails
- machine-readable exports

Instead of treating infrastructure as isolated containers, Stackmium attempts to reason about:
- exposure
- privilege
- propagation
- segmentation
- operational context
- infrastructure intent

---

## Current Focus Areas

- Self-hosted infrastructure
- Homelabs
- AI / RAG deployments
- Multi-service Compose environments
- Observability-heavy stacks
- Gateway-centric architectures

---

## Current Capabilities

### Semantic Infrastructure Analysis
Infers operational service roles from Compose topology and configuration patterns.

### Trust Boundary Reasoning
Attempts to identify segmentation boundaries and risky cross-zone relationships.

### Attack Propagation Modeling
Builds possible propagation paths across exposed or interconnected services.

### Contextual Hardening
Distinguishes operationally expected behavior from genuinely dangerous exposure where possible.

### AI Infrastructure Recognition
Recognizes patterns involving:
- inference gateways
- vector databases
- GPU workloads
- pipelines
- RAG architectures
- model serving topologies

### Reasoning Audit Trails
Provides visibility into why findings or relationships were inferred.

### Structured Exports
Machine-readable export formats for downstream tooling or automation.

---

## Current Limitations

This is still an active technical preview.

Known limitations include:
- Kubernetes support is not implemented yet
- Some topology inference remains probabilistic
- Flat networks can still create noisy assumptions in edge cases
- Real-world Compose diversity produces difficult semantic ambiguity
- Certain infrastructure patterns still require additional contextual suppression logic

---

## Design Direction

Recent work has focused heavily on:
- reducing speculative reasoning
- suppressing duplicate propagation chains
- contextual severity adjustment
- topology-aware inference refinement
- observability-aware privilege interpretation
- explainability and auditability

---

## Feedback Wanted

Particularly interested in:
- weird Compose files
- false positives
- misleading propagation paths
- edge-case infrastructures
- unusual AI/RAG deployments
- segmented self-hosted environments

---

## Technical Preview

Stackmium is currently available as a hosted technical preview:

https://stackmium.com

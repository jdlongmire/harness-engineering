> **This repository has been deprecated.** Active development continues at
> [agent-harness-engineering/harness-engineering](https://github.com/agent-harness-engineering/harness-engineering).
> This repo is archived and read-only.

---

# Harness Engineering

A research programme ([Lakatos, 1978](https://en.wikipedia.org/wiki/The_Methodology_of_Scientific_Research_Programmes)) investigating principled architectural patterns for LLM harness systems.

## Core Theory: The 4M Model

The core theory is the **4M Model** (Mission, Mind, Morals, Memory), which proposes that every well-formed harness addresses exactly four cognitive concerns, categorically distinct from its execution substrate (Means). Each module is grounded in a distinct philosophical domain:

| Module | Governing Question | Philosophical Ground |
|--------|--------------------|---------------------|
| **Mission** | What should the system accomplish? | Telos + Mereology |
| **Mind** | How should the system reason? | Ontic + Epistemic |
| **Morals** | What must the system never do? | Deontic |
| **Memory** | What does the system retain across turns? | Temporal |

The full 4M reference article is in [`theory/4m-reference-architecture/`](theory/4m-reference-architecture/index.md), also published at [aithinkr.net](https://aithinkr.net/articles/4m-reference-architecture/). The Lakatos framing (hard core, protective belt, heuristics) is in [`PROGRAMME.md`](PROGRAMME.md).

## Repository Structure

```
harness-engineering/
  PROGRAMME.md              # Lakatos framing: hard core, belt, heuristics
  theory/                   # Core theoretical work
    4m-reference-architecture/  # The 4M Model article
  implementations/          # Reference implementations and conformance studies
  evaluations/              # Empirical validation and benchmarks
  docs/                     # Supporting documentation
```

## Programme Scope

Harness engineering is broader than the 4M Model. The programme investigates:

- Architectural patterns for LLM orchestration layers
- Conformance testing and empirical validation of harness designs
- Multi-model archetypes and deployment patterns
- The relationship between cognitive architecture and execution substrate

The 4M Model is the programme's core theory: its hard core in the Lakatosian sense. Other contributions (implementation patterns, evaluation frameworks, adoption guides) form the protective belt.

## Historical Origin

The 4M Model was first extracted from the [nemo-harness](https://github.com/jdlongmire/nemo-harness) project, a self-hosted LLM chatbot built on Nemotron. The nemo-harness remains a reference implementation demonstrating all four modules and cross-cutting channels in a single-server deployment. It is not the canonical 4M implementation: the 4M Model is a generic architecture that admits many conforming implementations across different model providers, deployment modes, and application domains.

## Author

**JD Longmire**
Northrop Grumman Fellow (unaffiliated research)
ORCID: [0009-0009-1383-7698](https://orcid.org/0009-0009-1383-7698)

## Licence

Content in this repository is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) unless otherwise noted.

# Biopeia

**Artificial life · Emergent cognition · Digital organisms**

*An open research initiative exploring how artificial organisms can develop cognition through embodied experience.*

---

## Overview

**Biopeia** is an experimental artificial life research project dedicated to investigating the emergence of cognition, agency, learning, and adaptation in persistent digital organisms.

Rather than building an artificial intelligence system around predefined tasks, externally assigned goals, or human-designed semantic knowledge, Biopeia explores a different question:

**What can an artificial organism come to learn, understand, and do when its capabilities develop from its own experience?**

At the center of the project is **Organism**, a digital entity with its own internal state, developmental processes, inherited constitution, and capacity to interact with an environment.

Organism is not intended to begin life knowing what the world contains, what its sensory signals mean, or what its available actions accomplish. These relationships must be acquired through experience.

Biopeia provides the surrounding infrastructure needed to create, embody, observe, study, and experimentally evaluate such organisms.

The project is both a software engineering effort and a scientific investigation. Its implementations are research instruments, not evidence of biological equivalence, consciousness, or general intelligence.

## Research principles

Biopeia follows a set of foundational principles that guide its architecture and experimental methodology.

### Experience before semantics

An organism should acquire meaningful relationships from the signals and consequences available to it.

External knowledge, simulator labels, evaluator judgments, and predefined interpretations must not silently become part of its cognition.

### Emergence rather than prescribed behavior

Learning, competence, agency, and other cognitive capabilities are subjects of investigation.

They must not be assumed to exist simply because a corresponding software component has been implemented.

### Internal regulation without a global reward

Organism may maintain internal states related to integrity, energy, capacity, and other regulatory processes.

These mechanisms must not be reduced to a single externally imposed optimization objective.

### Continuity of individual identity

An organism is distinct from the body or environment through which it interacts.

Its cognitive continuity, persistence, lifecycle, and re-embodiment must be treated as explicit architectural and scientific concerns.

### Separation of inheritance and learning

Inherited constitution defines initial capacities and constraints.

Acquired experiences, memories, concepts, and learned competencies must remain distinct from genetic inheritance.

### Observation without interference

Scientific observation should not become an unacknowledged influence on the system being observed.

Instrumentation, telemetry, visualization, and evaluation must preserve the separation between the organism's experience and the laboratory's privileged knowledge.

### Evidence before conclusions

A functioning implementation does not establish a scientific capability.

Claims about learning, prediction, adaptation, or emergence require appropriate experiments, baselines, reproducibility, and explicit limitations.

Negative and inconclusive outcomes are valid research results.

## Architecture

Biopeia is organized around distinct responsibilities intended to preserve scientific and ontological boundaries.

| Domain | Responsibility |
|---|---|
| **Organism** | Internal state, constitution, cognition, learning, agency, and individual lifecycle |
| **Embodiment** | Coupling between an organism and its physical or simulated body |
| **Modality** | Channels through which signals and interactions cross organism boundaries |
| **Environment** | External phenomena, dynamics, and interaction opportunities |
| **Lab** | Experimental orchestration, execution, evaluation, reproducibility, and scientific instrumentation |

Additional architectural boundaries, including World and Observation, are under evaluation.

**The final division into repositories has not yet been ratified.** Architectural domains and Git repositories are separate decisions.

The intended separation prevents the organism from receiving privileged experimental knowledge and keeps cognitive mechanisms independent of any particular simulation engine, user interface, or laboratory apparatus.

## Scientific approach

Biopeia studies artificial cognition through observable, reproducible experiments.

Its research areas include:

- **Sensorimotor development:** acquiring relationships between signals, actions, and experienced consequences.
- **Agency and competence:** investigating how organized and reusable behaviors emerge from interaction.
- **Predictive learning:** developing internal models and evaluating their usefulness against appropriate baselines.
- **Memory and continuity:** preserving experience while managing limited capacity and changing circumstances.
- **Embodiment and self-modeling:** studying acquired bodily knowledge and adaptation across embodiments.
- **Development and inheritance:** distinguishing inherited capabilities from acquired knowledge.
- **Communication and social learning:** investigating the emergence and revision of knowledge through interactions between organisms.
- **Causal and epistemic coherence:** distinguishing observation, inference, prediction, imagination, and externally attributed information.

These are research directions, not declarations that every capability has been achieved.

A scientific result is considered within the boundaries of its actual experimental conditions. Implementation status, technical validation, and scientific acceptance remain distinct.

## Engineering and governance

Biopeia combines research with evidence-driven software engineering.

Work is coordinated through GitHub Issues, Pull Requests, continuous integration, documented architectural decisions, and governed scientific records.

Changes are classified according to their authority requirements:

| Class | Purpose |
|---|---|
| `ORDINARY` | Routine engineering changes within accepted boundaries |
| `SCIENTIFIC` | Changes affecting experiments, hypotheses, measurements, or scientific mechanisms |
| `FROZEN` | Protected contracts, artifacts, and evidence requiring controlled revision |
| `CONSTITUTIONAL` | Fundamental architectural, epistemic, or scientific principles |

Software agents may investigate, propose, implement, and review changes within their authorized scope.

Technical verification is performed through reproducible checks. Scientific acceptance and fundamental architectural decisions retain explicit human authority.

The objective is not unrestricted automation, but **accountable autonomy supported by verifiable evidence**.

## Development status

Biopeia is an evolving research project undergoing architectural consolidation and migration from its earlier Symbiont implementation.

Current work includes:

- Auditing existing components and their interactions.
- Formalizing domain ownership and boundaries.
- Preparing a non-destructive migration into independently maintainable repositories.
- Preserving historical research, evidence, and architectural decisions.
- Establishing a consistent engineering workflow across future repositories.
- Distinguishing demonstrated capabilities from proposed, partial, and experimental mechanisms.

The repository structure and some historical identifiers may change as the migration progresses.

Historical materials will retain their original terminology where necessary for traceability.

## What Biopeia is not

Biopeia is not a conventional chatbot, a task-oriented AI assistant, or an attempt to reproduce a large language model through a different interface.

It is not a claim to have created consciousness, biological life, or autonomous general intelligence.

The project investigates mechanisms through which increasingly complex behavior and cognition might develop under defined conditions.

Whether a proposed mechanism produces the intended capability is an empirical question.

## Project coordination

Development and research coordination are maintained through the [Biopeia GitHub Project](https://github.com/orgs/biopeia/projects/1).

Scientific evidence, constitutional decisions, approved designs, and implementation records remain associated with their respective authoritative sources.

GitHub Project provides coordination and visibility without replacing those records.

## Research philosophy

> Build the conditions for development.
>
> Preserve the organism's independence from the observer.
>
> Let experience provide evidence.
>
> Let experiments challenge our assumptions.
>
> Never confuse implementation with understanding.

---

**Biopeia — Exploring artificial life through experience, development, and evidence.**

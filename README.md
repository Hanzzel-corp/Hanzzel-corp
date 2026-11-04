<!-- Keep this animated header: it is part of Hanzzel Corp's visual identity. -->
<p align="center">
  <img src="./assets/nct-cat-repair.gif" alt="Hanzzel Corp — NCT repairing the fracture" width="950">
</p>

<p align="center">
  <strong>NCT is the mathematical foundation behind a family of computational constructions, algorithms, and problem-solving experiments.</strong>
</p>

<h1 align="center">Hanzzel Corp</h1>

<p align="center">
  <strong>Local-first AI · Human-approved automation · Computational research · Practical software</strong>
</p>

<p align="center">
  <a href="https://github.com/Hanzzel-corp"><img src="https://img.shields.io/badge/GitHub-Hanzzel--corp-181717?logo=github" alt="Hanzzel Corp on GitHub"></a>
  <a href="https://hanzzel-corp.github.io/"><img src="https://img.shields.io/badge/Portfolio-Visit-0A66C2" alt="Portfolio"></a>
  <a href="https://orcid.org/0009-0005-3584-1779"><img src="https://img.shields.io/badge/ORCID-Researcher-A6CE39?logo=orcid&logoColor=white" alt="ORCID"></a>
</p>

Hanzzel Corp is an independent technical lab developing mathematical and computational research, practical software, local AI systems, and human-directed automation.

A central research direction is **NCT (Números Cuánticos Tridimensionales)**: a mathematical foundation from which we investigate constructions such as CQ, algorithmic approaches, geometric models, and computational methods for solving problems. These explorations can inform applications, while other Hanzzel Corp projects follow independent technical foundations.

Our work connects investigation with engineering: ideas are formalized, implemented, tested, documented, and developed into useful tools where possible.

> **AI should assist, organize, verify, and execute under human direction. The human remains the final authority.**

---

## Navigate

- [What we build](#what-we-build)
- [Featured projects](#featured-projects)
- [Ecosystem architecture](#ecosystem-architecture)
- [Project directory](#project-directory)
- [Research and evidence](#research-and-evidence)
- [Development principles](#development-principles)
- [Current direction](#current-direction)
- [Collaboration and links](#collaboration-and-links)

## What we build

Hanzzel Corp develops practical software, AI systems, and computational research. Within this work, **NCT is the mathematical foundation for a family of derived constructions and methods**; those constructions may then inform applications and tools. The organization also develops projects with independent technical foundations.

| Area | What it means |
|---|---|
| **Mathematical foundation** | NCT and the definitions, models, and hypotheses developed within that framework. |
| **Derived constructions** | CQ, algorithmic approaches, Archimedean spheres, and other computational or geometric constructions. |
| **Products and applications** | Software and utilities designed to address concrete workflows and problems. |
| **AI, automation, and infrastructure** | Local-first systems, orchestration, signal analysis, memory components, bridges, dashboards, and supporting tools. |

Not every repository is a finished product. Some are usable systems, some are under active development, and others are experimental research. Their maturity is identified separately wherever the available project documentation supports it.

## Featured projects

### Blue Arrow

**Human-approved local PC orchestration from Telegram.**

A modular, event-driven system for coordinating desktop, browser, terminal, system, and document workflows. Its design keeps real-world actions behind safety checks and human approval.

- Telegram-based local control
- Modular runtime, workers, and event flow
- Approval and execution-verification mechanisms
- Local AI integration
- Documented transition from token-based toward state-driven orchestration

**Documented status:** Architecture transition in progress; the project documentation distinguishes the current hybrid implementation from its state-driven target.

[Repository](https://github.com/Hanzzel-corp/blue-arrow) · [CI workflow](https://github.com/Hanzzel-corp/blue-arrow/actions/workflows/ci.yml)

### NCT Depth Motif

**Experimental NCT-based analysis over depth maps.**

A reproducible investigation of discrete symbolic motifs derived from depth-map descriptors, evaluated using NYU Depth V2 data.

- Four-state symbolic representation
- Local depth-map descriptors and motif analysis
- Grouped train/test evaluation
- Comparisons against randomized motif weights
- Falsifiability-oriented experiments

**Documented status:** Exploratory technical report; not peer-reviewed. The project README reports statistically significant effects of small magnitude and identifies comparison with classical detectors such as Canny, Sobel, and HED as outstanding work.

[Repository](https://github.com/Hanzzel-corp/nct-depth-motif) · [Technical DOI](https://doi.org/10.5281/zenodo.20045645)

### Observatorio Vivo

**Local trend-intelligence and signal-detection system.**

A local system for collecting public signals, identifying emerging phenomena, organizing observations, and generating confidence-based alerts.

- Multi-source public-signal collection
- Trend and emergence scoring
- Local SQLite persistence
- Watchlists, aliases, and observation workflows
- Configurable alerts and exports

**Documented version:** Public README identifies v0.3.0 and an internal engine version v6.1.2. Refer to the project documentation for the precise feature and deployment state.

[Repository](https://github.com/Hanzzel-corp/Observatorio.-Vivo)

### SAT Engine

**Experimental SAT-solving and computational-analysis project.**

A collection of solver implementations exploring algorithmic approaches to Boolean satisfiability, including Python/C++ integration and phase-transition analysis.

- Backtracking and stochastic local-search approaches
- GSAT and WalkSAT experiments
- Python/C++ integration
- Parallel execution experiments
- Computational measurements around SAT phase transitions

**Documentation note:** The repository is named SAT Engine v7, while the README's version history currently describes implementations through v5. The version history and v7 scope should be reconciled before treating the repository title as a precise release statement.

[Repository](https://github.com/Hanzzel-corp/SAT-Engine-v7)

### Telegram AI Video Bot

**Telegram-based AI-assisted short-video workflow.**

A project focused on generating short videos from text descriptions through an automated Telegram interface.

[Repository](https://github.com/Hanzzel-corp/telegram-ai-video-bot)

### Hanzzel Corp Portfolio

**Public portfolio and professional project index.**

The portfolio connects selected software projects, research, technical direction, and professional identity.

[Open portfolio](https://hanzzel-corp.github.io/)

---

## Ecosystem architecture

Hanzzel Corp's work is organized around a distinction between a mathematical foundation, the constructions developed from it, and the practical systems that apply ideas to concrete problems.

### 1. Mathematical foundation: NCT

**NCT (Números Cuánticos Tridimensionales)** is the mathematical foundation of this line of development. It provides the framework from which we investigate and construct models, structures, algorithms, and computational approaches.

NCT is not presented here as a finished universal theory or as proof of physical quantum behavior. Its definitions, implementations, hypotheses, experimental results, and open questions must be evaluated through their respective technical documentation.

### 2. Derived constructions and methods

On that foundation, the work explores and develops further constructions, including:

- **CQ:** structures and computational constructions developed within the NCT framework.
- **Quantum algorithms:** algorithmic approaches investigated through these mathematical constructions.
- **Archimedean spheres:** geometric constructions and experiments.
- **Problem-solving methods:** computational approaches intended to address specific mathematical, logical, and practical problems.

These are development and research directions. Their implementation status and degree of validation depend on each individual project.

### 3. Applications and systems

The constructions and methods can then inform practical software and systems, alongside projects that have their own independent architectures and purposes. Examples include:

- **AI and orchestration:** Blue Arrow and local AI workflows.
- **Signal intelligence:** Observatorio Vivo.
- **Developer and computational tools:** SAT Engine, Telegram AI Video Bot, and supporting infrastructure.
- **Applied solutions:** utilities and software aimed at concrete workflows and business problems.

Not every application currently uses NCT, and not every NCT-derived construction is integrated into a deployed product. The relationship is architectural and developmental, not a claim of universal integration.

### 4. Evidence and public documentation

The work is made inspectable through source code, tests, reproducible experiments, technical reports, demonstrations, releases, and research records. Each project should state what is implemented, what has been measured, what remains hypothetical, and what still needs validation.

This structure describes how the work is conceived and developed: **mathematical foundation → derived constructions and methods → applications and problem-solving systems**, with evidence and documentation supporting each stage.

## Project directory

This directory broadens the view beyond the featured projects. It is an index of repositories in the Hanzzel Corp organization, not a declaration that every repository is active, complete, integrated with NCT, or production-ready. For implementation details and maturity, follow each repository's own documentation.

### Core systems and applications

- [Blue Arrow](https://github.com/Hanzzel-corp/blue-arrow) — human-approved local PC orchestration.
- [Ciel Core](https://github.com/Hanzzel-corp/ciel-core) — local AI system core.
- [Ciel Bridge](https://github.com/Hanzzel-corp/ciel-bridge) — integration bridge for Ciel.
- [Hanzzel Social Bridge](https://github.com/Hanzzel-corp/hanzzel-social-bridge) — social-platform integration project.
- [Observatorio Vivo](https://github.com/Hanzzel-corp/Observatorio.-Vivo) — local signal and trend intelligence.
- [Alerta Temprana](https://github.com/Hanzzel-corp/AlertaTemprana) — early-warning project.
- [Hanzzel Store](https://github.com/Hanzzel-corp/hanzzel-store) — store and commerce project.
- [Nubea](https://github.com/Hanzzel-corp/nubea) — software project.
- [Hanzzel Bot Builder](https://github.com/Hanzzel-corp/hanzzel-bot-builder) — bot-building tools.
- [Telegram AI Video Bot](https://github.com/Hanzzel-corp/telegram-ai-video-bot) — Telegram-based AI video workflow.
- [IA Video](https://github.com/Hanzzel-corp/IA-video) — video and AI experiments.

### NCT, mathematics, and computational experiments

- [NCT Dossiers](https://github.com/Hanzzel-corp/nct-dossiers) — NCT research documentation.
- [NCT Depth Motif](https://github.com/Hanzzel-corp/nct-depth-motif) — NCT-based depth-map motif experiments.
- [NCT Milenio Solver](https://github.com/Hanzzel-corp/NCT_MILENIO_SOLVER) — mathematical and computational solver project.
- [Camino Cuaternario](https://github.com/Hanzzel-corp/camino-cuaternario) — research and computational exploration.
- [Cero Absoluto Simulation](https://github.com/Hanzzel-corp/Cero-Absoluto-Simulation) — simulation project.
- [Experimento 9 — Horizonte Perceptivo](https://github.com/Hanzzel-corp/Experimento-9-Horizonte-Perceptivo) — experimental research.
- [Experimento 10 — Resonancia PhiSync](https://github.com/Hanzzel-corp/Experimento10_ResonanciaPhiSync) — resonance experiment.
- [Fib-Hodge Dynamics](https://github.com/Hanzzel-corp/Fib-Hodge-Dynamics) — mathematical dynamics project.
- [Navier–Stokes Critical Flow Experiments](https://github.com/Hanzzel-corp/NavierStokes-CriticalFlow-Experiments) — computational experiments.
- [Yang–Mills SU(3) v7](https://github.com/Hanzzel-corp/YangMills-SU3-v7) — computational research project.
- [Elliptic Curve BSD Engine](https://github.com/Hanzzel-corp/EllipticCurve-BSD-Engine) — elliptic-curve and BSD-related computation.
- [Riemann Zeta Computational Engine](https://github.com/Hanzzel-corp/Riemann-Zeta-Computational-Engine) — computational exploration of the zeta function.
- [SAT Engine v7](https://github.com/Hanzzel-corp/SAT-Engine-v7) — SAT-solving experiments.
- [H2O Chemistry VQE](https://github.com/Hanzzel-corp/H2O-quimicaVQE) — quantum-chemistry / VQE experiment.

### Public presence

- [Hanzzel Corp organization](https://github.com/Hanzzel-corp) — organization profile and repositories.
- [Hanzzel Corp portfolio](https://hanzzel-corp.github.io/) — public portfolio and project index.

## Research and evidence

We aim to make technical work inspectable rather than relying on broad claims.

Depending on the project, evidence may include:

- Source code, reproducible scripts, and configuration
- Test procedures, logs, and measured outputs
- Technical reports and documented limitations
- Screenshots, demonstrations, and real workflows
- Releases and persistent research records

**Research integrity matters.** Experimental findings are presented as experimental findings. A result from a finite test does not, by itself, establish a universal theorem, a general-purpose capability, or a production-ready product.

For NCT-related work, Hanzzel Corp distinguishes the framework's research hypotheses, the concrete implementation under test, the measured results, and the limitations that remain.

## Development principles

### Human direction

AI may assist with analysis, planning, and execution. People retain authority over consequential actions.

### Local-first by design

We favor local execution, user-controlled data, and reduced dependence on external services when practical.

### Observable and verifiable behavior

Systems should expose meaningful inputs, outputs, decisions, logs, and execution results.

### Modular engineering

Components should have clear responsibilities and interfaces, making systems easier to inspect, test, and maintain.

### Evidence over claims

Documentation should distinguish implemented features, measured results, hypotheses, and future plans.

### Research connected to practice

Where appropriate, research is translated into code, experiments, reports, demonstrations, or usable tools.

## Current direction

The current direction is to:

- Continue developing Blue Arrow's human-approved orchestration architecture.
- Extend reproducible NCT experiments while documenting their limits.
- Develop Observatorio Vivo's local signal-intelligence workflow.
- Improve the usability, testing, and documentation of practical tools.
- Make project maturity and evidence easier to inspect.
- Connect software, research records, and public technical communication.

This is an evolving ecosystem, not a claim that every planned capability is complete or that all repositories form one integrated product.

## Collaboration and links

For technical discussion, evaluation, bug reports, or potential collaboration, start with the relevant project repository. Use its GitHub Issues to report a reproducible problem or propose a focused discussion; use pull requests when you have a concrete change to contribute. For broader inquiries, use the public organization profile or portfolio.

- **Organization:** [github.com/Hanzzel-corp](https://github.com/Hanzzel-corp)
- **Portfolio:** [hanzzel-corp.github.io](https://hanzzel-corp.github.io/)
- **ORCID:** [0009-0005-3584-1779](https://orcid.org/0009-0005-3584-1779)
- **Zenodo:** [Research record](https://zenodo.org/records/1561047960843)
- **Patreon:** [Hanzzel Corp](https://www.patreon.com/c/zamohanzze)

---

<p align="center">
  <strong>Build carefully. Measure honestly. Keep the human in control.</strong>
</p>

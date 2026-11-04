<!-- Keep this animated header: it is part of Hanzzel Corp's visual identity. -->
<p align="center">
  <img src="./assets/nct-cat-repair.gif" alt="Hanzzel Corp — NCT repairing the fracture" width="950">
</p>

<p align="center">
  <strong>NCT as a repair field for fractured systems: detecting, interpreting, and rebuilding through human-directed intelligence.</strong>
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

Hanzzel Corp is an independent technical lab building practical software, local AI systems, human-directed automation, and experimental computational research.

Our work connects engineering with investigation: prototypes become documented systems, experiments produce inspectable evidence, and useful ideas are developed into tools where possible.

> **AI should assist, organize, verify, and execute under human direction. The human remains the final authority.**

---

## Navigate

- [What we build](#what-we-build)
- [Featured projects](#featured-projects)
- [Ecosystem map](#ecosystem-map)
- [Research and evidence](#research-and-evidence)
- [Development principles](#development-principles)
- [Current direction](#current-direction)
- [Collaboration and links](#collaboration-and-links)

## What we build

Hanzzel Corp works across four connected areas:

| Area | What it means |
|---|---|
| **Products and tools** | Software and utilities designed to support concrete workflows. |
| **AI and automation** | Local-first systems, modular orchestration, signal analysis, and human-approved execution. |
| **Research and experiments** | NCT-based investigations and computational experiments with explicit methods and limitations. |
| **Infrastructure** | Bridges, memory components, dashboards, generators, and supporting development tools. |

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

## Ecosystem map

The ecosystem is organized into five connected areas:

- **Products and tools:** Blue Arrow, Telegram AI Video Bot, and practical local utilities.
- **AI and intelligence:** local AI orchestration, Observatorio Vivo, signal analysis, and human-approved automation.
- **Research and computation:** the NCT experimental framework, NCT Depth Motif, and SAT Engine.
- **Infrastructure:** local model bridges, memory components, documentation generators, dashboards, and utilities.
- **Public evidence:** source code, tests, technical documentation, demonstrations, releases, and research records.

These areas describe the organization's work; they do not imply that every component is already integrated into one deployed system.

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

For technical discussion, evaluation, or potential collaboration, start with the relevant project repository or the public organization profile.

- **Organization:** [github.com/Hanzzel-corp](https://github.com/Hanzzel-corp)
- **Portfolio:** [hanzzel-corp.github.io](https://hanzzel-corp.github.io/)
- **ORCID:** [0009-0005-3584-1779](https://orcid.org/0009-0005-3584-1779)
- **Zenodo:** [Research record](https://zenodo.org/records/1561047960843)
- **Patreon:** [Hanzzel Corp](https://www.patreon.com/c/zamohanzze)

---

<p align="center">
  <strong>Build carefully. Measure honestly. Keep the human in control.</strong>
</p>

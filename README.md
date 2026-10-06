<p align="center">
  <img src="./avatar.png" width="180" alt="Avatar" />
</p>


# Ulrich Tan

Research scientist and systems engineer working at the intersection of AI, distributed systems, safety-critical software, and large-scale infrastructure.

My work explores a common question across these domains:

> How can reliable systems emerge from imperfect components?

I investigate this question through multi-agent AI architectures, execution isolation mechanisms, distributed coordination, learning dynamics, and trustworthy computing systems.

This repository provides an overview of selected public and private projects, research work, and engineering explorations.

---

## 🚀 Featured Projects

### IronGhost (Public, Active)  
Research Area: Reliable Multi-Agent Systems  
Repository: [IronGhost](https://github.com/jietra/IronGhost)

Mission-driven orchestration for untrusted AI agents.

IronGhost is an experimental architecture exploring whether reliable AI systems can emerge from the organization, specialization, and mutual verification of imperfect agents.

Key research questions:

- How should state be represented in multi-agent systems?
- How can error propagation be contained?
- What information should agents share?
- How should validation be separated from planning?
- Can reliability emerge from architecture rather than model capability alone?

Core concepts:

- Mission Graph as persistent system state
- DAG-based execution
- Zero-trust AI architecture
- Agent specialization
- Amnesia protocol
- Independent validation layers
- Human authorization
- Deterministic execution boundaries

Technology:

Rust, C++, Tauri, Svelte, llama.cpp

---

### xWALT (Public, Active)  
Research Area: Trusted Execution & AI Isolation  
Repository: [xWALT](https://github.com/jietra/wos)  

Lean Type-I hypervisor and minimal operating-system stack written in Rust (no_std).

xWALT investigates how hardware-enforced trust boundaries can be used to safely deploy increasingly autonomous AI systems alongside safety-critical software.

> Recent milestone: Successfully booted a Linux guest kernel under full ARM64 Stage-2 virtualization, validating the complete EL2 → EL1 → EL0 execution chain.

The project currently includes:

- a Type-I ARM64 hypervisor (EL2)
- Stage-2 memory virtualization
- Linux guest boot support
- a compact Rust kernel
- user-space execution primitives
- ARM64 and RISC-V support

Research themes:

- trusted computing bases
- deterministic execution
- memory safety
- virtualization
- sandboxing of AI components
- isolation of perception, planning, and control systems

Target domains:

- robotics
- drones
- autonomous systems
- embedded AI
- safety-critical software

---

### dendritic_segment_model (Public)  
Repository: [dendritic_segment_model](https://github.com/jietra/dendritic_segment_model)  
A Python package modeling dendritic segment behavior for computational neuroscience experiments.

---

### speann (Public, Archived)  
Repository: [speann](https://github.com/jietra/speann)  
A Python package implementing evolutionary artificial neural networks.  
Archived but kept for reference.

---

### 🔓 Multi-Agent Local AI System (Private, 2025)

Early exploration of local multi-agent architectures built around embedded LLM inference and agent orchestration.

Implemented as a fully local C++/Qt application featuring:

- Multiple specialized AI agents collaborating on complex tasks
- Embedded local inference (no cloud dependency)
- Tool use through filesystem, process, and networking primitives
- Web search, code generation, and controlled code execution
- Agent orchestration and coordination mechanisms
- Custom runtime adaptations for desktop and mobile environments

This project served as an early exploration of many of the questions later investigated in IronGhost, including agent specialization, orchestration, tool use, state management, and reliability in multi-agent systems.

---

### Selected Large-Scale Systems

#### Sovereign LLM Platform (2023)

Architect and technical lead of the French State's sovereign LLM platform, serving more than 10,000 daily users across public-sector organizations.

Topics:
- secure AI infrastructure
- model hosting
- RAG
- evaluation
- monitoring
- AI governance

#### Data Platforms (2020)

Large-scale lakehouse and analytics infrastructures.  

#### Privacy-Preserving Identity Systems (2018)

Privacy-preserving identity and credential systems based on distributed identity, zero-knowledge proofs, secure multiparty computation, and post-quantum cryptography.

---

## Research Interests

### Reliable AI Systems
- Multi-agent architectures
- Verification and validation
- Collective intelligence
- Agent orchestration

### Learning Dynamics
- Hebbian plasticity
- Optimal transport
- Computational neuroscience

### Systems & Infrastructure
- Trusted execution
- Virtualization
- Distributed systems
- Safety-critical software

### Language Model Systems
- RAG
- Evaluation
- Monitoring
- Sovereign AI infrastructure

---

## Selected Publications

### A Wasserstein Geometric Framework for Hebbian Plasticity
[ArXiv, 2026](https://arxiv.org/abs/2604.16052)

A mathematical framework connecting Hebbian learning dynamics and optimal transport geometry.

### LLM Summarisation for Legislation
[ArXiv, 2024](https://arxiv.org/abs/2401.16182)

Application and evaluation of large language models for legislative summarisation.

---

## Selected Talks & Writing

### National AI Strategy
[HAL, 2024](https://hal.science/hal-04825691)

### Articles
*Annales des Mines* ([DOI:10.3917/rindu1.252.0027](https://doi.org/10.3917/rindu1.252.0027)); *Culture \& Recherche* (2025)

---

## Technical Focus

Languages:
Rust, C++, Python

Domains:
Multi-agent systems, AI systems, distributed systems,
virtualization, safety-critical software, cryptographic systems.

---

## 📈 Contributions

This portfolio provides a high‑level overview of the work I do across both public and private repositories.

---

## Current focus:
Reliable AI systems, multi-agent architectures, validation mechanisms, and trustworthy execution environments.

---

## 📫 Contact

Feel free to reach out via GitHub or connect for collaboration opportunities.

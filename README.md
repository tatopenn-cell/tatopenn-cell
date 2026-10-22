<h1 align="center">
  Hi there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> I'm Tato Penn
</h1>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&center=true&vCenter=true&width=900&lines=Software+Engineer+%7C+AI+%26+Scientific+Computing;JAX+XLA+Systems+Engineer;Quantum+Simulation+%26+VQE;AI+Runtime+Robustness;Bio-Computational+Pipelines)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-pennacchio-090924413/)
[![Email](https://img.shields.io/badge/Email-Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tatopenn@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tatopenn-cell)
[![Docs](https://img.shields.io/badge/Docs-Dense--Evolution-00e5ff?style=for-the-badge&logo=materialformkdocs&logoColor=white)](https://tatopenn-cell.github.io/Dense-Evolution/)
[![PyPI](https://img.shields.io/badge/PyPI-dense--evolution-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/dense-evolution/)

</div>

---

## 👋 About Me

I am a **Software Engineer and AI-driven scientific researcher** based in Napoli, Italy.

I build software where ideas move through the complete engineering cycle:

**research → design → prototype → implementation → testing → validation → documentation → release**

My work sits at the intersection of:

- 🧑‍💻 **Software Engineering**
- 🤖 **AI-assisted development**
- ⚛️ **Quantum simulation**
- 🧮 **Scientific computing**
- 🛡️ **AI runtime robustness**
- 📈 **Online machine learning**
- 🧬 **Computational biology**

The goal is not simply to write experimental code, but to turn mathematical and scientific ideas into **tested, reproducible and maintainable software**.

I am the author of [`dense-evolution`](https://pypi.org/project/dense-evolution/), a JAX/XLA statevector simulator for NISQ circuits, VQE and QML, and [`dense-armor`](https://github.com/tatopenn-cell/Dense-Armor), an online-learning library for robots and LLMs with a runtime protection layer. Two further repositories support the work: [`Dense-Evolution-Discovery`](https://github.com/tatopenn-cell/Dense-Evolution-Discovery), the research lab where every claim is a script run and checked before it is written up, and [`local-quantum-rag`](https://github.com/tatopenn-cell/local-quantum-rag), the local hybrid RAG that grounds the research in the actual PDFs.

All four projects are developed as real software projects, with automated testing, CI, documentation and public releases.

---

## 🧑‍💻 How I Work

My development workflow is **AI-assisted but human-supervised**.

AI is used as an engineering tool — not as an autonomous decision maker.

### 1. 💡 Start from the problem

I begin from a concrete technical or scientific question.

The literature, mathematical model or existing implementation provides the starting point, but the final implementation is designed around the actual problem being solved.

### 2. 🧪 Prototype quickly

Ideas are first implemented as practical prototypes.

The objective is to discover:

- what actually works;
- where assumptions fail;
- what needs to be redesigned;
- which parts deserve production-quality implementation.

### 3. 🔬 Validate aggressively

A prototype is not considered successful simply because it runs.

Validation can include:

- unit tests;
- integration tests;
- numerical checks;
- statistical validation;
- comparison against references;
- independent implementations;
- adversarial testing;
- regression testing;
- reproducibility checks.

When AI is involved, its output is also treated as something that must be **verified rather than trusted automatically**.

### 4. 🚀 Turn successful prototypes into software

Once an implementation proves itself, it is promoted into a proper engineering pipeline:

- structured source code;
- automated tests;
- CI;
- documentation;
- package releases;
- reproducible experiments;
- research artifacts when applicable.

The objective is simple:

> **A result should be reproducible by running the software that produced it.**

---

## 🔄 The Method: Four Phases

The engineering process above is written down in [`local-quantum-rag/docs`](https://github.com/tatopenn-cell/local-quantum-rag/tree/main/docs) as an explicit four-phase architecture. The four phases are not interchangeable: each has its own environment, its own success criterion, and its own model requirements.

**1. Exploration.** Idea to prototype. Cheap, high-context model, many iterations, execution happening outside the model's session. Divergent, conversational, no dedicated process document.

**2. Verification.** The question changes from *does it work?* to *does it implement what the literature states?*. A stronger model with retrieval access to the actual PDFs checks the code against the source paper, equation by equation, under a set of standing constraints on the agent's behaviour. Divergent → convergent.

**3. Discovery.** The result moves into a public, reproducible environment where it may still be rejected. Every entry is a standalone script that produces its own result end to end; a negative result is written up with the same care as a positive one and left in place, so the next attempt does not repeat it. The single most common failure mode: a promising result that disappears under a negative control (shuffled labels, randomised baseline) was never a real effect.

**4. Production.** Only what survived Discovery ships to real users. The shipping list is checked against the real directory tree, the platform physically refuses a merge until the named checks are green, and publishing to the index is a separate human-confirmed step. A green checkmark is evidence toward safety, not proof of it.

Two principles run through all four phases:

- **Process documents are for the human, constraint documents are for the AI**, and they are different documents.
- **A static instruction only constrains behaviour at the specific trigger points it names** — everywhere else, it is invisible.

---

## 🧠 Engineering Mindset

I treat software development as an iterative engineering process.

~~~text
Idea
  ↓
Prototype
  ↓
Test
  ↓
Validate
  ↓
Find weaknesses
  ↓
Redesign
  ↓
Automate regression checks
  ↓
Document
  ↓
Release
  ↓
Repeat
~~~

AI agents can accelerate individual steps, but the engineering process remains under human control.

Each agent has a specific task, its output is checked, and unexpected behaviour is investigated rather than silently accepted.

---

## 🔬 Research Interests

<details>
<summary><b>View full research interests</b></summary>

Quantum Phase Transitions & Order Parameters • Molecular VQE & Potential Energy Curves • Quantum Defect Mapping • Crystalline Lattice Dispersion & Tight-Binding • Strained-Silicon & GaAs Bandstructure Engineering • Quantum Lattice Thermodynamics (Phonon Scattering & Decoherence) • Zero-Noise Extrapolation (Stochastic Richardson, ZNE-before-PSR, Photonic Predictive) • Loschmidt Echo & Channel Non-Commutativity • Topological Mott Insulators • Quantum Error Correction (Steane [[7,1,3]] on Real Hardware Calibration) • Traversable-Wormhole SYK Teleportation • Online Machine Learning • AI Runtime Robustness • Robust Statistics • Computational Biology • Multi-Agent AI Pipelines

</details>

---

# ⭐ Featured Projects

## ⚛️ Quantum Simulation & Chemistry

### 🧮 [dense-evolution](https://github.com/tatopenn-cell/Dense-Evolution)

A **JAX/XLA statevector simulator** for NISQ circuits, VQE and QML.

The project combines high-performance numerical computing with quantum chemistry functionality, including:

* stride-sliced kernel fusion;
* JAX/XLA execution;
* a native Hartree-Fock engine;
* **Obara-Saika recursion**;
* real molecular Hamiltonians;
* Jordan-Wigner mapping;
* Zero-Noise Extrapolation;
* Richardson extrapolation;
* Composer web UI;
* MCP server for agent-driven control.

The project is distributed as a real Python package and includes public documentation, CI and research artifacts.

**Concepts:**
`Obara-Saika Recursion` • `Jordan-Wigner Mapping` • `Richardson Extrapolation` • `Kernel Fusion` • `JAX/XLA`

[![PyPI](https://img.shields.io/pypi/v/dense-evolution?style=flat-square&color=00e5ff)](https://pypi.org/project/dense-evolution/)
[![CI](https://github.com/tatopenn-cell/Dense-Evolution/actions/workflows/ci.yml/badge.svg)](https://github.com/tatopenn-cell/Dense-Evolution/actions/workflows/ci.yml)
[![DOI](https://zenodo.org/badge/1247011090.svg)](https://doi.org/10.5281/zenodo.21855643)

---

### 🌀 [Dense-Evolution-Discovery](https://github.com/tatopenn-cell/Dense-Evolution-Discovery)

The research and experimental layer built on top of Dense-Evolution.

It contains **documented computational experiments**, with results re-measured when changes to the underlying simulator or noise model could affect previous conclusions.

The goal is to keep the experimental process reproducible rather than treating research results as static numbers. Every claim is a script, run and checked before it is written up, with the negative results kept alongside the positive ones.

Current experiments include:

* MPS GPU optimization of the matrix-product-state backend (2.16× measured, with the three real bugs found along the way);
* Dense-Armor robot safety on real IMU, Lidar and LeRobot arm data;
* MITRE ATT&CK APT29 attack detection on real Sysmon telemetry, plus Orca protecting a real scikit-learn model from adversarial input corruption;
* TFIM phase transitions, VQE, ZNE, tight-binding materials, and a critical replication of the traversable-wormhole teleportation protocol;
* density-matrix noise diagnostics (Rényi divergence, magic entropy) and vector-healing fixes shipped back into Dense-Evolution;
* the *Dynamic Vacuum Pressure Theory* paper, a `cosh`-shaped vacuum regularization checked against real EHT/LIGO/NICER data, with a `dense_evolution`-verified Z₂ symmetry linking `cosh`, the Bell state and Taoist duality.

**Concepts:**
`Parameter-Shift Rule` • `Born-Rule Kraus Sampling` • `Statistical Re-Verification` • `Negative Controls`

[![CI](https://github.com/tatopenn-cell/Dense-Evolution-Discovery/actions/workflows/ci.yml/badge.svg)](https://github.com/tatopenn-cell/Dense-Evolution-Discovery/actions/workflows/ci.yml)
[![DOI](https://zenodo.org/badge/1258407155.svg)](https://doi.org/10.5281/zenodo.21855620)

---

## 🛡️ AI Runtime Robustness & Online Learning

### 🐙 [Dense-Armor](https://github.com/tatopenn-cell/Dense-Armor)

**An online-learning library for robots and LLMs. One sample at a time, inside a control-loop budget, with a runtime protection layer.**

- **Learns one sample at a time.** Every estimator has `learn_one`, `predict_one`, `score_one`. No retraining, no batch.
- **Fits a control loop.** `budget_s` and `RealtimePipeline` refuse an estimator that does not fit the period.
- **Protects itself while it learns.** `Protected` and `SafeEstimator` wrap any model; a drift detector, an anomaly detector or the `Orca` runtime shield can flag and fall back.
- **One base for everything.** Classifiers, regressors, transformers, anomaly and drift detectors all inherit from `dense_armor.roles`. An estimator for a robot is also an estimator an LLM can call as a tool.

<details>
<summary>What is inside</summary>

**32 families** under `dense_armor/utility/`: linear models, naive Bayes, k-NN, incremental trees and forests, ensembles, factorization machines, recommenders, bandits, multiclass and multi-output; the full neural stack (dense, convolution, RNN/GRU/LSTM, multi-head attention, transformer blocks, plus `mlp`, `resnet_mlp`, `cnn`, `recurrent_net`, `transformer_encoder`); streaming statistics and sketches; CUSUM, Page-Hinkley, ADWIN, KSWIN, BOCPD; fourteen anomaly detectors; twenty online metrics; online vision; kinematic control and CBF filters.

**The protection layer** (`protect/`): `Armatura` (a Phi_AB coherence trigger on 1D signal streams) and `Orca` (an adaptive stabilizer with a Collatz-based damping gate). Thresholds adapt with Jensen-Shannon divergence on the local window. Adversarial robustness is measured against the same engine the system uses, not a separate benchmark; weak cases are reported, not hidden.

**Optional bridges**, installed as extras: `[river]`, `[llm]`, `[quantum]`, `[vision]`, `[drone]`, `[ros]`, `[finance-stream]`, `[data]`, `[audio]`, `[mcp]`.

**Documentation:** 39 sections on the site, including `docs/drones/` (13 pages), `docs/finance/` (17 pages), `docs/shields/` (5 pages) and `docs/compare/` where each batch class of the machine-learning task is compared, on the same data and metric, with its online counterpart.

</details>

**Concepts:** `online learning` · `one sample at a time` · `control-loop budget` · `JAX/XLA` · `finite-difference gradient checks` · `CUSUM` · `ADWIN` · `BOCPD` · `prequential evaluation` · `Jensen-Shannon adaptive threshold`

[![PyPI](https://img.shields.io/badge/pypi-dense--armor-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/dense-armor/)
[![tests](https://github.com/tatopenn-cell/Dense-Armor/actions/workflows/tests.yml/badge.svg)](https://github.com/tatopenn-cell/Dense-Armor/actions/workflows/tests.yml)
[![codecov](https://codecov.io/gh/tatopenn-cell/Dense-Armor/branch/master/graph/badge.svg)](https://codecov.io/gh/tatopenn-cell/Dense-Armor)
[![Docs](https://img.shields.io/badge/docs-tatopenn--cell.github.io-00e5ff?style=flat-square)](https://tatopenn-cell.github.io/Dense-Armor/)

---

## 🤖 Retrieval-Augmented Research

### 🔍 [local-quantum-rag](https://github.com/tatopenn-cell/local-quantum-rag)

A small, **local, hybrid RAG tool** for grounding technical conversations in your own PDFs and notes, so an AI assistant cites what a document actually says instead of what it remembers.

A CLI (`query.py`) covers everyday use; an optional local FastAPI server (`server.py`) keeps the embedding and reranker models warm across repeated queries, with endpoints `/search`, `/search_exact` and `/collections`, an in-process mtime-invalidated cache and token auth.

The four-phase methodology described above lives here, together with a case study of a context-reload trigger gap found and fixed.

**Concepts:**
`hybrid retrieval` · `cross-encoder reranking` · `PDF grounding` · `FastAPI` · `token auth` · `mtime cache`

[![CI](https://github.com/tatopenn-cell/local-quantum-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/tatopenn-cell/local-quantum-rag/actions/workflows/ci.yml)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22914813.svg)](https://doi.org/10.5281/zenodo.22914813)

---

# 🧬 Computational Biology

### 🧫 Dense-Evolution-Molecular-Pipeline

🚧 **Work in progress — repository currently private.**

A hybrid bio-quantum computational pipeline for **Chronic Myeloid Leukemia treatment optimization**.

The current architecture combines:

* JAX-accelerated genetic algorithms;
* BCR-ABL1 kinase-domain sequence exploration;
* Meta ESMFold API;
* protein structure generation;
* JAX-native molecular docking;
* computational optimization.

The project will be featured publicly once the implementation is ready to share.

---

# 📊 Engineering Signals

The projects are intended to demonstrate not only research ideas, but the ability to turn those ideas into software artifacts.

| Project | Package | CI | Tests | Documentation | Research Artifact |
| --- | --- | --- | --- | --- | --- |
| **Dense-Evolution** | ✅ PyPI 8.3.2 | ✅ | ✅ | ✅ | ✅ DOI |
| **Dense-Armor** | ✅ PyPI 1.1.33 | ✅ | ✅ | ✅ | — |
| **Dense-Evolution-Discovery** | Research repo | ✅ | ✅ | ✅ | ✅ DOI |
| **local-quantum-rag** | CLI + FastAPI server | ✅ | ✅ | ✅ | ✅ DOI |

The important distinction is between **an experiment that runs once** and **software that can be tested, reproduced, documented and released**.

---

# 🛠️ Technical Stack

## ⚛️ Quantum & Scientific Computing

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JAX](https://img.shields.io/badge/JAX_XLA-f9ab00?style=for-the-badge&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)
![PennyLane](https://img.shields.io/badge/PennyLane-1a1a2e?style=for-the-badge)
![Numba](https://img.shields.io/badge/Numba-00A3E0?style=for-the-badge&logo=numba&logoColor=white)

## 🧪 Testing & Code Quality

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![coverage](https://img.shields.io/badge/coverage-CC0000?style=for-the-badge&logo=codecov&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)
![Mypy](https://img.shields.io/badge/Mypy-2A6DB2?style=for-the-badge&logo=python&logoColor=white)
![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?style=for-the-badge&logo=precommit&logoColor=white)

## 📊 Data & Figures

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 🧠 Deep Learning & Adversarial

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Optax](https://img.shields.io/badge/Optax-1a1a2e?style=for-the-badge)
![Flax](https://img.shields.io/badge/Flax-1a1a2e?style=for-the-badge)

## 🧬 Bio-Computational

![RDKit](https://img.shields.io/badge/RDKit-1a1a2e?style=for-the-badge)
![Py3Dmol](https://img.shields.io/badge/Py3Dmol-2e7d32?style=for-the-badge)

## 🔍 RAG & AI Tooling

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-1a1a2e?style=for-the-badge)
![Model Context Protocol](https://img.shields.io/badge/MCP-000000?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG_Knowledge_Base-6a0dad?style=for-the-badge)

## 📄 Research Tooling

![pypdf](https://img.shields.io/badge/pypdf-1a1a2e?style=for-the-badge)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-1a1a2e?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

## 📦 Release & Publishing

![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![Zenodo](https://img.shields.io/badge/Zenodo-1682D4?style=for-the-badge&logo=zenodo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MkDocs Material](https://img.shields.io/badge/MkDocs_Material-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=white)

## 🤖 Multi-Agent Pipelines

![Multi--Agent Pipelines](https://img.shields.io/badge/Multi--Agent_Pipelines-00897b?style=for-the-badge)

## 🧑‍💻 Development Environment

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

## ⚙️ Tools & Workflow

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

# 🔄 From Research to Software

~~~text
Scientific / Technical Idea
            │
            ▼
       Literature
            │
            ▼
        Prototype
            │
            ▼
     Practical Testing
            │
            ▼
   AI-Assisted Validation
            │
            ▼
   Independent Verification
            │
            ▼
    Automated Regression
            │
            ▼
      Documentation
            │
            ▼
       Package / Release
            │
            ▼
    Reproducible Artifact
~~~

The objective is to make the entire chain traceable.

**Idea → implementation → test → result.**

---

# 💡 Philosophy

> **A paper becomes math, math becomes code, and every claim — quantum, statistical, or biological — ships next to the script that produced it.**

Good research should be reproducible.

Good software should be testable.

And when the two meet, the implementation should make the reasoning easier to inspect rather than harder.

---

# 📬 Get in Touch

Questions, ideas, or a paper worth implementing?

[**tatopenn@gmail.com**](mailto:tatopenn@gmail.com) ·
[**LinkedIn**](https://www.linkedin.com/in/salvatore-pennacchio-090924413/) ·
[**Dense-Evolution issues →**](https://github.com/tatopenn-cell/Dense-Evolution/issues) ·
[**Dense-Armor issues →**](https://github.com/tatopenn-cell/Dense-Armor/issues)

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/216656967-625b2a52-e638-4c21-a8ae-180560386f96.gif" width="160" />
<img src="https://user-images.githubusercontent.com/74038190/216649426-0c2ee152-84d8-4707-85c4-27a378d2f78a.gif" width="160"/>
<img src="https://user-images.githubusercontent.com/74038190/216656944-f8c1b44e-493b-487f-87be-6cfe6a1a3374.gif" width="160"/>
<img src="https://user-images.githubusercontent.com/74038190/216655855-e00c1861-e964-4b4f-90ae-2592cad7b272.gif" width="160"/>

</div>

<h1 align="center">
  Hi there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> I'm Tato Penn
</h1>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&center=true&vCenter=true&width=900&lines=AI-Driven+Quantum+Researcher;JAX+XLA+Systems+Engineer;Quantum+Chemistry+%26+VQE;AI+Runtime+Robustness;Bio-Computational+Pipelines)](https://git.io/typing-svg)

[![Email](https://img.shields.io/badge/Email-Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tatopenn@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tatopenn-cell)
[![Docs](https://img.shields.io/badge/Docs-Dense--Evolution-00e5ff?style=for-the-badge&logo=materialformkdocs&logoColor=white)](https://tatopenn-cell.github.io/Dense-Evolution/)
[![PyPI](https://img.shields.io/badge/PyPI-dense--evolution-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/dense-evolution/)

<!-- LinkedIn badge goes here once the profile URL is confirmed -->

</div>

---

## 👋 About Me

I am an **AI-Driven Quantum Researcher** based in Napoli, Italia, working across three fronts: quantum simulation, AI runtime robustness, and bio-computational pipelines — each one carrying a paper's math straight into tested, published code through a multi-agent research pipeline.

Author of [`dense-evolution`](https://pypi.org/project/dense-evolution/) (NISQ statevector simulator) and [`dense-armor`](https://github.com/tatopenn-cell/Dense-Armor) (runtime shield for AI model I/O), both published on PyPI.

---

## 🧠 How I Work

- 💡 **Theory-first, idea-driven:** literature sets the starting point, and an original idea always builds on top of it.
- 🧪 **Free prototyping:** drafts get built and tested on free compute resources.
- 🚀 **Promoted when it earns it:** a prototype that proves itself moves into a full coding pipeline, paired with an AI agent and a RAG-backed research base.
- 🔧 **Adapted:** a paper's method serves as a reference that bends to what the idea actually needs.

---

## 🔬 Research Interests

Quantum Phase Transitions & Order Parameters • Molecular VQE & Potential Energy Curves • Quantum Defect Mapping • Crystalline Lattice Dispersion & Tight-Binding • Strained-Silicon & GaAs Bandstructure Engineering • Quantum Lattice Thermodynamics (Phonon Scattering & Decoherence) • Zero-Noise Extrapolation (Stochastic Richardson, ZNE-before-PSR, Photonic Predictive) • Loschmidt Echo & Channel Non-Commutativity • Topological Mott Insulators • Quantum Error Correction (Steane [[7,1,3]] on Real Hardware Calibration) • Traversable-Wormhole SYK Teleportation • AI Runtime Robustness • Robust Statistics • Computational Biology • Multi-Agent AI Pipelines

---

## ⭐ Featured Projects

### ⚛️ Quantum Simulation & Chemistry

### 🧮 [dense-evolution](https://github.com/tatopenn-cell/Dense-Evolution)

A JAX XLA statevector simulator for NISQ circuits, VQE, and QML: stride-sliced kernel fusion, a native Hartree-Fock engine built directly on the **Obara-Saika recursion**, real molecular Hamiltonians, Zero-Noise Extrapolation, and a Composer web UI + MCP server for agent-driven control.

**Concepts:** Obara-Saika Recursion • Jordan-Wigner Mapping • Richardson Extrapolation • Kernel Fusion

[![PyPI](https://img.shields.io/pypi/v/dense-evolution?style=flat-square&color=00e5ff)](https://pypi.org/project/dense-evolution/)
[![CI](https://github.com/tatopenn-cell/Dense-Evolution/actions/workflows/ci.yml/badge.svg)](https://github.com/tatopenn-cell/Dense-Evolution/actions/workflows/ci.yml)
[![DOI](https://zenodo.org/badge/1247011090.svg)](https://doi.org/10.5281/zenodo.21855643)

### 🌀 [Dense-Evolution-Discovery](https://github.com/tatopenn-cell/Dense-Evolution-Discovery)

The research log built on top of it — 23 documented experiments, each re-measured whenever the underlying simulator's noise model changes.

**Concepts:** Parameter-Shift Rule • Born-Rule Kraus Sampling • Statistical Re-Verification

---

### 🛡️ AI Runtime Robustness

### 🐙 [Dense-Armor](https://github.com/tatopenn-cell/Dense-Armor)

A runtime shield for AI model input/output, no retraining required: `Armatura` filters 1D signal streams (loss curves, sensor telemetry) through a binary Phi_AB coherence trigger shared with Dense-Evolution's healing engine; `Orca` wraps a whole model with an adaptive stabilizer plus a Collatz-based damping gate on both sides of inference. Four classical anomaly detectors — **Chauvenet's criterion (1863)**, **Tukey's fences**, the **Hampel filter**, and iterative **sigma-clipping** — combine through a Lagrange-multiplier **BLUE** (minimum-variance) estimator, with the decision threshold itself widened adaptively via **Jensen-Shannon divergence** between local and reference windows.

Adversarial robustness measured directly against the same engine used in production, not a separate benchmark harness: PGD/BIM/MI-FGSM, affine/elastic, Carlini-Wagner (L2/L∞), DeepFool, and Fourier-domain attacks, with the one weak point (C&W L∞, 64%) investigated and reported alongside the wins (Fourier: 99.78%+).

**Concepts:** Chauvenet's Criterion • Tukey's Fences • Hampel Filter • Lagrange-Multiplier BLUE • Jensen-Shannon Adaptive Thresholding

[![PyPI](https://img.shields.io/badge/pypi-dense--armor-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/dense-armor/)
[![tests](https://github.com/tatopenn-cell/Dense-Armor/actions/workflows/tests.yml/badge.svg)](https://github.com/tatopenn-cell/Dense-Armor/actions/workflows/tests.yml)
[![codecov](https://codecov.io/gh/tatopenn-cell/Dense-Armor/branch/master/graph/badge.svg)](https://codecov.io/gh/tatopenn-cell/Dense-Armor)
[![Docs](https://img.shields.io/badge/docs-tatopenn--cell.github.io-00e5ff?style=flat-square)](https://tatopenn-cell.github.io/Dense-Armor/)

---

### 🧬 Computational Biology

### 🧫 [Dense-Evolution-Molecular-Pipeline](https://github.com/tatopenn-cell/Dense-Evolution-Molecular-Pipeline)

A hybrid bio-quantum pipeline for Chronic Myeloid Leukemia treatment optimization: a JAX-accelerated genetic algorithm — steered by the same Phi_AB predictive-healing coherence signal from `dense_evolution/healing.py` — searches BCR-ABL1 kinase-domain sequence variants, folded via the Meta ESMFold API (with a deterministic alpha-helix fallback), then scored by AutoDock Vina docking against Imatinib. Best measured run: **−9.79 kcal/mol** binding affinity.

**Concepts:** JAX Genetic Optimization • Phi_AB Predictive Healing • ESMFold Structure Prediction • AutoDock Vina Docking

---

## 🛠️ Technical Stack

### ⚛️ Quantum & Scientific Computing

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JAX](https://img.shields.io/badge/JAX_XLA-f9ab00?style=for-the-badge&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)
![PennyLane](https://img.shields.io/badge/PennyLane-1a1a2e?style=for-the-badge)

### 🧬 Bio-Computational

![RDKit](https://img.shields.io/badge/RDKit-1a1a2e?style=for-the-badge)
![AutoDock Vina](https://img.shields.io/badge/AutoDock_Vina-2e7d32?style=for-the-badge)
![Py3Dmol](https://img.shields.io/badge/Py3Dmol-2e7d32?style=for-the-badge)

### 📦 Release & Publishing

![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![Zenodo](https://img.shields.io/badge/Zenodo-1682D4?style=for-the-badge&logo=zenodo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MkDocs Material](https://img.shields.io/badge/MkDocs_Material-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=white)

### 🤖 Multi-Agent & Knowledge Tooling

![Model Context Protocol](https://img.shields.io/badge/MCP-000000?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG_Knowledge_Base-6a0dad?style=for-the-badge)
![Multi--Agent Pipelines](https://img.shields.io/badge/Multi--Agent_Pipelines-00897b?style=for-the-badge)

### ⚙️ Tools & Workflow

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 💡 Philosophy

A paper becomes math, math becomes code, and every claim — quantum, statistical, or biological — ships next to the script that produced it.

---

## 📬 Get in Touch

Questions, ideas, or a paper worth implementing? [tatopenn@gmail.com](mailto:tatopenn@gmail.com) · [Dense-Evolution issues →](https://github.com/tatopenn-cell/Dense-Evolution/issues)

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/216656967-625b2a52-e638-4c21-a8ae-180560386f96.gif" width="160" />
<img src="https://user-images.githubusercontent.com/74038190/216649426-0c2ee152-84d8-4707-85c4-27a378d2f78a.gif" width="160"/>
<img src="https://user-images.githubusercontent.com/74038190/216656944-f8c1b44e-493b-487f-87be-6cfe6a1a3374.gif" width="160"/>
<img src="https://user-images.githubusercontent.com/74038190/216655855-e00c1861-e964-4b4f-90ae-2592cad7b272.gif" width="160"/>
</div>

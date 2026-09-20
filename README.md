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
- 🧬 **Computational biology**

The goal is not simply to write experimental code, but to turn mathematical and scientific ideas into **tested, reproducible and maintainable software**.

I am the author of [`dense-evolution`](https://pypi.org/project/dense-evolution/), a JAX/XLA statevector simulator for NISQ circuits, VQE and QML, and [`dense-armor`](https://github.com/tatopenn-cell/Dense-Armor), a runtime robustness framework for AI model input/output.

Both projects are developed as real software projects, with automated testing, CI, documentation and public releases.

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

## 🧠 Engineering Mindset

I treat software development as an iterative engineering process.

```text
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
````

AI agents can accelerate individual steps, but the engineering process remains under human control.

Each agent has a specific task, its output is checked, and unexpected behaviour is investigated rather than silently accepted.

---

## 🔬 Research Interests

<details>
<summary><b>View full research interests</b></summary>

Quantum Phase Transitions & Order Parameters • Molecular VQE & Potential Energy Curves • Quantum Defect Mapping • Crystalline Lattice Dispersion & Tight-Binding • Strained-Silicon & GaAs Bandstructure Engineering • Quantum Lattice Thermodynamics (Phonon Scattering & Decoherence) • Zero-Noise Extrapolation (Stochastic Richardson, ZNE-before-PSR, Photonic Predictive) • Loschmidt Echo & Channel Non-Commutativity • Topological Mott Insulators • Quantum Error Correction (Steane [[7,1,3]] on Real Hardware Calibration) • Traversable-Wormhole SYK Teleportation • AI Runtime Robustness • Robust Statistics • Computational Biology • Multi-Agent AI Pipelines

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

[![PyPI](https://img.shields.io/pypi/v/dense-evolution?style=flat-square\&color=00e5ff)](https://pypi.org/project/dense-evolution/)
[![CI](https://github.com/tatopenn-cell/Dense-Evolution/actions/workflows/ci.yml/badge.svg)](https://github.com/tatopenn-cell/Dense-Evolution/actions/workflows/ci.yml)
[![DOI](https://zenodo.org/badge/1247011090.svg)](https://doi.org/10.5281/zenodo.21855643)

---

### 🌀 [Dense-Evolution-Discovery](https://github.com/tatopenn-cell/Dense-Evolution-Discovery)

The research and experimental layer built on top of Dense-Evolution.

It contains **documented computational experiments**, with results re-measured when changes to the underlying simulator or noise model could affect previous conclusions.

The goal is to keep the experimental process reproducible rather than treating research results as static numbers.

**Concepts:**
`Parameter-Shift Rule` • `Born-Rule Kraus Sampling` • `Statistical Re-Verification`

---

# 🛡️ AI Runtime Robustness

### 🐙 [Dense-Armor](https://github.com/tatopenn-cell/Dense-Armor)

A runtime shield for **AI model input/output**, designed to work without retraining the underlying model.

Dense-Armor contains two main components:

### `Armatura`

Filters 1D signal streams such as:

* loss curves;
* sensor telemetry;
* numerical monitoring streams.

It uses a binary Phi_AB coherence trigger connected to the healing mechanism developed in Dense-Evolution.

### `Orca`

Wraps an entire model with:

* an adaptive stabilizer;
* a Collatz-based damping gate;
* protection applied around inference.

The statistical detection layer combines four classical anomaly-detection approaches:

* **Chauvenet's criterion (1863)**
* **Tukey's fences**
* **Hampel filter**
* **iterative sigma-clipping**

Their outputs are combined through a Lagrange-multiplier **BLUE** estimator.

The decision threshold is then adapted using **Jensen-Shannon divergence** between local and reference windows.

### Adversarial validation

Robustness is measured against the same engine used by the system rather than relying only on a separate benchmark harness.

The project investigates attacks including:

* PGD;
* BIM;
* MI-FGSM;
* affine attacks;
* elastic attacks;
* Carlini-Wagner;
* DeepFool;
* Fourier-domain attacks.

Weak cases are investigated alongside successful defenses rather than being hidden.

For example, the reported results include a weaker C&W L∞ case and Fourier-domain results above 99.78%.

**Concepts:**
`Chauvenet's Criterion` • `Tukey's Fences` • `Hampel Filter` • `Lagrange-Multiplier BLUE` • `Jensen-Shannon Adaptive Thresholding`

[![PyPI](https://img.shields.io/badge/pypi-dense--armor-3775A9?style=flat-square\&logo=pypi\&logoColor=white)](https://pypi.org/project/dense-armor/)
[![tests](https://github.com/tatopenn-cell/Dense-Armor/actions/workflows/tests.yml/badge.svg)](https://github.com/tatopenn-cell/Dense-Armor/actions/workflows/tests.yml)
[![codecov](https://codecov.io/gh/tatopenn-cell/Dense-Armor/branch/master/graph/badge.svg)](https://codecov.io/gh/tatopenn-cell/Dense-Armor)
[![Docs](https://img.shields.io/badge/docs-tatopenn--cell.github.io-00e5ff?style=flat-square)](https://tatopenn-cell.github.io/Dense-Armor/)

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

| Project                       | Package          | CI | Tests | Documentation | Research Artifact |
| ----------------------------- | ---------------- | -- | ----- | ------------- | ----------------- |
| **Dense-Evolution**           | ✅ PyPI           | ✅  | ✅     | ✅             | ✅ DOI             |
| **Dense-Armor**               | ✅ PyPI           | ✅  | ✅     | ✅             | —                 |
| **Dense-Evolution-Discovery** | 🔬 Research repo | —  | 🔬    | 🔬            | 🔬                |

The important distinction is between **an experiment that runs once** and **software that can be tested, reproduced, documented and released**.

---

# 🛠️ Technical Stack

## ⚛️ Quantum & Scientific Computing

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![JAX](https://img.shields.io/badge/JAX_XLA-f9ab00?style=for-the-badge\&logo=google\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge\&logo=scipy\&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge\&logo=qiskit\&logoColor=white)
![PennyLane](https://img.shields.io/badge/PennyLane-1a1a2e?style=for-the-badge)

## 🧬 Bio-Computational

![RDKit](https://img.shields.io/badge/RDKit-1a1a2e?style=for-the-badge)
![Py3Dmol](https://img.shields.io/badge/Py3Dmol-2e7d32?style=for-the-badge)

## 📦 Release & Publishing

![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge\&logo=pypi\&logoColor=white)
![Zenodo](https://img.shields.io/badge/Zenodo-1682D4?style=for-the-badge\&logo=zenodo\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)
![MkDocs Material](https://img.shields.io/badge/MkDocs_Material-526CFE?style=for-the-badge\&logo=materialformkdocs\&logoColor=white)

## 🤖 Multi-Agent & Knowledge Tooling

![Model Context Protocol](https://img.shields.io/badge/MCP-000000?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG_Knowledge_Base-6a0dad?style=for-the-badge)
![Multi--Agent Pipelines](https://img.shields.io/badge/Multi--Agent_Pipelines-00897b?style=for-the-badge)

## ⚙️ Tools & Workflow

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)

---

# 🔄 From Research to Software

```text
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
```

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
[**Dense-Evolution issues →**](https://github.com/tatopenn-cell/Dense-Evolution/issues)

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/216656967-625b2a52-e638-4c21-a8ae-180560386f96.gif" width="160" />
<img src="https://user-images.githubusercontent.com/74038190/216649426-0c2ee152-84d8-4707-85c4-27a378d2f78a.gif" width="160"/>
<img src="https://user-images.githubusercontent.com/74038190/216656944-f8c1b44e-493b-487f-87be-6cfe6a1a3374.gif" width="160"/>
<img src="https://user-images.githubusercontent.com/74038190/216655855-e00c1861-e964-4b4f-90ae-2592cad7b272.gif" width="160"/>

</div>
```


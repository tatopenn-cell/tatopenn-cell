<h1 align="center">
  Hi there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> I'm Tato Penn
</h1>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&center=true&vCenter=true&width=900&lines=Software+Engineer+%7C+Scientific+Computing;JAX+XLA+Systems+Engineering;Quantum+Simulation+%26+VQE;Online+Learning+%26+Runtime+Robustness)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-pennacchio-090924413/)
[![Email](https://img.shields.io/badge/Email-Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tatopenn@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tatopenn-cell)
[![Dense-Evolution Docs](https://img.shields.io/badge/Docs-Dense--Evolution-00e5ff?style=for-the-badge&logo=materialformkdocs&logoColor=white)](https://tatopenn-cell.github.io/Dense-Evolution/)
[![PyPI dense-evolution](https://img.shields.io/badge/PyPI-dense--evolution-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/dense-evolution/)

</div>

---

## Purpose

Four public repositories, all tested in CI, all documented, all with a license. Each one is an engineering artifact, not a demo.

- **[Dense-Evolution](https://github.com/tatopenn-cell/Dense-Evolution)** — NISQ quantum simulation toolkit in JAX/XLA, on PyPI, with a research DOI.
- **[Dense-Evolution-Discovery](https://github.com/tatopenn-cell/Dense-Evolution-Discovery)** — the research lab where quantum, robot-safety and adversarial experiments are run before they are trusted; results re-measured, negative results kept.
- **[Dense-Armor](https://github.com/tatopenn-cell/Dense-Armor)** — online-learning library for robots and LLMs, with a runtime protection layer.
- **[local-quantum-rag](https://github.com/tatopenn-cell/local-quantum-rag)** — local hybrid RAG that grounds the AI's claims in the actual PDFs, so the answers cite what a document says instead of what a model remembers.

| | |
|---|---|
| 📍 **Location** | Napoli, Italy |
| 🧭 **Focus** | JAX/XLA · quantum simulation · online learning · runtime robustness |
| 📦 **PyPI** | [`dense-evolution` 8.3.2](https://pypi.org/project/dense-evolution/) (Python ≥3.9) · [`dense-armor` 1.1.33](https://pypi.org/project/dense-armor/) (Python ≥3.10) |
| 🏷️ **Research DOIs** | Dense-Evolution [10.5281/zenodo.21855643](https://doi.org/10.5281/zenodo.21855643) · Discovery [10.5281/zenodo.21855620](https://doi.org/10.5281/zenodo.21855620) · local-quantum-rag [10.5281/zenodo.22914813](https://doi.org/10.5281/zenodo.22914813) |
| ✅ **CI** | [Dense-Armor](https://github.com/tatopenn-cell/Dense-Armor/actions) · [Dense-Evolution](https://github.com/tatopenn-cell/Dense-Evolution/actions) · [Discovery](https://github.com/tatopenn-cell/Dense-Evolution-Discovery/actions) · [local-quantum-rag](https://github.com/tatopenn-cell/local-quantum-rag/actions) |

---

## Currently

- **Dense-Armor** — the N03 online-learning layers (convolution, recurrent, attention) are merged; one task per week.
- **Dense-Evolution-Discovery** — re-running quantum experiments after the noise-model update; results re-measured, not copied.
- **local-quantum-rag** — the four-phase methodology is documented; the constraint layer is being extended.
- **Reading and re-implementing** — *Attention Is All You Need* (Vaswani et al. 2017) and *LSTM: A Search Space Odyssey* (Greff et al. 2017).

---

## Method: how the work is structured

The work is AI-assisted but human-supervised. AI is a tool inside a documented process, not an autonomous decision maker. The process itself is written down in [local-quantum-rag](https://github.com/tatopenn-cell/local-quantum-rag), in four phases that are not interchangeable:

1. **Exploration.** Idea to prototype. Cheap, high-context model, many iterations, code runs outside the model's session.
2. **Verification.** The question changes from "does it work" to "does it implement what the paper states". A stronger model with retrieval access to the actual PDFs checks the code against the source paper, equation by equation.
3. **Discovery.** The result moves into a public, reproducible repository, where it may still be rejected. Every script runs end to end; negative results are kept, not deleted.
4. **Production.** Only what survived Discovery ships to real users. The shipping list is checked against the real directory tree, the platform physically refuses a merge until the named checks are green, and publishing to the index is a separate human-confirmed step.

Two principles run through all four phases: **process documents** are for the human, **constraint documents** are for the AI, and they are different documents; and a static instruction only constrains behaviour at the specific trigger points it names — everywhere else, it is invisible.

> A paper becomes math, math becomes code, and every claim — quantum, statistical or biological — ships next to the script that produced it.

---

## About

Software engineer in Napoli, Italy. The scope is the full engineering cycle — research, design, prototype, implementation, testing, validation, documentation, release — on the four projects above. Every project ships as a Python package (or, for local-quantum-rag, a CLI plus a FastAPI server) with CI, documentation and a license.

---

# Featured Projects

## [Dense-Evolution](https://github.com/tatopenn-cell/Dense-Evolution)

**NISQ quantum simulation toolkit in JAX/XLA. Statevector and MPS engines, with compilation, noise, VQE, QEC, chemistry and an MCP server for agent-driven control.**

- Up to 28 qubits in about 3 seconds, JIT-compiled through JAX XLA, with automatic chunking and disk spill past the RAM ceiling.
- A native Hartree-Fock engine with Obara-Saika recursion, real molecular Hamiltonians, Jordan-Wigner mapping.
- Zero-Noise Extrapolation (Richardson, ZNE-before-PSR), VQE, QEC.
- Composer web UI and a local Streamlit dashboard.
- Featured in [Awesome Quantum Software](https://github.com/qosf/awesome-quantum-software).

<details>
<summary>Install, license</summary>

~~~bash
pip install dense-evolution
~~~

License: AGPL-3.0. Distributed with documentation, CI and a research DOI.

</details>

[PyPI](https://pypi.org/project/dense-evolution/) · [CI](https://github.com/tatopenn-cell/Dense-Evolution/actions/workflows/ci.yml) · [DOI](https://doi.org/10.5281/zenodo.21855643) · [Docs](https://tatopenn-cell.github.io/Dense-Evolution/)

---

## [Dense-Evolution-Discovery](https://github.com/tatopenn-cell/Dense-Evolution-Discovery)

**The research lab for Dense-Evolution and Dense-Armor. Every claim is a script, run and checked before it was written up, with the negative results kept alongside the positive ones.**

<details>
<summary>What is inside, license</summary>

- **MPS GPU optimization** — the matrix-product-state backend on GPU (2.16× measured), with the three real bugs found along the way.
- **Dense-Armor: robot safety** — drift, fault detection and safety filtering on real IMU, Lidar and LeRobot arm data.
- **Dense-Armor: security telemetry** — MITRE ATT&CK APT29 attack detection on real Sysmon telemetry, plus Orca protecting a real scikit-learn model from adversarial input corruption.
- **Quantum simulation and physics** — TFIM phase transitions, VQE, ZNE, tight-binding materials, and a critical replication of the traversable-wormhole teleportation protocol.
- **Diagnostics and healing** — density-matrix noise diagnostics (Rényi divergence, magic entropy) and vector-healing fixes that were shipped back into Dense-Evolution.
- **Dynamic Vacuum Pressure Theory** — a cosh-shaped vacuum regularization derived from three independent directions, checked against real EHT/LIGO/NICER data, with a dense_evolution-verified Z₂ symmetry linking cosh, the Bell state and Taoist duality.

License: see the LICENSE.md file in the repository.

</details>

[CI](https://github.com/tatopenn-cell/Dense-Evolution-Discovery/actions/workflows/ci.yml) · [DOI](https://doi.org/10.5281/zenodo.21855620) · [Docs](https://tatopenn-cell.github.io/Dense-Evolution-Discovery/)

---

## [Dense-Armor](https://github.com/tatopenn-cell/Dense-Armor)

**Online-learning library for robots and LLMs. One sample at a time, inside a control-loop budget, with a runtime protection layer.**

- **Learns one sample at a time.** Every estimator has `learn_one`, `predict_one`, `score_one`. No retraining, no batch.
- **Fits a control loop.** `budget_s` and `RealtimePipeline` refuse an estimator that does not fit the period.
- **Protects itself while it learns.** `Protected` and `SafeEstimator` wrap any model; a drift detector, an anomaly detector or the `Orca` runtime shield can flag and fall back.
- **One base for everything.** Classifiers, regressors, transformers, anomaly and drift detectors inherit from `dense_armor.roles`. An estimator for a robot is also an estimator an LLM can call as a tool.

<details>
<summary>Install, what is inside, license</summary>

~~~bash
pip install dense-armor
~~~

**32 families** under `dense_armor/utility/`: linear models, naive Bayes, k-NN, incremental trees and forests, ensembles, factorization machines, recommenders, bandits, multiclass and multi-output; the neural stack (dense, convolution, RNN/GRU/LSTM, multi-head attention, transformer blocks, plus `mlp`, `resnet_mlp`, `cnn`, `recurrent_net`, `transformer_encoder`); streaming statistics and sketches; CUSUM, Page-Hinkley, ADWIN, KSWIN, BOCPD; fourteen anomaly detectors; twenty online metrics; online vision; kinematic control and CBF filters.

**The protection layer** (`protect/`): `Armatura` (a Phi_AB coherence trigger on 1D signal streams) and `Orca` (an adaptive stabilizer with a Collatz-based damping gate). Thresholds adapt with Jensen-Shannon divergence on the local window. Adversarial robustness is measured against the same engine the system uses; weak cases are reported, not hidden.

**Optional bridges**, installed as extras: `river`, `llm`, `quantum`, `vision`, `drone`, `ros`, `finance-stream`, `data`, `audio`, `mcp`.

**Documentation:** 39 sections on the site, including `docs/drones/` (13 pages), `docs/finance/` (17 pages), `docs/shields/` (5 pages) and `docs/compare/`, where each batch class of the machine-learning task is compared, on the same data and metric, with its online counterpart.

License: the repository carries `LICENSE` and `LICENSE-BUSL-1.1-until-1.1.32.md` (the historical license for versions up to 1.1.32).

</details>

[PyPI](https://pypi.org/project/dense-armor/) · [CI](https://github.com/tatopenn-cell/Dense-Armor/actions/workflows/tests.yml) · [codecov](https://codecov.io/gh/tatopenn-cell/Dense-Armor) · [Docs](https://tatopenn-cell.github.io/Dense-Armor/)

---

## [local-quantum-rag](https://github.com/tatopenn-cell/local-quantum-rag)

**Local hybrid RAG that grounds technical conversations in your own PDFs and notes, so an AI assistant cites what a document actually says instead of what it remembers.**

- CLI (`query.py`) for everyday use; optional local FastAPI server (`server.py`) that keeps the embedding and reranker models warm across repeated queries.
- Endpoints `/search`, `/search_exact`, `/collections`, with an in-process mtime-invalidated cache and token auth.
- The methodology described above lives here: four phases, process documents vs constraint documents, verification against the source paper.

<details>
<summary>Install, license</summary>

~~~bash
pip install -e .
~~~

Optional server:

~~~bash
pip install -e .[server]
python server.py --port 8000
~~~

License: MIT.

</details>

[CI](https://github.com/tatopenn-cell/local-quantum-rag/actions/workflows/ci.yml) · [DOI](https://doi.org/10.5281/zenodo.22914813) · [Docs](https://tatopenn-cell.github.io/local-quantum-rag/)

---

# Engineering Signals

| Project | Package | CI | Tests | Documentation | DOI |
|---|---|---|---|---|---|
| Dense-Evolution | PyPI 8.3.2 | ✅ | ✅ | ✅ | ✅ |
| Dense-Evolution-Discovery | research repo | ✅ | ✅ | ✅ | ✅ |
| Dense-Armor | PyPI 1.1.33 | ✅ | ✅ | ✅ | — |
| local-quantum-rag | CLI + FastAPI server | ✅ | ✅ | ✅ | ✅ |

The distinction that matters: **an experiment that runs once** vs **software that can be tested, reproduced, documented and released**.

---

# Technical Stack

**Scientific computing** — Python · JAX/XLA · NumPy · SciPy · Qiskit · PennyLane

**Engineering** — pytest · coverage · Ruff · Mypy · GitHub Actions · MkDocs Material · PyPI · Zenodo

**RAG and AI tooling** — FastAPI · sentence-transformers · cross-encoder rerankers · MCP

**Environment** — Jupyter · Colab · Kaggle · Git · Linux

---

# Get in Touch

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

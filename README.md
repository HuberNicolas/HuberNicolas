<div align="center">

# `Nicolas Huber`

### makes messy data behave

**`raw data`** &nbsp;→&nbsp; **`pipeline`** &nbsp;→&nbsp; **`model`**

[![Website](https://img.shields.io/badge/nicolas--huber.dev-0d0d14?style=flat-square&logo=firefox&logoColor=5cf0b0)](https://nicolas-huber.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d0d14?style=flat-square&logo=linkedin&logoColor=6eb5ff)](https://www.linkedin.com/in/nicolas-huber-dev/)
[![ORCID](https://img.shields.io/badge/ORCID-0d0d14?style=flat-square&logo=orcid&logoColor=a6ce39)](https://orcid.org/0009-0001-3266-2338)
![Location](https://img.shields.io/badge/Zürich,%20CH-0d0d14?style=flat-square&logo=googlemaps&logoColor=ffc06e)

</div>

---

## `> whoami`

I build data pipelines and machine-learning systems. Since June 2025 I'm an IT
trainee at Migros, rotating through the data teams of the group. Before that I
did my BSc and MSc in Informatics at the **University of Zurich**, with a
semester at UTS Sydney in between.

What I enjoy most is the full chain: a pipeline, a model, and an interactive
visualisation at the end that people actually use. I like to understand the
data before I build on it, and I'd rather publish a worse number than a wrong
one (see the heart disease rewrite below).

```python
class NicolasHuber:
    role     = "IT trainee, data engineering & ML"
    employer = "Migros-Genossenschafts-Bund"
    rotation = "Digitec Galaxus, product development"   # current station
    degree   = "MSc Informatics, UZH"
    focus    = ["data pipelines", "ML in production", "visual analytics"]
```

## `> git log --oneline`

```text
2026  digitec-galaxus  product development team: moving ML models to a new Airflow platform
2026  migros-bank      dbt + Dagster pipeline on OpenShift, workshops on dbt, data products and Git
2025  mgb-data         aggregation layer for model training, built as a dbt pipeline on Google Cloud
2025  msc-uzh          thesis: SDG Tag Heroes, graded 6.0
2024  uts-sydney       exchange semester: UNIX systems, data science, cyber security
2023  ivda-uzh         research assistant: visual analytics prototypes with FastAPI, Qdrant, Vue, D3
2023  ieee             co-author of a paper on Moving Target Defense, from my bachelor's thesis
2021  novu             junior web developer: Symfony apps, an internal ERP, courses for apprentices
```

## `> featured work`

### `live` &nbsp;you can open these right now

| Project | What it is |
| --- | --- |
| **[SDG Tag Heroes](https://github.com/HuberNicolas/sdg-tag-heroes)** · [open the app](https://frontend-qluali6siqmkdt9wqr0q9jbd.169.58.124.58.sslip.io/) | Researchers label papers by UN Sustainable Development Goal: a model suggests, players vote and decide. Covers the whole chain from harvesting publications over embeddings and a vector database to the API and a D3 frontend. Master's thesis, 2025, graded 6.0; the thesis state lives on the [`thesis`](https://github.com/HuberNicolas/sdg-tag-heroes/tree/thesis) branch. Runs on my own server ([infrastructure](https://github.com/HuberNicolas/infrastructure)). `Nuxt` `D3` `FastAPI` `Qdrant` |
| **[Towers vs. Monsters](https://github.com/HuberNicolas/tower-defense-remastered)** · [play it](https://hubernicolas.github.io/tower-defense-remastered/) | A tower defense game where every tower fires in one straight line, so where you put it and which way it faces decides everything. 30 rounds with boss waves. Remake of our 2021 software engineering lab project, which needed a Java server and a fixed window; this one runs in the browser, on desktop and phone. `React` `TypeScript` `Canvas` |
| **[OkCupid Explorer](https://github.com/HuberNicolas/okcupid-explorer)** · [live demo](https://hubernicolas.github.io/okcupid-explorer/) | Answer a dating questionnaire and see where you land among 842 OkCupid profiles. Cosine similarity, PCA and k-means run in the browser. Group project 2022, rebuilt 2026. `Vue` `TypeScript` `ECharts` |

<p align="center">
  <a href="https://hubernicolas.github.io/tower-defense-remastered/"><img src="https://raw.githubusercontent.com/HuberNicolas/tower-defense-remastered/main/docs/images/game.png" alt="Towers vs. Monsters: plant towers shooting along the path at a wave of monsters" width="620"></a>
</p>

### `data & ml`

| Project | What it is |
| --- | --- |
| **[heart-disease-risk-factors-uzh](https://github.com/HuberNicolas/heart-disease-risk-factors-uzh)** | Our first data science project from 2021, rewritten in 2026. The rewrite found target leakage in the original: without it, the models barely beat the baseline. `scikit-learn` `pandas` |
| **[sdg-classifier](https://github.com/HuberNicolas/sdg-classifier)** | DistilBERT fine-tuned for multi-label SDG classification of abstracts, with full fine-tuning or LoRA. Built for the thesis in 2024, rebuilt as a package in 2026 with a fix for the class weights. `PyTorch` `Transformers` |
| **[academia-maestro](https://github.com/HuberNicolas/academia-maestro)** | Asks a folder of research papers the same questions and turns the answers into a comparison table for a literature review. Works with ChatPDF, Claude or a local model through Ollama. `Python` `LLM` |

### `academia`

| Project | What it is |
| --- | --- |
| **[MTDStrategySelectionAgent](https://github.com/HuberNicolas/MTDStrategySelectionAgent)** | An agent on small IoT devices reads system metrics and picks the Moving Target Defense that fits the malware it sees. Bachelor's thesis; I'm co-author of the resulting [IEEE paper](https://ieeexplore.ieee.org/document/10224824) (2023). `Python` `IoT security` |
| **[network-science-uzh](https://github.com/HuberNicolas/network-science-uzh)** | Four graded assignments from the Network Science course: centralities, community detection, null models and epidemics on networks. UZH, 2023. `NetworkX` `Jupyter` |
| **[numerical-methods-uzh](https://github.com/HuberNicolas/numerical-methods-uzh)** | The classic numerical methods, from root finding to numerical integration, each written from scratch as a MATLAB function. UZH, 2020. `MATLAB` |
| **[gaia-classifier](https://github.com/HuberNicolas/gaia-classifier)** | Sorts Gaia DR3 stars by spectral class: feature sets by decision-tree importance, then a cross-validated grid search over ten classifiers. Class Kaggle competition at UTS Sydney, 2024. `scikit-learn` |

Also here: [infrastructure](https://github.com/HuberNicolas/infrastructure) (one VPS, Coolify, images built in GitHub Actions)
and [docker-dbs](https://github.com/HuberNicolas/docker-dbs) (six databases for local development, one command).

## `> toolbox`

**Languages**
&nbsp;![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

**Data & ML**
&nbsp;![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square)
![Dagster](https://img.shields.io/badge/Dagster-4F43DD?style=flat-square)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)

**Web**
&nbsp;![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)

**Infra & Ops**
&nbsp;![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

---

<div align="center">

<sub>Formerly known as the aspiring code alchemist.</sub>

</div>

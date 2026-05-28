# Multi-metric Analysis of the Relation Between Movement Complexity and Creativity Measures

> **University of Tartu (2026)**  
> **Author:** Jared Michael Wildermuth  
> **Scientific Domain:** Computer Science, Spatial Data Analysis, Cognitive Computing  

---

## 📄 Read the Research
* **[Click here to read the full Master's Thesis Paper (PDF)](https://thesis.cs.ut.ee/bc22158c-0b74-48a5-b1ac-e1d151947ecf)**

---

## 📐 Data & Analytics Pipeline Architecture
Below is the structural architecture of the data engineering, natural language processing, and statistical validation pipeline implemented for this research:

![Thesis Data Pipeline](./Visual_Pipeline.png)

---

## 🔍 Executive Project Overview

This research bridges behavioral data science and cognitive computing by quantifying the intricate relationship between physical movement complexity in virtual environments and divergent creativity. Using spatial tracking data and natural language processing, the pipeline processes multi-modal inputs to uncover behavioral markers of cognitive flexibility.

### 📊 Project at a Glance
| Dimension | Specifications |
| :--- | :--- |
| **Dataset & Sample** | $N = 104$ subjects in a standardized virtual reality environment |
| **Spatial Ingestion** | 10 Hz 3D positional telemetry tracking (Meta Quest 3) |
| **NLP Framework** | Subword tokenization and semantic distance modeling via `fastText` |
| **Statistical Core** | Partial Spearman frameworks and non-linear distance correlations |

### 🛠️ Core Engineering & Analytical Challenges Solved
* **High-Dimensional Feature Extraction:** Transformed raw, noisy 3D spatial coordinates into 18 distinct kinematic, directional, and information-theoretic metrics.
* **Cross-Lingual NLP Modeling:** Successfully adapted semantic distance frameworks (such as the Divergent Association Task) to handle the complex, highly inflected morphology of the Estonian language without loss of contextual meaning.
* **Confound Isolation:** Engineered a rigorous statistical validation step to residualize demographic and environmental noise, ensuring behavioral-cognitive correlations were mathematically sound.
* **ML Architectural Evaluation:** Applied unsupervised learning (PCA and $k$-means clustering) to prove that exploratory behavior exists on a continuous behavioral spectrum rather than rigid, discrete clusters, validating the choice of a statistical framework over an over-parameterized machine learning model.





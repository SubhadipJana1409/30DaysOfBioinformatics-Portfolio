<div align="center">

# 🧬 #30DaysOfBioinformatics
### A 30-Day Computational Biology Portfolio

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Plotly](https://img.shields.io/badge/Plotly-5.0+-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)]()
[![Days](https://img.shields.io/badge/Projects-30%2B-blue?style=for-the-badge)]()

<br/>

> **30 consecutive bioinformatics projects** spanning gut microbiome analysis, antimicrobial resistance prediction, AI/ML on omics data, and complete metagenomic pipelines — all using real public datasets.

<br/>

**[📊 View Interactive Dashboard](#-interactive-portfolio-dashboard) · [📄 Read Capstone Report](#-capstone-report) · [🔬 Browse All Projects](#-project-index)**

</div>

---

## 📌 At a Glance

| | |
|---|---|
| 🗓️ **Duration** | 30 Days |
| 📦 **Projects** | 30 + 3 Bonus |
| 🧪 **Datasets** | BV-BRC · NCBI GEO · ECDC · Gevers 2014 · HUMAnN3 |
| 🤖 **Best Model AUC** | 0.9996 (SNP-based Isoniazid resistance) |
| 🦠 **Best AMR AUC** | 0.993 (Vancomycin Random Forest classifier) |
| 🔬 **Best IBD AUC** | 0.968 (Microbiome Disease Classifier) |
| 💻 **Stack** | Python · sklearn · PyTorch · Plotly · ReportLab · BioPython |
| 📊 **Output** | Interactive dashboard · 8-page PDF report · 28 GitHub repos |

---

## 🗂️ Portfolio Structure

```
30DaysOfBioinformatics-Portfolio/
│
├── day29_dashboard.html        # Full interactive Plotly dashboard (Day 29)
├── day30_portfolio.html        # Final portfolio with Day 30 Capstone section
├── day30_capstone_report.pdf   # 8-page publication-ready scientific report
└── README.md                   # This file
```

---

## 📊 Interactive Portfolio Dashboard

**`day30_portfolio.html`** — Download and open in any browser. Zero dependencies, fully self-contained.

| Section | Content |
|---------|---------|
| 📊 Overview | 30-day timeline · Model performance comparison across all ML projects |
| 🦠 Block 1 | Shannon diversity violin plots · F/B ratio · SCFA trajectories · Hub taxa |
| 🧫 Block 2 | AMR prevalence · AUC by drug · Resistance trends 2002–2017 · SHAP · Risk tiers |
| 🤖 Block 3 | IBD feature importance · Biomarker scatter · AutoML benchmark · SNP resistance |
| 🔬 Block 4 | Bracken species abundance · Pathway log₂FC · Phage catalogue |
| 🏆 Day 30 | Capstone findings · 5 clinical conclusions · 8-stat banner |
| ✅ Summary | Complete 30-day table with methods, datasets, and key results |

> **20 interactive Plotly charts** across 7 sections with dark-theme GitHub-style UI

---

## 📄 Capstone Report

**`day30_capstone_report.pdf`** — 8 pages, publication-ready, 567 KB

- Abstract + Table of Contents
- Full write-up for all 4 blocks + bonus projects
- 5 original matplotlib figures
- 3 data tables (AMR classifiers · ML models · Phage catalogue)
- **Integrated finding:** the microbiome–resistome axis
- Methods summary · Clinical implications · 10 real references
- Complete GitHub repository index with clickable links

---

## 🧱 The Four Blocks

### 🦠 Block 1 — Gut Microbiome Analysis (Days 1–7)

Probiotic intervention trial (LGG vs Placebo · n=44 samples · 2 time points)

| Day | Project | Key Result | Repo |
|-----|---------|------------|------|
| 1 | Alpha Diversity Analysis | Shannon: LGG T2 > Placebo T2 | [→](https://github.com/SubhadipJana1409/Alpha_Diversity_Analysis) |
| 1 | Beta Diversity / PCoA | Bray-Curtis PCoA separation | [→](https://github.com/SubhadipJana1409/Beta_Diversity_Analysis) |
| 2 | Probiotic DEA | 12 taxa enriched in LGG group | [→](https://github.com/SubhadipJana1409/Differential_abundance_analysis) |
| 3 | Enterotyping | 3 distinct enterotypes (PAM + JSD) | [→](https://github.com/SubhadipJana1409/Enterotype_classifier) |
| 4 | F/B Ratio Tracker | High F/B in 67% Placebo vs 45% LGG | [→](https://github.com/SubhadipJana1409/Firmicutes-Bacteroidetes_Ratio_Tracker) |
| 5 | SCFA Prediction | Butyrate index ↑ LGG T2 (+12.3%) | [→](https://github.com/SubhadipJana1409/Short-Chain-Fatty-Acid-Prediction) |
| 6 | Co-abundance Network | 10 hub taxa · Eubacterium hub=1.71 | [→](https://github.com/SubhadipJana1409/Microbiome-Network-Analysis) |
| 7 | Temporal Stability | 130 taxa tracked · ICC>0.8 for 68 | [→](https://github.com/SubhadipJana1409/Longitudinal-Microbiome-Stability-Analysis) |

---

### 🧫 Block 2 — AMR Profiling & Prediction (Days 8–16)

BV-BRC clinical AMR data · ECDC resistance surveillance 2002–2017 · 39 antibiotics · 8 species

| Day | Project | Key Result | Repo |
|-----|---------|------------|------|
| 8 | AMR Prevalence Profiling | KAN 100% · COL 81.2% · VAN 35.6% | [→](https://github.com/SubhadipJana1409/AMR-Prevalence-Profiling) |
| 9 | AMR Classifier (RF) | **AUC=0.993** (Vancomycin) | [→](https://github.com/SubhadipJana1409/Multi-label-RF-Classifier) |
| 10 | SHAP Explainability | Age + S. epidermidis = top predictors | [→](https://github.com/SubhadipJana1409/Gradient-Boosting-SHAP-explainability) |
| 11 | MIC Value Prediction | log₂MIC regression · Ridge/Lasso/SVR | [→](https://github.com/SubhadipJana1409/MIC-Value-Prediction) |
| 12 | Ensemble Classifier | Voting ensemble · improved edge cases | [→](https://github.com/SubhadipJana1409/Ensemble-Stacking-Classifier) |
| 13 | Clinical Risk Scoring | 4 risk tiers · Critical MDR=100% | [→](https://github.com/SubhadipJana1409/Clinical-AMR-Risk-Scoring) |
| 14 | Resistance Trends | CIP 2.25× rise 2002–2017 | [→](https://github.com/SubhadipJana1409/AMR-Trend-Analysis) |
| 15 | Co-resistance Network | 34 antibiotic nodes · phi correlation | [→](https://github.com/SubhadipJana1409/AMR-Co-resistance-Network-Analysis) |

---

### 🤖 Block 3 — AI/ML on Omics Data (Days 17–23)

| Day | Project | Best AUC | Method | Repo |
|-----|---------|----------|--------|------|
| 17 | AMR Phenotype Predictor | 0.743 | GBT + SHAP | [→](https://github.com/SubhadipJana1409/AMR-Phenotype-Predictor) |
| 17 | IBD Disease Classifier | **0.968** | Random Forest + CLR | [→](https://github.com/SubhadipJana1409/Microbiome-based-Disease-Classifie) |
| 18 | Biomarker Discovery | — | SHAP + literature | [→](https://github.com/SubhadipJana1409/Biomarker-Discovery-with-SHAP) |
| 19 | Gene Expression Clustering | — | PCA + K-means | [→](https://github.com/SubhadipJana1409/scRNA-gut-clustering) |
| 20 | Transfer Learning | 0.707 | PyTorch fine-tune (3× vs scratch) | [→](https://github.com/SubhadipJana1409/Transfer-Learning-on-Microbiome-Data) |
| 21 | Anomaly Detection | 0.700 | Elliptic Envelope | [→](https://github.com/SubhadipJana1409/Anomaly-Detection-in-Microbiome) |
| 22 | SNP Resistance Predictor | **0.9996** | Logistic L1 (Isoniazid) | [→](https://github.com/SubhadipJana1409/Drug-Resistance-Mutation-Predictor) |
| 23 | AutoML Benchmark | **0.997** | RF wins · 13 models | [→](https://github.com/SubhadipJana1409/AutoML-Pipeline) |

---

### 🔬 Block 4 — Metagenomic Pipelines (Days 24–27)

| Day | Project | Key Result | Repo |
|-----|---------|------------|------|
| 24 | Taxonomic Profiling | Kraken2 + Bracken · F. prausnitzii 11.9% | [→](https://github.com/SubhadipJana1409/Taxonomic-Profiling-Pipeline) |
| 25 | Functional Annotation | HUMAnN3-style · 20 differential pathways | [→](https://github.com/SubhadipJana1409/Functional-Gene-Annotation-Pipeline) |
| 26 | MAG Assembly | MetaBAT2 + CheckM · high-quality MAGs | [→](https://github.com/SubhadipJana1409/Metagenome-Assembled-Genome-Pipeline) |
| 27 | Phage–Bacteria Interaction | 4-phage gut catalogue · Crassvirales | [→](https://github.com/SubhadipJana1409/Phage-Bacteria-Interaction-Finder) |

---

### ⭐ Bonus Projects — Genomics Deep Dive

| Project | Dataset | Key Result | Repo |
|---------|---------|------------|------|
| Genome Sequence Analysis | E. coli K-12 MG1655 | 4,289 ORFs · GC=50.8% | [→](https://github.com/SubhadipJana1409/Genome-Sequence-Analysis) |
| SNP & Variant Analysis | VCF files | Ts/Tv=2.1 · 94.2% Q≥30 | [→](https://github.com/SubhadipJana1409/SNP-Variant-Analysis) |
| DEG Analysis | **GSE71562 (REAL)** | 96 DEGs · fli*/che* operon | [→](https://github.com/SubhadipJana1409/RNA-seq-DEG-analysis) |
| Bulk RNA-seq DEG | Real RNA-seq | Differential expression pipeline | [→](https://github.com/SubhadipJana1409/Bulk-RNA-seq-differential-expression) |

---

## 🔑 Key Integrated Finding

> *"Gut dysbiosis (↓* Faecalibacterium prausnitzii*, ↑* Escherichia/Shigella*) co-occurs with elevated clinical MDR risk across all analysis blocks, supporting the **microbiome–resistome axis** as a clinically actionable biomarker."*

This cross-block insight connects:
- **Block 1** — LGG probiotic reduces Proteobacteria bloom
- **Block 2** — Escherichia is a top SHAP predictor for AMR
- **Block 3** — Escherichia/Shigella = #1 IBD classifier feature (permutation importance 0.077)
- **Block 4** — Kraken2 confirms Proteobacteria dominance in dysbiotic samples

---

## 🛠️ Tech Stack

```
Data Analysis      pandas · numpy · scipy · statsmodels
Machine Learning   scikit-learn · PyTorch · SHAP · TPOT
Microbiome         scikit-bio · skbio · CLR normalisation
Metagenomics       Kraken2 · Bracken · MetaBAT2 · HUMAnN3 (simulated)
Genomics           BioPython · pysam · VCF parsing
Visualisation      matplotlib · seaborn · Plotly.js
Reporting          ReportLab · HTML/CSS/JS
```

---

## 📚 Real Datasets Used

| Dataset | Source | Used In |
|---------|--------|---------|
| AMR Phenotypes | [BV-BRC](https://www.bv-brc.org) | Days 8–16 |
| Resistance Surveillance | [ECDC](https://ecdc.europa.eu) | Day 14 |
| IBD Microbiome | Gevers et al. 2014, *Cell Host Microbe* | Days 17–18 |
| E. coli RNA-seq | [GSE71562, NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE71562) | Bonus B3 |
| E. coli K-12 Genome | [NCBI RefSeq](https://www.ncbi.nlm.nih.gov/nuccore/U00096) | Bonus B1 |
| Gut WGS (simulated pipeline) | HUMAnN3 / Bracken style | Days 24–27 |

---

## 🚀 Quick Start

```bash
# Clone this repo
git clone https://github.com/SubhadipJana1409/30DaysOfBioinformatics-Portfolio
cd 30DaysOfBioinformatics-Portfolio

# Open the interactive dashboard (no install needed)
open day30_portfolio.html        # macOS
xdg-open day30_portfolio.html    # Linux
start day30_portfolio.html       # Windows

# View the capstone report
open day30_capstone_report.pdf
```

For individual project pipelines, clone the specific day's repository:

```bash
# Example: IBD Disease Classifier
git clone https://github.com/SubhadipJana1409/Microbiome-based-Disease-Classifie
cd Microbiome-based-Disease-Classifie
pip install -r requirements.txt
python classifier.py
```

---

## 📈 Results Summary

```
┌─────────────────────────────────────────────────────────┐
│              Top Model Performances                     │
├──────────────────────────────┬──────────┬───────────────┤
│ Project                      │ AUC-ROC  │ Method        │
├──────────────────────────────┼──────────┼───────────────┤
│ SNP Resistance (Isoniazid)   │ 0.9996   │ Logistic L1   │
│ AutoML Benchmark             │ 0.9967   │ Random Forest │
│ AMR Classifier (Vancomycin)  │ 0.9928   │ Random Forest │
│ AMR Classifier (Ceftazidime) │ 0.9841   │ Random Forest │
│ IBD Disease Classifier       │ 0.9676   │ Random Forest │
│ AMR Classifier (Penicillin)  │ 0.9592   │ Random Forest │
│ Transfer Learning (fine-tune)│ 0.7067   │ PyTorch       │
│ Anomaly Detection            │ 0.6996   │ Elliptic Env. │
└──────────────────────────────┴──────────┴───────────────┘
```

---

## 👤 Author

**Subhadip Jana**

[![GitHub](https://img.shields.io/badge/GitHub-SubhadipJana1409-181717?style=for-the-badge&logo=github)](https://github.com/SubhadipJana1409)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-subhadip--jana1409-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/subhadip-jana1409)

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

All datasets are publicly available and credited to their respective sources.
Analyses are reproducible with Python 3.10+ and open-source libraries.

---

<div align="center">

**⭐ If this portfolio helped you, please star the repo!**

*Built with 🧬 curiosity · 🐍 Python · ☕ coffee · and 30 days of persistence*

</div>

# 🧭 Interactive Schema Viewer for fMRI Preprocessing and Graph-Analysis Benchmarking

This repository provides an **open-access, web-based schema visualization and reporting tool** designed to support transparent documentation, inspection, and validation of analytical decision spaces in graph-based fMRI research.

The repository contains **only the interactive schema viewer and its associated visual assets**. No datasets, annotations, LLM outputs, or benchmarking results are included here.

This separation ensures that the methodological schema is **publicly accessible and reusable**, while sensitive benchmark data and internal pipelines remain protected in a separate private repository.

---

## 📌 Overview

Graph-based fMRI analyses involve a large number of preprocessing, connectivity estimation, and graph-construction decisions. These analytical choices form a complex *methodological decision space* that is often difficult to document, compare, or reproduce across studies.

This repository hosts an **interactive schema viewer** that makes this decision space explicit and navigable. The tool enables users to:

- Explore the full hierarchical benchmarking schema used for fMRI preprocessing and graph analysis
- Inspect schema families, groups, steps, and sublabels in a structured and visual manner
- Support human-in-the-loop validation of extracted methodological metadata
- Generate standardized, structured reports of preprocessing and analysis pipelines

The viewer is intended for **researchers, reviewers, and collaborators** who wish to better understand, audit, or communicate analytical pipelines in connectome-based neuroimaging studies.

---

## 📂 Repository Structure

```
├── Images/
│   ├── tab1.jpeg
│   ├── tab2.jpeg
│   ├── tab3.jpeg
│   └── workflow.png
│
├── Schema_Viewer/
│   └── schema_viewer.html
│
└── README.md
```

---

## 🧭 Schema_Viewer (Interactive Schema Explorer)

**Path:**  
`Schema_Viewer/schema_viewer.html`

### Description

The schema viewer is a **client-side, browser-based application** that provides an interactive interface for exploring and documenting the benchmarking schema used in graph-based fMRI analyses.

It bridges the gap between **abstract annotation schemas** and **concrete preprocessing and analysis pipelines** implemented in empirical studies.

---

## 🔹 Key Functionalities

### Schema Graph (Tab 1)
Interactive force-directed graph of the full benchmarking schema, allowing exploration of families, groups, steps, and sublabels with zoom, search, and hierarchical inspection.

### Annotations Explorer (Tab 2)
Visualization and inspection of Label Studio–compatible JSON annotations, enabling rapid qualitative validation of extracted metadata.

### Generate Report (Tab 3)
Guided report builder for manual documentation of preprocessing and graph-analysis pipelines, producing structured text summaries aligned with the schema.

---

## ▶️ Usage

- Open `Schema_Viewer/schema_viewer.html` in any modern browser (Chrome or Edge recommended)
- No backend or server required; runs fully client-side
- Optionally load external JSON annotation files for inspection

---

## 🔁 Contextual Workflow

The schema viewer integrates into a broader LLM-assisted benchmarking framework involving extraction, merging, validation, and standardized reporting of analytical decisions. This repository provides the **schema visualization and reporting component only**.

---

## 📄 License

See the LICENSE file in this repository.

---

## 📬 Contact

**Sana Hassan Imam**  
PhD Researcher, Data Science & Neuroimaging  
GitHub: https://github.com/sanahassanimam  
Email: sana.hassan.imam@uni-oldenburg.de

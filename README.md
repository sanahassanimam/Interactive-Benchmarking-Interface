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

- Interactive force-directed graph representation of the full benchmarking schema  
- Nodes represent families, groups, steps, and sublabels  
- Click to inspect definitions, relationships, and hierarchy  
- Supports expand/collapse, zooming, and search  
<p align="center">
  <img src="Images/tab1.jpeg" width="800">
</p>

### Annotations Explorer (Tab 2)

- Load Label Studio–compatible JSON files  
- Visualize extracted text with highlighted annotation spans  
- Inspect label distributions and annotation metadata  
<p align="center">
  <img src="Images/tab2.jpeg" width="800">
</p>


### Generate Report (Tab 3)

- Manual, guided report builder aligned with the benchmarking schema  
- Allows users to:
  - Select schema families  
  - Tick present preprocessing steps  
  - Enter step numbers, software, algorithms/types, and parameters  
- Produces a structured, text-based report summarizing preprocessing and analysis decisions  
<p align="center">
  <img src="Images/tab3.jpeg" width="800">
</p>


## 🎯 Purpose in the Benchmarking Pipeline

The `schema_viewer` serves multiple roles:

- **Schema documentation**: makes the full analytical decision space explicit and navigable  
- **Annotation validation**: enables rapid inspection of extracted metadata  
- **Human-in-the-loop review**: supports correction and confirmation of LLM outputs  
- **Reporting aid**: standardizes how preprocessing pipelines are summarized  

This tool is especially useful for:

- Onboarding new collaborators  
- Reviewing edge cases and mismatches  
- Demonstrating the scope and complexity of the benchmarking schema  

## ▶️ Usage

- Open `schema_viewer.html` in any modern web browser (Chrome/Edge recommended)  
- No server or backend required — runs fully client-side  
- Optional: load JSON annotation files in the **Annotations Explorer** tab  

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

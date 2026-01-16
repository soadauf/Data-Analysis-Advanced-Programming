# 🧬 Shared Biomarkers: COVID-19 & Alzheimer’s Disease
> **An analysis of pathway dysregulations and bidirectional risk.**

![Status](https://img.shields.io/badge/Status-Complete-green)
![Domain](https://img.shields.io/badge/Domain-Bioinformatics-blue)
![Focus](https://img.shields.io/badge/Focus-Gene%20Expression-purple)

---

## 🎥 Project Presentation
**Watch the full explanation of our methodology and results here:**

[![Watch Video](https://img.shields.io/badge/▶️_[Watch_Presentation_Video-Click_Here-red?style=for-the-badge&logo=youtube](https://drive.google.com/file/d/1qCYBjA7FKeZcoFZpCZ40vY-XgD5nqcnu/view?usp=sharing))]

*(Click the button above to view the presentation on Google Drive)*

---

## 📌 Project Overview
This analysis elucidates the shared biomarkers between **COVID-19 (SARS-CoV-2)** and **Alzheimer’s disease (AD)**. By integrating differential gene expression with pathway enrichment analysis, we identify specific molecular mechanisms that indicate a bidirectional risk between the viral infection and neurodegenerative progression.

---

## 🔍 Key Findings: Critical Mechanisms
Our research highlights two distinct mechanisms driving the co-pathogenesis of these conditions:

### 1. Vascular & Adrenergic Stress
* **Target Gene:** `ADRA1D` (Upregulated ⬆️)
* **Pathway:** MAPK Signaling Pathway
* **Mechanism:** The upregulation of `ADRA1D` is highly linked to increased **calcium channel activity**. This dysregulation suggests a pathway where adrenergic stress contributes to vascular instability common in both conditions.

### 2. Inflammatory Dysregulation
* **Target Gene:** `SERPINA3` (Suppressed ⬇️)
* **Pathway:** TNF Signaling Pathway
* **Mechanism:** The suppression of `SERPINA3` correlates with a **hyper-activated TNF signaling pathway**.
* **Outcome:** The loss of this protease inhibitor fuels the "cytokine storm" via specific chemokines:
    * `Ccl2`
    * `Cxcl1`

---

## 📊 Summary of Pathway Dysregulations

| Mechanism | Gene Status | Signaling Pathway | Key Consequence |
| :--- | :---: | :--- | :--- |
| **Adrenergic Stress** | `ADRA1D` (High) | MAPK Signaling | Increased Ca2+ channel activity |
| **Inflammation** | `SERPINA3` (Low) | TNF Signaling | Cytokine storm via `Ccl2`, `Cxcl1` |

---

## 🧠 Conclusion & Therapeutic Implications
These findings provide molecular evidence that SARS-CoV-2 infection increases neurodegenerative risks through specific, identifiable pathways.

The analysis highlights **`ADRA1D`** and **`SERPINA3`** as potential **therapeutic targets** to mitigate post-infectious cognitive decline.

---

## 🛠️ Tools & Methods
* **Analysis:** R Programming Environment
* **Data Source:** NCBI GEO Datasets (GSE188847, GSE104704)
* **Techniques:** Differential Gene Expression (DGE) & Pathway Enrichment Analysis

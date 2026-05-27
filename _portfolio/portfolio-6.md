---
title: "Subfamily Classification and Functional Analysis of CAZy Family GH5"
excerpt: "Bioinformatics workflow for classification and functional analysis of the CAZy GH5 glycoside hydrolase family.<br/><img src='/images/gh5.png'>"
collection: portfolio
---

# Subfamily Classification and Functional Analysis of CAZy Family GH5

**Aug 2025 – Dec 2025**  
Associated with University of Nebraska-Lincoln

Developed a bioinformatics workflow for the classification and functional characterization of the CAZy GH5 glycoside hydrolase family.

---

## GitHub Repository

🔗 [View Project on GitHub](https://github.com/sachinkavindaa/gh5-subfamily-classification)

---

## Technologies

![Python](https://img.shields.io/badge/Python-blue?style=for-the-badge&logo=python)
![Linux](https://img.shields.io/badge/Linux-black?style=for-the-badge&logo=linux)
![HPC](https://img.shields.io/badge/HPC-Cluster-green?style=for-the-badge)

---

## Workflow Overview

```text
Raw Protein Sequences
        ↓
Domain Annotation (HMMER/dbCAN)
        ↓
SSN Construction
        ↓
Cytoscape Visualization
        ↓
Phylogenetic Analysis
```

---

## Example Workflow Log

```bash
$ module load hmmer
$ module load mafft

$ hmmscan --domtblout gh5_domains.out dbCAN-HMMdb proteins.faa

Processing protein sequences...
Domain annotation completed.

$ mafft --auto sequences.fa > aligned.fa
```

---

## Project Highlights

✔ Processed large-scale protein sequence datasets  
✔ Built automated Linux/Bash workflows on HPC  
✔ Constructed sequence similarity networks  
✔ Conducted phylogenetic analysis using MAFFT

---

## Network Visualization

<img src="/images/gh5_network.png" width="700">

---

## Interactive Technical Details

<details>
<summary><strong>View Domain Annotation Details</strong></summary>

Used HMMER and dbCAN to identify conserved CAZy domains within GH5 protein sequences.

</details>

<details>
<summary><strong>View SSN Analysis</strong></summary>

Constructed Sequence Similarity Networks using SSNpipe and visualized relationships in Cytoscape.

</details>

---

## Research Impact

This project improves understanding of functional diversity within the GH5 enzyme family and supports future bioinformatics and enzyme engineering studies.


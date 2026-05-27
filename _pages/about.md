---
permalink: /
title: "Bio"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.hero {
  padding: 30px;
  border-radius: 20px;
  background: linear-gradient(135deg, #eef6ff, #ffffff);
  box-shadow: 0 8px 25px rgba(0,0,0,0.08);
  margin-bottom: 30px;
}

.hero h1 {
  margin-top: 0;
  font-size: 2rem;
}

.badge {
  display: inline-block;
  padding: 7px 13px;
  margin: 5px;
  border-radius: 20px;
  background: #e8f1ff;
  font-size: 0.85rem;
}

.filter-btn {
  padding: 8px 14px;
  margin: 5px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  background: #007acc;
  color: white;
}

.project-card {
  padding: 20px;
  margin: 18px 0;
  border-radius: 16px;
  background: #ffffff;
  box-shadow: 0 5px 18px rgba(0,0,0,0.08);
  transition: 0.25s;
}

.project-card:hover {
  transform: translateY(-5px);
}

.project-card summary {
  font-size: 1.1rem;
  font-weight: bold;
  cursor: pointer;
}

.tech {
  font-size: 0.9rem;
  color: #555;
}
</style>

<div class="hero">
  <h1>Hi, I’m Sachin Chandrasekara</h1>
  <p>
    Graduate student in Animal Science at the University of Nebraska–Lincoln,
    working at the intersection of microbiome science, bioinformatics,
    computational biology, mathematical modeling, and machine learning.
  </p>

  <span class="badge">Bioinformatics</span>
  <span class="badge">Metagenomics</span>
  <span class="badge">Microbiome</span>
  <span class="badge">HPC / SLURM</span>
  <span class="badge">Python</span>
  <span class="badge">R</span>
  <span class="badge">Machine Learning</span>
</div>

## About Me

I am a graduate student in Animal Science at the University of Nebraska–Lincoln with a background in Mathematics and Computer Science. My research combines bioinformatics, computational biology, mathematical modeling, microbiome science, and data-driven approaches to better understand animal health and host–microbe interactions.

My work focuses on shotgun metagenomics, microbial community analysis, microbiome sequencing, and computational analysis of large-scale biological datasets. I am particularly interested in infectious bovine keratoconjunctivitis (IBK), microbial genomics, and genetically engineered microbes in cattle.

## Projects

<button class="filter-btn" onclick="filterProjects('all')">All</button>
<button class="filter-btn" onclick="filterProjects('bioinformatics')">Bioinformatics</button>
<button class="filter-btn" onclick="filterProjects('ml')">Machine Learning</button>
<button class="filter-btn" onclick="filterProjects('math')">Mathematical Modeling</button>

<div class="project-card bioinformatics">
<details open>
<summary>Metagenomic Identification and Variant Analysis of a Viral Genome</summary>

*Jan 2026 – May 2026*

Developed a viral genome analysis pipeline on a High-Performance Computing cluster to identify a mystery virus from Nanopore sequencing data.

Performed metagenomic classification, genome alignment, coverage analysis, and variant detection using Centrifuge, Minimap2, Samtools, and Bcftools.

<p class="tech"><strong>Technologies:</strong> Linux, Bash, HPC, SLURM, Centrifuge, Minimap2, Samtools, Bcftools, Nanopore Sequencing</p>
</details>
</div>

<div class="project-card ml">
<details>
<summary>Dynamic Ride Fare Prediction Using Weather and Demand Data</summary>

*Jan 2026 – Apr 2026*

Designed an end-to-end machine learning pipeline to predict Uber and Lyft fares using ride and weather datasets.

<p class="tech"><strong>Technologies:</strong> Python, Jupyter Notebook, R, Random Forest, Gradient Boosting</p>
</details>
</div>

<div class="project-card bioinformatics">
<details>
<summary>Subfamily Classification and Functional Analysis of CAZy Family GH5</summary>

*Aug 2025 – Dec 2025*

Developed a bioinformatics workflow to classify GH5 proteins into subfamilies and analyze their possible functions using sequence analysis, domain annotation, network analysis, and phylogenetic methods.

<p class="tech"><strong>Technologies:</strong> Python, Bash, Linux, HMMER, dbCAN, SSNpipe, Cytoscape, MAFFT, HPC</p>
</details>
</div>

<div class="project-card math">
<details>
<summary>Mathematical Modeling of Cell Signalling Pathways in Cancer</summary>

*Oct 2022 – Feb 2023*

Developed mathematical models using ordinary differential equations to study cancer-related cell signalling pathways and apoptosis.

<p class="tech"><strong>Technologies:</strong> Java, Python, ODE Modeling, Numerical Methods</p>
</details>
</div>

<div class="project-card math">
<details>
<summary>Numerical Simulations for 1D and 2D Mass Spring Models</summary>

*Oct 2021 – Jan 2022*

Studied vibration behavior using one-dimensional and two-dimensional mass-spring models with numerical simulations.

<p class="tech"><strong>Technologies:</strong> MATLAB, Numerical Simulation, Runge-Kutta Method</p>
</details>
</div>

## International Research Experience

<div class="project-card bioinformatics">
<details>
<summary>EMBL Lautenschläger Summer School – Visualising Life</summary>

*Jul 2022 · Heidelberg, Germany*

Participated in an international summer research program at EMBL focused on biological imaging, microscopy, and computational image analysis.

[EMBL Summer School 2022](https://www.embl.org/news/events/visualising-life-embl-lautenschlager-summer-school-2022/)

<p class="tech"><strong>Topics:</strong> Biological Imaging, Microscopy, Machine Learning, Computational Biology</p>
</details>
</div>

<script>
function filterProjects(category) {
  const cards = document.querySelectorAll('.project-card');

  cards.forEach(card => {
    if (category === 'all') {
      card.style.display = 'block';
    } else if (card.classList.contains(category)) {
      card.style.display = 'block';
    } else {
      card.style.display = 'none';
    }
  });
}
</script>
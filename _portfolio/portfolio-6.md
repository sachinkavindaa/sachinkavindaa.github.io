---
title: "Metagenomic Identification and Variant Analysis of a Viral Genome"
excerpt: "Developed a viral genome analysis pipeline on a High-Performance Computing (HPC) cluster to identify a mystery virus from Nanopore sequencing data.<br/><img src='/images/A.png'>"
collection: portfolio
---

<style>
.project-card {
  padding: 28px;
  border-radius: 18px;
  background: linear-gradient(135deg, #eef6ff, #f8fbff);
  border: 1px solid #dbeafe;
  margin-bottom: 28px;
}

.badge {
  display: inline-block;
  padding: 7px 13px;
  margin: 5px;
  border-radius: 20px;
  background: #e0f2fe;
  color: #075985;
  font-weight: 600;
  font-size: 14px;
}

.github-button {
  display: inline-block;
  margin-top: 15px;
  padding: 12px 18px;
  background: #111827;
  color: white !important;
  border-radius: 10px;
  font-weight: bold;
  text-decoration: none;
}

.section-box {
  padding: 22px;
  margin: 24px 0;
  border-radius: 16px;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  box-shadow: 0 4px 12px rgba(0,0,0,0.06);
}

.workflow-step {
  margin: 14px 0;
  padding: 16px;
  border-left: 5px solid #2563eb;
  border-radius: 12px;
  background: #f8fafc;
}

.workflow-step summary {
  cursor: pointer;
  font-weight: 700;
  color: #1f2937;
}

.workflow-step:hover {
  background: #eff6ff;
  transform: translateX(5px);
  transition: 0.2s;
}

.terminal {
  background: #111827;
  color: #d1fae5;
  padding: 18px;
  border-radius: 12px;
  font-family: monospace;
  overflow-x: auto;
}

.highlight-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 15px;
}

.highlight {
  background: #f0fdf4;
  border: 1px solid #bbf7d0;
  padding: 16px;
  border-radius: 12px;
}
</style>

<div class="project-card">

Developed a viral genome analysis pipeline on a High-Performance Computing cluster to identify a mystery virus from Nanopore sequencing data. The project included metagenomic classification, reference alignment, coverage analysis, and variant detection.

<a class="github-button" href="https://github.com/sachinkavindaa/virus-genome-analysis" target="_blank">
View Project on GitHub
</a>

</div>

<div class="section-box">

## Project Highlights

<div class="highlight-grid">

<div class="highlight">
<strong>Virus Identification</strong>
<p>Identified the mystery virus as Lone Star virus.</p>
</div>

<div class="highlight">
<strong>Genome Analysis</strong>
<p>Analyzed three viral genome segments: L, M, and S.</p>
</div>

<div class="highlight">
<strong>Variant Calling</strong>
<p>Detected genomic variants using Samtools and Bcftools.</p>
</div>

<div class="highlight">
<strong>HPC Workflow</strong>
<p>Built a reproducible Linux, Bash, and SLURM-based pipeline.</p>
</div>

</div>

</div>

<div class="section-box">

## Interactive Workflow

<details class="workflow-step">
<summary>1. Raw Nanopore Sequencing Reads</summary>
<p>Started with sequencing reads from an unknown viral sample.</p>
</details>

<details class="workflow-step">
<summary>2. Metagenomic Classification</summary>
<p>Used Centrifuge to classify reads and identify the likely viral organism.</p>
</details>

<details class="workflow-step">
<summary>3. Reference Genome Selection</summary>
<p>Selected Lone Star virus reference genome segments for alignment.</p>
</details>

<details class="workflow-step">
<summary>4. Read Alignment</summary>
<p>Mapped reads to the viral reference genome using Minimap2.</p>
</details>

<details class="workflow-step">
<summary>5. BAM Processing</summary>
<p>Used Samtools to sort, index, and summarize alignment files.</p>
</details>

<details class="workflow-step">
<summary>6. Variant Calling</summary>
<p>Used Bcftools to identify sequence variants across the viral genome.</p>
</details>

<details class="workflow-step">
<summary>7. Biological Interpretation</summary>
<p>Interpreted variants and genome coverage to understand the identified virus.</p>
</details>

</div>

<div class="section-box">

## Example Pipeline Log

<pre class="terminal">
Input reads → Centrifuge classification
           → Lone Star virus identified
           → Minimap2 reference alignment
           → Samtools BAM processing
           → Bcftools variant calling
           → Genome segment and mutation analysis
</pre>

</div>

<div class="section-box">

## Technologies Used

<span class="badge">Linux</span>
<span class="badge">Bash</span>
<span class="badge">HPC</span>
<span class="badge">SLURM</span>
<span class="badge">Centrifuge</span>
<span class="badge">Minimap2</span>
<span class="badge">Samtools</span>
<span class="badge">Bcftools</span>
<span class="badge">Nanopore Sequencing</span>
<span class="badge">Git/GitHub</span>

</div>

<div class="section-box">

## Recruiter-Friendly Summary

This project shows experience in bioinformatics pipeline development, command-line tools, high-performance computing, viral genome analysis, and reproducible research. It demonstrates the ability to move from raw sequencing data to biological interpretation using real computational genomics tools.

</div>


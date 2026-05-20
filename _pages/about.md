---
permalink: /
title: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a graduate student in Animal Science at the University of Nebraska–Lincoln with a background in Mathematics and Computer Science. My research combines bioinformatics, computational biology, mathematical modeling, microbiome science, and data-driven approaches to better understand animal health and host–microbe interactions.

My work focuses on shotgun metagenomics, microbial community analysis, microbiome sequencing, and computational analysis of large-scale biological datasets. I am particularly interested in infectious bovine keratoconjunctivitis (IBK), microbial genomics, and genetically engineered microbes in cattle.

I have experience developing bioinformatics pipelines, high-performance computing (HPC) workflows, and applying machine learning and mathematical modeling techniques to biological data. In addition to computational research, I also have hands-on wet lab experience in molecular biology and microbiome-related laboratory techniques.

My interdisciplinary background allows me to integrate experimental biology with computational and machine learning approaches for microbiome research and precision animal health.

Projects
======
### Metagenomic Identification and Variant Analysis of a Viral Genome 
*Jan 2026 – May 2026*

Developed a viral genome analysis pipeline on a High-Performance Computing (HPC) cluster to identify a mystery virus from Nanopore sequencing data. Performed metagenomic classification, genome alignment, coverage analysis, and variant detection using Centrifuge, Minimap2, Samtools, and Bcftools.
Used Linux, Bash scripting, SLURM, and Git/GitHub to automate and manage the workflow. Successfully identified Lone Star virus (Bandavirus amblyommae), reconstructed its three-segment genome, and analyzed genomic variants.

Technologies: *Linux, Bash, HPC Cluster, SLURM, Git, GitHub, Centrifuge, Minimap2, Samtools, Bcftools, Nanopore Sequencing.*

### Dynamic Ride Fare Prediction Using Weather and Demand Data
*Jan 2026 – Apr 2026*

Designed and developed an end-to-end machine learning pipeline to predict ride fares for Uber and Lyft using large-scale real-world ride and weather datasets. Processed large datasets through data cleaning, missing value treatment, encoding, and feature engineering. Developed and optimized regression models, including Random Forest and Gradient Boosting, to improve fare prediction accuracy. Evaluated model performance using RMSE and R² metrics, and created visual comparisons to communicate business insights. Demonstrated strong skills in predictive analytics, scalable data processing, and machine learning workflows.

Technologies used: *Python, Jupyter Notebook, R.*

### Subfamily Classification and Functional Analysis of CAZy Family GH5
*Aug 2025 – Dec 2025*

Developed a bioinformatics workflow to study the CAZy GH5 glycoside hydrolase family, an important group of enzymes involved in breaking down carbohydrates. The project focused on classifying GH5 proteins into subfamilies and understanding their possible functions using sequence analysis, domain annotation, network analysis, and phylogenetic methods. Large protein sequence datasets were processed and analyzed using tools such as HMMER, dbCAN, SSNpipe, Cytoscape, and MAFFT. The study also included building Sequence Similarity Networks (SSNs), analyzing conserved protein domains, integrating EC numbers for functional interpretation, and visualizing protein relationships. Linux, Bash scripting, and HCC computing environments were used to automate and manage the workflow efficiently.

Technologies used:  *Python, Bash, Linux, HMMER, dbCAN, SSNpipe, Cytoscape, MAFFT, High-Performance Computing (HPC)*

### Mathematical Modeling of Cell Signalling Pathways in Cancer: Numerical Investigation and Stability Analysis
*Oct 2022 – Feb 2023*

This project focused on understanding how cancer-related cell signalling pathways control apoptosis (programmed cell death) using mathematical modeling. The study investigated the interactions between important proteins such as STAT1, STAT3, Bcl-2, and BAX, which play key roles in cancer cell survival and cell death. A mathematical model based on ordinary differential equations (ODEs) was developed to represent the signalling network, and numerical methods including Euler’s Method and the Runge-Kutta Fourth-Order Method were used to analyze the system. The study examined the stability of different equilibrium points under varying conditions and showed how changes in signalling pathways can affect downstream cellular responses in cancer. This research highlights the importance of mathematical and computational approaches in understanding complex biological systems and cancer signalling mechanisms.

Technologies used; *Java, Python*

### Numerical Simulations for Selected 1D and 2D Mass Spring Models and Applications
*Oct 2021 – Jan 2022*

This project focused on studying vibration behavior using one-dimensional (1D) and two-dimensional (2D) mass-spring models. Vibrations are important in many real-world applications, including sound, vision, mechanical systems, and engineering technologies. The study aimed to improve the physical accuracy and visual representation of existing mass-spring models through numerical simulations. The motion of connected oscillator systems was modeled using the Lagrangian approach, and numerical methods were applied to analyze the system behavior. MATLAB was used to simulate the models and compare computational methods, showing that the Runge-Kutta Fourth-Order Method provided more efficient and accurate numerical results for solving vibration-related problems.

Technologies Used: Matlab

### Low-grade glioma tumour segmentation and area calculation using convolutional neural networks
*Feb 2021 – May 2021*

This project focused on detecting and segmenting low-grade glioma brain tumors from MRI brain images using deep learning techniques. The study used a dataset from The Cancer Imaging Archive containing 3,929 MRI images of lower-grade glioma patients. Convolutional Neural Networks (CNNs) and deep learning models were implemented in Google Colab to automatically identify tumor regions and calculate tumor areas. The dataset was divided into training, testing, and validation sets in a 70:15:15 ratio. Model performance was evaluated using Intersection over Union (IoU) and Sørensen Dice Coefficient scores. The study tested multiple training epochs and achieved the best performance at 50 epochs, reaching 99.92% training accuracy and 92.64% validation accuracy. The developed approach demonstrated that deep learning can effectively automate brain tumor segmentation and area calculation from MRI images with high accuracy.

Technologies Used: *Python*

### Numerical investigation of a mathematical model for CD4+ and Cytokines interaction on tumour growth
*Apr 2021 – May 2021*

This project focused on studying how CD4+ immune cells and cytokines interact with tumor growth using mathematical modeling and numerical analysis. The research explored how cancer immunotherapy can help the immune system recognize and destroy tumor cells. Mathematical models were developed to analyze the interactions between tumors, CD4+ cells, and cytokines, and to study the effects of different treatment doses on tumor regression. The results showed that treatment dosage plays an important role in controlling tumor growth, and that higher cytokine doses could potentially eliminate tumor cells completely. Numerical simulations and analysis were carried out using Python and MATLAB.

Technologies Used: *Python, Matlab*

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

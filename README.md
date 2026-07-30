# 👋 Hi, I'm Shreya

## 🧬 Bioinformatics Researcher | Cancer Genomics

I'm an MS Bioinformatics candidate at Boston University, currently working as a Bioinformatics Intern in the Van Galen Lab at Brigham and Women's Hospital / Harvard Medical School, where I work on single-cell multiomics in AML — integrating gene expression, chromatin accessibility, and mitochondrial variant data to trace clonal evolution across treatment timepoints.

### 🔬 What I Do

- **Single-Cell Multiomics**: Building pipelines that integrate scRNA-seq, scATAC-seq, and mitochondrial variant data to study clonal structure in AML.
- **Mitochondrial Variant Calling & Clonal Tracking**: Running and benchmarking mgatk, ReDeeM, Numbat, and Mutect2; performing barcode concordance analysis across modalities to validate variant calls.
- **Pipeline & HPC Engineering**: Deploying and debugging bioinformatics tools on SLURM clusters, resolving conda/R dependency conflicts, and patching source-level bugs (e.g., a soft-masking issue in mgatk).
- **Reproducible Workflows**: Building Nextflow-based pipelines for RNA-seq differential expression and ChIP-seq analysis, from raw reads to pathway-level interpretation.

### 🛠️ Tech Stack

![My Skills](https://skillicons.dev/icons?i=py,r,java,bash,git,github,docker,linux,aws,tensorflow,sklearn,anaconda)

- **Languages:** Python · R · Java · Bash/Shell
- **Single-Cell & Genomics:** Seurat · Signac · mgatk · redeemR · scRNA-seq · scATAC-seq · STAR · Bowtie2 · BWA · VERSE · DESeq2 · GATK · HOMER · deepTools · SAMtools · bedtools · FastQC/MultiQC · Trimmomatic · BLAST · Bioconductor
- **Workflow & Infrastructure:** Nextflow · Snakemake · SLURM/HPC · Docker · Conda · Git · AWS
- **ML & Data Science:** Scikit-learn · TensorFlow/Keras · XGBoost · LightGBM · Optuna · NumPy · Pandas · RDKit
- **Visualization & Stats:** Matplotlib · Seaborn · ggplot2 · Plotly · scipy · statsmodels
- **Computational Neuroimaging:** FSL/Nilearn · ANTs · FreeSurfer

### 📌 Featured Projects

- **[AML Clonal Evolution Dashboard](#)** — Interactive dashboard visualizing clonal dynamics from the van Galen et al. 2019 *Cell* AML atlas (GSE116256). *In development.*
- **RNA-seq DEG Pipeline** — Differential expression analysis in pancreatic beta-derived iPSCs (6 samples, ~50M reads/sample); identified 1,227 significant DEGs (padj < 0.05) with PI3K-Akt/p53 pathway enrichment.
- **ChIP-seq Pipeline** — RUNX1 binding site analysis in breast cancer cells (GSE75070), integrated with RNA-seq DEG data via a Nextflow/HOMER workflow; surfaced an hg19→hg38 build mismatch as a key reproducibility finding.

### 🤝 Let's Connect!

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shreyadas-maple/) [![Email](https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:dshreya@bu.edu)

### 💡 A Bit More About Me

- Background spans neuroscience, cell & molecular biology, and immunology (University of Toronto) — I like bridging computational genomics with adjacent fields like neuroimmunology.
- Prior experience applying ensemble and deep learning models to Alzheimer's neuroimaging data.
- Always looking for the cleanest way to turn a messy multi-modal dataset into a clear biological story.

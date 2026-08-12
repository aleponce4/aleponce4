# Alex Ponce-Flores

Bioinformatics Analyst and scientific software engineer. I build reproducible genomics pipelines, viral variant-analysis workflows, HPC orchestration layers, and instrument software.

Researcher I, Bioinformatics at the UTHSC Regional Biocontainment Laboratory (BSL-3). M.S. Bioinformatics, Brandeis University (2024); B.S. Biology, University of Memphis (2021).

## Technical focus

- **Viral genomics and bioinformatics** — Nextflow DSL2 and nf-core workflows, intra-host variant calling (LoFreq, iVar), quasispecies haplotype reconstruction, evolutionary selection analysis (SNPGenie), bulk RNA-seq (DESeq2).
- **HPC and SLURM orchestration** — job array management, containerization (Singularity/Apptainer, Docker), automated input validation, execution monitoring.
- **Scientific software and instrumentation** — Python scientific software, signal processing, spectral acquisition, hardware integration, interactive R/Shiny analytics.

## Featured repositories

**[viral-intrahost-variant-workflow](https://github.com/aleponce4/viral-intrahost-variant-workflow)** — Containerized Nextflow DSL2 pipeline for viral intra-host variant calling (iSNV), quasispecies haplotype reconstruction, and evolutionary selection analysis. Tested on synthetic fixtures with an end-to-end Nextflow test suite.

**[libs-spectroscopy-workbench](https://github.com/aleponce4/libs-spectroscopy-workbench)** — Python workbench for LIBS spectral processing: baseline correction, elemental line identification against a NIST-derived line database, and simulated acquisition.

**[tiling-amplicon-primer-design](https://github.com/aleponce4/tiling-amplicon-primer-design)** — Python package for designing tiled amplicon primer schemes for NGS of small viral genomes, with automated window planning, primer QC, and pooling assignment.

**[preclinical-study-analysis-shiny](https://github.com/aleponce4/preclinical-study-analysis-shiny)** — Modular R/Shiny application for longitudinal animal study data: weight trajectory tracking, Kaplan-Meier survival analysis, and report export.

## Supporting repositories

**[lab-bioinfo-templates](https://github.com/aleponce4/lab-bioinfo-templates)** — Reusable virology and genomics analysis templates in R, Python, and Quarto, running on synthetic example data. Rendered gallery: **[aleponce4.github.io/lab-bioinfo-templates](https://aleponce4.github.io/lab-bioinfo-templates/)**

**[akodon-genome-assembly-workflow](https://github.com/aleponce4/akodon-genome-assembly-workflow)** — SLURM pipeline for *Akodon* genome assembly (10x Genomics Supernova) and BRAKER-based gene prediction on HPC.

**[rnaseq-nfcore-wrapper-alphavirus](https://github.com/aleponce4/rnaseq-nfcore-wrapper-alphavirus)** — SLURM execution wrapper and preflight validation layer for [nf-core/rnaseq](https://github.com/nf-core/rnaseq) in viral transcriptomics studies.

## Contact

- Email: [aleponce92@gmail.com](mailto:aleponce92@gmail.com)
- LinkedIn: [alejandroponceflores](https://linkedin.com/in/alejandroponceflores/)

Open to bioinformatics and scientific software engineering roles.

## Licensing

Public repositories here are released under MIT, except `libs-spectroscopy-workbench`, which is GPLv3. Commercial instrument software, trained model weights, vendor hardware SDKs, and client datasets are maintained privately and are not part of this profile.

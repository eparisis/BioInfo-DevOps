# Nextflow

Nextflow is a industry standard workflow management system that enables scalable and reproducible scientific workflows using software containers. 

It enables you to write workflows in a way that is easy to understand, easy to maintain and easy to deploy locally, in the cloud or in a HPC cluster.

## Nextflow resources

<div align="center">

[![Training](https://img.shields.io/badge/Nextflow_Training-%23008B8B.svg?style=for-the-badge&logo=nextflow&logoColor=white)](https://training.nextflow.io/latest/)
[![Documentation](https://img.shields.io/badge/Nextflow_Docs-%23008B8B.svg?style=for-the-badge&logo=nextflow&logoColor=white)](https://www.nextflow.io/docs/latest/index.html)
[![Patterns](https://img.shields.io/badge/Nextflow_Patterns-%23008B8B.svg?style=for-the-badge&logo=nextflow&logoColor=white)](https://nextflow-io.github.io/patterns/)
[![Tutorials](https://img.shields.io/badge/Nextflow_Tutorial-%23008B8B.svg?style=for-the-badge&logo=nextflow&logoColor=white)](https://carpentries-incubator.github.io/workflows-nextflow/index.html)
</div>

## nf-core

`nf-core` is a community-led framework for building and sharing bioinformatics pipelines.

<div align="center">

[![Pipelines](https://img.shields.io/badge/Pipelines-nf--core-%2347A248.svg?style=for-the-badge&logoColor=white)](https://nf-co.re/pipelines)
[![Tutorials](https://img.shields.io/badge/Tutorials-nf--core-%2347A248.svg?style=for-the-badge&logoColor=white)](https://nf-co.re/docs/tutorials/)
[![Documentation](https://img.shields.io/badge/Documentation-nf--core-%2347A248.svg?style=for-the-badge&logoColor=white)](https://nf-co.re/docs)
</div>

`nf-core` provides a whole framework for building pipelines, including:

- A set of best practices for building pipelines
- A set of modules and subworkflows for building pipelines
- A set of community-maintained pipelines
- A toolkit for building pipelines `nf-core/tools` which includes:
  - Templates for building pipelines
  - Test Datasets for testing pipelines
  - Code linting and formatting
  - Helper functions for input and output validation
  - Code test guidelines for modules, subworkflows and pipelines.
  - CI tooling through GitHub Actions


## Example pipelines

Here we list some example pipelines that you can look into to get an idea of how to build your own pipeline.

### Simple one-script pipelines

| Pipeline | Description | Link |
|:------:|:-------------:|:-------------:|
| nf-villumina | A simple pipeline for analyzing viral Illumina sequence data. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/peterk87/nf-villumina) |
| microPIPE | Bacterial genome construction using ONT and Illumina sequencing. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BeatsonLab-MicrobialGenomics/micropipe) |

### Advanced Pipelines

**_nf-core pipelines_** 

| Pipeline | Description | Link |
|:------:|:-------------:|:-------------:|
| nf-core/viralrecon | A pipeline for analyzing viral sequence data. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nf-core/viralrecon) |

**_epi2me-labs pipelines_** 

[EPI2ME](https://epi2me.nanoporetech.com/) is the official provider of pipelines for [Oxford Nanopore Technologies](https://nanoporetech.com/) (ONT). The pipelines are open-source and build with Nextflow.

| Pipeline | Description | Link |
|:------:|:-------------:|:-------------:|
| epi2me-labs/wf-metagenomics | A pipeline for analyzing metagenomic sequence data. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/epi2me-labs/wf-metagenomics/) |
| epi2me-labs/wf-bacterial-genomes | A pipeline for Bacterial assembly and annotation workflow. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/epi2me-labs/wf-bacterial-genomes/) |

**_advanced nf-core style pipelines_**

| Pipeline | Description | Link |
|:------:|:-------------:|:-------------:|
| bactopia | A pipeline for complete analysis of bacterial genomes. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bactopia/bactopia) |
|ARETE | Antimicrobial Resistance: Emergence, Transmission, and Ecology. A pipeline for profiling the genomic repertoire and evolutionary dynamics of microorganisms with a particular focus on pathogens. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/beiko-lab/arete) |

**_Overkill Pipelines_**



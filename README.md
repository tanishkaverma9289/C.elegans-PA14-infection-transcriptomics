# *C. elegans*–PA14 Infection Transcriptomics

### Bioinformatics analysis of host transcriptional responses to bacterial infection

## Overview

This project investigates changes in gene expression in *Caenorhabditis elegans* following exposure to *Pseudomonas aeruginosa* PA14, an opportunistic bacterial pathogen. Publicly available data from the NCBI Gene Expression Omnibus (GEO) are used to explore host responses to infection and identify potentially relevant biological processes and molecular interactions.

## Research Question

How does exposure to *P. aeruginosa* PA14 alter gene expression in *C. elegans*, and which biological processes and molecular interaction networks are associated with the response?

## Dataset

- **GEO accession:** [GSE121091](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE121091)
- **Host organism:** *Caenorhabditis elegans*
- **Infection condition:** *Pseudomonas aeruginosa* PA14
- **Control condition:** *Escherichia coli* OP50
- **Exposure duration:** 24 hours
- **Data type:** RNA sequencing (RNA-seq)

The primary comparison focuses on wild-type N2 worms exposed to PA14 versus the OP50 control. Three biological replicates per condition are planned for the main comparison.

## Planned Workflow

1. **Dataset preparation:** Organize expression data, sample metadata, and experimental conditions.
2. **Quality assessment:** Inspect data structure, sample consistency, and expression patterns.
3. **Differential expression analysis:** Identify genes associated with differences between PA14-exposed and control samples using a method appropriate for the available data.
4. **Functional enrichment:** Investigate biological processes and pathways associated with candidate genes.
5. **STRING network analysis:** Explore protein–protein associations among selected genes or proteins.
6. **Biological interpretation:** Relate findings to published research on host–pathogen interactions.

## Tools and Resources

- NCBI GEO
- STRING database
- Gene Ontology and pathway resources
- Data visualization and statistical analysis tools

## Project Status

**Completed**: completed the computational analysis of publicly available *C. elegans* data associated with *Pseudomonas aeruginosa* PA14 infection.

The project includes GEO dataset exploration, compiled data organization, and STRING interaction-network analysis to investigate host–pathogen responses.

The findings are based on computational analysis of public data and should be interpreted in the context of the original study and relevant scientific literature.

## Data Sources and Acknowledgment

This project uses publicly available data from the [NCBI Gene Expression Omnibus (GEO), accession GSE121091](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE121091), alongside protein association information obtained from the [STRING database](https://string-db.org/).

Credit for the original experimental data belongs to the original study authors. This repository documents an independent computational analysis and does not represent an original wet-lab experiment.

## Repository Contents

### Compiled Gene Data
- [Gene-comparison dataset](data/C.elegans-PA14-infection-transcriptomics.csv)
- [Data documentation](data/README.md)

### STRING Network Analysis
- [Network visualization](string-network/bitmap-C.elegans.png)
- [Protein interaction table](string-network/Tabular%20Output-C.elegans.tsv)
- [Protein annotations](string-network/Protein%20annotations-C.elegans.tsv)
- [Functional annotations](string-network/Functional%20annotations-C.elegans.tsv)
- [Protein node-degree table](string-network/string%20node%20degrees-C.elegans.tsv)
- [STRING analysis documentation](string-network/README.md)

## Reproducibility and Interpretation

The repository provides compiled gene data, STRING network exports, and associated annotations. For reproducibility, analytical methods, data-processing steps, filtering criteria, and relevant STRING settings should be documented alongside the results.

Gene-level findings and network associations should be interpreted in the context of the available data and published literature. STRING associations alone do not establish direct physical interactions or prove that a gene responds to infection.

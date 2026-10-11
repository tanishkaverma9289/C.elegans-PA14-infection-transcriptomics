# Data and Dataset Documentation

## GEO Dataset

- **Accession:** [GSE121091](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE121091)
- **Source:** NCBI Gene Expression Omnibus (GEO)
- **Organism:** *Caenorhabditis elegans*
- **Control condition:** *Escherichia coli* OP50
- **Treatment condition:** *Pseudomonas aeruginosa* PA14
- **Exposure duration:** 24 hours
- **Biological replicates:** 3 per condition for the wild-type PA14-versus-OP50 comparison

## Dataset Description

GSE121091 contains gene-expression data from *C. elegans* exposed to *P. aeruginosa* PA14 and control conditions involving *E. coli* OP50. This project focuses on the wild-type PA14-versus-OP50 comparison to investigate gene-expression patterns associated with bacterial exposure.

## Data Files

## Data Files

- [C.elegans-PA14-infection-transcriptomics.csv](C.elegans-PA14-infection-transcriptomics.csv) — compiled gene-expression dataset used in the project.
- [string-network](../string-network) — contains the STRING network visualization, protein-association data, protein and functional annotations, and node-degree table.
- [RESULTS.md](../RESULTS.md) — detailed findings, network interpretation, and biological insights.
- [Main repository README](../README.md) — project overview and repository structure.

## Data Handling

The project uses publicly available data from NCBI GEO. The compiled dataset and associated network files are organized within this repository to support transparent interpretation of the results.

Gene-expression findings should be interpreted in the context of the original dataset, the processing methods used, and the limitations of the available statistical and functional evidence.

## Source

NCBI Gene Expression Omnibus: [GSE121091 — Quantitative Analysis of Worms after *P. aeruginosa* Infection](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE121091)

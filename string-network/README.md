# STRING Network Analysis

## Overview

This directory contains protein-association network data generated using the [STRING Database](https://string-db.org/) for the *Caenorhabditis elegans* PA14 infection transcriptomics project.

## Network Analysis

The network was used to explore functional associations among proteins associated with the project’s gene set. The accompanying files include the network visualization, interaction table, protein annotations, functional annotations, and node-degree data.

The network highlights connected protein groups and candidate network hubs for further investigation. These associations provide functional context for interpreting the gene-expression results but do not necessarily represent direct physical interactions or establish causal relationships.

## Files

* bitmap-C.elegans.png: STRING protein-association network visualization.
* Tabular Output-C.elegans.tsv: tabular network data, including protein associations and evidence scores.
* Protein annotations-C.elegans.tsv: protein annotation information.
* Functional annotations-C.elegans.tsv: functional annotations associated with the analyzed proteins.
* string node degrees-C.elegans.tsv: node-degree values showing the number of connections for each network node.

## Data Source

[STRING Database](https://string-db.org/)

STRING integrates evidence from multiple sources to predict and describe functional associations between proteins. Network edges may represent direct interactions or broader functional relationships, depending on the underlying evidence.

For interpretation, consult the accompanying tables and annotations, and consider the evidence scores and limitations of the STRING network.

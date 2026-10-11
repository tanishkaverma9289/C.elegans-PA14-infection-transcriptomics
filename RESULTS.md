# Results & Biological Insights

## Chemosensory and Neuroendocrine Response

The differential gene-expression results highlight changes in sensory-associated and transmembrane signaling genes following *Pseudomonas aeruginosa* PA14 exposure. These patterns are consistent with a potential role for sensory perception and signaling in the *Caenorhabditis elegans* response to bacterial challenge.

- **Serpentine receptor genes:** *srw-115* (reported log₂FC: 5.73) and *srab-24* (reported log₂FC: 4.17) showed strong upregulation. The STRING network also places *srw-115* within a sensory-associated module containing *srw-22* and *srh-148*. These findings identify candidate genes for investigating sensory responses during infection. However, the expression results alone cannot establish whether these receptors directly detect PA14-derived molecules or initiate specific neuroendocrine pathways.
- **Transmembrane signaling-associated genes:** *olrn-1* (reported log₂FC: 4.48) and *irld-20* (reported log₂FC: 4.31) were also upregulated. Their expression patterns suggest possible changes in membrane-associated signaling. A connection to insulin-like signaling, including the DAF-2/DAF-16 pathway, remains a hypothesis that would require additional functional or pathway-enrichment evidence.

## Metabolic Reprogramming and Oxidative Stress

The expression and network results also point to candidate genes involved in metabolism and cellular stress management.

- **Candidate metabolic gene *B0395.3*:** With a reported log₂FC of 5.55, *B0395.3* was among the most strongly upregulated genes in the dataset. Its annotated carnitine acetyltransferase domain suggests a possible role in acyl-group metabolism. This makes it a candidate for further investigation into metabolic changes during infection, although the expression result alone does not demonstrate increased fatty-acid β-oxidation or mobilization of energy reserves.
- **Association with antioxidant defense:** The STRING network includes an association between *B0395.3* and *ctl-2*, which encodes catalase-2 and is associated with peroxide detoxification. This network relationship raises the possibility of a connection between metabolic processes and oxidative-stress responses. It does not, by itself, establish a direct physical interaction or demonstrate that these genes jointly neutralize PA14-derived reactive oxygen species.

Together, these findings provide candidate links between metabolic regulation and cellular stress responses. Confirming these links would require additional analyses, such as pathway enrichment, examination of relevant gene annotations, and validation of the underlying interaction evidence.

## Mitochondrial Stress and Protein Homeostasis

The STRING protein-association network highlights proteins associated with chaperone activity and ubiquitin-mediated protein regulation. These features suggest possible involvement of protein homeostasis in the host response to PA14 exposure.

- **The *hsp-75* network hub:** *hsp-75* had the highest node degree in the analyzed network, with eight connections. It encodes a mitochondrial HSP90-family chaperone related to mammalian TRAP1. Its network position makes it a candidate for investigating mitochondrial protein maintenance during infection. However, high node degree does not establish that *hsp-75* is the principal regulator of the response, and the network alone cannot confirm activation of the mitochondrial unfolded protein response (UPRᵐᵗ).
- **Ubiquitin-associated proteins:** *ddb-1* and *skr-8* had node degrees of six each and appeared among the more connected proteins in the network. Their annotations associate them with components of ubiquitin-ligase machinery, which participates in the regulation and turnover of proteins. These results identify a potential protein-quality-control module for further study. The current network does not establish that this module specifically targets PA14 toxins or that its activity increases during infection.

The prominence of these proteins in the network suggests that chaperone-associated functions and protein turnover are worthwhile areas for further investigation. Establishing their roles in infection would require expression-level validation, functional studies, or additional pathway-specific evidence.

## Integrated Interpretation

Taken together, the results identify three candidate biological themes in the response of *C. elegans* to PA14 exposure:

1. **Sensory and signaling responses**, represented by upregulated receptor-associated genes such as *srw-115*, *srab-24*, *olrn-1*, and *irld-20*.
2. **Metabolic and oxidative-stress processes**, highlighted by *B0395.3* and its reported STRING association with *ctl-2*.
3. **Protein homeostasis**, reflected in the network positions of *hsp-75*, *ddb-1*, and *skr-8*.

A working hypothesis is that PA14 exposure is associated with changes in sensory signaling, metabolism, oxidative-stress management, and protein maintenance. These processes may contribute to the host response, but their causal relationships have not been established by the current analyses.

The transcriptomic results and STRING network provide complementary evidence: gene-expression measurements describe changes in transcript abundance, whereas STRING associations provide functional context for relationships among proteins. Integrating these evidence types helps prioritize candidate genes and processes for further investigation without treating network connectivity as proof of biological mechanism.

## Limitations

- **Differential-expression statistics:** Reported log₂ fold changes describe the magnitude and direction of expression differences. Statistical significance should be interpreted alongside the underlying statistical method, sample size, and multiple-testing correction. A nominal *p* value below 0.05 is not sufficient by itself to establish robust differential expression across a genome-wide analysis.
- **Functional interpretation:** Gene annotations suggest possible biological roles but do not establish the function of a gene under the specific experimental conditions.
- **STRING evidence:** Protein-association edges may represent evidence from different sources, including functional associations, co-expression, experiments, and curated databases. They should not automatically be interpreted as direct physical interactions.
- **Network centrality:** Node degree measures the number of connections in the analyzed network. It does not independently establish regulatory importance, causal influence, or a gene's biological activity during infection.
- **Mechanistic hypotheses:** Proposed links involving PA14-derived toxins, DAF-2/DAF-16 signaling, fatty-acid oxidation, and the mitochondrial unfolded protein response require independent evidence before they can be considered demonstrated mechanisms.

## Conclusion

This analysis identifies sensory-associated genes, a candidate metabolic gene, and protein-homeostasis-associated network components as potential targets for studying the *C. elegans* response to PA14. The combination of gene-expression patterns and STRING network topology provides a basis for prioritizing candidates, including *srw-115*, *B0395.3*, *ctl-2*, *hsp-75*, *ddb-1*, and *skr-8*.

Further validation and pathway-level analysis are needed to determine which of these candidates contribute directly to host defense and how their functions are connected during infection.

## References

1. NCBI Gene Expression Omnibus. **GSE121091: Quantitative Analysis of Worms after *P. aeruginosa* Infection.** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE121091
2. Szklarczyk D, et al. The STRING database in 2023: protein–protein association networks and functional enrichment analyses for any sequenced genome of interest. *Nucleic Acids Research*. 2023;51(D1):D638–D646. https://doi.org/10.1093/nar/gkac1000

# Results

## 1. Transcriptome Profiling and Differential Gene Expression
Analysis of RNA-seq expression data from *Caenorhabditis elegans* exposed to *Pseudomonas aeruginosa* PA14 compared to uninfected controls identified substantial transcriptional reprogramming. Filtering based on statistical significance ($p < 0.05$) and magnitude of change revealed a robust host immune and stress response. 

* **Upregulated Pathways:** Genes exhibiting the highest positive log2 fold changes were predominantly associated with pathogen defense, innate immunity, and cellular detoxification.
* **Downregulated Pathways:** Suppressed transcripts frequently mapped to metabolic housekeeping and non-essential developmental functions, indicating resource reallocation toward host defense mechanisms.

## 2. Protein-Protein Interaction (PPI) Network Topology
To evaluate the functional connectivity among the **80 identified proteins**, network mapping was performed using the STRING database. 

* **Global Connectivity:** The resulting network demonstrated scale-free properties characterized by tightly interacting functional clusters alongside independent singleton nodes representing specialized or uncharacterized responses.
* **Key Centrality Hubs (Top Node Degrees):**
  * **`hsp-75` (Degree = 8):** Identified as the central regulatory hub of the network. As a member of the heat shock protein family, its high connectivity underscores the critical role of protein-folding homeostasis and cellular stress mitigation during pathogen challenge.
  * **`D1081.3` (Degree = 7) & `ddb-1` (Degree = 6):** Act as primary bridging nodes linking stress-response machinery and regulatory complexes.
  * **`skr-8` (Degree = 6):** Implicated in SCF ubiquitin ligase complexes, highlighting targeted protein turnover and degradation pathways during infection.

## 3. Functional Modules and Biological Insights
* **Cuticle and Extracellular Matrix Remodeling:** Strong interaction scores and co-occurrence were observed among structural and collagen-associated genes (e.g., **`col-117`** and **`col-167`**, combined score $>0.64$). This reflects active physical barrier reinforcement against bacterial colonization.
* **Pathogen Sensing and Behavioral Avoidance:** A distinct, tightly co-expressed cluster comprising serpentine and chemoreceptor families (**`srw-115`**, **`srw-22`**, **`srh-148`**) illustrates the sensory mechanisms employed by *C. elegans* to detect bacterial metabolites and coordinate innate immune or avoidance behaviors.
* **Protein Quality Control:** Coordinated interactions among **`otub-1`**, **`T24C2.2`**, **`ddb-1`**, and **`skr-8`** point to an active proteolytic response managing pathogen-induced cellular damage.

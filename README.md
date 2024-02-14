# A unified nomenclature for RSV-lineages

This repository contains the results described in the article [**"The unified proposal for classification of human respiratory syncytial virus below the subgroup level"**](https://www.medrxiv.org/content/10.1101/2024.02.13.24302237v1) by Goya et al first posted on medRxiv in February 2024.

### Abstract
*A globally implemented unified classification for human respiratory syncytial virus (HRSV) below the subgroup level remains elusive. Here, we formulate the global consensus of HRSV classification based on the challenges and limitations of our previous proposals and the future of genomic surveillance. From a high-quality dataset of 1,480 HRSV-A and 1,385 HRSV-B genomes submitted to NCBI and GISAID up to March 2023, we categorized HRSV-A/B sequences into lineages based on phylogenetic clades and amino acid markers. We defined 24 lineages within HRSV-A and 16 within HRSV-B, providing guidelines for prospective lineages definition. Our classification demonstrated robustness in its applicability to both complete and partial genomes. In addition, it allowed the observation of notable lineage replacements and the identification of lineages exclusively detected since the COVID-19 pandemic. We envision that this unified HRSV classification proposal will strengthen and facilitate HRSV molecular epidemiology on a global scale.*

## Files and directories

**Full-genomes-trees:** contains the maximum likelihood trees reconstrusted with the complete genome dataset used for the classification

**Augur-trees-autolin:** contains the json files used to evaluate different classification thresholds with autolin online tool (https://github.com/jmcbroome/automated-lineage-json.git), that can be visualized in https://auspice.us/

**G-gene-trees:** contains the maximum likelihood trees reconstrusted with the G gene region of the dataset used for the classification

**Tanglegram-trees:** contains the maximum likelihood trees inferred with the 5’ and 3’ ends of the alignments (4,500-nt each) that can be visualized in https://auspice.us/

**Outgroup-rooted-trees:** contains the maximum likelihood trees with the complete genome dataset used for the classification rooted against an outgroup

**Phylodynamic-trees:** contains the phylodynamic trees reconstrusted with treetime using the complete genomes dataset for the classification 

**Classification-excluded-genomes:** contains the maximum likelihood trees to classify genomes excluded from the classification dataset, using the reference alignment

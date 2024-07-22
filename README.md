# Standardized Phylogenetic Classification of Human Respiratory Syncytial Virus below the Subgroup Level

This repository contains the results described in the article [**"Standardized Phylogenetic Classification of Human Respiratory Syncytial Virus below the Subgroup Level"**] (https://wwwnc.cdc.gov/eid/article/30/8/24-0209_article) published on Emerging Infectious Diseases in July 2024.

### Abstract
*A globally implemented unified phylogenetic classification for human respiratory syncytial virus (HRSV) below the subgroup level remains elusive. We formulated global consensus of HRSV classification on the basis of the challenges and limitations of our previous proposals and the future of genomic surveillance. From a high-quality curated dataset of 1,480 HRSV-A and 1,385 HRSV-B genomes submitted to GenBank and GISAID public sequence databases through March 2023, we categorized HRSV-A/B sequences into lineages based on phylogenetic clades and amino acid markers. We defined 24 lineages within HRSV-A and 16 within HRSV-B and provided guidelines for defining prospective lineages. Our classification demonstrated robustness in its applicability to both complete and partial genomes. We envision that this unified HRSV classification proposal will strengthen HRSV molecular epidemiology on a global scale.*

## Files and directories

**Full-genomes-trees:** contains the maximum likelihood trees reconstrusted with the complete genome dataset used for the classification

**Augur-trees-autolin:** contains the json files used to evaluate different classification thresholds with autolin online tool (https://github.com/jmcbroome/automated-lineage-json.git), that can be visualized in https://auspice.us/

**G-gene-trees:** contains the maximum likelihood trees reconstrusted with the G gene region of the dataset used for the classification

**Tanglegram-trees:** contains the maximum likelihood trees inferred with the 5’ and 3’ ends of the alignments (4,500-nt each) that can be visualized in https://auspice.us/

**Outgroup-rooted-trees:** contains the maximum likelihood trees with the complete genome dataset used for the classification rooted against an outgroup

**Phylodynamic-trees:** contains the phylodynamic trees reconstrusted with treetime using the complete genomes dataset for the classification 

**Classification-excluded-genomes:** contains the maximum likelihood trees to classify genomes excluded from the classification dataset, using the reference alignment

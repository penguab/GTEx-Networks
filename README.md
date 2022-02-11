# GTEx-Networks

This directory contains the MEGENA co-expression networks for 50 human tissues from GTEx database. The donor age was adjusted before network construction. 

Author: Peng Xu

Email: peng.xu@mssm.edu

Draft date: Oct 4, 2021

## Description

The co-expression networks for different human tissues were uniformly processed by the MEGENA pipeline. The gene expressions were generated from the normalized RNA-seq data from the GTEx (v8) database. 

Four files were shared for the co-expression network results.

GTEx_network_age_adjusted.tsv: The co-expression networks for all tissues.

GTEx_module_bigtable_age_adjusted.tsv: The module summary information for each co-expression network.

GTEx_module_age_adjusted.tsv: The module genes for each co-expression network.

GTEx_module_REACTOME_age_adjusted.tsv: The enriched REACTOME pathways for the network modules.

## Citation
For detailed method information, please refer to the Senescence manuscript and the MEGENA publication (Song W.-M., Zhang B. (2015) Multiscale Embedded Gene Co-expression Network Analysis. PLoS Comput Biol 11(11): e1004574.)

## News

10/4/2021: First version released.


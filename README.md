# Modelling gene regulation from transcriptomics and chromatin accessibility single-cell data

## Scenario

Cells regulate gene transcription to coordinate cellular activities in response to intracellular and extracellular signals. The study of gene regulation is useful to understand how cellular identity is established, maintained and disrupted in disease. The interplay between chromatin, transcription factors and genes generates complex regulatory circuits that can be represented computationally as gene regulatory networks (GRNs) [1].

In this course, trainees will infer and analyse GRNs from a 10X multiome single-cell dataset of human peripheral blood mononuclear cells (PBMCs). Organised in groups, trainees will first select a cell trajectory of their choice and will infer a multimodal GRN using the celloracle python package [2]. Then, they will identify key TFs using network centrality measures and enrichment analysis with the python package decoupler [3]. Finally, they will perform in-silico gene perturbations to model if those TFs drive the observed cell lineage.

[1] Badia-i-Mompel, P., Wessels, L., Müller-Dott, S. et al. Gene regulatory network inference in the era of single-cell multi-omics. Nat Rev Genet 24, 739–754 (2023).

[2] Kamimoto, K., Stringa, B., Hoffmann, C.M. et al. Dissecting cell identity via network inference and in silico gene perturbation. Nature 614, 742–751 (2023).

[3] Badia-i-Mompel, P. et al. decoupleR: ensemble of computational methods to infer biological activities from omics data. Bioinforma. Adv. 2, vbac016 (2022).

## Dataset
Custom processed 10X multiome (snRNA-seq + snATAC-seq) dataset

## Project aims
- Handling of single-cell datasets
- Learning to infer GRNs from multimodal data
- Understanding how and which TFs determine cell lineage

## Project breakdown into days
- Discussion of the dataset and objectives (45 min)
- Inference of  a multimodal GRN using celloracle (3h)
- Identification of key TFs using decoupler (1h 30 min)
- Perturbation experiments of TFs to change cell fate using celloracle (3h)
- Interpretation of results and preparation of the presentation (3h)

Etiology-Specific Prognostic Modeling in TCGA-LIHC
This project investigates how molecular risk signatures differ between HBV- and HCV-associated hepatocellular carcinoma (TCGA-LIHC).

Original Goal
Model counterfactual survival outcomes under alternate viral etiologies (HBV ↔ HCV).

Current Focus (Phase 1)
Establish transcriptional differences between HBV and HCV tumors using:
Differential expression analysis
False discovery rate correction
Volcano visualization
Gene annotation (Ensembl → symbol mapping)

What Has Been Completed
Filtred TCGA-LIHC transcriptomic data by viral status
Computed log2 fold changes (HBV − HCV)
Applied FDR correction (adj_pval < 0.05)
Gnerated volcano plot visualization
Annotated significant genes using MyGene API
Produced biologically interpretable gene-level comparison table

Next Phase
Pathway enrichment analysis (GSEA)
Integrate survival metadata
Build Cox proportional hazards models
Develop counterfactual survival simulations

Status
Early-stage independent research project. Ongoing.
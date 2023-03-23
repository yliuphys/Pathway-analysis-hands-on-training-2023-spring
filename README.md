# Pathway-analysis-hands-on-training-2023-spring

Please make sure to:

1): create a GenePattern account under https://cloud.genepattern.org/gp/pages/login.jsf. It is free.

2): Download and install free GSEA software on your own computer: http://www.gsea-msigdb.org/gsea/login.jsp. 

Hands on training Steps:
1): Start from file Pathway-analysis-hands-on-training-2023-spring/TCGA_source_data/ tcga_raw_counts.txt. This file can also been downloaded from https://raw.githubusercontent.com/sheffield-bioinformatics-core/rna-seq-in-galaxy/gh-pages/tcga_raw_counts.csv
2): organize the tcga_raw_counts.txt and create the two files under Pathway-analysis-hands-on-training-2023-spring/GenePattern/Input_files/
3): Run GenePattern, the results can be seen at Pathway-analysis-hands-on-training-2023-spring/GenePattern/Results/
4): The file of tcga_raw_counts.Tumor.vs.Normal.normalized_counts.gct from GenePattern results  at Pathway-analysis-hands-on-training-2023-spring/GenePattern/Results/ and the same .cls file used for running GenePattern will be used to run GSEA. The two files can be found at  Pathway-analysis-hands-on-training-2023-spring/GSEA/GSEA_input_files/
5): Run GSEA, the results can be found at Pathway-analysis-hands-on-training-2023-spring/GSEA/GSEA_results/
6): with the file tcga_raw_counts.Tumor.vs.Normal.DESeq2_results_report.xlsx from GenePattern results folder (Pathway-analysis-hands-on-training-2023-spring/GenePattern/Results/), select list of genes to run DAVID and IPA.

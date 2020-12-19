## RcisTarget R Package: Transcription factor binding motif enrichment

RcisTarget identifies transcription factor binding motifs (TFBS) over-represented on a gene list. In a first step, RcisTarget selects DNA motifs that are significantly over-represented in the surroundings of the transcription start site (TSS) of the genes in the gene-set. This is achieved by using a database that contains genome-wide cross-species rankings for each motif. The motifs that are then annotated to TFs and those that have a high Normalized Enrichment Score (NES) are retained. Finally, for each motif and gene-set, RcisTarget predicts the candidate target genes (i.e. genes in the gene-set that are ranked above the leading edge). For additional details about RcisTarget package, please refer [Reference Paper 1](https://pubmed.ncbi.nlm.nih.gov/28991892/), [R Package 1](https://www.bioconductor.org/packages/release/bioc/html/RcisTarget.html), and [R Package 1 vignettes](https://www.bioconductor.org/packages/devel/bioc/vignettes/RcisTarget/inst/doc/RcisTarget.html
)

Brief instructions about application of the RcisTarget package on Generation 3 Modules

1. The RcisTarget R script was applied on all 382 modules Generation 3 modules [Reference Paper 2](https://www.biorxiv.org/content/10.1101/525709v2) using the default settings. 

2. The input data is the .txt files containing Gene Symbol column as mandatory.

3. The output data (refer below table) of the analysis is Motif_Enrichment_AUC_Histogram_Plot.pdf, Best_Enrichment_Motifs_NES_Plot.pdf,  motifEnrichmentTable.csv, motifEnrichmentTable_wGenes.csv, Motif_data_table.html, and Network.html. For more details about the interpretation of the outputs of the RcisTarget package, refer the documentation link provided above.
   
   *  *All the plots and csv files can be opened by a simple left click and viewed, however, Motif_data_table.html and Network.html cannot be viewed by a simple left click. To view the interactive Motif data table and Network for appropriate module, click on the visualize_interactive_motif_data_table and Visualize_Interactive_Network links to view the html contents*
   
   *  *Best_Enrichment_Motifs_NES_Plot.pdf and Network.html outputs are only the subset data (just considering the top 3 best motif enrichments) because of the size of the output files and storage issues. However, it is also possible to include all data as well*
   
4. In summary, outputs were obtained for a total of 235 modules successfully, however, 147 modules failed to run (due to non-matching Gene Symbol identifier between the input file and motif database). Hence, no results will be found here.



**Module Analysis Result Output**




| Module ID | Aggregate   Number | Module   Annotation               | Number of unique   genes | RcisTarget   Result                                                                                   |
|-----------|--------------------|-----------------------------------|--------------------------|-------------------------------------------------------------------------------------------------------|
| M3.1      |         A29        | Cell cycle                        | 106                      | No Result                                                                                             |
| M8.1      |         A29        | TBD                               | 51                       | No Result                                                                                             |
| M8.2      |         A34        | Prostanoids                       | 36                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M8.2%20)    |
| M8.3      |         A28        | Type 1 Interferon                 | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M8.3%20)    |
| M9.1      |         A2         | Cytotoxic lymphocytes             | 28                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M9.1%20)    |
| M9.2      |         A37        | Erythrocytes                      | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M9.2%20)    |
| M10.1     |         A28        | Interferon                        | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M10.1%20)   |
| M10.2     |         A9         | Protein synthesis                 | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M10.2%20)   |
| M10.3     |         A34        | Platelet                          | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M10.3%20)   |
| M10.4     |         A38        | Neutrophil activation             | 13                       | No Result                                                                                             |
| M11.1     |         A1         | Protein synthesis                 | 46                       | No Result                                                                                             |
| M11.2     |         A37        | TBD                               | 39                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M11.2%20)   |
| M11.3     |         A37        | Erythrocytes                      | 24                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M11.3%20)   |
| M11.4     |         A37        | TBD                               | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M11.4%20)   |
| M12.1     |         A1         | Protein modification              | 111                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.1%20)   |
| M12.2     |         A26        | Monocytes                         | 44                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.2%20)   |
| M12.3     |         A1         | Cell cycle                        | 70                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.3%20)   |
| M12.4     |         A2         | Gene transcription                | 62                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.4%20)   |
| M12.5     |         A3         | Protein modification              | 91                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.5%20)   |
| M12.6     |         A1         | T cells                           | 33                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.6%20)   |
| M12.7     |         A1         | Protein synthesis                 | 35                       | No Result                                                                                             |
| M12.8     |         A1         | B cells                           | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.8%20)   |
| M12.9     |         A38        | Protein   phosphorylation         | 42                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.9%20)   |
| M12.10    |         A35        | Inflammation                      | 53                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.10%20)  |
| M12.11    |         A37        | Erythrocytes                      | 24                       | No Result                                                                                             |
| M12.12    |         A25        | Oxidative stress                  | 31                       | No Result                                                                                             |
| M12.13    |         A24        | Oxidative   phosphorylation       | 47                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.13%20)  |
| M12.14    |         A29        | TBD                               | 20                       | No Result                                                                                             |
| M12.15    |         A27        | Cell cycle                        | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.15%20)  |
| M13.1     |         A35        | Inflammation                      | 137                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.1%20)   |
| M13.2     |         A1         | Gene transcription                | 92                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.2%20)   |
| M13.3     |         A35        | TBD                               | 100                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.3%20)   |
| M13.4     |         A2         | Protein synthesis                 | 119                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.4%20)   |
| M13.5     |         A32        | Cell death                        | 134                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.5%20)   |
| M13.6     |         A1         | Gene transcription                | 127                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.6%20)   |
| M13.7     |         A33        | TBD                               | 98                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.7%20)   |
| M13.8     |         A3         | TBD                               | 55                       | No Result                                                                                             |
| M13.9     |         A3         | Gene transcription                | 99                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.9%20)   |
| M13.10    |         A2         | Protein synthesis                 | 91                       | No Result                                                                                             |
| M13.11    |         A26        | TBD                               | 78                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.11%20)  |
| M13.12    |         A35        | Inflammation                      | 55                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.12%20)  |
| M13.13    |         A2         | Gene transcription                | 58                       | No Result                                                                                             |
| M13.14    |         A2         | Proteolysis                       | 72                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.14%20)  |
| M13.15    |         A32        | Gene transcription                | 76                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.15%20)  |
| M13.16    |         A35        | Cytokines/chemokines              | 39                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.16%20)  |
| M13.17    |         A28        | Interferon                        | 31                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.17%20)  |
| M13.18    |         A1         | B cells                           | 88                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.18%20)  |
| M13.19    |         A30        | Protein   phosphorylation         | 63                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.19%20)  |
| M13.20    |         A29        | Cell cycle                        | 47                       | No Result                                                                                             |
| M13.21    |         A2         | Cytotoxic lymphocytes             | 23                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.21%20)  |
| M13.22    |         A35        | Neutrophils                       | 65                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.22%20)  |
| M13.23    |         A3         | TBD                               | 79                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.23%20)  |
| M13.24    |         A24        | TBD                               | 70                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.24%20)  |
| M13.25    |         A32        | Protein   phosphorylation         | 79                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.25%20)  |
| M13.26    |         A37        | Oxidative stress                  | 40                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.26%20)  |
| M13.27    |         A1         | B cells                           | 33                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.27%20)  |
| M13.28    |         A1         | Protein synthesis                 | 29                       | No Result                                                                                             |
| M13.29    |         A2         | Protein modification              | 65                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.29%20)  |
| M13.30    |         A37        | Erythrocytes                      | 29                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.30%20)  |
| M13.31    |         A25        | TBD                               | 25                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.31%20)  |
| M13.32    |         A27        | Cell cycle                        | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M13.32%20)  |
| M14.1     |         A32        | Gene transcription                | 44                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.1%20)   |
| M14.2     |         A2         | Protein synthesis                 | 44                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.2%20)   |
| M14.3     |         A2         | Protein modification              | 39                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.3%20)   |
| M14.4     |         A1         | Gene transcription                | 38                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.4%20)   |
| M14.5     |         A1         | Gene transcription                | 36                       | No Result                                                                                             |
| M14.6     |         A3         | TBD                               | 31                       | No Result                                                                                             |
| M14.7     |         A35        | TBD                               | 31                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.7%20)   |
| M14.8     |         A2         | TBD                               | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.8%20)   |
| M14.9     |         A32        | TBD                               | 27                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.9%20)   |
| M14.10    |         A26        | TBD                               | 28                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.10%20)  |
| M14.11    |         A32        | TBD                               | 28                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.11%20)  |
| M14.12    |         A1         | Cell cycle                        | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.12%20)  |
| M14.13    |         A2         | Oxidative   phosphorylation       | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.13%20)  |
| M14.14    |         A6         | Protein modification              | 27                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.14%20)  |
| M14.15    |         A6         | Protein modification              | 25                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.15%20)  |
| M14.16    |         A24        | TBD                               | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.16%20)  |
| M14.17    |         A2         | Gene transcription                | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.17%20)  |
| M14.18    |         A32        | TBD                               | 25                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.18%20)  |
| M14.19    |         A33        | Inflammation                      | 23                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.19%20)  |
| M14.20    |         A1         | Gene transcription                | 24                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.20%20)  |
| M14.21    |         A26        | TBD                               | 23                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.21%20)  |
| M14.22    |         A32        | TBD                               | 23                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.22%20)  |
| M14.23    |         A1         | Gene transcription                | 24                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.23%20)  |
| M14.24    |         A33        | Inflammation                      | 23                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.24%20)  |
| M14.25    |         A2         | TBD                               | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.25%20)  |
| M14.26    |         A33        | Inflammation                      | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.26%20)  |
| M14.27    |         A25        | Protein synthesis                 | 21                       | No Result                                                                                             |
| M14.28    |         A35        | Neutrophils                       | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.28%20)  |
| M14.29    |         A32        | TBD                               | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.29%20)  |
| M14.30    |         A24        | Oxidative   phosphorylation       | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.30%20)  |
| M14.31    |         A3         | Cell cycle                        | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.31%20)  |
| M14.32    |         A26        | TBD                               | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.32%20)  |
| M14.33    |         A30        | Proteolysis                       | 22                       | No Result                                                                                             |
| M14.34    |         A2         | Gene transcription                | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.34%20)  |
| M14.35    |         A2         | TBD                               | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.35%20)  |
| M14.36    |         A32        | TBD                               | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.36%20)  |
| M14.37    |         A6         | TBD                               | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.37%20)  |
| M14.38    |         A31        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.38%20)  |
| M14.39    |         A34        | Cell cycle                        | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.39%20)  |
| M14.40    |         A6         | Cellular respiration              | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.40%20)  |
| M14.41    |         A24        | TBD                               | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.41%20)  |
| M14.42    |         A1         | T cells                           | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.42%20)  |
| M14.43    |         A3         | TBD                               | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.43%20)  |
| M14.44    |         A2         | Protein synthesis                 | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.44%20)  |
| M14.45    |         A2         | TBD                               | 18                       | No Result                                                                                             |
| M14.46    |         A3         | TBD                               | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.46%20)  |
| M14.47    |         A2         | Protein synthesis                 | 18                       | No Result                                                                                             |
| M14.48    |         A31        | Inflammation                      | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.48%20)  |
| M14.49    |         A1         | Gene transcription                | 18                       | No Result                                                                                             |
| M14.50    |         A33        | Inflammation                      | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.50%20)  |
| M14.51    |         A36        | Oxidative stress                  | 14                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.51%20)  |
| M14.52    |         A3         | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.52%20)  |
| M14.53    |         A37        | Erythrocytes                      | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.53%20)  |
| M14.54    |         A6         | Cell cycle                        | 18                       | No Result                                                                                             |
| M14.55    |         A6         | Gene transcription                | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.55%20)  |
| M14.56    |         A32        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.56%20)  |
| M14.57    |         A24        | Protein modification              | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.57%20)  |
| M14.58    |         A1         | Protein synthesis                 | 17                       | No Result                                                                                             |
| M14.59    |         A34        | TBD                               | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.59%20)  |
| M14.60    |         A29        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.60%20)  |
| M14.61    |         A2         | Protein modification              | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.61%20)  |
| M14.62    |         A32        | TBD                               | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.62%20)  |
| M14.63    |         A24        | Oxidative   phosphorylation       | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.63%20)  |
| M14.64    |         A1         | Cell cycle                        | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.64%20)  |
| M14.65    |         A35        | Monocytes                         | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.65%20)  |
| M14.66    |         A33        | Inflammation                      | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.66%20)  |
| M14.67    |         A32        | Gene transcription                | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.67%20)  |
| M14.68    |         A38        | Protein synthesis                 | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.68%20)  |
| M14.69    |         A1         | Gene transcription                | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.69%20)  |
| M14.70    |         A26        | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.70%20)  |
| M14.71    |         A1         | Gene transcription                | 14                       | No Result                                                                                             |
| M14.72    |         A2         | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.72%20)  |
| M14.73    |         A32        | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.73%20)  |
| M14.74    |         A35        | TBD                               | 14                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.74%20)  |
| M14.75    |         A1         | Protein synthesis                 | 15                       | No Result                                                                                             |
| M14.76    |         A33        | Leukocyte activation              | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.76%20)  |
| M14.77    |         A1         | Gene transcription                | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.77%20)  |
| M14.78    |         A3         | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.78%20)  |
| M14.79    |         A2         | Protein synthesis                 | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.79%20)  |
| M14.80    |         A1         | Protein synthesis                 | 12                       | No Result                                                                                             |
| M14.81    |         A31        | Platelet                          | 14                       | No Result                                                                                             |
| M14.82    |         A33        | Cytokines/chemokines              | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.82%20)  |
| M14.83    |         A25        | TBD                               | 14                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M14.83%20)  |
| M15.1     |         A6         | TBD                               | 79                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.1%20)   |
| M15.2     |         A6         | TBD                               | 60                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.2%20)   |
| M15.3     |         A2         | Gene transcription                | 57                       | No Result                                                                                             |
| M15.4     |         A1         | B cells                           | 54                       | No Result                                                                                             |
| M15.5     |         A5         | Protein modification              | 53                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.5%20)   |
| M15.6     |         A7         | Cell cycle                        | 54                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.6%20)   |
| M15.7     |         A26        | Monocytes                         | 52                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.7%20)   |
| M15.8     |         A2         | Gene transcription                | 51                       | No Result                                                                                             |
| M15.9     |         A6         | T cells                           | 51                       | No Result                                                                                             |
| M15.10    |         A6         | Gene transcription                | 50                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.10%20)  |
| M15.11    |         A6         | TBD                               | 49                       | No Result                                                                                             |
| M15.12    |         A33        | TBD                               | 48                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.12%20)  |
| M15.13    |         A33        | TBD                               | 48                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.13%20)  |
| M15.14    |         A33        | TBD                               | 47                       | No Result                                                                                             |
| M15.15    |         A6         | TBD                               | 46                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.15%20)  |
| M15.16    |         A3         | Antigen presentation              | 45                       | No Result                                                                                             |
| M15.17    |         A22        | TBD                               | 44                       | No Result                                                                                             |
| M15.18    |         A32        | TBD                               | 41                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.18%20)  |
| M15.19    |         A6         | Gene transcription                | 43                       | No Result                                                                                             |
| M15.20    |         A32        | TBD                               | 41                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.20%20)  |
| M15.21    |         A2         | Gene transcription                | 42                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.21%20)  |
| M15.22    |         A6         | TBD                               | 42                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.22%20)  |
| M15.23    |         A2         | Cell death                        | 41                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.23%20)  |
| M15.24    |         A33        | TBD                               | 41                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.24%20)  |
| M15.25    |         A4         | TBD                               | 38                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.25%20)  |
| M15.26    |         A35        | Neutrophils                       | 38                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.26%20)  |
| M15.27    |         A6         | Cell cycle                        | 40                       | No Result                                                                                             |
| M15.28    |         A24        | Oxidative   phosphorylation       | 37                       | No Result                                                                                             |
| M15.29    |         A1         | Cell death                        | 35                       | No Result                                                                                             |
| M15.30    |         A32        | TBD                               | 36                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.30%20)  |
| M15.31    |         A2         | Protein modification              | 35                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.31%20)  |
| M15.32    |         A29        | TBD                               | 36                       | No Result                                                                                             |
| M15.33    |         A1         | T cells                           | 35                       | No Result                                                                                             |
| M15.34    |         A6         | T cells                           | 34                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.34%20)  |
| M15.35    |         A33        | Neutrophils                       | 33                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.35%20)  |
| M15.36    |         A26        | Protein modification              | 34                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.36%20)  |
| M15.37    |         A35        | Inflammation                      | 33                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.37%20)  |
| M15.38    |         A1         | T cells                           | 32                       | No Result                                                                                             |
| M15.39    |         A8         | TBD                               | 32                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.39%20)  |
| M15.40    |         A6         | Gene transcription                | 31                       | No Result                                                                                             |
| M15.41    |         A2         | TBD                               | 31                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.41%20)  |
| M15.42    |         A6         | Gene transcription                | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.42%20)  |
| M15.43    |         A35        | TBD                               | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.43%20)  |
| M15.44    |         A3         | Protein modification              | 28                       | No Result                                                                                             |
| M15.45    |         A6         | Platelet                          | 29                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.45%20)  |
| M15.46    |         A2         | TBD                               | 27                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.46%20)  |
| M15.47    |         A32        | Antigen presentation              | 28                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.47%20)  |
| M15.48    |         A3         | TBD                               | 27                       | No Result                                                                                             |
| M15.49    |         A4         | Cell death                        | 27                       | No Result                                                                                             |
| M15.50    |         A2         | TBD                               | 27                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.50%20)  |
| M15.51    |         A1         | Protein synthesis                 | 26                       | No Result                                                                                             |
| M15.52    |         A3         | TBD                               | 27                       | No Result                                                                                             |
| M15.53    |         A37        | Erythrocytes                      | 25                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.53%20)  |
| M15.54    |         A2         | TBD                               | 26                       | No Result                                                                                             |
| M15.55    |         A25        | Protein   phosphorylation         | 24                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.55%20)  |
| M15.56    |         A30        | Cell adhesion                     | 25                       | No Result                                                                                             |
| M15.57    |         A26        | TBD                               | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.57%20)  |
| M15.58    |         A31        | Monocytes                         | 22                       | No Result                                                                                             |
| M15.59    |         A7         | TBD                               | 24                       | No Result                                                                                             |
| M15.60    |         A1         | TBD                               | 25                       | No Result                                                                                             |
| M15.61    |         A7         | Monocytes                         | 25                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.61%20)  |
| M15.62    |         A32        | TBD                               | 25                       | No Result                                                                                             |
| M15.63    |         A26        | TBD                               | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.63%20)  |
| M15.64    |         A28        | Interferon                        | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.64%20)  |
| M15.65    |         A2         | TBD                               | 23                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.65%20)  |
| M15.66    |         A33        | TBD                               | 23                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.66%20)  |
| M15.67    |         A11        | TBD                               | 22                       | No Result                                                                                             |
| M15.68    |         A29        | TBD                               | 23                       | No Result                                                                                             |
| M15.69    |         A32        | TBD                               | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.69%20)  |
| M15.70    |         A26        | Protein modification              | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.70%20)  |
| M15.71    |         A6         | TBD                               | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.71%20)  |
| M15.72    |         A2         | TBD                               | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.72%20)  |
| M15.73    |         A30        | Cell cycle                        | 22                       | No Result                                                                                             |
| M15.74    |         A37        | Erythrocytes                      | 21                       | No Result                                                                                             |
| M15.75    |         A4         | TBD                               | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.75%20)  |
| M15.76    |         A32        | TBD                               | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.76%20)  |
| M15.77    |         A25        | TBD                               | 21                       | No Result                                                                                             |
| M15.78    |         A35        | TBD                               | 20                       | No Result                                                                                             |
| M15.79    |         A3         | Mitochondrial   Stress/Proteasome | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.79%20)  |
| M15.80    |         A6         | TBD                               | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.80%20)  |
| M15.81    |         A35        | TBD                               | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.81%20)  |
| M15.82    |         A1         | TBD                               | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.82%20)  |
| M15.83    |         A6         | Gene transcription                | 20                       | No Result                                                                                             |
| M15.84    |         A35        | Cytokines/chemokines              | 20                       | No Result                                                                                             |
| M15.85    |         A3         | TBD                               | 20                       | No Result                                                                                             |
| M15.86    |         A28        | Interferon                        | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.86%20)  |
| M15.87    |         A1         | TBD                               | 19                       | No Result                                                                                             |
| M15.88    |         A32        | TBD                               | 19                       | No Result                                                                                             |
| M15.89    |         A24        | TBD                               | 19                       | No Result                                                                                             |
| M15.90    |         A33        | TBD                               | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.90%20)  |
| M15.91    |         A2         | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.91%20)  |
| M15.92    |         A6         | Protein modification              | 18                       | No Result                                                                                             |
| M15.93    |         A1         | TBD                               | 18                       | No Result                                                                                             |
| M15.94    |         A3         | TBD                               | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.94%20)  |
| M15.95    |         A7         | TBD                               | 18                       | No Result                                                                                             |
| M15.96    |         A6         | TBD                               | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.96%20)  |
| M15.97    |         A36        | Cell death                        | 17                       | No Result                                                                                             |
| M15.98    |         A6         | T cells                           | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.98%20)  |
| M15.99    |         A32        | Protein modification              | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.99%20)  |
| M15.100   |         A37        | Erythrocytes                      | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.100%20) |
| M15.101   |         A3         | TBD                               | 18                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.101%20) |
| M15.102   |         A10        | Prostanoids                       | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.102%20) |
| M15.103   |         A24        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.103%20) |
| M15.104   |         A33        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.104%20) |
| M15.105   |         A35        | Inflammation                      | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.105%20) |
| M15.106   |         A32        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.106%20) |
| M15.107   |         A15        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.107%20) |
| M15.108   |         A33        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.108%20) |
| M15.109   |         A35        | Inflammation                      | 17                       | No Result                                                                                             |
| M15.110   |         A27        | Cell cycle                        | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.110%20) |
| M15.111   |         A33        | TBD                               | 17                       | No Result                                                                                             |
| M15.112   |         A26        | TBD                               | 16                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.112%20) |
| M15.113   |         A35        | Inflammation                      | 16                       | No Result                                                                                             |
| M15.114   |         A1         | TBD                               | 16                       | No Result                                                                                             |
| M15.115   |         A2         | TBD                               | 16                       | No Result                                                                                             |
| M15.116   |         A2         | TBD                               | 16                       | No Result                                                                                             |
| M15.117   |         A25        | TBD                               | 16                       | No Result                                                                                             |
| M15.118   |         A36        | Gene transcription                | 14                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.118%20) |
| M15.119   |         A2         | TBD                               | 16                       | No Result                                                                                             |
| M15.120   |         A2         | TBD                               | 16                       | No Result                                                                                             |
| M15.121   |         A31        | TBD                               | 14                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.121%20) |
| M15.122   |         A2         | TBD                               | 15                       | No Result                                                                                             |
| M15.123   |         A24        | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.123%20) |
| M15.124   |         A3         | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.124%20) |
| M15.125   |         A12        | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.125%20) |
| M15.126   |         A17        | Gene transcription                | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M15.126%20) |
| M15.127   |         A28        | Interferon                        | 14                       | No Result                                                                                             |
| M16.1     |         A33        | TBD                               | 169                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.1%20)   |
| M16.2     |         A32        | Protein synthesis                 | 161                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.2%20)   |
| M16.3     |         A6         | T cells                           | 145                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.3%20)   |
| M16.4     |         A6         | TBD                               | 130                      | No Result                                                                                             |
| M16.5     |         A32        | TBD                               | 123                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.5%20)   |
| M16.6     |         A8         | Monocytes                         | 119                      | No Result                                                                                             |
| M16.7     |         A2         | TBD                               | 116                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.7%20)   |
| M16.8     |         A6         | TBD                               | 116                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.8%20)   |
| M16.9     |         A32        | Protein modification              | 109                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.9%20)   |
| M16.10    |         A3         | TBD                               | 105                      | No Result                                                                                             |
| M16.11    |         A4         | Protein synthesis                 | 102                      | No Result                                                                                             |
| M16.12    |         A15        | B cells                           | 100                      | No Result                                                                                             |
| M16.13    |         A5         | Protein modification              | 94                       | No Result                                                                                             |
| M16.14    |         A6         | TBD                               | 89                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.14%20)  |
| M16.15    |         A4         | Cell death                        | 86                       | No Result                                                                                             |
| M16.16    |         A32        | TBD                               | 88                       | No Result                                                                                             |
| M16.17    |         A17        | Gene transcription                | 83                       | No Result                                                                                             |
| M16.18    |         A5         | TBD                               | 82                       | No Result                                                                                             |
| M16.19    |         A18        | TBD                               | 82                       | No Result                                                                                             |
| M16.20    |         A23        | TBD                               | 81                       | No Result                                                                                             |
| M16.21    |         A15        | TBD                               | 80                       | No Result                                                                                             |
| M16.22    |         A33        | TBD                               | 76                       | No Result                                                                                             |
| M16.23    |         A17        | Cell cycle                        | 76                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.23%20)  |
| M16.24    |         A6         | T cells                           | 72                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.24%20)  |
| M16.25    |         A6         | TBD                               | 74                       | No Result                                                                                             |
| M16.26    |         A26        | TBD                               | 72                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.26%20)  |
| M16.27    |         A32        | TBD                               | 69                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.27%20)  |
| M16.28    |         A15        | TBD                               | 67                       | No Result                                                                                             |
| M16.29    |         A8         | TBD                               | 62                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.29%20)  |
| M16.30    |         A8         | Complement                        | 61                       | No Result                                                                                             |
| M16.31    |         A6         | TBD                               | 62                       | No Result                                                                                             |
| M16.32    |         A26        | TBD                               | 59                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.32%20)  |
| M16.33    |         A15        | TBD                               | 59                       | No Result                                                                                             |
| M16.34    |         A36        | Gene transcription                | 56                       | No Result                                                                                             |
| M16.35    |         A15        | TBD                               | 55                       | No Result                                                                                             |
| M16.36    |         A5         | Gene transcription                | 54                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.36%20)  |
| M16.37    |         A33        | TBD                               | 48                       | No Result                                                                                             |
| M16.38    |         A15        | TBD                               | 52                       | No Result                                                                                             |
| M16.39    |         A8         | TBD                               | 52                       | No Result                                                                                             |
| M16.40    |         A7         | Monocytes                         | 51                       | No Result                                                                                             |
| M16.41    |         A2         | TBD                               | 48                       | No Result                                                                                             |
| M16.42    |         A3         | TBD                               | 50                       | No Result                                                                                             |
| M16.43    |         A4         | Gene transcription                | 48                       | No Result                                                                                             |
| M16.44    |         A33        | Protein synthesis                 | 48                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.44%20)  |
| M16.45    |         A3         | TBD                               | 47                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.45%20)  |
| M16.46    |         A26        | TBD                               | 48                       | No Result                                                                                             |
| M16.47    |         A18        | TNF                               | 47                       | No Result                                                                                             |
| M16.48    |         A21        | TBD                               | 47                       | No Result                                                                                             |
| M16.49    |         A25        | Inflammation                      | 45                       | No Result                                                                                             |
| M16.50    |         A4         | Protein modification              | 45                       | No Result                                                                                             |
| M16.51    |         A33        | Protein synthesis                 | 43                       | No Result                                                                                             |
| M16.52    |         A20        | Lymphocyte                        | 43                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.52%20)  |
| M16.53    |         A8         | TBD                               | 42                       | No Result                                                                                             |
| M16.54    |         A6         | TBD                               | 40                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.54%20)  |
| M16.55    |         A15        | TBD                               | 40                       | No Result                                                                                             |
| M16.56    |         A1         | Protein synthesis                 | 38                       | No Result                                                                                             |
| M16.57    |         A5         | B cells                           | 38                       | No Result                                                                                             |
| M16.58    |         A15        | TBD                               | 39                       | No Result                                                                                             |
| M16.59    |         A6         | TBD                               | 38                       | No Result                                                                                             |
| M16.60    |         A27        | Cell cycle                        | 36                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.60%20)  |
| M16.61    |         A25        | TBD                               | 36                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.61%20)  |
| M16.62    |         A33        | TBD                               | 35                       | No Result                                                                                             |
| M16.63    |         A33        | TBD                               | 35                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.63%20)  |
| M16.64    |         A31        | Platelet/Prostaglandin            | 33                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.64%20)  |
| M16.65    |         A5         | TGF-beta                          | 34                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.65%20)  |
| M16.66    |         A15        | TBD                               | 34                       | No Result                                                                                             |
| M16.67    |         A33        | TBD                               | 33                       | No Result                                                                                             |
| M16.68    |         A2         | Protein synthesis                 | 33                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.68%20)  |
| M16.69    |         A4         | Lipid metabolism                  | 32                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.69%20)  |
| M16.70    |         A33        | TBD                               | 29                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.70%20)  |
| M16.71    |         A25        | TBD                               | 31                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.71%20)  |
| M16.72    |         A4         | TBD                               | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.72%20)  |
| M16.73    |         A25        | Protein synthesis                 | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.73%20)  |
| M16.74    |         A25        | TBD                               | 29                       | No Result                                                                                             |
| M16.75    |         A17        | Cell death                        | 30                       | No Result                                                                                             |
| M16.76    |         A33        | TBD                               | 25                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.76%20)  |
| M16.77    |         A4         | Antigen presentation              | 28                       | No Result                                                                                             |
| M16.78    |         A1         | B cells                           | 28                       | No Result                                                                                             |
| M16.79    |         A35        | Protein synthesis                 | 27                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.79%20)  |
| M16.80    |         A33        | Cytokines/chemokines              | 27                       | No Result                                                                                             |
| M16.81    |         A6         | TBD                               | 27                       | No Result                                                                                             |
| M16.82    |         A36        | Gene transcription                | 25                       | No Result                                                                                             |
| M16.83    |         A7         | Cell adhesion                     | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.83%20)  |
| M16.84    |         A5         | Protein   phosphorylation         | 25                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.84%20)  |
| M16.85    |         A32        | TBD                               | 24                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.85%20)  |
| M16.86    |         A29        | Oxidative stress                  | 25                       | No Result                                                                                             |
| M16.87    |         A15        | TBD                               | 23                       | No Result                                                                                             |
| M16.88    |         A36        | Erythrocytes                      | 23                       | No Result                                                                                             |
| M16.89    |         A30        | TBD                               | 23                       | No Result                                                                                             |
| M16.90    |         A14        | TBD                               | 22                       | No Result                                                                                             |
| M16.91    |         A1         | TBD                               | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.91%20)  |
| M16.92    |         A27        | Cell cycle                        | 22                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.92%20)  |
| M16.93    |         A31        | TBD                               | 22                       | No Result                                                                                             |
| M16.94    |         A19        | TBD                               | 21                       | No Result                                                                                             |
| M16.95    |         A5         | B cells                           | 21                       | No Result                                                                                             |
| M16.96    |         A38        | Erythrocytes                      | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.96%20)  |
| M16.97    |         A17        | Cell death                        | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.97%20)  |
| M16.98    |         A35        | TBD                               | 18                       | No Result                                                                                             |
| M16.99    |         A5         | Protein modification              | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.99%20)  |
| M16.100   |         A33        | TBD                               | 18                       | No Result                                                                                             |
| M16.101   |         A33        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.101%20) |
| M16.102   |         A33        | TBD                               | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.102%20) |
| M16.103   |         A31        | TBD                               | 17                       | No Result                                                                                             |
| M16.104   |         A8         | Cell cycle                        | 17                       | No Result                                                                                             |
| M16.105   |         A6         | TBD                               | 17                       | No Result                                                                                             |
| M16.106   |         A8         | TBD                               | 15                       | No Result                                                                                             |
| M16.107   |         A16        | Oxidative stress                  | 16                       | No Result                                                                                             |
| M16.108   |         A13        | TBD                               | 16                       | No Result                                                                                             |
| M16.109   |         A34        | Platelet                          | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.109%20) |
| M16.110   |         A16        | TBD                               | 15                       | No Result                                                                                             |
| M16.111   |         A5         | TBD                               | 15                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M16.111%20) |


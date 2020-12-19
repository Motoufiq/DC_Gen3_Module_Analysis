# RcisTarget Analysis Results using Generation 3 Modules

**RcisTarget: Transcription factor binding motif enrichment**

RcisTarget identifies transcription factor binding motifs (TFBS) over-represented on a gene list. In a first step, RcisTarget selects DNA motifs that are significantly over-represented in the surroundings of the transcription start site (TSS) of the genes in the gene-set. This is achieved by using a database that contains genome-wide cross-species rankings for each motif. The motifs that are then annotated to TFs and those that have a high Normalized Enrichment Score (NES) are retained. Finally, for each motif and gene-set, RcisTarget predicts the candidate target genes (i.e. genes in the gene-set that are ranked above the leading edge).

For additional details, refer:
1. https://pubmed.ncbi.nlm.nih.gov/28991892/
2. https://www.bioconductor.org/packages/release/bioc/html/RcisTarget.html (OR) https://www.bioconductor.org/packages/devel/bioc/vignettes/RcisTarget/inst/doc/RcisTarget.html


Note:
The RcisTarget R script was applied on 382 modules [Ref](https://www.biorxiv.org/content/10.1101/525709v2) using the default settings. The results were obtained 235 modules successfully and 147 modules failed to run (due to non-matching identifier between the Gene Symbols and motif database).




Module Table:

| Module ID | Aggregate   Number | Module   Annotation         | Number of unique   genes | RcisTarget   Result                                                                                  |
|-----------|--------------------|-----------------------------|--------------------------|------------------------------------------------------------------------------------------------------|
| M3.1      |         A29        | Cell cycle                  | 106                      | No Result                                                                                            |
| M8.1      |         A29        | TBD                         | 51                       | No Result                                                                                            |
| M8.2      |         A34        | Prostanoids                 | 36                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M8.2%20)   |
| M8.3      |         A28        | Type 1 Interferon           | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M8.3%20)   |
| M9.1      |         A2         | Cytotoxic lymphocytes       | 28                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M9.1%20)   |
| M9.2      |         A37        | Erythrocytes                | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M9.2%20)   |
| M10.1     |         A28        | Interferon                  | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M10.1%20)  |
| M10.2     |         A9         | Protein synthesis           | 19                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M10.2%20)  |
| M10.3     |         A34        | Platelet                    | 20                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M10.3%20)  |
| M10.4     |         A38        | Neutrophil activation       | 13                       | No Result                                                                                            |
| M11.1     |         A1         | Protein synthesis           | 46                       | No Result                                                                                            |
| M11.2     |         A37        | TBD                         | 39                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M11.2%20)  |
| M11.3     |         A37        | Erythrocytes                | 24                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M11.3%20)  |
| M11.4     |         A37        | TBD                         | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M11.4%20)  |
| M12.1     |         A1         | Protein modification        | 111                      | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.1%20)  |
| M12.2     |         A26        | Monocytes                   | 44                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.2%20)  |
| M12.3     |         A1         | Cell cycle                  | 70                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.3%20)  |
| M12.4     |         A2         | Gene transcription          | 62                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.4%20)  |
| M12.5     |         A3         | Protein modification        | 91                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.5%20)  |
| M12.6     |         A1         | T cells                     | 33                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.6%20)  |
| M12.7     |         A1         | Protein synthesis           | 35                       | No Result                                                                                            |
| M12.8     |         A1         | B cells                     | 26                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.8%20)  |
| M12.9     |         A38        | Protein   phosphorylation   | 42                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.9%20)  |
| M12.10    |         A35        | Inflammation                | 53                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.10%20) |
| M12.11    |         A37        | Erythrocytes                | 24                       | No Result                                                                                            |
| M12.12    |         A25        | Oxidative stress            | 31                       | No Result                                                                                            |
| M12.13    |         A24        | Oxidative   phosphorylation | 47                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.13%20) |
| M12.14    |         A29        | TBD                         | 20                       | No Result                                                                                            |
| M12.15    |         A27        | Cell cycle                  | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M12.15%20) |

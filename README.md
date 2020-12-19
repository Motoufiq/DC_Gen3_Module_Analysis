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




| Module ID | Aggregate   Number | Module   Annotation   | Number of unique   genes | RcisTarget-   Full Analysis Data                                                                    | RcisTarget-   Motif Data Table                                                                                        | RcisTarget-   Network Analysis                                                                               |
|-----------|--------------------|-----------------------|--------------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| M3.1      |         A29        | Cell cycle            | 106                      | No Result                                                                                           | No Result                                                                                                             | No Result                                                                                                    |
| M8.1      |         A29        | TBD                   | 51                       | No Result                                                                                           | No Result                                                                                                             | No Result                                                                                                    |
| M8.2      |         A34        | Prostanoids           | 36                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M8.2%20)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M8.2%20/Motif_data_table.html)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M8.2%20/Network.html)  |
| M8.3      |         A28        | Type 1 Interferon     | 17                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M8.3%20)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M8.3%20/Motif_data_table.html)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M8.3%20/Network.html)  |
| M9.1      |         A2         | Cytotoxic lymphocytes | 28                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M9.1%20)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M9.1%20/Motif_data_table.html)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M9.1%20/Network.html)  |
| M9.2      |         A37        | Erythrocytes          | 30                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M9.2%20)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M9.2%20/Motif_data_table.html)  | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M9.2%20/Network.html)  |
| M10.1     |         A28        | Interferon            | 21                       | [Link](https://github.com/Motoufiq/DC_Gen3_Module_Analysis/tree/main/RcisTarget_Output_v1/M10.1%20) | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M10.1%20/Motif_data_table.html) | [View   Here](https://motoufiq.github.io/DC_Gen3_Module_Analysis/RcisTarget_Output_v1/M10.1%20/Network.html) |

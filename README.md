# RcisTarget Analysis Results using Generation 3 Modules

**RcisTarget: Transcription factor binding motif enrichment**

RcisTarget identifies transcription factor binding motifs (TFBS) over-represented on a gene list. In a first step, RcisTarget selects DNA motifs that are significantly over-represented in the surroundings of the transcription start site (TSS) of the genes in the gene-set. This is achieved by using a database that contains genome-wide cross-species rankings for each motif. The motifs that are then annotated to TFs and those that have a high Normalized Enrichment Score (NES) are retained. Finally, for each motif and gene-set, RcisTarget predicts the candidate target genes (i.e. genes in the gene-set that are ranked above the leading edge).

For additional details, refer:
1. https://pubmed.ncbi.nlm.nih.gov/28991892/
2. https://www.bioconductor.org/packages/release/bioc/html/RcisTarget.html (OR) https://www.bioconductor.org/packages/devel/bioc/vignettes/RcisTarget/inst/doc/RcisTarget.html


Note:
1. The RcisTarget R script was applied on 382 modules [Ref](https://www.biorxiv.org/content/10.1101/525709v2) using the default settings. The results were obtained 235 modules successfully and 147 modules failed to run (due to non-matching identifier between the Gene Symbols and motif database).
2. To view the results of the RcisTarget analysis for 235 modules. Click here: https://github.com/Motoufiq/DC_Gen3_Module_Analysis/blob/main/Module_List.md




Module Table:

| Module ID | Aggregate   Number | Module   Annotation               | Number of unique   genes | RcisTarget Results |
|-----------|--------------------|-----------------------------------|--------------------------|--------------------|
| M3.1      |         A29        | Cell cycle                        | 106                      |     No Result      |
| M8.1      |         A29        | TBD                               | 51                       |                    |
| M8.2      |         A34        | Prostanoids                       | 36                       |                    |
| M8.3      |         A28        | Type 1 Interferon                 | 17                       |                    |
| M9.1      |         A2         | Cytotoxic lymphocytes             | 28                       |                    |
| M9.2      |         A37        | Erythrocytes                      | 30                       |                    |
| M10.1     |         A28        | Interferon                        | 21                       |                    |
| M10.2     |         A9         | Protein synthesis                 | 19                       |                    |
| M10.3     |         A34        | Platelet                          | 20                       |                    |
| M10.4     |         A38        | Neutrophil activation             | 13                       |                    |
| M11.1     |         A1         | Protein synthesis                 | 46                       |                    |
| M11.2     |         A37        | TBD                               | 39                       |                    |
| M11.3     |         A37        | Erythrocytes                      | 24                       |                    |
| M11.4     |         A37        | TBD                               | 26                       |                    |
| M12.1     |         A1         | Protein modification              | 111                      |                    |
| M12.2     |         A26        | Monocytes                         | 44                       |                    |
| M12.3     |         A1         | Cell cycle                        | 70                       |                    |
| M12.4     |         A2         | Gene transcription                | 62                       |                    |
| M12.5     |         A3         | Protein modification              | 91                       |                    |
| M12.6     |         A1         | T cells                           | 33                       |                    |
| M12.7     |         A1         | Protein synthesis                 | 35                       |                    |
| M12.8     |         A1         | B cells                           | 26                       |                    |
| M12.9     |         A38        | Protein   phosphorylation         | 42                       |                    |
| M12.10    |         A35        | Inflammation                      | 53                       |                    |
| M12.11    |         A37        | Erythrocytes                      | 24                       |                    |
| M12.12    |         A25        | Oxidative stress                  | 31                       |                    |
| M12.13    |         A24        | Oxidative   phosphorylation       | 47                       |                    |
| M12.14    |         A29        | TBD                               | 20                       |                    |
| M12.15    |         A27        | Cell cycle                        | 17                       |                    |
| M13.1     |         A35        | Inflammation                      | 137                      |                    |
| M13.2     |         A1         | Gene transcription                | 92                       |                    |
| M13.3     |         A35        | TBD                               | 100                      |                    |
| M13.4     |         A2         | Protein synthesis                 | 119                      |                    |
| M13.5     |         A32        | Cell death                        | 134                      |                    |
| M13.6     |         A1         | Gene transcription                | 127                      |                    |
| M13.7     |         A33        | TBD                               | 98                       |                    |
| M13.8     |         A3         | TBD                               | 55                       |                    |
| M13.9     |         A3         | Gene transcription                | 99                       |                    |
| M13.10    |         A2         | Protein synthesis                 | 91                       |                    |
| M13.11    |         A26        | TBD                               | 78                       |                    |
| M13.12    |         A35        | Inflammation                      | 55                       |                    |
| M13.13    |         A2         | Gene transcription                | 58                       |                    |
| M13.14    |         A2         | Proteolysis                       | 72                       |                    |
| M13.15    |         A32        | Gene transcription                | 76                       |                    |
| M13.16    |         A35        | Cytokines/chemokines              | 39                       |                    |
| M13.17    |         A28        | Interferon                        | 31                       |                    |
| M13.18    |         A1         | B cells                           | 88                       |                    |
| M13.19    |         A30        | Protein   phosphorylation         | 63                       |                    |
| M13.20    |         A29        | Cell cycle                        | 47                       |                    |
| M13.21    |         A2         | Cytotoxic lymphocytes             | 23                       |                    |
| M13.22    |         A35        | Neutrophils                       | 65                       |                    |
| M13.23    |         A3         | TBD                               | 79                       |                    |
| M13.24    |         A24        | TBD                               | 70                       |                    |
| M13.25    |         A32        | Protein   phosphorylation         | 79                       |                    |
| M13.26    |         A37        | Oxidative stress                  | 40                       |                    |
| M13.27    |         A1         | B cells                           | 33                       |                    |
| M13.28    |         A1         | Protein synthesis                 | 29                       |                    |
| M13.29    |         A2         | Protein modification              | 65                       |                    |
| M13.30    |         A37        | Erythrocytes                      | 29                       |                    |
| M13.31    |         A25        | TBD                               | 25                       |                    |
| M13.32    |         A27        | Cell cycle                        | 30                       |                    |
| M14.1     |         A32        | Gene transcription                | 44                       |                    |
| M14.2     |         A2         | Protein synthesis                 | 44                       |                    |
| M14.3     |         A2         | Protein modification              | 39                       |                    |
| M14.4     |         A1         | Gene transcription                | 38                       |                    |
| M14.5     |         A1         | Gene transcription                | 36                       |                    |
| M14.6     |         A3         | TBD                               | 31                       |                    |
| M14.7     |         A35        | TBD                               | 31                       |                    |
| M14.8     |         A2         | TBD                               | 30                       |                    |
| M14.9     |         A32        | TBD                               | 27                       |                    |
| M14.10    |         A26        | TBD                               | 28                       |                    |
| M14.11    |         A32        | TBD                               | 28                       |                    |
| M14.12    |         A1         | Cell cycle                        | 26                       |                    |
| M14.13    |         A2         | Oxidative   phosphorylation       | 26                       |                    |
| M14.14    |         A6         | Protein modification              | 27                       |                    |
| M14.15    |         A6         | Protein modification              | 25                       |                    |
| M14.16    |         A24        | TBD                               | 26                       |                    |
| M14.17    |         A2         | Gene transcription                | 26                       |                    |
| M14.18    |         A32        | TBD                               | 25                       |                    |
| M14.19    |         A33        | Inflammation                      | 23                       |                    |
| M14.20    |         A1         | Gene transcription                | 24                       |                    |
| M14.21    |         A26        | TBD                               | 23                       |                    |
| M14.22    |         A32        | TBD                               | 23                       |                    |
| M14.23    |         A1         | Gene transcription                | 24                       |                    |
| M14.24    |         A33        | Inflammation                      | 23                       |                    |
| M14.25    |         A2         | TBD                               | 22                       |                    |
| M14.26    |         A33        | Inflammation                      | 22                       |                    |
| M14.27    |         A25        | Protein synthesis                 | 21                       |                    |
| M14.28    |         A35        | Neutrophils                       | 20                       |                    |
| M14.29    |         A32        | TBD                               | 22                       |                    |
| M14.30    |         A24        | Oxidative   phosphorylation       | 21                       |                    |
| M14.31    |         A3         | Cell cycle                        | 22                       |                    |
| M14.32    |         A26        | TBD                               | 22                       |                    |
| M14.33    |         A30        | Proteolysis                       | 22                       |                    |
| M14.34    |         A2         | Gene transcription                | 21                       |                    |
| M14.35    |         A2         | TBD                               | 20                       |                    |
| M14.36    |         A32        | TBD                               | 20                       |                    |
| M14.37    |         A6         | TBD                               | 19                       |                    |
| M14.38    |         A31        | TBD                               | 17                       |                    |
| M14.39    |         A34        | Cell cycle                        | 18                       |                    |
| M14.40    |         A6         | Cellular respiration              | 19                       |                    |
| M14.41    |         A24        | TBD                               | 19                       |                    |
| M14.42    |         A1         | T cells                           | 19                       |                    |
| M14.43    |         A3         | TBD                               | 18                       |                    |
| M14.44    |         A2         | Protein synthesis                 | 18                       |                    |
| M14.45    |         A2         | TBD                               | 18                       |                    |
| M14.46    |         A3         | TBD                               | 18                       |                    |
| M14.47    |         A2         | Protein synthesis                 | 18                       |                    |
| M14.48    |         A31        | Inflammation                      | 17                       |                    |
| M14.49    |         A1         | Gene transcription                | 18                       |                    |
| M14.50    |         A33        | Inflammation                      | 18                       |                    |
| M14.51    |         A36        | Oxidative stress                  | 14                       |                    |
| M14.52    |         A3         | TBD                               | 17                       |                    |
| M14.53    |         A37        | Erythrocytes                      | 16                       |                    |
| M14.54    |         A6         | Cell cycle                        | 18                       |                    |
| M14.55    |         A6         | Gene transcription                | 17                       |                    |
| M14.56    |         A32        | TBD                               | 17                       |                    |
| M14.57    |         A24        | Protein modification              | 16                       |                    |
| M14.58    |         A1         | Protein synthesis                 | 17                       |                    |
| M14.59    |         A34        | TBD                               | 16                       |                    |
| M14.60    |         A29        | TBD                               | 17                       |                    |
| M14.61    |         A2         | Protein modification              | 16                       |                    |
| M14.62    |         A32        | TBD                               | 16                       |                    |
| M14.63    |         A24        | Oxidative   phosphorylation       | 16                       |                    |
| M14.64    |         A1         | Cell cycle                        | 16                       |                    |
| M14.65    |         A35        | Monocytes                         | 15                       |                    |
| M14.66    |         A33        | Inflammation                      | 16                       |                    |
| M14.67    |         A32        | Gene transcription                | 16                       |                    |
| M14.68    |         A38        | Protein synthesis                 | 16                       |                    |
| M14.69    |         A1         | Gene transcription                | 15                       |                    |
| M14.70    |         A26        | TBD                               | 15                       |                    |
| M14.71    |         A1         | Gene transcription                | 14                       |                    |
| M14.72    |         A2         | TBD                               | 15                       |                    |
| M14.73    |         A32        | TBD                               | 15                       |                    |
| M14.74    |         A35        | TBD                               | 14                       |                    |
| M14.75    |         A1         | Protein synthesis                 | 15                       |                    |
| M14.76    |         A33        | Leukocyte activation              | 15                       |                    |
| M14.77    |         A1         | Gene transcription                | 15                       |                    |
| M14.78    |         A3         | TBD                               | 15                       |                    |
| M14.79    |         A2         | Protein synthesis                 | 15                       |                    |
| M14.80    |         A1         | Protein synthesis                 | 12                       |                    |
| M14.81    |         A31        | Platelet                          | 14                       |                    |
| M14.82    |         A33        | Cytokines/chemokines              | 15                       |                    |
| M14.83    |         A25        | TBD                               | 14                       |                    |
| M15.1     |         A6         | TBD                               | 79                       |                    |
| M15.2     |         A6         | TBD                               | 60                       |                    |
| M15.3     |         A2         | Gene transcription                | 57                       |                    |
| M15.4     |         A1         | B cells                           | 54                       |                    |
| M15.5     |         A5         | Protein modification              | 53                       |                    |
| M15.6     |         A7         | Cell cycle                        | 54                       |                    |
| M15.7     |         A26        | Monocytes                         | 52                       |                    |
| M15.8     |         A2         | Gene transcription                | 51                       |                    |
| M15.9     |         A6         | T cells                           | 51                       |                    |
| M15.10    |         A6         | Gene transcription                | 50                       |                    |
| M15.11    |         A6         | TBD                               | 49                       |                    |
| M15.12    |         A33        | TBD                               | 48                       |                    |
| M15.13    |         A33        | TBD                               | 48                       |                    |
| M15.14    |         A33        | TBD                               | 47                       |                    |
| M15.15    |         A6         | TBD                               | 46                       |                    |
| M15.16    |         A3         | Antigen presentation              | 45                       |                    |
| M15.17    |         A22        | TBD                               | 44                       |                    |
| M15.18    |         A32        | TBD                               | 41                       |                    |
| M15.19    |         A6         | Gene transcription                | 43                       |                    |
| M15.20    |         A32        | TBD                               | 41                       |                    |
| M15.21    |         A2         | Gene transcription                | 42                       |                    |
| M15.22    |         A6         | TBD                               | 42                       |                    |
| M15.23    |         A2         | Cell death                        | 41                       |                    |
| M15.24    |         A33        | TBD                               | 41                       |                    |
| M15.25    |         A4         | TBD                               | 38                       |                    |
| M15.26    |         A35        | Neutrophils                       | 38                       |                    |
| M15.27    |         A6         | Cell cycle                        | 40                       |                    |
| M15.28    |         A24        | Oxidative   phosphorylation       | 37                       |                    |
| M15.29    |         A1         | Cell death                        | 35                       |                    |
| M15.30    |         A32        | TBD                               | 36                       |                    |
| M15.31    |         A2         | Protein modification              | 35                       |                    |
| M15.32    |         A29        | TBD                               | 36                       |                    |
| M15.33    |         A1         | T cells                           | 35                       |                    |
| M15.34    |         A6         | T cells                           | 34                       |                    |
| M15.35    |         A33        | Neutrophils                       | 33                       |                    |
| M15.36    |         A26        | Protein modification              | 34                       |                    |
| M15.37    |         A35        | Inflammation                      | 33                       |                    |
| M15.38    |         A1         | T cells                           | 32                       |                    |
| M15.39    |         A8         | TBD                               | 32                       |                    |
| M15.40    |         A6         | Gene transcription                | 31                       |                    |
| M15.41    |         A2         | TBD                               | 31                       |                    |
| M15.42    |         A6         | Gene transcription                | 30                       |                    |
| M15.43    |         A35        | TBD                               | 30                       |                    |
| M15.44    |         A3         | Protein modification              | 28                       |                    |
| M15.45    |         A6         | Platelet                          | 29                       |                    |
| M15.46    |         A2         | TBD                               | 27                       |                    |
| M15.47    |         A32        | Antigen presentation              | 28                       |                    |
| M15.48    |         A3         | TBD                               | 27                       |                    |
| M15.49    |         A4         | Cell death                        | 27                       |                    |
| M15.50    |         A2         | TBD                               | 27                       |                    |
| M15.51    |         A1         | Protein synthesis                 | 26                       |                    |
| M15.52    |         A3         | TBD                               | 27                       |                    |
| M15.53    |         A37        | Erythrocytes                      | 25                       |                    |
| M15.54    |         A2         | TBD                               | 26                       |                    |
| M15.55    |         A25        | Protein   phosphorylation         | 24                       |                    |
| M15.56    |         A30        | Cell adhesion                     | 25                       |                    |
| M15.57    |         A26        | TBD                               | 26                       |                    |
| M15.58    |         A31        | Monocytes                         | 22                       |                    |
| M15.59    |         A7         | TBD                               | 24                       |                    |
| M15.60    |         A1         | TBD                               | 25                       |                    |
| M15.61    |         A7         | Monocytes                         | 25                       |                    |
| M15.62    |         A32        | TBD                               | 25                       |                    |
| M15.63    |         A26        | TBD                               | 22                       |                    |
| M15.64    |         A28        | Interferon                        | 21                       |                    |
| M15.65    |         A2         | TBD                               | 23                       |                    |
| M15.66    |         A33        | TBD                               | 23                       |                    |
| M15.67    |         A11        | TBD                               | 22                       |                    |
| M15.68    |         A29        | TBD                               | 23                       |                    |
| M15.69    |         A32        | TBD                               | 22                       |                    |
| M15.70    |         A26        | Protein modification              | 22                       |                    |
| M15.71    |         A6         | TBD                               | 22                       |                    |
| M15.72    |         A2         | TBD                               | 22                       |                    |
| M15.73    |         A30        | Cell cycle                        | 22                       |                    |
| M15.74    |         A37        | Erythrocytes                      | 21                       |                    |
| M15.75    |         A4         | TBD                               | 20                       |                    |
| M15.76    |         A32        | TBD                               | 21                       |                    |
| M15.77    |         A25        | TBD                               | 21                       |                    |
| M15.78    |         A35        | TBD                               | 20                       |                    |
| M15.79    |         A3         | Mitochondrial   Stress/Proteasome | 19                       |                    |
| M15.80    |         A6         | TBD                               | 20                       |                    |
| M15.81    |         A35        | TBD                               | 20                       |                    |
| M15.82    |         A1         | TBD                               | 20                       |                    |
| M15.83    |         A6         | Gene transcription                | 20                       |                    |
| M15.84    |         A35        | Cytokines/chemokines              | 20                       |                    |
| M15.85    |         A3         | TBD                               | 20                       |                    |
| M15.86    |         A28        | Interferon                        | 15                       |                    |
| M15.87    |         A1         | TBD                               | 19                       |                    |
| M15.88    |         A32        | TBD                               | 19                       |                    |
| M15.89    |         A24        | TBD                               | 19                       |                    |
| M15.90    |         A33        | TBD                               | 16                       |                    |
| M15.91    |         A2         | TBD                               | 17                       |                    |
| M15.92    |         A6         | Protein modification              | 18                       |                    |
| M15.93    |         A1         | TBD                               | 18                       |                    |
| M15.94    |         A3         | TBD                               | 18                       |                    |
| M15.95    |         A7         | TBD                               | 18                       |                    |
| M15.96    |         A6         | TBD                               | 18                       |                    |
| M15.97    |         A36        | Cell death                        | 17                       |                    |
| M15.98    |         A6         | T cells                           | 18                       |                    |
| M15.99    |         A32        | Protein modification              | 15                       |                    |
| M15.100   |         A37        | Erythrocytes                      | 17                       |                    |
| M15.101   |         A3         | TBD                               | 18                       |                    |
| M15.102   |         A10        | Prostanoids                       | 15                       |                    |
| M15.103   |         A24        | TBD                               | 17                       |                    |
| M15.104   |         A33        | TBD                               | 17                       |                    |
| M15.105   |         A35        | Inflammation                      | 16                       |                    |
| M15.106   |         A32        | TBD                               | 17                       |                    |
| M15.107   |         A15        | TBD                               | 17                       |                    |
| M15.108   |         A33        | TBD                               | 17                       |                    |
| M15.109   |         A35        | Inflammation                      | 17                       |                    |
| M15.110   |         A27        | Cell cycle                        | 16                       |                    |
| M15.111   |         A33        | TBD                               | 17                       |                    |
| M15.112   |         A26        | TBD                               | 16                       |                    |
| M15.113   |         A35        | Inflammation                      | 16                       |                    |
| M15.114   |         A1         | TBD                               | 16                       |                    |
| M15.115   |         A2         | TBD                               | 16                       |                    |
| M15.116   |         A2         | TBD                               | 16                       |                    |
| M15.117   |         A25        | TBD                               | 16                       |                    |
| M15.118   |         A36        | Gene transcription                | 14                       |                    |
| M15.119   |         A2         | TBD                               | 16                       |                    |
| M15.120   |         A2         | TBD                               | 16                       |                    |
| M15.121   |         A31        | TBD                               | 14                       |                    |
| M15.122   |         A2         | TBD                               | 15                       |                    |
| M15.123   |         A24        | TBD                               | 15                       |                    |
| M15.124   |         A3         | TBD                               | 15                       |                    |
| M15.125   |         A12        | TBD                               | 15                       |                    |
| M15.126   |         A17        | Gene transcription                | 15                       |                    |
| M15.127   |         A28        | Interferon                        | 14                       |                    |
| M16.1     |         A33        | TBD                               | 169                      |                    |
| M16.2     |         A32        | Protein synthesis                 | 161                      |                    |
| M16.3     |         A6         | T cells                           | 145                      |                    |
| M16.4     |         A6         | TBD                               | 130                      |                    |
| M16.5     |         A32        | TBD                               | 123                      |                    |
| M16.6     |         A8         | Monocytes                         | 119                      |                    |
| M16.7     |         A2         | TBD                               | 116                      |                    |
| M16.8     |         A6         | TBD                               | 116                      |                    |
| M16.9     |         A32        | Protein modification              | 109                      |                    |
| M16.10    |         A3         | TBD                               | 105                      |                    |
| M16.11    |         A4         | Protein synthesis                 | 102                      |                    |
| M16.12    |         A15        | B cells                           | 100                      |                    |
| M16.13    |         A5         | Protein modification              | 94                       |                    |
| M16.14    |         A6         | TBD                               | 89                       |                    |
| M16.15    |         A4         | Cell death                        | 86                       |                    |
| M16.16    |         A32        | TBD                               | 88                       |                    |
| M16.17    |         A17        | Gene transcription                | 83                       |                    |
| M16.18    |         A5         | TBD                               | 82                       |                    |
| M16.19    |         A18        | TBD                               | 82                       |                    |
| M16.20    |         A23        | TBD                               | 81                       |                    |
| M16.21    |         A15        | TBD                               | 80                       |                    |
| M16.22    |         A33        | TBD                               | 76                       |                    |
| M16.23    |         A17        | Cell cycle                        | 76                       |                    |
| M16.24    |         A6         | T cells                           | 72                       |                    |
| M16.25    |         A6         | TBD                               | 74                       |                    |
| M16.26    |         A26        | TBD                               | 72                       |                    |
| M16.27    |         A32        | TBD                               | 69                       |                    |
| M16.28    |         A15        | TBD                               | 67                       |                    |
| M16.29    |         A8         | TBD                               | 62                       |                    |
| M16.30    |         A8         | Complement                        | 61                       |                    |
| M16.31    |         A6         | TBD                               | 62                       |                    |
| M16.32    |         A26        | TBD                               | 59                       |                    |
| M16.33    |         A15        | TBD                               | 59                       |                    |
| M16.34    |         A36        | Gene transcription                | 56                       |                    |
| M16.35    |         A15        | TBD                               | 55                       |                    |
| M16.36    |         A5         | Gene transcription                | 54                       |                    |
| M16.37    |         A33        | TBD                               | 48                       |                    |
| M16.38    |         A15        | TBD                               | 52                       |                    |
| M16.39    |         A8         | TBD                               | 52                       |                    |
| M16.40    |         A7         | Monocytes                         | 51                       |                    |
| M16.41    |         A2         | TBD                               | 48                       |                    |
| M16.42    |         A3         | TBD                               | 50                       |                    |
| M16.43    |         A4         | Gene transcription                | 48                       |                    |
| M16.44    |         A33        | Protein synthesis                 | 48                       |                    |
| M16.45    |         A3         | TBD                               | 47                       |                    |
| M16.46    |         A26        | TBD                               | 48                       |                    |
| M16.47    |         A18        | TNF                               | 47                       |                    |
| M16.48    |         A21        | TBD                               | 47                       |                    |
| M16.49    |         A25        | Inflammation                      | 45                       |                    |
| M16.50    |         A4         | Protein modification              | 45                       |                    |
| M16.51    |         A33        | Protein synthesis                 | 43                       |                    |
| M16.52    |         A20        | Lymphocyte                        | 43                       |                    |
| M16.53    |         A8         | TBD                               | 42                       |                    |
| M16.54    |         A6         | TBD                               | 40                       |                    |
| M16.55    |         A15        | TBD                               | 40                       |                    |
| M16.56    |         A1         | Protein synthesis                 | 38                       |                    |
| M16.57    |         A5         | B cells                           | 38                       |                    |
| M16.58    |         A15        | TBD                               | 39                       |                    |
| M16.59    |         A6         | TBD                               | 38                       |                    |
| M16.60    |         A27        | Cell cycle                        | 36                       |                    |
| M16.61    |         A25        | TBD                               | 36                       |                    |
| M16.62    |         A33        | TBD                               | 35                       |                    |
| M16.63    |         A33        | TBD                               | 35                       |                    |
| M16.64    |         A31        | Platelet/Prostaglandin            | 33                       |                    |
| M16.65    |         A5         | TGF-beta                          | 34                       |                    |
| M16.66    |         A15        | TBD                               | 34                       |                    |
| M16.67    |         A33        | TBD                               | 33                       |                    |
| M16.68    |         A2         | Protein synthesis                 | 33                       |                    |
| M16.69    |         A4         | Lipid metabolism                  | 32                       |                    |
| M16.70    |         A33        | TBD                               | 29                       |                    |
| M16.71    |         A25        | TBD                               | 31                       |                    |
| M16.72    |         A4         | TBD                               | 30                       |                    |
| M16.73    |         A25        | Protein synthesis                 | 30                       |                    |
| M16.74    |         A25        | TBD                               | 29                       |                    |
| M16.75    |         A17        | Cell death                        | 30                       |                    |
| M16.76    |         A33        | TBD                               | 25                       |                    |
| M16.77    |         A4         | Antigen presentation              | 28                       |                    |
| M16.78    |         A1         | B cells                           | 28                       |                    |
| M16.79    |         A35        | Protein synthesis                 | 27                       |                    |
| M16.80    |         A33        | Cytokines/chemokines              | 27                       |                    |
| M16.81    |         A6         | TBD                               | 27                       |                    |
| M16.82    |         A36        | Gene transcription                | 25                       |                    |
| M16.83    |         A7         | Cell adhesion                     | 26                       |                    |
| M16.84    |         A5         | Protein   phosphorylation         | 25                       |                    |
| M16.85    |         A32        | TBD                               | 24                       |                    |
| M16.86    |         A29        | Oxidative stress                  | 25                       |                    |
| M16.87    |         A15        | TBD                               | 23                       |                    |
| M16.88    |         A36        | Erythrocytes                      | 23                       |                    |
| M16.89    |         A30        | TBD                               | 23                       |                    |
| M16.90    |         A14        | TBD                               | 22                       |                    |
| M16.91    |         A1         | TBD                               | 21                       |                    |
| M16.92    |         A27        | Cell cycle                        | 22                       |                    |
| M16.93    |         A31        | TBD                               | 22                       |                    |
| M16.94    |         A19        | TBD                               | 21                       |                    |
| M16.95    |         A5         | B cells                           | 21                       |                    |
| M16.96    |         A38        | Erythrocytes                      | 19                       |                    |
| M16.97    |         A17        | Cell death                        | 20                       |                    |
| M16.98    |         A35        | TBD                               | 18                       |                    |
| M16.99    |         A5         | Protein modification              | 17                       |                    |
| M16.100   |         A33        | TBD                               | 18                       |                    |
| M16.101   |         A33        | TBD                               | 17                       |                    |
| M16.102   |         A33        | TBD                               | 17                       |                    |
| M16.103   |         A31        | TBD                               | 17                       |                    |
| M16.104   |         A8         | Cell cycle                        | 17                       |                    |
| M16.105   |         A6         | TBD                               | 17                       |                    |
| M16.106   |         A8         | TBD                               | 15                       |                    |
| M16.107   |         A16        | Oxidative stress                  | 16                       |                    |
| M16.108   |         A13        | TBD                               | 16                       |                    |
| M16.109   |         A34        | Platelet                          | 15                       |                    |
| M16.110   |         A16        | TBD                               | 15                       |                    |
| M16.111   |         A5         | TBD                               | 15                       |                    |
  
  
  
 

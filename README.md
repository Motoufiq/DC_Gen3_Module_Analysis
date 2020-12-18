# RcisTarget Analysis Results using Generation 3 Modules

**RcisTarget: Transcription factor binding motif enrichment**

RcisTarget identifies transcription factor binding motifs (TFBS) over-represented on a gene list. In a first step, RcisTarget selects DNA motifs that are significantly over-represented in the surroundings of the transcription start site (TSS) of the genes in the gene-set. This is achieved by using a database that contains genome-wide cross-species rankings for each motif. The motifs that are then annotated to TFs and those that have a high Normalized Enrichment Score (NES) are retained. Finally, for each motif and gene-set, RcisTarget predicts the candidate target genes (i.e. genes in the gene-set that are ranked above the leading edge).

For additional details, refer:
1. https://pubmed.ncbi.nlm.nih.gov/28991892/
2. https://www.bioconductor.org/packages/release/bioc/html/RcisTarget.html (OR) https://www.bioconductor.org/packages/devel/bioc/vignettes/RcisTarget/inst/doc/RcisTarget.html


**Note: 
There are some cases where RcisTarget does not output the results if the Gene Symbols identifier in the a particular module does not match with the motif database.  We experience the below error:
Error in .RcisTarget_calcAUC(geneSets = geneSets, rankings = rankings,  : 
  Fewer than 80% of the genes/features in the gene-sets are included in the rankings.Check wether the IDs in the 'rankings' (columns) and 'geneSets' match.
  
  
  
  
 

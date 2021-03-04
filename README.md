## system_biology_mps
Comprehensive analysis of neurological symptoms of Mucopolysaccharidoses: A system biology approach

# Methods
Download and Analysis of Transcriptome Data
The transcriptome datasets were retrieved from Gene Expression Omnibus (GEO – Edgar et al., 2002; Barrett et al., 2013) with the accession numbers GSE111906 (MPS type I, human neural ips), GSE95224 (MPS II, mouse cerebral cortex and midbrain/diencephalon/hippocampus), GSE23075 (MPS IIIB, human neural stem cells cultivated in neurospheres), GSE15758 (MPS IIIB, mouse neurons of medial entorhinal cortex and lateral entorhinal cortex), and GSE76283 (MPS VII, mouse hippocampus). 
We perform gene expression analysis in edgeR v.3.28.1(Robinson et al., 2010), in the case of RNA-seq datasets. We used limma package v.3.44.3 for the microarray datasets (Ritchie et al., 2015), with the appropriate functions according to the GeneChip requirements. More information about the datasets may be found in our database for differential expressed genes in Mucopolysaccharidoses,  MPSBase <https://www.ufrgs.br/mpsbase/>.
Gene network was primarily employed in metasearch engine STRING v.11.0 (Szklarczyk et al., 2019), with the most 2000 expressed genes of each dataset, filtered by False Discovery Rate (FDR) adjust method. 
The functional enrichment was quantitatively assessed (p-value) using a hypergeometric distribution. Multiple test correction was also implemented by applying the false discovery rate (FDR) algorithm (Benjamini and Hochberg 1995) at a significance level of p<0.05. We used the Biological Network Gene Ontology (BiNGO) plugin v.3.0.4 (Maere et al., 2005) and CluePedia: A ClueGO plugin for pathway insights using integrated experimental and in silico data v.2.5.7 (Bindea et al., 2009; Bindea et al., 2013), with the terms or pathways consulted in the database of GO Immune System, KEGG, Reactome, and Wikipathways (Ashburner et al., 2000; Kanehisa et al., 2002; Kelder et al., 2012; Jassal et al., 2020).

# Data
Origin of all data: GEO, retrieved at 03-12-2019
String: August 2019
Cytoscape: August 2019

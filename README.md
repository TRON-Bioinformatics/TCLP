# TCLP: an online cancer cell line catalogue integrating HLA type, predicted neo-epitopes, virus and gene expression
Genome Medicine volume 7, Article number: 118 (2015) 

https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-015-0240-5

# Abstract
Human cancer cell lines are an important resource for research and drug development. However, the available annotations of cell lines are sparse, incomplete, and distributed in multiple repositories. Re-analyzing publicly available raw RNA-Seq data, we determined the human leukocyte antigen (HLA) type and abundance, identified expressed viruses and calculated gene expression of 1,082 cancer cell lines. Using the determined HLA types, public databases of cell line mutations, and existing HLA binding prediction algorithms, we predicted antigenic mutations in each cell line. We integrated the results into a comprehensive knowledgebase. Using the Django web framework, we provide an interactive user interface with advanced search capabilities to find and explore cell lines and an application programming interface to extract cell line information. The portal is available at http://celllines.tron-mainz.de.

The data from the portal is stored here (or in DropBox) as text files:

 - [TRON_expression_values.txt](https://www.dropbox.com/scl/fi/36ycwvot25dbwv0u2r1vg/TRON_expression_values.txt?rlkey=rhve8omp61uv8nl92l990d4uh&dl=0) - matrix of cell lines and gene expression values 
- [20240226_TCLP_HLA_data.csv](https://github.com/TRON-Bioinformatics/TCLP/blob/main/20240226_TCLP_HLA_data.csv) - list of class 1 and 2 MHC alleles per cell line, including expression 
- [TCLP_neoepitope_catalog.csv](https://www.dropbox.com/scl/fi/kltz9jyf0wboxg0z4rah0/TCLP_neoepitope_catalog.csv?rlkey=rou7gkn1hcxebdfzi8gt8l5fx&dl=0) - original catalog of neoepitopes \
Columns: cell line name, gene, chromosome, position, mutation, allele, IC50, rank, peptide, WT IC50, WT rank, WT peptide
- [20240226_TCLP_virus_data.csv](https://github.com/TRON-Bioinformatics/TCLP/blob/main/20240226_TCLP_virus_data.csv) - dataset of detected viruses in cell lines
  


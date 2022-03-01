# Datasets

## Mouse signature genes
Mouse signature genes are obtained from [Pal et al. 2021 mouse paper](https://breast-cancer-research.biomedcentral.com/articles/10.1186/s13058-021-01445-4) containing **1464 Basal** genes, **428 LP** genes and **528 ML** genes. <br />

The **raw basal** gene number in the mouse paper is **1467**, while two of them have ```NA``` GeneIDs and one of them has the same GeneID with another gene, hence, these three genes are removed. <br />
       
**```Mouse_positive_signature_genes.rds```** is a data.frame including 4 columns ("GeneID", "Symbol", "alias", "gene_type"). <br />
**GeneID**: Entrez gene ID from NCBI <br />
**Symbol**: Official gene symbol from NCBI <br />
**alias** : Gene symbol obtained from _cellranger_ feature annotation file <br />
**gene_type**: signature gene type (Basal, LP or ML) <br />


## Human signature genes
Human signature genes are obtained from [Pal et al. 2021 human paper](https://doi.org/10.15252/embj.2020107333) containing **515 Basal** genes, **323 LP** genes, **765 ML** genes and **1094 Stroma** genes. <br />

**```Human_positive_signature_genes.rds```** is a data.frame including 3 columns ("GeneID", "SYMBOL", "gene_type"). <br />
**GeneID**: Entrez gene ID from NCBI <br /> 
**SYMBOL**: Gene symbol <br />
**gene_type**: signature gene type (Basal, LP, ML or Stroma) <br />

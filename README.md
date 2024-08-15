# Hackathon-Summer-2024
Hackathon 2024 why-axis team repository


## Challenge overview

Single-cell multiome (RNA + ATAC) sequencing is a recently developed technology platform that simultaneously profiles gene expression and chromatin accessibility from the same cell. Single-cell multiome can transform your understanding of biology, for example, estimating the association between enhancer and gene expression using single-cell multiome data. However, such multiome data have an overabundance of zeros due to dropout events where the mRNA or chromatin accessibility is undetected in a cell. Thus, typical correlation methods (like Pearson correlation and Spearman's rank correlation) showed a low power in estimating the associations between regulatory elements and gene expression. For an overview of zero inflation in single-cell data, see Jiang et al. (2022, PMID: 35063006). Accurate detection of associations between regulatory elements and gene expression remains a significant challenge, and no single method outperforms all others.

The goal of this hackathon is to develop your model to identify associations between chromatin accessibility and gene expression using single-cell multiome data. Chromatin accessibility (ATAC in this hackathon) represents a functional canalization of the epigenome by defining a repertoire of putative regulatory regions (peaks in this hackathon) across the genome, further shaping gene expression programs (RNA in this hackathon). For an overview of the relationship between Chromatin accessibility and gene regulation, see Klemm et al. (2019, PMID: 30675018).

---
layout: page
permalink: meetings/24-09-11
---

### Meeting Details

**Date**: 24-09-11

**Time**: 11:00-12:00 

**Location**: Hybrid: Rm 6E032/34 and via Teams 

**Presenter**: Dr. Charles Breeze 

###  F-MAGMA: leveraging epigenomic data for enhanced target gene identification in GWAS

Genome-wide association studies (GWAS) have linked many variants to various traits and diseases, yet identifying actionable gene targets remains a challenge. MAGMA is commonly used to prioritize target genes from GWAS data; however, MAGMA does not account for tissue- and cell type-specific variant context. Here, we present F-MAGMA, an enhanced version of MAGMA that integrates cell type-specific regulatory element data for individual variants. By incorporating regulatory element data, F-MAGMA refines gene and gene set analyses, offering deeper insights into disease pathways. To annotate regulatory elements, F-MAGMA incorporates epigenomic data across histone mark peaks, chromatin states, DNase I hypersensitive sites, and ATAC-seq peaks. We used Benchmarker, a unified framework to evaluate gene-prioritization methods, to compare the performance of F-MAGMA and MAGMA on GWAS summary statistics from a diverse set of 30 diseases and traits. Compared to MAGMA, we discovered that F-MAGMA achieves higher normalized SNP heritability (τ*) across all 30 GWAS (P<3.73e-09), indicating superior trait-relevant gene identification. On average, 15.5% of genes identified by F-MAGMA as being significantly associated with disease (p<5e-5) were not detected using MAGMA. For example, for height GWAS, F-MAGMA identified a higher proportion of OMIM genes related to skeletal growth disorders than MAGMA (p=0.048). In downstream gene ontology (GO) analyses using the top 100 highest ranked genes for each GWAS, F-MAGMA identified different GO terms than MAGMA, with an average of 62.5% of unique GO terms not observed in parallel MAGMA analyses. For example, F-MAGMA revealed a novel and biologically relevant association between the GO term “positive T cell selection" and nucleated red blood cell count. In gene set enrichment analyses using the 14,462 reconstituted DEPICT gene sets, on average, 43.7% gene sets identified by F-MAGMA were not detected by MAGMA. For example, F-MAGMA identified the "induced chromosome breakage" gene set for melanoma, which was missed by MAGMA. For ease of use, F-MAGMA and MAGMA are implemented as a new cloud-based webtool, termed GWAStarget (https://analysistools.cancer.gov/gwas-target/analysis). GWAStarget provides a graphical interface for rapid analysis of GWAS summary statistics, and includes a reference set of tissue and cell type chromatin accessibility datasets, while also allowing upload of user-generated epigenomic peaks. In conclusion, F-MAGMA is an integrative approach that uses cell type-specific chromatin data to deliver an advanced gene prioritization method for post-GWAS analysis, offering deeper insights into disease etiology.


---

<br><br>


# Pan-cancer characterization of polymerase families using single and bulk-RNA sequencing 

Polymerase families are essential for DNA replication and repair, but their functional roles across various cancer types and cellular contexts remain incompletely defined. In this study, we utilize both bulk and single-cell RNA sequencing (scRNA-seq) data to systematically investigate the function of polymerases across a wide spectrum of cancers. Our analysis includes RNA-seq data from The Cancer Genome Atlas (TCGA), covering 33 distinct cancer types, and scRNA-seq data from 20 clinical tumor tissue datasets. We will curate, integrate, and perform comprehensive quality control of these datasets, employing sophisticated batch correction techniques to address technical variability. This integrated pan-cancer and cell-type-specific analysis aims to provide novel insights into the diverse roles of polymerases in cancer biology, potentially revealing new therapeutic targets or biomarkers.


## Data access

### scRNA-seq data collection

Transcriptome data of 346 tumor samples from 251 individuals across 20 scRNA-seq 10x Genomics droplet based datasets were obtained from public data. 

1. Li, R. Y. et al. Mapping single-cell transcriptomes in the intra-tumoral and associated territories of kidney cancer. Cancer Cell 40, 1583-+ (2022). https://doi.org:10.1016/j.ccell.2022.11.001

2. Zhang, Y. P. et al. Single-cell analyses of renal cell cancers reveal insights into tumor microenvironment, cell of origin, and therapy response. Proceedings of the National Academy of Sciences of the United States of America 118 (2021). https://doi.org:ARTN e210324011810.1073/pnas.2103240118

3. Werba, G. et al. Single-cell RNA sequencing reveals the effects of chemotherapy on human pancreatic adenocarcinoma and its tumor microenvironment (vol 14, 797, 2023). Nature Communications 14 (2023). https://doi.org:ARTN 391210.1038/s41467-023-39680-2

4. Ma, L. C. et al. Tumor Cell Biodiversity Drives Microenvironmental Reprogramming in Liver Cancer. Cancer Cell 36, 418-+ (2019). https://doi.org:10.1016/j.ccell.2019.08.007

5. Regner, M. J. et al. A multi-omic single-cell landscape of human gynecologic malignancies. Mol Cell 81, 4924-4941 e4910 (2021). https://doi.org:10.1016/j.molcel.2021.10.013

6. Chen, Y. P. et al. Single-cell transcriptomics reveals regulators underlying immune cell diversity and immune subtypes associated with prognosis in nasopharyngeal carcinoma. Cell Res 30, 1024-1042 (2020). https://doi.org:10.1038/s41422-020-0374-x

7. Xu, J. F. et al. Single-Cell RNA Sequencing Reveals the Tissue Architecture in Human High-Grade Serous Ovarian Cancer. Clinical Cancer Research 28, 3590-3602 (2022). https://doi.org:10.1158/1078-0432.Ccr-22-0296

8. Li, C. B. et al. Single-cell transcriptomics reveals cellular heterogeneity and molecular stratification of cervical cancer. Communications Biology 5 (2022). https://doi.org:ARTN 120810.1038/s42003-022-04142-w

9. Luo, H. et al. Pan-cancer single-cell analysis reveals the heterogeneity and plasticity of cancer-associated fibroblasts in the tumor microenvironment. Nature Communications 13 (2022). https://doi.org:ARTN 661910.1038/s41467-022-34395-2

10. Sathe, A. et al. Single-Cell Genomic Characterization Reveals the Cellular Reprogramming of the Gastric Tumor Microenvironment. Clin Cancer Res 26, 2640-2653 (2020). https://doi.org:10.1158/1078-0432.CCR-19-3231

11. Kim, N. et al. Single-cell RNA sequencing demonstrates the molecular and cellular reprogramming of metastatic lung adenocarcinoma. Nat Commun 11, 2285 (2020). https://doi.org:10.1038/s41467-020-16164-1

12. Lambrechts, D. et al. Phenotype molding of stromal cells in the lung tumor microenvironment. Nat Med 24, 1277-1289 (2018). https://doi.org:10.1038/s41591-018-0096-5

13. Chen, S. J. et al. Single-cell analysis reveals transcriptomic remodellings in distinct cell types that contribute to human prostate cancer progression. Nature Cell Biology 23 (2021). https://doi.org:10.1038/s41556-020-00613-6

14. Ma, X. S. et al. Identification of a distinct luminal subgroup diagnosing and stratifying early stage prostate cancer by tissue-based single-cell RNA sequencing. Molecular Cancer 19 (2020). https://doi.org:ARTN 14710.1186/s12943-020-01264-9

15. Luo, H. et al. Characterizing dedifferentiation of thyroid cancer by integrated analysis. Science Advances 7 (2021). https://doi.org:ARTN eabf365710.1126/sciadv.abf3657

16. Chen, Z. H. et al. Single-cell RNA sequencing highlights the role of inflammatory cancer-associated fibroblasts in bladder urothelial carcinoma. Nature Communications 11 (2020). https://doi.org:ARTN 507710.1038/s41467-020-18916-5

17. Qian, J. B. et al. A pan-cancer blueprint of the heterogeneous tumor microenvironment revealed by single-cell profiling. Cell Research 30, 745-762 (2020). https://doi.org:10.1038/s41422-020-0355-0

18. Zhang, M. et al. Single-cell transcriptomic architecture and intercellular crosstalk of human intrahepatic cholangiocarcinoma. Journal of Hepatology 73, 1118-1130 (2020). https://doi.org:10.1016/j.jhep.2020.05.039

19. Peng, J. Y. et al. Single-cell RNA-seq highlights intra-tumoral heterogeneity and malignant progression in pancreatic ductal adenocarcinoma. Cell Research 29, 725-738 (2019). https://doi.org:10.1038/s41422-019-0195-y

20. Lin, W. et al. Single-cell transcriptome analysis of tumor and stromal compartments of pancreatic ductal adenocarcinoma primary tumors and metastatic lesions. Genome Medicine 12 (2020). https://doi.org:ARTN 8010.1186/s13073-020-00776-9


### Bulk RNA-seq 

Bulk RNA-seq was downloaded from The Cancer Genome Atlas (TCGA) project for processed data sets (https://portal.gdc.cancer.gov/, https://labs.icahn.mssm.edu/minervalab/resources/data-ark/tcga/). 



## Software 

### scRNA-seq

Analyses for single-cell RNA seq will be conducted using R (version 4.3.1) and Python (version 3.10.9). 

In Python, we will use the packages such as Scanpy (v.1.9.5), Pandas (v.2.0.0), Conda (v.4.11.0), NumPy (v.1.24.2), Scipy (v.1.10.1), and scVI Python package (scvi-tools; v.1.0.4) for data analysis.

In R, we will use the packages ggplot2 (v.3.3.5), ggpubr (v.0.6.0), and ggrepel (v.0.9.2), and ComplexHeatmap (v.2.11.1) for data visualization. 


### Bulk RNA-seq

Analyses for bulk RNA-seq will be conducted using R (version 4.3.1). 

In R, we will use the survminer package (v.0.4.9) to evaluate log-rank or Cox statistics and visualize using Kaplan–Meier survival curves. Also, further downstream analysis will be performed using DESeq2 (v.1.44.0) to retrieve differentially expressed genes and GO-terms. 


## Data processing proposal 

We will first download all the datasets and intially work on the processing the sc-RNA seq raw data. 

1. Downloading all datasets (both sc-RNA and bulk-RNA seq) from their respective locations and uploading onto the cluster. 

2. Running quality control and pre-processing for the 20 scRNA-seq datasets. 

    - We will use the Scanpy package (version 1.9.5) to perform quality control filtering and integration of the datasets. 
    - Initial filtering criteria will be: (1) confirmation that information was available for all 9 Y signature genes, (2) cells had greater than 200 detected genes and (3) the mitochondrial gene counts were below 20%
    - Second quality filtering criteria will be: (1) remove barcodes that fall into any of the following categories -  (a) possible debris with too few genes expressed (<400) and too few UMIs (<800) + (b) possibility of duplicate cells based on genes expressed (>5500) or UMIs (>5000)
    - Count matrices and AnnData objects will be then combined using a concatenate function, and raw counts will be saved for each cell to facilitate further analysis. 
    - Final quality filtering will be removing non-tumor cells and normalizing the counts to log transcripts per million (TPM) units using the “sc.pp.normalize_total” function, followed by log transformation using the “sc.pp.log1p” function.


3. Combining and batch effect correction on the processed and filtered 20 scRNA-seq datasets.  

    - We will use the scVI Python package (scvi-tools; v.1.0.4) to batch correct and the scVI model will be trained on the scRNA-seq data to consider samples as covariates.
    - If multiple batches are present, the corrected data will be integrated together. 
    - To assess if batch correction was done properly, we will examine the reduction in batch-specific variation in terms of signal presence. 

4. Downstream analysis (such as clustering, differential expression analysis, or trajectory inference) and visualization (such as 2D UMAP plots, illustrating cell types, batches, datasets, gender, organs, and cancer types) on the filtered and batch-correced 20 scRNA-seq datasets will be performed. 


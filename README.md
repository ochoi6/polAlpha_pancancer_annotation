# Pan-cancer and cell-type specific characterization of polymerase alpha using bulk and single-cell RNA-seq profiling 


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

Bulk The Cancer Genome Atlas (TCGA) project (https://portal.gdc.cancer.gov/). 


## Software 

### scRNA-seq

Analyses for single-cell RNA seq will be conducted using R (version 4.3.1) and Python (version 3.10.9). 

In Python, we will use the packages such as Scanpy (v.1.9.5), Pandas (v.2.0.0), Conda (v.4.11.0), NumPy (v.1.24.2), and Scipy (v.1.10.1) for data analysis.

In R, we will use the packages ggplot2 (v.3.3.5), ggpubr (v.0.6.0), and ggrepel (v.0.9.2), and ComplexHeatmap (v.2.11.1) for data visualization. 


### Bulk RNA-seq

Analyses for bulk RNA-seq will be conducted using R (version 4.3.1). 

In R, we will use the survminer package (v.0.4.9) to evaluate log-rank or Cox statistics and visualize using Kaplan–Meier survival curves. Also, 


## Data processing 


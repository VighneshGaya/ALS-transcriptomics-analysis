# ALS-transcriptomics-analysis



\## ALS and TDP-43 Depletion: Comparative Transcriptomics



This project explores whether gene-expression changes associated with amyotrophic lateral sclerosis (ALS) show similarities to changes produced by TDP-43 depletion.



The analysis compares two publicly available gene-expression datasets from the NCBI Gene Expression Omnibus (GEO):



\- \[GSE76220](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE76220)

\- \[GSE121569](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE121569)



The analysis includes gene-level statistical testing, multiple-testing correction, gene matching between the datasets, comparison of expression changes, overlap and directional-agreement analysis, genes of interest, visualisation, and functional enrichment.



The aim is to explore whether gene-expression changes in ALS show similarities to those seen after TDP-43 depletion, which could suggest a possible biological link. TDP-43 dysfunction is already strongly associated with ALS, including loss of its normal nuclear function and abnormal accumulation in the cytoplasm. However, this analysis is exploratory and the datasets analysed here are not used to suggest that TDP-43 depletion causes ALS or to prove a causal relationship.



\## Notebook



`notebooks/ALS\_Transcriptomics.ipynb`



\## Requirements



```bash

pip install pandas numpy matplotlib seaborn scipy statsmodels scikit-learn mygene

```


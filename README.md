# Kaggle-Single_Cell_Integration
## GOAL: 
### In this competition, we predicted the variation of distribution of DNA, RNA and protein in the single cell  
## Background:
Genetic information goes from DNA to RNA to proteins. DNA must be accessible (ATAC data) to produce RNA (GEX data), which in turn is used as a template to produce proteins (ADT data). These processes are regulated by feedback, for example, a protein might bind DNA to prevent the production of more RNA. This genetic regulation is the basis of dynamic cellular processes that allow organisms to develop and adapt to changing environments.
## Dataset
DNA-RNA(Multiome) data and RNA-protein (CITEseq) data at 5 time points in 10 days tested by 4 volunteers.
## Evaluation
### Ranked by Pearson correlation coefficient
1. Correlations between DNA and RNA were calculated for each observation in the Multiome dataset
2. For each observation in the CITEseq dataset, we calculated the correlation between RNA and the predicted protein.  
3. The total score is the average of the relevant scores for each sample. If the predictions of the sample are all the same, the sample has a correlation score of -1.0
### Testset
1. **Public leader board:**  the difference is about volunteer, for example, the NO.13176 volunteer's data is not contained in the training set but in public test set.  

2. **Private leader board:** the difference is about date, for example, the seventh day's data is not contained in the training set but in private test set.

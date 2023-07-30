Assumes 'AML_datasets.RData' is in the working directory.

'proj_models_v03_14.ipynb'
Dataset 1. Develops 9 models. Looks at 2 ensembles of 3 models. 1 ensemble is applied
to Dataset 2. 
Does k fold validation. Feature selection on ttest and correlation.

'ensemble.test.DS2_v03_14.ipynb'
Three models created on data set 1 are tested on dataset 2 individually, and as ensemble.

Two of the files are genelists used by the models, from dataset 1:
-'fold1.100.ttest.csv'
-'rand50.of100.best.genes.csv'

Three of the RData files are different models:
-'model.rF.1.RData'
-'model.svm.lin.1.RData'
-'model.svm.rad.1.RData'

'proj-heatmap.ipynb'
Heatmap of the top 100 genes used for clustering patients, K-means, Rand Index

'proj-SVM-updated-1.ipynb'
The SVM code containing AML VS non-AML without feature selection, FAB VS Disease, and else

'proj-SVM-updated-2.ipynb'
The final SVM code containing AML VS non-AML with top 100 genes only.



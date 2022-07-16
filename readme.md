# Classification Modelling with R
This assignment will focus on building simple classification models for
**predicting fetal health** based on a number of clinical measurements known
as *cardiotocographic data*. 

The following introductory information was taken from the main
[Kaggle Dataset page](https://www.kaggle.com/andrewmvd/fetal-health-classification) for this data:

## Contents
All completed work for this project can be viewed in the html file [Classification Modelling with R](hw3_w22_classification_r_fetalhealth_ogbeborevans.html). The html file can be pulled from the repo or downloaded to your local device and viewed in a compatible browser.

The project was completed in R, and the code can be found in the [RMD](hw3_w22_classification_r_fetalhealth_ogbeborevans.Rmd) file.

The [source file](hw3_w22_classification_r_fetalhealth_problem.Rmd) for this project was created by Professor Mark Isken, SBA, Oakland University, Rochester, MI. USA.

You can learn much more about the study behind this dataset from the following
published paper:

* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6822315/

While in the original study and dataset, there were three classes for the
target variable (Normal, Suspect, Pathological), we will convert this to
a binary classification problem where 1 will be Suspect or Pathological and
0 will be Normal.
# MLDM_project
Final project for MLDM course. (kaggle competition) <br/>
My first competetition in Kaggle.<br/> 
The competition: Mechanisms of Action (MoA) Prediction <br/>
The link: https://www.kaggle.com/c/lish-moa/overview
# Overview of the project
Identify a protein target associated with a disease and develop a molecule that can modulate that protein target. MoA - biological activity of a given molecule.  
# Data
Training set consists of 23814 samples and 876 features(including id's of patients), target consists of 206 features. So it is multilabel classification task. <br/>
<li>Training features:</li> 
<li> g-0 - g-771 gene expression</li>
<li>c-0 -c-100 - cell viablility </li>
<li>cp_time - treatment duration(24, 48, 72 hours) </li>
<li>cp_dose - dose(high or low)</li>
<li>cp_type - sample treated with compounds or with control perturbation</li>
# Authors
Aslan Ubingazhibov - Data Science, Higher School of Economics, aubinagzhibov@edu.hse.ru <br/>
# Reference
https://www.kaggle.com/headsortails/explorations-of-action-moa-eda <br/>
https://www.kaggle.com/isaienkov/mechanisms-of-action-moa-prediction-eda <br/>
https://www.kaggle.com/namanj27/new-baseline-pytorch-moa <br/>
https://www.kaggle.com/yasufuminakama/moa-pytorch-nn-starter <br/>

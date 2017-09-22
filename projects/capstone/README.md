# Personalized Medicine: Redefining Cancer Treatment
https://www.kaggle.com/c/msk-redefining-cancer-treatment/data

The genetic testing is crucial us to understanding more about cancer, while the research has been slow due to significant amount of manual work, Therefore the Memorial Sloan Kettering Cancer Center (MSKCC)  proposed this competition on Kaggle as one of the item of the NIPS 2017 Competition Track [1].

There are many genetic mutations inside a cancer tumor, but only some mutations (drivers) contributing to the growth of the tumor. Currently, those drivers are captured manually. It is a really time-consuming task as the clinical pathologist need to classify every single genetic mutation based on evidence from the text-based clinical literature. Therefore it will be a natural language plus a classification problem.


## Datasets
Download here:
https://www.kaggle.com/c/msk-redefining-cancer-treatment/data

The dataset is expert-annotated and published by MSKCC. Those features are included because those are the evidence used by the experts. There are 3321 training samples and 5668 testing samples for tuning the model.


## Documents
The reports are located at the project root.
1. proposal.pdf
2. report.pdf


## Codes
All Code are located at /src directory
There are 3 notebooks:
1. /src/Exploratory data analysis.ipynb
2. /src/Comparison of Different Text Vectorization Methods.ipynb
3. /src/Model Refinement and Kaggle Submission.ipynb

The notebook 1 explores the given dataset and provide some description of the data.
The notebook 2 compares different NLP methods and visualize transformed vectors.
The notebbok 3 contains the whole pipeline of the final model.

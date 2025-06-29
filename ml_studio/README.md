# Machine Leaning Studio

In this repository you will find the data notebooks used for throughout for the AutoML and Jupyter Notebooks section. 

- The beginner notebook with how to build, train, and measure a deep neural network in a Jupyter notebook (./pytorch_demo.ipynb)
- The advanced notebook using the same code as in the above, with the exception of the training being run as a Azure ML job (./pytorch_aml.ipynb)
- The dataset used through the module. A nuemeric dataset from which to predict wine quality (./winequality.csv)

All files will need to be downloaded to your local computer and then uploaded to your Azure ML Studio workspace.

For the notebooks, this is very straightforward with an **add files** button within the file system structure in the notebooks section.

For the dataset, upload it through the data sub-section in **Assets**, following the portals instructions. Please choose the tabular format for this data when asked for the type under dropdown from **Dataset types (from Azure MLv1 APIs). The v2 mltable does not work with a standard csv file.

The origin of the wine quality dataset is from Kaggle and can be found [here](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset).
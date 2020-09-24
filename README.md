This is the code for the Spectral Biclustering tutorial on Kaggle Survey dataset available [here](https://nikolay-shenkov.github.io/blog/survey/clustering/umap/2020/09/19/clustering-kaggle-survey.html).

To run the analysis: 

#### Download the survey dataset.

Download the data from [Kaggle](https://www.kaggle.com/c/kaggle-survey-2019/data) and place it in the `data` directory.

#### Install requirements

You may wish to use a virtual environment for this.

```pip install -r requirements.txt```

If you have difficulty with some of the umap.plot requirements, see the UMAP [installation instructions](https://pypi.org/project/umap-learn/).

#### Run notebooks
First you need to run `preprocessing.ipynb` to generate the intermediate datasets.

The main clustering analysis (also shown in the tutorial) is in `clustering.ipynb`.

# Case study

*by Kai-Yang Lee*

### Content

This repository contains the case study "Document Clustering for News Articles". Four CSV-datafiles were provided to generate a model that clusters news articles into categories.
To tackle this challenge, TF-IDF vectorization and k-means was implemented in order to handle clustering of text contents. The implementation can be found in the notebook "Case_study.ipynb".
The provided data and all output images are stored in "data".

### Environment

The Python version 3.9.4 was used, which can be installed using pyenv in a virtual environment:

```
pyenv local 3.9.4
python -m venv .venv
source .venv/bin/activate
```

In order to install the required libraries, the following command line is recommended:

```
pip install -r requirements.txt
```

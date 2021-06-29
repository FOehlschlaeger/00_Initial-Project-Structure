# 00_Initial-Project-Structure
This is a dummy repository for standardized repository projects

## Description / Project Goal / Project Background

Project description on the topic of the project, its goal or a short overview, additionally with sources, references, links.
Initial project structure for a **standardized and more structured project kickoff** for github repositories. 

#### Sources

This slightly modified project structure is based on **http://drivendata.github.io/cookiecutter-data-science/** : 

├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   ├── raw            <- The original, immutable data dump.
│   └── tests          <- Data for testing purposes.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── release            <- Releasable versions of the script.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- Make this project pip installable with `pip install -e`
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.testrun.org

## Keywords
* Python
* Machine Learning
* Neural Networks
* Apache Kafka
* ...

## Programming Languages Used
* Python
* ...

## Tools / Libraries Used
* pandas
* scikit-learn
* tensorflow
* ...

## Personal  Approach / Idea / Concept / Steps
* EDA of the given data
* Data Visualization
* Building a model
* ...

## ToDo / Next steps
* Training of a neural network
* ...

## Conclusion / Remarks
* In this project I learned to ...

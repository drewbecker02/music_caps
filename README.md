# Music Caption Genre Classifier

This repository contains a notebook for preprocessing data and creating creating clssifiers using NLP to classify music genres based on descriptions of tracks. This code utlizes a dataset created by (Agostinelli et. al. 2023) containing ~5500 instances of descriptions of music clips. This dataset was orginally created for the MusicLM texg-to-audio model from Google. Each clip comes **AudioSet** dataset, a large audio dataset from Google research.

### REQUIREMENTS:
`python>=3.7, nltk>=3.8.1, sklearn>=1.2.2, imblearn>=0.10.1`

### OPTIONAL:
`scikit-learn-intelex>=2023.1.1`

### IMPORTANT:
This noteboook also requires access to `music-caps-public.csv` from https://www.kaggle.com/datasets/googleai/musiccaps and access to `ontology.json` file from the **AudioSet ontology** available at https://github.com/audioset/ontology.


## Getting Started

To run the notebook, first download `music-caps-public.csv` and `ontology.json` from the links provided **above**. Then, download `music_caps.ipynb` and follow the instructions to access the dataset and ontology files. After that, simply follow the notebook to preprocess the data and create classifiers! There are code blocks available for performing `Grid Search`, `SGD`, `Random Forest` and other classifiers, as well as visualizing the dataset, and vizualizing results. 

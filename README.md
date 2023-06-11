# Multimodal Fake News Classifier

## About

This is the project for identifying fake news from real news by using deep learning 
and a novel technique for multimodal fusion between the textual and visual
dimensions. The model is named **F**ake **N**ews **D**etection with **M**ulti **l**evel **A**ttention **(FND-MLA)**

## Layout of the project
* [Experiments](./Experiments) - This directory contains all the experiments conducted with Twitter
MediaEval and Weibo datasets on individual dimensions of text and images.
* [Analysis](./Analysis) - This directory contains the graphical analysis and t-SNE analysis
of the final models on both the datasets.
* [Diagrams](./model-architecture) - This directory has a notebook that has been used to
capture the deep-learning architecture of the various parts of FND-MLA.
* [Twitter-EDA](Twitter_multimodal_EDA.ipynb) - The EDA on Twitter MediaEval dataset. Also saves
the final training and test dataframes in _pickle_ files.
* [Weibo-EDA](Weibo_multimodal_EDA.ipynb) - The EDA on Weibo dataset. Also saves
  the final training and test dataframes in _pickle_ files.
* [Twitter-model](Twitter_multimodal_classifier_MHA_Luong_Regularized.ipynb) - FND-MLA final model on Twitter
dataset.
* [Weibo-model](Weibo_multimodal_classifier_MHA_Luong_Regularized.ipynb) - FND-MLA final model on Weibo
  dataset.
* [FND-MLA-LA For Twitter](Twitter_multimodal_classifier_Scaled_Attention.ipynb) - Part of Ablation
study on Twitter MediaEval dataset.
* [FND-MLA-LA For Weibo](Weibo_multimodal_classifier_Scaled_Attention.ipynb) - Part of Ablation
  study on Weibo dataset.
* [FND-MLA-MHA For Twitter](Twitter_multimodal_classifier.ipynb) - Part of Ablation
  study on Twitter MediaEval dataset.
* [FND-MLA-MHA For Weibo](Weibo_multimodal_classifier.ipynb) - Part of Ablation
    study on Weibo dataset.
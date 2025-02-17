Graph Feature Selection for Metabolite Recommendation
==========
 [![repo size](https://img.shields.io/github/repo-size/mamintoosi-papers-codes/GFS-for-Met-Rec.svg)](https://github.com/mamintoosi-papers-codes/GFS-for-Met-Rec/archive/master.zip)
 [![GitHub forks](https://img.shields.io/github/forks/mamintoosi-papers-codes/GFS-for-Met-Rec)](https://github.com/mamintoosi-papers-codes/GFS-for-Met-Rec/network)
[![GitHub issues](https://img.shields.io/github/issues/mamintoosi-papers-codes/GFS-for-Met-Rec)](https://github.com/mamintoosi-papers-codes/GFS-for-Met-Rec/issues)
[![GitHub license](https://img.shields.io/github/license/mamintoosi-papers-codes/GFS-for-Met-Rec)](https://github.com/mamintoosi-papers-codes/GFS-for-Met-Rec/blob/main/LICENSE)
 
 
A Python implementation of "Graph Feature Selection for Metabolite Recommendation" 
<p align="center">
  <img width="600" src="doc/fungal_metabolite_-_aflatoxin_b1.webp">
  <a href="https://www.thermofisher.com/blog/food/turbulent-flow-clean-up-for-plant-and-fungal-metabolite-screening/">Image Source</a>
</p>

### Abstract

<p align="justify">
Motivation: Every year tremendous experimental analysis has been done for evaluation of anti-cancer properties of plants. A good ranked list of potential anti-cancer plants which raised out of verified anti-cancer metabolites, reduces the time and cost for evaluating plants; otherwise, we charged for testing unrelated plants. Ranked list produced by analyzing plant-metabolite biological graphs are candidate for such situation. Graph nodes are ranked according to some graph features. A problem with this approach is how to select the good features of graphs. In this paper a metric used in information retrieval and recommender systems was employed for comparing two different ranked list. In an information retrieval system such as search engines, a good system should show the top results first. A metric named Average Precision (AP) is used here for discriminating different lists, resulted from different features. We build a network of similarity of plants according to their common metabolites. After that, with various combinations of the graph features, the plants are ranked. The subset of features which produces the ranked list with higher AP score is considered as the best features for anti-cancer plant recommendation.

Results:   The proposed method could be employed to select the best graph features in screening of anti-cancer plants from an unverified plants list. So that, the plant with higher score in the list have higher chance to have anti-cancer properties. Although, different graph features are applicable for anti-cancer plant recommendation in each cancer type.
</p>

This repository provides a Python implementation of GFS-for-Met-Rec as described in the draft paper:

> Graph Feature Selection for Metabolite Recommendation,
> Mahmood Amintoosi, Eisa Kohan
> 2022


### Requirements
The codebase is implemented in Python 3.7.11 on Google colab. 

### Run on Google Colab
https://colab.research.google.com/github/mamintoosi-papers-codes/GFS-for-Met-Rec/blob/master/GFS-for-Met-Rec.ipynb

### Datasets
<p align="justify">
All of the datasets used here are accessible from <em>data</em> folder.
</p>

### Results
The best graph features for Breast anti-cancer metabolite recommendation
![Stomach](results/FS_St_AC_Met_Plant_mc1_k1-9_apk.png)

The best graph features for Stomach anti-cancer metabolite recommendation
![Breast](results/FS_Br_AC_Met_Plant_mc1_k1-9_apk.png)

[![Github All Releases](https://img.shields.io/github/downloads/mamintoosi-papers-codes/GFS-for-Met-Rec/total.svg)]()

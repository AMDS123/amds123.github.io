---
layout: post
title: "Drug-Drug Interaction Prediction Based on Knowledge Graph Embeddings and Convolutional-LSTM Network"
date: 2019-08-04 07:19:21
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding CNN RNN Prediction
author: Md. Rezaul Karim, Michael Cochez, Joao Bosco Jares, Mamtaz Uddin, Oya Beyan, Stefan Decker
mathjax: true
---

* content
{:toc}

##### Abstract
Interference between pharmacological substances can cause serious medical injuries. Correctly predicting so-called drug-drug interactions (DDI) does not only reduce these cases but can also result in a reduction of drug development cost. Presently, most drug-related knowledge is the result of clinical evaluations and post-marketing surveillance; resulting in a limited amount of information. Existing data-driven prediction approaches for DDIs typically rely on a single source of information, while using information from multiple sources would help improve predictions. Machine learning (ML) techniques are used, but the techniques are often unable to deal with skewness in the data. Hence, we propose a new ML approach for predicting DDIs based on multiple data sources. For this task, we use 12,000 drug features from DrugBank, PharmGKB, and KEGG drugs, which are integrated using Knowledge Graphs (KGs). To train our prediction model, we first embed the nodes in the graph using various embedding approaches. We found that the best performing combination was a ComplEx embedding method creating using PyTorch-BigGraph (PBG) with a Convolutional-LSTM network and classic machine learning-based prediction models. The model averaging ensemble method of three best classifiers yields up to 0.94, 0.92, 0.80 for AUPR, F1-score, and MCC, respectively during 5-fold cross-validation tests.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01288](http://arxiv.org/abs/1908.01288)

##### PDF
[http://arxiv.org/pdf/1908.01288](http://arxiv.org/pdf/1908.01288)


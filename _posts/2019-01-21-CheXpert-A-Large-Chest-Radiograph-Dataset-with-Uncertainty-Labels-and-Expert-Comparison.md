---
layout: post
title: "CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison"
date: 2019-01-21 18:41:59
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning Detection
author: Jeremy Irvin, Pranav Rajpurkar, Michael Ko, Yifan Yu, Silviana Ciurea-Ilcus, Chris Chute, Henrik Marklund, Behzad Haghgoo, Robyn Ball, Katie Shpanskaya, Jayne Seekins, David A. Mong, Safwan S. Halabi, Jesse K. Sandberg, Ricky Jones, David B. Larson, Curtis P. Langlotz, Bhavik N. Patel, Matthew P. Lungren, Andrew Y. Ng
mathjax: true
---

* content
{:toc}

##### Abstract
Large, labeled datasets have driven deep learning methods to achieve expert-level performance on a variety of medical imaging tasks. We present CheXpert, a large dataset that contains 224,316 chest radiographs of 65,240 patients. We design a labeler to automatically detect the presence of 14 observations in radiology reports, capturing uncertainties inherent in radiograph interpretation. We investigate different approaches to using the uncertainty labels for training convolutional neural networks that output the probability of these observations given the available frontal and lateral radiographs. On a validation set of 200 chest radiographic studies which were manually annotated by 3 board-certified radiologists, we find that different uncertainty approaches are useful for different pathologies. We then evaluate our best model on a test set composed of 500 chest radiographic studies annotated by a consensus of 5 board-certified radiologists, and compare the performance of our model to that of 3 additional radiologists in the detection of 5 selected pathologies. On Cardiomegaly, Edema, and Pleural Effusion, the model ROC and PR curves lie above all 3 radiologist operating points. We release the dataset to the public as a standard benchmark to evaluate performance of chest radiograph interpretation models. 
 The dataset is freely available at https://stanfordmlgroup.github.io/competitions/chexpert .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07031](http://arxiv.org/abs/1901.07031)

##### PDF
[http://arxiv.org/pdf/1901.07031](http://arxiv.org/pdf/1901.07031)


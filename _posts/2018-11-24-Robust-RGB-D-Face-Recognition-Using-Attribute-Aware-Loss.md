---
layout: post
title: "Robust RGB-D Face Recognition Using Attribute-Aware Loss"
date: 2018-11-24 15:07:12
categories: arXiv_CV
tags: arXiv_CV Face CNN Relation Recognition Face_Recognition
author: Luo Jiang, Juyong Zhang, Bailin Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Existing convolutional neural network (CNN) based face recognition algorithms typically learn a discriminative feature mapping, using a loss function that enforces separation of features from different classes and/or aggregation of features within the same class. However, they may suffer from bias in the training data such as uneven sampling density, because they optimize the adjacency relationship of the learned features without considering the proximity of the underlying faces. Moreover, since they only use facial images for training, the learned feature mapping may not correctly indicate the relationship of other attributes such as gender and ethnicity, which can be important for some face recognition applications. In this paper, we propose a new CNN-based face recognition approach that incorporates such attributes into the training process. Using an attribute-aware loss function that regularizes the feature mapping using attribute proximity, our approach learns more discriminative features that are correlated with the attributes. We train our face recognition model on a large-scale RGB-D data set with over 100K identities captured under real application conditions. By comparing our approach with other methods on a variety of experiments, we demonstrate that depth channel and attribute-aware loss greatly improve the accuracy and robustness of face recognition.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09847](https://arxiv.org/abs/1811.09847)

##### PDF
[https://arxiv.org/pdf/1811.09847](https://arxiv.org/pdf/1811.09847)


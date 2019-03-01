---
layout: post
title: "Channel Max Pooling Layer for Fine-Grained Vehicle Classification"
date: 2019-02-14 14:47:04
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Zhanyu Ma, Dongliang Chang, Xiaoxu Li
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks have recently shown excellent performance on Fine-Grained Vehicle Classification. Based on these existing works, we consider that the back-probation algorithm does not focus on extracting less discriminative feature as much as possible, but focus on that the loss function equals zero. Intuitively, if we can learn less discriminative features, and these features still could fit the training data well, the generalization ability of neural network could be improved. Therefore, we propose a new layer which is placed between fully connected layers and convolutional layers, called as Chanel Max Pooling. The proposed layer groups the features map first and then compress each group into a new feature map by computing maximum of pixels with same positions in the group of feature maps. Meanwhile, the proposed layer has an advantage that it could help neural network reduce massive parameters. Experimental results on two fine-grained vehicle datasets, the Stanford Cars-196 dataset and the Comp Cars dataset, demonstrate that the proposed layer could improve classification accuracies of deep neural networks on fine-grained vehicle classification in the situation that a massive of parameters are reduced. Moreover, it has a competitive performance with the-state-of-art performance on the two datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11107](http://arxiv.org/abs/1902.11107)

##### PDF
[http://arxiv.org/pdf/1902.11107](http://arxiv.org/pdf/1902.11107)


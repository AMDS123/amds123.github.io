---
layout: post
title: "An Effective Label Noise Model for DNN Text Classification"
date: 2019-03-18 15:27:50
categories: arXiv_CL
tags: arXiv_CL Regularization Attention Text_Classification CNN Image_Classification Classification
author: Ishan Jindal, Daniel Pressel, Brian Lester, Matthew Nokleby
mathjax: true
---

* content
{:toc}

##### Abstract
Because large, human-annotated datasets suffer from labeling errors, it is crucial to be able to train deep neural networks in the presence of label noise. While training image classification models with label noise have received much attention, training text classification models have not. In this paper, we propose an approach to training deep networks that is robust to label noise. This approach introduces a non-linear processing layer (noise model) that models the statistics of the label noise into a convolutional neural network (CNN) architecture. The noise model and the CNN weights are learned jointly from noisy training data, which prevents the model from overfitting to erroneous labels. Through extensive experiments on several text classification datasets, we show that this approach enables the CNN to learn better sentence representations and is robust even to extreme label noise. We find that proper initialization and regularization of this noise model is critical. Further, by contrast to results focusing on large batch sizes for mitigating label noise for image classification, we find that altering the batch size does not have much effect on classification performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07507](http://arxiv.org/abs/1903.07507)

##### PDF
[http://arxiv.org/pdf/1903.07507](http://arxiv.org/pdf/1903.07507)


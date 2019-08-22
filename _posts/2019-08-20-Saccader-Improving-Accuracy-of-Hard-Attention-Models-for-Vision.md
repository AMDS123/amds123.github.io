---
layout: post
title: "Saccader: Improving Accuracy of Hard Attention Models for Vision"
date: 2019-08-20 23:40:21
categories: arXiv_CV
tags: arXiv_CV Attention CNN Image_Classification Optimization Classification Prediction
author: Gamaleldin F. Elsayed, Simon Kornblith, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep convolutional neural networks achieve state-of-the-art performance across nearly all image classification tasks, they are often regarded as black boxes. Because they compute a nonlinear function of the entire input image, their decisions are difficult to interpret. One approach that offers some level of interpretability by design is \textit{hard attention}, which selects only relevant portions of the image. However, training hard attention models with only class label supervision is challenging, and hard attention has proved difficult to scale to complex datasets. Here, we propose a novel hard attention model, which we term Saccader, as well as a self-supervised pretraining procedure for this model that does not suffer from optimization challenges. Through pretraining and policy gradient optimization, the Saccader model estimates the relevance of different image patches to the downstream task, and uses a novel cell to select patches to classify at different times. Our approach achieves high accuracy on ImageNet while providing more interpretable predictions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07644](http://arxiv.org/abs/1908.07644)

##### PDF
[http://arxiv.org/pdf/1908.07644](http://arxiv.org/pdf/1908.07644)


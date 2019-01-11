---
layout: post
title: "Local Learning with Deep and Handcrafted Features for Facial Expression Recognition"
date: 2019-01-10 12:26:07
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge CNN Recognition
author: Mariana-Iuliana Georgescu, Radu Tudor Ionescu, Marius Popescu
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach that combines automatic features learned by convolutional neural networks (CNN) and handcrafted features computed by the bag-of-visual-words (BOVW) model in order to achieve state-of-the-art results in facial expression recognition. To obtain automatic features, we experiment with multiple CNN architectures, pre-trained models and training procedures, e.g. Dense-Sparse-Dense. After fusing the two types of features, we employ a local learning framework to predict the class label for each test image. The local learning framework is based on three steps. First, a k-nearest neighbors model is applied for selecting the nearest training samples for an input test image. Second, a one-versus-all Support Vector Machines (SVM) classifier is trained on the selected training samples. Finally, the SVM classifier is used for predicting the class label only for the test image it was trained for. Although we used local learning in combination with handcrafted features in our previous work, to the best of our knowledge, local learning has never been employed in combination with deep features. The experiments on the 2013 Facial Expression Recognition (FER) Challenge data set and the FER+ data set demonstrate that our approach achieves state-of-the-art results. With a top accuracy of 75.42% on the FER 2013 data set and 87.76% on the FER+ data set, we surpass all competition by more than 2% on both data sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.10892](http://arxiv.org/abs/1804.10892)

##### PDF
[http://arxiv.org/pdf/1804.10892](http://arxiv.org/pdf/1804.10892)


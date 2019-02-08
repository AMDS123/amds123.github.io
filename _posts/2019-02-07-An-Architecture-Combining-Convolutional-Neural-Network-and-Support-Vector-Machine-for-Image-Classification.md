---
layout: post
title: "An Architecture Combining Convolutional Neural Network and Support Vector Machine for Image Classification"
date: 2019-02-07 06:25:08
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Abien Fred Agarap
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) are similar to "ordinary" neural networks in the sense that they are made up of hidden layers consisting of neurons with "learnable" parameters. These neurons receive inputs, performs a dot product, and then follows it with a non-linearity. The whole network expresses the mapping between raw image pixels and their class scores. Conventionally, the Softmax function is the classifier used at the last layer of this network. However, there have been studies (Alalshekmubarak and Smith, 2013; Agarap, 2017; Tang, 2013) conducted to challenge this norm. The cited studies introduce the usage of linear support vector machine (SVM) in an artificial neural network architecture. This project is yet another take on the subject, and is inspired by (Tang, 2013). Empirical data has shown that the CNN-SVM model was able to achieve a test accuracy of ~99.04% using the MNIST dataset (LeCun, Cortes, and Burges, 2010). On the other hand, the CNN-Softmax was able to achieve a test accuracy of ~99.23% using the same dataset. Both models were also tested on the recently-published Fashion-MNIST dataset (Xiao, Rasul, and Vollgraf, 2017), which is suppose to be a more difficult image classification dataset than MNIST (Zalandoresearch, 2017). This proved to be the case as CNN-SVM reached a test accuracy of ~90.72%, while the CNN-Softmax reached a test accuracy of ~91.86%. The said results may be improved if data preprocessing techniques were employed on the datasets, and if the base CNN model was a relatively more sophisticated than the one used in this study.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.03541](http://arxiv.org/abs/1712.03541)

##### PDF
[http://arxiv.org/pdf/1712.03541](http://arxiv.org/pdf/1712.03541)


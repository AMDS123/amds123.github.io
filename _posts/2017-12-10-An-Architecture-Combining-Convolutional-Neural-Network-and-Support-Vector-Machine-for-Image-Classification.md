---
layout: post
title: "An Architecture Combining Convolutional Neural Network and Support Vector Machine for Image Classification"
date: 2017-12-10 14:50:28
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
卷积神经网络（CNN）与“普通”神经网络类似，它们是由具有“可学习”参数的神经元组成的隐藏层组成的。这些神经元接收输入，执行一个点积，然后用非线性跟随它。整个网络表示原始图像像素与其类别分数之间的映射。通常，Softmax功能是在该网络的最后一层使用的分类器。然而，有一些研究（Alalshekmubarak和Smith，2013; Agarap，2017; Tang，2013）进行挑战这个规范。引用的研究介绍了线性支持向量机（SVM）在人工神经网络体系结构中的用法。这个项目是另一个主题，受到启发（Tang，2013）。经验数据表明，使用MNIST数据集（LeCun，Cortes和Burges，2010），CNN-SVM模型能够达到〜99.04％的测试精度。另一方面，使用相同的数据集，CNN-Softmax能够达到〜99.23％的测试精度。这两种模型也都在最近发表的Fashion-MNIST数据集（Xiao，Rasul和Vollgraf，2017）上进行了测试，该数据集比MNIST（Zalandoresearch，2017）假设是一个更困难的图像分类数据集。事实证明，CNN-SVM达到了〜90.72％的测试精度，而CNN-Softmax达到了〜91.86％的测试精度。如果在数据集上使用数据预处理技术，并且基础CNN模型比本研究中使用的基础CNN模型更复杂，则可以改进上述结果。

##### URL
[http://arxiv.org/abs/1712.03541](http://arxiv.org/abs/1712.03541)

##### PDF
[http://arxiv.org/pdf/1712.03541](http://arxiv.org/pdf/1712.03541)


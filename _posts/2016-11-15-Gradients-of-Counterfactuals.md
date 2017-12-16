---
layout: post
title: "Gradients of Counterfactuals"
date: 2016-11-15 19:55:26
categories: arXiv_CV
tags: arXiv_CV GAN RNN Language_Model Prediction Recognition
author: Mukund Sundararajan, Ankur Taly, Qiqi Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Gradients have been used to quantify feature importance in machine learning models. Unfortunately, in nonlinear deep networks, not only individual neurons but also the whole network can saturate, and as a result an important input feature can have a tiny gradient. We study various networks, and observe that this phenomena is indeed widespread, across many inputs. We propose to examine interior gradients, which are gradients of counterfactual inputs constructed by scaling down the original input. We apply our method to the GoogleNet architecture for object recognition in images, as well as a ligand-based virtual screening network with categorical features and an LSTM based language model for the Penn Treebank dataset. We visualize how interior gradients better capture feature importance. Furthermore, interior gradients are applicable to a wide variety of deep networks, and have the attribution property that the feature importance scores sum to the the prediction score. Best of all, interior gradients can be computed just as easily as gradients. In contrast, previous methods are complex to implement, which hinders practical adoption.

##### Abstract (translated by Google)
渐变已被用来量化机器学习模型中的特征重要性。不幸的是，在非线性深度网络中，不仅单个神经元而且整个网络都会饱和，因此重要的输入特征可能会有一个很小的梯度。我们研究各种网络，并观察到这种现象在许多输入中确实是广泛的。我们建议检查内部梯度，即通过缩小原始输入构建的反事实输入的梯度。我们将我们的方法应用到GoogleNet架构中，用于图像中的对象识别，以及基于配体的具有分类特征的虚拟筛选网络和Penn Treebank数据集的基于LSTM的语言模型。我们想象如何内部渐变更好地捕捉功能的重要性。此外，内部梯度适用于各种深度网络，并具有特征重要性分数与预测分数相加的属性。最重要的是，内部渐变可以像渐变一样容易地计算出来。相反，以前的方法实施起来很复杂，这阻碍了实际的采用。

##### URL
[https://arxiv.org/abs/1611.02639](https://arxiv.org/abs/1611.02639)

##### PDF
[https://arxiv.org/pdf/1611.02639](https://arxiv.org/pdf/1611.02639)


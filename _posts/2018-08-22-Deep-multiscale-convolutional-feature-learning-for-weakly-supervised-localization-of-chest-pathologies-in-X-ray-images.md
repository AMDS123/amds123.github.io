---
layout: post
title: "Deep multiscale convolutional feature learning for weakly supervised localization of chest pathologies in X-ray images"
date: 2018-08-22 06:08:45
categories: arXiv_CV
tags: arXiv_CV Attention Weakly_Supervised CNN Classification
author: Suman Sedai, Dwarikanath Mahapatra, Zongyuan Ge, Rajib Chakravorty, Rahil Garnavi
mathjax: true
---

* content
{:toc}

##### Abstract
Localization of chest pathologies in chest X-ray images is a challenging task because of their varying sizes and appearances. We propose a novel weakly supervised method to localize chest pathologies using class aware deep multiscale feature learning. Our method leverages intermediate feature maps from CNN layers at different stages of a deep network during the training of a classification model using image level annotations of pathologies. During the training phase, a set of \emph{layer relevance weights} are learned for each pathology class and the CNN is optimized to perform pathology classification by convex combination of feature maps from both shallow and deep layers using the learned weights. During the test phase, to localize the predicted pathology, the multiscale attention map is obtained by convex combination of class activation maps from each stage using the \emph{layer relevance weights} learned during the training phase. We have validated our method using 112000 X-ray images and compared with the state-of-the-art localization methods. We experimentally demonstrate that the proposed weakly supervised method can improve the localization performance of small pathologies such as nodule and mass while giving comparable performance for bigger pathologies e.g., Cardiomegaly

##### Abstract (translated by Google)
胸部X射线图像中胸部病变的定位是一项具有挑战性的任务，因为它们的大小和外观各不相同。我们提出了一种新的弱监督方法，使用类感知深度多尺度特征学习来定位胸部病理。我们的方法在使用病理的图像级注释训练分类模型期间利用来自深度网络的不同阶段的CNN层的中间特征图。在训练阶段期间，针对每个病理类学习一组\ emph {层相关性权重}，并且CNN被优化以使用所学习的权重通过来自浅层和深层的特征图的凸组合来执行病理学分类。在测试阶段期间，为了定位预测的病理学，通过使用在训练阶段期间学习的\ emph {层相关性权重}来自每个阶段的类激活图的凸组合来获得多尺度注意力图。我们使用112000 X射线图像验证了我们的方法，并与最先进的定位方法进行了比较。我们通过实验证明，所提出的弱监督方法可以改善小病理（如结节和肿块）的定位性能，同时为更大的病理学提供可比较的性能，例如Cardiomegaly

##### URL
[http://arxiv.org/abs/1808.08280](http://arxiv.org/abs/1808.08280)

##### PDF
[http://arxiv.org/pdf/1808.08280](http://arxiv.org/pdf/1808.08280)


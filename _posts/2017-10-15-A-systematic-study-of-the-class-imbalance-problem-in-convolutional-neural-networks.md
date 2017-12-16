---
layout: post
title: "A systematic study of the class imbalance problem in convolutional neural networks"
date: 2017-10-15 19:01:43
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Mateusz Buda, Atsuto Maki, Maciej A. Mazurowski
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks (CNNs) and compare frequently used methods to address the issue. Class imbalance is a common problem that has been comprehensively studied in classical machine learning, yet very limited systematic research is available in the context of deep learning. In our study, we use three benchmark datasets of increasing complexity, MNIST, CIFAR-10 and ImageNet, to investigate the effects of imbalance on classification and perform an extensive comparison of several methods to address the issue: oversampling, undersampling, two-phase training, and thresholding that compensates for prior class probabilities. Our main evaluation metric is area under the receiver operating characteristic curve (ROC AUC) adjusted to multi-class tasks since overall accuracy metric is associated with notable difficulties in the context of imbalanced data. Based on results from our experiments we conclude that (i) the effect of class imbalance on classification performance is detrimental; (ii) the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling; (iii) oversampling should be applied to the level that totally eliminates the imbalance, whereas undersampling can perform better when the imbalance is only removed to some extent; (iv) as opposed to some classical machine learning models, oversampling does not necessarily cause overfitting of CNNs; (v) thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest.

##### Abstract (translated by Google)
在本研究中，我们系统地研究了类不平衡对卷积神经网络（CNN）分类性能的影响，并比较了常用的方法来解决这个问题。类别失衡是经典机器学习中已经被广泛研究的一个常见问题，然而在深度学习的背景下，非常有限的系统研究是可行的。在我们的研究中，我们使用复杂度越来越高的三个基准数据集，MNIST，CIFAR-10和ImageNet来研究不平衡对分类的影响，并进行了多种方法的广泛比较以解决这个问题：过采样，欠采样，两阶段训练，和阈值补偿前类概率。我们的主要评估指标是根据受试者工作特征曲线（ROC AUC）调整为多类任务的面积，因为总体准确性度量与不平衡数据背景下的显着困难相关联。基于我们实验的结果，我们得出结论：（i）类别不平衡对分类性能的影响是有害的; （2）解决在几乎所有分析情景中出现占主导地位的阶级失衡的方法都是过度抽样; （iii）过度取样应用于完全消除不平衡的水平，而不平衡仅在一定程度上被消除时，欠取样才能更好地发挥作用; （iv）与一些经典的机器学习模型相反，过采样不一定会导致CNN的过拟合; （v）当适当分类的个案总数受关注时，应使用阈值来补偿先前的概率。

##### URL
[https://arxiv.org/abs/1710.05381](https://arxiv.org/abs/1710.05381)

##### PDF
[https://arxiv.org/pdf/1710.05381](https://arxiv.org/pdf/1710.05381)


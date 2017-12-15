---
layout: post
title: "Minimally Supervised Feature Selection for Classification"
date: 2015-12-09 19:49:29
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification
author: Alexandra Maria Radu
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of the highly increasing number of features that are available nowadays we design a robust and fast method for feature selection. The method tries to select the most representative features that are independent from each other, but are strong together. We propose an algorithm that requires very limited labeled data (as few as one labeled frame per class) and can accommodate as many unlabeled samples. We also present here the supervised approach from which we started. We compare our two formulations with established methods like AdaBoost, SVM, Lasso, Elastic Net and FoBa and show that our method is much faster and it has constant training time. Moreover, the unsupervised approach outperforms all the methods with which we compared and the difference might be quite prominent. The supervised approach is in most cases better than the other methods, especially when the number of training shots is very limited. All that the algorithm needs is to choose from a pool of positively correlated features. The methods are evaluated on the Youtube-Objects dataset of videos and on MNIST digits dataset, while at training time we also used features obtained on CIFAR10 dataset and others pre-trained on ImageNet dataset. Thereby, we also proved that transfer learning is useful, even though the datasets differ very much: from low-resolution centered images from 10 classes, to high-resolution images with objects from 1000 classes occurring in different regions of the images or to very difficult videos with very high intraclass variance. 7

##### Abstract (translated by Google)
在现在可用的功能数量大量增加的情况下，我们设计了一种强大而快速的特征选择方法。该方法试图选择相互独立，但相辅相成的最具代表性的特征。我们提出一种算法，要求标记数据非常有限（每个类只有一个带标记的帧），并且可以容纳很多未标记的样本。我们在这里还介绍了我们开始的监督方法。我们将两个公式与AdaBoost，SVM，Lasso，Elastic Net和FoBa等已有方法进行比较，结果表明我们的方法速度更快，而且训练时间更长。而且，无监督方法胜过了我们所比较的所有方法，差异可能相当突出。监督方法在大多数情况下比其他方法更好，特别是当训练镜头的数量非常有限时。算法所需要的是从正相关特征池中进行选择。在视频的Youtube-Objects数据集和MNIST数字数据集上评估方法，而在训练时，我们还使用在CIFAR10数据集上获得的特征以及在ImageNet数据集上预先训练的特征。因此，我们也证明了转移学习是有用的，尽管数据集有很大的不同：从10个类的低分辨率中心图像到1000个不同类别的对象出现在图像不同区域的高分辨率图像，或者是非常困难的视频具有很高的组内差异。 7

##### URL
[https://arxiv.org/abs/1512.03019](https://arxiv.org/abs/1512.03019)

##### PDF
[https://arxiv.org/pdf/1512.03019](https://arxiv.org/pdf/1512.03019)


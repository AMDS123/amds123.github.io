---
layout: post
title: "Why do deep convolutional networks generalize so poorly to small image transformations?"
date: 2018-05-30 18:56:33
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Aharon Azulay, Yair Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional network architectures are often assumed to guarantee generalization for small image translations and deformations. In this paper we show that modern CNNs (VGG16, ResNet50, and InceptionResNetV2) can drastically change their output when an image is translated in the image plane by a few pixels, and that this failure of generalization also happens with other realistic small image transformations. Furthermore, the deeper the network the more we see these failures to generalize. We show that these failures are related to the fact that the architecture of modern CNNs ignores the classical sampling theorem so that generalization is not guaranteed. We also show that biases in the statistics of commonly used image datasets makes it unlikely that CNNs will learn to be invariant to these transformations. Taken together our results suggest that the performance of CNNs in object recognition falls far short of the generalization capabilities of humans.

##### Abstract (translated by Google)
深卷积网络体系结构通常被假定为保证小图像平移和变形的一般化。在本文中，我们展示现代CNN（VGG16，ResNet50和InceptionResNetV2）可以在图像在像平面上平移几个像素时大幅改变它们的输出，并且这种泛化的失败也会发生在其他实际的小图像变换中。而且，网络越深，我们越能看到这些失败的概括。我们表明，这些失败与现代CNN的体系结构忽略了经典采样定理的事实有关，因此不能保证泛化。我们还表明，常用图像数据集的统计偏差使得CNN不太可能学会对这些转换不变。综合考虑，我们的结果表明，CNNs在物体识别中的表现远不及人类的泛化能力。

##### URL
[http://arxiv.org/abs/1805.12177](http://arxiv.org/abs/1805.12177)

##### PDF
[http://arxiv.org/pdf/1805.12177](http://arxiv.org/pdf/1805.12177)


---
layout: post
title: "DeepProposal: Hunting Objects by Cascading Deep Convolutional Layers"
date: 2015-10-15 08:34:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Amir Ghodrati, Ali Diba, Marco Pedersoli, Tinne Tuytelaars, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we evaluate the quality of the activation layers of a convolutional neural network (CNN) for the gen- eration of object proposals. We generate hypotheses in a sliding-window fashion over different activation layers and show that the final convolutional layers can find the object of interest with high recall but poor localization due to the coarseness of the feature maps. Instead, the first layers of the network can better localize the object of interest but with a reduced recall. Based on this observation we design a method for proposing object locations that is based on CNN features and that combines the best of both worlds. We build an inverse cascade that, going from the final to the initial convolutional layers of the CNN, selects the most promising object locations and refines their boxes in a coarse-to-fine manner. The method is efficient, because i) it uses the same features extracted for detection, ii) it aggregates features using integral images, and iii) it avoids a dense evaluation of the proposals due to the inverse coarse-to-fine cascade. The method is also accurate; it outperforms most of the previously proposed object proposals approaches and when plugged into a CNN-based detector produces state-of-the- art detection performance.

##### Abstract (translated by Google)
在本文中，我们评估卷积神经网络（CNN）活化层的质量，以生成目标提议。我们在不同的激活层上以滑动窗口方式产生假设，并且显示最终的卷积层可以由于特征映射的粗糙度而找到具有高回忆但是差的局部化的感兴趣对象。相反，网络的第一层可以更好地定位感兴趣的对象，但回忆减少。基于这一观察，我们设计了一种提出基于CNN特征的对象位置的方法，该方法结合了两者的优点。我们建立一个反向级联，从CNN的最终卷积层到最初的卷积层，选择最有前景的对象位置，并以粗到细的方式细化它们的方框。该方法是有效的，因为：i）它使用提取用于检测的相同特征，ii）它使用积分图像来聚合特征，以及iii）由于反转的粗到细级联，避免了提议的密集评估。该方法也是准确的;它胜过了以前提出的大多数对象提议方法，并且当插入到基于CNN的检测器中时，产生了最先进的检测性能。

##### URL
[https://arxiv.org/abs/1510.04445](https://arxiv.org/abs/1510.04445)

##### PDF
[https://arxiv.org/pdf/1510.04445](https://arxiv.org/pdf/1510.04445)


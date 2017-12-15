---
layout: post
title: "DeepProposals: Hunting Objects and Actions by Cascading Deep Convolutional Layers"
date: 2016-06-15 09:57:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Amir Ghodrati, Ali Diba, Marco Pedersoli, Tinne Tuytelaars, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a new method for generating object and action proposals in images and videos is proposed. It builds on activations of different convolutional layers of a pretrained CNN, combining the localization accuracy of the early layers with the high informative-ness (and hence recall) of the later layers. To this end, we build an inverse cascade that, going backward from the later to the earlier convolutional layers of the CNN, selects the most promising locations and refines them in a coarse-to-fine manner. The method is efficient, because i) it re-uses the same features extracted for detection, ii) it aggregates features using integral images, and iii) it avoids a dense evaluation of the proposals thanks to the use of the inverse coarse-to-fine cascade. The method is also accurate. We show that our DeepProposals outperform most of the previously proposed object proposal and action proposal approaches and, when plugged into a CNN-based object detector, produce state-of-the-art detection performance.

##### Abstract (translated by Google)
本文提出了一种在图像和视频中生成对象和动作提议的新方法。它建立在预先训练的CNN的不同卷积层的激活之上，将早期层的定位准确度与后面层的高信息量（因此回想起来）相结合。为此，我们建立一个反向级联，从后面的CNN的卷积层向后，选择最有希望的位置，并以粗到细的方式细化它们。该方法是有效的，因为：i）它重新使用提取出来的相同特征用于检测，ii）它使用积分图像来聚合特征，以及iii）由于使用了反粗糙 - 细级联。该方法也是准确的。我们表明，我们的DeepPropsals胜过了以前提出的大部分对象建议和行动建议方法，并且在插入基于CNN的对象检测器时，可以产生最先进的检测性能。

##### URL
[https://arxiv.org/abs/1606.04702](https://arxiv.org/abs/1606.04702)

##### PDF
[https://arxiv.org/pdf/1606.04702](https://arxiv.org/pdf/1606.04702)


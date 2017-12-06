---
layout: post
title: "Learning to Read Chest X-Rays: Recurrent Neural Cascade Model for Automated Image Annotation"
date: 2016-03-28 19:02:07
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization GAN Caption CNN RNN Deep_Learning
author: Hoo-Chang Shin, Kirk Roberts, Le Lu, Dina Demner-Fushman, Jianhua Yao, Ronald M Summers
---

* content
{:toc}

##### Abstract
Despite the recent advances in automatically describing image contents, their applications have been mostly limited to image caption datasets containing natural images (e.g., Flickr 30k, MSCOCO). In this paper, we present a deep learning model to efficiently detect a disease from an image and annotate its contexts (e.g., location, severity and the affected organs). We employ a publicly available radiology dataset of chest x-rays and their reports, and use its image annotations to mine disease names to train convolutional neural networks (CNNs). In doing so, we adopt various regularization techniques to circumvent the large normal-vs-diseased cases bias. Recurrent neural networks (RNNs) are then trained to describe the contexts of a detected disease, based on the deep CNN features. Moreover, we introduce a novel approach to use the weights of the already trained pair of CNN/RNN on the domain-specific image/text dataset, to infer the joint image/text contexts for composite image labeling. Significantly improved image annotation results are demonstrated using the recurrent neural cascade model by taking the joint image/text contexts into account.

##### Abstract (translated by Google)
尽管最近在自动描述图像内容方面取得了进展，但其应用大多局限于包含自然图像的图像标题数据集（例如，Flickr 30k，MSCOCO）。在本文中，我们提出了一个深度学习模型，从图像中高效地检测疾病，并注释其背景（例如位置，严重程度和受影响的器官）。我们采用公开可用的胸部X射线放射学数据集及其报告，并使用其图像注释来挖掘疾病名称以训练卷积神经网络（CNN）。这样做，我们采取各种正规化技术来规避大的正常与病态的偏见。然后训练递归神经网络（RNN），以深度CNN特征为基础描述检测到的疾病的背景。此外，我们引入了一种新颖的方法来使用已经被训练的一对CNN / RNN在特定领域的图像/文本数据集上的权重来推断用于复合图像标记的联合图像/文本上下文。通过考虑联合图像/文本背景，使用递归神经级联模型来证明显着改善的图像注释结果。

##### URL
[https://arxiv.org/abs/1603.08486](https://arxiv.org/abs/1603.08486)


---
layout: post
title: "Gated Siamese Convolutional Neural Network Architecture for Human Re-Identification"
date: 2016-09-26 16:28:58
categories: arXiv_CV
tags: arXiv_CV Re-identification CNN
author: Rahul Rama Varior, Mrinal Haloi, Gang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Matching pedestrians across multiple camera views, known as human re-identification, is a challenging research problem that has numerous applications in visual surveillance. With the resurgence of Convolutional Neural Networks (CNNs), several end-to-end deep Siamese CNN architectures have been proposed for human re-identification with the objective of projecting the images of similar pairs (i.e. same identity) to be closer to each other and those of dissimilar pairs to be distant from each other. However, current networks extract fixed representations for each image regardless of other images which are paired with it and the comparison with other images is done only at the final level. In this setting, the network is at risk of failing to extract finer local patterns that may be essential to distinguish positive pairs from hard negative pairs. In this paper, we propose a gating function to selectively emphasize such fine common local patterns by comparing the mid-level features across pairs of images. This produces flexible representations for the same image according to the images they are paired with. We conduct experiments on the CUHK03, Market-1501 and VIPeR datasets and demonstrate improved performance compared to a baseline Siamese CNN architecture.

##### Abstract (translated by Google)
在多个摄像机视图之间匹配行人，被称为人类再识别，是一个具有挑战性的研究问题，在视觉监视中有许多应用。随着卷积神经网络（CNNs）的复兴，已经提出了几种端到端的深度连体CNN体系结构用于人类再识别，其目的是将类似对的图像（即相同的身份）投影到彼此更接近而那些不相似的双方彼此远离。然而，当前的网络提取每个图像的固定表示，而不管与其配对的其他图像，并且与其他图像的比较仅在最终级别完成。在这种情况下，网络有可能无法提取更精细的局部模式，这些模式可能是区分正负对和硬负对的关键。在本文中，我们提出了一种门控功能，通过比较跨越图像的中间特征来选择性地强调这种良好的共同局部模式。这根据与其配对的图像对同一图像产生灵活的表示。我们在CUHK03，Market-1501和VIPeR数据集上进行实验，并证明与基准连体CNN架构相比，性能有所提高。

##### URL
[https://arxiv.org/abs/1607.08378](https://arxiv.org/abs/1607.08378)

##### PDF
[https://arxiv.org/pdf/1607.08378](https://arxiv.org/pdf/1607.08378)


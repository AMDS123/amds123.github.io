---
layout: post
title: "Image Co-segmentation via Multi-scale Local Shape Transfer"
date: 2018-05-15 07:48:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding Relation
author: Wei Teng, Yu Zhang, Xiaowu Chen, Jia Li, Zhiqiang He
mathjax: true
---

* content
{:toc}

##### Abstract
Image co-segmentation is a challenging task in computer vision that aims to segment all pixels of the objects from a predefined semantic category. In real-world cases, however, common foreground objects often vary greatly in appearance, making their global shapes highly inconsistent across images and difficult to be segmented. To address this problem, this paper proposes a novel co-segmentation approach that transfers patch-level local object shapes which appear more consistent across different images. In our framework, a multi-scale patch neighbourhood system is first generated using proposal flow on arbitrary image-pair, which is further refined by Locally Linear Embedding. Based on the patch relationships, we propose an efficient algorithm to jointly segment the objects in each image while transferring their local shapes across different images. Extensive experiments demonstrate that the proposed method can robustly and effectively segment common objects from an image set. On iCoseg, MSRC and Coseg-Rep dataset, the proposed approach performs comparable or better than the state-of-thearts, while on a more challenging benchmark Fashionista dataset, our method achieves significant improvements.

##### Abstract (translated by Google)
图像共分割是计算机视觉中的一项具有挑战性的任务，旨在从预定义的语义范畴中分割出对象的所有像素。然而，在现实世界的情况下，常见的前景对象在外观上经常变化很大，使得它们的全局形状在图像上高度不一致并且难以被分割。为了解决这个问题，本文提出了一种新颖的协同分割方法，该方法可以在不同图像之间传输看起来更一致的补丁级别局部对象形状。在我们的框架中，首先使用任意图像对上的提议流来生成多尺度补丁邻域系统，这通过局部线性嵌入进一步细化。基于贴片关系，我们提出了一种有效的算法来联合分割每个图像中的对象，同时在不同的图像上传输它们的局部形状。大量的实验表明，所提出的方法可以从图像集合中有效地分割普通对象。在iCoseg，MSRC和Coseg-Rep数据集中，所提出的方法的表现与艺术级的表现相当或更好，而在更具挑战性的基准Fashionista数据集上，我们的方法取得了显着的改善。

##### URL
[http://arxiv.org/abs/1805.05610](http://arxiv.org/abs/1805.05610)

##### PDF
[http://arxiv.org/pdf/1805.05610](http://arxiv.org/pdf/1805.05610)


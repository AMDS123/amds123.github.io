---
layout: post
title: "Towards Human-Machine Cooperation: Self-supervised Sample Mining for Object Detection"
date: 2018-03-27 03:06:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Keze Wang, Xiaopeng Yan, Dongyu Zhang, Lei Zhang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Though quite challenging, leveraging large-scale unlabeled or partially labeled images in a cost-effective way has increasingly attracted interests for its great importance to computer vision. To tackle this problem, many Active Learning (AL) methods have been developed. However, these methods mainly define their sample selection criteria within a single image context, leading to the suboptimal robustness and impractical solution for large-scale object detection. In this paper, aiming to remedy the drawbacks of existing AL methods, we present a principled Self-supervised Sample Mining (SSM) process accounting for the real challenges in object detection. Specifically, our SSM process concentrates on automatically discovering and pseudo-labeling reliable region proposals for enhancing the object detector via the introduced cross image validation, i.e., pasting these proposals into different labeled images to comprehensively measure their values under different image contexts. By resorting to the SSM process, we propose a new AL framework for gradually incorporating unlabeled or partially labeled data into the model learning while minimizing the annotating effort of users. Extensive experiments on two public benchmarks clearly demonstrate our proposed framework can achieve the comparable performance to the state-of-the-art methods with significantly fewer annotations.

##### Abstract (translated by Google)
虽然相当具有挑战性，但以具有成本效益的方式利用大规模未标记或部分标记的图像越来越引起人们对计算机视觉的重视。为了解决这个问题，已经开发了许多主动学习（AL）方法。然而，这些方法主要是在单个图像上下文中定义它们的样本选择标准，从而导致对于大规模物体检测的不理想的鲁棒性和不切实际的解决方案。在本文中，为了弥补现有AL方法的缺陷，我们提出了一个原则性的自监督抽样挖掘（SSM）过程，以解决目标检测中的真实挑战。具体来说，我们的SSM过程集中在通过引入的交叉图像验证自动发现和伪标记可靠区域提议以增强对象检测器，即将这些提议粘贴到不同的标记图像中以在不同图像上下文中全面测量它们的值。通过采用SSM过程，我们提出了一种新的AL框架，用于逐渐将未标记或部分标记的数据合并到模型学习中，同时最大限度地减少用户的注释工作量。对两个公共基准的大量实验清楚地表明，我们提出的框架可以实现与最先进的方法相媲美的性能，并且注释的数量显着减少。

##### URL
[https://arxiv.org/abs/1803.09867](https://arxiv.org/abs/1803.09867)

##### PDF
[https://arxiv.org/pdf/1803.09867](https://arxiv.org/pdf/1803.09867)


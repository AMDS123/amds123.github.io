---
layout: post
title: "Diagnose like a Radiologist: Attention Guided Convolutional Neural Network for Thorax Disease Classification"
date: 2018-01-30 10:55:23
categories: arXiv_CV
tags: arXiv_CV Attention CNN Inference Classification
author: Qingji Guan, Yaping Huang, Zhun Zhong, Zhedong Zheng, Liang Zheng, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the task of thorax disease classification on chest X-ray images. Existing methods generally use the global image as input for network learning. Such a strategy is limited in two aspects. 1) A thorax disease usually happens in (small) localized areas which are disease specific. Training CNNs using global image may be affected by the (excessive) irrelevant noisy areas. 2) Due to the poor alignment of some CXR images, the existence of irregular borders hinders the network performance. In this paper, we address the above problems by proposing a three-branch attention guided convolution neural network (AG-CNN). AG-CNN 1) learns from disease-specific regions to avoid noise and improve alignment, 2) also integrates a global branch to compensate the lost discriminative cues by local branch. Specifically, we first learn a global CNN branch using global images. Then, guided by the attention heat map generated from the global branch, we inference a mask to crop a discriminative region from the global image. The local region is used for training a local CNN branch. Lastly, we concatenate the last pooling layers of both the global and local branches for fine-tuning the fusion branch. The Comprehensive experiment is conducted on the ChestX-ray14 dataset. We first report a strong global baseline producing an average AUC of 0.841 with ResNet-50 as backbone. After combining the local cues with the global information, AG-CNN improves the average AUC to 0.868. While DenseNet-121 is used, the average AUC achieves 0.871, which is a new state of the art in the community.

##### Abstract (translated by Google)
本文考虑胸部X线片胸部疾病分类的任务。现有的方法通常使用全局图像作为网络学习的输入。这样的战略在两个方面是有限的。 1）胸部疾病通常发生在疾病特异的（小）局部区域。使用全局图像训练CNN可能会受（过度）不相关的噪声区域的影响。 2）由于某些CXR图像对齐不良，边界不规则的存在阻碍了网络的性能。在本文中，我们通过提出三分支注意引导卷积神经网络（AG-CNN）来解决上述问题。 AG-CNN 1）从疾病特定区域学习，以避免噪音和改善校准，2）还集成了一个全球分支，以弥补当地分支丢失的区分线索。具体来说，我们首先学习使用全局图像的全球CNN分支。然后，在全局分支生成的注意力热点图的引导下，我们推导出一个掩模，从全局图像中裁剪出一个有区别的区域。本地区域用于培训本地CNN分支。最后，我们连接全局和本地分支的最后一个池层，用于微调融合分支。综合实验在ChestX-ray14数据集上进行。我们首先报告了一个强大的全球基线，以ResNet-50为骨干，平均AUC为0.841。将地方线索与全球信息相结合后，AG-CNN将平均AUC提高到0.868。在使用DenseNet-121的同时，平均AUC达到了0.871，这是社区内最新的技术。

##### URL
[http://arxiv.org/abs/1801.09927](http://arxiv.org/abs/1801.09927)

##### PDF
[http://arxiv.org/pdf/1801.09927](http://arxiv.org/pdf/1801.09927)


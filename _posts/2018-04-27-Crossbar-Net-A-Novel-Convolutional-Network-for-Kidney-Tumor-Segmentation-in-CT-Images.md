---
layout: post
title: "Crossbar-Net: A Novel Convolutional Network for Kidney Tumor Segmentation in CT Images"
date: 2018-04-27 13:09:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Qian Yu, Yinhuan Shi, Jinquan Sun, Yang Gao, Yakang Dai, Jianbing Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the irregular motion, similar appearance and diverse shape, accurate segmentation of kidney tumor in CT images is a difficult and challenging task. To this end, we present a novel automatic segmentation method, termed as Crossbar-Net, with the goal of accurate segmenting the kidney tumors. Firstly, considering that the traditional learning-based segmentation methods normally employ either whole images or squared patches as the training samples, we innovatively sample the orthogonal non-squared patches (namely crossbar patches), to fully cover the whole kidney tumors in either horizontal or vertical directions. These sampled crossbar patches could not only represent the detailed local information of kidney tumor as the traditional patches, but also describe the global appearance from either horizontal or vertical direction using contextual information. Secondly, with the obtained crossbar patches, we trained a convolutional neural network with two sub-models (i.e., horizontal sub-model and vertical sub-model) in a cascaded manner, to integrate the segmentation results from two directions (i.e., horizontal and vertical). This cascaded training strategy could effectively guarantee the consistency between sub-models, by feeding each other with the most difficult samples, for a better segmentation. In the experiment, we evaluate our method on a real CT kidney tumor dataset, collected from 94 different patients including 3,500 images. Compared with the state-of-the-art segmentation methods, the results demonstrate the superior results of our method on dice ratio score, true positive fraction, centroid distance and Hausdorff distance. Moreover, we have extended our crossbar-net to a different task: cardiac segmentation, showing the promising results for the better generalization.

##### Abstract (translated by Google)
由于运动不规则，外形相似，形态多样，CT图像中肾脏肿瘤的准确分割是一项艰巨且具有挑战性的任务。为此，我们提出了一种新的自动分割方法，称为Crossbar-Net，其目标是精确分割肾肿瘤。首先，考虑到传统的基于学习的分割方法通常使用整幅图像或平方斑块作为训练样本，我们创新性地对正交非平方斑块（即交叉斑块）进行采样，以完全覆盖整个肾脏肿瘤的水平或垂直方向。这些取样的横断面贴片不仅可以像传统贴片一样表示肾肿瘤的详细局部信息，还可以使用上下文信息从水平或垂直方向描述全局外观。其次，利用所获得的横杆贴片，以级联的方式训练了一个具有两个子模型（即水平子模型和垂直子模型）的卷积神经网络，将来自两个方向的分割结果（即水平和垂直子模型）垂直）。这种级联训练策略可以有效地保证子模型之间的一致性，通过互相提供最难的样本，实现更好的分割。在实验中，我们评估了我们的方法在一个真正的CT肾脏肿瘤数据集上，收集了94个不同的患者，其中包括3500个图像。与最先进的分割方法相比，结果证明了我们的方法在骰子比率分数，真正分数，质心距离和Hausdorff距离上的优越结果。此外，我们已经将我们的交叉网络扩展到不同的任务：心脏分割，显示更好的泛化的有希望的结果。

##### URL
[https://arxiv.org/abs/1804.10484](https://arxiv.org/abs/1804.10484)

##### PDF
[https://arxiv.org/pdf/1804.10484](https://arxiv.org/pdf/1804.10484)


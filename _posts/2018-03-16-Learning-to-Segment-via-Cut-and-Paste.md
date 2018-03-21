---
layout: post
title: "Learning to Segment via Cut-and-Paste"
date: 2018-03-16 21:58:51
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Weakly_Supervised Detection
author: Tal Remez, Jonathan Huang, Matthew Brown
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a weakly-supervised approach to object instance segmentation. Starting with known or predicted object bounding boxes, we learn object masks by playing a game of cut-and-paste in an adversarial learning setup. A mask generator takes a detection box and Faster R-CNN features, and constructs a segmentation mask that is used to cut-and-paste the object into a new image location. The discriminator tries to distinguish between real objects, and those cut and pasted via the generator, giving a learning signal that leads to improved object masks. We verify our method experimentally using Cityscapes, COCO, and aerial image datasets, learning to segment objects without ever having seen a mask in training. Our method exceeds the performance of existing weakly supervised methods, without requiring hand-tuned segment proposals, and reaches 90% of supervised performance.

##### Abstract (translated by Google)
本文提出了一种用于对象实例分割的弱监督方法。从已知或预测的对象边界框开始，我们通过在敌对学习设置中进行剪切粘贴游戏来学习对象掩模。蒙版生成器使用检测框和更快的R-CNN特征，并构建用于将对象剪切并粘贴到新图像位置的分割蒙版。鉴别器试图区分真实物体和通过发生器剪切和粘贴的物体，从而给出导致改进的物体掩模的学习信号。我们使用Cityscapes，COCO和航空图像数据集进行实验验证，学习如何在没有看到过训练中的面具的情况下对对象进行分割。我们的方法超出了现有弱监督方法的表现，无需手动调整细分提案，并达到监督表现的90％。

##### URL
[https://arxiv.org/abs/1803.06414](https://arxiv.org/abs/1803.06414)

##### PDF
[https://arxiv.org/pdf/1803.06414](https://arxiv.org/pdf/1803.06414)


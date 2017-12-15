---
layout: post
title: "Unsupervised Learning of Visual Representations using Videos"
date: 2015-10-06 17:05:49
categories: arXiv_CV
tags: arXiv_CV Face Tracking CNN
author: Xiaolong Wang, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Is strong supervision necessary for learning a good visual representation? Do we really need millions of semantically-labeled images to train a Convolutional Neural Network (CNN)? In this paper, we present a simple yet surprisingly powerful approach for unsupervised learning of CNN. Specifically, we use hundreds of thousands of unlabeled videos from the web to learn visual representations. Our key idea is that visual tracking provides the supervision. That is, two patches connected by a track should have similar visual representation in deep feature space since they probably belong to the same object or object part. We design a Siamese-triplet network with a ranking loss function to train this CNN representation. Without using a single image from ImageNet, just using 100K unlabeled videos and the VOC 2012 dataset, we train an ensemble of unsupervised networks that achieves 52% mAP (no bounding box regression). This performance comes tantalizingly close to its ImageNet-supervised counterpart, an ensemble which achieves a mAP of 54.4%. We also show that our unsupervised network can perform competitively in other tasks such as surface-normal estimation.

##### Abstract (translated by Google)
学习良好的视觉表现是否需要强有力的监督？我们是否真的需要数百万个语义标记的图像来训练卷积神经网络（CNN）？在本文中，我们提出了一个简单但令人惊讶的强大的方法，无监督学习CNN。具体而言，我们使用数十万个来自网络的未标记视频来学习视觉表示。我们的主要想法是视觉跟踪提供监督。也就是说，由轨道连接的两个补丁在深度特征空间中应该具有相似的视觉表示，因为它们可能属于相同的对象或对象部分。我们设计一个具有排名损失函数的连体三重网络来训练这个CNN表示。如果不使用来自ImageNet的单个图像，只使用100K无标签的视频和VOC 2012数据集，我们将训练无监督网络集合，达到52％的mAP（无边界框回归）。这个表现非常接近ImageNet监督的对手，一个合奏，达到了54.4％的mAP。我们还表明，我们的无监督网络可以在其他任务，如表面法线估计竞争力。

##### URL
[https://arxiv.org/abs/1505.00687](https://arxiv.org/abs/1505.00687)

##### PDF
[https://arxiv.org/pdf/1505.00687](https://arxiv.org/pdf/1505.00687)


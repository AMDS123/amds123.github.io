---
layout: post
title: "Pooling Facial Segments to Face: The Shallow and Deep Ends"
date: 2017-01-29 00:30:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Upal Mahbub, Sayantan Sarkar, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Generic face detection algorithms do not perform very well in the mobile domain due to significant presence of occluded and partially visible faces. One promising technique to handle the challenge of partial faces is to design face detectors based on facial segments. In this paper two such face detectors namely, SegFace and DeepSegFace, are proposed that detect the presence of a face given arbitrary combinations of certain face segments. Both methods use proposals from facial segments as input that are found using weak boosted classifiers. SegFace is a shallow and fast algorithm using traditional features, tailored for situations where real time constraints must be satisfied. On the other hand, DeepSegFace is a more powerful algorithm based on a deep convolutional neutral network (DCNN) architecture. DeepSegFace offers certain advantages over other DCNN-based face detectors as it requires relatively little amount of data to train by utilizing a novel data augmentation scheme and is very robust to occlusion by design. Extensive experiments show the superiority of the proposed methods, specially DeepSegFace, over other state-of-the-art face detectors in terms of precision-recall and ROC curve on two mobile face datasets.

##### Abstract (translated by Google)
通用人脸检测算法在移动领域中表现不佳，因为大量存在遮挡和部分可见的人脸。面对局部人脸挑战的一个有前途的技术是设计基于面部片段的人脸检测器。在本文中，提出了两种这样的面部检测器，即SegFace和DeepSegFace，其检测给定面部片段的任意组合的面部的存在。这两种方法都使用面部细分提案作为输入，使用弱提升分类器。 SegFace是一种使用传统特征的浅而快的算法，适用于必须满足实时约束条件的情况。另一方面，DeepSegFace是基于深度卷积中立网络（DCNN）架构的更强大的算法。 DeepSegFace提供超过其他基于DCNN的人脸检测器的一些优势，因为它需要相对较少量的数据来训练，通过使用新颖的数据增强方案，并且非常有效地阻止设计。广泛的实验表明，所提出的方法（特别是DeepSegFace）相对于其他现有技术的面部检测器在两个移动面部数据集上的精确回忆和ROC曲线方面的优越性。

##### URL
[https://arxiv.org/abs/1701.08341](https://arxiv.org/abs/1701.08341)

##### PDF
[https://arxiv.org/pdf/1701.08341](https://arxiv.org/pdf/1701.08341)


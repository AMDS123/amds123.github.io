---
layout: post
title: "Shuffle and Learn: Unsupervised Learning using Temporal Order Verification"
date: 2016-07-26 17:26:01
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Action_Recognition CNN Recognition
author: Ishan Misra, C. Lawrence Zitnick, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an approach for learning a visual representation from the raw spatiotemporal signals in videos. Our representation is learned without supervision from semantic labels. We formulate our method as an unsupervised sequential verification task, i.e., we determine whether a sequence of frames from a video is in the correct temporal order. With this simple task and no semantic labels, we learn a powerful visual representation using a Convolutional Neural Network (CNN). The representation contains complementary information to that learned from supervised image datasets like ImageNet. Qualitative results show that our method captures information that is temporally varying, such as human pose. When used as pre-training for action recognition, our method gives significant gains over learning without external data on benchmark datasets like UCF101 and HMDB51. To demonstrate its sensitivity to human pose, we show results for pose estimation on the FLIC and MPII datasets that are competitive, or better than approaches using significantly more supervision. Our method can be combined with supervised representations to provide an additional boost in accuracy.

##### Abstract (translated by Google)
在本文中，我们提出了一种从视频中的原始时空信号学习视觉表示的方法。我们的表示是在没有语义标签的监督下学习的。我们将我们的方法制定为无监督的顺序验证任务，即，我们确定来自视频的帧序列是否处于正确的时间顺序。有了这个简单的任务，没有语义标签，我们使用卷积神经网络（CNN）学习强大的视觉表示。该表示包含从ImageNet监督的图像数据集中学习到的补充信息。定性结果表明，我们的方法捕捉时间变化的信息，如人的姿势。当用作动作识别的预训练时，我们的方法在基准数据集（如UCF101和HMDB51）上没有外部数据的情况下获得显着的收益。为了证明其对人体姿态的敏感性，我们在FLIC和MPII数据集上展示了姿态估计结果，这些数据集是有竞争力的，或者比使用更多监督的方法更好。我们的方法可以与监督表示相结合，以提高准确度。

##### URL
[https://arxiv.org/abs/1603.08561](https://arxiv.org/abs/1603.08561)

##### PDF
[https://arxiv.org/pdf/1603.08561](https://arxiv.org/pdf/1603.08561)


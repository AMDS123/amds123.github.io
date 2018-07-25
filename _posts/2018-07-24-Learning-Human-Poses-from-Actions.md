---
layout: post
title: "Learning Human Poses from Actions"
date: 2018-07-24 12:58:58
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Aditya Arun, C.V. Jawahar, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of learning to estimate human pose in still images. In order to avoid the high cost of full supervision, we propose to use a diverse data set, which consists of two types of annotations: (i) a small number of images are labeled using the expensive ground-truth pose; and (ii) other images are labeled using the inexpensive action label. As action information helps narrow down the pose of a human, we argue that this approach can help reduce the cost of training without significantly affecting the accuracy. To demonstrate this we design a probabilistic framework that employs two distributions: (i) a conditional distribution to model the uncertainty over the human pose given the image and the action; and (ii) a prediction distribution, which provides the pose of an image without using any action information. We jointly estimate the parameters of the two aforementioned distributions by minimizing their dissimilarity coefficient, as measured by a task-specific loss function. During both training and testing, we only require an efficient sampling strategy for both the aforementioned distributions. This allows us to use deep probabilistic networks that are capable of providing accurate pose estimates for previously unseen images. Using the MPII data set, we show that our approach outperforms baseline methods that either do not use the diverse annotations or rely on pointwise estimates of the pose.

##### Abstract (translated by Google)
我们考虑学习估计静止图像中人体姿势的任务。为了避免全面监督的高成本，我们建议使用多种数据集，其由两种类型的注释组成：（i）使用昂贵的地面实况姿势标记少量图像; （ii）使用廉价的动作标签标记其他图像。由于行动信息有助于缩小人类的姿势，我们认为这种方法可以帮助降低培训成本，而不会显着影响准确性。为了证明这一点，我们设计了一个采用两种分布的概率框架：（i）条件分布，用于模拟给定图像和动作的人体姿势的不确定性; （ii）预测分布，其提供图像的姿势而不使用任何动作信息。我们通过最小化它们的相异系数来共同估计上述两个分布的参数，如通过任务特定的损失函数所测量的。在训练和测试期间，我们只需要对上述两种分布都采用有效的采样策略。这允许我们使用能够为先前看不见的图像提供精确姿势估计的深度概率网络。使用MPII数据集，我们表明我们的方法优于基线方法，这些方法要么不使用不同的注释，要么依赖于姿势的逐点估计。

##### URL
[https://arxiv.org/abs/1807.09075](https://arxiv.org/abs/1807.09075)

##### PDF
[https://arxiv.org/pdf/1807.09075](https://arxiv.org/pdf/1807.09075)


---
layout: post
title: "Can 3D Pose be Learned from 2D Projections Alone?"
date: 2018-08-22 01:57:33
categories: arXiv_CV
tags: arXiv_CV Adversarial Weakly_Supervised Pose_Estimation
author: Dylan Drover, Rohith MV, Ching-Hang Chen, Amit Agrawal, Ambrish Tyagi, Cong Phuoc Huynh
mathjax: true
---

* content
{:toc}

##### Abstract
3D pose estimation from a single image is a challenging task in computer vision. We present a weakly supervised approach to estimate 3D pose points, given only 2D pose landmarks. Our method does not require correspondences between 2D and 3D points to build explicit 3D priors. We utilize an adversarial framework to impose a prior on the 3D structure, learned solely from their random 2D projections. Given a set of 2D pose landmarks, the generator network hypothesizes their depths to obtain a 3D skeleton. We propose a novel Random Projection layer, which randomly projects the generated 3D skeleton and sends the resulting 2D pose to the discriminator. The discriminator improves by discriminating between the generated poses and pose samples from a real distribution of 2D poses. Training does not require correspondence between the 2D inputs to either the generator or the discriminator. We apply our approach to the task of 3D human pose estimation. Results on Human3.6M dataset demonstrates that our approach outperforms many previous supervised and weakly supervised approaches.

##### Abstract (translated by Google)
来自单个图像的3D姿势估计在计算机视觉中是具有挑战性的任务。我们提出了一种弱监督方法来估计3D姿势点，仅给出2D姿势地标。我们的方法不需要2D和3D点之间的对应来构建明确的3D先验。我们利用对抗框架在3D结构上施加先验，仅从他们的随机2D投影中学习。给定一组2D姿势界标，生成器网络假设其深度以获得3D骨架。我们提出了一种新颖的随机投影层，它随机投影生成的3D骨架并将得到的2D姿势发送给鉴别器。通过从2D姿势的真实分布中区分所生成的姿势和姿势样本来改进鉴别器。训练不要求2D输入与发生器或鉴别器之间的对应关系。我们将我们的方法应用于3D人体姿态估计的任务。 Human3.6M数据集的结果表明，我们的方法优于许多以前的监督和弱监督方法。

##### URL
[http://arxiv.org/abs/1808.07182](http://arxiv.org/abs/1808.07182)

##### PDF
[http://arxiv.org/pdf/1808.07182](http://arxiv.org/pdf/1808.07182)


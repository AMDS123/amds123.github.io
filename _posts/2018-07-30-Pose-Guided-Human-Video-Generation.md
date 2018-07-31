---
layout: post
title: "Pose Guided Human Video Generation"
date: 2018-07-30 02:46:43
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Prediction
author: Ceyuan Yang, Zhe Wang, Xinge Zhu, Chen Huang, Jianping Shi, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the emergence of Generative Adversarial Networks, video synthesis has witnessed exceptional breakthroughs. However, existing methods lack a proper representation to explicitly control the dynamics in videos. Human pose, on the other hand, can represent motion patterns intrinsically and interpretably, and impose the geometric constraints regardless of appearance. In this paper, we propose a pose guided method to synthesize human videos in a disentangled way: plausible motion prediction and coherent appearance generation. In the first stage, a Pose Sequence Generative Adversarial Network (PSGAN) learns in an adversarial manner to yield pose sequences conditioned on the class label. In the second stage, a Semantic Consistent Generative Adversarial Network (SCGAN) generates video frames from the poses while preserving coherent appearances in the input image. By enforcing semantic consistency between the generated and ground-truth poses at a high feature level, our SCGAN is robust to noisy or abnormal poses. Extensive experiments on both human action and human face datasets manifest the superiority of the proposed method over other state-of-the-arts.

##### Abstract (translated by Google)
由于Generative Adversarial Networks的出现，视频合成已经见证了非凡的突破。然而，现有方法缺乏适当的表示来明确控制视频中的动态。另一方面，人体姿势可以本质上和可解释地表示运动模式，并且无论外观如何都强加几何约束。在本文中，我们提出了一种姿态引导的方法，以解开的方式合成人类视频：合理的运动预测和连贯的外观生成。在第一阶段，姿势序列生成对抗网络（PSGAN）以对抗方式学习以产生以类标签为条件的姿势序列。在第二阶段，语义一致生成对抗网络（SCGAN）从姿势生成视频帧，同时保留输入图像中的相干外观。通过在高特征级别强制生成和地面真实姿势之间的语义一致性，我们的SCGAN对于噪声或异常姿势是健壮的。对人类行为和人脸数据集的广泛实验表明，所提出的方法优于其他现有技术。

##### URL
[http://arxiv.org/abs/1807.11152](http://arxiv.org/abs/1807.11152)

##### PDF
[http://arxiv.org/pdf/1807.11152](http://arxiv.org/pdf/1807.11152)


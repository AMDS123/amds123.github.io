---
layout: post
title: "Augmented Skeleton Space Transfer for Depth-based Hand Pose Estimation"
date: 2018-05-11 17:28:49
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Pose_Estimation Optimization Quantitative
author: Seungryul Baek, Kwang In Kim, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Crucial to the success of training a depth-based 3D hand pose estimator (HPE) is the availability of comprehensive datasets covering diverse camera perspectives, shapes, and pose variations. However, collecting such annotated datasets is challenging. We propose to complete existing databases by generating new database entries. The key idea is to synthesize data in the skeleton space (instead of doing so in the depth-map space) which enables an easy and intuitive way of manipulating data entries. Since the skeleton entries generated in this way do not have the corresponding depth map entries, we exploit them by training a separate hand pose generator (HPG) which synthesizes the depth map from the skeleton entries. By training the HPG and HPE in a single unified optimization framework enforcing that 1) the HPE agrees with the paired depth and skeleton entries; and 2) the HPG-HPE combination satisfies the cyclic consistency (both the input and the output of HPG-HPE are skeletons) observed via the newly generated unpaired skeletons, our algorithm constructs a HPE which is robust to variations that go beyond the coverage of the existing database. Our training algorithm adopts the generative adversarial networks (GAN) training process. As a by-product, we obtain a hand pose discriminator (HPD) that is capable of picking out realistic hand poses. Our algorithm exploits this capability to refine the initial skeleton estimates in testing, further improving the accuracy. We test our algorithm on four challenging benchmark datasets (ICVL, MSRA, NYU and Big Hand 2.2M datasets) and demonstrate that our approach outperforms or is on par with state-of-the-art methods quantitatively and qualitatively.

##### Abstract (translated by Google)
培训基于深度的3D手姿势估计器（HPE）的成功至关重要的是可用的综合数据集，涵盖不同的摄像机视角，形状和姿态变化。但是，收集这些带注释的数据集具有挑战性。我们建议通过生成新的数据库条目来完成现有数据库。关键的想法是在骨架空间中合成数据（而不是在深度图空间中这样做），从而实现操作数据条目的简单而直观的方法。由于以这种方式生成的骨架条目没有相应的深度图条目，因此我们通过训练单独的手形成生成器（HPG）来利用它们，该手形合成器从骨架条目合成深度图。通过在单一统一优化框架中对HPG和HPE进行培训，强化1）HPE同意配对深度和骨架条目;和2）HPG-HPE组合满足通过新生成的不成对骨架观察到的循环一致性（HPG-HPE的输入和输出都是骨架），我们的算法构建了一个HPE，该变量对超出覆盖范围现有的数据库。我们的训练算法采用生成对抗网络（GAN）训练过程。作为副产品，我们获得了一个能够挑选逼真手姿的手姿识别器（HPD）。我们的算法利用此功能来优化测试中的初始骨架估计，进一步提高准确性。我们在四个具有挑战性的基准数据集（ICVL，MSRA，NYU和Big Hand 2.2M数据集）上测试我们的算法，并证明我们的方法在数量和质量上都优于或与最先进的方法相当。

##### URL
[http://arxiv.org/abs/1805.04497](http://arxiv.org/abs/1805.04497)

##### PDF
[http://arxiv.org/pdf/1805.04497](http://arxiv.org/pdf/1805.04497)


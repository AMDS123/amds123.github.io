---
layout: post
title: "Weakly Supervised Localisation for Fetal Ultrasound Images"
date: 2018-08-02 13:02:37
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Weakly_Supervised GAN Pose_Estimation CNN Classification Detection
author: Nicolas Toussaint, Bishesh Khanal, Matthew Sinclair, Alberto Gomez, Emily Skelton, Jacqueline Matthew, Julia A. Schnabel
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the task of detecting and localising fetal anatomical regions in 2D ultrasound images, where only image-level labels are present at training, i.e. without any localisation or segmentation information. We examine the use of convolutional neural network architectures coupled with soft proposal layers. The resulting network simultaneously performs anatomical region detection (classification) and localisation tasks. We generate a proposal map describing the attention of the network for a particular class. The network is trained on 85,500 2D fetal Ultrasound images and their associated labels. Labels correspond to six anatomical regions: head, spine, thorax, abdomen, limbs, and placenta. Detection achieves an average accuracy of 90\% on individual regions, and show that the proposal maps correlate well with relevant anatomical structures. This work presents itself as a powerful and essential step towards subsequent tasks such as fetal position and pose estimation, organ-specific segmentation, or image-guided navigation. Code and additional material is available at https://ntoussaint.github.io/fetalnav.

##### Abstract (translated by Google)
本文讨论了在2D超声图像中检测和定位胎儿解剖区域的任务，其中在训练时仅存在图像级标签，即没有任何定位或分割信息。我们研究了与软提议层相结合的卷积神经网络架构的使用。由此产生的网络同时执行解剖区域检测（分类）和定位任务。我们生成一个提案图，描述网络对特定类的关注。该网络接受85,500个2D胎儿超声图像及其相关标签的培训。标签对应于六个解剖区域：头部，脊柱，胸部，腹部，四肢和胎盘。检测在各个区域实现了90％的平均准确度，并且表明提案图与相关的解剖结构很好地相关。这项工作本身就是一个强大而重要的步骤，可用于后续任务，如胎位和姿势估计，器官特定分割或图像引导导航。代码和其他材料可在https://ntoussaint.github.io/fetalnav获得。

##### URL
[http://arxiv.org/abs/1808.00793](http://arxiv.org/abs/1808.00793)

##### PDF
[http://arxiv.org/pdf/1808.00793](http://arxiv.org/pdf/1808.00793)


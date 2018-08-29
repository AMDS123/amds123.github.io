---
layout: post
title: "DeepHPS: End-to-end Estimation of 3D Hand Pose and Shape by Learning from Synthetic Depth"
date: 2018-08-28 10:29:20
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jameel Malik, Ahmed Elhayek, Fabrizio Nunnari, Kiran Varanasi, Kiarash Tamaddon, Alexis Heloir, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Articulated hand pose and shape estimation is an important problem for vision-based applications such as augmented reality and animation. In contrast to the existing methods which optimize only for joint positions, we propose a fully supervised deep network which learns to jointly estimate a full 3D hand mesh representation and pose from a single depth image. To this end, a CNN architecture is employed to estimate parametric representations i.e. hand pose, bone scales and complex shape parameters. Then, a novel hand pose and shape layer, embedded inside our deep framework, produces 3D joint positions and hand mesh. Lack of sufficient training data with varying hand shapes limits the generalized performance of learning based methods. Also, manually annotating real data is suboptimal. Therefore, we present SynHand5M: a million-scale synthetic dataset with accurate joint annotations, segmentation masks and mesh files of depth maps. Among model based learning (hybrid) methods, we show improved results on our dataset and two of the public benchmarks i.e. NYU and ICVL. Also, by employing a joint training strategy with real and synthetic data, we recover 3D hand mesh and pose from real images in 3.7ms.

##### Abstract (translated by Google)
铰接手姿势和形状估计是基于视觉的应用（例如增强现实和动画）的重要问题。与仅针对关节位置进行优化的现有方法相比，我们提出了一种完全监督的深度网络，其学习从单个深度图像联合估计完整的3D手部网格表示和姿势。为此，采用CNN架构来估计参数表示，即手姿势，骨骼尺度和复杂形状参数。然后，嵌入在我们的深框架内的新颖的手姿势和形状层产生3D关节位置和手网格。缺乏足够的手形训练数据限制了基于学习的方法的广义性能。此外，手动注释真实数据不是最理想的。因此，我们提出了SynHand5M：一个百万级的合成数据集，具有精确的联合注释，分割掩模和深度图的网格文件。在基于模型的学习（混合）方法中，我们在我们的数据集和两个公共基准（即NYU和ICVL）上显示了改进的结果。此外，通过采用真实和合成数据的联合训练策略，我们恢复3D手网并在3.7ms内从真实图像中进行姿势。

##### URL
[http://arxiv.org/abs/1808.09208](http://arxiv.org/abs/1808.09208)

##### PDF
[http://arxiv.org/pdf/1808.09208](http://arxiv.org/pdf/1808.09208)


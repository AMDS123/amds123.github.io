---
layout: post
title: "LCR-Net++: Multi-person 2D and 3D Pose Detection in Natural Images"
date: 2018-03-01 15:39:38
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Classification Detection
author: Gregory Rogez, Philippe Weinzaepfel, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end architecture for joint 2D and 3D human pose estimation in natural images. Key to our approach is the generation and scoring of a number of pose proposals per image, which allows us to predict 2D and 3D poses of multiple people simultaneously. Hence, our approach does not require an approximate localization of the humans for initialization. Our Localization-Classification-Regression architecture, named LCR-Net, contains 3 main components: 1) the pose proposal generator that suggests candidate poses at different locations in the image; 2) a classifier that scores the different pose proposals; and 3) a regressor that refines pose proposals both in 2D and 3D. All three stages share the convolutional feature layers and are trained jointly. The final pose estimation is obtained by integrating over neighboring pose hypotheses, which is shown to improve over a standard non maximum suppression algorithm. Our method recovers full-body 2D and 3D poses, hallucinating plausible body parts when the persons are partially occluded or truncated by the image boundary. Our approach significantly outperforms the state of the art in 3D pose estimation on Human3.6M, a controlled environment. Moreover, it shows promising results on real images for both single and multi-person subsets of the MPII 2D pose benchmark and demonstrates satisfying 3D pose results even for multi-person images.

##### Abstract (translated by Google)
我们提出了一种在自然图像中联合2D和3D人体姿态估计的端到端体系结构。我们的方法的关键是每个图像生成和评分多个姿势提案，这使我们能够同时预测多个人的2D和3D姿势。因此，我们的方法不需要对人进行初始化的近似定位。我们的名为LCR-Net的本地化 - 分类 - 回归体系结构包含3个主要组件：1）姿势建议生成器，其在图像中的不同位置建议候选姿势; 2）对不同姿势提议进行评分的分类器;以及3）以2D和3D改善姿态提议的回归器。所有三个阶段共享卷积要素图层并共同训练。通过对相邻的姿势假设进行积分来获得最终的姿势估计，其被证明可以在标准的非最大抑制算法上得到改善。我们的方法恢复全身二维和三维姿势，当人被图像边界部分遮挡或截断时幻觉出合理的身体部位。我们的方法明显优于人类在可控环境Human3.6M上进行3D姿态估计的最新技术。此外，它显示MPII二维姿态基准的单人和多人子集的真实图像上的有希望的结果，并且证明即使对于多人图像也满足三维姿态结果。

##### URL
[http://arxiv.org/abs/1803.00455](http://arxiv.org/abs/1803.00455)

##### PDF
[http://arxiv.org/pdf/1803.00455](http://arxiv.org/pdf/1803.00455)


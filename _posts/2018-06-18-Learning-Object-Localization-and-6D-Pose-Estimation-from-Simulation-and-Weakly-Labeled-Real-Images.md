---
layout: post
title: "Learning Object Localization and 6D Pose Estimation from Simulation and Weakly Labeled Real Images"
date: 2018-06-18 18:48:12
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Pose_Estimation Classification Detection
author: Jean-Philippe Mercier, Chaitanya Mitash, Philippe Gigu&#xe8;re, Abdeslam Boularias
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a process for efficiently training a point-wise object detector that enables localizing objects and computing their 6D poses in cluttered and occluded scenes. Accurate pose estimation is typically a requirement for robust robotic grasping and manipulation of objects placed in cluttered, tight environments, such as a shelf with multiple objects. To minimize the human labor required for annotation, the proposed object detector is first trained in simulation by using automatically annotated synthetic images. We then show that the performance of the detector can be substantially improved by using a small set of weakly annotated real images, where a human provides only a list of objects present in each image without indicating the location of the objects. To close the gap between real and synthetic images, we adopt a domain adaptation approach through adversarial training. The detector resulting from this training process can be used to localize objects by using its per-object activation maps. In this work, we use the activation maps to guide the search of 6D poses of objects. Our proposed approach is evaluated on several publicly available datasets for pose estimation. We also evaluated our model on classification and localization in unsupervised and semi-supervised settings. The results clearly indicate that this approach could provide an efficient way toward fully automating the training process of computer vision models used in robotics.

##### Abstract (translated by Google)
这项工作提出了一个有效地训练点对象检测器的流程，该对象检测器可以在混乱和遮挡的场景中定位对象并计算它们的6D姿态。准确的姿态估计通常是强健的机器人抓取和操纵放置在杂乱，严密环境中的物体（如多物体的货架）的要求。为了最大限度地减少注释所需的人工，所提议的对象检测器首先通过使用自动注释的合成图像进行模拟训练。然后我们表明，通过使用一小组弱标注的真实图像可以大大提高探测器的性能，其中人类仅提供每个图像中存在的对象列表而不指示对象的位置。为了缩小真实和合成图像之间的差距，我们通过对抗训练采用了领域适应方法。该训练过程产生的检测器可用于通过使用每个对象的激活图来定位对象。在这项工作中，我们使用激活图来指导对象6D姿势的搜索。我们提出的方法是在几个公开可用的数据集上评估姿态估计。我们还评估了我们的模型在无监督和半监督环境下的分类和定位。结果清楚地表明，这种方法可以为使机器人中使用的计算机视觉模型的训练过程完全自动化提供有效途径。

##### URL
[http://arxiv.org/abs/1806.06888](http://arxiv.org/abs/1806.06888)

##### PDF
[http://arxiv.org/pdf/1806.06888](http://arxiv.org/pdf/1806.06888)


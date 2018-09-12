---
layout: post
title: "A Real-time Robotic Grasp Approach with Oriented Anchor Box"
date: 2018-09-08 12:30:54
categories: arXiv_RO
tags: arXiv_RO CNN Classification Detection
author: Hanbo Zhang, Xinwen Zhou, Xuguang Lan, Jin Li, Zhiqiang Tian, Nanning Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Grasp is an essential skill for robots to interact with humans and the environment. In this paper, we build a vision-based, robust and real-time robotic grasp approach with fully convolutional neural network. The main component of our approach is a grasp detection network with oriented anchor boxes as detection priors. Because the orientation of detected grasps is significant, which determines the rotation angle configuration of the gripper, we propose the Orientation Anchor Box Mechanism to regress grasp angle based on predefined assumption instead of classification or regression without any priors. With oriented anchor boxes, the grasps can be predicted more accurately and efficiently. Besides, to accelerate the network training and further improve the performance of angle regression, Angle Matching is proposed during training instead of Jaccard Index Matching. Five-fold cross validation results demonstrate that our proposed algorithm achieves an accuracy of 98.8% and 97.8% in image-wise split and object-wise split respectively, and the speed of our detection algorithm is 67 FPS with GTX 1080Ti, outperforming all the current state-of-the-art grasp detection algorithms on Cornell Dataset both in speed and accuracy. Robotic experiments demonstrate the robustness and generalization ability in unseen objects and real-world environment, with the average success rate of 90.0% and 84.2% of familiar things and unseen things respectively on Baxter robot platform.

##### Abstract (translated by Google)
掌握是机器人与人类和环境互动的基本技能。在本文中，我们构建了一个基于视觉，强大和实时的机器人抓取方法与完全卷积神经网络。我们的方法的主要组成部分是一个抓握检测网络，其定向锚盒作为检测先验。由于检测到的抓握的方向是显着的，这决定了抓手的旋转角度配置，我们建议定向锚箱机构基于预定义的假设而不是没有任何先验的分类或回归来回归抓握角度。通过定向锚箱，可以更准确，更有效地预测抓取。此外，为加速网络训练，进一步提高角度回归的性能，在训练过程中提出了角度匹配，而不是Jaccard指数匹配。五重交叉验证结果表明，我们提出的算法在图像分割和逐个对象分割中分别达到98.8％和97.8％的准确度，我们的检测算法的速度为67 FPS，GTX 1080Ti，优于所有当前康奈尔数据集在速度和准确度方面的最先进的抓握检测算法。机器人实验证明了在看不见的物体和现实世界环境中的鲁棒性和泛化能力，在Baxter机器人平台上，熟悉的东西和看不见的东西的平均成功率分别为90.0％和84.2％。

##### URL
[http://arxiv.org/abs/1809.03873](http://arxiv.org/abs/1809.03873)

##### PDF
[http://arxiv.org/pdf/1809.03873](http://arxiv.org/pdf/1809.03873)


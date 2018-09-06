---
layout: post
title: "Learning 6-D compliant motion primitives from demonstration"
date: 2018-09-05 14:58:04
categories: arXiv_RO
tags: arXiv_RO
author: Markku Suomalainen, Ville Kyrki
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method for learning 6-D compliant motions from demonstration. The key advantage of our learning method compared to current Learning from Demonstration (LfD) methods is that we learn to take advantage of existing mechanical gradients (such as chamfers) with compliance to perform in-contact motions consisting of both translation and rotation, as in aligning workpieces or attaching hose couplers. We find the desired direction, which leads the robot's end-effector to the location shown in the demonstration either in free space or in contact, separately for translational and rotational motions. The key idea is to first compute a set of directions which would result in the observed motion at each timestep during a demonstration. By taking an intersection over all such sets from a demonstration we find a single desired direction which can reproduce the demonstrated motion. Finding the number of compliant axes and their directions in both rotation and translation is based on the assumption that in the presence of a desired direction of motion, all other observed motion is caused by the contact force of the environment, signalling the need for compliance. We evaluate the method on a KUKA LWR4+ robot with test setups imitating typical tasks where a human would use compliance to cope with positional uncertainty. Results show that the method can successfully learn and reproduce compliant motions by taking advantage of the geometry of the task, therefore reducing the need for initial accuracy.

##### Abstract (translated by Google)
我们提出了一种从演示中学习符合6-D的运动的新方法。与当前的演示学习（LfD）方法相比，我们的学习方法的关键优势在于，我们学会利用现有的机械渐变（例如倒角）以及顺应性来执行由平移和旋转组成的接触运动，如对齐工件或连接软管接头。我们找到了所需的方向，它将机器人的末端执行器引导到演示中所示的位置，无论是在自由空间还是在接触中，分别用于平移和旋转运动。关键的想法是首先计算一组方向，这些方向将导致在演示期间每个时间步的观察到的运动。通过在演示中对所有这些集合进行交叉，我们找到了可以再现所演示的运动的单个期望方向。在旋转和平移中找到柔顺轴的数量及其方向是基于这样的假设：在存在期望的运动方向的情况下，所有其他观察到的运动是由环境的接触力引起的，表明需要合规。我们在KUKA LWR4 +机器人上评估该方法，其中测试设置模仿人类将使用顺应性来应对位置不确定性的典型任务。结果表明，该方法可以利用任务的几何形状成功地学习和再现柔顺运动，从而减少对初始精度的需求。

##### URL
[http://arxiv.org/abs/1809.01561](http://arxiv.org/abs/1809.01561)

##### PDF
[http://arxiv.org/pdf/1809.01561](http://arxiv.org/pdf/1809.01561)


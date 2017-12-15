---
layout: post
title: "Adapting Deep Visuomotor Representations with Weak Pairwise Constraints"
date: 2017-05-25 21:51:55
categories: arXiv_CV
tags: arXiv_CV
author: Eric Tzeng, Coline Devin, Judy Hoffman, Chelsea Finn, Pieter Abbeel, Sergey Levine, Kate Saenko, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Real-world robotics problems often occur in domains that differ significantly from the robot's prior training environment. For many robotic control tasks, real world experience is expensive to obtain, but data is easy to collect in either an instrumented environment or in simulation. We propose a novel domain adaptation approach for robot perception that adapts visual representations learned on a large easy-to-obtain source dataset (e.g. synthetic images) to a target real-world domain, without requiring expensive manual data annotation of real world data before policy search. Supervised domain adaptation methods minimize cross-domain differences using pairs of aligned images that contain the same object or scene in both the source and target domains, thus learning a domain-invariant representation. However, they require manual alignment of such image pairs. Fully unsupervised adaptation methods rely on minimizing the discrepancy between the feature distributions across domains. We propose a novel, more powerful combination of both distribution and pairwise image alignment, and remove the requirement for expensive annotation by using weakly aligned pairs of images in the source and target domains. Focusing on adapting from simulation to real world data using a PR2 robot, we evaluate our approach on a manipulation task and show that by using weakly paired images, our method compensates for domain shift more effectively than previous techniques, enabling better robot performance in the real world.

##### Abstract (translated by Google)
现实世界中的机器人问题经常发生在与机器人之前的训练环境有显着差异的领域。对于许多机器人控制任务来说，真实世界的经验是昂贵的，但是数据很容易在仪表环境或模拟中收集。我们提出了一种新颖的机器人感知领域适应方法，使得在大型易于获取的源数据集（例如合成图像）上学习的视觉表示适应目标真实世界的领域，而不需要在政策之前对现实世界数据进行昂贵的手动数据注释搜索。监督域自适应方法使用包含源域和目标域中相同对象或场景的对齐图像对来最小化跨域差异，从而学习域不变表示。但是，它们需要手动对齐这些图像对。完全无监督的自适应方法依赖于最小化跨域的特征分布之间的差异。我们提出了一种新的，更强大的分配和成对图像对齐的组合，并且通过使用源和目标域中的弱对齐图像对来消除昂贵的注释的需求。着眼于使用PR2机器人从仿真到现实世界的数据适应性，我们评估我们的处理任务的方法，并显示，通过使用弱配对的图像，我们的方法比以前的技术更有效地补偿了域转移，使得更好的机器人性能世界。

##### URL
[https://arxiv.org/abs/1511.07111](https://arxiv.org/abs/1511.07111)

##### PDF
[https://arxiv.org/pdf/1511.07111](https://arxiv.org/pdf/1511.07111)


---
layout: post
title: "Learning to Grasp Without Seeing"
date: 2018-05-10 22:56:45
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Adithyavairavan Murali, Yin Li, Dhiraj Gandhi, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Can a robot grasp an unknown object without seeing it? In this paper, we present a tactile-sensing based approach to this challenging problem of grasping novel objects without prior knowledge of their location or physical properties. Our key idea is to combine touch based object localization with tactile based re-grasping. To train our learning models, we created a large-scale grasping dataset, including more than 30 RGB frames and over 2.8 million tactile samples from 7800 grasp interactions of 52 objects. To learn a representation of tactile signals, we propose an unsupervised auto-encoding scheme, which shows a significant improvement of 4-9% over prior methods on a variety of tactile perception tasks. Our system consists of two steps. First, our touch localization model sequentially 'touch-scans' the workspace and uses a particle filter to aggregate beliefs from multiple hits of the target. It outputs an estimate of the object's location, from which an initial grasp is established. Next, our re-grasping model learns to progressively improve grasps with tactile feedback based on the learned features. This network learns to estimate grasp stability and predict adjustment for the next grasp. Re-grasping thus is performed iteratively until our model identifies a stable grasp. Finally, we demonstrate extensive experimental results on grasping a large set of novel objects using tactile sensing alone. Furthermore, when applied on top of a vision-based policy, our re-grasping model significantly boosts the overall accuracy by 10.6%. We believe this is the first attempt at learning to grasp with only tactile sensing and without any prior object knowledge.

##### Abstract (translated by Google)
机器人能够在不看到它的情况下抓住一个未知物体吗在本文中，我们提出了一种基于触觉感知的方法来处理这个具有挑战性的问题，即在事先不知道它们的位置或物理属性的情况下抓住新物体。我们的主要想法是将基于触摸的物体定位与基于触觉的重新抓取相结合。为了训练我们的学习模型，我们创建了一个大型的抓取数据集，包括来自52个对象的7800个抓握相互作用的超过30个RGB帧和超过280万个触觉样本。为了学习触觉信号的表示，我们提出了一种无监督的自动编码方案，与各种触觉感知任务的现有方法相比，其显示出4-9％的显着改进。我们的系统由两个步骤组成。首先，我们的触摸本地化模型按顺序“触摸扫描”工作空间，并使用粒子滤波器来聚合来自多个目标点击的信念。它输出对象位置的估计值，从该位置开始初始抓取。接下来，我们的重新掌握模型学习基于学习功能逐步改进掌握触觉反馈。该网络学习估计把握稳定性并预测下一个把握的调整。因此，重新执行重复操作直到我们的模型识别出稳定的抓取。最后，我们展示了广泛的实验结果，以单独使用触觉感知来掌握大量新颖物体。此外，如果将其应用于基于视力的政策之上，我们的重新抓取模型显着提高了10.6％的总体准确性。我们相信这是第一次只学习触觉感知并且没有任何事先知识的学习。

##### URL
[http://arxiv.org/abs/1805.04201](http://arxiv.org/abs/1805.04201)

##### PDF
[http://arxiv.org/pdf/1805.04201](http://arxiv.org/pdf/1805.04201)


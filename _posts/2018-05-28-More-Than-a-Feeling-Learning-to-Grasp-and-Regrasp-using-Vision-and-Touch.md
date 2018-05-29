---
layout: post
title: "More Than a Feeling: Learning to Grasp and Regrasp using Vision and Touch"
date: 2018-05-28 17:54:31
categories: arXiv_RO
tags: arXiv_RO CNN
author: Roberto Calandra, Andrew Owens, Dinesh Jayaraman, Justin Lin, Wenzhen Yuan, Jitendra Malik, Edward H. Adelson, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
For humans, the process of grasping an object relies heavily on rich tactile feedback. Recent robotic grasping work, however, has been largely based only on visual input, and thus cannot easily benefit from feedback after initiating contact. In this paper, we investigate if a robot can learn to use tactile information to iteratively and efficiently adjust its grasp. To this end, we propose an end-to-end action-conditional model that learns greedy regrasping policies from raw visuo-tactile data. This model - a deep, multimodal convolutional network - predicts the outcome of a candidate grasp adjustment, and then executes a grasp by iteratively selecting the most promising actions. Our approach requires neither calibration of the tactile sensors, nor any analytical modeling of contact forces, thus reducing the engineering effort required to obtain efficient grasping policies. We train our model with data from over 6,450 grasping trials on a two-finger gripper equipped with GelSight high-resolution tactile sensors on each finger. Across extensive experiments, our approach outperforms a variety of baselines at (i) estimating grasp adjustment outcomes, (ii) selecting efficient grasp adjustments for quick grasping, and (iii) reducing the amount of force applied at the fingers, while maintaining competitive performance. Finally, we study the choices made by our model and show that it has successfully acquired useful and interpretable grasping behaviors.

##### Abstract (translated by Google)
对于人类来说，抓住物体的过程在很大程度上依赖丰富的触觉反馈。然而，最近的机器人抓取工作主要仅基于视觉输入，因此在开始接触后不易从反馈中受益。在本文中，我们调查机器人是否可以学习如何使用触觉信息来迭代和有效地调整其掌握。为此，我们提出了一个端到端的行为 - 条件模型，该模型从原始的视觉触觉数据中学习贪婪重新聚合策略。这种模型 - 一种深层的多模式卷积网络 - 预测候选抓握调整的结果，然后通过迭代地选择最有希望的动作来执行抓握。我们的方法既不需要校准触觉传感器，也不需要对接触力进行任何分析建模，从而减少了获得高效抓取策略所需的工程量。我们使用来自超过6,450次抓握试验的数据对我们的模型进行训练，这些试验在每个手指上配备GelSight高分辨率触觉传感器的双指夹具上进行。在广泛的实验中，我们的方法在（i）估计抓取调整结果，（ii）选择有效抓取调整以快速抓取，以及（iii）减少施加在手指上的力量的同时，保持竞争性能的同时胜过各种基线。最后，我们研究了我们模型的选择，并表明它已经成功地获得了有用的和可解释的掌握行为。

##### URL
[http://arxiv.org/abs/1805.11085](http://arxiv.org/abs/1805.11085)

##### PDF
[http://arxiv.org/pdf/1805.11085](http://arxiv.org/pdf/1805.11085)


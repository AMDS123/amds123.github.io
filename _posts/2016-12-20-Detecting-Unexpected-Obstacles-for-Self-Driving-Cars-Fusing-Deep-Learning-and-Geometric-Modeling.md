---
layout: post
title: "Detecting Unexpected Obstacles for Self-Driving Cars: Fusing Deep Learning and Geometric Modeling"
date: 2016-12-20 09:55:00
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Sebastian Ramos, Stefan Gehrig, Peter Pinggera, Uwe Franke, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
The detection of small road hazards, such as lost cargo, is a vital capability for self-driving cars. We tackle this challenging and rarely addressed problem with a vision system that leverages appearance, contextual as well as geometric cues. To utilize the appearance and contextual cues, we propose a new deep learning-based obstacle detection framework. Here a variant of a fully convolutional network is used to predict a pixel-wise semantic labeling of (i) free-space, (ii) on-road unexpected obstacles, and (iii) background. The geometric cues are exploited using a state-of-the-art detection approach that predicts obstacles from stereo input images via model-based statistical hypothesis tests. We present a principled Bayesian framework to fuse the semantic and stereo-based detection results. The mid-level Stixel representation is used to describe obstacles in a flexible, compact and robust manner. We evaluate our new obstacle detection system on the Lost and Found dataset, which includes very challenging scenes with obstacles of only 5 cm height. Overall, we report a major improvement over the state-of-the-art, with relative performance gains of up to 50%. In particular, we achieve a detection rate of over 90% for distances of up to 50 m. Our system operates at 22 Hz on our self-driving platform.

##### Abstract (translated by Google)
检测货物丢失等小型道路危险是自动驾驶汽车的重要功能。我们利用外观，上下文以及几何线索的视觉系统来处理这个具有挑战性且很少解决的问题。为了利用外观和语境线索，我们提出了一个新的基于深度学习的障碍物检测框架。这里使用完全卷积网络的变体来预测（i）自由空间，（ii）路上意想不到的障碍和（iii）背景的像素方式的语义标签。利用最先进的检测方法利用几何线索，通过基于模型的统计假设检验来预测来自立体输入图像的障碍物。我们提出一个有原则的贝叶斯框架来融合语义和基于立体的检测结果。中等水平的Stixel表示法用于以灵活，紧凑和可靠的方式描述障碍物。我们在Lost and Found数据集上评估了我们的新障碍物检测系统，其中包括极具挑战性的场景，只有5厘米高的障碍物。总的来说，我们报告了最先进的一项重大改进，相对业绩增长高达50％。特别是距离达到50米时，检测率达到90％以上。我们的系统在我们的自驾平台上以22赫兹运行。

##### URL
[https://arxiv.org/abs/1612.06573](https://arxiv.org/abs/1612.06573)

##### PDF
[https://arxiv.org/pdf/1612.06573](https://arxiv.org/pdf/1612.06573)


---
layout: post
title: "Repulsion Loss: Detecting Pedestrians in a Crowd"
date: 2017-11-21 12:38:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xinlong Wang, Tete Xiao, Yuning Jiang, Shuai Shao, Jian Sun, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting individual pedestrians in a crowd remains a challenging problem since the pedestrians often gather together and occlude each other in real-world scenarios. In this paper, we first explore how a state-of-the-art pedestrian detector is harmed by crowd occlusion via experimentation, providing insights into the crowd occlusion problem. Then, we propose a novel bounding box regression loss specifically designed for crowd scenes, termed repulsion loss. This loss is driven by two motivations: the attraction by target, and the repulsion by other surrounding objects. The repulsion term prevents the proposal from shifting to surrounding objects thus leading to more crowd-robust localization. Our detector trained by repulsion loss outperforms all the state-of-the-art methods with a significant improvement in occlusion cases.

##### Abstract (translated by Google)
在人群中检测行人仍然是一个具有挑战性的问题，因为在现实世界中，行人经常聚集在一起并相互遮挡。在本文中，我们首先探讨一个最先进的行人探测器如何通过实验受到人群遮挡的伤害，从而提供人群遮挡问题的见解。然后，我们提出了一个专门为人群场景设计的新颖的边界框回归损失，称为排斥损失。这种损失是由两个动机驱动的：目标的吸引力和其他周围物体的排斥。排斥术语阻止提议转移到周围的物体，从而导致更多的人群强大的本地化。我们的检测器通过排斥损失进行训练，胜过所有最先进的方法，在遮挡情况下有显着的改善。

##### URL
[https://arxiv.org/abs/1711.07752](https://arxiv.org/abs/1711.07752)

##### PDF
[https://arxiv.org/pdf/1711.07752](https://arxiv.org/pdf/1711.07752)


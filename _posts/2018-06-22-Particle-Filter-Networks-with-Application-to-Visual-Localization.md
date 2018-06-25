---
layout: post
title: "Particle Filter Networks with Application to Visual Localization"
date: 2018-06-22 17:44:03
categories: arXiv_AI
tags: arXiv_AI Tracking
author: Peter Karkus, David Hsu, Wee Sun Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Particle filtering is a powerful method for sequential state estimation and is extensively used in many domains, including robot localization, visual tracking, etc. To apply particle filters in practice, a main challenge is to construct an effective probabilistic system model, especially when the system exhibits complex dynamic behavior or processes rich sensor information from, e.g., visual cameras. This paper introduces the Particle Filter Network (PF-Net), which captures both a system model and the particle filter algorithm in a single neural network. This unified network representation enables end-to-end model learning, which trains the model in the context of a specific algorithm, resulting in improved performance, compared with conventional model-learning methods. We apply PF-net to visual robot localization. The robot must localize in rich 3-D environments, using only a schematic 2-D floor map. In preliminary experiments, PF-Net consistently outperformed alternative learning architectures, as well as conventional model-based localization methods. PF-net learns effective models that generalize to new, unseen environments. It can also incorporate semantic labels on the floor map.

##### Abstract (translated by Google)
粒子滤波是一种有序的状态估计方法，广泛应用于许多领域，包括机器人定位，视觉跟踪等。为了在实践中应用粒子滤波器，主要的挑战是构建一个有效的概率系统模型，特别是当系统表现出复杂的动态行为或处理来自例如可视相机的丰富传感器信息。本文介绍了粒子滤波网络（PF-Net），它在单个神经网络中捕获了系统模型和粒子滤波算法。这种统一的网络表示形式实现了端到端的模型学习，与传统的模型学习方法相比，该模型在特定算法的上下文中进行训练，从而提高了性能。我们将PF-net应用于视觉机器人定位。机器人必须在丰富的3-D环境中进行本地化，仅使用示意图的2D楼层地图。在初步实验中，PF-Net始终优于其他学习架构，以及传统的基于模型的本地化方法。 PF-net学习了推广到新的，看不见的环境的有效模型。它也可以在地图上包含语义标签。

##### URL
[http://arxiv.org/abs/1805.08975](http://arxiv.org/abs/1805.08975)

##### PDF
[http://arxiv.org/pdf/1805.08975](http://arxiv.org/pdf/1805.08975)


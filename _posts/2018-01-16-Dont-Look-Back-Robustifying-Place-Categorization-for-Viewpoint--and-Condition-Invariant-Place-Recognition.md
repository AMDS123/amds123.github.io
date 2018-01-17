---
layout: post
title: "Don't Look Back: Robustifying Place Categorization for Viewpoint- and Condition-Invariant Place Recognition"
date: 2018-01-16 00:44:18
categories: arXiv_RO
tags: arXiv_RO SLAM Recognition
author: Sourav Garg, Niko Suenderhauf, Michael Milford
mathjax: true
---

* content
{:toc}

##### Abstract
When a human drives a car along a road for the first time, they later recognize where they are on the return journey typically without needing to look in their rear-view mirror or turn around to look back, despite significant viewpoint and appearance change. Such navigation capabilities are typically attributed to our semantic visual understanding of the environment [1] beyond geometry to recognizing the types of places we are passing through such as "passing a shop on the left" or "moving through a forested area". Humans are in effect using place categorization [2] to perform specific place recognition even when the viewpoint is 180 degrees reversed. Recent advances in deep neural networks have enabled high-performance semantic understanding of visual places and scenes, opening up the possibility of emulating what humans do. In this work, we develop a novel methodology for using the semantics-aware higher-order layers of deep neural networks for recognizing specific places from within a reference database. To further improve the robustness to appearance change, we develop a descriptor normalization scheme that builds on the success of normalization schemes for pure appearance-based techniques such as SeqSLAM [3]. Using two different datasets - one road-based, one pedestrian-based, we evaluate the performance of the system in performing place recognition on reverse traversals of a route with a limited field of view camera and no turn-back-and-look behaviours, and compare to existing state-of-the-art techniques and vanilla off-the-shelf features. The results demonstrate significant improvements over the existing state of the art, especially for extreme perceptual challenges that involve both great viewpoint change and environmental appearance change. We also provide experimental analyses of the contributions of the various system components.

##### Abstract (translated by Google)
当人们第一次沿着道路驾驶汽车时，他们后来认识到他们在回程中的位置，通常不需要看后视镜，也不必回头看看，尽管观点和外观有了显着的改变。这样的导航能力通常归因于我们对环境的语义视觉理解[1]，而不是几何学，以及识别我们正在经过的地点的类型，例如“通过左边的商店”或“穿过森林地带”。即使视点180度颠倒，人类也会使用地点归类[2]来执行特定的地点识别。深度神经网络的最新进展使得对视觉场所和场景的高性能语义理解成为可能，从而开辟了模拟人类行为的可能性。在这项工作中，我们开发了一种新的方法，使用深层神经网络的语义感知高阶层来识别参考数据库中的特定地点。为了进一步提高对外观变化的鲁棒性，我们开发了一个描述符规范化方案，该方案建立在基于外观的纯技术（如SeqSLAM [3]）的规范化方案的成功基础上。使用两个不同的数据集（一个是基于道路的，一个是基于行人的），我们评估系统在有限视野摄像机的路线的反向遍历中进行地点识别时的性能，并且没有折回看的行为，并与现有的最先进的技术和香草现成的功能进行比较。结果表明相对于现有技术的显着改进，特别是对于涉及极大视点变化和环境外观变化的极端感知挑战。我们还提供各种系统组件的贡献的实验分析。

##### URL
[http://arxiv.org/abs/1801.05078](http://arxiv.org/abs/1801.05078)

##### PDF
[http://arxiv.org/pdf/1801.05078](http://arxiv.org/pdf/1801.05078)


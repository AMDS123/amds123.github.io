---
layout: post
title: "A Computational Model for Amodal Completion"
date: 2016-03-29 14:49:41
categories: arXiv_CV
tags: arXiv_CV
author: Maria Oliver, Gloria Haro, Mariella Dimiccoli, Baptiste Mazin, Coloma Ballester
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a computational model to recover the most likely interpretation of the 3D scene structure from a planar image, where some objects may occlude others. The estimated scene interpretation is obtained by integrating some global and local cues and provides both the complete disoccluded objects that form the scene and their ordering according to depth. Our method first computes several distal scenes which are compatible with the proximal planar image. To compute these different hypothesized scenes, we propose a perceptually inspired object disocclusion method, which works by minimizing the Euler's elastica as well as by incorporating the relatability of partially occluded contours and the convexity of the disoccluded objects. Then, to estimate the preferred scene we rely on a Bayesian model and define probabilities taking into account the global complexity of the objects in the hypothesized scenes as well as the effort of bringing these objects in their relative position in the planar image, which is also measured by an Euler's elastica-based quantity. The model is illustrated with numerical experiments on, both, synthetic and real images showing the ability of our model to reconstruct the occluded objects and the preferred perceptual order among them. We also present results on images of the Berkeley dataset with provided figure-ground ground-truth labeling.

##### Abstract (translated by Google)
本文提出了一个计算模型来恢复从一个平面图像的3D场景结构的最可能的解释，其中一些对象可能会包括其他对象。通过整合一些全局和局部线索来获得估计的场景解释，并且提供形成场景的完全隔绝物体和根据深度的排序。我们的方法首先计算与近端平面图像兼容的多个远端场景。为了计算这些不同的假设场景，我们提出了一种感知的物体去除方法，它通过最小化欧拉弹性以及通过结合部分遮挡轮廓的可靠性和遮挡物体的凸面来实现。然后，为了估计首选场景，我们依赖于贝叶斯模型，并且在假设场景中考虑对象的全局复杂性以及将这些对象置于其在平面图像中的相对位置上的努力来定义概率，这也是用欧拉弹性数量来衡量。该模型用合成和真实图像的数值实验进行说明，显示了我们的模型重建遮挡物体的能力以及它们之间的首选感知顺序。我们还提供了伯克利数据集的图像结果，并提供了基于地面的真实标注。

##### URL
[https://arxiv.org/abs/1511.08418](https://arxiv.org/abs/1511.08418)

##### PDF
[https://arxiv.org/pdf/1511.08418](https://arxiv.org/pdf/1511.08418)


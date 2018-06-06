---
layout: post
title: "Practical Deep Stereo : Toward applications-friendly deep stereo matching"
date: 2018-06-05 13:24:40
categories: arXiv_CV
tags: arXiv_CV Inference
author: Stepan Tulyakov, Anton Ivanov, Francois Fleuret
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end deep-learning networks recently demonstrated extremely good perfor- mance for stereo matching. However, existing networks are difficult to use for practical applications since (1) they are memory-hungry and unable to process even modest-size images, (2) they have to be trained for a given disparity range. The Practical Deep Stereo (PDS) network that we propose addresses both issues: First, its architecture relies on novel bottleneck modules that drastically reduce the memory footprint in inference, and additional design choices allow to handle greater image size during training. This results in a model that leverages large image context to resolve matching ambiguities. Second, a novel sub-pixel cross- entropy loss combined with a MAP estimator make this network less sensitive to ambiguous matches, and applicable to any disparity range without re-training. We compare PDS to state-of-the-art methods published over the recent months, and demonstrate its superior performance on FlyingThings3D and KITTI sets.

##### Abstract (translated by Google)
端到端深度学习网络最近展示了极佳的立体匹配性能。然而，现有网络难以用于实际应用，因为（1）它们需要内存并且无法处理即使是中等大小的图像，（2）必须针对给定视差范围进行训练。我们建议，同时解决问题的实用深受立体声（PDS）网络：首先，它的体系结构依赖于新的瓶颈模块大大减少推理的内存占用，以及额外的设计选择，允许在训练中处理更大的图像尺寸。这导致利用大型图像上下文来解决匹配歧义的模型。其次，与MAP估计相结合的新颖的亚像素交叉熵损失使得该网络对模糊匹配较不敏感，并且适用于没有重新训练的任何视差范围。我们将PDS与最近几个月发布的最先进的方法进行比较，并展示其在FlyingThings3D和KITTI套装上的出众表现。

##### URL
[http://arxiv.org/abs/1806.01677](http://arxiv.org/abs/1806.01677)

##### PDF
[http://arxiv.org/pdf/1806.01677](http://arxiv.org/pdf/1806.01677)


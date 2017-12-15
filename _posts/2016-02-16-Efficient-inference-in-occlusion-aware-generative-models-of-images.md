---
layout: post
title: "Efficient inference in occlusion-aware generative models of images"
date: 2016-02-16 07:22:02
categories: arXiv_CV
tags: arXiv_CV Inference
author: Jonathan Huang, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
We present a generative model of images based on layering, in which image layers are individually generated, then composited from front to back. We are thus able to factor the appearance of an image into the appearance of individual objects within the image --- and additionally for each individual object, we can factor content from pose. Unlike prior work on layered models, we learn a shape prior for each object/layer, allowing the model to tease out which object is in front by looking for a consistent shape, without needing access to motion cues or any labeled data. We show that ordinary stochastic gradient variational bayes (SGVB), which optimizes our fully differentiable lower-bound on the log-likelihood, is sufficient to learn an interpretable representation of images. Finally we present experiments demonstrating the effectiveness of the model for inferring foreground and background objects in images.

##### Abstract (translated by Google)
我们提出了基于分层的图像生成模型，其中图像层是单独生成的，然后从前到后进行合成。因此，我们可以将图像的外观与图像内单个对象的外观相结合 - 此外对于每个单独的对象，我们可以将姿势的内容分解。与以前在分层模型上的工作不同，我们先学习每个对象/图层的形状，通过查找一致的形状，允许模型梳理出前面的对象，而无需访问运动提示或任何标记的数据。我们表明，普通的随机梯度变分贝叶斯（SGVB），它优化我们完全可微的对数似然下界，足以学习一个可解释的图像表示。最后，我们提出了实验来证明模型在推断图像中前景和背景物体的有效性。

##### URL
[https://arxiv.org/abs/1511.06362](https://arxiv.org/abs/1511.06362)

##### PDF
[https://arxiv.org/pdf/1511.06362](https://arxiv.org/pdf/1511.06362)


---
layout: post
title: "Open Logo Detection Challenge"
date: 2018-07-05 12:40:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning Detection
author: Hang Su, Xiatian Zhu, Shaogang Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Existing logo detection benchmarks consider artificial deployment scenarios by assuming that large training data with fine-grained bounding box annotations for each class are available for model training. Such assumptions are often invalid in realistic logo detection scenarios where new logo classes come progressively and require to be detected with little or none budget for exhaustively labelling fine-grained training data for every new class. Existing benchmarks are thus unable to evaluate the true performance of a logo detection method in realistic and open deployments. In this work, we introduce a more realistic and challenging logo detection setting, called Open Logo Detection. Specifically, this new setting assumes fine-grained labelling only on a small proportion of logo classes whilst the remaining classes have no labelled training data to simulate the open deployment. We further create an open logo detection benchmark, called OpenLogo,to promote the investigation of this new challenge. OpenLogo contains 27,189 images from 309 logo classes, built by aggregating/refining 7 existing datasets and establishing an open logo detection evaluation protocol. To address this challenge, we propose a Context Adversarial Learning (CAL) approach to synthesising training data with coherent logo instance appearance against diverse background context for enabling more effective optimisation of contemporary deep learning detection models. Experiments show the performance advantage of CAL over existing state-of-the-art alternative methods on the more realistic and challenging OpenLogo benchmark.

##### Abstract (translated by Google)
现有的徽标检测基准通过假设每个类的具有细粒度边界框注释的大型训练数据可用于模型训练来考虑人工部署场景。在现实的徽标检测方案中，这种假设通常是无效的，其中新的徽标类逐渐出现并且需要以很少或没有预算来检测，以便为每个新类别详尽地标记细粒度的训练数据。因此，现有的基准测试无法评估徽标检测方法在实际和开放式部署中的真实性能。在这项工作中，我们引入了更现实和具有挑战性的徽标检测设置，称为开放徽标检测。具体来说，这个新设置假定仅对一小部分徽标类别进行细粒度标记，而其余类别没有标记的训练数据来模拟开放部署。我们进一步创建了一个名为OpenLogo的开放式徽标检测基准，以促进对这一新挑战的调查。 OpenLogo包含来自309个徽标类的27,189个图像，通过聚合/优化7个现有数据集并建立开放徽标检测评估协议来构建。为了应对这一挑战，我们提出了一种上下文对抗性学习（CAL）方法，用于将训练数据与连贯的徽标实例外观相结合，以适应不同的背景环境，从而更有效地优化当代深度学习检测模型。实验表明，CAL比现有的最先进的替代方法在更现实和更具挑战性的OpenLogo基准测试中具有性能优势。

##### URL
[http://arxiv.org/abs/1807.01964](http://arxiv.org/abs/1807.01964)

##### PDF
[http://arxiv.org/pdf/1807.01964](http://arxiv.org/pdf/1807.01964)


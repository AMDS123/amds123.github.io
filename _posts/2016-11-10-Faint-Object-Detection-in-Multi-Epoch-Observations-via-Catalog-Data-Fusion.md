---
layout: post
title: "Faint Object Detection in Multi-Epoch Observations via Catalog Data Fusion"
date: 2016-11-10 03:16:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Survey Detection
author: Tamas Budavari, Alexander S. Szalay, Thomas J. Loredo
mathjax: true
---

* content
{:toc}

##### Abstract
Observational astronomy in the time-domain era faces several new challenges. One of them is the efficient use of observations obtained at multiple epochs. The work presented here addresses faint object detection with multi-epoch data, and describes an incremental strategy for separating real objects from artifacts in ongoing surveys, in situations where the single-epoch data are summaries of the full image data, such as single-epoch catalogs of flux and direction estimates for candidate sources. The basic idea is to produce low-threshold single-epoch catalogs, and use a probabilistic approach to accumulate catalog information across epochs; this is in contrast to more conventional strategies based on co-added or stacked image data across all epochs. We adopt a Bayesian approach, addressing object detection by calculating the marginal likelihoods for hypotheses asserting there is no object, or one object, in a small image patch containing at most one cataloged source at each epoch. The object-present hypothesis interprets the sources in a patch at different epochs as arising from a genuine object; the no-object (noise) hypothesis interprets candidate sources as spurious, arising from noise peaks. We study the detection probability for constant-flux objects in a simplified Gaussian noise setting, comparing results based on single exposures and stacked exposures to results based on a series of single-epoch catalog summaries. Computing the detection probability based on catalog data amounts to generalized cross-matching: it is the product of a factor accounting for matching of the estimated fluxes of candidate sources, and a factor accounting for matching of their estimated directions. We find that probabilistic fusion of multi-epoch catalog information can detect sources with only modest sacrifice in sensitivity and selectivity compared to stacking.

##### Abstract (translated by Google)
时空时代的观测天文学面临着一些新的挑战。其中之一是有效利用在多个时期获得的观测资料。这里介绍的工作提出了多时元数据的微弱物体检测，并描述了一种增量策略，即在单历元数据是完整图像数据的摘要的情况下，将正在进行的勘测中的真实物体与工件分开，例如单历元候选资源的通量和方向估计目录。其基本思想是生成低门限的单一时代目录，并使用概率方法在各个时代积累目录信息;这与在所有时期基于共同添加或堆叠图像数据的更传统策略形成对比。我们采用贝叶斯方法，通过计算在每个时期最多包含一个编目源的小图像片断中没有对象或一个对象的假设的边际可能性，来处理对象检测。客体存在的假设在不同的时代以不同的时代解释源自一个真正的客体;无对象（噪声）假设将候选源解释为由噪声峰值引起的伪造。我们在简化的高斯噪声设置中研究常量通量对象的检测概率，将基于单次曝光和叠加曝光的结果与基于一系列单历元目录摘要的结果进行比较。根据目录数据来计算检测概率相当于广义交叉匹配：它是估计候选源通量匹配的因素和估计方向匹配的一个因素的乘积。我们发现，与叠加相比，多时期目录信息的概率融合可以在灵敏度和选择性方面仅仅适度地牺牲来源。

##### URL
[https://arxiv.org/abs/1611.03171](https://arxiv.org/abs/1611.03171)

##### PDF
[https://arxiv.org/pdf/1611.03171](https://arxiv.org/pdf/1611.03171)


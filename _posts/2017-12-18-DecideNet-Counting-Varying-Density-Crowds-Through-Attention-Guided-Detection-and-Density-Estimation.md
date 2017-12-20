---
layout: post
title: "DecideNet: Counting Varying Density Crowds Through Attention Guided Detection and Density Estimation"
date: 2017-12-18 21:17:35
categories: arXiv_CV
tags: arXiv_CV Attention Detection
author: Jiang Liu, Chenqiang Gao, Deyu Meng, Alexander G. Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
In real-world crowd counting applications, the crowd densities vary greatly in spatial and temporal domains. A detection based counting method will estimate crowds accurately in low density scenes, while its reliability in congested areas is downgraded. A regression based approach, on the other hand, captures the general density information in crowded regions. Without knowing the location of each person, it tends to overestimate the count in low density areas. Thus, exclusively using either one of them is not sufficient to handle all kinds of scenes with varying densities. To address this issue, a novel end-to-end crowd counting framework, named DecideNet (DEteCtIon and Density Estimation Network) is proposed. It can adaptively decide the appropriate counting mode for different locations on the image based on its real density conditions. DecideNet starts with estimating the crowd density by generating detection and regression based density maps separately. To capture inevitable variation in densities, it incorporates an attention module, meant to adaptively assess the reliability of the two types of estimations. The final crowd counts are obtained with the guidance of the attention module to adopt suitable estimations from the two kinds of density maps. Experimental results show that our method achieves state-of-the-art performance on three challenging crowd counting datasets.

##### Abstract (translated by Google)
在现实世界的人群计数应用中，人群密度在空间和时间方面差异很大。基于检测的计数方法将在低密度场景中准确估计人群，而在拥挤区域的可靠性降低。另一方面，基于回归的方法捕捉拥挤地区的一般密度信息。不知道每个人的位置，往往会高估低密度地区的人数。因此，仅仅使用其中任何一个都不足以处理各种密度不同的场景。为了解决这个问题，提出了一个名为DecideNet（DEteCtIon and Density Estimation Network）的新型端到端人群统计框架。它可以根据实际密度条件自适应地决定图像上不同位置的适当计数模式。 DecideNet首先通过分别生成基于检测和回归的密度图来估计人群密度。为了捕捉不可避免的密度变化，它包含一个注意模块，旨在适应性地评估这两种估计的可靠性。在关注模块的引导下获得最终的人群数量，以从两种密度图中采用适当的估计。实验结果表明，我们的方法达到了三个具有挑战性的人群计数数据集的最先进的性能。

##### URL
[http://arxiv.org/abs/1712.06679](http://arxiv.org/abs/1712.06679)

##### PDF
[http://arxiv.org/pdf/1712.06679](http://arxiv.org/pdf/1712.06679)


---
layout: post
title: "Modeling Retinal Ganglion Cell Population Activity with Restricted Boltzmann Machines"
date: 2017-01-17 10:01:46
categories: arXiv_CV
tags: arXiv_CV GAN
author: Matteo Zanotto, Riccardo Volpi, Alessandro Maccione, Luca Berdondini, Diego Sona, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
The retina is a complex nervous system which encodes visual stimuli before higher order processing occurs in the visual cortex. In this study we evaluated whether information about the stimuli received by the retina can be retrieved from the firing rate distribution of Retinal Ganglion Cells (RGCs), exploiting High-Density 64x64 MEA technology. To this end, we modeled the RGC population activity using mean-covariance Restricted Boltzmann Machines, latent variable models capable of learning the joint distribution of a set of continuous observed random variables and a set of binary unobserved random units. The idea was to figure out if binary latent states encode the regularities associated to different visual stimuli, as modes in the joint distribution. We measured the goodness of mcRBM encoding by calculating the Mutual Information between the latent states and the stimuli shown to the retina. Results show that binary states can encode the regularities associated to different stimuli, using both gratings and natural scenes as stimuli. We also discovered that hidden variables encode interesting properties of retinal activity, interpreted as population receptive fields. We further investigated the ability of the model to learn different modes in population activity by comparing results associated to a retina in normal conditions and after pharmacologically blocking GABA receptors (GABAC at first, and then also GABAA and GABAB). As expected, Mutual Information tends to decrease if we pharmacologically block receptors. We finally stress that the computational method described in this work could potentially be applied to any kind of neural data obtained through MEA technology, though different techniques should be applied to interpret the results.

##### Abstract (translated by Google)
视网膜是一种复杂的神经系统，在视觉皮层发生高阶处理之前编码视觉刺激。在这项研究中，我们评估是否可以从视网膜神经节细胞（RGC）的利用高密度64×64 MEA技术的发射率分布中获取有关视网膜接收的刺激的信息。为此，我们使用平均协方差受限玻耳兹曼机（Boltzmann Machines）模拟了研资局人口活动，能够学习一组连续观察到的随机变量的联合分布的潜变量模型以及一组二元未观察到的随机单元。这个想法是要弄清楚二元潜伏状态是否编码与不同的视觉刺激相关的规律，如联合分布中的模式。我们通过计算潜伏状态和视网膜上显示的刺激之间的相互信息来测量mcRBM编码的优劣。结果表明，二进制状态可以编码与不同的刺激有关的规则，使用光栅和自然场景作为刺激。我们还发现隐藏的变量编码有趣的视网膜活动性质，解释为人口接受领域。我们通过比较正常情况下与视网膜相关的结果以及药理学阻断GABA受体（首先是GABA，然后是GABAA和GABAB）之后，我们进一步研究了模型在群体活动中学习不同模式的能力。正如所料，互信息往往会减少，如果我们药理学阻断受体。我们最后强调，这项工作中所描述的计算方法可以应用于通过MEA技术获得的任何类型的神经数据，尽管应用不同的技术来解释结果。

##### URL
[https://arxiv.org/abs/1701.02898](https://arxiv.org/abs/1701.02898)

##### PDF
[https://arxiv.org/pdf/1701.02898](https://arxiv.org/pdf/1701.02898)


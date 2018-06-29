---
layout: post
title: "State-aware Anti-drift Robust Correlation Tracking"
date: 2018-06-28 03:58:44
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Optimization Quantitative Relation
author: Yuqi Han, Chenwei Deng, Zengshuo Zhang, Jinghong Nan, Baojun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filter (CF) based trackers have aroused increasing attentions in visual tracking field due to the superior performance on several datasets while maintaining high running speed. For each frame, an ideal filter is trained in order to discriminate the target from its surrounding background. Considering that the target always undergoes external and internal interference during tracking procedure, the trained filter should take consideration of not only the external distractions but also the target appearance variation synchronously. To this end, we present a State-aware Anti-drift Tracker (SAT) in this paper, which jointly model the discrimination and reliability information in filter learning. Specifically, global context patches are incorporated into filter training stage to better distinguish the target from backgrounds. Meanwhile, a color-based reliable mask is learned to encourage the filter to focus on more reliable regions suitable for tracking. We show that the proposed optimization problem could be efficiently solved using Alternative Direction Method of Multipliers and fully carried out in Fourier domain. Extensive experiments are conducted on OTB-100 datasets to compare the SAT tracker (both hand-crafted feature and CNN feature) with other relevant state-of-the-art methods. Both quantitative and qualitative evaluations further demonstrate the effectiveness and robustness of the proposed work.

##### Abstract (translated by Google)
基于相关滤波器（CF）的跟踪器由于在保持高运行速度的同时在多个数据集上具有优异的性能而在视觉跟踪领域引起了越来越多的关注。对于每个帧，训练一个理想的滤波器以区分目标与其周围背景。考虑到跟踪过程中目标始终受到外部和内部的干扰，训练后的滤波器不仅要考虑外部干扰，还要考虑目标外观变化。为此，本文提出了一种状态感知反漂移跟踪器（SAT），它将滤波器学习中的识别和可靠性信息联合建模。具体而言，将全局上下文补丁纳入过滤培训阶段，以更好地区分目标和背景。同时，学会了基于颜色的可靠掩模，以鼓励滤波器专注于适合追踪的更可靠区域。我们表明，提出的优化问题可以有效地解决使用替代方向的乘法器，并充分执行傅立叶域。在OTB-100数据集上进行了大量实验，将SAT跟踪器（手工制作的特征和CNN特征）与其他相关的最先进的方法进行比较。定量和定性评估都进一步证明了拟议工作的有效性和稳健性。

##### URL
[http://arxiv.org/abs/1806.10759](http://arxiv.org/abs/1806.10759)

##### PDF
[http://arxiv.org/pdf/1806.10759](http://arxiv.org/pdf/1806.10759)


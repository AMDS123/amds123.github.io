---
layout: post
title: "ActiveStereoNet: End-to-End Self-Supervised Learning for Active Stereo Systems"
date: 2018-07-16 16:55:19
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Quantitative
author: Yinda Zhang, Sameh Khamis, Christoph Rhemann, Julien Valentin, Adarsh Kowdle, Vladimir Tankovich, Michael Schoenberg, Shahram Izadi, Thomas Funkhouser, Sean Fanello
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present ActiveStereoNet, the first deep learning solution for active stereo systems. Due to the lack of ground truth, our method is fully self-supervised, yet it produces precise depth with a subpixel precision of $1/30th$ of a pixel; it does not suffer from the common over-smoothing issues; it preserves the edges; and it explicitly handles occlusions. We introduce a novel reconstruction loss that is more robust to noise and texture-less patches, and is invariant to illumination changes. The proposed loss is optimized using a window-based cost aggregation with an adaptive support weight scheme. This cost aggregation is edge-preserving and smooths the loss function, which is key to allow the network to reach compelling results. Finally we show how the task of predicting invalid regions, such as occlusions, can be trained end-to-end without ground-truth. This component is crucial to reduce blur and particularly improves predictions along depth discontinuities. Extensive quantitatively and qualitatively evaluations on real and synthetic data demonstrate state of the art results in many challenging scenes.

##### Abstract (translated by Google)
在本文中，我们介绍ActiveStereoNet，这是有源立体声系统的第一个深度学习解决方案。由于缺乏基本事实，我们的方法是完全自我监督的，但它产生精确的深度，子像素精度为$ 1 / 30th $像素;它没有遭受常见的过度平滑问题;它保留了边缘;它明确地处理遮挡。我们引入了一种新的重建损耗，它对噪声和无纹理贴片更加稳健，并且对于光照变化是不变的。使用具有自适应支持权重方案的基于窗口的成本聚合来优化所提出的损失。这种成本聚合是边缘保留并使损失函数平滑，这是使网络达到令人信服的结果的关键。最后，我们展示了预测无效区域（如遮挡）的任务如何在没有地面实况的情况下进行端到端的训练。该组件对于减少模糊至关重要，特别是改善了深度不连续性的预测。对真实和合成数据进行广泛的定量和定性评估，证明了在许多具有挑战性的场景中的最新技术成果。

##### URL
[http://arxiv.org/abs/1807.06009](http://arxiv.org/abs/1807.06009)

##### PDF
[http://arxiv.org/pdf/1807.06009](http://arxiv.org/pdf/1807.06009)


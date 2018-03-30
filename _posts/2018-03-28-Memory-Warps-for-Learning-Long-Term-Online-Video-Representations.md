---
layout: post
title: "Memory Warps for Learning Long-Term Online Video Representations"
date: 2018-03-28 21:36:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Tuan-Hung Vu, Wongun Choi, Samuel Schulter, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel memory-based online video representation that is efficient, accurate and predictive. This is in contrast to prior works that often rely on computationally heavy 3D convolutions, ignore actual motion when aligning features over time, or operate in an off-line mode to utilize future frames. In particular, our memory (i) holds the feature representation, (ii) is spatially warped over time to compensate for observer and scene motions, (iii) can carry long-term information, and (iv) enables predicting feature representations in future frames. By exploring a variant that operates at multiple temporal scales, we efficiently learn across even longer time horizons. We apply our online framework to object detection in videos, obtaining a large 2.3 times speed-up and losing only 0.9% mAP on ImageNet-VID dataset, compared to prior works that even use future frames. Finally, we demonstrate the predictive property of our representation in two novel detection setups, where features are propagated over time to (i) significantly enhance a real-time detector by more than 10% mAP in a multi-threaded online setup and to (ii) anticipate objects in future frames.

##### Abstract (translated by Google)
本文提出了一种高效，准确和预测的基于内存的在线视频表示。这与通常依赖计算量大的3D卷积的先前的作品形成对比，在随着时间的推移对齐特征时忽略实际运动，或者在离线模式下操作以利用未来的帧。特别是，我们的记忆（i）保存了特征表示，（ii）随时间空间扭曲以补偿观察者和场景的运动，（iii）能够携带长期信息，并且（iv）能够预测未来帧中的特征表示。通过探索在多个时间尺度上运行的变体，我们有效地学习了更长的时间范围。我们将我们的在线框架应用于视频中的对象检测，与以前的作品甚至使用未来的帧相比，ImageNet-VID数据集获得2.3倍的加速并仅损失0.9％的mAP。最后，我们演示了我们在两种新颖检测设置中的表示的预测属性，其中特征随时间传播以（i）在多线程在线设置中将实时检测器显着增强10％以上的mAP，并且（ii） ）预测未来帧中的对象。

##### URL
[http://arxiv.org/abs/1803.10861](http://arxiv.org/abs/1803.10861)

##### PDF
[http://arxiv.org/pdf/1803.10861](http://arxiv.org/pdf/1803.10861)


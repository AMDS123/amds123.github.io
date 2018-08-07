---
layout: post
title: "Towards Closing the Gap in Weakly Supervised Semantic Segmentation with DCNNs: Combining Local and Global Models"
date: 2018-08-05 14:19:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Semantic_Segmentation Prediction
author: Christoph Mayer, Radu Timofte, Grégory Paul
mathjax: true
---

* content
{:toc}

##### Abstract
Generating training sets for deep convolutional neural networks is a bottleneck for modern real-world applications. This is a demanding tasks for applications where annotating training data is costly, such as in semantic segmentation. In the literature, there is still a gap between the performance achieved by a network trained on full and on weak annotations. In this paper, we establish a strategy to measure this gap and to identify the ingredients necessary to close it. On scribbles, we establish state-of-the-art results comparable to the latest published ones (Tang et al., 2018, arXiv:1804.01346): we obtain a gap in mIoU of 2.4% without CRF (2.8% in Tang et al., 2018, arXiv:1804.01346), and 2.9% with CRF post-processing (2.3% in Tang et al., 2018, arXiv:1804.01346). However, we use completely different ideas: combining local and global annotator models and regularising their prediction to train DeepLabV2. Finally, closing the gap was reported only recently for bounding boxes in Khoreva et al. (arXiv:1603.07485v2), by requiring 10x more training images. By simulating varying amounts of pixel-level annotations respecting scribble human annotations statistics, we show that our training strategy reacts to small increases in the amount of annotations and requires only 2-5x more annotated pixels, closing the gap with only 3.1% of all pixels annotated. This work contributes new ideas towards closing the gap in real-world applications.

##### Abstract (translated by Google)
为深度卷积神经网络生成训练集是现代实际应用的瓶颈。对于注释训练数据成本高昂的应用程序（例如语义分段），这是一项要求苛刻的任务。在文献中，在完全和弱注释训练的网络所实现的性能之间仍然存在差距。在本文中，我们制定了一种策略来衡量这一差距并确定关闭它所需的成分。在涂鸦上，我们建立了与最新发表的结果相当的最新结果（Tang et al。，2018，arXiv：1804.01346）：我们在没有CRF的情况下获得了2.4％的mIoU差距（在Tang等人中为2.8％） 。，2018，arXiv：1804.01346），以及2.9％的CRF后处理（在Tang等人，2018，arxiv：1804.01346中为2.3％）。然而，我们使用完全不同的想法：结合局部和全局注释器模型并规范其预测以训练DeepLabV2。最后，最近才报道了Khoreva等人的边界框。 （arXiv：1603.07485v2），需要10倍以上的训练图像。通过模拟关于涂鸦人类注释统计数据的不同数量的像素级注释，我们显示我们的训练策略对注释量的小幅增加作出反应，并且仅需要多2到5倍的注释像素，仅用所有像素的3.1％缩小差距注释。这项工作为缩小实际应用中的差距提供了新思路。

##### URL
[https://arxiv.org/abs/1808.01625](https://arxiv.org/abs/1808.01625)

##### PDF
[https://arxiv.org/pdf/1808.01625](https://arxiv.org/pdf/1808.01625)


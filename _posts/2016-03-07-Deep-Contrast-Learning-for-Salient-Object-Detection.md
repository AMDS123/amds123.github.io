---
layout: post
title: "Deep Contrast Learning for Salient Object Detection"
date: 2016-03-07 08:50:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Guanbin Li, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Salient object detection has recently witnessed substantial progress due to powerful features extracted using deep convolutional neural networks (CNNs). However, existing CNN-based methods operate at the patch level instead of the pixel level. Resulting saliency maps are typically blurry, especially near the boundary of salient objects. Furthermore, image patches are treated as independent samples even when they are overlapping, giving rise to significant redundancy in computation and storage. In this CVPR 2016 paper, we propose an end-to-end deep contrast network to overcome the aforementioned limitations. Our deep network consists of two complementary components, a pixel-level fully convolutional stream and a segment-wise spatial pooling stream. The first stream directly produces a saliency map with pixel-level accuracy from an input image. The second stream extracts segment-wise features very efficiently, and better models saliency discontinuities along object boundaries. Finally, a fully connected CRF model can be optionally incorporated to improve spatial coherence and contour localization in the fused result from these two streams. Experimental results demonstrate that our deep model significantly improves the state of the art.

##### Abstract (translated by Google)
由于使用深度卷积神经网络（CNN）提取的强大特征，凸显对象检测最近已经取得了实质性进展。但是，现有的基于CNN的方法是在补丁级而不是像素级上运行的。产生的显着图通常是模糊的，尤其是在显着物体的边界附近。此外，即使图像块重叠，图像块也被视为独立的样本，从而导致计算和存储的显着冗余。在这份CVPR 2016论文中，我们提出了一个端到端的深度对比网络来克服上述限制。我们的深层网络包含两个互补的组件，一个像素级完全卷积流和一个分段空间池流。第一个流直接从输入图像生成具有像素级精度的显着图。第二流非常有效地提取分段特征，并更好地模拟沿着对象边界的显着不连续性。最后，一个完全连接的CRF模型可以选择合并，以提高这两个流的融合结果的空间相干性和轮廓定位。实验结果表明，我们的深层模型显着改善了现有技术。

##### URL
[https://arxiv.org/abs/1603.01976](https://arxiv.org/abs/1603.01976)

##### PDF
[https://arxiv.org/pdf/1603.01976](https://arxiv.org/pdf/1603.01976)


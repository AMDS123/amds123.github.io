---
layout: post
title: "Learning Rich Features for Image Manipulation Detection"
date: 2018-05-13 21:29:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention GAN Detection
author: Peng Zhou, Xintong Han, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Image manipulation detection is different from traditional semantic object detection because it pays more attention to tampering artifacts than to image content, which suggests that richer features need to be learned. We propose a two-stream Faster R-CNN network and train it endto- end to detect the tampered regions given a manipulated image. One of the two streams is an RGB stream whose purpose is to extract features from the RGB image input to find tampering artifacts like strong contrast difference, unnatural tampered boundaries, and so on. The other is a noise stream that leverages the noise features extracted from a steganalysis rich model filter layer to discover the noise inconsistency between authentic and tampered regions. We then fuse features from the two streams through a bilinear pooling layer to further incorporate spatial co-occurrence of these two modalities. Experiments on four standard image manipulation datasets demonstrate that our two-stream framework outperforms each individual stream, and also achieves state-of-the-art performance compared to alternative methods with robustness to resizing and compression.

##### Abstract (translated by Google)
图像操纵检测不同于传统的语义对象检测，因为它更注重篡改伪像而不是图像内容，这表明需要学习更丰富的特征。我们提出了一个更快的R-CNN双流网络，并将其训练到端到端，以检测被操纵的图像的篡改区域。两个流之一是RGB流，其目的是从RGB图像输入中提取特征以找到篡改伪像，如强烈的对比度差异，非自然的篡改边界等等。另一种是噪声流，利用从富含隐写分析的模型滤波器层中提取的噪声特征来发现真实和篡改区域之间的噪声不一致性。然后，我们通过双线性汇聚层融合来自两个流的特征，以进一步结合这两种模态的空间共现。对四个标准图像处理数据集的实验表明，我们的双流框架优于每个单独的流，并且与可调整大小和压缩稳健性的替代方法相比，还实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1805.04953](https://arxiv.org/abs/1805.04953)

##### PDF
[https://arxiv.org/pdf/1805.04953](https://arxiv.org/pdf/1805.04953)


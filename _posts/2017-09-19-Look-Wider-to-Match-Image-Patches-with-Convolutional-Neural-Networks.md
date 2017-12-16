---
layout: post
title: "Look Wider to Match Image Patches with Convolutional Neural Networks"
date: 2017-09-19 04:31:43
categories: arXiv_CV
tags: arXiv_CV CNN
author: Haesol Park, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
When a human matches two images, the viewer has a natural tendency to view the wide area around the target pixel to obtain clues of right correspondence. However, designing a matching cost function that works on a large window in the same way is difficult. The cost function is typically not intelligent enough to discard the information irrelevant to the target pixel, resulting in undesirable artifacts. In this paper, we propose a novel learn a stereo matching cost with a large-sized window. Unlike conventional pooling layers with strides, the proposed per-pixel pyramid-pooling layer can cover a large area without a loss of resolution and detail. Therefore, the learned matching cost function can successfully utilize the information from a large area without introducing the fattening effect. The proposed method is robust despite the presence of weak textures, depth discontinuity, illumination, and exposure difference. The proposed method achieves near-peak performance on the Middlebury benchmark.

##### Abstract (translated by Google)
当人匹配两个图像时，观察者自然倾向于观察目标像素周围的广阔区域以获得正确对应的线索。然而，以相同的方式设计在大窗口上工作的匹配成本函数是困难的。成本函数通常不够智能以丢弃与目标像素无关的信息，导致不希望的伪像。在本文中，我们提出了一种新颖的学习与大窗口的立体匹配成本。与传统的具有步幅的池化层不同，所提出的每像素金字塔池化层可以覆盖大面积而不会损失分辨率和细节。因此，学习匹配成本函数可以成功地利用大面积的信息，而不会引入肥育效应。尽管存在弱纹理，深度不连续性，照明和曝光差异，但所提出的方法仍是可靠的。所提出的方法在Middlebury基准上达到接近峰值的性能。

##### URL
[https://arxiv.org/abs/1709.06248](https://arxiv.org/abs/1709.06248)

##### PDF
[https://arxiv.org/pdf/1709.06248](https://arxiv.org/pdf/1709.06248)


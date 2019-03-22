---
layout: post
title: "Progressive Sparse Local Attention for Video object detection"
date: 2019-03-21 17:33:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Attention Detection
author: Chaoxu Guo, Bin Fan, Jie Gu, Qian Zhang, Shiming Xiang, Veronique Prinet, Chunhong Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Transferring image-based object detectors to domain of videos remains a challenging problem. Previous efforts mostly exploit optical flow to propagate features across frames, aiming to achieve a good trade-off between performance and computational complexity. However, introducing an extra model to estimate optical flow would significantly increase the overall model size. The gap between optical flow and high-level features can hinder it from establishing the spatial correspondence accurately. Instead of relying on optical flow, this paper proposes a novel module called Progressive Sparse Local Attention (PSLA), which establishes the spatial correspondence between features across frames in a local region with progressive sparse strides and uses the correspondence to propagate features. Based on PSLA, Recursive Feature Updating (RFU) and Dense feature Transforming (DFT) are introduced to model temporal appearance and enrich feature representation respectively. Finally, a novel framework for video object detection is proposed. Experiments on ImageNet VID are conducted. Our framework achieves a state-of-the-art speed-accuracy trade-off with significantly reduced model capacity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09126](http://arxiv.org/abs/1903.09126)

##### PDF
[http://arxiv.org/pdf/1903.09126](http://arxiv.org/pdf/1903.09126)


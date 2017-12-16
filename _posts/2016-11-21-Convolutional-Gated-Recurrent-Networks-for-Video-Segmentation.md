---
layout: post
title: "Convolutional Gated Recurrent Networks for Video Segmentation"
date: 2016-11-21 21:47:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Semantic_Segmentation
author: Mennatullah Siam, Sepehr Valipour, Martin Jagersand, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation has recently witnessed major progress, where fully convolutional neural networks have shown to perform well. However, most of the previous work focused on improving single image segmentation. To our knowledge, no prior work has made use of temporal video information in a recurrent network. In this paper, we introduce a novel approach to implicitly utilize temporal data in videos for online semantic segmentation. The method relies on a fully convolutional network that is embedded into a gated recurrent architecture. This design receives a sequence of consecutive video frames and outputs the segmentation of the last frame. Convolutional gated recurrent networks are used for the recurrent part to preserve spatial connectivities in the image. Our proposed method can be applied in both online and batch segmentation. This architecture is tested for both binary and semantic video segmentation tasks. Experiments are conducted on the recent benchmarks in SegTrack V2, Davis, CityScapes, and Synthia. Using recurrent fully convolutional networks improved the baseline network performance in all of our experiments. Namely, 5% and 3% improvement of F-measure in SegTrack2 and Davis respectively, 5.7% improvement in mean IoU in Synthia and 3.5% improvement in categorical mean IoU in CityScapes. The performance of the RFCN network depends on its baseline fully convolutional network. Thus RFCN architecture can be seen as a method to improve its baseline segmentation network by exploiting spatiotemporal information in videos.

##### Abstract (translated by Google)
最近，语义分割取得了重大进展，完全卷积神经网络表现出色。然而，以往的大部分工作都集中在改进单个图像分割上。据我们所知，在经常性网络中没有以前的工作使用过时间视频信息。在本文中，我们引入了一种新颖的方法来隐式地利用视频中的时间数据进行在线语义分割。该方法依赖于嵌入到门控循环体系结构中的完全卷积网络。这种设计接收一系列连续的视频帧，并输出最后一帧的分割。卷积门控循环网络被用于循环部分以保持图像中的空间连通性。我们提出的方法可以应用于在线和批量分割。该体系结构经过了二进制和语义视频分割任务的测试。在SegTrack V2，Davis，CityScapes和Synthia的最新基准测试中进行实验。使用循环完全卷积网络改进了我们所有实验中的基线网络性能。即SegTrack2和Davis的F-measure分别提高了5％和3％，Synthia的平均IoU提高了5.7％，CityScapes提高了3.5％的IoU。 RFCN网络的性能取决于其基线完全卷积网络。因此RFCN体系结构可以被看作是通过利用视频中的时空信息来改善其基线分割网络的方法。

##### URL
[https://arxiv.org/abs/1611.05435](https://arxiv.org/abs/1611.05435)

##### PDF
[https://arxiv.org/pdf/1611.05435](https://arxiv.org/pdf/1611.05435)


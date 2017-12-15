---
layout: post
title: "GPU-FV: Realtime Fisher Vector and Its Applications in Video Monitoring"
date: 2016-04-12 18:22:08
categories: arXiv_CV
tags: arXiv_CV Optimization Recognition
author: Wenying Ma, Liangliang Cao, Lei Yu, Guoping Long, Yucheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Fisher vector has been widely used in many multimedia retrieval and visual recognition applications with good performance. However, the computation complexity prevents its usage in real-time video monitoring. In this work, we proposed and implemented GPU-FV, a fast Fisher vector extraction method with the help of modern GPUs. The challenge of implementing Fisher vector on GPUs lies in the data dependency in feature extraction and expensive memory access in Fisher vector computing. To handle these challenges, we carefully designed GPU-FV in a way that utilizes the computing power of GPU as much as possible, and applied optimizations such as loop tiling to boost the performance. GPU-FV is about 12 times faster than the CPU version, and 50\% faster than a non-optimized GPU implementation. For standard video input (320*240), GPU-FV can process each frame within 34ms on a model GPU. Our experiments show that GPU-FV obtains a similar recognition accuracy as traditional FV on VOC 2007 and Caltech 256 image sets. We also applied GPU-FV for realtime video monitoring tasks and found that GPU-FV outperforms a number of previous works. Especially, when the number of training examples are small, GPU-FV outperforms the recent popular deep CNN features borrowed from ImageNet. The code can be downloaded from the following link this https URL

##### Abstract (translated by Google)
Fisher矢量在许多多媒体检索和视觉识别应用中被广泛使用，性能良好。但是，计算的复杂性阻碍了它在实时视频监控中的使用。在这项工作中，我们在现代GPU的帮助下提出并实现了GPU-FV，一种快速的Fisher矢量提取方法。在GPU上实现Fisher矢量的挑战在于特征提取中的数据依赖性以及费希矢量计算中昂贵的存储器访问。为了应对这些挑战，我们精心设计了GPU-FV，尽可能多地利用GPU的计算能力，并应用循环平铺等优化来提升性能。 GPU-FV比CPU版本快大约12倍，比非优化GPU实现快50％。对于标准视频输入（320 * 240），GPU-FV可以在模型GPU上以34ms的速度处理每个帧。我们的实验显示GPU-FV在VOC 2007和Caltech 256图像集上获得了与传统FV类似的识别精度。我们还将GPU-FV用于实时视频监控任务，发现GPU-FV的性能优于以前的一些作品。特别是当训练样本数量较少时，GPU-FV优于最近流行的深度CNN特征，这些特征来源于ImageNet。该代码可以从以下链接下载此https网址

##### URL
[https://arxiv.org/abs/1604.03498](https://arxiv.org/abs/1604.03498)

##### PDF
[https://arxiv.org/pdf/1604.03498](https://arxiv.org/pdf/1604.03498)


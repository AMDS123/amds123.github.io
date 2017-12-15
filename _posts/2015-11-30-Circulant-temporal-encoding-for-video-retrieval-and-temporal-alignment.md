---
layout: post
title: "Circulant temporal encoding for video retrieval and temporal alignment"
date: 2015-11-30 17:00:13
categories: arXiv_CV
tags: arXiv_CV
author: Matthijs Douze, Jérôme Revaud, Jakob Verbeek, Hervé Jégou, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of specific video event retrieval. Given a query video of a specific event, e.g., a concert of Madonna, the goal is to retrieve other videos of the same event that temporally overlap with the query. Our approach encodes the frame descriptors of a video to jointly represent their appearance and temporal order. It exploits the properties of circulant matrices to efficiently compare the videos in the frequency domain. This offers a significant gain in complexity and accurately localizes the matching parts of videos. The descriptors can be compressed in the frequency domain with a product quantizer adapted to complex numbers. In this case, video retrieval is performed without decompressing the descriptors. We also consider the temporal alignment of a set of videos. We exploit the matching confidence and an estimate of the temporal offset computed for all pairs of videos by our retrieval approach. Our robust algorithm aligns the videos on a global timeline by maximizing the set of temporally consistent matches. The global temporal alignment enables synchronous playback of the videos of a given scene.

##### Abstract (translated by Google)
我们解决了特定的视频事件检索问题。给定特定事件的查询视频，例如麦当娜的音乐会，目标是检索与查询在时间上重叠的相同事件的其他视频。我们的方法对视频的帧描述符进行编码，以共同表示它们的外观和时间顺序。它利用循环矩阵的特性来高效地比较频域中的视频。这提供了显着的复杂性增加，并准确地定位视频的匹配部分。描述符可以在适应复数的产品量化器的频域中进行压缩。在这种情况下，视频检索在不解压描述符的情况下被执行。我们也考虑一组视频的时间对齐。我们通过我们的检索方法利用匹配置信度和对所有视频对计算的时间偏移的估计。我们的鲁棒算法通过最大化时间一致性匹配集来在全局时间线上对齐视频。全局时间对齐使得能够同步回放给定场景的视频。

##### URL
[https://arxiv.org/abs/1506.02588](https://arxiv.org/abs/1506.02588)

##### PDF
[https://arxiv.org/pdf/1506.02588](https://arxiv.org/pdf/1506.02588)


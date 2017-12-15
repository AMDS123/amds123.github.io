---
layout: post
title: "Learning Binary Residual Representations for Domain-specific Video Streaming"
date: 2017-12-14 04:06:33
categories: arXiv_CV
tags: arXiv_CV
author: Yi-Hsuan Tsai, Ming-Yu Liu, Deqing Sun, Ming-Hsuan Yang, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
We study domain-specific video streaming. Specifically, we target a streaming setting where the videos to be streamed from a server to a client are all in the same domain and they have to be compressed to a small size for low-latency transmission. Several popular video streaming services, such as the video game streaming services of GeForce Now and Twitch, fall in this category. While conventional video compression standards such as H.264 are commonly used for this task, we hypothesize that one can leverage the property that the videos are all in the same domain to achieve better video quality. Based on this hypothesis, we propose a novel video compression pipeline. Specifically, we first apply H.264 to compress domain-specific videos. We then train a novel binary autoencoder to encode the leftover domain-specific residual information frame-by-frame into binary representations. These binary representations are then compressed and sent to the client together with the H.264 stream. In our experiments, we show that our pipeline yields consistent gains over standard H.264 compression across several benchmark datasets while using the same channel bandwidth.

##### Abstract (translated by Google)
我们研究领域特定的视频流。具体而言，我们的目标是一个流媒体设置，从服务器到客户端的流媒体视频都在同一个域中，并且必须将其压缩到较小的尺寸才能进行低​​延迟传输。几种流行的视频流媒体服务，如GeForce Now和Twitch的视频游戏流媒体服务都属于这一类。虽然传统的视频压缩标准（如H.264）通常用于此任务，但我们假设可以利用视频都在同一个域中的属性来获得更好的视频质量。基于这个假设，我们提出了一种新颖的视频压缩流水线。具体来说，我们首先应用H.264来压缩特定于域的视频。然后，我们训练一个新颖的二进制自动编码器，将残余域特定的残差信息逐帧编码为二进制表示。这些二进制表示然后被压缩并与H.264流一起发送到客户端。在我们的实验中，我们展示了在使用相同信道带宽的情况下，我们的流水线在跨越几个基准数据集的标准H.264压缩下产生了一致的增益

##### URL
[http://arxiv.org/abs/1712.05087](http://arxiv.org/abs/1712.05087)

##### PDF
[http://arxiv.org/pdf/1712.05087](http://arxiv.org/pdf/1712.05087)


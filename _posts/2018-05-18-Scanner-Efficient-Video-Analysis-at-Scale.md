---
layout: post
title: "Scanner: Efficient Video Analysis at Scale"
date: 2018-05-18 17:43:55
categories: arXiv_CV
tags: arXiv_CV GAN
author: Alex Poms, Will Crichton, Pat Hanrahan, Kayvon Fatahalian
mathjax: true
---

* content
{:toc}

##### Abstract
A growing number of visual computing applications depend on the analysis of large video collections. The challenge is that scaling applications to operate on these datasets requires efficient systems for pixel data access and parallel processing across large numbers of machines. Few programmers have the capability to operate efficiently at these scales, limiting the field's ability to explore new applications that leverage big video data. In response, we have created Scanner, a system for productive and efficient video analysis at scale. Scanner organizes video collections as tables in a data store optimized for sampling frames from compressed video, and executes pixel processing computations, expressed as dataflow graphs, on these frames. Scanner schedules video analysis applications expressed using these abstractions onto heterogeneous throughput computing hardware, such as multi-core CPUs, GPUs, and media processing ASICs, for high-throughput pixel processing. We demonstrate the productivity of Scanner by authoring a variety of video processing applications including the synthesis of stereo VR video streams from multi-camera rigs, markerless 3D human pose reconstruction from video, and data-mining big video datasets such as hundreds of feature-length films or over 70,000 hours of TV news. These applications achieve near-expert performance on a single machine and scale efficiently to hundreds of machines, enabling formerly long-running big video data analysis tasks to be carried out in minutes to hours.

##### Abstract (translated by Google)
越来越多的视觉计算应用依赖于对大型视频集合的分析。面临的挑战是，缩放应用程序以在这些数据集上运行需要有效的系统，以便在大量机器上进行像素数据访问和并行处理。很少有程序员能够在这些规模上高效地运作，限制了该领域探索利用大视频数据的新应用程序的能力。作为回应，我们已经创建了扫描仪，这是一个大规模生产和高效视频分析系统。扫描仪将视频集合组织为针对从压缩视频采样帧进行优化的数据存储中的表格，并在这些帧上执行像数据流图表一样的像素处理计算。扫描仪将使用这些抽象表达的视频分析应用程序调度到异构吞吐量计算硬件（如多核CPU，GPU和媒体处理ASIC），以实现高吞吐量像素处理。我们通过创作各种视频处理应用来演示Scanner的生产力，包括从多摄像头钻机合成立体VR视频流，从视频无标记3D人体姿态重建以及数据挖掘大视频数据集，例如数百个特征长度电影或超过70,000小时的电视新闻。这些应用程序在单台机器上实现近乎专业的性能，并可高效扩展至数百台机器，从而使以前长时间运行的大型视频数据分析任务可在数分钟至数小时内完成。

##### URL
[http://arxiv.org/abs/1805.07339](http://arxiv.org/abs/1805.07339)

##### PDF
[http://arxiv.org/pdf/1805.07339](http://arxiv.org/pdf/1805.07339)


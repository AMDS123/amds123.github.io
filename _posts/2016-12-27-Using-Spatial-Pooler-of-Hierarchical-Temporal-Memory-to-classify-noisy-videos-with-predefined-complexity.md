---
layout: post
title: "Using Spatial Pooler of Hierarchical Temporal Memory to classify noisy videos with predefined complexity"
date: 2016-12-27 11:13:40
categories: arXiv_CV
tags: arXiv_CV Face Recognition
author: Maciej Wielgosz, Marcin Pietroń
mathjax: true
---

* content
{:toc}

##### Abstract
This paper examines the performance of a Spatial Pooler (SP) of a Hierarchical Temporal Memory (HTM) in the task of noisy object recognition. To address this challenge, a dedicated custom-designed system based on the SP, histogram calculation module and SVM classifier was implemented. In addition to implementing their own version of HTM, the authors also designed a profiler which is capable of tracing all of the key parameters of the system. This was necessary, since an analysis and monitoring of the system performance turned out to be extremely difficult using conventional testing and debugging tools. The system was initially trained on artificially prepared videos without noise and then tested with a set of noisy video streams. This approach was intended to mimic a real life scenario where an agent or a system trained to deal with ideal objects faces a task of classifying distorted and noisy ones in its regular working conditions. The authors conducted a series of experiments for various macro parameters of HTM SP, as well as for different levels of video reduction ratios. The experiments allowed them to evaluate the performance of two different system setups (i.e. 'Multiple HTMs' and 'Single HTM') under various noise conditions with 32--frame video files. Results of all the tests were compared to SVM baseline setup. It was determined that the system featuring SP is capable of achieving approximately 12 times the noise reduction for a video signal with with distorted bits accounting for 13\% of the total. Furthermore, the system featuring SP performed better also in the experiments without a noise component and achieved a max F1 score of 0.96. The experiments also revealed that a rise of column and synapse number of SP has a substantial impact on the performance of the system. Consequently, the highest F1 score values were obtained for 256 and 4096 synapses and columns respectively.

##### Abstract (translated by Google)
本文考察了噪声对象识别任务中层次时间存储器（HTM）的空间搜索器（Spatial Pooler，SP）的性能。为了解决这个难题，实现了基于SP，直方图计算模块和SVM分类器的专用定制系统。除了实现他们自己的HTM版本外，作者还设计了一个能够跟踪系统所有关键参数的分析器。这是必要的，因为使用传统的测试和调试工具对系统性能进行分析和监控变得非常困难。该系统最初是在没有噪声的情况下人工制作视频的训练，然后用一组嘈杂的视频流进行测试。这种方法的目的是模仿一个真实的生活场景，一个经过训练的理想物体的代理人或系统在正常的工作条件下面临扭曲和嘈杂的任务。作者对HTM SP的各种宏观参数以及不同级别的视频压缩率进行了一系列的实验。这些实验允许他们在32帧视频文件的各种噪声条件下评估两种不同系统设置（即“多个HTM”和“单个HTM”）的性能。将所有测试的结果与SVM基线设置进行比较。确定SP系统能够对失真比特视频信号实现约12倍的降噪，占总量的13％。此外，SP系统在没有噪声成分的实验中也表现较好，最大F1分数为0.96。实验还表明，SP的列数和突触数目的增加对系统的性能有很大的影响。因此，分别获得了256和4096个突触和列的最高F1得分值。

##### URL
[https://arxiv.org/abs/1609.03093](https://arxiv.org/abs/1609.03093)

##### PDF
[https://arxiv.org/pdf/1609.03093](https://arxiv.org/pdf/1609.03093)


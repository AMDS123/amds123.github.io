---
layout: post
title: "shapeDTW: shape Dynamic Time Warping"
date: 2016-06-06 02:38:01
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification Quantitative
author: Jiaping Zhao, Laurent Itti
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic Time Warping (DTW) is an algorithm to align temporal sequences with possible local non-linear distortions, and has been widely applied to audio, video and graphics data alignments. DTW is essentially a point-to-point matching method under some boundary and temporal consistency constraints. Although DTW obtains a global optimal solution, it does not necessarily achieve locally sensible matchings. Concretely, two temporal points with entirely dissimilar local structures may be matched by DTW. To address this problem, we propose an improved alignment algorithm, named shape Dynamic Time Warping (shapeDTW), which enhances DTW by taking point-wise local structural information into consideration. shapeDTW is inherently a DTW algorithm, but additionally attempts to pair locally similar structures and to avoid matching points with distinct neighborhood structures. We apply shapeDTW to align audio signal pairs having ground-truth alignments, as well as artificially simulated pairs of aligned sequences, and obtain quantitatively much lower alignment errors than DTW and its two variants. When shapeDTW is used as a distance measure in a nearest neighbor classifier (NN-shapeDTW) to classify time series, it beats DTW on 64 out of 84 UCR time series datasets, with significantly improved classification accuracies. By using a properly designed local structure descriptor, shapeDTW improves accuracies by more than 10% on 18 datasets. To the best of our knowledge, shapeDTW is the first distance measure under the nearest neighbor classifier scheme to significantly outperform DTW, which had been widely recognized as the best distance measure to date. Our code is publicly accessible at: this https URL

##### Abstract (translated by Google)
动态时间规整（Dynamic Time Warping，DTW）是一种将时间序列与可能的局部非线性失真对齐的算法，并已广泛应用于音频，视频和图形数据的对齐。 DTW本质上是一些边界和时间一致性约束下的点对点匹配方法。尽管DTW获得全局最优解决方案，但并不一定能实现本地明智的匹配。具体而言，DTW可以匹配具有完全不相似的局部结构的两个时间点。为了解决这个问题，我们提出了一种改进的对齐算法，称为shape Dynamic Time Warping（shapeDTW），它通过考虑点对点局部结构信息来增强DTW。 shapeDTW固有地是DTW算法，但是另外尝试将局部相似的结构配对，并且避免具有不同邻域结构的匹配点。我们应用shapeDTW来对齐具有地面真实对准的音频信号对，以及人工模拟的对比序列对，并且比DTW及其两个变体定量获得低得多的对准误差。当shapeDTW用作最近邻分类器（NN-shapeDTW）中的距离度量来对时间序列进行分类时，它在84个UCR时间序列数据集中的64个中击败DTW，分类精度显着提高。通过使用适当设计的局部结构描述符，shapeDTW在18个数据集上提高了10％以上的精度。据我们所知，shapeDTW是最近邻分类器方案下的第一个距离度量，它大大地超过了DTW，DTW被广泛认为是迄今为止最好的距离度量。我们的代码可在以下网址公开访问：

##### URL
[https://arxiv.org/abs/1606.01601](https://arxiv.org/abs/1606.01601)

##### PDF
[https://arxiv.org/pdf/1606.01601](https://arxiv.org/pdf/1606.01601)


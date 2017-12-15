---
layout: post
title: "Vectors of Locally Aggregated Centers for Compact Video Representation"
date: 2015-09-13 13:06:36
categories: arXiv_CV
tags: arXiv_CV Detection
author: Alhabib Abbas, Nikos Deligiannis, Yiannis Andreopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel vector aggregation technique for compact video representation, with application in accurate similarity detection within large video datasets. The current state-of-the-art in visual search is formed by the vector of locally aggregated descriptors (VLAD) of Jegou et. al. VLAD generates compact video representations based on scale-invariant feature transform (SIFT) vectors (extracted per frame) and local feature centers computed over a training set. With the aim to increase robustness to visual distortions, we propose a new approach that operates at a coarser level in the feature representation. We create vectors of locally aggregated centers (VLAC) by first clustering SIFT features to obtain local feature centers (LFCs) and then encoding the latter with respect to given centers of local feature centers (CLFCs), extracted from a training set. The sum-of-differences between the LFCs and the CLFCs are aggregated to generate an extremely-compact video description used for accurate video segment similarity detection. Experimentation using a video dataset, comprising more than 1000 minutes of content from the Open Video Project, shows that VLAC obtains substantial gains in terms of mean Average Precision (mAP) against VLAD and the hyper-pooling method of Douze et. al., under the same compaction factor and the same set of distortions.

##### Abstract (translated by Google)
我们提出了一种新的矢量聚合技术，用于紧凑的视频表示，可用于大视频数据集内的精确相似度检测。视觉搜索的当前最新技术是由Jegou等人的局部聚合描述符（VLAD）矢量形成的。人。 VLAD基于尺度不变特征变换（SIFT）矢量（每帧提取）和在训练集上计算的局部特征中心生成紧凑视频表示。为了增强对视觉扭曲的鲁棒性，我们提出了一种新的方法，在特征表示中以较粗糙的级别进行操作。我们通过首先对SIFT特征进行聚类以获得局部特征中心（LFC），然后针对从训练集中提取的局部特征中心（CLFC）的给定中心对后者进行编码来创建局部聚集中心（VLAC）的矢量。将LFC和CLFC之间的差异总和聚合以生成用于准确的视频段相似度检测的非常紧凑的视频描述。使用视频数据集进行的实验（包含来自开放视频项目的超过1000分钟的内容）表明VLAC在针对VLAD的平均平均精确度（mAP）和Douze等人的超级归并方法方面获得了实质性收益。在相同的压缩因子和相同的一组扭曲下。

##### URL
[https://arxiv.org/abs/1509.03844](https://arxiv.org/abs/1509.03844)

##### PDF
[https://arxiv.org/pdf/1509.03844](https://arxiv.org/pdf/1509.03844)


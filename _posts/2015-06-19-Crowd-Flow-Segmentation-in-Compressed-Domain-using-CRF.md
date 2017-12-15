---
layout: post
title: "Crowd Flow Segmentation in Compressed Domain using CRF"
date: 2015-06-19 14:01:24
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Srinivas S. S. Kruthiventi, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd flow segmentation is an important step in many video surveillance tasks. In this work, we propose an algorithm for segmenting flows in H.264 compressed videos in a completely unsupervised manner. Our algorithm works on motion vectors which can be obtained by partially decoding the compressed video without extracting any additional features. Our approach is based on modelling the motion vector field as a Conditional Random Field (CRF) and obtaining oriented motion segments by finding the optimal labelling which minimises the global energy of CRF. These oriented motion segments are recursively merged based on gradient across their boundaries to obtain the final flow segments. This work in compressed domain can be easily extended to pixel domain by substituting motion vectors with motion based features like optical flow. The proposed algorithm is experimentally evaluated on a standard crowd flow dataset and its superior performance in both accuracy and computational time are demonstrated through quantitative results.

##### Abstract (translated by Google)
人群流动分割是许多视频监控任务中的重要一步。在这项工作中，我们提出了一个完全无监督的方式在H.264压缩视频分割流程的算法。我们的算法工作在运动矢量上，可以通过对压缩视频进行部分解码而不需要提取任何附加的特征。我们的方法是基于将运动矢量场建模为条件随机场（CRF），并通过寻找使CRF的全局能量最小化的最佳标记来获得定向运动段。这些定向的运动片段基于跨越其边界的梯度递归合并以获得最终的流动片段。这项工作在压缩域可以很容易地扩展到像素域，通过运动基于像光流的功能代替运动矢量。该算法在标准人群流数据集上进行了实验评估，并通过定量结果验证了其在精度和计算时间上的优越性能。

##### URL
[https://arxiv.org/abs/1506.06006](https://arxiv.org/abs/1506.06006)

##### PDF
[https://arxiv.org/pdf/1506.06006](https://arxiv.org/pdf/1506.06006)


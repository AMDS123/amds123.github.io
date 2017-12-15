---
layout: post
title: "Rapid building detection using machine learning"
date: 2016-03-14 19:03:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Joseph Paul Cohen, Wei Ding, Caitlin Kuhlman, Aijun Chen, Liping Di
mathjax: true
---

* content
{:toc}

##### Abstract
This work describes algorithms for performing discrete object detection, specifically in the case of buildings, where usually only low quality RGB-only geospatial reflective imagery is available. We utilize new candidate search and feature extraction techniques to reduce the problem to a machine learning (ML) classification task. Here we can harness the complex patterns of contrast features contained in training data to establish a model of buildings. We avoid costly sliding windows to generate candidates; instead we innovatively stitch together well known image processing techniques to produce candidates for building detection that cover 80-85% of buildings. Reducing the number of possible candidates is important due to the scale of the problem. Each candidate is subjected to classification which, although linear, costs time and prohibits large scale evaluation. We propose a candidate alignment algorithm to boost classification performance to 80-90% precision with a linear time algorithm and show it has negligible cost. Also, we propose a new concept called a Permutable Haar Mesh (PHM) which we use to form and traverse a search space to recover candidate buildings which were lost in the initial preprocessing phase.

##### Abstract (translated by Google)
这项工作描述了执行离散对象检测的算法，特别是在建筑物的情况下，通常只有低质量的仅有RGB的地理空间反射图像是可用的。我们利用新的候选搜索和特征提取技术将问题减少到机器学习（ML）分类任务。在这里，我们可以利用训练数据中包含的复杂对比特征模式来建立建筑模型。我们避免昂贵的滑动窗口来生成候选人;相反，我们创新地将众所周知的图像处理技术缝合在一起，以产生涵盖80-85％建筑物的建筑物检测的候选者。由于问题的严重性，减少可能的候选人的数量非常重要。每个候选人都受到分类，虽然是线性的，但是花费时间并且禁止大规模的评估。我们提出了一个候选对齐算法，通过线性时间算法将分类性能提高到80-90％的精度，并显示其成本可以忽略不计。此外，我们提出了一个新概念，称为可互换Haar网格（PHM），我们用它来形成和遍历搜索空间，以恢复在初始预处理阶段丢失的候选建筑物。

##### URL
[https://arxiv.org/abs/1603.04392](https://arxiv.org/abs/1603.04392)

##### PDF
[https://arxiv.org/pdf/1603.04392](https://arxiv.org/pdf/1603.04392)


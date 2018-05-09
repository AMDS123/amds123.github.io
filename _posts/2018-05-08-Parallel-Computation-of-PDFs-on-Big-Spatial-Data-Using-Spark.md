---
layout: post
title: "Parallel Computation of PDFs on Big Spatial Data Using Spark"
date: 2018-05-08 16:22:25
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Ji Liu, Noel Moreno Lemus, Esther Pacitti, Fabio Porto, Patrick Valduriez
mathjax: true
---

* content
{:toc}

##### Abstract
We consider big spatial data, which is typically produced in scientific areas such as geological or seismic interpretation. The spatial data can be produced by observation (e.g. using sensors or soil instrument) or numerical simulation programs and correspond to points that represent a 3D soil cube area. However, errors in signal processing and modeling create some uncertainty, and thus a lack of accuracy in identifying geological or seismic phenomenons. Such uncertainty must be carefully analyzed. To analyze uncertainty, the main solution is to compute a Probability Density Function (PDF) of each point in the spatial cube area. However, computing PDFs on big spatial data can be very time consuming (from several hours to even months on a parallel computer). In this paper, we propose a new solution to efficiently compute such PDFs in parallel using Spark, with three methods: data grouping, machine learning prediction and sampling. We evaluate our solution by extensive experiments on different computer clusters using big data ranging from hundreds of GB to several TB. The experimental results show that our solution scales up very well and can reduce the execution time by a factor of 33 (in the order of seconds or minutes) compared with a baseline method.

##### Abstract (translated by Google)
我们考虑大量的空间数据，这些数据通常在诸如地质或地震解释等科学领域中产生。空间数据可以通过观察（例如使用传感器或土壤仪器）或数字模拟程序产生，并且对应于表示3D土壤立方体面积的点。然而，信号处理和建模中的错误会产生一些不确定性，因此在识别地质或地震现象方面缺乏准确性。这种不确定性必须仔细分析。为了分析不确定性，主要解决方案是计算空间立方体区域中每个点的概率密度函数（PDF）。但是，计算大型空间数据的PDF可能非常耗时（在并行计算机上从几个小时到几个月）。在本文中，我们提出了一种新的解决方案，以使用Spark并行高效地计算这些PDF，其中有三种方法：数据分组，机器学习预测和采样。我们通过在不同计算机集群上进行广泛的实验来评估我们的解决方案，使用的数据范围从数百GB到几TB。实验结果表明，我们的解决方案扩展得非常好，并且与基准方法相比，可以将执行时间缩短33倍（以秒或分钟为单位）。

##### URL
[https://arxiv.org/abs/1805.03141](https://arxiv.org/abs/1805.03141)

##### PDF
[https://arxiv.org/pdf/1805.03141](https://arxiv.org/pdf/1805.03141)


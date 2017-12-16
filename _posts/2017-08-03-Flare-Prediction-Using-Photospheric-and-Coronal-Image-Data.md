---
layout: post
title: "Flare Prediction Using Photospheric and Coronal Image Data"
date: 2017-08-03 22:31:38
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Eric Jonas, Monica G. Bobra, Vaishaal Shankar, J. Todd Hoeksema, Benjamin Recht
mathjax: true
---

* content
{:toc}

##### Abstract
The precise physical process that triggers solar flares is not currently understood. Here we attempt to capture the signature of this mechanism in solar image data of various wavelengths and use these signatures to predict flaring activity. We do this by developing an algorithm that [1] automatically generates features in 5.5 TB of image data taken by the Solar Dynamics Observatory of the solar photosphere, chromosphere, transition region, and corona during the time period between May 2010 and May 2014, [2] combines these features with other features based on flaring history and a physical understanding of putative flaring processes, and [3] classifies these features to predict whether a solar active region will flare within a time period of $T$ hours, where $T$ = 2 and 24. We find that when optimizing for the True Skill Score (TSS), photospheric vector magnetic field data combined with flaring history yields the best performance, and when optimizing for the area under the precision-recall curve, all the data are helpful. Our model performance yields a TSS of $0.84 \pm 0.03$ and $0.81 \pm 0.03$ in the $T$ = 2 and 24 hour cases, respectively, and a value of $0.13 \pm 0.07$ and $0.43 \pm 0.08$ for the area under the precision-recall curve in the $T$ = 2 and 24 hour cases, respectively. These relatively high scores are similar to, but not greater than, other attempts to predict solar flares. Given the similar values of algorithm performance across various types of models reported in the literature, we conclude that we can expect a certain baseline predictive capacity using these data. This is the first attempt to predict solar flares using photospheric vector magnetic field data as well as multiple wavelengths of image data from the chromosphere, transition region, and corona.

##### Abstract (translated by Google)
触发太阳耀斑的确切物理过程目前尚不清楚。在这里，我们尝试捕获这种机制在不同波长的太阳图像数据中的签名，并使用这些签名来预测扩展活动。我们通过开发一种算法[1]，在2010年5月至2014年5月期间，太阳光球，色球，过渡区和日冕等太阳动力观测站采集的5.5TB图像数据中自动生成特征[ 2]将这些特征与其他特征相结合，这些特征基于耀斑历史和对假定的耀斑过程的物理理解[3]，并将这些特征分类以预测太阳活动区域是否会在$ T $小时的时间段内闪耀，其中$ T我们发现在优化真实技能分数（TSS）时，光球矢量磁场数据结合闪耀历史记录会产生最佳性能，并且在精度 - 回忆曲线下的面积优化时，所有数据是有帮助的。在$ T $ = 2和24小时的情况下，我们的模型性能分别为0.84美元/小时0.03美元和0.81美元/小时0.03美元的TSS，以及该区域的价值为0.13美元/小时0.07美元和0.43美元/小时0.08美元在$ T $ = 2和24小时情况下的精度 - 回忆曲线下。这些相对较高的分数与预测太阳耀斑的其他尝试类似，但不会大于其他。考虑到文献中报告的各种模型的算法性能相似的值，我们可以得出结论，我们可以使用这些数据预期一定的基线预测能力。这是首次尝试使用光球矢量磁场数据以及来自色球，过渡区和日冕的多波长图像数据预测太阳耀斑。

##### URL
[https://arxiv.org/abs/1708.01323](https://arxiv.org/abs/1708.01323)

##### PDF
[https://arxiv.org/pdf/1708.01323](https://arxiv.org/pdf/1708.01323)


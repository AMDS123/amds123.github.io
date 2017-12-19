---
layout: post
title: "On the Distribution of Salient Objects in Web Images and its Influence on Salient Object Detection"
date: 2015-01-10 17:36:24
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Detection
author: Boris Schauerte, Rainer Stiefelhagen
mathjax: true
---

* content
{:toc}

##### Abstract
It has become apparent that a Gaussian center bias can serve as an important prior for visual saliency detection, which has been demonstrated for predicting human eye fixations and salient object detection. Tseng et al. have shown that the photographer's tendency to place interesting objects in the center is a likely cause for the center bias of eye fixations. We investigate the influence of the photographer's center bias on salient object detection, extending our previous work. We show that the centroid locations of salient objects in photographs of Achanta and Liu's data set in fact correlate strongly with a Gaussian model. This is an important insight, because it provides an empirical motivation and justification for the integration of such a center bias in salient object detection algorithms and helps to understand why Gaussian models are so effective. To assess the influence of the center bias on salient object detection, we integrate an explicit Gaussian center bias model into two state-of-the-art salient object detection algorithms. This way, first, we quantify the influence of the Gaussian center bias on pixel- and segment-based salient object detection. Second, we improve the performance in terms of F1 score, Fb score, area under the recall-precision curve, area under the receiver operating characteristic curve, and hit-rate on the well-known data set by Achanta and Liu. Third, by debiasing Cheng et al.'s region contrast model, we exemplarily demonstrate that implicit center biases are partially responsible for the outstanding performance of state-of-the-art algorithms. Last but not least, as a result of debiasing Cheng et al.'s algorithm, we introduce a non-biased salient object detection method, which is of interest for applications in which the image data is not likely to have a photographer's center bias (e.g., image data of surveillance cameras or autonomous robots).

##### Abstract (translated by Google)
显而易见的是，高斯中心偏差可以作为视觉显着性检测的重要先验，已经被证明用于预测人眼识别和显着物体检测。 Tseng等人已经表明，摄影师倾向于在中心放置有趣的物体，这可能是眼睛注视的中心偏见的原因。我们调查摄影师的中心偏见对显着物体检测的影响，扩展了我们以前的工作。我们表明，Achanta和Liu数据集的照片中显着物体的质心位置实际上与高斯模型有很强的相关性。这是一个重要的洞察力，因为它提供了一个经验性的动机和合理的证据，将这种中心偏差集成到显着的目标检测算法中，有助于理解高斯模型为什么如此有效。为了评估中心偏差对显着物体检测的影响，我们将明确的高斯中心偏差模型集成到两个最先进的显着物体检测算法中。这样，首先我们量化高斯中心偏差对基于像素和分段的显着物体检测的影响。其次，我们根据F1评分，Fb评分，召回精度曲线下面积，受试者操作特征曲线下面积以及Achanta和Liu着名数据的命中率来改善表现。第三，通过去除Cheng等人的区域对比模型，我们举例说明隐含的中心偏差是最先进的算法的突出表现的部分原因。最后但并非最不重要的是，作为去除Cheng等人的算法的结果，我们引入了无偏差的显着物体检测方法，这对于图像数据不可能具有摄影师的中心偏差的应用是有意义的例如监视摄像机或自主机器人的图像数据）。

##### URL
[https://arxiv.org/abs/1501.03383](https://arxiv.org/abs/1501.03383)

##### PDF
[https://arxiv.org/pdf/1501.03383](https://arxiv.org/pdf/1501.03383)


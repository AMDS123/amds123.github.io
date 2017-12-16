---
layout: post
title: "Multi-Oriented Text Detection and Verification in Video Frames and Scene Images"
date: 2017-10-04 16:48:08
categories: arXiv_CV
tags: arXiv_CV Text_Classification Classification Detection
author: Aneeshan Sain, Ayan Kumar Bhunia, Partha Pratim Roy, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we bring forth a novel approach of video text detection using Fourier-Laplacian filtering in the frequency domain that includes a verification technique using Hidden Markov Model (HMM). The proposed approach deals with the text region appearing not only in horizontal or vertical directions, but also in any other oblique or curved orientation in the image. Until now only a few methods have been proposed that look into curved text detection in video frames, wherein lies our novelty. In our approach, we first apply Fourier-Laplacian transform on the image followed by an ideal Laplacian-Gaussian filtering. Thereafter K-means clustering is employed to obtain the asserted text areas depending on a maximum difference map. Next, the obtained connected components (CC) are skeletonized to distinguish various text strings. Complex components are disintegrated into simpler ones according to a junction removal algorithm followed by a concatenation performed on possible combination of the disjoint skeletons to obtain the corresponding text area. Finally these text hypotheses are verified using HMM-based text/non-text classification system. False positives are thus eliminated giving us a robust text detection performance. We have tested our framework in multi-oriented text lines in four scripts, namely, English, Chinese, Devanagari and Bengali, in video frames and scene texts. The results obtained show that proposed approach surpasses existing methods on text detection.

##### Abstract (translated by Google)
在本文中，我们提出了一种使用傅立叶 - 拉普拉斯滤波的频域中的视频文本检测的新方法，其包括使用隐马尔可夫模型（HMM）的验证技术。所提出的方法涉及不仅在水平或垂直方向出现的文本区域，而且在图像中的任何其他倾斜或弯曲取向。到目前为止，只有少数几种方法可以研究视频帧中的弯曲文本检测，这是我们的新颖之处。在我们的方法中，我们首先对图像应用傅里叶 - 拉普拉斯变换，然后进行理想的拉普拉斯 - 高斯滤波。此后，采用K均值聚类来根据最大差异图来获得所断言的文本区域。接下来，将所获得的连接组件（CC）镂空以区分各种文本串。根据结点去除算法将复杂的组件分解为更简单的组件，然后对不相交的骨架进行可能的组合，以获得相应的文本区域。最后，使用基于HMM的文本/非文本分类系统来验证这些文本假设。错误的肯定因此被消除，给我们一个强大的文本检测性能。我们用英文，中文，梵文和孟加拉语四种文字在视频框架和场景文本中测试了我们的框架。得到的结果表明，提出的方法超越了现有的文本检测方法。

##### URL
[https://arxiv.org/abs/1707.07150](https://arxiv.org/abs/1707.07150)

##### PDF
[https://arxiv.org/pdf/1707.07150](https://arxiv.org/pdf/1707.07150)


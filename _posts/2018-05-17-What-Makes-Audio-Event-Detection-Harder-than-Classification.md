---
layout: post
title: "What Makes Audio Event Detection Harder than Classification?"
date: 2018-05-17 13:51:52
categories: arXiv_SD
tags: arXiv_SD Object_Detection Classification Detection
author: Huy Phan, Philipp Koch, Fabrice Katzberg, Marco Maass, Radoslaw Mazur, Ian McLoughlin, Alfred Mertins
mathjax: true
---

* content
{:toc}

##### Abstract
There is a common observation that audio event classification is easier to deal with than detection. So far, this observation has been accepted as a fact and we lack of a careful analysis. In this paper, we reason the rationale behind this fact and, more importantly, leverage them to benefit the audio event detection task. We present an improved detection pipeline in which a verification step is appended to augment a detection system. This step employs a high-quality event classifier to postprocess the benign event hypotheses outputted by the detection system and reject false alarms. To demonstrate the effectiveness of the proposed pipeline, we implement and pair up different event detectors based on the most common detection schemes and various event classifiers, ranging from the standard bag-of-words model to the state-of-the-art bank-of-regressors one. Experimental results on the ITC-Irst dataset show significant improvements to detection performance. More importantly, these improvements are consistent for all detector-classifier combinations.

##### Abstract (translated by Google)
有一种常见的观察，音频事件分类比检测更容易处理。到目前为止，这种观察已被接受为事实，我们缺乏仔细的分析。在本文中，我们推测这个事实背后的基本原理，更重要的是，利用它们来使音频事件检测任务受益。我们提出了一个改进的检测流水线，其中附加了验证步骤以增强检测系统。该步骤使用高质量事件分类器对检测系统输出的良性事件假设进行后处理，并拒绝错误警报。为了证明所提出的流水线的有效性，我们基于最常见的检测方案和各种事件分类器来实现和配对不同的事件检测器，从标准袋子模型到最先进的银行 - 的回归者之一。 ITC-Irst数据集上的实验结果显示检测性能显着提高。更重要的是，这些改进对于所有检测器 - 分类器组合是一致的。

##### URL
[http://arxiv.org/abs/1612.09089](http://arxiv.org/abs/1612.09089)

##### PDF
[http://arxiv.org/pdf/1612.09089](http://arxiv.org/pdf/1612.09089)


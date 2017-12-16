---
layout: post
title: "High Five: Improving Gesture Recognition by Embracing Uncertainty"
date: 2017-10-25 20:04:37
categories: arXiv_CV
tags: arXiv_CV Tracking Inference Classification Recognition
author: Diman Zad Tootaghaj, Adrian Sampson, Todd Mytkowicz, Kathryn S McKinley
mathjax: true
---

* content
{:toc}

##### Abstract
Sensors on mobile devices---accelerometers, gyroscopes, pressure meters, and GPS---invite new applications in gesture recognition, gaming, and fitness tracking. However, programming them remains challenging because human gestures captured by sensors are noisy. This paper illustrates that noisy gestures degrade training and classification accuracy for gesture recognition in state-of-the-art deterministic Hidden Markov Models (HMM). We introduce a new statistical quantization approach that mitigates these problems by (1) during training, producing gesture-specific codebooks, HMMs, and error models for gesture sequences; and (2) during classification, exploiting the error model to explore multiple feasible HMM state sequences. We implement classification in Uncertain<t>, a probabilistic programming system that encapsulates HMMs and error models and then automates sampling and inference in the runtime. Uncertain<T> developers directly express a choice of application-specific trade-off between recall and precision at gesture recognition time, rather than at training time. We demonstrate benefits in configurability, precision, recall, and recognition on two data sets with 25 gestures from 28 people and 4200 total gestures. Incorporating gesture error more accurately in modeling improves the average recognition rate of 20 gestures from 34\% in prior work to 62\%. Incorporating the error model during classification further improves the average gesture recognition rate to 71\%. As far as we are aware, no prior work shows how to generate an HMM error model during training and use it to improve classification rates.

##### Abstract (translated by Google)
移动设备上的传感器---加速度计，陀螺仪，压力计和GPS ---在手势识别，游戏和健身追踪中引入了新的应用。然而，对它们进行编程仍然具有挑战性，因为传感器捕获的人类手势是嘈杂的本文阐述了噪声手势降低了最先进的确定性隐马尔可夫模型（HMM）中手势识别的训练和分类精度。我们引入了一种新的统计量化方法，通过（1）在训练期间减少这些问题，产生手势特定的码本，HMM和手势序列的误差模型; （2）在分类过程中，利用误差模型探索多个可行的HMM状态序列。我们在Uncertain中实现分类，这个概率编程系统封装了HMM和错误模型，然后在运行时自动进行采样和推理。不确定的开发者在手势识别时直接表示在召回和精确度之间的应用特定折衷的选择，而不是在训练时间。我们在可配置性，精确度，召回率和识别两个数据集方面展示了优势，其中有来自28个人的25个手势和4200个手势。在建模中更精确地包含手势错误，将20个手势的平均识别率从之前工作的34％提高到62％。在分类期间合并误差模型进一步将平均手势识别率提高到71％。据我们所知，以前的工作没有展示如何在训练期间生成HMM误差模型，并使用它来提高分类率。

##### URL
[https://arxiv.org/abs/1710.09441](https://arxiv.org/abs/1710.09441)

##### PDF
[https://arxiv.org/pdf/1710.09441](https://arxiv.org/pdf/1710.09441)


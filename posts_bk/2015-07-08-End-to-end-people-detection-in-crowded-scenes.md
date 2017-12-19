---
layout: post
title: "End-to-end people detection in crowded scenes"
date: 2015-07-08 21:55:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection RNN Prediction Detection
author: Russell Stewart, Mykhaylo Andriluka
mathjax: true
---

* content
{:toc}

##### Abstract
Current people detectors operate either by scanning an image in a sliding window fashion or by classifying a discrete set of proposals. We propose a model that is based on decoding an image into a set of people detections. Our system takes an image as input and directly outputs a set of distinct detection hypotheses. Because we generate predictions jointly, common post-processing steps such as non-maximum suppression are unnecessary. We use a recurrent LSTM layer for sequence generation and train our model end-to-end with a new loss function that operates on sets of detections. We demonstrate the effectiveness of our approach on the challenging task of detecting people in crowded scenes.

##### Abstract (translated by Google)
当前的人员检测器或者通过以滑动窗口方式扫描图像或者通过对离散的一组提议进行分类来操作。我们提出了一种基于将图像解码为一组人检测的模型。我们的系统将图像作为输入，并直接输出一组不同的检测假设。因为我们联合产生预测，所以不需要通常的后处理步骤，如非最大抑制。我们使用一个循环的LSTM层来生成序列，并通过一个新的损失函数来对我们的模型进行端到端的训练。我们展示了我们的方法在检测拥挤的场景中的人的具有挑战性的任务上的有效性。

##### URL
[https://arxiv.org/abs/1506.04878](https://arxiv.org/abs/1506.04878)

##### PDF
[https://arxiv.org/pdf/1506.04878](https://arxiv.org/pdf/1506.04878)


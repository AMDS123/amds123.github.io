---
layout: post
title: "Background subtraction - separating the modeling and the inference"
date: 2015-11-05 06:57:38
categories: arXiv_CV
tags: arXiv_CV Inference
author: Manjunath Narayana, Allen Hanson, Erik Learned-Miller
mathjax: true
---

* content
{:toc}

##### Abstract
In its early implementations, background modeling was a process of building a model for the background of a video with a stationary camera, and identifying pixels that did not conform well to this model. The pixels that were not well-described by the background model were assumed to be moving objects. Many systems today maintain models for the foreground as well as the background, and these models compete to explain the pixels in a video. In this paper, we argue that the logical endpoint of this evolution is to simply use Bayes' rule to classify pixels. In particular, it is essential to have a background likelihood, a foreground likelihood, and a prior at each pixel. A simple application of Bayes' rule then gives a posterior probability over the label. The only remaining question is the quality of the component models: the background likelihood, the foreground likelihood, and the prior. We describe a model for the likelihoods that is built by using not only the past observations at a given pixel location, but by also including observations in a spatial neighborhood around the location. This enables us to model the influence between neighboring pixels and is an improvement over earlier pixelwise models that do not allow for such influence. Although similar in spirit to the joint domain-range model, we show that our model overcomes certain deficiencies in that model. We use a spatially dependent prior for the background and foreground. The background and foreground labels from the previous frame, after spatial smoothing to account for movement of objects,are used to build the prior for the current frame.

##### Abstract (translated by Google)
在早期的实现中，背景建模是一个利用固定摄像机为视频背景建立模型的过程，并识别不符合该模型的像素。没有被背景模型描述的像素被假定为移动物体。现在许多系统都维护前景和背景的模型，而这些模型竞相解释视频中的像素。在本文中，我们认为这个演化的逻辑终点是简单地使用贝叶斯规则来对像素进行分类。具体而言，在每个像素处具有背景似然性，前景似然性和先验性是至关重要的。贝叶斯规则的一个简单的应用就给出了标签的后验概率。剩下的唯一问题是组件模型的质量：背景可能性，前景可能性和先验。我们描述了一个模型的可能性，不仅使用过去的观察在一个给定的像素位置，而且还包括在位置周围的空间邻域的观测。这使我们能够模拟相邻像素之间的影响，并且是对早期的不允许这种影响的像素模型的改进。尽管在联合领域范围模型的精神上相似，但我们表明，我们的模型克服了该模型中的某些缺陷。我们使用空间依赖的前景作为背景和前景。来自前一帧的背景和前景标签在经过空间平滑以考虑对象的移动之后被用于构建当前帧的先验。

##### URL
[https://arxiv.org/abs/1511.01627](https://arxiv.org/abs/1511.01627)

##### PDF
[https://arxiv.org/pdf/1511.01627](https://arxiv.org/pdf/1511.01627)


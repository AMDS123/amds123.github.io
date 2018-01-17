---
layout: post
title: "Benchmark Visual Question Answer Models by using Focus Map"
date: 2018-01-13 09:09:33
categories: arXiv_CV
tags: arXiv_CV Segmentation VQA
author: Wenda Qiu, Yueyang Xianzang, Zhekai Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Inferring and Executing Programs for Visual Reasoning proposes a model for visual reasoning that consists of a program generator and an execution engine to avoid end-to-end models. To show that the model actually learns which objects to focus on to answer the questions, the authors give a visualization of the norm of the gradient of the sum of the predicted answer scores with respect to the final feature map. However, the authors do not evaluate the efficiency of focus map. This paper purposed a method for evaluating it. We generate several kinds of questions to test different keywords. We infer focus maps from the model by asking these questions and evaluate them by comparing with the segmentation graph. Furthermore, this method can be applied to any model if focus maps can be inferred from it. By evaluating focus map of different models on the CLEVR dataset, we will show that CLEVR-iep model has learned where to focus more than end-to-end models.

##### Abstract (translated by Google)
为视觉推理推荐和执行程序提出了一个视觉推理模型，它由程序生成器和执行引擎组成，以避免端到端模型。为了表明模型实际上学习了哪些对象要回答问题，作者给出了相对于最终特征映射的预测答案分数之和的梯度范数的可视化。然而，作者并没有评估焦点图的效率。本文提出了一种评估方法。我们生成几种问题来测试不同的关键字。我们通过询问这些问题并通过与分割图进行比较来从模型中推断焦点图。此外，如果可以从中推断出焦点地图，则该方法可以应用于任何模型。通过评估CLEVR数据集上的不同模型的焦点图，我们将展示CLEVR-iep模型已经学到了比端到端模型更多的关注点。

##### URL
[http://arxiv.org/abs/1801.05302](http://arxiv.org/abs/1801.05302)

##### PDF
[http://arxiv.org/pdf/1801.05302](http://arxiv.org/pdf/1801.05302)


---
layout: post
title: "Training Deep Networks to be Spatially Sensitive"
date: 2017-08-07 17:26:13
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Semantic_Segmentation Optimization Inference Prediction Gradient_Descent Relation
author: Nicholas Kolkin, Gregory Shakhnarovich, Eli Shechtman
mathjax: true
---

* content
{:toc}

##### Abstract
In many computer vision tasks, for example saliency prediction or semantic segmentation, the desired output is a foreground map that predicts pixels where some criteria is satisfied. Despite the inherently spatial nature of this task commonly used learning objectives do not incorporate the spatial relationships between misclassified pixels and the underlying ground truth. The Weighted F-measure, a recently proposed evaluation metric, does reweight errors spatially, and has been shown to closely correlate with human evaluation of quality, and stably rank predictions with respect to noisy ground truths (such as a sloppy human annotator might generate). However it suffers from computational complexity which makes it intractable as an optimization objective for gradient descent, which must be evaluated thousands or millions of times while learning a model's parameters. We propose a differentiable and efficient approximation of this metric. By incorporating spatial information into the objective we can use a simpler model than competing methods without sacrificing accuracy, resulting in faster inference speeds and alleviating the need for pre/post-processing. We match (or improve) performance on several tasks compared to prior state of the art by traditional metrics, and in many cases significantly improve performance by the weighted F-measure.

##### Abstract (translated by Google)
在许多计算机视觉任务中，例如显着性预测或语义分割，期望输出是预测满足某些标准的像素的前景图。尽管这个任务的内在空间性质，但是常用的学习目标并没有包含错误分类的像素与潜在的地面真相之间的空间关系。最近提出的评估指标Weighted F-measure在空间上对错误进行重新估计，并且已经显示出与人类对质量的评估密切相关，并且对于嘈杂的基本事实（例如马虎的注释者可能产生的） 。然而，它的计算复杂性使其难以作为梯度下降的优化目标，在学习模型参数的同时必须评估上千或上百万次。我们提出了这个度量的一个微分和有效的近似。通过将空间信息结合到目标中，我们可以使用比竞争方法更简单的模型，而不会牺牲准确性，从而加快推理速度，减轻对前/后处理的需求。与传统指标相比，我们匹配（或改进）了几个任务的性能，并且在许多情况下通过加权的F-measure显着提高性能。

##### URL
[https://arxiv.org/abs/1708.02212](https://arxiv.org/abs/1708.02212)

##### PDF
[https://arxiv.org/pdf/1708.02212](https://arxiv.org/pdf/1708.02212)


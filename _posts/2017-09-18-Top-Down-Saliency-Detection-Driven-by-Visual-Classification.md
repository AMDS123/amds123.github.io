---
layout: post
title: "Top-Down Saliency Detection Driven by Visual Classification"
date: 2017-09-18 10:05:33
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Classification Detection Recognition
author: Francesca Murabito, Concetto Spampinato, Simone Palazzo, Konstantin Pogorelov, Michael Riegler
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an approach for top-down saliency detection guided by visual classification tasks. We first learn how to compute visual saliency when a specific visual task has to be accomplished, as opposed to most state-of-the-art methods which assess saliency merely through bottom-up principles. Afterwards, we investigate if and to what extent visual saliency can support visual classification in nontrivial cases. To achieve this, we propose SalClassNet, a CNN framework consisting of two networks jointly trained: a) the first one computing top-down saliency maps from input images, and b) the second one exploiting the computed saliency maps for visual classification. To test our approach, we collected a dataset of eye-gaze maps, using a Tobii T60 eye tracker, by asking several subjects to look at images from the Stanford Dogs dataset, with the objective of distinguishing dog breeds. Performance analysis on our dataset and other saliency bench-marking datasets, such as POET, showed that SalClassNet out-performs state-of-the-art saliency detectors, such as SalNet and SALICON. Finally, we analyzed the performance of SalClassNet in a fine-grained recognition task and found out that it generalizes better than existing visual classifiers. The achieved results, thus, demonstrate that 1) conditioning saliency detectors with object classes reaches state-of-the-art performance, and 2) providing explicitly top-down saliency maps to visual classifiers enhances classification accuracy.

##### Abstract (translated by Google)
本文提出了一种由视觉分类任务指导的自上而下显着性检测的方法。我们首先学习如何在完成特定的视觉任务时计算视觉显着性，而不是仅仅通过自下而上的原则评估显着性的大多数最先进的方法。之后，我们调查视觉显着性是否以及在多大程度上支持非平凡病例的视觉分类。为此，我们提出了一个由两个网络联合训练的CNN框架SalClassNet：a）输入图像的第一个计算自顶向下的显着图; b）第二个利用计算的显着图进行视觉分类。为了测试我们的方法，我们使用Tobii T60眼动仪收集了一个眼睛注视图的数据集，要求几个学科从斯坦福犬数据集中查看图像，目的是区分狗的品种。对我们的数据集和其他显着性基准数据集（如POET）的性能分析显示，SalClassNet超出了SalNet和SALICON等最先进的显着性检测器。最后，我们分析了SalClassNet在细粒度识别任务中的性能，发现它比现有的视觉分类器更好地推广。所获得的结果表明：1）具有目标类别的调节显着性检测器达到最新的性能，以及2）为视觉分类器提供明显的自顶向下的显着图增强了分类准确性。

##### URL
[https://arxiv.org/abs/1709.05307](https://arxiv.org/abs/1709.05307)

##### PDF
[https://arxiv.org/pdf/1709.05307](https://arxiv.org/pdf/1709.05307)


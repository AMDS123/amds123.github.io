---
layout: post
title: "Annotating Object Instances with a Polygon-RNN"
date: 2017-04-18 22:17:28
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN Prediction
author: Lluis Castrejon, Kaustav Kundu, Raquel Urtasun, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach for semi-automatic annotation of object instances. While most current methods treat object segmentation as a pixel-labeling problem, we here cast it as a polygon prediction task, mimicking how most current datasets have been annotated. In particular, our approach takes as input an image crop and sequentially produces vertices of the polygon outlining the object. This allows a human annotator to interfere at any time and correct a vertex if needed, producing as accurate segmentation as desired by the annotator. We show that our approach speeds up the annotation process by a factor of 4.7 across all classes in Cityscapes, while achieving 78.4% agreement in IoU with original ground-truth, matching the typical agreement between human annotators. For cars, our speed-up factor is 7.3 for an agreement of 82.2%. We further show generalization capabilities of our approach to unseen datasets.

##### Abstract (translated by Google)
我们提出了一种半自动注释对象实例的方法。尽管目前大多数方法将对象分割视为像素标记问题，但我们将其作为一个多边形预测任务，模仿大多数当前数据集是如何被注释的。具体来说，我们的方法作为输入一个图像作物，并顺序产生概述该对象的多边形的顶点。这允许人类注释器在任何时候干涉并且如果需要校正顶点，产生如注释者所期望的准确分割。我们表明，我们的方法在城市风景中的所有类别上加快了注释过程的4.7倍，同时在原始地面事实上达到了78.4％的IoU一致性，与人类注释人之间的典型协议相匹配。对于汽车来说，我们的加速因素是7.3，达成了82.2％的协议。我们进一步显示了我们的方法的未知数据集的泛化能力。

##### URL
[https://arxiv.org/abs/1704.05548](https://arxiv.org/abs/1704.05548)

##### PDF
[https://arxiv.org/pdf/1704.05548](https://arxiv.org/pdf/1704.05548)


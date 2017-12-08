---
layout: post
title: "Adversarial Examples that Fool Detectors"
date: 2017-12-07 05:13:54
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Jiajun Lu, Hussein Sibai, Evan Fabry
mathjax: true
---

* content
{:toc}

##### Abstract
An adversarial example is an example that has been adjusted to produce a wrong label when presented to a system at test time. To date, adversarial example constructions have been demonstrated for classifiers, but not for detectors. If adversarial examples that could fool a detector exist, they could be used to (for example) maliciously create security hazards on roads populated with smart vehicles. In this paper, we demonstrate a construction that successfully fools two standard detectors, Faster RCNN and YOLO. The existence of such examples is surprising, as attacking a classifier is very different from attacking a detector, and that the structure of detectors - which must search for their own bounding box, and which cannot estimate that box very accurately - makes it quite likely that adversarial patterns are strongly disrupted. We show that our construction produces adversarial examples that generalize well across sequences digitally, even though large perturbations are needed. We also show that our construction yields physical objects that are adversarial.

##### Abstract (translated by Google)
敌对的例子是在测试时间被提交给系统时被调整以产生错误的标签的例子。迄今为止，已经为分类器展示了对抗性的示例性构造，但是对于检测器而言不是这样。如果存在可能欺骗探测器的对抗性例子，它们可能会被用来（例如）在智能车辆的道路上恶意制造安全隐患。在本文中，我们展示了一个成功地愚弄两个标准探测器，更快的RCNN和YOLO的构造。这样的例子的存在是令人惊讶的，因为攻击分类器与攻击检测器是非常不同的，检测器的结构 - 必须搜索自己的边界框，并且不能非常准确地估计框 - 使得很有可能敌对模式被强烈打乱。我们表明，我们的建设产生了对抗性的例子，即使需要大的扰动，数字化序列也能很好地推广。我们还表明，我们的建设产生对抗的物理对象。

##### URL
[http://arxiv.org/abs/1712.02494](http://arxiv.org/abs/1712.02494)

##### PDF
[http://arxiv.org/pdf/1712.02494](http://arxiv.org/pdf/1712.02494)


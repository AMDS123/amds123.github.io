---
layout: post
title: "Cut, Paste and Learn: Surprisingly Easy Synthesis for Instance Detection"
date: 2017-08-04 18:58:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Debidatta Dwibedi, Ishan Misra, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
A major impediment in rapidly deploying object detection models for instance detection is the lack of large annotated datasets. For example, finding a large labeled dataset containing instances in a particular kitchen is unlikely. Each new environment with new instances requires expensive data collection and annotation. In this paper, we propose a simple approach to generate large annotated instance datasets with minimal effort. Our key insight is that ensuring only patch-level realism provides enough training signal for current object detector models. We automatically `cut' object instances and `paste' them on random backgrounds. A naive way to do this results in pixel artifacts which result in poor performance for trained models. We show how to make detectors ignore these artifacts during training and generate data that gives competitive performance on real data. Our method outperforms existing synthesis approaches and when combined with real images improves relative performance by more than 21% on benchmark datasets. In a cross-domain setting, our synthetic data combined with just 10% real data outperforms models trained on all real data.

##### Abstract (translated by Google)
在实例检测中快速部署对象检测模型的一个主要障碍是缺少大的注释数据集。例如，在特定的厨房中找到包含实例的大型标签数据集是不太可能的。每个具有新实例的新环境都需要昂贵的数据收集和注释。在本文中，我们提出了一种简单的方法来以最小的努力生成大型的带注释的实例数据集。我们关键的洞察是确保只有补丁级别的真实性为当前的物体探测器模型提供足够的训练信号。我们自动“剪切”对象实例并将它们粘贴到随机背景上。一个幼稚的方式来做这个会导致像素人为因素导致训练模型的糟糕的表现。我们展示了如何让检测器在训练过程中忽略这些工件，并生成数据，从而提供真实数据的有竞争力的表现。我们的方法胜过现有的综合方法，当与真实图像相结合时，基准数据集的相对性能提高了21％以上。在跨域设置中，我们的综合数据与仅10％的实际数据相结合，胜过了所有真实数据的训练模型。

##### URL
[https://arxiv.org/abs/1708.01642](https://arxiv.org/abs/1708.01642)

##### PDF
[https://arxiv.org/pdf/1708.01642](https://arxiv.org/pdf/1708.01642)


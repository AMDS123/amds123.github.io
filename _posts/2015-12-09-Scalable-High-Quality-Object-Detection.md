---
layout: post
title: "Scalable, High-Quality Object Detection"
date: 2015-12-09 03:41:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Christian Szegedy, Scott Reed, Dumitru Erhan, Dragomir Anguelov, Sergey Ioffe
mathjax: true
---

* content
{:toc}

##### Abstract
Current high-quality object detection approaches use the scheme of salience-based object proposal methods followed by post-classification using deep convolutional features. This spurred recent research in improving object proposal methods. However, domain agnostic proposal generation has the principal drawback that the proposals come unranked or with very weak ranking, making it hard to trade-off quality for running time. This raises the more fundamental question of whether high-quality proposal generation requires careful engineering or can be derived just from data alone. We demonstrate that learning-based proposal methods can effectively match the performance of hand-engineered methods while allowing for very efficient runtime-quality trade-offs. Using the multi-scale convolutional MultiBox (MSC-MultiBox) approach, we substantially advance the state-of-the-art on the ILSVRC 2014 detection challenge data set, with $0.5$ mAP for a single model and $0.52$ mAP for an ensemble of two models. MSC-Multibox significantly improves the proposal quality over its predecessor MultiBox~method: AP increases from $0.42$ to $0.53$ for the ILSVRC detection challenge. Finally, we demonstrate improved bounding-box recall compared to Multiscale Combinatorial Grouping with less proposals on the Microsoft-COCO data set.

##### Abstract (translated by Google)
目前的高质量对象检测方法使用基于显着性的对象提议方法的方案，随后使用深度卷积特征进行后分类。这激发了最近在改进对象提议方法方面的研究。但是，域不可知的提案生成的主要缺点是提案没有排名或者排名非常低，使得难以在运行时间上取舍质量。这就提出了一个更为根本性的问题：高质量的提案生成是需要精心设计还是只能从数据中提取。我们证明，基于学习的提案方法可以有效地匹配手工方法的性能，同时允许非常有效的运行时质量折衷。使用多尺度卷积MultiBox（MSC-MultiBox）方法，我们大大提高了ILSVRC 2014检测挑战数据集的最新技术水平，单个模型为$ 0.5 $ mAP，合并为$ 0.52 $ mAP两个模型。对于ILSVRC检测挑战，MSC-Multibox相对于其前身MultiBox〜方法显着提高了提案质量：AP从$ 0.42 $增加到$ 0.53 $。最后，我们展示了与多尺度组合分组相比改进的边界框回忆，并且在Microsoft-COCO数据集上的建议较少。

##### URL
[https://arxiv.org/abs/1412.1441](https://arxiv.org/abs/1412.1441)

##### PDF
[https://arxiv.org/pdf/1412.1441](https://arxiv.org/pdf/1412.1441)


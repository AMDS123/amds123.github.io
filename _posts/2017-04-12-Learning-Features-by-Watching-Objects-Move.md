---
layout: post
title: "Learning Features by Watching Objects Move"
date: 2017-04-12 04:28:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Transfer_Learning Detection
author: Deepak Pathak, Ross Girshick, Piotr Dollár, Trevor Darrell, Bharath Hariharan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel yet intuitive approach to unsupervised feature learning. Inspired by the human visual system, we explore whether low-level motion-based grouping cues can be used to learn an effective visual representation. Specifically, we use unsupervised motion-based segmentation on videos to obtain segments, which we use as 'pseudo ground truth' to train a convolutional network to segment objects from a single frame. Given the extensive evidence that motion plays a key role in the development of the human visual system, we hope that this straightforward approach to unsupervised learning will be more effective than cleverly designed 'pretext' tasks studied in the literature. Indeed, our extensive experiments show that this is the case. When used for transfer learning on object detection, our representation significantly outperforms previous unsupervised approaches across multiple settings, especially when training data for the target task is scarce.

##### Abstract (translated by Google)
本文提出了一种新颖而直观的无监督特征学习方法。受人类视觉系统的启发，我们探讨是否可以使用低级别的基于运动的分组线索来学习有效的视觉表示。具体而言，我们使用无监督的基于视频的运动分割来获取片段，我们将其用作“伪基础真实”来训练卷积网络以从单个帧中分割对象。鉴于运动在人类视觉系统发展中起着关键作用的广泛证据，我们希望这种直接的无监督学习方法比文献中研究的巧妙设计的“借口”任务更有效。事实上，我们广泛的实验表明，情况就是如此。当用于物体检测的转移学习时，我们的表示明显优于以前的多个设置的无监督方法，特别是当目标任务的训练数据稀缺时。

##### URL
[https://arxiv.org/abs/1612.06370](https://arxiv.org/abs/1612.06370)

##### PDF
[https://arxiv.org/pdf/1612.06370](https://arxiv.org/pdf/1612.06370)


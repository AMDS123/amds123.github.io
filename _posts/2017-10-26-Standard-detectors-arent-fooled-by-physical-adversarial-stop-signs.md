---
layout: post
title: "Standard detectors aren't fooled by physical adversarial stop signs"
date: 2017-10-26 21:53:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Face Detection
author: Jiajun Lu, Hussein Sibai, Evan Fabry, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
An adversarial example is an example that has been adjusted to produce the wrong label when presented to a system at test time. If adversarial examples existed that could fool a detector, they could be used to (for example) wreak havoc on roads populated with smart vehicles. Recently, we described our difficulties creating physical adversarial stop signs that fool a detector. More recently, Evtimov et al. produced a physical adversarial stop sign that fools a proxy model of a detector. In this paper, we show that these physical adversarial stop signs do not fool two standard detectors (YOLO and Faster RCNN) in standard configuration. Evtimov et al.'s construction relies on a crop of the image to the stop sign; this crop is then resized and presented to a classifier. We argue that the cropping and resizing procedure largely eliminates the effects of rescaling and of view angle. Whether an adversarial attack is robust under rescaling and change of view direction remains moot. We argue that attacking a classifier is very different from attacking a detector, and that the structure of detectors - which must search for their own bounding box, and which cannot estimate that box very accurately - likely makes it difficult to make adversarial patterns. Finally, an adversarial pattern on a physical object that could fool a detector would have to be adversarial in the face of a wide family of parametric distortions (scale; view angle; box shift inside the detector; illumination; and so on). Such a pattern would be of great theoretical and practical interest. There is currently no evidence that such patterns exist.

##### Abstract (translated by Google)
一个对抗性的例子就是一个在测试时被提交给系统时被调整为产生错误标签的例子。如果敌对的例子存在可能欺骗探测器的例子，那么他们可能会被用来（例如）在智能车辆的道路上造成严重破坏。最近，我们描述了我们的困难造成物理敌对的停止迹象，欺骗探测器。最近，Evtimov et al。产生了一个欺骗探测器代理模型的物理对抗停车标志。在本文中，我们表明这些物理对抗停止标志不愚弄标准配置中的两个标准检测器（YOLO和更快的RCNN）。 Evtimov等人的建筑依靠一幅画面的形象停止标志;这个作物然后调整大小，并呈现给分类器。我们认为，裁剪和调整大小程序很大程度上消除了重新缩放和视角的影响。对抗性攻击在重新缩放和改变视角方向上是否稳健仍然没有实际意义。我们认为，攻击分类器与攻击探测器是非常不同的，探测器的结构 - 必须搜索自己的边界框，并且不能非常准确地估计框 - 可能使得难以形成对抗模式。最后，面对广泛的参数失真（比例尺，视角，检测器内的盒子移位，照明等等），物理对象上的对抗模式可能会欺骗检测器。这样的模式将具有重大的理论和实践意义。目前还没有证据表明存在这种模式。

##### URL
[https://arxiv.org/abs/1710.03337](https://arxiv.org/abs/1710.03337)

##### PDF
[https://arxiv.org/pdf/1710.03337](https://arxiv.org/pdf/1710.03337)


---
layout: post
title: "Note on Attacking Object Detectors with Adversarial Stickers"
date: 2017-12-21 16:33:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Deep_Learning Detection
author: Kevin Eykholt, Ivan Evtimov, Earlence Fernandes, Bo Li, Dawn Song, Tadayoshi Kohno, Amir Rahmati, Atul Prakash, Florian Tramer
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has proven to be a powerful tool for computer vision and has seen widespread adoption for numerous tasks. However, deep learning algorithms are known to be vulnerable to adversarial examples. These adversarial inputs are created such that, when provided to a deep learning algorithm, they are very likely to be mislabeled. This can be problematic when deep learning is used to assist in safety critical decisions. Recent research has shown that classifiers can be attacked by physical adversarial examples under various physical conditions. Given the fact that state-of-the-art objection detection algorithms are harder to be fooled by the same set of adversarial examples, here we show that these detectors can also be attacked by physical adversarial examples. In this note, we briefly show both static and dynamic test results. We design an algorithm that produces physical adversarial inputs, which can fool the YOLO object detector and can also attack Faster-RCNN with relatively high success rate based on transferability. Furthermore, our algorithm can compress the size of the adversarial inputs to stickers that, when attached to the targeted object, result in the detector either mislabeling or not detecting the object a high percentage of the time. This note provides a small set of results. Our upcoming paper will contain a thorough evaluation on other object detectors, and will present the algorithm.

##### Abstract (translated by Google)
深度学习已经被证明是计算机视觉的一个强大的工具，并且已经被广泛的应用于许多任务中。然而，已知深度学习算法容易受到敌对的例子。这些对抗性输入被创建，使得当提供给深度学习算法时，它们很可能被错误标记。当深度学习被用来协助安全关键的决策时，这可能是有问题的。最近的研究表明，分类器可以在各种物理条件下受到物理对抗的攻击。鉴于最先进的异议检测算法难以被相同的敌对案例所迷惑，这里我们展示了这些检测器也可能受到物理对抗案例的攻击。在这个笔记中，我们简要地显示静态和动态测试结果。我们设计了一种产生物理敌对输入的算法，可以欺骗YOLO物体检测器，并且可以基于可转移性以较高的成功率攻击Faster-RCNN。此外，我们的算法可以将对抗输入的大小压缩为贴纸，当贴在目标物体上时，会导致检测器贴错标签，或者检测不到物体的高百分比时间。本笔记提供了一小组结果。我们即将发表的论文将包含对其他物体探测器的全面评估，并将介绍该算法。

##### URL
[http://arxiv.org/abs/1712.08062](http://arxiv.org/abs/1712.08062)

##### PDF
[http://arxiv.org/pdf/1712.08062](http://arxiv.org/pdf/1712.08062)


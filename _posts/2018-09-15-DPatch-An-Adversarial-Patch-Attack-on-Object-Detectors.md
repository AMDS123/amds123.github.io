---
layout: post
title: "DPatch: An Adversarial Patch Attack on Object Detectors"
date: 2018-09-15 03:08:34
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Knowledge Prediction Detection
author: Xin Liu, Huanrui Yang, Ziwei Liu, Linghao Song, Hai Li, Yiran Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Object detectors have emerged as an indispensable module in modern computer vision systems. Their vulnerability to adversarial attacks thus become a vital issue to consider. In this work, we propose DPatch, a adversarial-patch-based attack towards mainstream object detectors (i.e., Faster R-CNN and YOLO). Unlike the original adversarial patch that only manipulates image-level classifier, our DPatch simultaneously optimizes the bounding box location and category targets so as to disable their predictions. Compared to prior works, DPatch has several appealing properties: (1) DPatch can perform both untargeted and targeted effective attacks, degrading the mAP of Faster R-CNN and YOLO from 70.0% and 65.7% down to below 1% respectively; (2) DPatch is small in size and its attacking effect is location-independent, making it very practical to implement real-world attacks; (3) DPatch demonstrates great transferability between different detector architectures. For example, DPatch that is trained on Faster R-CNN can effectively attack YOLO, and vice versa. Extensive evaluations imply that DPatch can perform effective attacks under black-box setup, i.e., even without the knowledge of the attacked network's architectures and parameters. The successful realization of DPatch also illustrates the intrinsic vulnerability of the modern detector architectures to such patch-based adversarial attacks.

##### Abstract (translated by Google)
物体探测器已成为现代计算机视觉系统中不可或缺的模块。因此，他们对抗对抗性攻击的脆弱性成为一个需要考虑的重要问题。在这项工作中，我们提出了DPatch，一种针对主流物体探测器的基于对抗补丁的攻击（即，更快的R-CNN和YOLO）。与仅操纵图像级分类器的原始对抗补丁不同，我们的DPatch同时优化边界框位置和类别目标，以禁用其预测。与之前的工作相比，DPatch具有以下几个吸引人的特性：（1）DPatch可以同时执行非目标和有针对性的有效攻击，将快速R-CNN和YOLO的mAP分别从70.0％和65.7％降至1％以下; （2）DPatch体积小，攻击效果与位置无关，实现真实攻击非常实用; （3）DPatch在不同的探测器架构之间展示了很好的可转移性。例如，在更快的R-CNN上训练的DPatch可以有效地攻击YOLO，反之亦然。广泛的评估意味着DPatch可以在黑盒设置下执行有效的攻击，即使不了解受攻击网络的架构和参数。 DPatch的成功实现也说明了现代探测器架构对这种基于补丁的对抗性攻击的内在脆弱性。

##### URL
[http://arxiv.org/abs/1806.02299](http://arxiv.org/abs/1806.02299)

##### PDF
[http://arxiv.org/pdf/1806.02299](http://arxiv.org/pdf/1806.02299)


---
layout: post
title: "A-Fast-RCNN: Hard Positive Generation via Adversary for Object Detection"
date: 2017-04-11 16:57:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Xiaolong Wang, Abhinav Shrivastava, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
How do we learn an object detector that is invariant to occlusions and deformations? Our current solution is to use a data-driven strategy -- collect large-scale datasets which have object instances under different conditions. The hope is that the final classifier can use these examples to learn invariances. But is it really possible to see all the occlusions in a dataset? We argue that like categories, occlusions and object deformations also follow a long-tail. Some occlusions and deformations are so rare that they hardly happen; yet we want to learn a model invariant to such occurrences. In this paper, we propose an alternative solution. We propose to learn an adversarial network that generates examples with occlusions and deformations. The goal of the adversary is to generate examples that are difficult for the object detector to classify. In our framework both the original detector and adversary are learned in a joint manner. Our experimental results indicate a 2.3% mAP boost on VOC07 and a 2.6% mAP boost on VOC2012 object detection challenge compared to the Fast-RCNN pipeline. We also release the code for this paper.

##### Abstract (translated by Google)
我们如何学习一个对遮挡和变形不变的物体检测器？我们目前的解决方案是使用数据驱动策略 - 收集具有不同条件下的对象实例的大规模数据集。希望最终的分类器可以使用这些例子来学习不变的。但是真的有可能看到数据集中的所有遮挡？我们认为，像类别，遮挡和对象变形也遵循一个长尾巴。有些闭塞和变形是非常罕见的，几乎不发生。但是我们想要学习一个不变的模型。在本文中，我们提出了一个替代解决方案。我们建议学习一个敌对的网络，生成包含遮挡和变形的例子。对手的目标是生成对于物体检测器难以分类的示例。在我们的框架中，原始探测器和对手都是联合学习的。我们的实验结果表明，与Fast-RCNN管道相比，VOC07上的2.3％mAP提升和VOC2012目标检测挑战上的2.6％mAP提升。我们也发布了这篇论文的代码。

##### URL
[https://arxiv.org/abs/1704.03414](https://arxiv.org/abs/1704.03414)


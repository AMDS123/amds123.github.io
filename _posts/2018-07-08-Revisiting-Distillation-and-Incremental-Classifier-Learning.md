---
layout: post
title: "Revisiting Distillation and Incremental Classifier Learning"
date: 2018-07-08 11:42:31
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Khurram Javed, Faisal Shafait
mathjax: true
---

* content
{:toc}

##### Abstract
One of the key differences between the learning mechanism of humans and Artificial Neural Networks (ANNs) is the ability of humans to learn one task at a time. ANNs, on the other hand, can only learn multiple tasks simultaneously. Any attempts at learning new tasks incrementally cause them to completely forget about previous tasks. This lack of ability to learn incrementally, called Catastrophic Forgetting, is considered a major hurdle in building a true AI system. In this paper, our goal is to isolate the truly effective existing ideas for incremental learning from those that only work under certain conditions. To this end, we first thoroughly analyze the current state of the art (iCaRL) method for incremental learning and demonstrate that the good performance of the system is not because of the reasons presented in the existing literature. We conclude that the success of iCaRL is primarily due to knowledge distillation and recognize a key limitation of knowledge distillation, i.e, it often leads to bias in classifiers. Finally, we propose a dynamic threshold moving algorithm that is able to successfully remove this bias. We demonstrate the effectiveness of our algorithm on CIFAR100 and MNIST datasets showing near-optimal results. Our implementation is available at https://github.com/Khurramjaved96/incremental-learning.

##### Abstract (translated by Google)
人类学习机制与人工神经网络（ANN）之间的关键差异之一是人类一次学习一项任务的能力。另一方面，人工神经网络只能同时学习多项任务。任何尝试逐步学习新任务都会导致他们完全忘记以前的任务。这种缺乏逐渐学习的能力，称为灾难遗忘，被认为是建立真正的人工智能系统的主要障碍。在本文中，我们的目标是将真正有效的现有增量学习理念与仅在某些条件下工作的理念隔离开来。为此，我们首先彻底分析了当前的增量学习技术（iCaRL）方法，并证明系统的良好性能不是由于现有文献中提出的原因。我们得出结论，iCaRL的成功主要归功于知识蒸馏，并认识到知识蒸馏的关键限制，即它经常导致分类器的偏差。最后，我们提出了一种能够成功消除这种偏差的动态阈值移动算法。我们证明了我们的算法在CIFAR100和MNIST数据集上的有效性，显示了接近最优的结果。我们的实现可以在https://github.com/Khurramjaved96/incremental-learning上找到。

##### URL
[http://arxiv.org/abs/1807.02802](http://arxiv.org/abs/1807.02802)

##### PDF
[http://arxiv.org/pdf/1807.02802](http://arxiv.org/pdf/1807.02802)


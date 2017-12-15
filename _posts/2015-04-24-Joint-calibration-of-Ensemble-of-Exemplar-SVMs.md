---
layout: post
title: "Joint calibration of Ensemble of Exemplar SVMs"
date: 2015-04-24 16:42:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Detection
author: Davide Modolo, Alexander Vezhnevets, Olga Russakovsky, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for calibrating the Ensemble of Exemplar SVMs model. Unlike the standard approach, which calibrates each SVM independently, our method optimizes their joint performance as an ensemble. We formulate joint calibration as a constrained optimization problem and devise an efficient optimization algorithm to find its global optimum. The algorithm dynamically discards parts of the solution space that cannot contain the optimum early on, making the optimization computationally feasible. We experiment with EE-SVM trained on state-of-the-art CNN descriptors. Results on the ILSVRC 2014 and PASCAL VOC 2007 datasets show that (i) our joint calibration procedure outperforms independent calibration on the task of classifying windows as belonging to an object class or not; and (ii) this improved window classifier leads to better performance on the object detection task.

##### Abstract (translated by Google)
我们提出了一个校准Exemplar SVMs模型的方法。与标准方法（独立校准每个SVM）不同，我们的方法优化了它们作为一个整体的联合性能。我们将联合校准作为一个约束优化问题，并设计一个有效的优化算法来寻找其全局最优。该算法动态地丢弃了一些不能包含最优解的解空间的部分，使得优化在计算上是可行的。我们试验了用最先进的CNN描述符进行训练的EE-SVM。 ILSVRC 2014和PASCAL VOC 2007数据集的结果显示：（i）我们的联合校准程序优于独立校准，将窗口归类为属于一个对象类别;和（ii）这种改进的窗口分类器导致对物体检测任务更好的性能。

##### URL
[https://arxiv.org/abs/1503.00783](https://arxiv.org/abs/1503.00783)

##### PDF
[https://arxiv.org/pdf/1503.00783](https://arxiv.org/pdf/1503.00783)


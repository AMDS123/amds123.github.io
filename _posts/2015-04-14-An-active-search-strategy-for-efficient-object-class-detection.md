---
layout: post
title: "An active search strategy for efficient object class detection"
date: 2015-04-14 11:29:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Detection
author: Abel Gonzalez-Garcia, Alexander Vezhnevets, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Object class detectors typically apply a window classifier to all the windows in a large set, either in a sliding window manner or using object proposals. In this paper, we develop an active search strategy that sequentially chooses the next window to evaluate based on all the information gathered before. This results in a substantial reduction in the number of classifier evaluations and in a more elegant approach in general. Our search strategy is guided by two forces. First, we exploit context as the statistical relation between the appearance of a window and its location relative to the object, as observed in the training set. This enables to jump across distant regions in the image (e.g. observing a sky region suggests that cars might be far below) and is done efficiently in a Random Forest framework. Second, we exploit the score of the classifier to attract the search to promising areas surrounding a highly scored window, and to keep away from areas near low scored ones. Our search strategy can be applied on top of any classifier as it treats it as a black-box. In experiments with R-CNN on the challenging SUN2012 dataset, our method matches the detection accuracy of evaluating all windows independently, while evaluating 9x fewer windows.

##### Abstract (translated by Google)
对象类检测器通常以滑动窗口的方式或使用对象提议将窗口分类器应用于大集合中的所有窗口。在本文中，我们开发了一个主动搜索策略，依次选择下一个窗口来评估基于以前收集的所有信息。这导致了分类器评估数量的大幅减少，并且总体上更加优雅。我们的搜索策略是由两个力量的指导。首先，我们利用上下文作为在训练集中观察到的窗口外观与其相对于对象的位置之间的统计关系。这使得能够跳过图像中的遥远的区域（例如，观察天空区域表明汽车可能远远低于），并且在随机森林框架中有效地完成。其次，我们利用分类器的分数来吸引对高分值窗口周围的有希望的区域的搜索，并远离低分区域附近的区域。我们的搜索策略可以应用在任何分类器之上，因为它将其视为黑盒子。在具有挑战性的SUN2012数据集的R-CNN实验中，我们的方法与独立评估所有窗口的检测精度相匹配，而评估窗口数量减少了9倍。

##### URL
[https://arxiv.org/abs/1412.3709](https://arxiv.org/abs/1412.3709)

##### PDF
[https://arxiv.org/pdf/1412.3709](https://arxiv.org/pdf/1412.3709)


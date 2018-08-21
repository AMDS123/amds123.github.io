---
layout: post
title: "DeeSIL: Deep-Shallow Incremental Learning"
date: 2018-08-20 11:39:09
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Deep_Learning Recognition
author: Eden Belouadah, Adrian Popescu
mathjax: true
---

* content
{:toc}

##### Abstract
Incremental Learning (IL) is an interesting AI problem when the algorithm is assumed to work on a budget. This is especially true when IL is modeled using a deep learning approach, where two com- plex challenges arise due to limited memory, which induces catastrophic forgetting and delays related to the retraining needed in order to incorpo- rate new classes. Here we introduce DeeSIL, an adaptation of a known transfer learning scheme that combines a fixed deep representation used as feature extractor and learning independent shallow classifiers to in- crease recognition capacity. This scheme tackles the two aforementioned challenges since it works well with a limited memory budget and each new concept can be added within a minute. Moreover, since no deep re- training is needed when the model is incremented, DeeSIL can integrate larger amounts of initial data that provide more transferable features. Performance is evaluated on ImageNet LSVRC 2012 against three state of the art algorithms. Results show that, at scale, DeeSIL performance is 23 and 33 points higher than the best baseline when using the same and more initial data respectively.

##### Abstract (translated by Google)
当假定算法在预算上工作时，增量学习（IL）是一个有趣的AI问题。当使用深度学习方法对IL进行建模时尤其如此，其中由于有限的记忆而出现两个复杂的挑战，这导致灾难性的遗忘和与为了合并新类所需的再训练相关的延迟。这里我们介绍DeeSIL，它是一种已知的转移学习方案的改编，它结合了用作特征提取器的固定深度表示和学习独立的浅层分类器，以提高识别能力。该方案解决了上述两个挑战，因为它在有限的内存预算下运行良好，每个新概念可以在一分钟内添加。此外，由于模型递增时不需要深度重新训练，因此DeeSIL可以集成更大量的初始数据，从而提供更多可转移的功能。在ImageNet LSVRC 2012上针对三种最先进的算法评估性能。结果表明，在规模上，当分别使用相同和更多的初始数据时，DeeSIL性能比最佳基线高23和33个点。

##### URL
[http://arxiv.org/abs/1808.06396](http://arxiv.org/abs/1808.06396)

##### PDF
[http://arxiv.org/pdf/1808.06396](http://arxiv.org/pdf/1808.06396)


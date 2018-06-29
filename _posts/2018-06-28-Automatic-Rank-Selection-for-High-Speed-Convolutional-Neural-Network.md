---
layout: post
title: "Automatic Rank Selection for High-Speed Convolutional Neural Network"
date: 2018-06-28 08:25:40
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference
author: Hyeji Kim, Chong-Min Kyung
mathjax: true
---

* content
{:toc}

##### Abstract
Low-rank decomposition plays a central role in accelerating convolutional neural network (CNN), and the rank of decomposed kernel-tensor is a key parameter that determines the complexity and accuracy of a neural network. In this paper, we define rank selection as a combinatorial optimization problem and propose a methodology to minimize network complexity while maintaining the desired accuracy. Combinatorial optimization is not feasible due to search space limitations. To restrict the search space and obtain the optimal rank, we define the space constraint parameters with a boundary condition. We also propose a linearly-approximated accuracy function to predict the fine-tuned accuracy of the optimized CNN model during the cost reduction. Experimental results on AlexNet and VGG-16 show that the proposed rank selection algorithm satisfies the accuracy constraint. Our method combined with truncated-SVD outperforms state-of-the-art methods in terms of inference and training time at almost the same accuracy.

##### Abstract (translated by Google)
低阶分解在加速卷积神经网络（CNN）中起着核心作用，分解核内张量的秩是决定神经网络复杂性和精确性的关键参数。在本文中，我们将秩选择定义为组合优化问题，并提出一种方法来最小化网络复杂度，同时保持所需的准确性。由于搜索空间限制，组合优化不可行。为了限制搜索空间并获得最优秩，我们用边界条件定义空间约束参数。我们还提出了一个线性近似精度函数来预测优化CNN模型在降低成本期间的精确调整精度。在AlexNet和VGG-16上的实验结果表明，所提出的秩选择算法满足精度约束。我们的方法结合截断SVD在推理和训练时间方面的性能优于最先进的方法，精度几乎相同。

##### URL
[http://arxiv.org/abs/1806.10821](http://arxiv.org/abs/1806.10821)

##### PDF
[http://arxiv.org/pdf/1806.10821](http://arxiv.org/pdf/1806.10821)


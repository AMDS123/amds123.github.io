---
layout: post
title: "A discriminative view of MRF pre-processing algorithms"
date: 2017-08-08 22:41:43
categories: arXiv_CV
tags: arXiv_CV Inference Classification
author: Chen Wang, Charles Herrmann, Ramin Zabih
mathjax: true
---

* content
{:toc}

##### Abstract
While Markov Random Fields (MRFs) are widely used in computer vision, they present a quite challenging inference problem. MRF inference can be accelerated by pre-processing techniques like Dead End Elimination (DEE) or QPBO-based approaches which compute the optimal labeling of a subset of variables. These techniques are guaranteed to never wrongly label a variable but they often leave a large number of variables unlabeled. We address this shortcoming by interpreting pre-processing as a classification problem, which allows us to trade off false positives (i.e., giving a variable an incorrect label) versus false negatives (i.e., failing to label a variable). We describe an efficient discriminative rule that finds optimal solutions for a subset of variables. Our technique provides both per-instance and worst-case guarantees concerning the quality of the solution. Empirical studies were conducted over several benchmark datasets. We obtain a speedup factor of 2 to 12 over expansion moves without preprocessing, and on difficult non-submodular energy functions produce slightly lower energy.

##### Abstract (translated by Google)
尽管马尔可夫随机场（MRF）在计算机视觉中被广泛使用，但它们提出了一个相当具有挑战性的推理问题。 MRF推理可以通过预处理技术（如Dead End Elimination（DEE））或基于QPBO的方法来加速，这些方法计算变量子集的最佳标记。这些技术保证永远不会错误地标记一个变量，但是他们往往会留下大量的未标记的变量。我们通过将预处理解释为分类问题来解决这个缺点，这允许我们将假阳性（即给出变量不正确的标签）与假阴性（即，不能标注变量）进行交换。我们描述了一个有效的判别规则，为变量子集找到最优解。我们的技术针对解决方案的质量提供了每个实例和最差情况下的保证。对几个基准数据集进行实证研究。在没有预处理的情况下，我们可以获得2到12的加速因子，而在非子模块能量函数上，能量会稍低。

##### URL
[https://arxiv.org/abs/1708.02668](https://arxiv.org/abs/1708.02668)

##### PDF
[https://arxiv.org/pdf/1708.02668](https://arxiv.org/pdf/1708.02668)


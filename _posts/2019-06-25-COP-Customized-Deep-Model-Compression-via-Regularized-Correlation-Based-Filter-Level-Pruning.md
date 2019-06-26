---
layout: post
title: "COP: Customized Deep Model Compression via Regularized Correlation-Based Filter-Level Pruning"
date: 2019-06-25 06:15:42
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Relation
author: Wenxiao Wang, Cong Fu, Jishun Guo, Deng Cai, Xiaofei He
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network compression empowers the effective yet unwieldy deep convolutional neural networks (CNN) to be deployed in resource-constrained scenarios. Most state-of-the-art approaches prune the model in filter-level according to the "importance" of filters. Despite their success, we notice they suffer from at least two of the following problems: 1) The redundancy among filters is not considered because the importance is evaluated independently. 2) Cross-layer filter comparison is unachievable since the importance is defined locally within each layer. Consequently, we must manually specify layer-wise pruning ratios. 3) They are prone to generate sub-optimal solutions because they neglect the inequality between reducing parameters and reducing computational cost. Reducing the same number of parameters in different positions in the network may reduce different computational cost. To address the above problems, we develop a novel algorithm named as COP (correlation-based pruning), which can detect the redundant filters efficiently. We enable the cross-layer filter comparison through global normalization. We add parameter-quantity and computational-cost regularization terms to the importance, which enables the users to customize the compression according to their preference (smaller or faster). Extensive experiments have shown COP outperforms the others significantly. The code is released at https://github.com/ZJULearning/COP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10337](http://arxiv.org/abs/1906.10337)

##### PDF
[http://arxiv.org/pdf/1906.10337](http://arxiv.org/pdf/1906.10337)


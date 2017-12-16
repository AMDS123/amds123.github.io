---
layout: post
title: "Progressive Boosting for Class Imbalance"
date: 2017-06-05 20:32:55
categories: arXiv_CV
tags: arXiv_CV Re-identification Face Classification Prediction Recognition
author: Roghayeh Soleymani, Eric Granger, Giorgio Fumera
mathjax: true
---

* content
{:toc}

##### Abstract
Pattern recognition applications often suffer from skewed data distributions between classes, which may vary during operations w.r.t. the design data. Two-class classification systems designed using skewed data tend to recognize the majority class better than the minority class of interest. Several data-level techniques have been proposed to alleviate this issue by up-sampling minority samples or under-sampling majority samples. However, some informative samples may be neglected by random under-sampling and adding synthetic positive samples through up-sampling adds to training complexity. In this paper, a new ensemble learning algorithm called Progressive Boosting (PBoost) is proposed that progressively inserts uncorrelated groups of samples into a Boosting procedure to avoid loss of information while generating a diverse pool of classifiers. Base classifiers in this ensemble are generated from one iteration to the next, using subsets from a validation set that grows gradually in size and imbalance. Consequently, PBoost is more robust to unknown and variable levels of skew in operational data, and has lower computation complexity than Boosting ensembles in literature. In PBoost, a new loss factor is proposed to avoid bias of performance towards the negative class. Using this loss factor, the weight update of samples and classifier contribution in final predictions are set based on the ability to recognize both classes. Using the proposed loss factor instead of standard accuracy can avoid biasing performance in any Boosting ensemble. The proposed approach was validated and compared using synthetic data, videos from the FIA dataset that emulates face re-identification applications, and KEEL collection of datasets. Results show that PBoost can outperform state of the art techniques in terms of both accuracy and complexity over different levels of imbalance and overlap between classes.

##### Abstract (translated by Google)
模式识别应用程序经常遭受类之间的偏斜的数据分布，这在操作w.r.t中可能会变化。设计数据。使用倾斜数据设计的两级分类系统倾向于比少数利益类别更好地识别多数类别。已经提出了几种数据级别的技术来通过对少数样本进行上采样或对大部分样本进行欠采样来减轻这个问题。然而，一些有信息的样本可能会被随机欠采样忽略，通过上采样添加合成的正样本会增加训练的复杂度。在本文中，提出了一种新的集成学习算法 - 渐进式Boosting（PBoost），它逐步将不相关的样本组插入到Boosting过程中，以避免信息的丢失，同时产生多样化的分类器池。这个集合中的基本分类器是从一个迭代到下一个迭代生成的，使用来自验证集合的子集，这个验证集的大小和不平衡度都是逐渐增长的。因此，PBoost在操作数据中对于未知和不确定的偏斜水平具有更强的鲁棒性，并且比Boosting集合在文献中计算复杂度更低。在PBoost中，提出了一个新的损失因子来避免表现对负面类的偏见。使用这个损失因子，在最终预测中样本和分类器贡献的权重更新是基于识别两个类别的能力来设置的。使用建议的损耗因子而不是标准精度可以避免任何Boosting集成中的偏置性能。所提出的方法已经过验证，并且使用合成数据，来自FIA数据集的模拟面部重新识别应用的视频以及KEEL数据集集合进行比较。结果表明，PBoost在不同程度的不平衡和类别重叠的情况下，在准确性和复杂性方面都可以胜过现有技术。

##### URL
[https://arxiv.org/abs/1706.01531](https://arxiv.org/abs/1706.01531)

##### PDF
[https://arxiv.org/pdf/1706.01531](https://arxiv.org/pdf/1706.01531)


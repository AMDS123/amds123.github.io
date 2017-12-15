---
layout: post
title: "Clustering Based Feature Learning on Variable Stars"
date: 2016-02-29 14:26:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Survey Classification
author: Cristóbal Mackenzie, Karim Pichara, Pavlos Protopapas
mathjax: true
---

* content
{:toc}

##### Abstract
The success of automatic classification of variable stars strongly depends on the lightcurve representation. Usually, lightcurves are represented as a vector of many statistical descriptors designed by astronomers called features. These descriptors commonly demand significant computational power to calculate, require substantial research effort to develop and do not guarantee good performance on the final classification task. Today, lightcurve representation is not entirely automatic; algorithms that extract lightcurve features are designed by humans and must be manually tuned up for every survey. The vast amounts of data that will be generated in future surveys like LSST mean astronomers must develop analysis pipelines that are both scalable and automated. Recently, substantial efforts have been made in the machine learning community to develop methods that prescind from expert-designed and manually tuned features for features that are automatically learned from data. In this work we present what is, to our knowledge, the first unsupervised feature learning algorithm designed for variable stars. Our method first extracts a large number of lightcurve subsequences from a given set of photometric data, which are then clustered to find common local patterns in the time series. Representatives of these patterns, called exemplars, are then used to transform lightcurves of a labeled set into a new representation that can then be used to train an automatic classifier. The proposed algorithm learns the features from both labeled and unlabeled lightcurves, overcoming the bias generated when the learning process is done only with labeled data. We test our method on MACHO and OGLE datasets; the results show that the classification performance we achieve is as good and in some cases better than the performance achieved using traditional features, while the computational cost is significantly lower.

##### Abstract (translated by Google)
变星的自动分类的成功与否取决于光曲线的表示。通常，光线曲线表示为由天文学家设计的许多统计描述符的矢量，称为特征。这些描述符通常需要大量的计算能力来计算，需要大量的研究工作来开发，并且不能保证最终分类任务的良好性能。今天，光线曲线并不是完全自动的，提取光曲线特征的算法是由人类设计的，必须手动调整每个调查的算法。大量的数据将在未来的LSST调查中产生，这意味着天文学家必须开发可扩展和自动化的分析流水线。最近，机器学习社区已经做出重大努力来开发从专家设计和手动调整的特征中预先获得从数据中自动学习的特征的方法。在这项工作中，我们介绍了我们所知道的第一个为变星设计的无监督特征学习算法。我们的方法首先从一组给定的光度数据中提取大量的光曲线子序列，然后将这些子光束聚类，以找到时间序列中的常见局部模式。这些模式的代表，称为范例，然后被用来转换一个标记集合的光曲线为一个新的表示，然后可以用来训练一个自动分类器。所提出的算法从标记和未标记的光曲线学习特征，克服学习过程仅用标记数据产生的偏差。我们在MACHO和OGLE数据集上测试我们的方法;结果表明，我们实现的分类性能是一样的好，在某些情况下，比使用传统特征获得的性能好，而计算成本明显较低。

##### URL
[https://arxiv.org/abs/1602.08977](https://arxiv.org/abs/1602.08977)

##### PDF
[https://arxiv.org/pdf/1602.08977](https://arxiv.org/pdf/1602.08977)


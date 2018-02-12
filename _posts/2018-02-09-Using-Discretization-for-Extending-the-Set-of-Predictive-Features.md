---
layout: post
title: "Using Discretization for Extending the Set of Predictive Features"
date: 2018-02-09 13:00:44
categories: arXiv_AI
tags: arXiv_AI
author: Avi Rosenfeld, Ron Illuz, Dovid Gottesman, Mark Last
mathjax: true
---

* content
{:toc}

##### Abstract
To date, attribute discretization is typically performed by replacing the original set of continuous features with a transposed set of discrete ones. This paper provides support for a new idea that discretized features should often be used in addition to existing features and as such, datasets should be extended, and not replaced, by discretization. We also claim that discretization algorithms should be developed with the explicit purpose of enriching a non-discretized dataset with discretized values. We present such an algorithm, D-MIAT, a supervised algorithm that discretizes data based on Minority Interesting Attribute Thresholds. D-MIAT only generates new features when strong indications exist for one of the target values needing to be learned and thus is intended to be used in addition to the original data. We present extensive empirical results demonstrating the success of using D-MIAT on $ 28 $ benchmark datasets. We also demonstrate that $ 10 $ other discretization algorithms can also be used to generate features that yield improved performance when used in combination with the original non-discretized data. Our results show that the best predictive performance is attained using a combination of the original dataset with added features from a "standard" supervised discretization algorithm and D-MIAT.

##### Abstract (translated by Google)
迄今为止，属性离散化通常通过用一组转置的替换来替换原始的连续特征来执行。本文提供了一个新的思想，即除了现有的特征之外，还应该经常使用离散化特征，因此数据集应该扩展而不是被离散化替代。我们还声称，离散化算法的开发应明确的目的是用离散值丰富非离散化数据集。我们提出了一种基于少数感兴趣属性阈值的离散化数据的监督算法D-MIAT算法。 D-MIAT仅在需要学习的目标值之一存在强指示时才会生成新的特征，因此除了原始数据之外，还将使用该特征。我们提供了广泛的实证结果，证明了在$ 28 $基准数据集上使用D-MIAT的成功。我们还证明，$ 10 $其他离散化算法也可以用来生成与原始非离散化数据结合使用时可以提高性能的特性。我们的结果表明，使用原始数据集与“标准”有监督离散算法和D-MIAT的附加特征的组合，可以获得最佳的预测性能。

##### URL
[http://arxiv.org/abs/1802.03239](http://arxiv.org/abs/1802.03239)

##### PDF
[http://arxiv.org/pdf/1802.03239](http://arxiv.org/pdf/1802.03239)


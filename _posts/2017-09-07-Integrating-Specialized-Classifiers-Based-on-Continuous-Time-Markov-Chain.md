---
layout: post
title: "Integrating Specialized Classifiers Based on Continuous Time Markov Chain"
date: 2017-09-07 07:56:30
categories: arXiv_CV
tags: arXiv_CV Prediction Recognition
author: Zhizhong Li, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Specialized classifiers, namely those dedicated to a subset of classes, are often adopted in real-world recognition systems. However, integrating such classifiers is nontrivial. Existing methods, e.g. weighted average, usually implicitly assume that all constituents of an ensemble cover the same set of classes. Such methods can produce misleading predictions when used to combine specialized classifiers. This work explores a novel approach. Instead of combining predictions from individual classifiers directly, it first decomposes the predictions into sets of pairwise preferences, treating them as transition channels between classes, and thereon constructs a continuous-time Markov chain, and use the equilibrium distribution of this chain as the final prediction. This way allows us to form a coherent picture over all specialized predictions. On large public datasets, the proposed method obtains considerable improvement compared to mainstream ensemble methods, especially when the classifier coverage is highly unbalanced.

##### Abstract (translated by Google)
专门的分类器，即那些专门用于类的子集的分类器，通常在现实世界的识别系统中被采用。但是，整合这样的分类器是不平凡的。现有的方法，例如加权平均，通常隐含地假定一个集合的所有组成部分都包含相同的一组类。当用于组合专门的分类器时，这样的方法会产生误导性的预测。这项工作探索了一种新颖的方法。它不是直接将个体分类器的预测结合起来，而是先将预测分解成两两偏好集合，把它们作为类之间的转换通道，然后构造一个连续时间的马尔可夫链，并用该链的均衡分布作为最终预测。通过这种方式，我们可以在所有专门的预测中形成连贯的图像。在大型公共数据集上，与主流集成方法相比，所提出的方法获得了相当大的改进，特别是当分类器覆盖高度不平衡时。

##### URL
[https://arxiv.org/abs/1709.02123](https://arxiv.org/abs/1709.02123)

##### PDF
[https://arxiv.org/pdf/1709.02123](https://arxiv.org/pdf/1709.02123)


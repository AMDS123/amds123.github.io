---
layout: post
title: "Meta-Learning for Semi-Supervised Few-Shot Classification"
date: 2018-03-02 01:07:49
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Mengye Ren, Eleni Triantafillou, Sachin Ravi, Jake Snell, Kevin Swersky, Joshua B. Tenenbaum, Hugo Larochelle, Richard S. Zemel
mathjax: true
---

* content
{:toc}

##### Abstract
In few-shot classification, we are interested in learning algorithms that train a classifier from only a handful of labeled examples. Recent progress in few-shot classification has featured meta-learning, in which a parameterized model for a learning algorithm is defined and trained on episodes representing different classification problems, each with a small labeled training set and its corresponding test set. In this work, we advance this few-shot classification paradigm towards a scenario where unlabeled examples are also available within each episode. We consider two situations: one where all unlabeled examples are assumed to belong to the same set of classes as the labeled examples of the episode, as well as the more challenging situation where examples from other distractor classes are also provided. To address this paradigm, we propose novel extensions of Prototypical Networks (Snell et al., 2017) that are augmented with the ability to use unlabeled examples when producing prototypes. These models are trained in an end-to-end way on episodes, to learn to leverage the unlabeled examples successfully. We evaluate these methods on versions of the Omniglot and miniImageNet benchmarks, adapted to this new framework augmented with unlabeled examples. We also propose a new split of ImageNet, consisting of a large set of classes, with a hierarchical structure. Our experiments confirm that our Prototypical Networks can learn to improve their predictions due to unlabeled examples, much like a semi-supervised algorithm would.

##### Abstract (translated by Google)
在少数分类中，我们感兴趣的是仅从少数几个标记的例子中学习用于训练分类器的算法。最近在少量分类中的进展包括元学习，其中一个学习算法的参数化模型被定义和训练在表示不同分类问题的情节中，每个分类问题都有一个小标记训练集和相应的测试集。在这项工作中，我们将这个几分类范例推广到每个情节中还有未标记例子的场景。我们考虑两种情况：一种情况是所有未标记的例子被假定属于与情节的标记例子相同的一组类别，另一种情况下也提供了来自其他类型的事例的更具挑战性的情况。为了解决这个问题，我们提出了原型网络的新型扩展（Snell et al。，2017），这些扩展能够在生产原型时使用未标记的例子。这些模型在剧集上以端对端的方式进行培训，以学习如何成功地利用未标记的示例。我们在Omniglot和miniImageNet基准测试版本上评估这些方法，并对这个新框架进行了修改，增加了未标记的示例。我们还提出了一个新的ImageNet分割，它由一大组类组成，具有分层结构。我们的实验证实，我们的Prototypical Networks可以学习由于未标记的例子而改进他们的预测，就像半监督算法一样。

##### URL
[http://arxiv.org/abs/1803.00676](http://arxiv.org/abs/1803.00676)

##### PDF
[http://arxiv.org/pdf/1803.00676](http://arxiv.org/pdf/1803.00676)


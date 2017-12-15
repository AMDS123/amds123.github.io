---
layout: post
title: "Controlling for Unobserved Confounds in Classification Using Correlational Constraints"
date: 2017-03-05 21:57:25
categories: arXiv_SD
tags: arXiv_SD Classification Prediction Relation
author: Virgile Landeiro, Aron Culotta
mathjax: true
---

* content
{:toc}

##### Abstract
As statistical classifiers become integrated into real-world applications, it is important to consider not only their accuracy but also their robustness to changes in the data distribution. In this paper, we consider the case where there is an unobserved confounding variable $z$ that influences both the features $\mathbf{x}$ and the class variable $y$. When the influence of $z$ changes from training to testing data, we find that the classifier accuracy can degrade rapidly. In our approach, we assume that we can predict the value of $z$ at training time with some error. The prediction for $z$ is then fed to Pearl's back-door adjustment to build our model. Because of the attenuation bias caused by measurement error in $z$, standard approaches to controlling for $z$ are ineffective. In response, we propose a method to properly control for the influence of $z$ by first estimating its relationship with the class variable $y$, then updating predictions for $z$ to match that estimated relationship. By adjusting the influence of $z$, we show that we can build a model that exceeds competing baselines on accuracy as well as on robustness over a range of confounding relationships.

##### Abstract (translated by Google)
随着统计分类器被集成到实际应用中，不仅要考虑其准确性，还要考虑其对数据分布变化的稳健性。在这篇论文中，我们考虑了一个不可观测的混淆变量$ z $，这个变量影响了特征$ \ mathbf {x} $和类变量$ y $。当$ z $的影响从训练变为测试数据时，我们发现分类器的准确性可能会迅速降低。在我们的方法中，我们假设我们可以在训练时预测$ z $的值，但有一些错误。然后预测$ z $，然后反馈给Pearl的后门调整来建立我们的模型。由于$ z $的测量误差造成的衰减偏差，控制$ z $的标准方法是无效的。作为回应，我们提出了一个方法来正确控制$ z $的影响，首先估计它​​与类别变量$ y $的关系，然后更新$ z $的预测以匹配估计的关系。通过调整$ z $的影响，我们可以证明，我们可以建立一个超过竞争基准的准确性模型，以及一系列混杂关系的稳健性。

##### URL
[https://arxiv.org/abs/1703.01671](https://arxiv.org/abs/1703.01671)

##### PDF
[https://arxiv.org/pdf/1703.01671](https://arxiv.org/pdf/1703.01671)


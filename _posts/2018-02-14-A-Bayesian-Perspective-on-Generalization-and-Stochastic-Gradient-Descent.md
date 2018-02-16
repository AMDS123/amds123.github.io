---
layout: post
title: "A Bayesian Perspective on Generalization and Stochastic Gradient Descent"
date: 2018-02-14 19:42:20
categories: arXiv_AI
tags: arXiv_AI Prediction Gradient_Descent
author: Samuel L. Smith, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
We consider two questions at the heart of machine learning; how can we predict if a minimum will generalize to the test set, and why does stochastic gradient descent find minima that generalize well? Our work responds to Zhang et al. (2016), who showed deep neural networks can easily memorize randomly labeled training data, despite generalizing well on real labels of the same inputs. We show that the same phenomenon occurs in small linear models. These observations are explained by the Bayesian evidence, which penalizes sharp minima but is invariant to model parameterization. We also demonstrate that, when one holds the learning rate fixed, there is an optimum batch size which maximizes the test set accuracy. We propose that the noise introduced by small mini-batches drives the parameters towards minima whose evidence is large. Interpreting stochastic gradient descent as a stochastic differential equation, we identify the "noise scale" $g = \epsilon (\frac{N}{B} - 1) \approx \epsilon N/B$, where $\epsilon$ is the learning rate, $N$ the training set size and $B$ the batch size. Consequently the optimum batch size is proportional to both the learning rate and the size of the training set, $B_{opt} \propto \epsilon N$. We verify these predictions empirically.

##### Abstract (translated by Google)
我们认为机器学习的核心有两个问题。我们如何预测最小值是否会推广到测试集，为什么随机梯度下降发现最小值能够很好地推广？我们的工作回应张等人。 （2016年），尽管在相同输入的实际标签上进行了很好的概括，但展示深度神经网络的人可以很容易地记住随机标记的训练数据。我们证明在小线性模型中会出现相同的现象。这些观察结果由贝叶斯证据来解释，该证据惩罚尖锐的最小值，但对模型参数化不变。我们还证明，当保持固定的学习速率时，有一个最佳的批量大小可以最大化测试集的准确性。我们建议由小型小批量引入的噪音驱动参数朝​​向证据很大的最小值。将随机梯度下降解释为一个随机微分方程，我们确定了“噪声尺度”，其中$ \ epsilon $是学习率，$ N $训练集大小和$ B $批量大小。因此，最佳批量大小与训练集的学习率和大小成正比，即$ B_ {opt} \ propto \ N $。我们凭经验验证这些预测。

##### URL
[http://arxiv.org/abs/1710.06451](http://arxiv.org/abs/1710.06451)

##### PDF
[http://arxiv.org/pdf/1710.06451](http://arxiv.org/pdf/1710.06451)


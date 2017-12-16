---
layout: post
title: "Residual Parameter Transfer for Deep Domain Adaptation"
date: 2017-11-21 11:03:55
categories: arXiv_CV
tags: arXiv_CV
author: Artem Rozantsev, Mathieu Salzmann, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of Deep Domain Adaptation is to make it possible to use Deep Nets trained in one domain where there is enough annotated training data in another where there is little or none. Most current approaches have focused on learning feature representations that are invariant to the changes that occur when going from one domain to the other, which means using the same network parameters in both domains. While some recent algorithms explicitly model the changes by adapting the network parameters, they either severely restrict the possible domain changes, or significantly increase the number of model parameters. By contrast, we introduce a network architecture that includes auxiliary residual networks, which we train to predict the parameters in the domain with little annotated data from those in the other one. This architecture enables us to flexibly preserve the similarities between domains where they exist and model the differences when necessary. We demonstrate that our approach yields higher accuracy than state-of-the-art methods without undue complexity.

##### Abstract (translated by Google)
Deep Domain Adaptation的目标是使在一个域中使用深网训练成为可能，在这个域中有足够的注释训练数据，而在另一个域中很少或没有。大多数当前的方法已经集中在学习对于从一个域到另一个域时发生的变化不变的特征表示，这意味着在两个域中使用相同的网络参数。尽管一些最近的算法通过调整网络参数来明确地对变化进行建模，但是它们要么严格限制可能的域变化，要么显着增加模型参数的数量。相比之下，我们引入了一个包含辅助残余网络的网络体系结构，我们通过训练来预测域中的参数，而另一个网络中的参数却很少有注释。这种架构使我们能够灵活地保存它们所在域之间的相似性，并在必要时对差异进行建模。我们证明，我们的方法比没有过分复杂性的最先进的方法具有更高的准确性。

##### URL
[https://arxiv.org/abs/1711.07714](https://arxiv.org/abs/1711.07714)

##### PDF
[https://arxiv.org/pdf/1711.07714](https://arxiv.org/pdf/1711.07714)


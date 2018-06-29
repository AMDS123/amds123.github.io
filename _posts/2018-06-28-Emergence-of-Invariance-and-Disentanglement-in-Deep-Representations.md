---
layout: post
title: "Emergence of Invariance and Disentanglement in Deep Representations"
date: 2018-06-28 17:50:54
categories: arXiv_AI
tags: arXiv_AI Relation
author: Alessandro Achille, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
Using established principles from Statistics and Information Theory, we show that invariance to nuisance factors in a deep neural network is equivalent to information minimality of the learned representation, and that stacking layers and injecting noise during training naturally bias the network towards learning invariant representations. We then decompose the cross-entropy loss used during training and highlight the presence of an inherent overfitting term. We propose regularizing the loss by bounding such a term in two equivalent ways: One with a Kullbach-Leibler term, which relates to a PAC-Bayes perspective; the other using the information in the weights as a measure of complexity of a learned model, yielding a novel Information Bottleneck for the weights. Finally, we show that invariance and independence of the components of the representation learned by the network are bounded above and below by the information in the weights, and therefore are implicitly optimized during training. The theory enables us to quantify and predict sharp phase transitions between underfitting and overfitting of random labels when using our regularized loss, which we verify in experiments, and sheds light on the relation between the geometry of the loss function, invariance properties of the learned representation, and generalization error.

##### Abstract (translated by Google)
利用统计和信息理论中的既定原则，我们证明深度神经网络中的滋扰因子的不变性等价于学习表示的信息极小化，并且在训练过程中叠加层和注入噪声自然地使网络偏向于学习不变表示。然后，我们分解训练过程中使用的交叉熵损失，并强调一个固有的过度拟合项的存在。我们提出通过以两种等同方式界定这样一个术语来规范损失：一个与Kullbach-Leibler术语有关，它与PAC-Bayes观点有关;另一个使用权重中的信息作为学习模型的复杂度的量度，从而产生新的权重信息瓶颈。最后，我们证明网络学习表示的组成部分的不变性和独立性受权重信息的限制，因此在训练过程中被隐含地优化。该理论使我们能够量化和预测在使用我们的正则化损失时，随机标签的欠拟合和过拟合之间的急剧相变，我们在实验中验证了这一点，并揭示了损失函数的几何关系，学习表示的不变性和泛化错误。

##### URL
[http://arxiv.org/abs/1706.01350](http://arxiv.org/abs/1706.01350)

##### PDF
[http://arxiv.org/pdf/1706.01350](http://arxiv.org/pdf/1706.01350)


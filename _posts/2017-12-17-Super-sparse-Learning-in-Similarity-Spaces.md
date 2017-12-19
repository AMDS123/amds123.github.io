---
layout: post
title: "Super-sparse Learning in Similarity Spaces"
date: 2017-12-17 15:59:38
categories: arXiv_CV
tags: arXiv_CV Sparse Classification
author: Ambra Demontis, Marco Melis, Battista Biggio, Giorgio Fumera, Fabio Roli
mathjax: true
---

* content
{:toc}

##### Abstract
In several applications, input samples are more naturally represented in terms of similarities between each other, rather than in terms of feature vectors. In these settings, machine-learning algorithms can become very computationally demanding, as they may require matching the test samples against a very large set of reference prototypes. To mitigate this issue, different approaches have been developed to reduce the number of required reference prototypes. Current reduction approaches select a small subset of representative prototypes in the space induced by the similarity measure, and then separately train the classification function on the reduced subset. However, decoupling these two steps may not allow reducing the number of prototypes effectively without compromising accuracy. We overcome this limitation by jointly learning the classification function along with an optimal set of virtual prototypes, whose number can be either fixed a priori or optimized according to application-specific criteria. Creating a super-sparse set of virtual prototypes provides much sparser solutions, drastically reducing complexity at test time, at the expense of a slightly increased complexity during training. A much smaller set of prototypes also results in easier-to-interpret decisions. We empirically show that our approach can reduce up to ten times the complexity of Support Vector Machines, LASSO and ridge regression at test time, without almost affecting their classification accuracy.

##### Abstract (translated by Google)
在一些应用中，输入样本更加自然地表示为相互之间的相似性，而不是特征向量。在这些设置中，机器学习算法可能变得非常计算量大，因为它们可能需要将测试样本与大量的参考原型进行匹配。为了缓解这个问题，已经开发了不同的方法来减少所需参考原型的数量。目前的减少方法是在相似性度量所引入的空间中选择代表性原型的一个小子集，然后在减少的子集上分别训练分类函数。然而，解耦这两个步骤可能不会有效地减少原型的数量，而不会影响准确性。我们通过联合学习分类函数以及最佳的一组虚拟原型来克服这个限制，其中虚拟原型的数量可以是先验固定的，也可以是根据应用特定的标准进行优化的。创建一个超级稀疏的虚拟原型集提供了更为稀疏的解决方案，在测试时大幅度降低了复杂性，代价是培训期间的复杂度略有增加。一套小得多的原型也会导致更易于解释的决定。我们实验证明，我们的方法在测试时可以降低十倍于支持向量机，LASSO和岭回归的复杂度，而几乎不影响它们的分类准确性。

##### URL
[http://arxiv.org/abs/1712.06131](http://arxiv.org/abs/1712.06131)

##### PDF
[http://arxiv.org/pdf/1712.06131](http://arxiv.org/pdf/1712.06131)


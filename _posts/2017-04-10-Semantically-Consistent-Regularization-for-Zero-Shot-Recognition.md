---
layout: post
title: "Semantically Consistent Regularization for Zero-Shot Recognition"
date: 2017-04-10 19:59:33
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge CNN Classification Relation Recognition
author: Pedro Morgado, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
The role of semantics in zero-shot learning is considered. The effectiveness of previous approaches is analyzed according to the form of supervision provided. While some learn semantics independently, others only supervise the semantic subspace explained by training classes. Thus, the former is able to constrain the whole space but lacks the ability to model semantic correlations. The latter addresses this issue but leaves part of the semantic space unsupervised. This complementarity is exploited in a new convolutional neural network (CNN) framework, which proposes the use of semantics as constraints for recognition.Although a CNN trained for classification has no transfer ability, this can be encouraged by learning an hidden semantic layer together with a semantic code for classification. Two forms of semantic constraints are then introduced. The first is a loss-based regularizer that introduces a generalization constraint on each semantic predictor. The second is a codeword regularizer that favors semantic-to-class mappings consistent with prior semantic knowledge while allowing these to be learned from data. Significant improvements over the state-of-the-art are achieved on several datasets.

##### Abstract (translated by Google)
考虑了零点学习中语义的作用。根据所提供的监督形式分析了以往方法的有效性。有些人独立学习语义，而有些则只监督训练班所解释的语义子空间。因此，前者能够约束整个空间，但缺乏对语义相关性建模的能力。后者解决了这个问题，但留下了部分语义空间无人监督。这种互补性是在一个新的卷积神经网络（CNN）框架中被利用的，该框架提出了使用语义作为识别的约束。虽然被训练用于分类的CNN没有传输能力，但是可以通过学习隐藏的语义层用于分类的语义代码。然后引入两种形式的语义约束。第一种是基于损失的正规化器，它在每个语义预测器上引入一个泛化约束。第二个是码字正规化器，它支持与先前语义知识相一致的语义到类映射，同时允许从数据中学习这些映射。在一些数据集上实现了最先进的显着改进。

##### URL
[https://arxiv.org/abs/1704.03039](https://arxiv.org/abs/1704.03039)

##### PDF
[https://arxiv.org/pdf/1704.03039](https://arxiv.org/pdf/1704.03039)


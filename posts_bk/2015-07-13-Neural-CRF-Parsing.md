---
layout: post
title: "Neural CRF Parsing"
date: 2015-07-13 22:23:51
categories: arXiv_CL
tags: arXiv_CL Sparse Inference
author: Greg Durrett, Dan Klein
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a parsing model that combines the exact dynamic programming of CRF parsing with the rich nonlinear featurization of neural net approaches. Our model is structurally a CRF that factors over anchored rule productions, but instead of linear potential functions based on sparse features, we use nonlinear potentials computed via a feedforward neural network. Because potentials are still local to anchored rules, structured inference (CKY) is unchanged from the sparse case. Computing gradients during learning involves backpropagating an error signal formed from standard CRF sufficient statistics (expected rule counts). Using only dense features, our neural CRF already exceeds a strong baseline CRF model (Hall et al., 2014). In combination with sparse features, our system achieves 91.1 F1 on section 23 of the Penn Treebank, and more generally outperforms the best prior single parser results on a range of languages.

##### Abstract (translated by Google)
本文描述了一个解析模型，将CRF解析的精确动态规划与神经网络方法丰富的非线性特征相结合。我们的模型在结构上是CRF，它是锚定规则生成的因素，而不是基于稀疏特征的线性势函数，我们使用通过前馈神经网络计算的非线性势。因为潜在的规则仍然局限于锚定规则，所以结构化推理（CKY）与稀疏规则无关。在学习期间计算梯度涉及反向传播由标准CRF形成的足够统计（预期规则计数）的错误信号。只使用密集的特征，我们的神经CRF已经超过了一个强大的基线CRF模型（Hall et al。，2014）。结合稀疏特征，我们的系统在Penn Treebank的第23部分达到了91.1 F1，并且在一系列语言中更一般地胜过先前最好的单个解析器结果。

##### URL
[https://arxiv.org/abs/1507.03641](https://arxiv.org/abs/1507.03641)

##### PDF
[https://arxiv.org/pdf/1507.03641](https://arxiv.org/pdf/1507.03641)


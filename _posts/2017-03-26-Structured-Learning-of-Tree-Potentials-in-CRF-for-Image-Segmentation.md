---
layout: post
title: "Structured Learning of Tree Potentials in CRF for Image Segmentation"
date: 2017-03-26 04:15:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Relation
author: Fayao Liu, Guosheng Lin, Ruizhi Qiao, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new approach to image segmentation, which exploits the advantages of both conditional random fields (CRFs) and decision trees. In the literature, the potential functions of CRFs are mostly defined as a linear combination of some pre-defined parametric models, and then methods like structured support vector machines (SSVMs) are applied to learn those linear coefficients. We instead formulate the unary and pairwise potentials as nonparametric forests---ensembles of decision trees, and learn the ensemble parameters and the trees in a unified optimization problem within the large-margin framework. In this fashion, we easily achieve nonlinear learning of potential functions on both unary and pairwise terms in CRFs. Moreover, we learn class-wise decision trees for each object that appears in the image. Due to the rich structure and flexibility of decision trees, our approach is powerful in modelling complex data likelihoods and label relationships. The resulting optimization problem is very challenging because it can have exponentially many variables and constraints. We show that this challenging optimization can be efficiently solved by combining a modified column generation and cutting-planes techniques. Experimental results on both binary (Graz-02, Weizmann horse, Oxford flower) and multi-class (MSRC-21, PASCAL VOC 2012) segmentation datasets demonstrate the power of the learned nonlinear nonparametric potentials.

##### Abstract (translated by Google)
我们提出了一种新的图像分割方法，它利用了条件随机场（CRF）和决策树的优点。在文献中，CRF的潜在功能大多定义为一些预定义的参数模型的线性组合，然后使用结构化支持向量机（SSVM）等方法来学习这些线性系数。我们把一元和二元的潜能作为非参数森林---决策树集合，在大范围的框架内学习集合参数和树在一个统一的优化问题中。以这种方式，我们很容易实现CRF中一元和二元项潜在函数的非线性学习。此外，我们学习图像中出现的每个对象的分类决策树。由于决策树具有丰富的结构和灵活性，我们的方法在建模复杂的数据可能性和标签关系方面非常有效。由此产生的优化问题非常具有挑战性，因为它可能具有指数级的许多变量和约束条件。我们表明，这种具有挑战性的优化可以通过结合改进的柱生成和切割平面技术来有效地解决。在二元（Graz-02，Weizmann马，牛津花）和多类（MSRC-21，PASCAL VOC 2012）分割数据集上的实验结果证明了学习的非线性非参数电位的能力。

##### URL
[https://arxiv.org/abs/1703.08764](https://arxiv.org/abs/1703.08764)

##### PDF
[https://arxiv.org/pdf/1703.08764](https://arxiv.org/pdf/1703.08764)


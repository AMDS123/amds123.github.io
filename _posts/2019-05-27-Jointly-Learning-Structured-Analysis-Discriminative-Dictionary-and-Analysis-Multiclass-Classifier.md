---
layout: post
title: "Jointly Learning Structured Analysis Discriminative Dictionary and Analysis Multiclass Classifier"
date: 2019-05-27 23:52:46
categories: arXiv_CV
tags: arXiv_CV Sparse Classification
author: Zhao Zhang, Weiming Jiang, Jie Qin, Li Zhang, Fanzhang Li, Min Zhang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an analysis mechanism based structured Analysis Discriminative Dictionary Learning (ADDL) framework. ADDL seamlessly integrates the analysis discriminative dictionary learning, analysis representation and analysis classifier training into a unified model. The applied analysis mechanism can make sure that the learnt dictionaries, representations and linear classifiers over different classes are independent and discriminating as much as possible. The dictionary is obtained by minimizing a reconstruction error and an analytical incoherence promoting term that encourages the sub-dictionaries associated with different classes to be independent. To obtain the representation coefficients, ADDL imposes a sparse l2,1-norm constraint on the coding coefficients instead of using l0 or l1-norm, since the l0 or l1-norm constraint applied in most existing DL criteria makes the training phase time consuming. The codes-extraction projection that bridges data with the sparse codes by extracting special features from the given samples is calculated via minimizing a sparse codes approximation term. Then we compute a linear classifier based on the approximated sparse codes by an analysis mechanism to simultaneously consider the classification and representation powers. Thus, the classification approach of our model is very efficient, because it can avoid the extra time-consuming sparse reconstruction process with trained dictionary for each new test data as most existing DL algorithms. Simulations on real image databases demonstrate that our ADDL model can obtain superior performance over other state-of-the-arts.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11543](https://arxiv.org/abs/1905.11543)

##### PDF
[https://arxiv.org/pdf/1905.11543](https://arxiv.org/pdf/1905.11543)


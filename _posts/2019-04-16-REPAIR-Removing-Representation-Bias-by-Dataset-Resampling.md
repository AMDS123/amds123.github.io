---
layout: post
title: "REPAIR: Removing Representation Bias by Dataset Resampling"
date: 2019-04-16 18:35:40
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Optimization Classification Gradient_Descent Recognition
author: Yi Li, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
Modern machine learning datasets can have biases for certain representations that are leveraged by algorithms to achieve high performance without learning to solve the underlying task. This problem is referred to as "representation bias". The question of how to reduce the representation biases of a dataset is investigated and a new dataset REPresentAtion bIas Removal (REPAIR) procedure is proposed. This formulates bias minimization as an optimization problem, seeking a weight distribution that penalizes examples easy for a classifier built on a given feature representation. Bias reduction is then equated to maximizing the ratio between the classification loss on the reweighted dataset and the uncertainty of the ground-truth class labels. This is a minimax problem that REPAIR solves by alternatingly updating classifier parameters and dataset resampling weights, using stochastic gradient descent. An experimental set-up is also introduced to measure the bias of any dataset for a given representation, and the impact of this bias on the performance of recognition models. Experiments with synthetic and action recognition data show that dataset REPAIR can significantly reduce representation bias, and lead to improved generalization of models trained on REPAIRed datasets. The tools used for characterizing representation bias, and the proposed dataset REPAIR algorithm, are available at https://github.com/JerryYLi/Dataset-REPAIR/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07911](http://arxiv.org/abs/1904.07911)

##### PDF
[http://arxiv.org/pdf/1904.07911](http://arxiv.org/pdf/1904.07911)


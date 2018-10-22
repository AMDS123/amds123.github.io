---
layout: post
title: "Zero and Few Shot Learning with Semantic Feature Synthesis and Competitive Learning"
date: 2018-10-19 01:52:03
categories: arXiv_CV
tags: arXiv_CV
author: Zhiwu Lu, Jiechao Guan, Aoxue Li, Tao Xiang, An Zhao, Ji-Rong Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) is made possible by learning a projection function between a feature space and a semantic space (e.g.,~an attribute space). Key to ZSL is thus to learn a projection that is robust against the often large domain gap between the seen and unseen class domains. In this work, this is achieved by unseen class data synthesis and robust projection function learning. Specifically, a novel semantic data synthesis strategy is proposed, by which semantic class prototypes (e.g., attribute vectors) are used to simply perturb seen class data for generating unseen class ones. As in any data synthesis/hallucination approach, there are ambiguities and uncertainties on how well the synthesised data can capture the targeted unseen class data distribution. To cope with this, the second contribution of this work is a novel projection learning model termed competitive bidirectional projection learning (BPL) designed to best utilise the ambiguous synthesised data. Specifically, we assume that each synthesised data point can belong to any unseen class; and the most likely two class candidates are exploited to learn a robust projection function in a competitive fashion. As a third contribution, we show that the proposed ZSL model can be easily extended to few-shot learning (FSL) by again exploiting semantic (class prototype guided) feature synthesis and competitive BPL. Extensive experiments show that our model achieves the state-of-the-art results on both problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08332](http://arxiv.org/abs/1810.08332)

##### PDF
[http://arxiv.org/pdf/1810.08332](http://arxiv.org/pdf/1810.08332)


---
layout: post
title: "Visualizing and Understanding the Effectiveness of BERT"
date: 2019-08-15 16:11:45
categories: arXiv_CL
tags: arXiv_CL Face Optimization Language_Model
author: Yaru Hao, Li Dong, Furu Wei, Ke Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Language model pre-training, such as BERT, has achieved remarkable results in many NLP tasks. However, it is unclear why the pre-training-then-fine-tuning paradigm can improve performance and generalization capability across different tasks. In this paper, we propose to visualize loss landscapes and optimization trajectories of fine-tuning BERT on specific datasets. First, we find that pre-training reaches a good initial point across downstream tasks, which leads to wider optima and easier optimization compared with training from scratch. We also demonstrate that the fine-tuning procedure is robust to overfitting, even though BERT is highly over-parameterized for downstream tasks. Second, the visualization results indicate that fine-tuning BERT tends to generalize better because of the flat and wide optima, and the consistency between the training loss surface and the generalization error surface. Third, the lower layers of BERT are more invariant during fine-tuning, which suggests that the layers that are close to input learn more transferable representations of language.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05620](http://arxiv.org/abs/1908.05620)

##### PDF
[http://arxiv.org/pdf/1908.05620](http://arxiv.org/pdf/1908.05620)


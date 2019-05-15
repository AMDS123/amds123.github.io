---
layout: post
title: "The Lower The Simpler: Simplifying Hierarchical Recurrent Models"
date: 2019-05-14 16:14:36
categories: arXiv_AI
tags: arXiv_AI
author: Chao Wang, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
To improve the training efficiency of hierarchical recurrent models without compromising their performance, we propose a strategy named as `the lower the simpler', which is to simplify the baseline models by making the lower layers simpler than the upper layers. We carry out this strategy to simplify two typical hierarchical recurrent models, namely Hierarchical Recurrent Encoder-Decoder (HRED) and R-NET, whose basic building block is GRU. Specifically, we propose Scalar Gated Unit (SGU), which is a simplified variant of GRU, and use it to replace the GRUs at the middle layers of HRED and R-NET. Besides, we also use Fixed-size Ordinally-Forgetting Encoding (FOFE), which is an efficient encoding method without any trainable parameter, to replace the GRUs at the bottom layers of HRED and R-NET. The experimental results show that the simplified HRED and the simplified R-NET contain significantly less trainable parameters, consume significantly less training time, and achieve slightly better performance than their baseline models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.02790](http://arxiv.org/abs/1809.02790)

##### PDF
[http://arxiv.org/pdf/1809.02790](http://arxiv.org/pdf/1809.02790)


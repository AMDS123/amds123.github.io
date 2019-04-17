---
layout: post
title: "Multi-Head Multi-Layer Attention to Deep Language Representations for Grammatical Error Detection"
date: 2019-04-15 21:36:21
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Detection
author: Masahiro Kaneko, Mamoru Komachi
mathjax: true
---

* content
{:toc}

##### Abstract
It is known that a deep neural network model pre-trained with large-scale data greatly improves the accuracy of various tasks, especially when there are resource constraints. However, the information needed to solve a given task can vary, and simply using the output of the final layer is not necessarily sufficient. Moreover, to our knowledge, exploiting large language representation models to detect grammatical errors has not yet been studied. In this work, we investigate the effect of utilizing information not only from the final layer but also from intermediate layers of a pre-trained language representation model to detect grammatical errors. We propose a multi-head multi-layer attention model that determines the appropriate layers in Bidirectional Encoder Representation from Transformers (BERT). The proposed method achieved the best scores on three datasets for grammatical error detection tasks, outperforming the current state-of-the-art method by 6.0 points on FCE, 8.2 points on CoNLL14, and 12.2 points on JFLEG in terms of F_0.5. We also demonstrate that by using multi-head multi-layer attention, our model can exploit a broader range of information for each token in a sentence than a model that uses only the final layer's information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07334](http://arxiv.org/abs/1904.07334)

##### PDF
[http://arxiv.org/pdf/1904.07334](http://arxiv.org/pdf/1904.07334)


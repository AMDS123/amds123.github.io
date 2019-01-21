---
layout: post
title: "Improving Sequence-to-Sequence Learning via Optimal Transport"
date: 2019-01-18 14:52:34
categories: arXiv_CL
tags: arXiv_CL Image_Caption Summarization Caption
author: Liqun Chen, Yizhe Zhang, Ruiyi Zhang, Chenyang Tao, Zhe Gan, Haichao Zhang, Bai Li, Dinghan Shen, Changyou Chen, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models are commonly trained via maximum likelihood estimation (MLE). However, standard MLE training considers a word-level objective, predicting the next word given the previous ground-truth partial sentence. This procedure focuses on modeling local syntactic patterns, and may fail to capture long-range semantic structure. We present a novel solution to alleviate these issues. Our approach imposes global sequence-level guidance via new supervision based on optimal transport, enabling the overall characterization and preservation of semantic features. We further show that this method can be understood as a Wasserstein gradient flow trying to match our model to the ground truth sequence distribution. Extensive experiments are conducted to validate the utility of the proposed approach, showing consistent improvements over a wide variety of NLP tasks, including machine translation, abstractive text summarization, and image captioning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06283](http://arxiv.org/abs/1901.06283)

##### PDF
[http://arxiv.org/pdf/1901.06283](http://arxiv.org/pdf/1901.06283)


---
layout: post
title: "Joint Training for Neural Machine Translation Models with Monolingual Data"
date: 2018-03-01 13:14:35
categories: arXiv_CL
tags: arXiv_CL Optimization NMT
author: Zhirui Zhang, Shujie Liu, Mu Li, Ming Zhou, Enhong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Monolingual data have been demonstrated to be helpful in improving translation quality of both statistical machine translation (SMT) systems and neural machine translation (NMT) systems, especially in resource-poor or domain adaptation tasks where parallel data are not rich enough. In this paper, we propose a novel approach to better leveraging monolingual data for neural machine translation by jointly learning source-to-target and target-to-source NMT models for a language pair with a joint EM optimization method. The training process starts with two initial NMT models pre-trained on parallel data for each direction, and these two models are iteratively updated by incrementally decreasing translation losses on training data. In each iteration step, both NMT models are first used to translate monolingual data from one language to the other, forming pseudo-training data of the other NMT model. Then two new NMT models are learnt from parallel data together with the pseudo training data. Both NMT models are expected to be improved and better pseudo-training data can be generated in next step. Experiment results on Chinese-English and English-German translation tasks show that our approach can simultaneously improve translation quality of source-to-target and target-to-source models, significantly outperforming strong baseline systems which are enhanced with monolingual data for model training including back-translation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.00353](https://arxiv.org/abs/1803.00353)

##### PDF
[https://arxiv.org/pdf/1803.00353](https://arxiv.org/pdf/1803.00353)


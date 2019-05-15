---
layout: post
title: "Effective Cross-lingual Transfer of Neural Machine Translation Models without Shared Vocabularies"
date: 2019-05-14 09:13:23
categories: arXiv_CL
tags: arXiv_CL Embedding Transfer_Learning NMT
author: Yunsu Kim, Yingbo Gao, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer learning or multilingual model is essential for low-resource neural machine translation (NMT), but the applicability is limited to cognate languages by sharing their vocabularies. This paper shows effective techniques to transfer a pre-trained NMT model to a new, unrelated language without shared vocabularies. We relieve the vocabulary mismatch by using cross-lingual word embedding, train a more language-agnostic encoder by injecting artificial noises, and generate synthetic data easily from the pre-training data without back-translation. Our methods do not require restructuring the vocabulary or retraining the model. We improve plain NMT transfer by up to +5.1% BLEU in five low-resource translation tasks, outperforming multilingual joint training by a large margin. We also provide extensive ablation studies on pre-trained embedding, synthetic data, vocabulary size, and parameter freezing for a better understanding of NMT transfer.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05475](https://arxiv.org/abs/1905.05475)

##### PDF
[https://arxiv.org/pdf/1905.05475](https://arxiv.org/pdf/1905.05475)


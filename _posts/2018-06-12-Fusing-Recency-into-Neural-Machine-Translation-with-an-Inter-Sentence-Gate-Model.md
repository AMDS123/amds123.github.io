---
layout: post
title: "Fusing Recency into Neural Machine Translation with an Inter-Sentence Gate Model"
date: 2018-06-12 12:37:20
categories: arXiv_CL
tags: arXiv_CL NMT
author: Shaohui Kuang, Deyi Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) systems are usually trained on a large amount of bilingual sentence pairs and translate one sentence at a time, ignoring inter-sentence information. This may make the translation of a sentence ambiguous or even inconsistent with the translations of neighboring sentences. In order to handle this issue, we propose an inter-sentence gate model that uses the same encoder to encode two adjacent sentences and controls the amount of information flowing from the preceding sentence to the translation of the current sentence with an inter-sentence gate. In this way, our proposed model can capture the connection between sentences and fuse recency from neighboring sentences into neural machine translation. On several NIST Chinese-English translation tasks, our experiments demonstrate that the proposed inter-sentence gate model achieves substantial improvements over the baseline.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.04466](https://arxiv.org/abs/1806.04466)

##### PDF
[https://arxiv.org/pdf/1806.04466](https://arxiv.org/pdf/1806.04466)


---
layout: post
title: "Neural Machine Translation Model with a Large Vocabulary Selected by Branching Entropy"
date: 2017-09-06 04:06:07
categories: arXiv_CL
tags: arXiv_CL Knowledge NMT
author: Zi Long, Ryuichiro Kimura, Takehito Utsuro, Tomoharu Mitsuhashi, Mikio Yamamoto
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT), a new approach to machine translation, has achieved promising results comparable to those of traditional approaches such as statistical machine translation (SMT). Despite its recent success, NMT cannot handle a larger vocabulary because the training complexity and decoding complexity proportionally increase with the number of target words. This problem becomes even more serious when translating patent documents, which contain many technical terms that are observed infrequently. In this paper, we propose to select phrases that contain out-of-vocabulary words using the statistical approach of branching entropy. This allows the proposed NMT system to be applied to a translation task of any language pair without any language-specific knowledge about technical term identification. The selected phrases are then replaced with tokens during training and post-translated by the phrase translation table of SMT. Evaluation on Japanese-to-Chinese, Chinese-to-Japanese, Japanese-to-English and English-to-Japanese patent sentence translation proved the effectiveness of phrases selected with branching entropy, where the proposed NMT model achieves a substantial improvement over a baseline NMT model without our proposed technique. Moreover, the number of translation errors of under-translation by the baseline NMT model without our proposed technique reduces to around half by the proposed NMT model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.04520](https://arxiv.org/abs/1704.04520)

##### PDF
[https://arxiv.org/pdf/1704.04520](https://arxiv.org/pdf/1704.04520)


---
layout: post
title: "English-Japanese Neural Machine Translation with Encoder-Decoder-Reconstructor"
date: 2017-06-26 00:55:04
categories: arXiv_CL
tags: arXiv_CL NMT
author: Yukio Matsumura, Takayuki Sato, Mamoru Komachi
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has recently become popular in the field of machine translation. However, NMT suffers from the problem of repeating or missing words in the translation. To address this problem, Tu et al. (2017) proposed an encoder-decoder-reconstructor framework for NMT using back-translation. In this method, they selected the best forward translation model in the same manner as Bahdanau et al. (2015), and then trained a bi-directional translation model as fine-tuning. Their experiments show that it offers significant improvement in BLEU scores in Chinese-English translation task. We confirm that our re-implementation also shows the same tendency and alleviates the problem of repeating and missing words in the translation on a English-Japanese task too. In addition, we evaluate the effectiveness of pre-training by comparing it with a jointly-trained model of forward translation and back-translation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.08198](https://arxiv.org/abs/1706.08198)

##### PDF
[https://arxiv.org/pdf/1706.08198](https://arxiv.org/pdf/1706.08198)


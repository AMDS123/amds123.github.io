---
layout: post
title: "CGMH: Constrained Sentence Generation by Metropolis-Hastings Sampling"
date: 2018-11-14 15:46:57
categories: arXiv_CL
tags: arXiv_CL Inference RNN
author: Ning Miao, Hao Zhou, Lili Mou, Rui Yan, Lei Li
mathjax: true
---

* content
{:toc}

##### Abstract
In real-world applications of natural language generation, there are often constraints on the target sentences in addition to fluency and naturalness requirements. Existing language generation techniques are usually based on recurrent neural networks (RNNs). However, it is non-trivial to impose constraints on RNNs while maintaining generation quality, since RNNs generate sentences sequentially (or with beam search) from the first word to the last. In this paper, we propose CGMH, a novel approach using Metropolis-Hastings sampling for constrained sentence generation. CGMH allows complicated constraints such as the occurrence of multiple keywords in the target sentences, which cannot be handled in traditional RNN-based approaches. Moreover, CGMH works in the inference stage, and does not require parallel corpora for training. We evaluate our method on a variety of tasks, including keywords-to-sentence generation, unsupervised sentence paraphrasing, and unsupervised sentence error correction. CGMH achieves high performance compared with previous supervised methods for sentence generation. Our code is released at https://github.com/NingMiao/CGMH

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10996](http://arxiv.org/abs/1811.10996)

##### PDF
[http://arxiv.org/pdf/1811.10996](http://arxiv.org/pdf/1811.10996)


---
layout: post
title: "Listen, Attend, Spell and Adapt: Speaker Adapted Sequence-to-Sequence ASR"
date: 2019-07-08 15:09:40
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Felix Weninger, Jes&#xfa;s Andr&#xe9;s-Ferrer, Xinwei Li, Puming Zhan
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence (seq2seq) based ASR systems have shown state-of-the-art performances while having clear advantages in terms of simplicity. However, comparisons are mostly done on speaker independent (SI) ASR systems, though speaker adapted conventional systems are commonly used in practice for improving robustness to speaker and environment variations. In this paper, we apply speaker adaptation to seq2seq models with the goal of matching the performance of conventional ASR adaptation. Specifically, we investigate Kullback-Leibler divergence (KLD) as well as Linear Hidden Network (LHN) based adaptation for seq2seq ASR, using different amounts (up to 20 hours) of adaptation data per speaker. Our SI models are trained on large amounts of dictation data and achieve state-of-the-art results. We obtained 25% relative word error rate (WER) improvement with KLD adaptation of the seq2seq model vs. 18.7% gain from acoustic model adaptation in the conventional system. We also show that the WER of the seq2seq model decreases log-linearly with the amount of adaptation data. Finally, we analyze adaptation based on the minimum WER criterion and adapting the language model (LM) for score fusion with the speaker adapted seq2seq model, which result in further improvements of the seq2seq system performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04916](http://arxiv.org/abs/1907.04916)

##### PDF
[http://arxiv.org/pdf/1907.04916](http://arxiv.org/pdf/1907.04916)


---
layout: post
title: "Fine-grained robust prosody transfer for single-speaker neural text-to-speech"
date: 2019-07-04 16:20:42
categories: arXiv_CL
tags: arXiv_CL Attention Embedding
author: Viacheslav Klimkov, Srikanth Ronanki, Jonas Rohnke, Thomas Drugman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural text-to-speech system for fine-grained prosody transfer from one speaker to another. Conventional approaches for end-to-end prosody transfer typically use either fixed-dimensional or variable-length prosody embedding via a secondary attention to encode the reference signal. However, when trained on a single-speaker dataset, the conventional prosody transfer systems are not robust enough to speaker variability, especially in the case of a reference signal coming from an unseen speaker. Therefore, we propose decoupling of the reference signal alignment from the overall system. For this purpose, we pre-compute phoneme-level time stamps and use them to aggregate prosodic features per phoneme, injecting them into a sequence-to-sequence text-to-speech system. We incorporate a variational auto-encoder to further enhance the latent representation of prosody embeddings. We show that our proposed approach is significantly more stable and achieves reliable prosody transplantation from an unseen speaker. We also propose a solution to the use case in which the transcription of the reference signal is absent. We evaluate all our proposed methods using both objective and subjective listening tests.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02479](http://arxiv.org/abs/1907.02479)

##### PDF
[http://arxiv.org/pdf/1907.02479](http://arxiv.org/pdf/1907.02479)


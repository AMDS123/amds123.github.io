---
layout: post
title: "Finding Better Subword Segmentation for Neural Machine Translation"
date: 2018-07-25 14:43:46
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Yingting Wu, Hai Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
For different language pairs, word-level neural machine translation (NMT) models with a fixed-size vocabulary suffer from the same problem of representing out-of-vocabulary (OOV) words. The common practice usually replaces all these rare or unknown words with a <UNK> token, which limits the translation performance to some extent. Most of recent work handled such a problem by splitting words into characters or other specially extracted subword units to enable open-vocabulary translation. Byte pair encoding (BPE) is one of the successful attempts that has been shown extremely competitive by providing effective subword segmentation for NMT systems. In this paper, we extend the BPE style segmentation to a general unsupervised framework with three statistical measures: frequency (FRQ), accessor variety (AV) and description length gain (DLG). We test our approach on two translation tasks: German to English and Chinese to English. The experimental results show that AV and DLG enhanced systems outperform the FRQ baseline in the frequency weighted schemes at different significant levels.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.09639](https://arxiv.org/abs/1807.09639)

##### PDF
[https://arxiv.org/pdf/1807.09639](https://arxiv.org/pdf/1807.09639)


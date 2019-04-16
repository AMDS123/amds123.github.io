---
layout: post
title: "Exploring Recombination for Efficient Decoding of Neural Machine Translation"
date: 2018-10-15 01:08:02
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Zhisong Zhang, Rui Wang, Masao Utiyama, Eiichiro Sumita, Hai Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
In Neural Machine Translation (NMT), the decoder can capture the features of the entire prediction history with neural connections and representations. This means that partial hypotheses with different prefixes will be regarded differently no matter how similar they are. However, this might be inefficient since some partial hypotheses can contain only local differences that will not influence future predictions. In this work, we introduce recombination in NMT decoding based on the concept of the "equivalence" of partial hypotheses. Heuristically, we use a simple $n$-gram suffix based equivalence function and adapt it into beam search decoding. Through experiments on large-scale Chinese-to-English and English-to-Germen translation tasks, we show that the proposed method can obtain similar translation quality with a smaller beam size, making NMT decoding more efficient.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.08482](https://arxiv.org/abs/1808.08482)

##### PDF
[https://arxiv.org/e-print/1808.08482](https://arxiv.org/e-print/1808.08482)


---
layout: post
title: "When to Finish? Optimal Beam Search for Neural Text Generation"
date: 2018-08-31 22:01:48
categories: arXiv_CV
tags: arXiv_CV Image_Caption Summarization Text_Generation Caption
author: Liang Huang, Kai Zhao, Mingbo Ma
mathjax: true
---

* content
{:toc}

##### Abstract
In neural text generation such as neural machine translation, summarization, and image captioning, beam search is widely used to improve the output text quality. However, in the neural generation setting, hypotheses can finish in different steps, which makes it difficult to decide when to end beam search to ensure optimality. We propose a provably optimal beam search algorithm that will always return the optimal-score complete hypothesis (modulo beam size), and finish as soon as the optimality is established (finishing no later than the baseline). To counter neural generation's tendency for shorter hypotheses, we also introduce a bounded length reward mechanism which allows a modified version of our beam search algorithm to remain optimal. Experiments on neural machine translation demonstrate that our principled beam search algorithm leads to improvement in BLEU score over previously proposed alternatives.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.00069](https://arxiv.org/abs/1809.00069)

##### PDF
[https://arxiv.org/pdf/1809.00069](https://arxiv.org/pdf/1809.00069)


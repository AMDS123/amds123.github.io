---
layout: post
title: "SwitchOut: an Efficient Data Augmentation Algorithm for Neural Machine Translation"
date: 2018-08-28 15:43:09
categories: arXiv_CL
tags: arXiv_CL Optimization NMT
author: Xinyi Wang, Hieu Pham, Zihang Dai, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we examine methods for data augmentation for text-based tasks such as neural machine translation (NMT). We formulate the design of a data augmentation policy with desirable properties as an optimization problem, and derive a generic analytic solution. This solution not only subsumes some existing augmentation schemes, but also leads to an extremely simple data augmentation strategy for NMT: randomly replacing words in both the source sentence and the target sentence with other random words from their corresponding vocabularies. We name this method SwitchOut. Experiments on three translation datasets of different scales show that SwitchOut yields consistent improvements of about 0.5 BLEU, achieving better or comparable performances to strong alternatives such as word dropout (Sennrich et al., 2016a). Code to implement this method is included in the appendix.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.07512](https://arxiv.org/abs/1808.07512)

##### PDF
[https://arxiv.org/pdf/1808.07512](https://arxiv.org/pdf/1808.07512)


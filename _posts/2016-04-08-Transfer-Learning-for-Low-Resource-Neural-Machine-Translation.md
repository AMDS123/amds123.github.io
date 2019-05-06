---
layout: post
title: "Transfer Learning for Low-Resource Neural Machine Translation"
date: 2016-04-08 00:16:35
categories: arXiv_CL
tags: arXiv_CL Transfer_Learning NMT
author: Barret Zoph, Deniz Yuret, Jonathan May, Kevin Knight
mathjax: true
---

* content
{:toc}

##### Abstract
The encoder-decoder framework for neural machine translation (NMT) has been shown effective in large data scenarios, but is much less effective for low-resource languages. We present a transfer learning method that significantly improves Bleu scores across a range of low-resource languages. Our key idea is to first train a high-resource language pair (the parent model), then transfer some of the learned parameters to the low-resource pair (the child model) to initialize and constrain training. Using our transfer learning method we improve baseline NMT models by an average of 5.6 Bleu on four low-resource language pairs. Ensembling and unknown word replacement add another 2 Bleu which brings the NMT performance on low-resource machine translation close to a strong syntax based machine translation (SBMT) system, exceeding its performance on one language pair. Additionally, using the transfer learning model for re-scoring, we can improve the SBMT system by an average of 1.3 Bleu, improving the state-of-the-art on low-resource machine translation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1604.02201](https://arxiv.org/abs/1604.02201)

##### PDF
[https://arxiv.org/pdf/1604.02201](https://arxiv.org/pdf/1604.02201)


---
layout: post
title: "Bi-Directional Neural Machine Translation with Synthetic Parallel Data"
date: 2018-05-30 15:54:48
categories: arXiv_CL
tags: arXiv_CL NMT
author: Xing Niu, Michael Denkowski, Marine Carpuat
mathjax: true
---

* content
{:toc}

##### Abstract
Despite impressive progress in high-resource settings, Neural Machine Translation (NMT) still struggles in low-resource and out-of-domain scenarios, often failing to match the quality of phrase-based translation. We propose a novel technique that combines back-translation and multilingual NMT to improve performance in these difficult cases. Our technique trains a single model for both directions of a language pair, allowing us to back-translate source or target monolingual data without requiring an auxiliary model. We then continue training on the augmented parallel data, enabling a cycle of improvement for a single model that can incorporate any source, target, or parallel data to improve both translation directions. As a byproduct, these models can reduce training and deployment costs significantly compared to uni-directional models. Extensive experiments show that our technique outperforms standard back-translation in low-resource scenarios, improves quality on cross-domain tasks, and effectively reduces costs across the board.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.11213](https://arxiv.org/abs/1805.11213)

##### PDF
[https://arxiv.org/pdf/1805.11213](https://arxiv.org/pdf/1805.11213)


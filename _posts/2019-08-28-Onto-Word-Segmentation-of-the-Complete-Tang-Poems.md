---
layout: post
title: "Onto Word Segmentation of the Complete Tang Poems"
date: 2019-08-28 10:06:19
categories: arXiv_AI
tags: arXiv_AI Knowledge Segmentation RNN
author: Chao-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We aim at segmenting words in the Complete Tang Poems (CTP). Although it is possible to do some research about CTP without doing full-scale word segmentation, we must move forward to word-level analysis of CTP for conducting advanced research topics. In November 2018 when we submitted the manuscript for DH 2019 (ADHO), we collected only 2433 poems that were segmented by trained experts, and used the segmented poems to evaluate the segmenter that considered domain knowledge of Chinese poetry. We trained pointwise mutual information (PMI) between Chinese characters based on the CTP poems (excluding the 2433 poems, which were used exclusively only for testing) and the domain knowledge. The segmenter relied on the PMI information to the recover 85.7% of words in the test poems. We could segment a poem completely correct only 17.8% of the time, however. When we presented our work at DH 2019, we have annotated more than 20000 poems. With a much larger amount of data, we were able to apply biLSTM models for this word segmentation task, and we segmented a poem completely correct above 20% of the time. In contrast, human annotators completely agreed on their annotations about 40% of the time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10621](http://arxiv.org/abs/1908.10621)

##### PDF
[http://arxiv.org/pdf/1908.10621](http://arxiv.org/pdf/1908.10621)


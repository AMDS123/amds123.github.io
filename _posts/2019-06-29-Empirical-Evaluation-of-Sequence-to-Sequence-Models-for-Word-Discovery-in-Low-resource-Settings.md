---
layout: post
title: "Empirical Evaluation of Sequence-to-Sequence Models for Word Discovery in Low-resource Settings"
date: 2019-06-29 11:47:22
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention RNN
author: Marcely Zanon Boito, Aline Villavicencio, Laurent Besacier
mathjax: true
---

* content
{:toc}

##### Abstract
Since Bahdanau et al. [1] first introduced attention for neural machine translation, most sequence-to-sequence models made use of attention mechanisms [2, 3, 4]. While they produce soft-alignment matrices that could be interpreted as alignment between target and source languages, we lack metrics to quantify their quality, being unclear which approach produces the best alignments. This paper presents an empirical evaluation of 3 main sequence-to-sequence models (CNN, RNN and Transformer-based) for word discovery from unsegmented phoneme sequences. This task consists in aligning word sequences in a source language with phoneme sequences in a target language, inferring from it word segmentation on the target side [5]. Evaluating word segmentation quality can be seen as an extrinsic evaluation of the soft-alignment matrices produced during training. Our experiments in a low-resource scenario on Mboshi and English languages (both aligned to French) show that RNNs surprisingly outperform CNNs and Transformer for this task. Our results are confirmed by an intrinsic evaluation of alignment quality through the use of Average Normalized Entropy (ANE). Lastly, we improve our best word discovery model by using an alignment entropy confidence measure that accumulates ANE over all the occurrences of a given alignment pair in the collection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00184](http://arxiv.org/abs/1907.00184)

##### PDF
[http://arxiv.org/pdf/1907.00184](http://arxiv.org/pdf/1907.00184)


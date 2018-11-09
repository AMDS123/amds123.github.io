---
layout: post
title: "Few-shot learning with attention-based sequence-to-sequence models"
date: 2018-11-08 16:05:50
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Classification Recognition
author: Bertrand Higy, Peter Bell
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end approaches have recently become popular as a means of simplifying the training and deployment of speech recognition systems. However, they often require large amounts of data to perform well on large vocabulary tasks. With the aim of making end-to-end approaches usable by a broader range of researchers, we explore the potential to use end-to-end methods in small vocabulary contexts where smaller datasets may be used. A significant drawback of small-vocabulary systems is the difficulty of expanding the vocabulary beyond the original training samples -- therefore we also study strategies to extend the vocabulary with only few examples per new class (few-shot learning). 
 Our results show that an attention-based encoder-decoder can be competitive against a strong baseline on a small vocabulary keyword classification task, reaching 97.5% of accuracy on Tensorflow's Speech Commands dataset. It also shows promising results on the few-shot learning problem where a simple strategy achieved 34.8% of accuracy on new keywords with only 10 examples for each new class. This score goes up to 80.3% with a larger set of 100 examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03519](http://arxiv.org/abs/1811.03519)

##### PDF
[http://arxiv.org/pdf/1811.03519](http://arxiv.org/pdf/1811.03519)


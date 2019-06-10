---
layout: post
title: "Word-based Domain Adaptation for Neural Machine Translation"
date: 2019-06-07 14:32:17
categories: arXiv_AI
tags: arXiv_AI Language_Model
author: Shen Yan, Leonard Dahlmann, Pavel Petrushkov, Sanjika Hewavitharana, Shahram Khadivi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we empirically investigate applying word-level weights to adapt neural machine translation to e-commerce domains, where small e-commerce datasets and large out-of-domain datasets are available. In order to mine in-domain like words in the out-of-domain datasets, we compute word weights by using a domain-specific and a non-domain-specific language model followed by smoothing and binary quantization. The baseline model is trained on mixed in-domain and out-of-domain datasets. Experimental results on English to Chinese e-commerce domain translation show that compared to continuing training without word weights, it improves MT quality by up to 2.11% BLEU absolute and 1.59% TER. We have also trained models using fine-tuning on the in-domain data. Pre-training a model with word weights improves fine-tuning up to 1.24% BLEU absolute and 1.64% TER, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03129](http://arxiv.org/abs/1906.03129)

##### PDF
[http://arxiv.org/pdf/1906.03129](http://arxiv.org/pdf/1906.03129)


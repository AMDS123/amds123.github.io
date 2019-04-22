---
layout: post
title: "A Scalable Handwritten Text Recognition System"
date: 2019-04-19 11:35:27
categories: arXiv_CV
tags: arXiv_CV OCR Inference RNN Recognition
author: R. Reeve Ingle, Yasuhisa Fujii, Thomas Deselaers, Jonathan Baccash, Ashok C. Popat
mathjax: true
---

* content
{:toc}

##### Abstract
Many studies on (Offline) Handwritten Text Recognition (HTR) systems have focused on building state-of-the-art models for line recognition on small corpora. However, adding HTR capability to a large scale multilingual OCR system poses new challenges. This paper addresses three problems in building such systems: data, efficiency, and integration. Firstly, one of the biggest challenges is obtaining sufficient amounts of high quality training data. We address the problem by using online handwriting data collected for a large scale production online handwriting recognition system. We describe our image data generation pipeline and study how online data can be used to build HTR models. We show that the data improve the models significantly under the condition where only a small number of real images is available, which is usually the case for HTR models. It enables us to support a new script at substantially lower cost. Secondly, we propose a line recognition model based on neural networks without recurrent connections. The model achieves a comparable accuracy with LSTM-based models while allowing for better parallelism in training and inference. Finally, we present a simple way to integrate HTR models into an OCR system. These constitute a solution to bring HTR capability into a large scale OCR system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09150](http://arxiv.org/abs/1904.09150)

##### PDF
[http://arxiv.org/pdf/1904.09150](http://arxiv.org/pdf/1904.09150)


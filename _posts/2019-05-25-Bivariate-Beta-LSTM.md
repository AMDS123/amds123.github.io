---
layout: post
title: "Bivariate Beta LSTM"
date: 2019-05-25 05:10:01
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge Caption Image_Classification RNN Classification Relation
author: Kyungwoo Song, JoonHo Jang, Seung jae Shin, Il-Chul Moon
mathjax: true
---

* content
{:toc}

##### Abstract
Long Short-Term Memory (LSTM) infers the long term dependency through a cell state maintained by the input and the forget gate structures, which models a gate output as a value in [0,1] through a sigmoid function. However, due to the graduality of the sigmoid function, the sigmoid gate is not flexible in representing multi-modality or skewness. Besides, the previous models lack correlation modeling between the gates, which would be a new method to adopt domain knowledge. This paper proposes a new gate structure with the bivariate Beta distribution. The proposed gate structure enables hierarchical probabilistic modeling on the gates within the LSTM cell, so the modelers can customize the cell state flow. Also, we observed that our structured flexible gate modeling is enabled by the probability density estimation. Moreover, we theoretically show and empirically experiment that the bivariate Beta distribution gate structure alleviates the gradient vanishing problem. We demonstrate the effectiveness of bivariate Beta gate structure on the sentence classification, image classification, polyphonic music modeling, and image caption generation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.10521](https://arxiv.org/abs/1905.10521)

##### PDF
[https://arxiv.org/pdf/1905.10521](https://arxiv.org/pdf/1905.10521)


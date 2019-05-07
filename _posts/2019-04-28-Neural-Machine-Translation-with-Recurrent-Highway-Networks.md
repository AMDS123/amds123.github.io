---
layout: post
title: "Neural Machine Translation with Recurrent Highway Networks"
date: 2019-04-28 08:27:55
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN Language_Model
author: Maulik Parmar, V.Susheela Devi
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks have lately gained a lot of popularity in language modelling tasks, especially in neural machine translation(NMT). Very recent NMT models are based on Encoder-Decoder, where a deep LSTM based encoder is used to project the source sentence to a fixed dimensional vector and then another deep LSTM decodes the target sentence from the vector. However there has been very little work on exploring architectures that have more than one layer in space(i.e. in each time step). This paper examines the effectiveness of the simple Recurrent Highway Networks(RHN) in NMT tasks. The model uses Recurrent Highway Neural Network in encoder and decoder, with attention .We also explore the reconstructor model to improve adequacy. We demonstrate the effectiveness of all three approaches on the IWSLT English-Vietnamese dataset. We see that RHN performs on par with LSTM based models and even better in some cases.We see that deep RHN models are easy to train compared to deep LSTM based models because of highway connections. The paper also investigates the effects of increasing recurrent depth in each time step.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01996](http://arxiv.org/abs/1905.01996)

##### PDF
[http://arxiv.org/pdf/1905.01996](http://arxiv.org/pdf/1905.01996)


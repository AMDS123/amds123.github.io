---
layout: post
title: "Fine-tuning on Clean Data for End-to-End Speech Translation: FBK @ IWSLT 2018"
date: 2018-10-16 09:54:37
categories: arXiv_CL
tags: arXiv_CL RNN
author: Mattia Antonino Di Gangi, Roberto Dess&#xec;, Roldano Cattoni, Matteo Negri, Marco Turchi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes FBK's submission to the end-to-end English-German speech translation task at IWSLT 2018. Our system relies on a state-of-the-art model based on LSTMs and CNNs, where the CNNs are used to reduce the temporal dimension of the audio input, which is in general much higher than machine translation input. Our model was trained only on the audio-to-text parallel data released for the task, and fine-tuned on cleaned subsets of the original training corpus. The addition of weight normalization and label smoothing improved the baseline system by 1.0 BLEU point on our validation set. The final submission also featured checkpoint averaging within a training run and ensemble decoding of models trained during multiple runs. On test data, our best single model obtained a BLEU score of 9.7, while the ensemble obtained a BLEU score of 10.24.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07652](http://arxiv.org/abs/1810.07652)

##### PDF
[http://arxiv.org/pdf/1810.07652](http://arxiv.org/pdf/1810.07652)


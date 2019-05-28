---
layout: post
title: "CIF: Continuous Integrate-and-Fire for End-to-End Speech Recognition"
date: 2019-05-27 14:00:45
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Inference Language_Model Recognition
author: Linhao Dong, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic speech recognition (ASR) system is undergoing an exciting pathway to be more simplified and practical with the spring up of various end-to-end models. However, the mainstream of them neglects the positioning of token boundaries from continuous speech, which is considered crucial in human language learning and instant speech recognition. In this work, we propose Continuous Integrate-and-Fire (CIF), a 'soft' and 'monotonic' acoustic-to-linguistic alignment mechanism that addresses the boundary positioning by simulating the integrate-and-fire neuron model using continuous functions under the encoder-decoder framework. As the connection between the encoder and decoder, the CIF forwardly integrates the information in the encoded acoustic representations to determine a boundary and instantly fires the integrated information to the decoder once a boundary is located. Multiple effective strategies are introduced to the CIF-based model to alleviate the problems brought by the inaccurate positioning. Besides, multi-task learning is performed during training and an external language model is incorporated during inference to further boost the model performance. Evaluated on multiple ASR datasets that cover different languages and speech types, the CIF-based model shows stable convergence and competitive performance. Especially, it achieves a word error rate (WER) of 3.70% on the test-clean of Librispeech.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11235](https://arxiv.org/abs/1905.11235)

##### PDF
[https://arxiv.org/pdf/1905.11235](https://arxiv.org/pdf/1905.11235)


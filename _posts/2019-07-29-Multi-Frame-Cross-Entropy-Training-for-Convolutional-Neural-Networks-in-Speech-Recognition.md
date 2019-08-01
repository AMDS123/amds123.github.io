---
layout: post
title: "Multi-Frame Cross-Entropy Training for Convolutional Neural Networks in Speech Recognition"
date: 2019-07-29 19:56:46
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN RNN Recognition
author: Tom Sercu, Neil Mallinar
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Multi-Frame Cross-Entropy training (MFCE) for convolutional neural network acoustic models. Recognizing that similar to RNNs, CNNs are in nature sequence models that take variable length inputs, we propose to take as input to the CNN a part of an utterance long enough that multiple labels are predicted at once, therefore getting cross-entropy loss signal from multiple adjacent frames. This increases the amount of label information drastically for small marginal computational cost. We show large WER improvements on hub5 and rt02 after training on the 2000-hour Switchboard benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13121](http://arxiv.org/abs/1907.13121)

##### PDF
[http://arxiv.org/pdf/1907.13121](http://arxiv.org/pdf/1907.13121)


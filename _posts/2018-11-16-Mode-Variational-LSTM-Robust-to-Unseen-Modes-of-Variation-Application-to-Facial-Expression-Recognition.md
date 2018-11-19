---
layout: post
title: "Mode Variational LSTM Robust to Unseen Modes of Variation: Application to Facial Expression Recognition"
date: 2018-11-16 17:40:13
categories: arXiv_CV
tags: arXiv_CV RNN Classification Recognition
author: Wissam J. Baddar, Yong Man Ro
mathjax: true
---

* content
{:toc}

##### Abstract
Spatio-temporal feature encoding is essential for encoding the dynamics in video sequences. Recurrent neural networks, particularly long short-term memory (LSTM) units, have been popular as an efficient tool for encoding spatio-temporal features in sequences. In this work, we investigate the effect of mode variations on the encoded spatio-temporal features using LSTMs. We show that the LSTM retains information related to the mode variation in the sequence, which is irrelevant to the task at hand (e.g. classification facial expressions). Actually, the LSTM forget mechanism is not robust enough to mode variations and preserves information that could negatively affect the encoded spatio-temporal features. We propose the mode variational LSTM to encode spatio-temporal features robust to unseen modes of variation. The mode variational LSTM modifies the original LSTM structure by adding an additional cell state that focuses on encoding the mode variation in the input sequence. To efficiently regulate what features should be stored in the additional cell state, additional gating functionality is also introduced. The effectiveness of the proposed mode variational LSTM is verified using the facial expression recognition task. Comparative experiments on publicly available datasets verified that the proposed mode variational LSTM outperforms existing methods. Moreover, a new dynamic facial expression dataset with different modes of variation, including various modes like pose and illumination variations, was collected to comprehensively evaluate the proposed mode variational LSTM. Experimental results verified that the proposed mode variational LSTM encodes spatio-temporal features robust to unseen modes of variation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06937](http://arxiv.org/abs/1811.06937)

##### PDF
[http://arxiv.org/pdf/1811.06937](http://arxiv.org/pdf/1811.06937)


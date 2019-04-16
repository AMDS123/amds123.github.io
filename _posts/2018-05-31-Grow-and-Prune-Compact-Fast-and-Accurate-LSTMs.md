---
layout: post
title: "Grow and Prune Compact, Fast, and Accurate LSTMs"
date: 2018-05-31 03:49:25
categories: arXiv_CV
tags: arXiv_CV Image_Caption Speech_Recognition Caption RNN Recognition
author: Xiaoliang Dai, Hongxu Yin, Niraj K. Jha
mathjax: true
---

* content
{:toc}

##### Abstract
Long short-term memory (LSTM) has been widely used for sequential data modeling. Researchers have increased LSTM depth by stacking LSTM cells to improve performance. This incurs model redundancy, increases run-time delay, and makes the LSTMs more prone to overfitting. To address these problems, we propose a hidden-layer LSTM (H-LSTM) that adds hidden layers to LSTM's original one level non-linear control gates. H-LSTM increases accuracy while employing fewer external stacked layers, thus reducing the number of parameters and run-time latency significantly. We employ grow-and-prune (GP) training to iteratively adjust the hidden layers through gradient-based growth and magnitude-based pruning of connections. This learns both the weights and the compact architecture of H-LSTM control gates. We have GP-trained H-LSTMs for image captioning and speech recognition applications. For the NeuralTalk architecture on the MSCOCO dataset, our three models reduce the number of parameters by 38.7x [floating-point operations (FLOPs) by 45.5x], run-time latency by 4.5x, and improve the CIDEr score by 2.6. For the DeepSpeech2 architecture on the AN4 dataset, our two models reduce the number of parameters by 19.4x (FLOPs by 23.5x), run-time latency by 15.7%, and the word error rate from 12.9% to 8.7%. Thus, GP-trained H-LSTMs can be seen to be compact, fast, and accurate.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.11797](https://arxiv.org/abs/1805.11797)

##### PDF
[https://arxiv.org/pdf/1805.11797](https://arxiv.org/pdf/1805.11797)


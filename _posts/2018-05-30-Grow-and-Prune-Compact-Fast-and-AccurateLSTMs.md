---
layout: post
title: "Grow and Prune Compact, Fast, and AccurateLSTMs"
date: 2018-05-30 04:15:58
categories: arXiv_SD
tags: arXiv_SD Image_Caption Speech_Recognition Caption RNN Recognition
author: Xiaoliang Dai, Hongxu Yin, Niraj K. Jha
mathjax: true
---

* content
{:toc}

##### Abstract
Long short-term memory (LSTM) has been widely used for sequential data modeling. Researchers have increased LSTM depth by stacking LSTM cells to improve performance. This incurs model redundancy, increases run-time delay, and makes the LSTMs more prone to overfitting. To address these problems, we propose a hidden-layer LSTM (H-LSTM) that adds hidden layers to LSTM's original one level non-linear control gates. H-LSTM increases accuracy while employing fewer external stacked layers, thus reducing the number of parameters and run-time latency significantly. We employ grow-and-prune (GP) training to iteratively adjust the hidden layers through gradient-based growth and magnitude-based pruning of connections. This learns both the weights and the compact architecture of H-LSTM control gates. We have GP-trained H-LSTMs for image captioning and speech recognition applications. For the NeuralTalk architecture on the MSCOCO dataset, our three models reduce the number of parameters by 38.7x [floating-point operations (FLOPs) by 45.5x], run-time latency by 4.5x, and improve the CIDEr score by 2.6. For the DeepSpeech2 architecture on the AN4 dataset, our two models reduce the number of parameters by 19.4x (FLOPs by 23.5x), run-time latency by 15.7%, and the word error rate from 12.9% to 8.7%. Thus, GP-trained H-LSTMs can be seen to be compact, fast, and accurate.

##### Abstract (translated by Google)
长期短期记忆（LSTM）已被广泛用于顺序数据建模。研究人员通过堆叠LSTM细胞来提高LSTM深度，以提高性能。这会导致模型冗余，延长运行时间，并使LSTM更容易出现过度配合。为了解决这些问题，我们提出了一个隐藏层LSTM（H-LSTM），它为LSTM原来的一级非线性控制门增加了隐藏层。 H-LSTM提高了准确性，同时采用更少的外部堆叠层，从而显着减少了参数数量和运行时间延迟。我们采用增长和修剪（GP）培训，通过基于梯度的增长和基于量值的连接修剪来迭代调整隐藏层。这将学习H-LSTM控制门的权重和紧凑架构。我们有GP训练的H-LSTM用于图像字幕和语音识别应用。对于MSCOCO数据集上的NeuralTalk架构，我们的三个模型将参数数量减少了38.7倍[浮点运算（FLOP）] 45.5倍，运行时延迟4.5倍，并将CIDEr得分提高2.6倍。对于AN4数据集上的DeepSpeech2架构，我们的两个模型将参数数量减少了19.4倍（FLOPs减少了23.5倍），运行时延迟了15.7％，字错误率从12.9％减少到了8.7％。因此，GP培训的H-LSTM可以看作是紧凑，快速和准确的。

##### URL
[http://arxiv.org/abs/1805.11797](http://arxiv.org/abs/1805.11797)

##### PDF
[http://arxiv.org/pdf/1805.11797](http://arxiv.org/pdf/1805.11797)


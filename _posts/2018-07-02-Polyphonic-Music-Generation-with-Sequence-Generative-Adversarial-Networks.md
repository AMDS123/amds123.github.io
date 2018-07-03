---
layout: post
title: "Polyphonic Music Generation with Sequence Generative Adversarial Networks"
date: 2018-07-02 04:44:03
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN Reinforcement_Learning Optimization RNN Quantitative
author: Sang-gil Lee, Uiwon Hwang, Seonwoo Min, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an application of sequence generative adversarial networks (SeqGAN), which are generative adversarial networks for discrete sequence generation, for creating polyphonic musical sequences. Instead of a monophonic melody generation suggested in the original work, we present an efficient representation of a polyphony MIDI file that simultaneously captures chords and melodies with dynamic timings. The proposed method condenses duration, octaves, and keys of both melodies and chords into a single word vector representation, and recurrent neural networks learn to predict distributions of sequences from the embedded musical word space. We experiment with the original method and the least squares method to the discriminator, which is known to stabilize the training of GANs. The network can create sequences that are musically coherent and shows an improved quantitative and qualitative measures. We also report that careful optimization of reinforcement learning signals of the model is crucial for general application of the model.

##### Abstract (translated by Google)
我们提出了序列生成对抗网络（SeqGAN）的应用，它是用于离散序列生成的生成对抗网络，用于创建复调音乐序列。我们提供了一个复音MIDI文件的有效表示，它可以同时捕捉带有动态时序的和弦和旋律，而不是原作中建议的单声道旋律生成。所提出的方法将旋律和和弦的持续时间，八度音阶和键压缩成单个单词矢量表示，并且循环神经网络学习预测来自嵌入音乐单词空间的序列的分布。我们用鉴别器的原始方法和最小二乘法进行实验，已知它可以稳定GAN的训练。网络可以创建音乐连贯的序列，并显示出改进的定量和定性测量。我们还报告说，仔细优化模型的强化学习信号对于模型的一般应用至关重要。

##### URL
[http://arxiv.org/abs/1710.11418](http://arxiv.org/abs/1710.11418)

##### PDF
[http://arxiv.org/pdf/1710.11418](http://arxiv.org/pdf/1710.11418)


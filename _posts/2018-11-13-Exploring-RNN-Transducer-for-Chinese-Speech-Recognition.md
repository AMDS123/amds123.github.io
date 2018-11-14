---
layout: post
title: "Exploring RNN-Transducer for Chinese Speech Recognition"
date: 2018-11-13 04:37:11
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition CNN RNN Language_Model Recognition
author: Senmao Wang, Pan Zhou, Wei Chen, Jia Jia, Lei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end approaches have drawn much attention recently for significantly simplifying the construction of an automatic speech recognition (ASR) system. RNN transducer (RNN-T) is one of the popular end-to-end methods. Previous studies have shown that RNN-T is difficult to train and a very complex training process is needed for a reasonable performance. In this paper, we explore RNN-T for a Chinese large vocabulary continuous speech recognition (LVCSR) task and aim to simplify the training process while maintaining performance. First, a new strategy of learning rate decay is proposed to accelerate the model convergence. Second, we find that adding convolutional layers at the beginning of the network and using ordered data can discard the pre-training process of the encoder without loss of performance. Besides, we design experiments to find a balance among the usage of GPU memory, training circle and model performance. Finally, we achieve 16.9% character error rate (CER) on our test set which is 2% absolute improvement from a strong BLSTM CE system with language model trained on the same text corpus.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.05097](https://arxiv.org/abs/1811.05097)

##### PDF
[https://arxiv.org/pdf/1811.05097](https://arxiv.org/pdf/1811.05097)


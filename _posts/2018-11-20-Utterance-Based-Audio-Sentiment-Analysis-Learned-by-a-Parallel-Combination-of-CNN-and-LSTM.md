---
layout: post
title: "Utterance-Based Audio Sentiment Analysis Learned by a Parallel Combination of CNN and LSTM"
date: 2018-11-20 04:10:23
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention CNN RNN Deep_Learning
author: Ziqian Luo, Hua Xu, Feiyang Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Audio Sentiment Analysis is a popular research area which extends the conventional text-based sentiment analysis to depend on the effectiveness of acoustic features extracted from speech. However, current progress on audio sentiment analysis mainly focuses on extracting homogeneous acoustic features or doesn't fuse heterogeneous features effectively. In this paper, we propose an utterance-based deep neural network model, which has a parallel combination of Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) based network, to obtain representative features termed Audio Sentiment Vector (ASV), that can maximally reflect sentiment information in an audio. Specifically, our model is trained by utterance-level labels and ASV can be extracted and fused creatively from two branches. In the CNN model branch, spectrum graphs produced by signals are fed as inputs while in the LSTM model branch, inputs include spectral features and cepstrum coefficient extracted from dependent utterances in an audio. Besides, Bidirectional Long Short-Term Memory (BiLSTM) with attention mechanism is used for feature fusion. Extensive experiments have been conducted to show our model can recognize audio sentiment precisely and quickly, and demonstrate our ASV are better than traditional acoustic features or vectors extracted from other deep learning models. Furthermore, experimental results indicate that the proposed model outperforms the state-of-the-art approach by 9.33% on Multimodal Opinion-level Sentiment Intensity dataset (MOSI) dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08065](http://arxiv.org/abs/1811.08065)

##### PDF
[http://arxiv.org/pdf/1811.08065](http://arxiv.org/pdf/1811.08065)


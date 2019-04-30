---
layout: post
title: "Hierarchical Recurrent Neural Network for Video Summarization"
date: 2019-04-28 03:32:21
categories: arXiv_CV
tags: arXiv_CV Video_Caption Summarization Caption RNN Classification
author: Bin Zhao, Xuelong Li, Xiaoqiang Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Exploiting the temporal dependency among video frames or subshots is very important for the task of video summarization. Practically, RNN is good at temporal dependency modeling, and has achieved overwhelming performance in many video-based tasks, such as video captioning and classification. However, RNN is not capable enough to handle the video summarization task, since traditional RNNs, including LSTM, can only deal with short videos, while the videos in the summarization task are usually in longer duration. To address this problem, we propose a hierarchical recurrent neural network for video summarization, called H-RNN in this paper. Specifically, it has two layers, where the first layer is utilized to encode short video subshots cut from the original video, and the final hidden state of each subshot is input to the second layer for calculating its confidence to be a key subshot. Compared to traditional RNNs, H-RNN is more suitable to video summarization, since it can exploit long temporal dependency among frames, meanwhile, the computation operations are significantly lessened. The results on two popular datasets, including the Combined dataset and VTW dataset, have demonstrated that the proposed H-RNN outperforms the state-of-the-arts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12251](http://arxiv.org/abs/1904.12251)

##### PDF
[http://arxiv.org/pdf/1904.12251](http://arxiv.org/pdf/1904.12251)


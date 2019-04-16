---
layout: post
title: "End-to-End Video Captioning with Multitask Reinforcement Learning"
date: 2019-01-01 10:40:07
categories: arXiv_CV
tags: arXiv_CV Video_Caption Knowledge Reinforcement_Learning Caption CNN RNN
author: Lijun Li, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Although end-to-end (E2E) learning has led to impressive progress on a variety of visual understanding tasks, it is often impeded by hardware constraints (e.g., GPU memory) and is prone to overfitting. When it comes to video captioning, one of the most challenging benchmark tasks in computer vision, those limitations of E2E learning are especially amplified by the fact that both the input videos and output captions are lengthy sequences. Indeed, state-of-the-art methods for video captioning process video frames by convolutional neural networks and generate captions by unrolling recurrent neural networks. If we connect them in an E2E manner, the resulting model is both memory-consuming and data-hungry, making it extremely hard to train. In this paper, we propose a multitask reinforcement learning approach to training an E2E video captioning model. The main idea is to mine and construct as many effective tasks (e.g., attributes, rewards, and the captions) as possible from the human captioned videos such that they can jointly regulate the search space of the E2E neural network, from which an E2E video captioning model can be found and generalized to the testing phase. To the best of our knowledge, this is the first video captioning model that is trained end-to-end from the raw video input to the caption output. Experimental results show that such a model outperforms existing ones to a large margin on two benchmark video captioning datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.07950](https://arxiv.org/abs/1803.07950)

##### PDF
[https://arxiv.org/pdf/1803.07950](https://arxiv.org/pdf/1803.07950)


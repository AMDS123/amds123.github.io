---
layout: post
title: "Review Networks for Caption Generation"
date: 2016-10-27 17:50:27
categories: arXiv_CV
tags: arXiv_CV Image_Caption Review Caption RNN
author: Zhilin Yang, Ye Yuan, Yuexin Wu, Ruslan Salakhutdinov, William W. Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel extension of the encoder-decoder framework, called a review network. The review network is generic and can enhance any existing encoder- decoder model: in this paper, we consider RNN decoders with both CNN and RNN encoders. The review network performs a number of review steps with attention mechanism on the encoder hidden states, and outputs a thought vector after each review step; the thought vectors are used as the input of the attention mechanism in the decoder. We show that conventional encoder-decoders are a special case of our framework. Empirically, we show that our framework improves over state-of- the-art encoder-decoder systems on the tasks of image captioning and source code captioning.

##### Abstract (translated by Google)
我们提出了一个新的扩展编码器 - 解码器框架，称为评论网络。审查网络是通用的，可以增强任何现有的编码器 - 解码器模型：在本文中，我们考虑使用CNN和RNN编码器的RNN解码器。评论网络对编码器隐藏状态进行多个关注机制的评论步骤，并在每个评论步骤之后输出思想向量;思想向量被用作解码器中的关注机制的输入。我们展示了传统的编码器解码器是我们框架的一个特例。实证上，我们表明，我们的框架在图像字幕和源代码字幕任务上优于最先进的编码器 - 解码器系统。

##### URL
[https://arxiv.org/abs/1605.07912](https://arxiv.org/abs/1605.07912)


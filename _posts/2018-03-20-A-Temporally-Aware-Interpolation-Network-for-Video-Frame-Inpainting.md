---
layout: post
title: "A Temporally-Aware Interpolation Network for Video Frame Inpainting"
date: 2018-03-20 02:01:37
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Prediction
author: Ximeng Sun, Ryan Szeto, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the first deep learning solution to video frame inpainting, a challenging instance of the general video inpainting problem with applications in video editing, manipulation, and forensics. Our task is less ambiguous than frame interpolation and video prediction because we have access to both the temporal context and a partial glimpse of the future, allowing us to better evaluate the quality of a model's predictions objectively. We devise a pipeline composed of two modules: a bidirectional video prediction module, and a temporally-aware frame interpolation module. The prediction module makes two intermediate predictions of the missing frames, one conditioned on the preceding frames and the other conditioned on the following frames, using a shared convolutional LSTM-based encoder-decoder. The interpolation module blends the intermediate predictions to form the final result. Specifically, it utilizes time information and hidden activations from the video prediction module to resolve disagreements between the predictions. Our experiments demonstrate that our approach produces more accurate and qualitatively satisfying results than a state-of-the-art video prediction method and many strong frame inpainting baselines.

##### Abstract (translated by Google)
我们提出了第一个视频帧修补的深度学习解决方案，这是视频编辑，操作和取证应用中一般视频修补问题的一个具有挑战性的实例。我们的任务与帧内插和视频预测相比不那么模糊，因为我们可以访问时间背景和对未来的部分瞥见，从而使我们能够更客观地评估模型预测的质量。我们设计了一个由两个模块组成的管道：一个双向视频预测模块和一个时间感知帧插值模块。预测模块使用共享的基于卷积LSTM的编码器 - 解码器对丢失帧进行两个中间预测，一个以前面的帧为条件，另一个以后面的帧为条件。插值模块混合中间预测以形成最终结果。具体而言，它利用来自视频预测模块的时间信息和隐藏激活来解决预测之间的不一致。我们的实验表明，我们的方法产生比最先进的视频预测方法和许多强大的帧内修复基线更准确和定性的满意结果。

##### URL
[http://arxiv.org/abs/1803.07218](http://arxiv.org/abs/1803.07218)

##### PDF
[http://arxiv.org/pdf/1803.07218](http://arxiv.org/pdf/1803.07218)


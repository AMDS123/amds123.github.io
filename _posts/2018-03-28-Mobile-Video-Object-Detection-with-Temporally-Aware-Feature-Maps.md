---
layout: post
title: "Mobile Video Object Detection with Temporally-Aware Feature Maps"
date: 2018-03-28 20:05:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Inference RNN Detection
author: Mason Liu, Menglong Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces an online model for object detection in videos designed to run in real-time on low-powered mobile and embedded devices. Our approach combines fast single-image object detection with convolutional long short term memory (LSTM) layers to create an interweaved recurrent-convolutional architecture. Additionally, we propose an efficient Bottleneck-LSTM layer that significantly reduces computational cost compared to regular LSTMs. Our network achieves temporal awareness by using Bottleneck-LSTMs to refine and propagate feature maps across frames. This approach is substantially faster than existing detection methods in video, outperforming the fastest single-frame models in model size and computational cost while attaining accuracy comparable to much more expensive single-frame models on the Imagenet VID 2015 dataset. Our model reaches a real-time inference speed of up to 15 FPS on a mobile CPU.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.06368](https://arxiv.org/abs/1711.06368)

##### PDF
[https://arxiv.org/pdf/1711.06368](https://arxiv.org/pdf/1711.06368)


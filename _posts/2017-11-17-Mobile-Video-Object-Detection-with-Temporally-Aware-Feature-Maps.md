---
layout: post
title: "Mobile Video Object Detection with Temporally-Aware Feature Maps"
date: 2017-11-17 01:40:12
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
本文介绍了一个在线模型，用于在低功耗移动设备和嵌入式设备上实时运行的视频中进行对象检测。我们的方法将快速单图像对象检测与卷积长短期记忆（LSTM）层相结合，以创建交织的循环卷积体系结构。此外，我们提出了一个高效的Bottleneck-LSTM层，与常规的LSTM相比，显着降低了计算成本。我们的网络通过使用Bottleneck-LSTM改进和传播跨帧的特征映射来实现时间感知。这种方法比视频中的现有检测方法快得多，在模型大小和计算成本方面超过了最快的单帧模型，同时获得了与Imagenet VID 2015数据集上更昂贵的单帧模型相当的精度。我们的模型在移动CPU上达到了15 FPS的实时推断速度。

##### URL
[https://arxiv.org/abs/1711.06368](https://arxiv.org/abs/1711.06368)

##### PDF
[https://arxiv.org/pdf/1711.06368](https://arxiv.org/pdf/1711.06368)


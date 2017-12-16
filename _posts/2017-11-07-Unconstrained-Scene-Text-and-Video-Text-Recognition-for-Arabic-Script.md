---
layout: post
title: "Unconstrained Scene Text and Video Text Recognition for Arabic Script"
date: 2017-11-07 11:07:48
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Recognition
author: Mohit Jain, Minesh Mathew, C.V. Jawahar
mathjax: true
---

* content
{:toc}

##### Abstract
Building robust recognizers for Arabic has always been challenging. We demonstrate the effectiveness of an end-to-end trainable CNN-RNN hybrid architecture in recognizing Arabic text in videos and natural scenes. We outperform previous state-of-the-art on two publicly available video text datasets - ALIF and ACTIV. For the scene text recognition task, we introduce a new Arabic scene text dataset and establish baseline results. For scripts like Arabic, a major challenge in developing robust recognizers is the lack of large quantity of annotated data. We overcome this by synthesising millions of Arabic text images from a large vocabulary of Arabic words and phrases. Our implementation is built on top of the model introduced here [37] which is proven quite effective for English scene text recognition. The model follows a segmentation-free, sequence to sequence transcription approach. The network transcribes a sequence of convolutional features from the input image to a sequence of target labels. This does away with the need for segmenting input image into constituent characters/glyphs, which is often difficult for Arabic script. Further, the ability of RNNs to model contextual dependencies yields superior recognition results.

##### Abstract (translated by Google)
建立强大的阿拉伯识别器一直是一个挑战。我们展示端到端可训练的CNN-RNN混合体系结构在视频和自然场景中识别阿拉伯文本的有效性。我们在两个公开可用的视频文本数据集（ALIF和ACTIV）上超越了以前的最新技术水平。对于场景文本识别任务，我们引入一个新的阿拉伯文场景文本数据集，并建立基线结果。对于像阿拉伯语这样的脚本来说，开发健壮识别器的一个主要挑战是缺少大量的注释数据。我们通过从阿拉伯词汇和短语的大量词汇中综合数以百万计的阿拉伯语文字图像来克服这一点。我们的实现建立在这里介绍的模型的基础之上[37]，这对于英文场景文本识别来说是相当有效的。该模型遵循无分段序列转录方法。网络从输入图像转换一系列卷积特征到一系列目标标签。这消除了将输入图像分割成组成字符/字形的需要，这对于阿拉伯文字来说通常是困难的。此外，RNN模拟上下文相关性的能力产生了优异的识别结果。

##### URL
[https://arxiv.org/abs/1711.02396](https://arxiv.org/abs/1711.02396)

##### PDF
[https://arxiv.org/pdf/1711.02396](https://arxiv.org/pdf/1711.02396)


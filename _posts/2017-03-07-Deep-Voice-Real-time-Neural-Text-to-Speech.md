---
layout: post
title: "Deep Voice: Real-time Neural Text-to-Speech"
date: 2017-03-07 23:09:23
categories: arXiv_SD
tags: arXiv_SD Segmentation Inference Classification Prediction Detection
author: Sercan O. Arik, Mike Chrzanowski, Adam Coates, Gregory Diamos, Andrew Gibiansky, Yongguo Kang, Xian Li, John Miller, Andrew Ng, Jonathan Raiman, Shubho Sengupta, Mohammad Shoeybi
mathjax: true
---

* content
{:toc}

##### Abstract
We present Deep Voice, a production-quality text-to-speech system constructed entirely from deep neural networks. Deep Voice lays the groundwork for truly end-to-end neural speech synthesis. The system comprises five major building blocks: a segmentation model for locating phoneme boundaries, a grapheme-to-phoneme conversion model, a phoneme duration prediction model, a fundamental frequency prediction model, and an audio synthesis model. For the segmentation model, we propose a novel way of performing phoneme boundary detection with deep neural networks using connectionist temporal classification (CTC) loss. For the audio synthesis model, we implement a variant of WaveNet that requires fewer parameters and trains faster than the original. By using a neural network for each component, our system is simpler and more flexible than traditional text-to-speech systems, where each component requires laborious feature engineering and extensive domain expertise. Finally, we show that inference with our system can be performed faster than real time and describe optimized WaveNet inference kernels on both CPU and GPU that achieve up to 400x speedups over existing implementations.

##### Abstract (translated by Google)
我们展示了Deep Voice，一个完全由深度神经网络构建的生产质量的文本到语音系统。 Deep Voice为真正的端到端神经语音合成奠定了基础。该系统包括五个主要构件：用于定位音素边界的分段模型，字形到音素转换模型，音素持续时间预测模型，基频预测模型和音频合成模型。对于分割模型，我们提出了一种使用连接主义时间分类（CTC）丢失的深度神经网络进行音素边界检测的新方法。对于音频合成模型，我们实现了WaveNet的一个变体，它需要更少的参数，并且训练速度比原来的要快。通过对每个组件使用神经网络，我们的系统比传统的文本到语音系统更简单和更灵活，其中每个组件需要费力的特征工程和广泛的领域专业知识。最后，我们展示了使用我们的系统进行推理可以比实时更快地执行，并且在CPU和GPU上描述优化的WaveNet推理内核，在现有实现上实现高达400倍的加速。

##### URL
[https://arxiv.org/abs/1702.07825](https://arxiv.org/abs/1702.07825)

##### PDF
[https://arxiv.org/pdf/1702.07825](https://arxiv.org/pdf/1702.07825)


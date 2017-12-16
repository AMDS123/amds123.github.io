---
layout: post
title: "Video Ladder Networks"
date: 2016-12-30 09:01:02
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Francesco Cricri, Xingyang Ni, Mikko Honkala, Emre Aksu, Moncef Gabbouj
mathjax: true
---

* content
{:toc}

##### Abstract
We present the Video Ladder Network (VLN) for efficiently generating future video frames. VLN is a neural encoder-decoder model augmented at all layers by both recurrent and feedforward lateral connections. At each layer, these connections form a lateral recurrent residual block, where the feedforward connection represents a skip connection and the recurrent connection represents the residual. Thanks to the recurrent connections, the decoder can exploit temporal summaries generated from all layers of the encoder. This way, the top layer is relieved from the pressure of modeling lower-level spatial and temporal details. Furthermore, we extend the basic version of VLN to incorporate ResNet-style residual blocks in the encoder and decoder, which help improving the prediction results. VLN is trained in self-supervised regime on the Moving MNIST dataset, achieving competitive results while having very simple structure and providing fast inference.

##### Abstract (translated by Google)
我们提供视频梯形网络（VLN），用于高效地生成未来的视频帧。 VLN是一种神经的编码器 - 解码器模型，在所有层面都被循环和前馈横向连接增强。在每一层，这些连接形成一个横向循环剩余块，其中前馈连接表示跳跃连接，并且反复连接表示剩余。由于经常性连接，解码器可以利用从编码器的所有层产生的时间总结。这样，顶层就可以免受建模低层次空间和时间细节的压力。此外，我们扩展了VLN的基本版本，在编码器和解码器中加入ResNet型残差块，有助于提高预测结果。 VLN在移动MNIST数据集的自我监督机制上得到了训练，在结构非常简单并提供快速推断的同时获得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1612.01756](https://arxiv.org/abs/1612.01756)

##### PDF
[https://arxiv.org/pdf/1612.01756](https://arxiv.org/pdf/1612.01756)


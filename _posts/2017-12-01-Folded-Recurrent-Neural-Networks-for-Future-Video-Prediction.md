---
layout: post
title: "Folded Recurrent Neural Networks for Future Video Prediction"
date: 2017-12-01 13:31:56
categories: arXiv_CV
tags: arXiv_CV RNN
author: Marc Oliu, Javier Selva, Sergio Escalera
mathjax: true
---

* content
{:toc}

##### Abstract
Future video prediction is an ill-posed Computer Vision problem that recently received much attention. Its main challenges are the high variability in video content, the propagation of errors through time, and the non-specificity of the future frames: given a sequence of past frames there is a continuous distribution of possible futures. This work introduces bijective Gated Recurrent Units, a double mapping between the input and output of a GRU layer. This allows for recurrent auto-encoders with state sharing between encoder and decoder, stratifying the sequence representation and helping to prevent capacity problems. We show how with this topology only the encoder or decoder needs to be applied for input encoding and prediction, respectively. This reduces the computational cost and avoids re-encoding the predictions when generating a sequence of frames, mitigating the propagation of errors. Furthermore, it is possible to remove layers from an already trained model, giving an insight to the role performed by each layer and making the model more explainable. We evaluate our approach on three video datasets, outperforming state of the art prediction results on MMNIST and UCF101, and obtaining competitive results on KTH with 2 and 3 times less memory usage and computational cost than the best scored approach.

##### Abstract (translated by Google)
未来的视频预测是一个不适合计算机视觉的问题，近来备受关注。它面临的主要挑战是视频内容的高度可变性，时间错误的传播以及未来帧的非特异性：给定一系列过去的帧，可能的未来将持续分布。这项工作引入了双重门控循环单元，一个GRU层的输入和输出之间的双重映射。这允许在编码器和解码器之间具有状态共享的经常性自动编码器，对序列表示进行分层并且帮助防止容量问题。我们展示了如何使用这种拓扑结构，只需要编码器或解码器分别应用于输入编码和预测。这降低了计算成本，避免了在生成帧序列时重新编码预测，减轻了错误的传播。此外，可以从已经过训练的模型中删除图层，从而洞察每个图层所执行的角色，并使模型更易于解释。我们在三个视频数据集上评估了我们的方法，超越了MMNIST和UCF101的最新技术预测结果，并在KTH上获得了比最佳评分方法少2和3倍的内存使用和计算成本的竞争结果。

##### URL
[https://arxiv.org/abs/1712.00311](https://arxiv.org/abs/1712.00311)


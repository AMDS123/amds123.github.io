---
layout: post
title: "Spatio-temporal video autoencoder with differentiable memory"
date: 2016-09-01 11:36:40
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation RNN Prediction
author: Viorica Patraucean, Ankur Handa, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a new spatio-temporal video autoencoder, based on a classic spatial image autoencoder and a novel nested temporal autoencoder. The temporal encoder is represented by a differentiable visual memory composed of convolutional long short-term memory (LSTM) cells that integrate changes over time. Here we target motion changes and use as temporal decoder a robust optical flow prediction module together with an image sampler serving as built-in feedback loop. The architecture is end-to-end differentiable. At each time step, the system receives as input a video frame, predicts the optical flow based on the current observation and the LSTM memory state as a dense transformation map, and applies it to the current frame to generate the next frame. By minimising the reconstruction error between the predicted next frame and the corresponding ground truth next frame, we train the whole system to extract features useful for motion estimation without any supervision effort. We present one direct application of the proposed framework in weakly-supervised semantic segmentation of videos through label propagation using optical flow.

##### Abstract (translated by Google)
我们描述了一个新的时空视频自动编码器，基于经典的空间图像自动编码器和新型嵌套时间自动编码器。时间编码器由一个可卷积的长时间短记忆（LSTM）单元组成的可微观视觉记忆表示，该单元集成了随时间变化的变化。在这里，我们针对运动变化，并使用一个强大的光流预测模块作为时间解码器和一个图像采样器作为内置的反馈环路。该体系结构是端到端可区分的。在每个时间步，系统接收视频帧作为输入，基于当前观察和LSTM存储器状态将光流预测为密集变换图，并将其应用于当前帧以生成下一帧。通过最小化预测的下一帧和相应的地面实况下一帧之间的重建误差，我们训练整个系统以在没有任何监督的情况下提取对运动估计有用的特征。通过使用光流的标签传播，我们提出了所提出的框架在视频的弱监督语义分割中的一个直接应用。

##### URL
[https://arxiv.org/abs/1511.06309](https://arxiv.org/abs/1511.06309)

##### PDF
[https://arxiv.org/pdf/1511.06309](https://arxiv.org/pdf/1511.06309)


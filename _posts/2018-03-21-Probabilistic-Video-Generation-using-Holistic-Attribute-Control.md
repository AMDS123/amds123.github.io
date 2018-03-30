---
layout: post
title: "Probabilistic Video Generation using Holistic Attribute Control"
date: 2018-03-21 18:39:47
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Jiawei He, Andreas Lehrmann, Joseph Marino, Greg Mori, Leonid Sigal
mathjax: true
---

* content
{:toc}

##### Abstract
Videos express highly structured spatio-temporal patterns of visual data. A video can be thought of as being governed by two factors: (i) temporally invariant (e.g., person identity), or slowly varying (e.g., activity), attribute-induced appearance, encoding the persistent content of each frame, and (ii) an inter-frame motion or scene dynamics (e.g., encoding evolution of the person ex-ecuting the action). Based on this intuition, we propose a generative framework for video generation and future prediction. The proposed framework generates a video (short clip) by decoding samples sequentially drawn from a latent space distribution into full video frames. Variational Autoencoders (VAEs) are used as a means of encoding/decoding frames into/from the latent space and RNN as a wayto model the dynamics in the latent space. We improve the video generation consistency through temporally-conditional sampling and quality by structuring the latent space with attribute controls; ensuring that attributes can be both inferred and conditioned on during learning/generation. As a result, given attributes and/orthe first frame, our model is able to generate diverse but highly consistent sets ofvideo sequences, accounting for the inherent uncertainty in the prediction task. Experimental results on Chair CAD, Weizmann Human Action, and MIT-Flickr datasets, along with detailed comparison to the state-of-the-art, verify effectiveness of the framework.

##### Abstract (translated by Google)
视频表达高度结构化的视觉数据的时空模式。视频可以被认为受两个因素支配：（i）时间不变（例如，人物身份）或缓慢变化（例如活动），属性引起的外观，编码每帧的持久内容，以及（ii） ）帧间运动或场景动态（例如，编码进行动作的人的进化）。基于这种直觉，我们提出了一个视频生成和未来预测的生成框架。所提出的框架通过将从潜在空间分布顺序绘制的样本解码为完整视频帧来生成视频（短片段）。变分自动编码器（VAEs）被用作对潜在空间和RNN进行编码/解码帧的手段，以此作为对潜在空间动态进行建模的一种方式。我们通过采用属性控制构建潜在空间，通过时间条件采样和质量来提高视频生成的一致性;确保在学习/生成过程中可以推断和限制属性。因此，给定属性和/或第一帧，我们的模型能够生成多样化但高度一致的视频序列集合，解决了预测任务中固有的不确定性。 Chair CAD，Weizmann Human Action和MIT-Flickr数据集的实验结果，以及与最新技术的详细比较，验证了框架的有效性。

##### URL
[https://arxiv.org/abs/1803.08085](https://arxiv.org/abs/1803.08085)

##### PDF
[https://arxiv.org/pdf/1803.08085](https://arxiv.org/pdf/1803.08085)


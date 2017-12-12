---
layout: post
title: "A Deep Recurrent Framework for Cleaning Motion Capture Data"
date: 2017-12-09 12:03:53
categories: arXiv_CV
tags: arXiv_CV Knowledge Relation
author: Utkarsh Mall, G. Roshan Lal, Siddhartha Chaudhuri, Parag Chaudhuri
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep, bidirectional, recurrent framework for cleaning noisy and incomplete motion capture data. It exploits temporal coherence and joint correlations to infer adaptive filters for each joint in each frame. A single model can be trained to denoise a heterogeneous mix of action types, under substantial amounts of noise. A signal that has both noise and gaps is preprocessed with a second bidirectional network that synthesizes missing frames from surrounding context. The approach handles a wide variety of noise types and long gaps, does not rely on knowledge of the noise distribution, and operates in a streaming setting. We validate our approach through extensive evaluations on noise both in joint angles and in joint positions, and show that it improves upon various alternatives.

##### Abstract (translated by Google)
我们提出了一个深入的，双向的，循环的框架来清理噪声和不完整的运动捕捉数据。它利用时间相干性和联合相关来推断每帧中每个关节的自适应滤波器。可以训练单个模型来在相当大的噪声下去噪声混合不同的动作类型。同时具有噪声和间隙的信号通过第二个双向网络进行预处理，合成周围环境的缺失帧。该方法处理各种各样的噪声类型和长时间的差距，不依赖于噪声分布的知识，并且在流式设置中操作。我们通过广泛的关节角度和关节位置的噪声评估验证了我们的方法，并表明它改进了各种选择。

##### URL
[http://arxiv.org/abs/1712.03380](http://arxiv.org/abs/1712.03380)

##### PDF
[http://arxiv.org/pdf/1712.03380](http://arxiv.org/pdf/1712.03380)


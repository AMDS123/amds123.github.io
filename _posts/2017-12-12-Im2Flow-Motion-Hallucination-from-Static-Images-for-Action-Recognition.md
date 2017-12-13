---
layout: post
title: "Im2Flow: Motion Hallucination from Static Images for Action Recognition"
date: 2017-12-12 03:11:34
categories: arXiv_CV
tags: arXiv_CV Face Action_Recognition CNN Prediction Recognition
author: Ruohan Gao, Bo Xiong, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods to recognize actions in static images take the images at their face value, learning the appearances---objects, scenes, and body poses---that distinguish each action class. However, such models are deprived of the rich dynamic structure and motions that also define human activity. We propose an approach that hallucinates the unobserved future motion implied by a single snapshot to help static-image action recognition. The key idea is to learn a prior over short-term dynamics from thousands of unlabeled videos, infer the anticipated optical flow on novel static images, and then train discriminative models that exploit both streams of information. Our main contributions are twofold. First, we devise an encoder-decoder convolutional neural network and a novel optical flow encoding that can translate a static image into an accurate flow map. Second, we show the power of hallucinated flow for recognition, successfully transferring the learned motion into a standard two-stream network for activity recognition. On seven datasets, we demonstrate the power of the approach. It not only achieves state-of-the-art accuracy for dense optical flow prediction, but also consistently enhances recognition of actions and dynamic scenes.

##### Abstract (translated by Google)
现有的识别静态图像中的动作的方法将图像置于其面值上，学习外观 - 对象，场景和身体姿势 - 区分每个动作类别。然而，这样的模型被剥夺了也定义人类活动的丰富的动态结构和动作。我们提出了一种方法，使单个快照隐含的未被察觉的未来运动产生幻觉，以帮助静态图像动作识别。关键的想法是从数以千计的未标记的视频中学习一个超前的短期动态，推断新的静态图像上的预期光流，然后训练利用这两种信息流的辨别模型。我们的主要贡献是双重的。首先，我们设计了一个编码器 - 解码器卷积神经网络和一个新颖的光流编码，可以将静态图像转换成精确的流程图。其次，我们展示了幻觉流的识别力，成功将学习动作转化为标准的双流网络进行活动识别。在七个数据集上，我们展示了这种方法的强大功能。它不仅实现了高密度光流预测的最新精度，而且还不断增强对动作和动态场景的识别。

##### URL
[http://arxiv.org/abs/1712.04109](http://arxiv.org/abs/1712.04109)

##### PDF
[http://arxiv.org/pdf/1712.04109](http://arxiv.org/pdf/1712.04109)


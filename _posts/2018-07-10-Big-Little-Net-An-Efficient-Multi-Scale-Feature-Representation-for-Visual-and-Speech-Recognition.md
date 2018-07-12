---
layout: post
title: "Big-Little Net: An Efficient Multi-Scale Feature Representation for Visual and Speech Recognition"
date: 2018-07-10 20:19:27
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition CNN Recognition
author: Chun-Fu Chen, Quanfu Fan, Neil Mallinar, Tom Sercu, Rogerio Feris
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel Convolutional Neural Network (CNN) architecture for learning multi-scale feature representations with good tradeoffs between speed and accuracy. This is achieved by using a multi-branch network, which has different computational complexity at different branches. Through frequent merging of features from branches at distinct scales, our model obtains multi-scale features while using less computation. The proposed approach demonstrates improvement of model efficiency and performance on both object recognition and speech recognition tasks,using popular architectures including ResNet and ResNeXt. For object recognition, our approach reduces computation by 33% on object recognition while improving accuracy with 0.9%. Furthermore, our model surpasses state-of-the-art CNN acceleration approaches by a large margin in accuracy and FLOPs reduction. On the task of speech recognition, our proposed multi-scale CNNs save 30% FLOPs with slightly better word error rates, showing good generalization across domains.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的卷积神经网络（CNN）架构，用于学习多尺度特征表示，并在速度和精度之间进行良好的权衡。这是通过使用多分支网络实现的，该分支网络在不同分支处具有不同的计算复杂度。通过频繁合并不同尺度分支的特征，我们的模型获得了多尺度特征，同时使用较少的计算。所提出的方法使用包括ResNet和ResNeXt在内的流行架构，证明了对象识别和语音识别任务的模型效率和性能的提高。对于物体识别，我们的方法在物体识别上减少了33％的计算，同时将精度提高了0.9％。此外，我们的模型在精度和FLOP降低方面超过了最先进的CNN加速方法。在语音识别的任务上，我们提出的多尺度CNN节省了30％的FLOP，具有稍好的字错误率，显示出跨域的良好泛化。

##### URL
[http://arxiv.org/abs/1807.03848](http://arxiv.org/abs/1807.03848)

##### PDF
[http://arxiv.org/pdf/1807.03848](http://arxiv.org/pdf/1807.03848)


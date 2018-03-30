---
layout: post
title: "Cracking the cocktail party problem by multi-beam deep attractor network"
date: 2018-03-29 04:42:26
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Zhuo Chen, Jinyu Li, Xiong Xiao, Takuya Yoshioka, Huaming Wang, Zhenghao Wang, Yifan Gong
mathjax: true
---

* content
{:toc}

##### Abstract
While recent progresses in neural network approaches to single-channel speech separation, or more generally the cocktail party problem, achieved significant improvement, their performance for complex mixtures is still not satisfactory. In this work, we propose a novel multi-channel framework for multi-talker separation. In the proposed model, an input multi-channel mixture signal is firstly converted to a set of beamformed signals using fixed beam patterns. For this beamforming, we propose to use differential beamformers as they are more suitable for speech separation. Then each beamformed signal is fed into a single-channel anchored deep attractor network to generate separated signals. And the final separation is acquired by post selecting the separating output for each beams. To evaluate the proposed system, we create a challenging dataset comprising mixtures of 2, 3 or 4 speakers. Our results show that the proposed system largely improves the state of the art in speech separation, achieving 11.5 dB, 11.76 dB and 11.02 dB average signal-to-distortion ratio improvement for 4, 3 and 2 overlapped speaker mixtures, which is comparable to the performance of a minimum variance distortionless response beamformer that uses oracle location, source, and noise information. We also run speech recognition with a clean trained acoustic model on the separated speech, achieving relative word error rate (WER) reduction of 45.76\%, 59.40\% and 62.80\% on fully overlapped speech of 4, 3 and 2 speakers, respectively. With a far talk acoustic model, the WER is further reduced.

##### Abstract (translated by Google)
虽然最近神经网络对单通道语音分离方法的进展，或者更普遍的鸡尾酒会问题取得了显着的改进，但它们在复杂混合物中的性能仍然不令人满意。在这项工作中，我们提出了一种新的多渠道分离的多渠道框架。在所提出的模型中，首先使用固定波束模式将输入多信道混合信号转换成一组波束形成信号。对于这种波束形成，我们建议使用差分波束形成器，因为它们更适合于语音分离。然后，每个波束形成的信号被馈送到单通道锚定深吸引器网络以生成分离的信号。通过选择每个光束的分离输出来获得最终分离。为了评估提出的系统，我们创建了一个具有挑战性的数据集，其中包含2,3或4个扬声器的混合。我们的结果表明，所提出的系统在很大程度上改善了语音分离领域的现状，对于4,3和2重叠的扬声器混合，实现了11.5dB，11.76dB和11.02dB的平均信号与失真比的改善，这与使用oracle位置，源和噪声信息的最小方差无失真响应波束成形器的性能。我们还使用清晰的训练好的声学模型对分离的语音进行语音识别，分别在4,3和2个讲话者的完全重叠语音上分别实现45.76％，59.40％和62.80％的相对误码率（WER）降低。使用远端讲话声学模型，WER进一步降低。

##### URL
[http://arxiv.org/abs/1803.10924](http://arxiv.org/abs/1803.10924)

##### PDF
[http://arxiv.org/pdf/1803.10924](http://arxiv.org/pdf/1803.10924)


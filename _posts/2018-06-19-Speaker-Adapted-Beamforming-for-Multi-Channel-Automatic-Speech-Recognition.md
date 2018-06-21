---
layout: post
title: "Speaker Adapted Beamforming for Multi-Channel Automatic Speech Recognition"
date: 2018-06-19 18:03:33
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Tobias Menne, Ralf Schl&#xfc;ter, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents, in the context of multi-channel ASR, a method to adapt a mask based, statistically optimal beamforming approach to a speaker of interest. The beamforming vector of the statistically optimal beamformer is computed by utilizing speech and noise masks, which are estimated by a neural network. The proposed adaptation approach is based on the integration of the beamformer, which includes the mask estimation network, and the acoustic model of the ASR system. This allows for the propagation of the training error, from the acoustic modeling cost function, all the way through the beamforming operation and through the mask estimation network. By using the results of a first pass recognition and by keeping all other parameters fixed, the mask estimation network can therefore be fine tuned by retraining. Utterances of a speaker of interest can thus be used in a two pass approach, to optimize the beamforming for the speech characteristics of that specific speaker. It is shown that this approach improves the ASR performance of a state-of-the-art multi-channel ASR system on the CHiME-4 data. Furthermore the effect of the adaptation on the estimated speech masks is discussed.

##### Abstract (translated by Google)
本文在多通道ASR的背景下提出了一种基于掩模的统计最优波束形成方法来适应感兴趣的说话者的方法。通过利用由神经网络估计的语音和噪声掩码来计算统计最佳波束形成器的波束形成向量。所提出的自适应方法基于包括掩模估计网络的波束形成器和ASR系统的声学模型的集成。这允许训练误差的传播，从声学建模成本函数，一直到波束形成操作以及通过掩模估计网络。通过使用第一遍识别的结果并保持所有其他参数不变，掩模估计网络因此可以通过再训练进行微调。感兴趣的讲话者的话语因此可以用于双通道方法中，以优化针对该特定讲话者的话音特性的波束形成。结果表明，这种方法在CHiME-4数据上改进了最先进的多通道ASR系统的ASR性能。此外，讨论了适应对估计语音掩码的影响。

##### URL
[http://arxiv.org/abs/1806.07407](http://arxiv.org/abs/1806.07407)

##### PDF
[http://arxiv.org/pdf/1806.07407](http://arxiv.org/pdf/1806.07407)


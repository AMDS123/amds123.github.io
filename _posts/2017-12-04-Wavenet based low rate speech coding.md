---
layout: post
title:  'Wavenet based low rate speech coding'
date:   2017-12-05 18:45:06
categories: SD
tags: SD
author: W. Bastiaan Kleijn, Felicia S. C. Lim, Alejandro Luebs, Jan Skoglund, Florian Stimberg, Quan Wang, Thomas C. Walters
---

* content
{:toc}

##### Abstract
Traditional parametric coding of speech facilitates low rate but provides poor reconstruction quality because of the inadequacy of the model used. We describe how a WaveNet generative speech model can be used to generate high quality speech from the bit stream of a standard parametric coder operating at 2.4 kb/s. We compare this parametric coder with a waveform coder based on the same generative model and show that approximating the signal waveform incurs a large rate penalty. Our experiments confirm the high performance of the WaveNet based coder and show that the speech produced by the system is able to additionally perform implicit bandwidth extension and does not significantly impair recognition of the original speaker for the human listener, even when that speaker has not been used during the training of the generative model.

##### Abstract (translated by Google)
传统的语音参数编码有利于低速率，但由于所用模型的不足，重建质量差。我们描述了如何使用WaveNet生成语音模型从2.4 kb / s的标准参数编码器的比特流中生成高质量的语音。我们将这个参数编码器与基于相同生成模型的波形编码器进行比较，并且显示近似信号波形导致较大的费率损失。我们的实验证实了基于WaveNet的编码器的高性能，并且表明由系统产生的语音能够附加地执行隐式带宽扩展，并且不会显着地损害对于听者的原始讲话者的识别，即使当讲话者还没有在生成模型的训练中使用。


---
layout: post
title: "Phase reconstruction from amplitude spectrograms based on von-Mises-distribution deep neural network"
date: 2018-07-10 04:14:55
categories: arXiv_SD
tags: arXiv_SD
author: Shinnosuke Takamichi, Yuki Saito, Norihiro Takamune, Daichi Kitamura, Hiroshi Saruwatari
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a deep neural network (DNN)-based phase reconstruction from amplitude spectrograms. In audio signal and speech processing, the amplitude spectrogram is often used for processing, and the corresponding phase spectrogram is reconstructed from the amplitude spectrogram on the basis of the Griffin-Lim method. However, the Griffin-Lim method causes unnatural artifacts in synthetic speech. Addressing this problem, we introduce the von-Mises-distribution DNN for phase reconstruction. The DNN is a generative model having the von Mises distribution that can model distributions of a periodic variable such as a phase, and the model parameters of the DNN are estimated on the basis of the maximum likelihood criterion. Furthermore, we propose a group-delay loss for DNN training to make the predicted group delay close to a natural group delay. The experimental results demonstrate that 1) the trained DNN can predict group delay accurately more than phases themselves, and 2) our phase reconstruction methods achieve better speech quality than the conventional Griffin-Lim method.

##### Abstract (translated by Google)
本文提出了一种基于振动谱的深度神经网络（DNN）相位重建。在音频信号和语音处理中，幅度谱图通常用于处理，并且基于Griffin-Lim方法从幅度谱图重建相应的相位谱图。然而，Griffin-Lim方法在合成语音中导致不自然的伪影。为解决这个问题，我们引入了用于相位重构的von-Mises分布DNN。 DNN是具有von Mises分布的生成模型，其可以对诸如阶段的周期变量的分布进行建模，并且基于最大似然准则来估计DNN的模型参数。此外，我们提出DNN训练的群延迟损失，以使预测群延迟接近自然群延迟。实验结果表明：1）训练好的DNN可以比相位本身更准确地预测群延迟; 2）我们的相位重建方法比传统的Griffin-Lim方法获得更好的语音质量。

##### URL
[http://arxiv.org/abs/1807.03474](http://arxiv.org/abs/1807.03474)

##### PDF
[http://arxiv.org/pdf/1807.03474](http://arxiv.org/pdf/1807.03474)


---
layout: post
title: "Monaural source enhancement maximizing source-to-distortion ratio via automatic differentiation"
date: 2018-06-15 02:38:40
categories: arXiv_SD
tags: arXiv_SD
author: Hiroaki Nakajima, Yu Takahashi, Kazunobu Kondo, Yuji Hisaminato
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep neural network (DNN) has made a breakthrough in monaural source enhancement. Through a training step by using a large amount of data, DNN estimates a mapping between mixed signals and clean signals. At this time, we use an objective function that numerically expresses the quality of a mapping by DNN. In the conventional methods, L1 norm, L2 norm, and Itakura-Saito divergence are often used as objective functions. Recently, an objective function based on short-time objective intelligibility (STOI) has also been proposed. However, these functions only indicate similarity between the clean signal and the estimated signal by DNN. In other words, they do not show the quality of noise reduction or source enhancement. Motivated by the fact, this paper adopts signal-to-distortion ratio (SDR) as the objective function. Since SDR virtually shows signal-to-noise ratio (SNR), maximizing SDR solves the above problem. The experimental results revealed that the proposed method achieved better performance than the conventional methods.

##### Abstract (translated by Google)
最近，深度神经网络（DNN）在单声源增强方面取得了突破。通过使用大量数据的训练步骤，DNN估计混合信号和干净信号之间的映射。目前，我们使用一个目标函数来数值地表达DNN映射的质量。在常规方法中，L1范数，L2范数和Itakura-Saito散度经常用作目标函数。最近，还提出了基于短时客观可懂度（STOI）的目标函数。但是，这些函数仅表示干净信号和DNN估计信号之间的相似性。换句话说，它们不显示降噪或声源增强的质量。受事实驱动，本文采用信号失真比（SDR）作为目标函数。由于SDR实际上表现出信噪比（SNR），所以SDR最大化解决了上述问题。实验结果表明，该方法比传统方法获得了更好的性能。

##### URL
[http://arxiv.org/abs/1806.05791](http://arxiv.org/abs/1806.05791)

##### PDF
[http://arxiv.org/pdf/1806.05791](http://arxiv.org/pdf/1806.05791)


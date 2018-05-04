---
layout: post
title: "End-to-End Speech Separation with Unfolded Iterative Phase Reconstruction"
date: 2018-04-26 13:14:22
categories: arXiv_CL
tags: arXiv_CL Deep_Learning
author: Zhong-Qiu Wang, Jonathan Le Roux, DeLiang Wang, John R. Hershey
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an end-to-end approach for single-channel speaker-independent multi-speaker speech separation, where time-frequency (T-F) masking, the short-time Fourier transform (STFT), and its inverse are represented as layers within a deep network. Previous approaches, rather than computing a loss on the reconstructed signal, used a surrogate loss based on the target STFT magnitudes. This ignores reconstruction error introduced by phase inconsistency. In our approach, the loss function is directly defined on the reconstructed signals, which are optimized for best separation. In addition, we train through unfolded iterations of a phase reconstruction algorithm, represented as a series of STFT and inverse STFT layers. While mask values are typically limited to lie between zero and one for approaches using the mixture phase for reconstruction, this limitation is less relevant if the estimated magnitudes are to be used together with phase reconstruction. We thus propose several novel activation functions for the output layer of the T-F masking, to allow mask values beyond one. On the publicly-available wsj0-2mix dataset, our approach achieves state-of-the-art 12.6 dB scale-invariant signal-to-distortion ratio (SI-SDR) and 13.1 dB SDR, revealing new possibilities for deep learning based phase reconstruction and representing a fundamental progress towards solving the notoriously-hard cocktail party problem.

##### Abstract (translated by Google)
本文提出了一种端到端的单通道扬声器无关多讲话者语音分离的方法，其中时频（TF）掩模，短时傅里叶变换（STFT）及其反转表示为层内一个深度网络。先前的方法，而不是计算重建信号的损失，使用基于目标STFT量值的替代损失。这忽略了由相位不一致引起的重建误差。在我们的方法中，损失函数直接定义在重建信号上，这些信号经过优化以获得最佳分离效果。另外，我们通过展开迭代的相位重构算法来训练，表示为一系列STFT和逆STFT层。尽管对于使用混合相位进行重建的方法，掩模值通常限于介于0和1之间，但如果估计的幅度与相位重构一起使用，则此限制较不相关。因此，我们为T-F掩模的输出层提出了几种新颖的激活函数，以允许掩模值超过1。在公开的wsj0-2mix数据集上，我们的方法实现了最先进的12.6 dB尺度不变信号与失真比（SI-SDR）和13.1 dB SDR，揭示了基于深度学习的相位重构的新可能性代表了解决臭名昭着的鸡尾酒会问题的根本性进展。

##### URL
[https://arxiv.org/abs/1804.10204](https://arxiv.org/abs/1804.10204)

##### PDF
[https://arxiv.org/pdf/1804.10204](https://arxiv.org/pdf/1804.10204)


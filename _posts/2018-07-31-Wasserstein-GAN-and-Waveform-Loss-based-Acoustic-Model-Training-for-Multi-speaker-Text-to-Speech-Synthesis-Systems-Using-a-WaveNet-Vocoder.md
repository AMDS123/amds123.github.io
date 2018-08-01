---
layout: post
title: "Wasserstein GAN and Waveform Loss-based Acoustic Model Training for Multi-speaker Text-to-Speech Synthesis Systems Using a WaveNet Vocoder"
date: 2018-07-31 06:38:54
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN RNN
author: Yi Zhao, Shinji Takaki, Hieu-Thi Luong, Junichi Yamagishi, Daisuke Saito, Nobuaki Minematsu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent neural networks such as WaveNet and sampleRNN that learn directly from speech waveform samples have achieved very high-quality synthetic speech in terms of both naturalness and speaker similarity even in multi-speaker text-to-speech synthesis systems. Such neural networks are being used as an alternative to vocoders and hence they are often called neural vocoders. The neural vocoder uses acoustic features as local condition parameters, and these parameters need to be accurately predicted by another acoustic model. However, it is not yet clear how to train this acoustic model, which is problematic because the final quality of synthetic speech is significantly affected by the performance of the acoustic model. Significant degradation happens, especially when predicted acoustic features have mismatched characteristics compared to natural ones. In order to reduce the mismatched characteristics between natural and generated acoustic features, we propose frameworks that incorporate either a conditional generative adversarial network (GAN) or its variant, Wasserstein GAN with gradient penalty (WGAN-GP), into multi-speaker speech synthesis that uses the WaveNet vocoder. We also extend the GAN frameworks and use the discretized mixture logistic loss of a well-trained WaveNet in addition to mean squared error and adversarial losses as parts of objective functions. Experimental results show that acoustic models trained using the WGAN-GP framework using back-propagated discretized-mixture-of-logistics (DML) loss achieves the highest subjective evaluation scores in terms of both quality and speaker similarity.

##### Abstract (translated by Google)
即使在多扬声器文本到语音合成系统中，最近直接从语音波形样本学习的诸如WaveNet和sampleRNN的神经网络已经在自然性和说话者相似性方面实现了非常高质量的合成语音。这种神经网络被用作声码器的替代品，因此它们通常被称为神经声码器。神经声码器使用声学特征作为局部条件参数，并且这些参数需要由另一声学模型准确地预测。然而，目前尚不清楚如何训练这种声学模型，这是有问题的，因为合成语音的最终质量受到声学模型性能的显着影响。发生显着的退化，特别是当预测的声学特征与自然特征相比具有不匹配的特征时。为了减少自然和生成的声学特征之间的不匹配特征，我们提出了将条件生成对抗网络（GAN）或其变体Wasserstein GAN与梯度惩罚（WGAN-GP）结合到多说话者语音合成中的框架。使用WaveNet声码器。我们还扩展了GAN框架，并使用经过良好训练的WaveNet的离散混合物后勤损失以及均方误差和对抗性损失作为目标函数的一部分。实验结果表明，使用WGAN-GP框架使用反向传播离散化物流混合（DML）损失训练的声学模型在质量和说话人相似性方面达到了最高的主观评价分数。

##### URL
[http://arxiv.org/abs/1807.11679](http://arxiv.org/abs/1807.11679)

##### PDF
[http://arxiv.org/pdf/1807.11679](http://arxiv.org/pdf/1807.11679)


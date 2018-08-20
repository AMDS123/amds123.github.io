---
layout: post
title: "Adversarial Attacks Against Automatic Speech Recognition Systems via Psychoacoustic Hiding"
date: 2018-08-16 20:00:47
categories: arXiv_SD
tags: arXiv_SD Adversarial Face Speech_Recognition Recognition
author: Lea Sch&#xf6;nherr, Katharina Kohls, Steffen Zeiler, Thorsten Holz, Dorothea Kolossa
mathjax: true
---

* content
{:toc}

##### Abstract
Voice interfaces are becoming accepted widely as input methods for a diverse set of devices. This development is driven by rapid improvements in automatic speech recognition (ASR), which now performs on par with human listening in many tasks. These improvements base on an ongoing evolution of DNNs as the computational core of ASR. However, recent research results show that DNNs are vulnerable to adversarial perturbations, which allow attackers to force the transcription into a malicious output. 
 In this paper, we introduce a new type of adversarial examples based on psychoacoustic hiding. Our attack exploits the characteristics of DNN-based ASR systems, where we extend the original analysis procedure by an additional backpropagation step. We use this backpropagation to learn the degrees of freedom for the adversarial perturbation of the input signal, i.e., we apply a psychoacoustic model and manipulate the acoustic signal below the thresholds of human perception. To further minimize the perceptibility of the perturbations, we use forced alignment to find the best fitting temporal alignment between the original audio sample and the malicious target transcription. These extensions allow us to embed an arbitrary audio input with a malicious voice command that is then transcribed by the ASR system, with the audio signal remaining barely distinguishable from the original signal. In an experimental evaluation, we attack the state-of-the-art speech recognition system Kaldi and determine the best performing parameter and analysis setup for different types of input. Our results show that we are successful in up to 98% of cases with a computational effort of fewer than two minutes for a ten-second audio file. Based on user studies, we found that none of our target transcriptions were audible to human listeners, who still understand the original speech content with unchanged accuracy.

##### Abstract (translated by Google)
语音接口正逐渐被广泛接受作为各种设备的输入方法。这种发展是由自动语音识别（ASR）的快速改进推动的，现在它在许多任务中与人类听力相当。这些改进基于DNN作为ASR的计算核心的持续演进。然而，最近的研究结果表明，DNN容易受到对抗性扰动的影响，这使得攻击者可以强迫转录成为恶意输出。
 在本文中，我们介绍了一种基于心理声学隐藏的新型对抗实例。我们的攻击利用了基于DNN的ASR系统的特性，我们通过额外的反向传播步骤扩展了原始分析过程。我们使用这种反向传播来学习输入信号的对抗扰动的自由度，即，我们应用心理声学模型并且将声学信号操纵到低于人类感知的阈值。为了进一步最小化扰动的可感知性，我们使用强制对齐来找到原始音频样本和恶意目标转录之间的最佳拟合时间对齐。这些扩展允许我们使用恶意语音命令嵌入任意音频输入，然后由ASR系统转录，音频信号几乎与原始信号无法区分。在实验评估中，我们攻击最先进的语音识别系统Kaldi，并确定针对不同类型输入的最佳性能参数和分析设置。我们的结果表明，对于10秒音频文件，我们在高达98％的情况下成功，计算工作量少于两分钟。根据用户研究，我们发现我们的目标转录都不能被人类听众听到，他们仍然能够准确地理解原始语音内容。

##### URL
[http://arxiv.org/abs/1808.05665](http://arxiv.org/abs/1808.05665)

##### PDF
[http://arxiv.org/pdf/1808.05665](http://arxiv.org/pdf/1808.05665)


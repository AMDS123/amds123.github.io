---
layout: post
title: "Local Gradients Smoothing: Defense against localized adversarial attacks"
date: 2018-07-03 14:48:05
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Inference Classification Deep_Learning
author: Muzammal Naseer, Salman Khan, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have shown vulnerability to adversarial attacks, i.e., carefully perturbed inputs designed to mislead the network at inference time. Recently introduced localized attacks, LaVAN and Adversarial patch, posed a new challenge to deep learning security by adding adversarial noise only within a specific region without affecting the salient objects in an image. Driven by the observation that such attacks introduce concentrated high-frequency changes at a particular image location, we have developed an effective method to estimate noise location in gradient domain and transform those high activation regions caused by adversarial noise in image domain while having minimal effect on the salient object that is important for correct classification. Our proposed Local Gradients Smoothing (LGS) scheme achieves this by regularizing gradients in the estimated noisy region before feeding the image to DNN for inference. We have shown the effectiveness of our method in comparison to other defense methods including JPEG compression, Total Variance Minimization (TVM) and Feature squeezing on ImageNet dataset. In addition, we systematically study the robustness of the proposed defense mechanism against Back Pass Differentiable Approximation (BPDA), a state of the art attack recently developed to break defenses that transform an input sample to minimize the adversarial effect. Compared to other defense mechanisms, LGS is by far the most resistant to BPDA in localized adversarial attack setting.

##### Abstract (translated by Google)
深度神经网络（DNN）已显示出对抗性攻击的脆弱性，即精心扰动的输入，旨在在推理时误导网络。最近引入的局部攻击，LaVAN和Adversarial补丁，通过仅在特定区域内添加对抗性噪声而不影响图像中的显着对象，对深度学习安全性提出了新的挑战。在观察到这种攻击在特定图像位置引入集中的高频变化的驱动下，我们开发了一种有效的方法来估计梯度域中的噪声位置，并转换由图像域中的对抗性噪声引起的那些高激活区域，同时对对于正确分类很重要的显着对象。我们提出的局部梯度平滑（LGS）方案通过在将图像馈送到DNN用于推断之前规范估计的噪声区域中的梯度来实现这一点。我们已经证明了我们的方法与其他防御方法相比的有效性，包括JPEG压缩，总方差最小化（TVM）和ImageNet数据集上的特征压缩。此外，我们系统地研究了提出的反向通过可微分近似（BPDA）防御机制的鲁棒性，BPDA是最近发展起来的一种先进技术，用于打破改变输入样本以最小化对抗效应的防御。与其他防御机制相比，LGS在本地化对抗性攻击设置中是迄今为止对BPDA最具抵抗力的。

##### URL
[https://arxiv.org/abs/1807.01216](https://arxiv.org/abs/1807.01216)

##### PDF
[https://arxiv.org/pdf/1807.01216](https://arxiv.org/pdf/1807.01216)


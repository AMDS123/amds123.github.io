---
layout: post
title: "Interpretable Learning for Self-Driving Cars by Visualizing Causal Attention"
date: 2017-03-30 18:37:49
categories: arXiv_CV
tags: arXiv_CV Attention
author: Jinkyu Kim, John Canny
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural perception and control networks are likely to be a key component of self-driving vehicles. These models need to be explainable - they should provide easy-to-interpret rationales for their behavior - so that passengers, insurance companies, law enforcement, developers etc., can understand what triggered a particular behavior. Here we explore the use of visual explanations. These explanations take the form of real-time highlighted regions of an image that causally influence the network's output (steering control). Our approach is two-stage. In the first stage, we use a visual attention model to train a convolution network end-to-end from images to steering angle. The attention model highlights image regions that potentially influence the network's output. Some of these are true influences, but some are spurious. We then apply a causal filtering step to determine which input regions actually influence the output. This produces more succinct visual explanations and more accurately exposes the network's behavior. We demonstrate the effectiveness of our model on three datasets totaling 16 hours of driving. We first show that training with attention does not degrade the performance of the end-to-end network. Then we show that the network causally cues on a variety of features that are used by humans while driving.

##### Abstract (translated by Google)
深度神经感知和控制网络很可能是自驾车辆的关键组成部分。这些模型需要解释 - 他们应该为他们的行为提供易于理解的理由 - 以便乘客，保险公司，执法人员，开发人员等能够理解是什么触发了特定的行为。在这里，我们探讨使用视觉解释。这些解释采用实时突出显示的图像区域的形式，因此影响网络的输出（转向控制）。我们的方法是两个阶段。在第一阶段，我们使用视觉注意模型来从图像到转向角度端到端地训练卷积网络。注意模型突出显示可能影响网络输出的图像区域。其中有些是真实的影响，但有些是虚假的。然后，我们应用因果过滤步骤来确定哪些输入区域实际影响输出。这产生了更简洁的视觉解释，更准确地揭露了网络的行为。我们证明了我们的模型在总共16小时的驾驶的三个数据集上的有效性。我们首先表明，注意训练不会降低端到端网络的性能。然后，我们显示网络因果关系提示驾驶时人类使用的各种功能。

##### URL
[https://arxiv.org/abs/1703.10631](https://arxiv.org/abs/1703.10631)

##### PDF
[https://arxiv.org/pdf/1703.10631](https://arxiv.org/pdf/1703.10631)


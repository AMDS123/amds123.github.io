---
layout: post
title: "Cascade Residual Learning: A Two-stage Convolutional Neural Network for Stereo Matching"
date: 2018-07-30 17:01:28
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jiahao Pang, Wenxiu Sun, Jimmy SJ. Ren, Chengxi Yang, Qiong Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Leveraging on the recent developments in convolutional neural networks (CNNs), matching dense correspondence from a stereo pair has been cast as a learning problem, with performance exceeding traditional approaches. However, it remains challenging to generate high-quality disparities for the inherently ill-posed regions. To tackle this problem, we propose a novel cascade CNN architecture composing of two stages. The first stage advances the recently proposed DispNet by equipping it with extra up-convolution modules, leading to disparity images with more details. The second stage explicitly rectifies the disparity initialized by the first stage; it couples with the first-stage and generates residual signals across multiple scales. The summation of the outputs from the two stages gives the final disparity. As opposed to directly learning the disparity at the second stage, we show that residual learning provides more effective refinement. Moreover, it also benefits the training of the overall cascade network. Experimentation shows that our cascade residual learning scheme provides state-of-the-art performance for matching stereo correspondence. By the time of the submission of this paper, our method ranks first in the KITTI 2015 stereo benchmark, surpassing the prior works by a noteworthy margin.

##### Abstract (translated by Google)
利用卷积神经网络（CNN）的最新发展，匹配来自立体声对的密集对应已被视为学习问题，其性能超过传统方法。然而，为本质上不适合的地区产生高质量的差异仍然具有挑战性。为了解决这个问题，我们提出了一个新的级联CNN架构，由两个阶段组成。第一阶段通过为其提供额外的上卷积模块来推进最近提出的DispNet，从而产生具有更多细节的视差图像。第二阶段明确纠正了第一阶段初始化的差异;它与第一阶段耦合并在多个尺度上产生残余信号。两个阶段的输出总和给出了最终的差异。与直接学习第二阶段的差异相反，我们表明残差学习提供了更有效的改进。此外，它还有利于整个级联网络的培训。实验表明，我们的级联残差学习方案为匹配立体声对应提供了最先进的性能。截至本文提交时，我们的方法在KITTI 2015立体声基准测试中排名第一，超过之前的作品值得注意。

##### URL
[http://arxiv.org/abs/1708.09204](http://arxiv.org/abs/1708.09204)

##### PDF
[http://arxiv.org/pdf/1708.09204](http://arxiv.org/pdf/1708.09204)


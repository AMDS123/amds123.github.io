---
layout: post
title: "Cascade Residual Learning: A Two-stage Convolutional Neural Network for Stereo Matching"
date: 2017-08-30 10:20:37
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
利用卷积神经网络（CNNs）近期的发展，匹配来自立体声对的密集对应已经成为一个学习问题，其性能超过了传统方法。但是，本质上不适应地区的高质量差距仍然是一个挑战。针对这个问题，我们提出了一个由两个阶段组成的新型级联CNN体系结构。第一阶段通过为最近提出的DispNet提供额外的上卷积模块，从而导出更多细节的差异图像。第二阶段明确整顿第一阶段初始化的差距，它与第一阶段耦合并在多个尺度上产生残余信号。两阶段产出的总和给出了最后的差距。与直接了解第二阶段的差距相反，我们表明残差学习提供了更有效的细化。此外，它也有利于整体级联网络的培训。实验表明，我们的级联残留学习方案为匹配立体声对应提供了最先进的性能。截至本文提交时，我们的方法在KITTI 2015立体声基准测试中排名第一，超过了以前的作品，值得注意的是保证金。

##### URL
[https://arxiv.org/abs/1708.09204](https://arxiv.org/abs/1708.09204)

##### PDF
[https://arxiv.org/pdf/1708.09204](https://arxiv.org/pdf/1708.09204)


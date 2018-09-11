---
layout: post
title: "Using phase instead of optical flow for action recognition"
date: 2018-09-10 12:07:17
categories: arXiv_CV
tags: arXiv_CV Tracking Action_Recognition Recognition
author: Omar Hommos, Silvia L. Pintea, Pascal S.M. Mettes, Jan C. van Gemert
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, the most common motion representation for action recognition is optical flow. Optical flow is based on particle tracking which adheres to a Lagrangian perspective on dynamics. In contrast to the Lagrangian perspective, the Eulerian model of dynamics does not track, but describes local chances. For video, an Eulerian phase-based motion representation, using complex steerable filters, has been successfully employed recently for motion magnification and video frame interpolation. Inspired by these previous works, here, we proposes learning Eulerian motion representations in a deep architecture for action recognition. We learn filters in the complex domain in an end-to-end manner. We design these complex filters to resemble complex Gabor filters, typically employed for phase-information extraction. We propose a phase-information extraction module, based on these complex filters, that can be used in any network architecture for extracting Eulerian representations. We experimentally analyze the added value of Eulerian motion representations, as extracted by our proposed phase extraction module, and compare with existing motion representations based on optical flow, on the UCF101 dataset.

##### Abstract (translated by Google)
目前，用于动作识别的最常见的运动表示是光流。光流是基于粒子跟踪的，它遵循拉格朗日的动力学观点。与拉格朗日观点相反，欧拉动力学模型不跟踪，但描述了当地的机会。对于视频，使用复数可控滤波器的欧拉基于相位的运动表示最近已成功用于运动放大和视频帧插值。受这些先前作品的启发，在这里，我们提出了在深层体系结构中学习欧拉运动表示以进行动作识别。我们以端到端的方式学习复杂域中的过滤器。我们将这些复杂滤波器设计成类似复杂的Gabor滤波器，通常用于相位信息提取。我们提出了一种基于这些复杂滤波器的相位信息提取模块，可以在任何网络架构中用于提取欧拉表示。我们通过实验分析欧拉运动表示的附加值，由我们提出的相位提取模块提取，并与UCF101数据集上基于光流的现有运动表示进行比较。

##### URL
[http://arxiv.org/abs/1809.03258](http://arxiv.org/abs/1809.03258)

##### PDF
[http://arxiv.org/pdf/1809.03258](http://arxiv.org/pdf/1809.03258)


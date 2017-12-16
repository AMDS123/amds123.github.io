---
layout: post
title: "Object-Extent Pooling for Weakly Supervised Single-Shot Localization"
date: 2017-07-19 16:10:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Weakly_Supervised Face Inference Detection
author: Amogh Gudi, Nicolai van Rosmalen, Marco Loog, Jan van Gemert
mathjax: true
---

* content
{:toc}

##### Abstract
In the face of scarcity in detailed training annotations, the ability to perform object localization tasks in real-time with weak-supervision is very valuable. However, the computational cost of generating and evaluating region proposals is heavy. We adapt the concept of Class Activation Maps (CAM) into the very first weakly-supervised 'single-shot' detector that does not require the use of region proposals. To facilitate this, we propose a novel global pooling technique called Spatial Pyramid Averaged Max (SPAM) pooling for training this CAM-based network for object extent localisation with only weak image-level supervision. We show this global pooling layer possesses a near ideal flow of gradients for extent localization, that offers a good trade-off between the extremes of max and average pooling. Our approach only requires a single network pass and uses a fast-backprojection technique, completely omitting any region proposal steps. To the best of our knowledge, this is the first approach to do so. Due to this, we are able to perform inference in real-time at 35fps, which is an order of magnitude faster than all previous weakly supervised object localization frameworks.

##### Abstract (translated by Google)
在详细的培训注释缺乏的情况下，以弱监督实时执行对象本地化任务的能力是非常有价值的。然而，生成和评估地区建议的计算成本很高。我们将阶级激活图（CAM）的概念调整为第一个弱监督的“单发”探测器，不需要使用区域提案。为了促进这一点，我们提出了一种称为空间金字塔平均最大（SPAM）池的新颖的全球池技术，用于训练这个基于CAM的网络对象范围的定位，只有弱的图像水平的监督。我们展示了这个全局池化层具有近似理想的流程梯度定位，在极大值和平均汇集之间提供了一个很好的折衷。我们的方法只需要一个网络传递，并使用快速反投影技术，完全省略了任何区域提案步骤。据我们所知，这是第一个这样做的方法。由于这个原因，我们能够以35fps的速度进行实时推断，这比以前的所有弱监督的对象定位框架要快一个数量级。

##### URL
[https://arxiv.org/abs/1707.06180](https://arxiv.org/abs/1707.06180)

##### PDF
[https://arxiv.org/pdf/1707.06180](https://arxiv.org/pdf/1707.06180)


---
layout: post
title: "UnrealStereo: Controlling Hazardous Factors to Analyze Stereo Vision"
date: 2018-09-06 12:08:22
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Yi Zhang, Weichao Qiu, Qi Chen, Xiaolin Hu, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
A reliable stereo algorithm is critical for many robotics applications. But textureless and specular regions can easily cause failure by making feature matching difficult. Understanding whether an algorithm is robust to these hazardous regions is important. Although many stereo benchmarks have been developed to evaluate performance, it is hard to quantify the effect of hazardous regions in real images because the location and severity of these regions are unknown. In this paper, we develop a synthetic image generation tool enabling to control hazardous factors, such as making objects more specular or transparent, to produce hazardous regions at different degrees. The densely controlled sampling strategy in virtual worlds enables to effectively stress test stereo algorithms by varying the types and degrees of the hazard. We generate a large synthetic image dataset with automatically computed hazardous regions and analyze algorithms on these regions. The observations from synthetic images are further validated by annotating hazardous regions in real-world datasets Middlebury and KITTI (which gives a sparse sampling of the hazards). Our synthetic image generation tool is based on a game engine Unreal Engine 4 and will be open-source along with the virtual scenes in our experiments. Many publicly available realistic game contents can be used by our tool to provide an enormous resource for development and evaluation of algorithms.

##### Abstract (translated by Google)
可靠的立体算法对于许多机器人应用至关重要。但是无纹理和镜面反射区域很容易通过使特征匹配变得困难而导致失败。了解算法是否对这些危险区域具有鲁棒性非常重要。尽管已经开发了许多立体基准来评估性能，但是很难量化实际图像中危险区域的影响，因为这些区域的位置和严重性是未知的。在本文中，我们开发了一种合成图像生成工具，可以控制危险因素，例如使物体更具镜面性或透明度，从而产生不同程度的危险区域。虚拟世界中的密集控制采样策略能够通过改变危险的类型和程度来有效地对立体算法进行压力测试。我们生成一个大型合成图像数据集，其中包含自动计算的危险区域并分析这些区域的算法。合成图像的观察结果通过在现实世界数据集Middlebury和KITTI（对危险进行稀疏抽样）中注释危险区域进一步验证。我们的合成图像生成工具基于游戏引擎虚幻引擎4，并将在我们的实验中与开源一起使用虚拟场景。我们的工具可以使用许多公开可用的真实游戏内容来为算法的开发和评估提供巨大的资源。

##### URL
[http://arxiv.org/abs/1612.04647](http://arxiv.org/abs/1612.04647)

##### PDF
[http://arxiv.org/pdf/1612.04647](http://arxiv.org/pdf/1612.04647)


---
layout: post
title: "Stacked Denoising Autoencoders and Transfer Learning for Immunogold Particles Detection and Recognition"
date: 2017-12-07 19:28:05
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Detection Recognition
author: Ricardo Gamelas Sousa, Jorge M. Santos, Lu&#xed;s M. Silva, Lu&#xed;s A. Alexandre, Tiago Esteves, Sara Rocha, Paulo Monjardino, Joaquim Marques de S&#xe1;, Francisco Figueiredo, Pedro Quelhas
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a system for the detection of immunogold particles and a Transfer Learning (TL) framework for the recognition of these immunogold particles. Immunogold particles are part of a high-magnification method for the selective localization of biological molecules at the subcellular level only visible through Electron Microscopy. The number of immunogold particles in the cell walls allows the assessment of the differences in their compositions providing a tool to analise the quality of different plants. For its quantization one requires a laborious manual labeling (or annotation) of images containing hundreds of particles. The system that is proposed in this paper can leverage significantly the burden of this manual task. 
 For particle detection we use a LoG filter coupled with a SDA. In order to improve the recognition, we also study the applicability of TL settings for immunogold recognition. TL reuses the learning model of a source problem on other datasets (target problems) containing particles of different sizes. The proposed system was developed to solve a particular problem on maize cells, namely to determine the composition of cell wall ingrowths in endosperm transfer cells. This novel dataset as well as the code for reproducing our experiments is made publicly available. 
 We determined that the LoG detector alone attained more than 84\% of accuracy with the F-measure. Developing immunogold recognition with TL also provided superior performance when compared with the baseline models augmenting the accuracy rates by 10\%.

##### Abstract (translated by Google)
在本文中，我们提出了免疫金颗粒的检测系统和用于识别这些免疫金颗粒的转移学习（TL）框架。免疫金颗粒是用于通过电子显微镜仅可见的亚细胞水​​平上选择性定位生物分子的高倍率方法的一部分。细胞壁中免疫金颗粒的数量允许评估它们组成的差异，从而提供分析不同植物质量的工具。对于量化，需要对包含数百个粒子的图像进行费力的手动标注（或注释）。本文提出的系统可以显着减轻本手册任务的负担。
 对于粒子检测，我们使用一个与SDA耦合的LoG滤波器。为了提高识别率，我们还研究了TL设置对免疫金识别的适用性。 TL在包含不同大小的粒子的其他数据集（目标问题）上重用源问题的学习模型。所提出的系统是为了解决玉米细胞的特定问题而开发的，即确定胚乳转移细胞中细胞壁向内生长的组成。这个新颖的数据集以及用于复制我们的实验的代码已公开发布。
 我们确定单独的LoG探测器获得超过84％的精度与F-措施。与基线模型相比，利用TL开发免疫金识别也提供了优越的性能，将准确率提高了10％。

##### URL
[http://arxiv.org/abs/1712.02824](http://arxiv.org/abs/1712.02824)

##### PDF
[http://arxiv.org/pdf/1712.02824](http://arxiv.org/pdf/1712.02824)


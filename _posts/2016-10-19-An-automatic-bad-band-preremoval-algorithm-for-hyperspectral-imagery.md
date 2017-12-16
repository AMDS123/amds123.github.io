---
layout: post
title: "An automatic bad band preremoval algorithm for hyperspectral imagery"
date: 2016-10-19 09:31:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Luyan Ji, Xiurui Geng, Yongchao Zhao, Fuxiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
For most hyperspectral remote sensing applications, removing bad bands, such as water absorption bands, is a required preprocessing step. Currently, the commonly applied method is by visual inspection, which is very time-consuming and it is easy to overlook some noisy bands. In this study, we find an inherent connection between target detection algorithms and the corrupted band removal. As an example, for the matched filter (MF), which is the most widely used target detection method for hyperspectral data, we present an automatic MF-based algorithm for bad band identification. The MF detector is a filter vector, and the resulting filter output is the sum of all bands weighted by the MF coefficients. Therefore, we can identify bad bands only by using the MF filter vector itself, the absolute value of whose entry accounts for the importance of each band for the target detection. For a specific target of interest, the bands with small MF weights correspond to the noisy or bad ones. Based on this fact, we develop an automatic bad band preremoval algorithm by utilizing the average absolute value of MF weights for multiple targets within a scene. Experiments with three well known hyperspectral datasets show that our method can always identify the water absorption and other low signal-to-noise (SNR) bands that are usually chosen as bad bands manually.

##### Abstract (translated by Google)
对于大多数高光谱遥感应用来说，去除诸如吸水带等不良波段是所需的预处理步骤。目前常用的方法是视觉检测，非常耗时，而且容易忽略一些噪声带。在这项研究中，我们发现目标检测算法和损坏带去除之间的内在联系。作为一个例子，对于高光谱数据中使用最广泛的目标检测方法匹配滤波器（MF），我们提出了一个自动的基于MF的算法来处理坏谱带。 MF检测器是一个滤波器矢量，得到的滤波器输出是由MF系数加权的所有频带的总和。因此，我们只能通过使用MF滤波器矢量本身来识别坏波段，其入口的绝对值说明了每个波段对于目标检测的重要性。对于一个特定的感兴趣的目标，具有小MF权重的频带对应于嘈杂或不好的频带。基于这个事实，我们利用场景中多个目标的MF加权平均绝对值，开发了一种自动坏带预除算法。使用三个众所周知的高光谱数据集进行的实验表明，我们的方法总是可以识别通常被手动选择为坏谱带的吸水率和其他低信噪比（SNR）谱带。

##### URL
[https://arxiv.org/abs/1610.05929](https://arxiv.org/abs/1610.05929)

##### PDF
[https://arxiv.org/pdf/1610.05929](https://arxiv.org/pdf/1610.05929)


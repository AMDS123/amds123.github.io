---
layout: post
title: "Fast object detection for use onboard satellites"
date: 2003-01-30 15:25:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Martin Bange (1), Stefan Jordan (2), Michael Biermann (3), Thomas Kaempke (1), R alf-Dieter Scholz (4) ((1) FAW, Ulm, Germany, (2) IAAT, Tuebingen, Germany, (3) ARI, Heidelberg, Germa ny, (4) AIP, Potsdam, Germany)
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an object detection algorithm which is efficient and fast enough to be used in (almost) real time with the limited computer capacities onboard satellites. For stars below the saturation limit of the CCD detectors it is based on a four neighbourhood local maximum criterion in order to find the centre of a stellar image. For saturated stars it is based on the assumption that the image is increasing monotonically towards the centre in the unsaturated part of the image. The algorithm also calculates approximate stellar magnitudes and efficiently rejects most of the cosmics which would otherwise lead to a large number of false detections. The quality of the algorithm was evaluated with the help of a large set of simulated data for the DIVA satellite mission; different assumptions were made for the noise level, and the presence of cosmics or for a variable sky background. We could show that our algorithm fulfills the requirements for DIVA; only in the case of simulated images which included the bright galaxy M31 some fainter stars could not be detected in the galaxy's vicinity. Since stellar images contain large areas without any stars, we propose an additional block-skipping algorithm which can be coded on special-purpose hardware.

##### Abstract (translated by Google)
我们提出了一种有效和快速的目标检测算法，可以在几乎是实时的情况下使用有限的机载卫星。对于低于CCD探测器饱和极限的恒星，它是基于四邻域局部最大准则，以便找到恒星图像的中心。对于饱和恒星，它是基于图像在图像的非饱和部分中朝向中心单调递增的假设。该算法还计算近似恒星的大小，并有效地拒绝大部分宇宙，否则会导致大量的错误检测。在DIVA卫星任务的大量模拟数据的帮助下评估算法的质量;对噪声水平，宇宙的存在或变化的天空背景做出了不同的假设。我们可以证明我们的算法符合DIVA的要求;只有在包含明亮星系M31的模拟图像的情况下，星系附近才能检测到一些较弱的恒星。由于恒星图像包含大面积没有星星，我们提出一个额外的块跳过算法，可以在专用硬件上编码。

##### URL
[https://arxiv.org/abs/astro-ph/0301611](https://arxiv.org/abs/astro-ph/0301611)

##### PDF
[https://arxiv.org/pdf/astro-ph/0301611](https://arxiv.org/pdf/astro-ph/0301611)


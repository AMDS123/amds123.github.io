---
layout: post
title: "Fast Estimation of Haemoglobin Concentration in Tissue Via Wavelet Decomposition"
date: 2017-06-22 11:32:09
categories: arXiv_CV
tags: arXiv_CV GAN
author: Geoffrey Jones, Neil T Clancy, Xiaofei Du, Maria Robu, Simon Arridge, Daniel S Elson, Danail Stoyanov
mathjax: true
---

* content
{:toc}

##### Abstract
Tissue oxygenation and perfusion can be an indicator for organ viability during minimally invasive surgery, for example allowing real-time assessment of tissue perfusion and oxygen saturation. Multispectral imaging is an optical modality that can inspect tissue perfusion in wide field images without contact. In this paper, we present a novel, fast method for using RGB images for MSI, which while limiting the spectral resolution of the modality allows normal laparoscopic systems to be used. We exploit the discrete Haar decomposition to separate individual video frames into low pass and directional coefficients and we utilise a different multispectral estimation technique on each. The increase in speed is achieved by using fast Tikhonov regularisation on the directional coefficients and more accurate Bayesian estimation on the low pass component. The pipeline is implemented using a graphics processing unit (GPU) architecture and achieves a frame rate of approximately 15Hz. We validate the method on animal models and on human data captured using a da Vinci stereo laparoscope.

##### Abstract (translated by Google)
组织充氧和灌注可以是微创手术期间器官活力的指标，例如允许组织灌注和氧饱和度的实时评估。多光谱成像是一种光学方式，可以在无接触的情况下检查宽视场图像中的组织灌注。在本文中，我们提出了一种新的，快速的方法使用RGB图像的MSI，同时限制模式的光谱分辨率允许使用正常的腹腔镜系统。我们利用离散Haar分解将单独的视频帧分离成低通和方向系数，并且我们在每一个上使用不同的多光谱估计技术。通过在方向系数上使用快速的Tikhonov正则化和在低通分量上的更精确的贝叶斯估计来实现速度的增加。该流水线是使用图形处理单元（GPU）架构实现的，并且实现了大约15Hz的帧速率。我们验证了动物模型的方法和使用达芬奇立体腹腔镜捕获的人体数据。

##### URL
[https://arxiv.org/abs/1706.07263](https://arxiv.org/abs/1706.07263)

##### PDF
[https://arxiv.org/pdf/1706.07263](https://arxiv.org/pdf/1706.07263)


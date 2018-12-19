---
layout: post
title: "SREdgeNet: Edge Enhanced Single Image Super Resolution using Dense Edge Detection Network and Feature Merge Network"
date: 2018-12-18 05:13:41
categories: arXiv_CV
tags: arXiv_CV Super_Resolution GAN Deep_Learning Quantitative Detection
author: Kwanyoung Kim, Se Young Chun
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based single image super-resolution (SR) methods have been rapidly evolved over the past few years and have yielded state-of-the-art performances over conventional methods. Since these methods usually minimized l1 loss between the output SR image and the ground truth image, they yielded very high peak signal-to-noise ratio (PSNR) that is inversely proportional to these losses. Unfortunately, minimizing these losses inevitably lead to blurred edges due to averaging of plausible solutions. Recently, SRGAN was proposed to avoid this average effect by minimizing perceptual losses instead of l1 loss and it yielded perceptually better SR images (or images with sharp edges) at the price of lowering PSNR. In this paper, we propose SREdgeNet, edge enhanced single image SR network, that was inspired by conventional SR theories so that average effect could be avoided not by changing the loss, but by changing the SR network property with the same l1 loss. Our SREdgeNet consists of 3 sequential deep neural network modules: the first module is any state-of-the-art SR network and we selected a variant of EDSR. The second module is any edge detection network taking the output of the first SR module as an input and we propose DenseEdgeNet for this module. Lastly, the third module is merging the outputs of the first and second modules to yield edge enhanced SR image and we propose MergeNet for this module. Qualitatively, our proposed method yielded images with sharp edges compared to other state-of-the-art SR methods. Quantitatively, our SREdgeNet yielded state-of-the-art performance in terms of structural similarity (SSIM) while maintained comparable PSNR for x8 enlargement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07174](http://arxiv.org/abs/1812.07174)

##### PDF
[http://arxiv.org/pdf/1812.07174](http://arxiv.org/pdf/1812.07174)


---
layout: post
title: "Adaptive Weighting Depth-variant Deconvolution of Fluorescence Microscopy Images with Convolutional Neural Network"
date: 2019-07-07 03:58:04
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Prediction
author: Da He, De Cai, Jiasheng Zhou, Jiajia Luo, Sung-Liang Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Fluorescence microscopy plays an important role in biomedical research. The depth-variant point spread function (PSF) of a fluorescence microscope produces low-quality images especially in the out-of-focus regions of thick specimens. Traditional deconvolution to restore the out-of-focus images is usually insufficient since a depth-invariant PSF is assumed. This article aims at handling fluorescence microscopy images by learning-based depth-variant PSF and reducing artifacts. We propose adaptive weighting depth-variant deconvolution (AWDVD) with defocus level prediction convolutional neural network (DelpNet) to restore the out-of-focus images. Depth-variant PSFs of image patches can be obtained by DelpNet and applied in the afterward deconvolution. AWDVD is adopted for a whole image which is patch-wise deconvolved and appropriately cropped before deconvolution. DelpNet achieves the accuracy of 98.2%, which outperforms the best-ever one using the same microscopy dataset. Image patches of 11 defocus levels after deconvolution are validated with maximum improvement in the peak signal-to-noise ratio and structural similarity index of 6.6 dB and 11%, respectively. The adaptive weighting of the patch-wise deconvolved image can eliminate patch boundary artifacts and improve deconvolved image quality. The proposed method can accurately estimate depth-variant PSF and effectively recover out-of-focus microscopy images. To our acknowledge, this is the first study of handling out-of-focus microscopy images using learning-based depth-variant PSF. Facing one of the most common blurs in fluorescence microscopy, the novel method provides a practical technology to improve the image quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03217](http://arxiv.org/abs/1907.03217)

##### PDF
[http://arxiv.org/pdf/1907.03217](http://arxiv.org/pdf/1907.03217)


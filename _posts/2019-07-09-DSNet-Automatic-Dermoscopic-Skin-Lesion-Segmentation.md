---
layout: post
title: "DSNet: Automatic Dermoscopic Skin Lesion Segmentation"
date: 2019-07-09 17:42:51
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Detection
author: Md. Kamrul Hasan, Lavsen Dahal, Prasad N. Samarakoon, Fakrul Islam Tushar, Robert Marti Marly
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of skin lesion is considered a crucial step in Computer Aided Diagnosis (CAD) for melanoma diagnosis. Despite its significance, skin lesion segmentation remains a challenging task due to their diverse color, texture, and indistinguishable boundaries and forms an open problem. Through this study, we present a new and automatic semantic segmentation network for robust skin lesion segmentation named Dermoscopic Skin Network (DSNet). In order to reduce the number of parameters to make the network lightweight, we used depth-wise separable convolution in lieu of standard convolution to project the learned discriminating features onto the pixel space at different stages of the encoder. Additionally, we implemented U-Net and Fully Convolutional Network (FCN8s) to compare against the proposed DSNet. We evaluate our proposed model on two publicly available datasets, namely ISIC-2017 and PH2. The obtained mean Intersection over Union (mIoU) is 77.5 % and 87.0 % respectively for ISIC-2017 and PH2 datasets which outperformed the ISIC-2017 challenge winner by 1.0 % with respect to mIoU. Our proposed network also outperformed U-Net and FCN8s respectively by 3.6 % and 6.8 % with respect to mIoU on the ISIC-2017 dataset. Our network for skin lesion segmentation outperforms other methods and can provide better segmented masks on two different test datasets which can lead to better performance in melanoma detection. Our trained model along with the source code and predicted masks are made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04305](http://arxiv.org/abs/1907.04305)

##### PDF
[http://arxiv.org/pdf/1907.04305](http://arxiv.org/pdf/1907.04305)


---
layout: post
title: "Deep learning based cloud detection for medium and high resolution remote sensing images of different sensors"
date: 2019-01-16 01:34:20
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning Detection
author: Zhiwei Li, Huanfeng Shen, Qing Cheng, Yuhao Liu, Shucheng You, Zongyi He
mathjax: true
---

* content
{:toc}

##### Abstract
Cloud detection is an important preprocessing step for the precise application of optical satellite imagery. In this paper, we propose a deep learning based cloud detection method named multi-scale convolutional feature fusion (MSCFF) for remote sensing images of different sensors. In the network architecture of MSCFF, the symmetric encoder-decoder module, which provides both local and global context by densifying feature maps with trainable convolutional filter banks, is utilized to extract multi-scale and high-level spatial features. The feature maps of multiple scales are then up-sampled and concatenated, and a novel multi-scale feature fusion module is designed to fuse the features of different scales for the output. The two output feature maps of the network are cloud and cloud shadow maps, which are in turn fed to binary classifiers outside the model to obtain the final cloud and cloud shadow mask. The MSCFF method was validated on hundreds of globally distributed optical satellite images, with spatial resolutions ranging from 0.5 to 50 m, including Landsat-5/7/8, Gaofen-1/2/4, Sentinel-2, Ziyuan-3, CBERS-04, Huanjing-1, and collected high-resolution images exported from Google Earth. The experimental results show that MSCFF achieves a higher accuracy than the traditional rule-based cloud detection methods and the state-of-the-art deep learning models, especially in bright surface covered areas. The effectiveness of MSCFF means that it has great promise for the practical application of cloud detection for multiple types of medium and high-resolution remote sensing images. Our established global high-resolution cloud detection validation dataset has been made available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.05801](http://arxiv.org/abs/1810.05801)

##### PDF
[http://arxiv.org/pdf/1810.05801](http://arxiv.org/pdf/1810.05801)


---
layout: post
title: "Infrared and Visible Image Fusion using a Deep Learning Framework"
date: 2018-12-18 08:36:54
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Hui Li, Xiao-Jun Wu, Josef Kittler
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep learning has become a very active research tool which is used in many image processing fields. In this paper, we propose an effective image fusion method using a deep learning framework to generate a single image which contains all the features from infrared and visible images. First, the source images are decomposed into base parts and detail content. Then the base parts are fused by weighted-averaging. For the detail content, we use a deep learning network to extract multi-layer features. Using these features, we use l_1-norm and weighted-average strategy to generate several candidates of the fused detail content. Once we get these candidates, the max selection strategy is used to get final fused detail content. Finally, the fused image will be reconstructed by combining the fused base part and detail content. The experimental results demonstrate that our proposed method achieves state-of-the-art performance in both objective assessment and visual quality. The Code of our fusion method is available at https://github.com/hli1221/imagefusion_deeplearning

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.06992](http://arxiv.org/abs/1804.06992)

##### PDF
[http://arxiv.org/pdf/1804.06992](http://arxiv.org/pdf/1804.06992)


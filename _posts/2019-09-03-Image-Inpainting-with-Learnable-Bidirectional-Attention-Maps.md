---
layout: post
title: "Image Inpainting with Learnable Bidirectional Attention Maps"
date: 2019-09-03 06:18:40
categories: arXiv_CV
tags: arXiv_CV Attention CNN Quantitative
author: Chaohao Xie, Shaohui Liu, Chao Li, Ming-Ming Cheng, Wangmeng Zuo, Xiao Liu, Shilei Wen, Errui Ding
mathjax: true
---

* content
{:toc}

##### Abstract
Most convolutional network (CNN)-based inpainting methods adopt standard convolution to indistinguishably treat valid pixels and holes, making them limited in handling irregular holes and more likely to generate inpainting results with color discrepancy and blurriness. Partial convolution has been suggested to address this issue, but it adopts handcrafted feature re-normalization, and only considers forward mask-updating. In this paper, we present a learnable attention map module for learning feature renormalization and mask-updating in an end-to-end manner, which is effective in adapting to irregular holes and propagation of convolution layers. Furthermore, learnable reverse attention maps are introduced to allow the decoder of U-Net to concentrate on filling in irregular holes instead of reconstructing both holes and known regions, resulting in our learnable bidirectional attention maps. Qualitative and quantitative experiments show that our method performs favorably against state-of-the-arts in generating sharper, more coherent and visually plausible inpainting results. The source code and pre-trained models will be available at: https://github.com/Vious/LBAM_inpainting/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00968](http://arxiv.org/abs/1909.00968)

##### PDF
[http://arxiv.org/pdf/1909.00968](http://arxiv.org/pdf/1909.00968)


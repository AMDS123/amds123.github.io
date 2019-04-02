---
layout: post
title: "Learning Content-Weighted Deep Image Compression"
date: 2019-04-01 09:40:37
categories: arXiv_CV
tags: arXiv_CV Salient CNN Optimization
author: Mu Li, Wangmeng Zuo, Shuhang Gu, Jane You, David Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Learning-based lossy image compression usually involves the joint optimization of rate-distortion performance. Most existing methods adopt spatially invariant bit length allocation and incorporate discrete entropy approximation to constrain compression rate. Nonetheless, the information content is spatially variant, where the regions with complex and salient structures generally are more essential to image compression. Taking the spatial variation of image content into account, this paper presents a content-weighted encoder-decoder model, which involves an importance map subnet to produce the importance mask for locally adaptive bit rate allocation. Consequently, the summation of importance mask can thus be utilized as an alternative of entropy estimation for compression rate control. Furthermore, the quantized representations of the learned code and importance map are still spatially dependent, which can be losslessly compressed using arithmetic coding. To compress the codes effectively and efficiently, we propose a trimmed convolutional network to predict the conditional probability of quantized codes. Experiments show that the proposed method can produce visually much better results, and performs favorably in comparison with deep and traditional lossy image compression approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00664](http://arxiv.org/abs/1904.00664)

##### PDF
[http://arxiv.org/pdf/1904.00664](http://arxiv.org/pdf/1904.00664)


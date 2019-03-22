---
layout: post
title: "Multi-scale Processing of Noisy Images using Edge Preservation Losses"
date: 2019-03-21 14:40:45
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Detection
author: Nati Ofir, Yosi Keller
mathjax: true
---

* content
{:toc}

##### Abstract
Noisy images processing is a fundamental task of computer vision. The first example is the detection of faint edges in noisy images, a challenging problem studied in the last decades. A recent study introduced a fast method to detect faint edges in the highest accuracy among all the existing approaches. Their complexity is nearly linear in the image's pixels and their runtime is seconds for a noisy image. Their approach utilizes a multi-scale binary partitioning of the image. By utilizing the multi-scale U-net architecture, we show in this paper that their method can be dramatically improved in both aspects of run time and accuracy. By training the network on a dataset of binary images, we developed an approach for faint edge detection that works in a linear complexity. Our runtime of a noisy image is milliseconds on a GPU. Even though our method is orders of magnitude faster, we still achieve higher accuracy of detection under many challenging scenarios. In addition, we show that our approach to performing multi-scale preprocessing of noisy images using U-net improves the ability to perform other vision tasks under the presence of noise. We prove it on the problems of noisy objects classification and classical image denoising. We show that multi-scale denoising can be carried out by a novel edge preservation loss. As our experiments show, we achieve high-quality results in the three aspects of faint edge detection, noisy image classification and natural image denoising.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.09420](http://arxiv.org/abs/1803.09420)

##### PDF
[http://arxiv.org/pdf/1803.09420](http://arxiv.org/pdf/1803.09420)


---
layout: post
title: "Efficient Misalignment-Robust Multi-Focus Microscopical Images Fusion"
date: 2018-12-21 02:17:35
categories: arXiv_CV
tags: arXiv_CV Salient Detection
author: Yixiong Liang, Yuan Mao, Zhihong Tang, Meng Yan, Yuqian Zhao, Jianfeng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a very efficient method to fuse the unregistered multi-focus microscopical images based on the speed-up robust features (SURF). Our method follows the pipeline of first registration and then fusion. However, instead of treating the registration and fusion as two completely independent stage, we propose to reuse the determinant of the approximate Hessian generated in SURF detection stage as the corresponding salient response for the final image fusion, thus it enables nearly cost-free saliency map generation. In addition, due to the adoption of SURF scale space representation, our method can generate scale-invariant saliency map which is desired for scale-invariant image fusion. We present an extensive evaluation on the dataset consisting of several groups of unregistered multi-focus 4K ultra HD microscopic images with size of 4112 x 3008. Compared with the state-of-the-art multi-focus image fusion methods, our method is much faster and achieve better results in the visual performance. Our method provides a flexible and efficient way to integrate complementary and redundant information from multiple multi-focus ultra HD unregistered images into a fused image that contains better description than any of the individual input images. Code is available at https://github.com/yiqingmy/JointRF.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08915](http://arxiv.org/abs/1812.08915)

##### PDF
[http://arxiv.org/pdf/1812.08915](http://arxiv.org/pdf/1812.08915)


---
layout: post
title: "DVC: An End-to-end Deep Video Compression Framework"
date: 2018-11-30 23:55:31
categories: arXiv_CV
tags: arXiv_CV
author: Guo Lu, Wanli Ouyang, Dong Xu, Xiaoyun Zhang, Chunlei Cai, Zhiyong Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional video compression approaches use the predictive coding architecture and encode the corresponding motion information and residual information. In this paper, taking advantage of both classical architecture in the conventional video compression method and the powerful non-linear representation ability of neural networks, we propose the first end-to-end video compression deep model that jointly optimizes all the components for video compression. Specifically, learning based optical flow estimation is utilized to obtain the motion information and reconstruct the current frames. Then we employ two auto-encoder style neural networks to compress the corresponding motion and residual information. All the modules are jointly learned through a single loss function, in which they collaborate with each other by considering the trade-off between reducing the number of compression bits and improving quality of the decoded video. Experimental results show that the proposed approach outperforms the widely used video coding standard H.264 in terms of PSNR and be even on par with the latest standard H.265 in terms of MS-SSIM. Code will be publicly available upon acceptance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00101](http://arxiv.org/abs/1812.00101)

##### PDF
[http://arxiv.org/pdf/1812.00101](http://arxiv.org/pdf/1812.00101)


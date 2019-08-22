---
layout: post
title: "MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors"
date: 2019-08-21 16:55:08
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Quantitative
author: Royson Lee, Stylianos I. Venieris, &#x141;ukasz Dudziak, Sourav Bhattacharya, Nicholas D. Lane
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, convolutional networks have demonstrated unprecedented performance in the image restoration task of super-resolution (SR). SR entails the upscaling of a single low-resolution image in order to meet application-specific image quality demands and plays a key role in mobile devices. To comply with privacy regulations and reduce the overhead of cloud computing, executing SR models locally on-device constitutes a key alternative approach. Nevertheless, the excessive compute and memory requirements of SR workloads pose a challenge in mapping SR networks on resource-constrained mobile platforms. This work presents MobiSR, a novel framework for performing efficient super-resolution on-device. Given a target mobile platform, the proposed framework considers popular model compression techniques and traverses the design space to reach the highest performing trade-off between image quality and processing speed. At run time, a novel scheduler dispatches incoming image patches to the appropriate model-engine pair based on the patch's estimated upscaling difficulty in order to meet the required image quality with minimum processing latency. Quantitative evaluation shows that the proposed framework yields on-device SR designs that achieve an average speedup of 2.13x over highly-optimized parallel difficulty-unaware mappings and 4.79x over highly-optimized single compute engine implementations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07985](http://arxiv.org/abs/1908.07985)

##### PDF
[http://arxiv.org/pdf/1908.07985](http://arxiv.org/pdf/1908.07985)


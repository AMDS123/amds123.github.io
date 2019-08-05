---
layout: post
title: "Scale Matters: Temporal Scale Aggregation Network for Precise Action Localization in Untrimmed Videos"
date: 2019-08-02 05:49:37
categories: arXiv_CV
tags: arXiv_CV Detection
author: Guoqiang Gong, Liangfeng Zheng, Kun Bai, Yadong Mu
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action localization is a recently-emerging task, aiming to localize video segments from untrimmed videos that contain specific actions. Despite the remarkable recent progress, most two-stage action localization methods still suffer from imprecise temporal boundaries of action proposals. This work proposes a novel integrated temporal scale aggregation network (TSA-Net). Our main insight is that ensembling convolution filters with different dilation rates can effectively enlarge the receptive field with low computational cost, which inspires us to devise multi-dilation temporal convolution (MDC) block. Furthermore, to tackle video action instances with different durations, TSA-Net consists of multiple branches of sub-networks. Each of them adopts stacked MDC blocks with different dilation parameters, accomplishing a temporal receptive field specially optimized for specific-duration actions. We follow the formulation of boundary point detection, novelly detecting three kinds of critical points (ie, starting / mid-point / ending) and pairing them for proposal generation. Comprehensive evaluations are conducted on two challenging video benchmarks, THUMOS14 and ActivityNet-1.3. Our proposed TSA-Net demonstrates clear and consistent better performances and re-calibrates new state-of-the-art on both benchmarks. For example, our new record on THUMOS14 is 46.9% while the previous best is 42.8% under mAP@0.5.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00707](http://arxiv.org/abs/1908.00707)

##### PDF
[http://arxiv.org/pdf/1908.00707](http://arxiv.org/pdf/1908.00707)


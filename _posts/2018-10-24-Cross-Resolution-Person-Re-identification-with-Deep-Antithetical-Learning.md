---
layout: post
title: "Cross-Resolution Person Re-identification with Deep Antithetical Learning"
date: 2018-10-24 07:33:30
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification
author: Zijie Zhuang, Haizhou Ai, Long Chen, Chong Shang
mathjax: true
---

* content
{:toc}

##### Abstract
Images with different resolutions are ubiquitous in public person re-identification (ReID) datasets and real-world scenes, it is thus crucial for a person ReID model to handle the image resolution variations for improving its generalization ability. However, most existing person ReID methods pay little attention to this resolution discrepancy problem. One paradigm to deal with this problem is to use some complicated methods for mapping all images into an artificial image space, which however will disrupt the natural image distribution and requires heavy image preprocessing. In this paper, we analyze the deficiencies of several widely-used objective functions handling image resolution discrepancies and propose a new framework called deep antithetical learning that directly learns from the natural image space rather than creating an arbitrary one. We first quantify and categorize original training images according to their resolutions. Then we create an antithetical training set and make sure that original training images have counterparts with antithetical resolutions in this new set. At last, a novel Contrastive Center Loss(CCL) is proposed to learn from images with different resolutions without being interfered by their resolution discrepancies. Extensive experimental analyses and evaluations indicate that the proposed framework, even using a vanilla deep ReID network, exhibits remarkable performance improvements. Without bells and whistles, our approach outperforms previous state-of-the-art methods by a large margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10221](http://arxiv.org/abs/1810.10221)

##### PDF
[http://arxiv.org/pdf/1810.10221](http://arxiv.org/pdf/1810.10221)


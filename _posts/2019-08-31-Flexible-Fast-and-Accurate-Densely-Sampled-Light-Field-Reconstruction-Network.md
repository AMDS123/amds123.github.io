---
layout: post
title: "Flexible, Fast and Accurate Densely-Sampled Light Field Reconstruction Network"
date: 2019-08-31 05:16:21
categories: arXiv_CV
tags: arXiv_CV Sparse Relation
author: Jing Jin, Junhui Hou, Jie Chen, Huanqiang Zeng, Sam Kwong, Jingyi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
The densely-sampled light field (LF) is highly desirable in various applications, such as 3-D reconstruction, post-capture refocusing and virtual reality. However, it is costly to acquire such data. Although many computational methods have been proposed to reconstruct a densely-sampled LF from a sparsely-sampled one, they still suffer from either low reconstruction quality, low computational efficiency, or the restriction on the regularity of the sampling pattern. To this end, we propose a novel learning-based method, which accepts sparsely-sampled LFs with irregular structures, and produces densely-sampled LFs with arbitrary angular resolution accurately and efficiently. Our proposed method, an end-to-end trainable network, reconstructs a densely-sampled LF in a coarse-to-fine manner. Specifically, the coarse sub-aperture image (SAI) synthesis module first explores the scene geometry from an unstructured sparsely-sampled LF and leverages it to independently synthesize novel SAIs, giving an intermediate densely-sampled LF. Then, the efficient LF refinement module learns the angular relations within the intermediate result to recover the LF parallax structure. Comprehensive experimental evaluations demonstrate the superiority of our method on both real-world and synthetic LF images when compared with state-of-the-art methods. In addition, we illustrate the benefits and advantages of the proposed approach when applied in various LF-based applications, including image-based rendering, depth estimation enhancement, and LF compression.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01341](http://arxiv.org/abs/1909.01341)

##### PDF
[http://arxiv.org/pdf/1909.01341](http://arxiv.org/pdf/1909.01341)


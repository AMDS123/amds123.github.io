---
layout: post
title: "Towards Multi-pose Guided Virtual Try-on Network"
date: 2019-02-28 11:34:52
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Haoye Dong, Xiaodan Liang, Bochao Wang, Hanjiang Lai, Jia Zhu, Jian Yin
mathjax: true
---

* content
{:toc}

##### Abstract
Virtual try-on system under arbitrary human poses has huge application potential, yet raises quite a lot of challenges, e.g. self-occlusions, heavy misalignment among diverse poses, and diverse clothes textures. Existing methods aim at fitting new clothes into a person can only transfer clothes on the fixed human pose, but still show unsatisfactory performances which often fail to preserve the identity, lose the texture details, and decrease the diversity of poses. In this paper, we make the first attempt towards multi-pose guided virtual try-on system, which enables transfer clothes on a person image under diverse poses. Given an input person image, a desired clothes image, and a desired pose, the proposed Multi-pose Guided Virtual Try-on Network (MG-VTON) can generate a new person image after fitting the desired clothes into the input image and manipulating human poses. Our MG-VTON is constructed in three stages: 1) a desired human parsing map of the target image is synthesized to match both the desired pose and the desired clothes shape; 2) a deep Warping Generative Adversarial Network (Warp-GAN) warps the desired clothes appearance into the synthesized human parsing map and alleviates the misalignment problem between the input human pose and desired human pose; 3) a refinement render utilizing multi-pose composition masks recovers the texture details of clothes and removes some artifacts. Extensive experiments on well-known datasets and our newly collected largest virtual try-on benchmark demonstrate that our MG-VTON significantly outperforms all state-of-the-art methods both qualitatively and quantitatively with promising multi-pose virtual try-on performances.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11026](http://arxiv.org/abs/1902.11026)

##### PDF
[http://arxiv.org/pdf/1902.11026](http://arxiv.org/pdf/1902.11026)


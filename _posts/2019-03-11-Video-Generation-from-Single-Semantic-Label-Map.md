---
layout: post
title: "Video Generation from Single Semantic Label Map"
date: 2019-03-11 17:56:34
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Junting Pan, Chengyu Wang, Xu Jia, Jing Shao, Lu Sheng, Junjie Yan, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes the novel task of video generation conditioned on a SINGLE semantic label map, which provides a good balance between flexibility and quality in the generation process. Different from typical end-to-end approaches, which model both scene content and dynamics in a single step, we propose to decompose this difficult task into two sub-problems. As current image generation methods do better than video generation in terms of detail, we synthesize high quality content by only generating the first frame. Then we animate the scene based on its semantic meaning to obtain the temporally coherent video, giving us excellent results overall. We employ a cVAE for predicting optical flow as a beneficial intermediate step to generate a video sequence conditioned on the initial single frame. A semantic label map is integrated into the flow prediction module to achieve major improvements in the image-to-video generation process. Extensive experiments on the Cityscapes dataset show that our method outperforms all competing methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.04480](https://arxiv.org/abs/1903.04480)

##### PDF
[https://arxiv.org/pdf/1903.04480](https://arxiv.org/pdf/1903.04480)


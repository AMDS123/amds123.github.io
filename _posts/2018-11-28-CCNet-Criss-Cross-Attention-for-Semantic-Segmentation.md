---
layout: post
title: "CCNet: Criss-Cross Attention for Semantic Segmentation"
date: 2018-11-28 18:18:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation
author: Zilong Huang, Xinggang Wang, Lichao Huang, Chang Huang, Yunchao Wei, Wenyu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Long-range dependencies can capture useful contextual information to benefit visual understanding problems. In this work, we propose a Criss-Cross Network (CCNet) for obtaining such important information through a more effective and efficient way. Concretely, for each pixel, our CCNet can harvest the contextual information of its surrounding pixels on the criss-cross path through a novel criss-cross attention module. By taking a further recurrent operation, each pixel can finally capture the long-range dependencies from all pixels. Overall, our CCNet is with the following merits: 1) GPU memory friendly. Compared with the non-local block, the recurrent criss-cross attention module requires $11\times$ less GPU memory usage. 2) High computational efficiency. The recurrent criss-cross attention significantly reduces FLOPs by about 85\% of the non-local block in computing long-range dependencies. 3) The state-of-the-art performance. We conduct extensive experiments on popular semantic segmentation benchmarks including Cityscapes, ADE20K, and instance segmentation benchmark COCO. In particular, our CCNet achieves the mIoU score of 81.4 and 45.22 on Cityscapes test set and ADE20K validation set, respectively, which are the new state-of-the-art results. We make the code publicly available at \url{https://github.com/speedinghzl/CCNet .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11721](http://arxiv.org/abs/1811.11721)

##### PDF
[http://arxiv.org/pdf/1811.11721](http://arxiv.org/pdf/1811.11721)


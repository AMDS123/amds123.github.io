---
layout: post
title: "Semantic Alignment: Finding Semantically Consistent Ground-truth for Facial Landmark Detection"
date: 2019-03-26 03:19:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Deep_Learning Detection
author: Zhiwei Liu, Xiangyu Zhu, Guosheng Hu, Haiyun Guo, Ming Tang, Zhen Lei, Neil M. Robertson, Jinqiao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep learning based facial landmark detection has achieved great success. Despite this, we notice that the semantic ambiguity greatly degrades the detection performance. Specifically, the semantic ambiguity means that some landmarks (e.g. those evenly distributed along the face contour) do not have clear and accurate definition, causing inconsistent annotations by annotators. Accordingly, these inconsistent annotations, which are usually provided by public databases, commonly work as the ground-truth to supervise network training, leading to the degraded accuracy. To our knowledge, little research has investigated this problem. In this paper, we propose a novel probabilistic model which introduces a latent variable, i.e. the 'real' ground-truth which is semantically consistent, to optimize. This framework couples two parts (1) training landmark detection CNN and (2) searching the 'real' ground-truth. These two parts are alternatively optimized: the searched 'real' ground-truth supervises the CNN training; and the trained CNN assists the searching of 'real' ground-truth. In addition, to recover the unconfidently predicted landmarks due to occlusion and low quality, we propose a global heatmap correction unit (GHCU) to correct outliers by considering the global face shape as a constraint. Extensive experiments on both image-based (300W and AFLW) and video-based (300-VW) databases demonstrate that our method effectively improves the landmark detection accuracy and achieves the state of the art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10661](http://arxiv.org/abs/1903.10661)

##### PDF
[http://arxiv.org/pdf/1903.10661](http://arxiv.org/pdf/1903.10661)


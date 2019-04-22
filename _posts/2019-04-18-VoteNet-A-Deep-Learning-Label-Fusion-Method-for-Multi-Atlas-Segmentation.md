---
layout: post
title: "VoteNet: A Deep Learning Label Fusion Method for Multi-Atlas Segmentation"
date: 2019-04-18 18:16:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Zhipeng Ding, Xu Han, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning (DL) approaches are state-of-the-art for many medical image segmentation tasks. They offer a number of advantages: they can be trained for specific tasks, computations are fast at test time, and segmentation quality is typically high. In contrast, previously popular multi-atlas segmentation (MAS) methods are relatively slow (as they rely on costly registrations) and even though sophisticated label fusion strategies have been proposed, DL approaches generally outperform MAS. In this work, we propose a DL-based label fusion strategy (VoteNet) which locally selects a set of reliable atlases whose labels are then fused via plurality voting. Experiments on 3D brain MRI data show that by selecting a good initial atlas set MAS with VoteNet significantly outperforms a number of other label fusion strategies as well as a direct DL segmentation approach. We also provide an experimental analysis of the upper performance bound achievable by our method. While unlikely achievable in practice, this bound suggests room for further performance improvements. Lastly, to address the runtime disadvantage of standard MAS, all our results make use of a fast DL registration approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08963](http://arxiv.org/abs/1904.08963)

##### PDF
[http://arxiv.org/pdf/1904.08963](http://arxiv.org/pdf/1904.08963)


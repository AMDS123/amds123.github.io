---
layout: post
title: "GAN-based Pose-aware Regulation for Video-based Person Re-identification"
date: 2019-03-27 17:14:51
categories: arXiv_CV
tags: arXiv_CV Re-identification GAN Person_Re-identification Embedding RNN
author: Alessandro Borgia, Yang Hua, Elyor Kodirov, Neil M. Robertson
mathjax: true
---

* content
{:toc}

##### Abstract
Video-based person re-identification deals with the inherent difficulty of matching unregulated sequences with different length and with incomplete target pose/viewpoint structure. Common approaches operate either by reducing the problem to the still images case, facing a significant information loss, or by exploiting inter-sequence temporal dependencies as in Siamese Recurrent Neural Networks or in gait analysis. However, in all cases, the inter-sequences pose/viewpoint misalignment is not considered, and the existing spatial approaches are mostly limited to the still images context. To this end, we propose a novel approach that can exploit more effectively the rich video information, by accounting for the role that the changing pose/viewpoint factor plays in the sequences matching process. Specifically, our approach consists of two components. The first one attempts to complement the original pose-incomplete information carried by the sequences with synthetic GAN-generated images, and fuse their feature vectors into a more discriminative viewpoint-insensitive embedding, namely Weighted Fusion (WF). Another one performs an explicit pose-based alignment of sequence pairs to promote coherent feature matching, namely Weighted-Pose Regulation (WPR). Extensive experiments on two large video-based benchmark datasets show that our approach outperforms considerably existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11552](http://arxiv.org/abs/1903.11552)

##### PDF
[http://arxiv.org/pdf/1903.11552](http://arxiv.org/pdf/1903.11552)


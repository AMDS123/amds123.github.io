---
layout: post
title: "Foreground-aware Pyramid Reconstruction for Alignment-free Occluded Person Re-identification"
date: 2019-04-10 02:04:24
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Lingxiao He, Yinggang Wang, Wu Liu, Xingyu Liao, He Zhao, Zhenan Sun, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Re-identifying a person across multiple disjoint camera views is important for intelligent video surveillance, smart retailing and many other applications. However, existing person re-identification (ReID) methods are challenged by the ubiquitous occlusion over persons and suffer from performance degradation. This paper proposes a novel occlusion-robust and alignment-free model for occluded person ReID and extends its application to realistic and crowded scenarios. The proposed model first leverages the full convolution network (FCN) and pyramid pooling to extract spatial pyramid features. Then an alignment-free matching approach, namely Foreground-aware Pyramid Reconstruction (FPR), is developed to accurately compute matching scores between occluded persons, despite their different scales and sizes. FPR uses the error from robust reconstruction over spatial pyramid features to measure similarities between two persons. More importantly, we design an occlusion-sensitive foreground probability generator that focuses more on clean human body parts to refine the similarity computation with less contamination from occlusion. The FPR is easily embedded into any end-to-end person ReID models. The effectiveness of the proposed method is clearly demonstrated by the experimental results (Rank-1 accuracy) on three occluded person datasets: Partial REID (78.30\%), Partial iLIDS (68.08\%) and Occluded REID (81.00\%); and three benchmark person datasets: Market1501 (95.42\%), DukeMTMC (88.64\%) and CUHK03 (76.08\%)

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04975](http://arxiv.org/abs/1904.04975)

##### PDF
[http://arxiv.org/pdf/1904.04975](http://arxiv.org/pdf/1904.04975)


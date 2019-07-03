---
layout: post
title: "An Integrated Image Filter for Enhancing Change Detection Results"
date: 2019-07-02 11:32:35
categories: arXiv_CV
tags: arXiv_CV Detection
author: Dawei Li, Siyuan Yan, Xin Cai, Yan Cao, Sifan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Change detection is a fundamental task in computer vision. Despite significant advances have been made, most of the change detection methods fail to work well in challenging scenes due to ubiquitous noise and interferences. Nowadays, post-processing methods (e.g. MRF, and CRF) aiming to enhance the binary change detection results still fall short of the requirements on universality for distinctive scenes, applicability for different types of detection methods, accuracy, and real-time performance. Inspired by the nature of image filtering, which separates noise from pixel observations and recovers the real structure of patches, we consider utilizing image filters to enhance the detection masks. In this paper, we present an integrated filter which comprises a weighted local guided image filter and a weighted spatiotemporal tree filter. The spatiotemporal tree filter leverages the global spatiotemporal information of adjacent video frames and meanwhile the guided filter carries out local window filtering of pixels, for enhancing the coarse change detection masks. The main contributions are three: (i) the proposed filter can make full use of the information of the same object in consecutive frames to improve its current detection mask by computations on a spatiotemporal minimum spanning tree; (ii) the integrated filter possesses both advantages of local filtering and global filtering; it not only has good edge-preserving property but also can handle heavily textured and colorful foreground regions; and (iii) Unlike some popular enhancement methods (MRF, and CRF) that require either a priori background probabilities or a posteriori foreground probabilities for every pixel to improve the coarse detection masks, our method is a versatile enhancement filter that can be applied after many different types of change detection methods, and is particularly suitable for video sequences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01301](http://arxiv.org/abs/1907.01301)

##### PDF
[http://arxiv.org/pdf/1907.01301](http://arxiv.org/pdf/1907.01301)


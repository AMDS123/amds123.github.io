---
layout: post
title: "Region Proposal by Guided Anchoring"
date: 2019-01-10 17:13:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jiaqi Wang, Kai Chen, Shuo Yang, Chen Change Loy, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Region anchors are the cornerstone of modern object detection techniques. State-of-the-art detectors mostly rely on a dense anchoring scheme, where anchors are sampled uniformly over the spatial domain with a predefined set of scales and aspect ratios. In this paper, we revisit this foundational stage. Our study shows that it can be done much more effectively and efficiently. Specifically, we present an alternative scheme, named Guided Anchoring, which leverages semantic features to guide the anchoring. The proposed method jointly predicts the locations where the center of objects of interest are likely to exist as well as the scales and aspect ratios at different locations. On top of predicted anchor shapes, we mitigate the feature inconsistency with a feature adaption module. We also study the use of high-quality proposals to improve detection performance. The anchoring scheme can be seamlessly integrated to proposal methods and detectors. With Guided Anchoring, we achieve $9.1\%$ higher recall on MS COCO with $90\%$ fewer anchors than the RPN baseline. We also adopt Guided Anchoring in Fast R-CNN, Faster R-CNN and RetinaNet, respectively improving the detection mAP by $2.2\%$, $2.7\%$ and $1.2\%$.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.03278](https://arxiv.org/abs/1901.03278)

##### PDF
[https://arxiv.org/pdf/1901.03278](https://arxiv.org/pdf/1901.03278)


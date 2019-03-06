---
layout: post
title: "Arc-support Line Segments Revisited: An Efficient and High-quality Ellipse Detection"
date: 2019-03-05 08:28:32
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Detection
author: Changsheng Lu, Siyu Xia, Ming Shao, Yun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
Over the years many ellipse detection algorithms spring up and are studied broadly, while the critical issue of detecting ellipses accurately and efficiently in real-world images remains a challenge. In this paper, we propose a valuable industry-oriented ellipse detector by arc-support line segments, which simultaneously reaches high detection accuracy and efficiency. To simplify the complicated curves in an image while retaining the general properties including convexity and polarity, the arc-support line segments are extracted, which grounds the successful detection of ellipses. The arc-support groups are formed by iteratively and robustly linking the arc-support line segments that latently belong to a common ellipse. Afterward, two complementary approaches, namely, locally selecting the arc-support group with higher saliency and globally searching all the valid paired groups, are adopted to fit the initial ellipses in a fast way. Then, the ellipse candidate set can be formulated by hierarchical clustering of 5D parameter space of initial ellipses. Finally, the salient ellipse candidates are selected and refined as detections subject to the stringent and effective verification. Extensive experiments on three public datasets are implemented and our method achieves the best F-measure scores compared to the state-of-the-art methods. The source code is available at https://github.com/AlanLuSun/High-quality-ellipse-detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03243](http://arxiv.org/abs/1810.03243)

##### PDF
[http://arxiv.org/pdf/1810.03243](http://arxiv.org/pdf/1810.03243)


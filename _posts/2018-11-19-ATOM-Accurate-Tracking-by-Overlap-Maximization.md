---
layout: post
title: "ATOM: Accurate Tracking by Overlap Maximization"
date: 2018-11-19 11:40:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Classification Prediction
author: Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
While recent years have witnessed astonishing improvements in visual tracking robustness, the advancements in tracking accuracy have been severely limited. As the focus has been directed towards the development of powerful classifiers, the problem of accurate target state estimation has been largely overlooked. Instead, the majority of methods resort to simple multi-scale search in order to estimate the target bounding box. We argue that this approach is fundamentally limited as target estimation is a complex task, requiring high-level knowledge about the object. We thus address the problem of target state estimation in tracking. 
 We propose a novel tracking architecture consisting of dedicated target estimation and classification components. Due to the complex nature of target estimation, we propose a component that can be entirely trained offline on large-scale datasets. Our target estimation component is trained to predict the overlap between the target object and an estimated bounding box. By carefully integrating target-specific information in the prediction, our approach achieves previously unseen bounding box accuracy. Furthermore, we integrate a classification component that is trained online to guarantee high discriminative power in the presence of distractors. Our final tracking framework, comprised of a unified multi-task architecture, sets a new state-of-the-art on four challenging benchmarks. On the large-scale TrackingNet dataset, our tracker ATOM achieves a relative gain of 15%, while running at over 30 FPS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07628](http://arxiv.org/abs/1811.07628)

##### PDF
[http://arxiv.org/pdf/1811.07628](http://arxiv.org/pdf/1811.07628)


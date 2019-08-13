---
layout: post
title: "Faster Training of Mask R-CNN by Focusing on Instance Boundaries"
date: 2019-08-10 08:55:37
categories: arXiv_CV
tags: arXiv_CV Segmentation Survey Inference Prediction Detection
author: Roland S. Zimmermann, Julien N. Siems
mathjax: true
---

* content
{:toc}

##### Abstract
We present an auxiliary task to Mask R-CNN, an instance segmentation network, which leads to faster training of the mask head. Our addition to Mask R-CNN is a new prediction head, the Edge Agreement Head, which is inspired by the way human annotators perform instance segmentation. Human annotators copy the contour of an object instance and only indirectly the occupied instance area. Hence, the edges of instance masks are particularly useful as they characterize the instance well. The Edge Agreement Head therefore encourages predicted masks to have similar image gradients to the ground-truth mask using edge detection filters. We provide a detailed survey of loss combinations and show improvements on the MS COCO Mask metrics compared to using no additional loss. Our approach marginally increases the model size and adds no additional trainable model variables. While the computational costs are increased slightly, the increment is negligible considering the high computational cost of the Mask R-CNN architecture. As the additional network head is only relevant during training, inference speed remains unchanged compared to Mask R-CNN. In a default Mask R-CNN setup, we achieve a training speed-up and a relative overall improvement of 8.1% on the MS COCO metrics compared to the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.07069](http://arxiv.org/abs/1809.07069)

##### PDF
[http://arxiv.org/pdf/1809.07069](http://arxiv.org/pdf/1809.07069)


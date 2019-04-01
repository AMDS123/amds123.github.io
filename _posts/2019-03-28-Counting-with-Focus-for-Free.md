---
layout: post
title: "Counting with Focus for Free"
date: 2019-03-28 18:16:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN
author: Zenglin Shi, Pascal Mettes, Cees G. M. Snoek
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to count arbitrary objects in images. The leading counting approaches start from point annotations per object from which they construct density maps. Then, their training objective transforms input images to density maps through deep convolutional networks. We posit that the point annotations serve more supervision purposes than just constructing density maps. We introduce ways to repurpose the points for free. First, we propose supervised focus from segmentation, where points are converted into binary maps. The binary maps are combined with a network branch and accompanying loss function to focus on areas of interest. Second, we propose supervised focus from global density, where the ratio of point annotations to image pixels is used in another branch to regularize the overall density estimation. To assist both the density estimation and the focus from segmentation, we also introduce an improved kernel size estimator for the point annotations. Experiments on four datasets show that all our contributions reduce the counting error, regardless of the base network, resulting in state-of-the-art accuracy using only a single network. Finally, we are the first to count on WIDER FACE, allowing us to show the benefits of our approach in handling varying object scales and crowding levels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12206](http://arxiv.org/abs/1903.12206)

##### PDF
[http://arxiv.org/pdf/1903.12206](http://arxiv.org/pdf/1903.12206)


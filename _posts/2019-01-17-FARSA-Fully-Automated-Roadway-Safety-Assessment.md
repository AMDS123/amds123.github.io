---
layout: post
title: "FARSA: Fully Automated Roadway Safety Assessment"
date: 2019-01-17 21:48:05
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Weilian Song, Scott Workman, Armin Hadzic, Xu Zhang, Eric Green, Mei Chen, Reginald Souleyrette, Nathan Jacobs
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the task of road safety assessment. An emerging approach for conducting such assessments in the United States is through the US Road Assessment Program (usRAP), which rates roads from highest risk (1 star) to lowest (5 stars). Obtaining these ratings requires manual, fine-grained labeling of roadway features in street-level panoramas, a slow and costly process. We propose to automate this process using a deep convolutional neural network that directly estimates the star rating from a street-level panorama, requiring milliseconds per image at test time. Our network also estimates many other road-level attributes, including curvature, roadside hazards, and the type of median. To support this, we incorporate task-specific attention layers so the network can focus on the panorama regions that are most useful for a particular task. We evaluated our approach on a large dataset of real-world images from two US states. We found that incorporating additional tasks, and using a semi-supervised training approach, significantly reduced overfitting problems, allowed us to optimize more layers of the network, and resulted in higher accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06013](http://arxiv.org/abs/1901.06013)

##### PDF
[http://arxiv.org/pdf/1901.06013](http://arxiv.org/pdf/1901.06013)


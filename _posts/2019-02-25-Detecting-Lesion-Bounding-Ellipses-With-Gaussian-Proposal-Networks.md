---
layout: post
title: "Detecting Lesion Bounding Ellipses With Gaussian Proposal Networks"
date: 2019-02-25 23:17:41
categories: arXiv_CV
tags: arXiv_CV Detection
author: Yi Li
mathjax: true
---

* content
{:toc}

##### Abstract
Lesions characterized by computed tomography (CT) scans, are arguably often elliptical objects. However, current lesion detection systems are predominantly adopted from the popular Region Proposal Networks (RPNs) that only propose bounding boxes without fully leveraging the elliptical geometry of lesions. In this paper, we present Gaussian Proposal Networks (GPNs), a novel extension to RPNs, to detect lesion bounding ellipses. Instead of directly regressing the rotation angle of the ellipse as the common practice, GPN represents bounding ellipses as 2D Gaussian distributions on the image plain and minimizes the Kullback-Leibler (KL) divergence between the proposed Gaussian and the ground truth Gaussian for object localization. We show the KL divergence loss approximately incarnates the regression loss in the RPN framework when the rotation angle is 0. Experiments on the DeepLesion dataset show that GPN significantly outperforms RPN for lesion bounding ellipse detection thanks to lower localization error. GPN is open sourced at https://github.com/baidu-research/GPN

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09658](http://arxiv.org/abs/1902.09658)

##### PDF
[http://arxiv.org/pdf/1902.09658](http://arxiv.org/pdf/1902.09658)


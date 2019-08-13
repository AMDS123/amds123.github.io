---
layout: post
title: "An overlapping-free leaf segmentation method for plant point clouds"
date: 2019-08-12 06:18:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Classification
author: Dawei Li, Yan Cao, Guoliang Shi, Xin Cai, Yang Chen, Sifan Wang, Siyuan Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic leaf segmentation, as well as identification and classification methods that built upon it, are able to provide immediate monitoring for plant growth status to guarantee the output. Although 3D plant point clouds contain abundant phenotypic features, plant leaves are usually distributed in clusters and are sometimes seriously overlapped in the canopy. Therefore, it is still a big challenge to automatically segment each individual leaf from a highly crowded plant canopy in 3D for plant phenotyping purposes. In this work, we propose an overlapping-free individual leaf segmentation method for plant point clouds using the 3D filtering and facet region growing. In order to separate leaves with different overlapping situations, we develop a new 3D joint filtering operator, which integrates a Radius-based Outlier Filter (RBOF) and a Surface Boundary Filter (SBF) to help to separate occluded leaves. By introducing the facet over-segmentation and facet-based region growing, the noise in segmentation is suppressed and labeled leaf centers can expand to their whole leaves, respectively. Our method can work on point clouds generated from three types of 3D imaging platforms, and also suitable for different kinds of plant species. In experiments, it obtains a point-level cover rate of 97% for Epipremnum aureum, 99% for Monstera deliciosa, 99% for Calathea makoyana, and 87% for Hedera nepalensis sample plants. At the leaf level, our method reaches an average Recall at 100.00%, a Precision at 99.33%, and an average F-measure at 99.66%, respectively. The proposed method can also facilitate the automatic traits estimation of each single leaf (such as the leaf area, length, and width), which has potential to become a highly effective tool for plant research and agricultural engineering.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.04018](https://arxiv.org/abs/1908.04018)

##### PDF
[https://arxiv.org/pdf/1908.04018](https://arxiv.org/pdf/1908.04018)


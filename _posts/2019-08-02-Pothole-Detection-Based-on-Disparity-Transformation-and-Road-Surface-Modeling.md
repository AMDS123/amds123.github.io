---
layout: post
title: "Pothole Detection Based on Disparity Transformation and Road Surface Modeling"
date: 2019-08-02 14:55:48
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Rui Fan, Umar Ozgunalp, Brett Hosking, Ming Liu, Ioannis Pitas
mathjax: true
---

* content
{:toc}

##### Abstract
Pothole detection is one of the most important tasks for road maintenance. Computer vision approaches are generally based on either 2D road image analysis or 3D road surface modeling. However, these two categories are always used independently. Furthermore, the pothole detection accuracy is still far from satisfactory. Therefore, in this paper, we present a robust pothole detection algorithm that is both accurate and computationally efficient. A dense disparity map is first transformed to better distinguish between damaged and undamaged road areas. To achieve greater disparity transformation efficiency, golden section search and dynamic programming are utilized to estimate the transformation parameters. Otsu's thresholding method is then used to extract potential undamaged road areas from the transformed disparity map. The disparities in the extracted areas are modeled by a quadratic surface using least squares fitting. To improve disparity map modeling robustness, the surface normal is also integrated into the surface modeling process. Furthermore, random sample consensus is utilized to reduce the effects caused by outliers. By comparing the difference between the actual and modeled disparity maps, the potholes can be detected accurately. Finally, the point clouds of the detected potholes are extracted from the reconstructed 3D road surface. The experimental results show that the successful detection accuracy of the proposed system is around 98.7% and the overall pixel-level accuracy is approximately 99.6%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00894](http://arxiv.org/abs/1908.00894)

##### PDF
[http://arxiv.org/pdf/1908.00894](http://arxiv.org/pdf/1908.00894)


---
layout: post
title: "Window detection in aerial texture images of the Berlin 3D CityGML Model"
date: 2018-12-19 17:15:02
categories: arXiv_CV
tags: arXiv_CV Detection Relation
author: Franziska Lippoldt, Marius Erdt
mathjax: true
---

* content
{:toc}

##### Abstract
This article explores the usage of the state-of-art neural network Mask R-CNN to be used for window detection of texture files from the CityGML model of Berlin. As texture files are very irregular in terms of size, exposure settings and orientation, we use several parameter optimisation methods to improve the precision. Those textures are cropped from aerial photos, which implies that the angle of the facade, the exposure as well as contrast are calibrated towards the mean and not towards the single facade. The analysis of a single texture image with the human eye itself is challenging: A combination of window and facade estimation and perspective analysis is necessary in order to determine the facades and windows. We train and detect bounding boxes and masks from two data sets with image size 128 and 256. We explore various configuration optimisation methods and the relation of the Region Proposal Network, detected ROIs and the mask output. Our final results shows that the we can improve the average precision scores for both data set sizes, yet the initial AP score varies and leads to different resulting scores.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08095](http://arxiv.org/abs/1812.08095)

##### PDF
[http://arxiv.org/pdf/1812.08095](http://arxiv.org/pdf/1812.08095)


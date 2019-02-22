---
layout: post
title: "Class-independent sequential full image segmentation, using a convolutional net that finds a segment within an attention region, given a pointer pixel within this segment"
date: 2019-02-20 23:35:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN
author: Sagi Eppel
mathjax: true
---

* content
{:toc}

##### Abstract
This work examines the use of a fully convolutional net (FCN) to find an image segment, given a pixel within this segment region. The net receives an image, a point in the image and a region of interest (RoI ) mask. The net output is a binary mask of the segment in which the point is located. The region where the segment can be found is contained within the input RoI mask. Full image segmentation can be achieved by running this net sequentially, region-by-region on the image, and stitching the output segments into a single segmentation map. This simple method addresses two major challenges of image segmentation: 1) Segmentation of unknown categories that were not included in the training set. 2) Segmentation of both individual object instances (things) and non-objects (stuff), such as sky and vegetation. Hence, if the pointer pixel is located within a person in a group, the net will output a mask that covers that individual person; if the pointer point is located within the sky region, the net returns the region of the sky in the image. This is true even if no example for sky or person appeared in the training set. The net was tested and trained on the COCO panoptic dataset and achieved 67% IOU for segmentation of familiar classes (that were part of the net training set) and 53% IOU for segmentation of unfamiliar classes (that were not included in the training).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07810](http://arxiv.org/abs/1902.07810)

##### PDF
[http://arxiv.org/pdf/1902.07810](http://arxiv.org/pdf/1902.07810)


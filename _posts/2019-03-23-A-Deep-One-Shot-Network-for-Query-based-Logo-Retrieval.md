---
layout: post
title: "A Deep One-Shot Network for Query-based Logo Retrieval"
date: 2019-03-23 22:01:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Ayan Kumar Bhunia, Ankan Kumar Bhunia, Shuvozit Ghose, Abhirup Das, Partha Pratim Roy, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Logo detection in real-world scene images is an important problem with applications in advertisement and marketing. Existing general-purpose object detection methods require large training data with annotations for every logo class. These methods do not satisfy the incremental demand of logo classes necessary for practical deployment since it is practically impossible to have such annotated data for new unseen logo. In this work, we develop an easy-to-implement query-based logo detection and localization system by employing a one-shot learning technique. Given an image of a query logo, our model searches for it within a given target image and predicts the possible location of the logo by estimating a binary segmentation mask. The proposed model consists of a conditional branch and a segmentation branch. The former gives a conditional latent representation of the given query logo which is combined with feature maps of the segmentation branch at multiple scales in order to find the matching position of the query logo in a target image, should it be present. Feature matching between the latent query representation and multi-scale feature maps of segmentation branch using simple concatenation operation followed by 1x1 convolution layer makes our model scale-invariant. Despite its simplicity, our query-based logo retrieval framework achieved superior performance in FlickrLogos-32 and TopLogos-10 dataset over different existing baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01395](http://arxiv.org/abs/1811.01395)

##### PDF
[http://arxiv.org/pdf/1811.01395](http://arxiv.org/pdf/1811.01395)


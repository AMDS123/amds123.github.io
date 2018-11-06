---
layout: post
title: "Query-based Logo Segmentation"
date: 2018-11-04 16:16:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Ayan Kumar Bhunia, Ankan Kumar Bhunia, Shuvozit Ghose, Abhirup Das, Partha Pratim Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Logo detection in real-world scene images is an important problem with useful applications in advertisement and marketing. Existing general-purpose object detection methods require large training data with bounding box annotations for every logo class. These methods do not satisfy the incremental demand of logo classes necessary for practical deployment as it is practically impossible to have such paired data for every new unseen logo. In this work, we propose a query-based logo search and detection system by employing a one-shot learning technique. Given an image of a query logo, the model searches for it within a given target image and predicts the possible location of the logo by estimating a corresponding binary mask. The proposed model consists of a conditional branch and a segmentation branch. The former gives a conditional representation of a given query logo which is combined with the feature maps at multiple scales of the segmentation branch. The multi-scale conditioning allows our model to obtain a scale-invariant solution. Experimental results reveal that our model can be successfully adapted for any logo classes without separately training the whole network. Also, our query-based logo retrieval framework achieved superior performance in FlickrLogos-32 and TopLogos-10 dataset over existing baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01395](http://arxiv.org/abs/1811.01395)

##### PDF
[http://arxiv.org/pdf/1811.01395](http://arxiv.org/pdf/1811.01395)


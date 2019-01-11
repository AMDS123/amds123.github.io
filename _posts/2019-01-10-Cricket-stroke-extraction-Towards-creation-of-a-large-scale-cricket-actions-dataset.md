---
layout: post
title: "Cricket stroke extraction: Towards creation of a large-scale cricket actions dataset"
date: 2019-01-10 11:35:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Detection
author: Arpan Gupta, Sakthi Balan M
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we deal with the problem of temporal action localization for a large-scale untrimmed cricket videos dataset. Our action of interest for cricket videos is a cricket stroke played by a batsman, which is, usually, covered by cameras placed at the stands of the cricket ground at both ends of the cricket pitch. After applying a sequence of preprocessing steps, we have ~73 million frames for 1110 videos in the dataset at constant frame rate and resolution. The method of localization is a generalized one which applies a trained random forest model for CUTs detection(using summed up grayscale histogram difference features) and two linear SVM camera models(CAM1 and CAM2) for first frame detection, trained on HOG features of CAM1 and CAM2 video shots. CAM1 and CAM2 are assumed to be part of the cricket stroke. At the predicted boundary positions, the HOG features of the first frames are computed and a simple algorithm was used to combine the positively predicted camera shots. In order to make the process as generic as possible, we did not consider any domain specific knowledge, such as tracking or specific shape and motion features. The detailed analysis of our methodology is provided along with the metrics used for evaluation of individual models, and the final predicted segments. We achieved a weighted mean TIoU of 0.5097 over a small sample of the test set.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.03107](https://arxiv.org/abs/1901.03107)

##### PDF
[https://arxiv.org/pdf/1901.03107](https://arxiv.org/pdf/1901.03107)


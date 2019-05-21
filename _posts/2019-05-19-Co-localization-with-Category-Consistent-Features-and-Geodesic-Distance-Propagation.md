---
layout: post
title: "Co-localization with Category-Consistent Features and Geodesic Distance Propagation"
date: 2019-05-19 08:47:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection
author: Hieu Le, Chen-Ping Yu, Gregory Zelinsky, Dimitris Samaras
mathjax: true
---

* content
{:toc}

##### Abstract
Co-localization is the problem of localizing objects of the same class using only the set of images that contain them. This is a challenging task because the object detector must be built without negative examples that can lead to more informative supervision signals. The main idea of our method is to cluster the feature space of a generically pre-trained CNN, to find a set of CNN features that are consistently and highly activated for an object category, which we call category-consistent CNN features. Then, we propagate their combined activation map using superpixel geodesic distances for co-localization. In our first set of experiments, we show that the proposed method achieves state-of-the-art performance on three related benchmarks: PASCAL 2007, PASCAL-2012, and the Object Discovery dataset. We also show that our method is able to detect and localize truly unseen categories, on six held-out ImageNet categories with accuracy that is significantly higher than previous state-of-the-art. Our intuitive approach achieves this success without any region proposals or object detectors and can be based on a CNN that was pre-trained purely on image classification tasks without further fine-tuning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1612.03236](http://arxiv.org/abs/1612.03236)

##### PDF
[http://arxiv.org/pdf/1612.03236](http://arxiv.org/pdf/1612.03236)


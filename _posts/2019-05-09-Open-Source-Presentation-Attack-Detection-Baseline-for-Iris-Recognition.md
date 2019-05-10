---
layout: post
title: "Open Source Presentation Attack Detection Baseline for Iris Recognition"
date: 2019-05-09 03:46:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection Recognition
author: Joseph McGrath, Kevin W. Bowyer, Adam Czajka
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes the first, known to us, open source presentation attack detection (PAD) solution to distinguish between authentic iris images (possibly wearing clear contact lenses) and irises with textured contact lenses. This software can serve as a baseline in various PAD evaluations, and also as an open-source platform with an up-to-date reference method for iris PAD. The software is written in C++ and Python and uses only open source resources, such as OpenCV. This method does not incorporate iris image segmentation, which may be problematic for unknown fake samples. Instead, it makes a best guess to localize the rough position of the iris. The PAD-related features are extracted with the Binary Statistical Image Features (BSIF), which are classified by an ensemble of classifiers incorporating support vector machine, random forest and multilayer perceptron. The models attached to the current software have been trained with the NDCLD'15 database and evaluated on the independent datasets included in the LivDet-Iris 2017 competition. The software implements the functionality of retraining the classifiers with any database of authentic and attack images. The accuracy of the current version offered with this paper exceeds 99% when tested on subject-disjoint subsets of NDCLD'15, and oscillates around 85% when tested on the LivDet-Iris 2017 benchmarks, which is on par with the results obtained by the LivDet-Iris 2017 winner.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.10172](http://arxiv.org/abs/1809.10172)

##### PDF
[http://arxiv.org/pdf/1809.10172](http://arxiv.org/pdf/1809.10172)


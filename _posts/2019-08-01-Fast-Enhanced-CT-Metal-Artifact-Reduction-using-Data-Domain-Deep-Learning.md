---
layout: post
title: "Fast Enhanced CT Metal Artifact Reduction using Data Domain Deep Learning"
date: 2019-08-01 16:16:35
categories: arXiv_AI
tags: arXiv_AI Adversarial Transfer_Learning Deep_Learning
author: Muhammad Usman Ghani, W. Clem Karl
mathjax: true
---

* content
{:toc}

##### Abstract
Filtered back projection (FBP) is the most widely used method for image reconstruction in X-ray computed tomography (CT) scanners. The presence of hyper-dense materials in a scene, such as metals, can strongly attenuate X-rays, producing severe streaking artifacts in the reconstruction. These metal artifacts can greatly limit subsequent object delineation and information extraction from the images, restricting their diagnostic value. This problem is particularly acute in the security domain, where there is great heterogeneity in the objects that can appear in a scene, highly accurate decisions must be made quickly. The standard practical approaches to reducing metal artifacts in CT imagery are either simplistic non-adaptive interpolation-based projection data completion methods or direct image post-processing methods. These standard approaches have had limited success. Motivated primarily by security applications, we present a new deep-learning-based metal artifact reduction (MAR) approach that tackles the problem in the projection data domain. We treat the projection data corresponding to metal objects as missing data and train an adversarial deep network to complete the missing data in the projection domain. The subsequent complete projection data is then used with FBP to reconstruct image intended to be free of artifacts. This new approach results in an end-to-end MAR algorithm that is computationally efficient so practical and fits well into existing CT workflows allowing easy adoption in existing scanners. Training deep networks can be challenging, and another contribution of our work is to demonstrate that training data generated using an accurate X-ray simulation can be used to successfully train the deep network when combined with transfer learning using limited real data sets. We demonstrate the effectiveness and potential of our algorithm on simulated and real examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04691](http://arxiv.org/abs/1904.04691)

##### PDF
[http://arxiv.org/pdf/1904.04691](http://arxiv.org/pdf/1904.04691)


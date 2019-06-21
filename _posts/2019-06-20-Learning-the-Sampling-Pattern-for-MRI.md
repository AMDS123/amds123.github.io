---
layout: post
title: "Learning the Sampling Pattern for MRI"
date: 2019-06-20 17:13:45
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Ferdia Sherry, Martin Benning, Juan Carlos De los Reyes, Martin J. Graves, Georg Maierhofer, Guy Williams, Carola-Bibiane Sch&#xf6;nlieb, Matthias J. Ehrhardt
mathjax: true
---

* content
{:toc}

##### Abstract
The discovery of the theory of compressed sensing brought the realisation that many inverse problems can be solved even when measurements are "incomplete". This is particularly interesting in magnetic resonance imaging (MRI), where long acquisition times can limit its use. In this work, we consider the problem of learning a sparse sampling pattern that can be used to optimally balance acquisition time versus quality of the reconstructed image. We use a supervised learning approach, making the assumption that our training data is representative enough of new data acquisitions. We demonstrate that this is indeed the case, even if the training data consists of just 5 training pairs of measurements and ground-truth images; with a training set of brain images of size 192 by 192, for instance, one of the learned patterns samples only 32% of k-space, however results in reconstructions with mean SSIM 0.956 on a test set of similar images. The proposed framework is general enough to learn arbitrary sampling patterns, including common patterns such as Cartesian, spiral and radial sampling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08754](http://arxiv.org/abs/1906.08754)

##### PDF
[http://arxiv.org/pdf/1906.08754](http://arxiv.org/pdf/1906.08754)


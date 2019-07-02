---
layout: post
title: "FAIM -- A ConvNet Method for Unsupervised 3D Medical Image Registration"
date: 2019-06-28 20:43:34
categories: arXiv_CV
tags: arXiv_CV Face
author: Dongyang Kuang, Tanya Schmah
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new unsupervised learning algorithm, "FAIM", for 3D medical image registration. With a different architecture than the popular "U-net", the network takes a pair of full image volumes and predicts the displacement fields needed to register source to target. Compared with "U-net" based registration networks such as VoxelMorph, FAIM has fewer trainable parameters but can achieve higher registration accuracy as judged by Dice score on region labels in the Mindboggle-101 dataset. Moreover, with the proposed penalty loss on negative Jacobian determinants, FAIM produces deformations with many fewer "foldings", i.e. regions of non-invertibility where the surface folds over itself. In our experiment, we varied the strength of this penalty and investigated changes in registration accuracy and non-invertibility in terms of number of "folding" locations. We found that FAIM is able to maintain both the advantages of higher accuracy and fewer "folding" locations over VoxelMorph, over a range of hyper-parameters (with the same values used for both networks). Further, when trading off registration accuracy for better invertibility, FAIM required less sacrifice of registration accuracy. Codes for this paper will be released upon publication.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09243](http://arxiv.org/abs/1811.09243)

##### PDF
[http://arxiv.org/pdf/1811.09243](http://arxiv.org/pdf/1811.09243)


---
layout: post
title: "Deep learning based 2.5D flow field estimation for maximum intensity projections of 4D optical coherence tomography"
date: 2018-10-26 07:10:51
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Deep_Learning Quantitative
author: Max-Heinrich Laves, L&#xfc;der A. Kahrs, Tobias Ortmaier
mathjax: true
---

* content
{:toc}

##### Abstract
In laser microsurgery, image-based control of the ablation laser can lead to higher accuracy and patient safety. However, camera-based image acquisition lacks the subcutaneous tissue perception. Optical coherence tomography (OCT) as high-resolution imaging modality yields transsectional images of tissue and can provide the missing depth information. Therefore, this paper deals with the tracking of distinctive subcutaneous structures on OCTs for automated control of ablation lasers in microsurgery. We present a deep learning based tracking scheme for concise representations of subsequent 3D OCT volumes. For each of the volume, a compact representation is created by calculating maximum intensity projections and projecting the depth value, were the maximum intensity voxel is found, onto an image plane. These depth images are then used for tracking by estimating the dense optical flow and depth changes with a self-supervisely trained convolutional neural network. Tracking performances are evaluated on a dataset of ex vivo human temporal bone with rigid ground truth transformations and on an in vivo sequence of human skin with non-rigid transformations. First quantitative evaluation reveals a mean endpoint error of 2.27voxel for scene flow estimation. Object tracking on 4D OCT data enables its use for sub-epithelial tracking of tissue structures for image-guidance in automated laser incision control for microsurgery.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11205](http://arxiv.org/abs/1810.11205)

##### PDF
[http://arxiv.org/pdf/1810.11205](http://arxiv.org/pdf/1810.11205)


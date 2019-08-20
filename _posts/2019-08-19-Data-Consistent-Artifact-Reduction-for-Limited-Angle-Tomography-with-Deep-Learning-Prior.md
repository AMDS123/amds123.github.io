---
layout: post
title: "Data Consistent Artifact Reduction for Limited Angle Tomography with Deep Learning Prior"
date: 2019-08-19 13:28:35
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Yixing Huang, Alexander Preuhs, Guenter Lauritsch, Michael Manhart, Xiaolin Huang, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Robustness of deep learning methods for limited angle tomography is challenged by two major factors: a) due to insufficient training data the network may not generalize well to unseen data; b) deep learning methods are sensitive to noise. Thus, generating reconstructed images directly from a neural network appears inadequate. We propose to constrain the reconstructed images to be consistent with the measured projection data, while the unmeasured information is complemented by learning based methods. For this purpose, a data consistent artifact reduction (DCAR) method is introduced: First, a prior image is generated from an initial limited angle reconstruction via deep learning as a substitute for missing information. Afterwards, a conventional iterative reconstruction algorithm is applied, integrating the data consistency in the measured angular range and the prior information in the missing angular range. This ensures data integrity in the measured area, while inaccuracies incorporated by the deep learning prior lie only in areas where no information is acquired. The proposed DCAR method achieves significant image quality improvement: for 120-degree cone-beam limited angle tomography more than 10% RMSE reduction in noise-free case and more than 24% RMSE reduction in noisy case compared with a state-of-the-art U-Net based method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06792](http://arxiv.org/abs/1908.06792)

##### PDF
[http://arxiv.org/pdf/1908.06792](http://arxiv.org/pdf/1908.06792)


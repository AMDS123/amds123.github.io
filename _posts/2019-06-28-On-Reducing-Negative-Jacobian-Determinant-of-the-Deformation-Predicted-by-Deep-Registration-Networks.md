---
layout: post
title: "On Reducing Negative Jacobian Determinant of the Deformation Predicted by Deep Registration Networks"
date: 2019-06-28 20:42:12
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Dongyang Kuang
mathjax: true
---

* content
{:toc}

##### Abstract
Image registration is a fundamental step in medical image analysis. Ideally, the transformation that registers one image to another should be a diffeomorphism that is both invertible and smooth. Traditional methods like geodesic shooting approach the problem via differential geometry, with theoretical guarantees that the resulting transformation will be smooth and invertible. Most previous research using unsupervised deep neural networks for registration have used a local smoothness constraint (typically, a spatial variation loss) to address the smoothness issue. These networks usually produce non-invertible transformations with ``folding'' in multiple voxel locations, indicated by a negative determinant of the Jacobian matrix of the transformation. While using a loss function that specifically penalizes the folding is a straightforward solution, this usually requires carefully tuning the regularization strength, especially when there are also other losses. In this paper we address this problem from a different angle, by investigating possible training mechanisms that will help the network avoid negative Jacobians and produce smoother deformations. We contribute two independent ideas in this direction. Both ideas greatly reduce the number of folding locations in the predicted deformation, without making changes to the hyperparameters or the architecture used in the existing baseline registration network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00068](http://arxiv.org/abs/1907.00068)

##### PDF
[http://arxiv.org/pdf/1907.00068](http://arxiv.org/pdf/1907.00068)


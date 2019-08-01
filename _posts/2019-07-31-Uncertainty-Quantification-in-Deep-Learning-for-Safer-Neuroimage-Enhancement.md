---
layout: post
title: "Uncertainty Quantification in Deep Learning for Safer Neuroimage Enhancement"
date: 2019-07-31 11:17:45
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Image_Enhancement Inference Deep_Learning
author: Ryutaro Tanno, Daniel Worrall, Enrico Kaden, Aurobrata Ghosh, Francesco Grussu, Alberto Bizzi, Stamatios N. Sotiropoulos, Antonio Criminisi, Daniel C. Alexander
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning (DL) has shown great potential in medical image enhancement problems, such as super-resolution or image synthesis. However, to date, little consideration has been given to uncertainty quantification over the output image. Here we introduce methods to characterise different components of uncertainty in such problems and demonstrate the ideas using diffusion MRI super-resolution. Specifically, we propose to account for $intrinsic$ uncertainty through a heteroscedastic noise model and for $parameter$ uncertainty through approximate Bayesian inference, and integrate the two to quantify $predictive$ uncertainty over the output image. Moreover, we introduce a method to propagate the predictive uncertainty on a multi-channelled image to derived scalar parameters, and separately quantify the effects of intrinsic and parameter uncertainty therein. The methods are evaluated for super-resolution of two different signal representations of diffusion MR images---DTIs and Mean Apparent Propagator MRI---and their derived quantities such as MD and FA, on multiple datasets of both healthy and pathological human brains. Results highlight three key benefits of uncertainty modelling for improving the safety of DL-based image enhancement systems. Firstly, incorporating uncertainty improves the predictive performance even when test data departs from training data. Secondly, the predictive uncertainty highly correlates with errors, and is therefore capable of detecting predictive "failures". Results demonstrate that such an uncertainty measure enables subject-specific and voxel-wise risk assessment of the output images. Thirdly, we show that the method for decomposing predictive uncertainty into its independent sources provides high-level "explanations" for the performance by quantifying how much uncertainty arises from the inherent difficulty of the task or the limited training examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13418](http://arxiv.org/abs/1907.13418)

##### PDF
[http://arxiv.org/pdf/1907.13418](http://arxiv.org/pdf/1907.13418)


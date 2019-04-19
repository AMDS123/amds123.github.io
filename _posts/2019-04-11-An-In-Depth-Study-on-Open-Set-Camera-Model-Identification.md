---
layout: post
title: "An In-Depth Study on Open-Set Camera Model Identification"
date: 2019-04-11 14:48:55
categories: arXiv_CV
tags: arXiv_CV GAN CNN Recognition
author: Pedro Ribeiro Mendes J&#xfa;nior, Luca Bondi, Paolo Bestagini, Stefano Tubaro, Anderson Rocha
mathjax: true
---

* content
{:toc}

##### Abstract
Camera model identification refers to the problem of linking a picture to the camera model used to shoot it. As this might be an enabling factor in different forensic applications to single out possible suspects (e.g., detecting the author of child abuse or terrorist propaganda material), many accurate camera model attribution methods have been developed in the literature. One of their main drawbacks, however, is the typical closed-set assumption of the problem. This means that an investigated photograph is always assigned to one camera model within a set of known ones present during investigation, i.e., training time, and the fact that the picture can come from a completely unrelated camera model during actual testing is usually ignored. Under realistic conditions, it is not possible to assume that every picture under analysis belongs to one of the available camera models. To deal with this issue, in this paper, we present the first in-depth study on the possibility of solving the camera model identification problem in open-set scenarios. Given a photograph, we aim at detecting whether it comes from one of the known camera models of interest or from an unknown device. We compare different feature extraction algorithms and classifiers specially targeting open-set recognition. We also evaluate possible open-set training protocols that can be applied along with any open-set classifier. More specifically, we evaluate one training protocol targeted for open-set classifiers with deep features. We observe that a simpler version of those training protocols works with similar results to the one that requires extra data, which can be useful in many applications in which deep features are employed. Thorough testing on independent datasets shows that it is possible to leverage a recently proposed convolutional neural network as feature extractor paired with a properly trained open-set classifier...

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08497](http://arxiv.org/abs/1904.08497)

##### PDF
[http://arxiv.org/pdf/1904.08497](http://arxiv.org/pdf/1904.08497)


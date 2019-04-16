---
layout: post
title: "ZerNet: Convolutional Neural Networks on Arbitrary Surfaces via Zernike Local Tangent Space Estimation"
date: 2019-04-13 03:44:26
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Recognition
author: Zhiyu Sun, Ethan Rooke, Yusen He, Jia Lu, Stephen Baek
mathjax: true
---

* content
{:toc}

##### Abstract
In many fields of science and engineering, geometric features play a key role in understanding certain quantity or phenomena. Recently, convolutional neural networks (CNNs) have been shown to possess a promising capability of extracting and codifying features from visual information. However, the application of such capable CNNs has been quite limited to mostly computer vision problems where the visual information is inherently given on a grid-like structure. This, unfortunately, was not the case for the geometry processing community, where many visual recognition problems are defined on arbitrary surfaces (2D-manifolds). Technical difficulties hindering the generalization of CNNs to arbitrary-shaped manifold are rooted in the lacks of such key elements including the canonical grid-like representation, the notion of consistent orientation, and a compatible local topology across the domain. Unfortunately, except for a few pioneering works, only very little has been studied in this regard. To this end, in this paper, we propose a novel mathematical formulation to extend CNNs onto two-dimensional (2D) manifold domains. More specifically, we approximate a tensor field defined over a manifold using orthogonal basis functions, called Zernike polynomials, on local tangent spaces. We prove that the convolution of two functions can be represented as a simple dot product between Zernike polynomial coefficients. We also prove that a rotation of a convolution kernel equates to a set of 2 by 2 rotation matrices applied to Zernike polynomial coefficients, which can be critical in manifold domains. As such, the key contribution of this work resides in a concise but rigorous mathematical generalization of the CNN building blocks. Furthermore, comparative to the other state-of-the-art methods, our method demonstrates substantially better performance on both classification and regression tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01082](http://arxiv.org/abs/1812.01082)

##### PDF
[http://arxiv.org/pdf/1812.01082](http://arxiv.org/pdf/1812.01082)


---
layout: post
title: "Automatic discrete differentiation and its applications"
date: 2019-05-21 13:21:46
categories: arXiv_AI
tags: arXiv_AI
author: Ai Ishikawa, Takaharu Yaguchi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a method for automatically deriving energy-preserving numerical methods for the Euler-Lagrange equation and the Hamilton equation is proposed. The derived energy-preserving scheme is based on the discrete gradient method. In the proposed approach, the discrete gradient, which is a key tool for designing the scheme, is automatically computed by a similar algorithm to the automatic differentiation. Besides, the discrete gradient coincides with the usual gradient if the two arguments required to define the discrete gradient are the same. Hence the proposed method is an extension of the automatic differentiation in the sense that the proposed method derives not only the discrete gradient but also the usual gradient. Due to this feature, both energy-preserving integrators and variational (and hence symplectic) integrators can be implemented in the same programming code simultaneously. This allows users to freely switch between the energy-preserving numerical method and the symplectic numerical method in accordance with the problem-setting and other requirements. As applications, an energy-preserving numerical scheme for a nonlinear wave equation and a training algorithm of artificial neural networks derived from an energy-dissipative numerical scheme are shown.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08604](http://arxiv.org/abs/1905.08604)

##### PDF
[http://arxiv.org/pdf/1905.08604](http://arxiv.org/pdf/1905.08604)


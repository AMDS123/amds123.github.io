---
layout: post
title: "Differential Scene Flow from Light Field Gradients"
date: 2019-07-26 15:47:14
categories: arXiv_CV
tags: arXiv_CV
author: Sizhuo Ma, Brandon M. Smith, Mohit Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents novel techniques for recovering 3D dense scene flow, based on differential analysis of 4D light fields. The key enabling result is a per-ray linear equation, called the ray flow equation, that relates 3D scene flow to 4D light field gradients. The ray flow equation is invariant to 3D scene structure and applicable to a general class of scenes, but is under-constrained (3 unknowns per equation). Thus, additional constraints must be imposed to recover motion. We develop two families of scene flow algorithms by leveraging the structural similarity between ray flow and optical flow equations: local 'Lucas-Kanade' ray flow and global 'Horn-Schunck' ray flow, inspired by corresponding optical flow methods. We also develop a combined local-global method by utilizing the correspondence structure in the light fields. We demonstrate high precision 3D scene flow recovery for a wide range of scenarios, including rotation and non-rigid motion. We analyze the theoretical and practical performance limits of the proposed techniques via the light field structure tensor, a 3x3 matrix that encodes the local structure of light fields. We envision that the proposed analysis and algorithms will lead to design of future light-field cameras that are optimized for motion sensing, in addition to depth sensing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11637](http://arxiv.org/abs/1907.11637)

##### PDF
[http://arxiv.org/pdf/1907.11637](http://arxiv.org/pdf/1907.11637)


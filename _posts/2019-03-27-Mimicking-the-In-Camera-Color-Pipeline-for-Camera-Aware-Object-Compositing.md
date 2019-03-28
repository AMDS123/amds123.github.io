---
layout: post
title: "Mimicking the In-Camera Color Pipeline for Camera-Aware Object Compositing"
date: 2019-03-27 04:41:19
categories: arXiv_CV
tags: arXiv_CV
author: Jun Gao, Xiao Li, Liwei Wang, Sanja Fidler, Stephen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for compositing virtual objects into a photograph such that the object colors appear to have been processed by the photo's camera imaging pipeline. Compositing in such a camera-aware manner is essential for high realism, and it requires the color transformation in the photo's pipeline to be inferred, which is challenging due to the inherent one-to-many mapping that exists from a scene to a photo. To address this problem for the case of a single photo taken from an unknown camera, we propose a dual-learning approach in which the reverse color transformation (from the photo to the scene) is jointly estimated. Learning of the reverse transformation is used to facilitate learning of the forward mapping, by enforcing cycle consistency of the two processes. We additionally employ a feature sharing schema to extract evidence from the target photo in the reverse mapping to guide the forward color transformation. Our dual-learning approach achieves object compositing results that surpass those of alternative techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11248](http://arxiv.org/abs/1903.11248)

##### PDF
[http://arxiv.org/pdf/1903.11248](http://arxiv.org/pdf/1903.11248)


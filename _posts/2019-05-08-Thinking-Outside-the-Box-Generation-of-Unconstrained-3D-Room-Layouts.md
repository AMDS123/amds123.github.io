---
layout: post
title: "Thinking Outside the Box: Generation of Unconstrained 3D Room Layouts"
date: 2019-05-08 14:43:26
categories: arXiv_CV
tags: arXiv_CV Inference Detection
author: Henry Howard-Jenkins, Shuda Li, Victor Prisacariu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for room layout estimation that does not rely on the typical box approximation or Manhattan world assumption. Instead, we reformulate the geometry inference problem as an instance detection task, which we solve by directly regressing 3D planes using an R-CNN. We then use a variant of probabilistic clustering to combine the 3D planes regressed at each frame in a video sequence, with their respective camera poses, into a single global 3D room layout estimate. Finally, we showcase results which make no assumptions about perpendicular alignment, so can deal effectively with walls in any alignment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03105](http://arxiv.org/abs/1905.03105)

##### PDF
[http://arxiv.org/pdf/1905.03105](http://arxiv.org/pdf/1905.03105)


---
layout: post
title: "Patch alignment manifold matting"
date: 2019-04-16 10:52:24
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Xuelong Li, Kang Liu, Yongsheng Dong, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Image matting is generally modeled as a space transform from the color space to the alpha space. By estimating the alpha factor of the model, the foreground of an image can be extracted. However, there is some dimensional information redundancy in the alpha space. It usually leads to the misjudgments of some pixels near the boundary between the foreground and the background. In this paper, a manifold matting framework named Patch Alignment Manifold Matting is proposed for image matting. In particular, we first propose a part modeling of color space in the local image patch. We then perform whole alignment optimization for approximating the alpha results using subspace reconstructing error. Furthermore, we utilize Nesterov's algorithm to solve the optimization problem. Finally, we apply some manifold learning methods in the framework, and obtain several image matting methods, such as named ISOMAP matting and its derived Cascade ISOMAP matting. The experimental results reveal that the manifold matting framework and its two examples are effective when compared with several representative matting methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07588](http://arxiv.org/abs/1904.07588)

##### PDF
[http://arxiv.org/pdf/1904.07588](http://arxiv.org/pdf/1904.07588)


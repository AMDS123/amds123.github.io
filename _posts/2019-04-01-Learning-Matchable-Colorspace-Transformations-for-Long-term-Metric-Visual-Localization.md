---
layout: post
title: "Learning Matchable Colorspace Transformations for Long-term Metric Visual Localization"
date: 2019-04-01 19:38:56
categories: arXiv_CV
tags: arXiv_CV
author: Lee Clement, Mona Gridseth, Justin Tomasi, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
Long-term metric localization is an essential capability of autonomous mobile robots, but remains challenging for vision-based systems in the presence of appearance change caused by lighting, weather or seasonal variations. While experience-based mapping has proven to be an effective technique for enabling visual localization across appearance change, the number of experiences required for reliable long-term localization can be large, and methods for reducing the necessary number of experiences are desired. Taking inspiration from physics-based models of color constancy, we propose a method for learning a nonlinear mapping from RGB to grayscale colorspaces that maximizes the number of feature matches for images captured under varying lighting and weather conditions. Our key insight is that useful image transformations can be learned by approximating conventional non-differentiable localization pipelines with a differentiable learned model that can predict a convenient measure of localization quality, such as the number of feature matches, for a given pair of images. Moreover, we find that the generality of appearance-robust RGB-to-grayscale mappings can be improved by incorporating a learned low-dimensional context feature computed for a specific image pair. Using synthetic and real-world datasets, we show that our method substantially improves feature matching across day-night cycles and presents a viable strategy for significantly improving the efficiency of experience-based visual localization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01080](http://arxiv.org/abs/1904.01080)

##### PDF
[http://arxiv.org/pdf/1904.01080](http://arxiv.org/pdf/1904.01080)


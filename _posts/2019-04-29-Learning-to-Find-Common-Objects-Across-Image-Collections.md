---
layout: post
title: "Learning to Find Common Objects Across Image Collections"
date: 2019-04-29 20:26:40
categories: arXiv_CV
tags: arXiv_CV Optimization Inference Recognition
author: Amirreza Shaban, Amir Rahimi, Stephen Gould, Byron Boots, Richard Hartley
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of finding a set of images containing a common, but unknown, object category from a collection of image proposals. Our formulation assumes that we are given a collection of bags where each bag is a set of image proposals. Our goal is to select one image from each bag such that the selected images are of the same object category. We model the selection as an energy minimization problem with unary and pairwise potential functions. Inspired by recent few-shot learning algorithms, we propose an approach to learn the potential functions directly from the data. Furthermore, we propose a fast and simple greedy inference algorithm for energy minimization. We evaluate our approach on few-shot common object recognition and object co-localization tasks. Our experiments show that learning the pairwise and unary terms greatly improves the performance of the model over several well-known methods for these tasks. The proposed greedy optimization algorithm achieves performance comparable to state-of-the-art structured inference algorithms while being ~10 times faster. The code is publicly available on https://github.com/haamoon/finding_common_object.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12936](http://arxiv.org/abs/1904.12936)

##### PDF
[http://arxiv.org/pdf/1904.12936](http://arxiv.org/pdf/1904.12936)


---
layout: post
title: "IGNOR: Image-guided Neural Object Rendering"
date: 2018-11-26 22:24:25
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Justus Thies, Michael Zollh&#xf6;fer, Christian Theobalt, Marc Stamminger, Matthias Nie&#xdf;ner
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new learning-based novel view synthesis approach for scanned objects that is trained based on a set of multi-view images. Instead of using texture mapping or hand-designed image-based rendering, we directly train a deep neural network to synthesize a view-dependent image of an object. First, we employ a coverage-based nearest neighbour look-up to retrieve a set of reference frames that are explicitly warped to a given target view using cross-projection. Our network then learns to best composite the warped images. This enables us to generate photo-realistic results, while not having to allocate capacity on `remembering' object appearance. Instead, the multi-view images can be reused. While this works well for diffuse objects, cross-projection does not generalize to view-dependent effects. Therefore, we propose a decomposition network that extracts view-dependent effects and that is trained in a self-supervised manner. After decomposition, the diffuse shading is cross-projected, while the view-dependent layer of the target view is regressed. We show the effectiveness of our approach both qualitatively and quantitatively on real as well as synthetic data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10720](http://arxiv.org/abs/1811.10720)

##### PDF
[http://arxiv.org/pdf/1811.10720](http://arxiv.org/pdf/1811.10720)


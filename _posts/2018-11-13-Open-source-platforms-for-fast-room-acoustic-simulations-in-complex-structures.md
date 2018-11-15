---
layout: post
title: "Open-source platforms for fast room acoustic simulations in complex structures"
date: 2018-11-13 14:41:25
categories: arXiv_SD
tags: arXiv_SD Face
author: Matthieu Aussal, Robin Gueguen
mathjax: true
---

* content
{:toc}

##### Abstract
This article presents new numerical simulation tools, respectively developed in Matlab and Blender softwares. Available in open-source under the GPL 3.0 license, it uses a ray-tracing/image-sources hybrid method to calculate the room acoustics for large meshes. Performances are optimized to solve problems of significant size (typically more than 100,000 surface elements and about a million of rays). For this purpose, a Divide and Conquer approach with a recursive binary tree structure has been implemented to reduce the quadratic complexity of the ray/element interactions to near-linear. Thus, execution times are less sensitive to the mesh density, which allows simulations of complex geometry. After ray propagation, a hybrid method leads to image-sources, which can be visually analyzed to localize sound map. Finally, impulse responses are constructed from the image-sources and FIR filters are proposed natively over 8 octave bands, taking into account material absorption properties and propagation medium. This algorithm is validated by comparisons with theoretical test cases. Furthermore, an example on a quite complex case, namely the ancient theater of Orange is presented.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05784](http://arxiv.org/abs/1811.05784)

##### PDF
[http://arxiv.org/pdf/1811.05784](http://arxiv.org/pdf/1811.05784)


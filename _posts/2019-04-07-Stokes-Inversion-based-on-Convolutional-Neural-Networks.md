---
layout: post
title: "Stokes Inversion based on Convolutional Neural Networks"
date: 2019-04-07 19:03:45
categories: arXiv_CV
tags: arXiv_CV CNN
author: A. Asensio Ramos (1,2), C. Diaz Baso (3) ((1) Instituto de Astrofisica de Canarias, (2) Universidad de La Laguna, (3) Institute for Solar Physics, Dept. of Astronomy, Stockholm University)
mathjax: true
---

* content
{:toc}

##### Abstract
Spectropolarimetric inversions are routinely used in the field of Solar Physics for the extraction of physical information from observations. The application to two-dimensional fields of view often requires the use of supercomputers with parallelized inversion codes. Even in this case, the computing time spent on the process is still very large. Our aim is to develop a new inversion code based on the application of convolutional neural networks that can quickly provide a three-dimensional cube of thermodynamical and magnetic properties from the interpretation of two-dimensional maps of Stokes profiles. We train two different architectures of fully convolutional neural networks. To this end, we use the synthetic Stokes profiles obtained from two snapshots of three-dimensional magneto-hydrodynamic numerical simulations of different structures of the solar atmosphere. We provide an extensive analysis of the new inversion technique, showing that it infers the thermodynamical and magnetic properties with a precision comparable to that of standard inversion techniques. However, it provides several key improvements: our method is around one million times faster, it returns a three-dimensional view of the physical properties of the region of interest in geometrical height, it provides quantities that cannot be obtained otherwise (pressure and Wilson depression) and the inferred properties are decontaminated from the blurring effect of instrumental point spread functions for free. The code is provided for free on a specific repository, with options for training and evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03714](http://arxiv.org/abs/1904.03714)

##### PDF
[http://arxiv.org/pdf/1904.03714](http://arxiv.org/pdf/1904.03714)


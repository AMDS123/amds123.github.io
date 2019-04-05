---
layout: post
title: "Geometry in Active Learning for Binary and Multi-class Image Segmentation"
date: 2019-04-04 08:28:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Ksenia Konyushkova, Raphael Sznitman, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an active learning approach to image segmentation that exploits geometric priors to speed up and streamline the annotation process. It can be applied for both background-foreground and multi-class segmentation tasks in 2D images and 3D image volumes. Our approach combines geometric smoothness priors in the image space with more traditional uncertainty measures to estimate which pixels or voxels are the most informative, and thus should to be annotated next. For multi-class settings, we additionally introduce two novel criteria for uncertainty. In the 3D case, we use the resulting uncertainty measure to select voxels lying on a planar patch, which makes batch annotation much more convenient for the end user compared to the setting where voxels are randomly distributed in a volume. The planar patch is found using a branch-and-bound algorithm that looks for a 2D patch in a 3D volume where the most informative instances are located. We evaluate our approach on Electron Microscopy and Magnetic Resonance image volumes, as well as on regular images of horses and faces. We demonstrate a substantial performance increase over other approaches thanks to the use of geometric priors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1606.09029](http://arxiv.org/abs/1606.09029)

##### PDF
[http://arxiv.org/pdf/1606.09029](http://arxiv.org/pdf/1606.09029)


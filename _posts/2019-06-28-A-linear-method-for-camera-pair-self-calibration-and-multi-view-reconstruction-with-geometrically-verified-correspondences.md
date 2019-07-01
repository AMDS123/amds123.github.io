---
layout: post
title: "A linear method for camera pair self-calibration and multi-view reconstruction with geometrically verified correspondences"
date: 2019-06-28 07:45:19
categories: arXiv_CV
tags: arXiv_CV Relation
author: Nikos Melanitis, Petros Maragos
mathjax: true
---

* content
{:toc}

##### Abstract
We examine 3D reconstruction of architectural scenes in unordered sets of uncalibrated images. We introduce a linear method to self-calibrate and find the metric reconstruction of a camera pair. We assume unknown and different focal lengths but otherwise known internal camera parameters and a known projective reconstruction of the camera pair. We recover two possible camera configurations in space and use the Cheirality condition, that all 3D scene points are in front of both cameras, to disambiguate the solution. We show in two Theorems, first that the two solutions are in mirror positions and then the relations between their viewing directions. Our new method performs on par (median rotation error $\Delta R = 3.49^{\circ}$) with the standard approach of Kruppa equations ($\Delta R = 3.77^{\circ}$) for self-calibration and 5-Point algorithm for calibrated metric reconstruction of a camera pair. We reject erroneous image correspondences by introducing a method to examine whether point correspondences appear in the same order along $x, y$ image axes in image pairs. We evaluate this method by its precision and recall and show that it improves the robustness of point matches in architectural and general scenes. Finally, we integrate all the introduced methods to a 3D reconstruction pipeline. We utilize the numerous camera pair metric recontructions using rotation-averaging algorithms and a novel method to average focal length estimates.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12075](http://arxiv.org/abs/1906.12075)

##### PDF
[http://arxiv.org/pdf/1906.12075](http://arxiv.org/pdf/1906.12075)


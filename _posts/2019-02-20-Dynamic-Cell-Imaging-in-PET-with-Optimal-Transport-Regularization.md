---
layout: post
title: "Dynamic Cell Imaging in PET with Optimal Transport Regularization"
date: 2019-02-20 11:45:14
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking Optimization
author: Bernhard Schmitzer, Klaus P. Sch&#xe4;fers, Benedikt Wirth
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel dynamic image reconstruction method from PET listmode data that could be particularly suited to tracking single or small numbers of cells. In contrast to conventional PET reconstruction the proposed method combines the information from all detected events not only to reconstruct the dynamic evolution of the radionuclide distribution, but also to simultaneously improve the reconstruction at each single time point by enforcing temporal consistency. This is achieved via the use of optimal transport regularization where in principle, among all possible temporally evolving radionuclide distributions consistent with the PET measurement, the one is chosen with least kinetic motion energy. The reconstruction is found by convex optimization so that there is no dependence on the initialization of the method. We study its behaviour on simulated data of a human PET system and demonstrate its robustness even in settings with very low radioactivity. In contrast to previously reported cell tracking algorithms, the proposed technique is oblivious to the number of tracked cells. Without any additional complexity one or multiple cells can be reconstructed, and the model automatically determines the number of particles. As one of the results, four radiolabelled cells moving with a velocity of 3.1 mm/s and a PET recorded count rate of 1.1 cps (for each cell) could be simultaneously tracked with a tracking accuracy of 5.4 mm inside a simulated human body.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07521](http://arxiv.org/abs/1902.07521)

##### PDF
[http://arxiv.org/pdf/1902.07521](http://arxiv.org/pdf/1902.07521)


---
layout: post
title: "Accurate Global Trajectory Alignment using Poles and Road Markings"
date: 2019-03-25 09:40:11
categories: arXiv_CV
tags: arXiv_CV
author: Haohao Hu, Marc Sons, Christoph Stiller
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, digital maps are indispensable for automated driving. However, due to the low precision and reliability of GNSS particularly in urban areas, fusing trajectories of independent recording sessions and different regions is a challenging task. To bypass the flaws from direct incorporation of GNSS measurements for geo-referencing, the usage of aerial imagery seems promising. Furthermore, more accurate geo-referencing improves the global map accuracy and allows to estimate the sensor calibration error. In this paper, we present a novel geo-referencing approach to align trajectories to aerial imagery using poles and road markings. To match extracted features from sensor observations to aerial imagery landmarks robustly, a RANSAC-based matching approach is applied in a sliding window. For that, we assume that the trajectories are roughly referenced to the imagery which can be achieved by rough GNSS measurements from a low-cost GNSS receiver. Finally, we align the initial trajectories precisely to the aerial imagery by minimizing a geometric cost function comprising all determined matches. Evaluations performed on data recorded in Karlsruhe, Germany show that our algorithm yields trajectories which are accurately referenced to the used aerial imagery.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10205](http://arxiv.org/abs/1903.10205)

##### PDF
[http://arxiv.org/pdf/1903.10205](http://arxiv.org/pdf/1903.10205)


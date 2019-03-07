---
layout: post
title: "Robust Video Background Identification by Dominant Rigid Motion Estimation"
date: 2019-03-06 08:11:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Quantitative
author: Kaimo Lin, Nianjuan Jiang, Loong Fah Cheong, Jiangbo Lu, Xun Xu
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to identify the static background in videos captured by a moving camera is an important pre-requisite for many video applications (e.g. video stabilization, stitching, and segmentation). Existing methods usually face difficulties when the foreground objects occupy a larger area than the background in the image. Many methods also cannot scale up to handle densely sampled feature trajectories. In this paper, we propose an efficient local-to-global method to identify background, based on the assumption that as long as there is sufficient camera motion, the cumulative background features will have the largest amount of trajectories. Our motion model at the two-frame level is based on the epipolar geometry so that there will be no over-segmentation problem, another issue that plagues the 2D motion segmentation approach. Foreground objects erroneously labelled due to intermittent motions are also taken care of by checking their global consistency with the final estimated background motion. Lastly, by virtue of its efficiency, our method can deal with densely sampled trajectories. It outperforms several state-of-the-art motion segmentation methods on public datasets, both quantitatively and qualitatively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02232](http://arxiv.org/abs/1903.02232)

##### PDF
[http://arxiv.org/pdf/1903.02232](http://arxiv.org/pdf/1903.02232)


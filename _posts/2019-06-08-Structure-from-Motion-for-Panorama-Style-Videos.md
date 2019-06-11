---
layout: post
title: "Structure from Motion for Panorama-Style Videos"
date: 2019-06-08 23:29:45
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Chris Sweeney, Aleksander Holynski, Brian Curless, Steve M Seitz
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel Structure from Motion pipeline that is capable of reconstructing accurate camera poses for panorama-style video capture without prior camera intrinsic calibration. While panorama-style capture is common and convenient, previous reconstruction methods fail to obtain accurate reconstructions due to the rotation-dominant motion and small baseline between views. Our method is built on the assumption that the camera motion approximately corresponds to motion on a sphere, and we introduce three novel relative pose methods to estimate the fundamental matrix and camera distortion for spherical motion. These solvers are efficient and robust, and provide an excellent initialization for bundle adjustment. A soft prior on the camera poses is used to discourage large deviations from the spherical motion assumption when performing bundle adjustment, which allows cameras to remain properly constrained for optimization in the absence of well-triangulated 3D points. To validate the effectiveness of the proposed method we evaluate our approach on both synthetic and real-world data, and demonstrate that camera poses are accurate enough for multiview stereo.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03539](http://arxiv.org/abs/1906.03539)

##### PDF
[http://arxiv.org/pdf/1906.03539](http://arxiv.org/pdf/1906.03539)


---
layout: post
title: "HE-SLAM: a Stereo SLAM System Based on Histogram Equalization and ORB Features"
date: 2019-02-09 03:23:41
categories: arXiv_RO
tags: arXiv_RO Detection SLAM
author: Yinghong Fang, Guangcun Shan, Xin Li, Wenliang Liu, Tian Wang, Hichem Snoussi
mathjax: true
---

* content
{:toc}

##### Abstract
In the real-life environments, due to the sudden appearance of windows, lights, and objects blocking the light source, the visual SLAM system can easily capture the low-contrast images caused by over-exposure or over-darkness. At this time, the direct method of estimating camera motion based on pixel luminance information is infeasible, and it is often difficult to find enough valid feature points without image processing. This paper proposed HE-SLAM, a new method combining histogram equalization and ORB feature extraction, which can be robust in more scenes, especially in stages with low-contrast images. Because HE-SLAM uses histogram equalization to improve the contrast of images, it can extract enough valid feature points in low-contrast images for subsequent feature matching, keyframe selection, bundle adjustment, and loop closure detection. The proposed HE-SLAM has been tested on the popular datasets (such as KITTI and EuRoc), and the real-time performance and robustness of the system are demonstrated by comparing system runtime and the mean square root error (RMSE) of absolute trajectory error (ATE) with state-of-the-art methods like ORB-SLAM2.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03365](http://arxiv.org/abs/1902.03365)

##### PDF
[http://arxiv.org/pdf/1902.03365](http://arxiv.org/pdf/1902.03365)


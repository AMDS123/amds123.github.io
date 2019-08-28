---
layout: post
title: "LiDARTag: A Real-Time Fiducial Tag using Point Clouds"
date: 2019-08-23 22:10:39
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection SLAM
author: Jiunn-Kai Huang, Maani Ghaffari, Ross Hartley, Lu Gan, Ryan M. Eustice, Jessy W. Grizzle
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based fiducial markers are widely used in robotics and computer vision problems such as object tracking in cluttered or textureless environments, camera (and multi-sensor) calibration tasks, or vision-based simultaneous localization and mapping (SLAM). The state-of-the-art fiducial marker detection algorithms rely on consistency of the ambient lighting. This paper introduces LiDARTag, a novel fiducial tag design and detection algorithm suitable for light detection and ranging (LiDAR) point clouds. The proposed tag runs in real-time and can process data faster than the currently available LiDAR sensors frequencies. Due to the nature of the LiDAR's sensor, rapidly changing ambient lighting will not affect detection of a LiDARTag; hence, the proposed fiducial marker can operate in a completely dark environment. In addition, the LiDARTag nicely complements available visual fiducial markers as the tag design is compatible with available techniques, such as AprilTags, allowing for efficient multi-sensor fusion and calibration tasks. The experimental results, verified by a motion capture system, confirm the proposed technique can reliably provide a tag's pose and its unique ID code. All implementations are done in C++ and will be available soon at: https://github.com/brucejk/LiDARTag

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10349](http://arxiv.org/abs/1908.10349)

##### PDF
[http://arxiv.org/pdf/1908.10349](http://arxiv.org/pdf/1908.10349)


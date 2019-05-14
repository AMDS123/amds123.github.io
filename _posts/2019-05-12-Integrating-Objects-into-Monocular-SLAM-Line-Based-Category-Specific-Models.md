---
layout: post
title: "Integrating Objects into Monocular SLAM: Line Based Category Specific Models"
date: 2019-05-12 11:27:06
categories: arXiv_RO
tags: arXiv_RO SLAM
author: Nayan Joshi, Yogesh Sharma, Parv Parkhiya, Rishabh Khawad, K Madhava Krishna, Brojeshwar Bhowmick
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel Line based parameterization for category specific CAD models. The proposed parameterization associates 3D category-specific CAD model and object under consideration using a dictionary based RANSAC method that uses object Viewpoints as prior and edges detected in the respective intensity image of the scene. The association problem is posed as a classical Geometry problem rather than being dataset driven, thus saving the time and labour that one invests in annotating dataset to train Keypoint Network for different category objects. Besides eliminating the need of dataset preparation, the approach also speeds up the entire process as this method processes the image only once for all objects, thus eliminating the need of invoking the network for every object in an image across all images. A 3D-2D edge association module followed by a resection algorithm for lines is used to recover object poses. The formulation optimizes for shape and pose of the object, thus aiding in recovering object 3D structure more accurately. Finally, a Factor Graph formulation is used to combine object poses with camera odometry to formulate a SLAM problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04698](http://arxiv.org/abs/1905.04698)

##### PDF
[http://arxiv.org/pdf/1905.04698](http://arxiv.org/pdf/1905.04698)


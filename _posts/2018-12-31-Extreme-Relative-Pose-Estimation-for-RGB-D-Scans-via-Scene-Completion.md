---
layout: post
title: "Extreme Relative Pose Estimation for RGB-D Scans via Scene Completion"
date: 2018-12-31 23:43:16
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Zhenpei Yang, Jeffrey Z.Pan, Linjie Luo, Xiaowei Zhou, Kristen Grauman, Qixing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the relative rigid pose between two RGB-D scans of the same underlying environment is a fundamental problem in computer vision, robotics, and computer graphics. Most existing approaches allow only limited maximum relative pose changes since they require considerable overlap between the input scans. We introduce a novel deep neural network that extends the scope to extreme relative poses, with little or even no overlap between the input scans. The key idea is to infer more complete scene information about the underlying environment and match on the completed scans. In particular, instead of only performing scene completion from each individual scan, our approach alternates between relative pose estimation and scene completion. This allows us to perform scene completion by utilizing information from both input scans at late iterations, resulting in better results for both scene completion and relative pose estimation. Experimental results on benchmark datasets show that our approach leads to considerable improvements over state-of-the-art approaches for relative pose estimation. In particular, our approach provides encouraging relative pose estimates even between non-overlapping scans.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.00063](https://arxiv.org/abs/1901.00063)

##### PDF
[https://arxiv.org/pdf/1901.00063](https://arxiv.org/pdf/1901.00063)


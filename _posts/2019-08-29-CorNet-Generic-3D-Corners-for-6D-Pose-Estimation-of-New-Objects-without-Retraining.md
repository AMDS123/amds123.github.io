---
layout: post
title: "CorNet: Generic 3D Corners for 6D Pose Estimation of New Objects without Retraining"
date: 2019-08-29 21:17:09
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Detection
author: Giorgia Pitteri, Slobodan Ilic, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach to the detection and 3D pose estimation of objects in color images. Its main contribution is that it does not require any training phases nor data for new objects, while state-of-the-art methods typically require hours of training time and hundreds of training registered images. Instead, our method relies only on the objects' geometries. Our method focuses on objects with prominent corners, which covers a large number of industrial objects. We first learn to detect object corners of various shapes in images and also to predict their 3D poses, by using training images of a small set of objects. To detect a new object in a given image, we first identify its corners from its CAD model; we also detect the corners visible in the image and predict their 3D poses. We then introduce a RANSAC-like algorithm that robustly and efficiently detects and estimates the object's 3D pose by matching its corners on the CAD model with their detected counterparts in the image. Because we also estimate the 3D poses of the corners in the image, detecting only 1 or 2 corners is sufficient to estimate the pose of the object, which makes the approach robust to occlusions. We finally rely on a final check that exploits the full 3D geometry of the objects, in case multiple objects have the same corner spatial arrangement. The advantages of our approach make it particularly attractive for industrial contexts, and we demonstrate our approach on the challenging T-LESS dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11457](http://arxiv.org/abs/1908.11457)

##### PDF
[http://arxiv.org/pdf/1908.11457](http://arxiv.org/pdf/1908.11457)


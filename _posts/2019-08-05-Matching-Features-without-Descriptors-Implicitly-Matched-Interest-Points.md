---
layout: post
title: "Matching Features without Descriptors: Implicitly Matched Interest Points"
date: 2019-08-05 13:17:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Detection
author: Titus Cieslewski, Michael Bloesch, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
The extraction and matching of interest points is a prerequisite for many geometric computer vision problems. Traditionally, matching has been achieved by assigning descriptors to interest points and matching points that have similar descriptors. In this paper, we propose a method by which interest points are instead already implicitly matched at detection time. With this, descriptors do not need to be calculated, stored, communicated, or matched any more. This is achieved by a convolutional neural network with multiple output channels and can be thought of as a collection of a variety of detectors, each specialized to specific visual features. This paper describes how to design and train such a network in a way that results in successful relative pose estimation performance despite the limitation on interest point count. While the overall matching score is slightly lower than with traditional methods, the approach is descriptor free and thus enables localization systems with a significantly smaller memory footprint and multi-agent localization systems with lower bandwidth requirements. The network also outputs the confidence for a specific interest point resulting in a valid match. We evaluate performance relative to state-of-the-art alternatives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10681](http://arxiv.org/abs/1811.10681)

##### PDF
[http://arxiv.org/pdf/1811.10681](http://arxiv.org/pdf/1811.10681)


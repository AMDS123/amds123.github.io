---
layout: post
title: "High-speed Video from Asynchronous Camera Array"
date: 2019-01-17 23:26:55
categories: arXiv_CV
tags: arXiv_CV
author: Si Lu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for capturing high-speed video using an asynchronous camera array. Our method sequentially fires each sensor in a camera array with a small time offset and assembles captured frames into a high-speed video according to the time stamps. The resulting video, however, suffers from parallax jittering caused by the viewpoint difference among sensors in the camera array. To address this problem, we develop a dedicated novel view synthesis algorithm that transforms the video frames as if they were captured by a single reference sensor. Specifically, for any frame from a non-reference sensor, we find the two temporally neighboring frames captured by the reference sensor. Using these three frames, we render a new frame with the same time stamp as the non-reference frame but from the viewpoint of the reference sensor. Specifically, we segment these frames into super-pixels and then apply local content-preserving warping to warp them to form the new frame. We employ a multi-label Markov Random Field method to blend these warped frames. Our experiments show that our method can produce high-quality and high-speed video of a wide variety of scenes with large parallax, scene dynamics, and camera motion and outperforms several baseline and state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06034](http://arxiv.org/abs/1901.06034)

##### PDF
[http://arxiv.org/pdf/1901.06034](http://arxiv.org/pdf/1901.06034)


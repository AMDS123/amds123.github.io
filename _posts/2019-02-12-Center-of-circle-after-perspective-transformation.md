---
layout: post
title: "Center of circle after perspective transformation"
date: 2019-02-12 18:38:04
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Xi Wang, Albert Chern, Marc Alexa
mathjax: true
---

* content
{:toc}

##### Abstract
Video-based glint-free eye tracking commonly estimates gaze direction based on the pupil center. The boundary of the pupil is fitted with an ellipse and the euclidean center of the ellipse in the image is taken as the center of the pupil. However, the center of the pupil is generally not mapped to the center of the ellipse by the projective camera transformation. This error resulting from using a point that is not the true center of the pupil directly affects eye tracking accuracy. We investigate the underlying geometric problem of determining the center of a circular object based on its projective image. The main idea is to exploit two concentric circles -- in the application scenario these are the pupil and the iris. We show that it is possible to computed the center and the ratio of the radii from the mapped concentric circles with a direct method that is fast and robust in practice. We evaluate our method on synthetically generated data and find that it improves systematically over using the center of the fitted ellipse. Apart from applications of eye tracking we estimate that our approach will be useful in other tracking applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04541](http://arxiv.org/abs/1902.04541)

##### PDF
[http://arxiv.org/pdf/1902.04541](http://arxiv.org/pdf/1902.04541)


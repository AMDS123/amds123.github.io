---
layout: post
title: "MAGSAC: marginalizing sample consensus"
date: 2019-06-04 23:06:14
categories: arXiv_CV
tags: arXiv_CV
author: Daniel Barath, Jana Noskova, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
A method called, sigma-consensus, is proposed to eliminate the need for a user-defined inlier-outlier threshold in RANSAC. Instead of estimating the noise sigma, it is marginalized over a range of noise scales. The optimized model is obtained by weighted least-squares fitting where the weights come from the marginalization over sigma of the point likelihoods of being inliers. A new quality function is proposed not requiring sigma and, thus, a set of inliers to determine the model quality. Also, a new termination criterion for RANSAC is built on the proposed marginalization approach. Applying sigma-consensus, MAGSAC is proposed with no need for a user-defined sigma and improving the accuracy of robust estimation significantly. It is superior to the state-of-the-art in terms of geometric accuracy on publicly available real-world datasets for epipolar geometry (F and E) and homography estimation. In addition, applying sigma-consensus only once as a post-processing step to the RANSAC output always improved the model quality on a wide range of vision problems without noticeable deterioration in processing time, adding a few milliseconds. The source code is at https://github.com/danini/magsac.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.07469](http://arxiv.org/abs/1803.07469)

##### PDF
[http://arxiv.org/pdf/1803.07469](http://arxiv.org/pdf/1803.07469)


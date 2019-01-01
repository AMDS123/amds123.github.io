---
layout: post
title: "Unsupervised monocular stereo matching"
date: 2018-12-31 02:13:55
categories: arXiv_CV
tags: arXiv_CV GAN Deep_Learning
author: Zhimin Zhang, Jianzhong Qiao, Shukuan Lin
mathjax: true
---

* content
{:toc}

##### Abstract
At present, deep learning has been applied more and more in monocular image depth estimation and has shown promising results. The current more ideal method for monocular depth estimation is the supervised learning based on ground truth depth, but this method requires an abundance of expensive ground truth depth as the supervised labels. Therefore, researchers began to work on unsupervised depth estimation methods. Although the accuracy of unsupervised depth estimation method is still lower than that of supervised method, it is a promising research direction. 
 In this paper, Based on the experimental results that the stereo matching models outperforms monocular depth estimation models under the same unsupervised depth estimation model, we proposed an unsupervised monocular vision stereo matching method. In order to achieve the monocular stereo matching, we constructed two unsupervised deep convolution network models, one was to reconstruct the right view from the left view, and the other was to estimate the depth map using the reconstructed right view and the original left view. The two network models are piped together during the test phase. The output results of this method outperforms the current mainstream unsupervised depth estimation method in the challenging KITTI dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11671](http://arxiv.org/abs/1812.11671)

##### PDF
[http://arxiv.org/pdf/1812.11671](http://arxiv.org/pdf/1812.11671)


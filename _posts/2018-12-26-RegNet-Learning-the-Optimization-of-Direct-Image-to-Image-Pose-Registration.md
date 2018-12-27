---
layout: post
title: "RegNet: Learning the Optimization of Direct Image-to-Image Pose Registration"
date: 2018-12-26 03:47:31
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning
author: Lei Han, Mengqi Ji, Lu Fang, Matthias Nie&#xdf;ner
mathjax: true
---

* content
{:toc}

##### Abstract
Direct image-to-image alignment that relies on the optimization of photometric error metrics suffers from limited convergence range and sensitivity to lighting conditions. Deep learning approaches has been applied to address this problem by learning better feature representations using convolutional neural networks, yet still require a good initialization. In this paper, we demonstrate that the inaccurate numerical Jacobian limits the convergence range which could be improved greatly using learned approaches. Based on this observation, we propose a novel end-to-end network, RegNet, to learn the optimization of image-to-image pose registration. By jointly learning feature representation for each pixel and partial derivatives that replace handcrafted ones (e.g., numerical differentiation) in the optimization step, the neural network facilitates end-to-end optimization. The energy landscape is constrained on both the feature representation and the learned Jacobian, hence providing more flexibility for the optimization as a consequence leads to more robust and faster convergence. In a series of experiments, including a broad ablation study, we demonstrate that RegNet is able to converge for large-baseline image pairs with fewer iterations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10212](http://arxiv.org/abs/1812.10212)

##### PDF
[http://arxiv.org/pdf/1812.10212](http://arxiv.org/pdf/1812.10212)


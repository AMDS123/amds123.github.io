---
layout: post
title: "Anytime Stereo Image Depth Estimation on Mobile Devices"
date: 2018-10-26 16:22:27
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Yan Wang, Zihang Lai, Gao Huang, Brian H. Wang, Laurens van der Maaten, Mark Campbell, Kilian Q. Weinberger
mathjax: true
---

* content
{:toc}

##### Abstract
Many real-world applications of stereo depth estimation in robotics require the generation of accurate disparity maps in real time under significant computational constraints. Current state-of-the-art algorithms can either generate accurate but slow mappings, or fast but inaccurate ones, and typically require far too many parameters for power- or memory-constrained devices. Motivated by this shortcoming, we propose a novel approach for disparity prediction in the anytime setting. In contrast to prior work, our end-to-end learned approach can trade off computation and accuracy at inference time. The depth estimation is performed in stages, during which the model can be queried at any time to output its current best estimate. Our final model can process 1242$ \times $375 resolution images within a range of 10-35 FPS on an NVIDIA Jetson TX2 module with only marginal increases in error -- using two orders of magnitude fewer parameters than the most competitive baseline. Our code is available as open source on https://github.com/mileyan/AnyNet .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11408](http://arxiv.org/abs/1810.11408)

##### PDF
[http://arxiv.org/pdf/1810.11408](http://arxiv.org/pdf/1810.11408)


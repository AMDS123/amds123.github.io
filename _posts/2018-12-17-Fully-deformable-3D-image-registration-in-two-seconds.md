---
layout: post
title: "Fully-deformable 3D image registration in two seconds"
date: 2018-12-17 13:52:09
categories: arXiv_CV
tags: arXiv_CV
author: Daniel Budelmann, Lars K&#xf6;nig, Nils Papenberg, Jan Lellmann
mathjax: true
---

* content
{:toc}

##### Abstract
We present a highly parallel method for accurate and efficient variational deformable 3D image registration on a consumer-grade graphics processing unit (GPU). We build on recent matrix-free variational approaches and specialize the concepts to the massively-parallel manycore architecture provided by the GPU. Compared to a parallel and optimized CPU implementation, this allows us to achieve an average speedup of 32.53 on 986 real-world CT thorax-abdomen follow-up scans. At a resolution of approximately $256^3$ voxels, the average runtime is 1.99 seconds for the full registration. On the publicly available DIR-lab benchmark, our method ranks third with respect to average landmark error at an average runtime of 0.32 seconds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06765](http://arxiv.org/abs/1812.06765)

##### PDF
[http://arxiv.org/pdf/1812.06765](http://arxiv.org/pdf/1812.06765)


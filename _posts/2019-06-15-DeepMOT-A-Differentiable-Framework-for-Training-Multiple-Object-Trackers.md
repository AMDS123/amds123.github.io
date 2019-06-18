---
layout: post
title: "DeepMOT: A Differentiable Framework for Training Multiple Object Trackers"
date: 2019-06-15 21:34:30
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking
author: Yihong Xu, Yutong Ban, Xavier Alameda-Pineda, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple Object Tracking accuracy and precision (MOTA and MOTP) are two standard and widely-used metrics to assess the quality of multiple object trackers. They are specifically designed to encode the challenges and difficulties of tracking multiple objects. To directly optimize a tracker based on MOTA and MOTP is difficult, since both the metrics are strongly rely on the Hungarian algorithm, which are non-differentiable. We propose a differentiable proxy for the MOTA and MOTP, thus allowing to train a deep multiple-object tracker by directly optimizing (a proxy of) the standard MOT metrics. The proposed approximation is based on a bidirectional recurrent network that inputs the object-to-hypothesis distance matrix and outputs the optimal hypothesis-to-object association, thus emulating the Hungarian algorithm. Followed by a differentiable module, the estimated association is used to compute the MOTA and MOTP. The experimental study demonstrates the benefits of this differentiable framework on two recent deep trackers over the MOT17 dataset. Moreover, the code is publicly available from https://gitlab.inria.fr/yixu/deepmot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06618](http://arxiv.org/abs/1906.06618)

##### PDF
[http://arxiv.org/pdf/1906.06618](http://arxiv.org/pdf/1906.06618)


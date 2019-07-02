---
layout: post
title: "DuDoNet: Dual Domain Network for CT Metal Artifact Reduction"
date: 2019-06-29 20:23:01
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Wei-An Lin, Haofu Liao, Cheng Peng, Xiaohang Sun, Jingdan Zhang, Jiebo Luo, Rama Chellappa, Shaohua Kevin Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Computed tomography (CT) is an imaging modality widely used for medical diagnosis and treatment. CT images are often corrupted by undesirable artifacts when metallic implants are carried by patients, which creates the problem of metal artifact reduction (MAR). Existing methods for reducing the artifacts due to metallic implants are inadequate for two main reasons. First, metal artifacts are structured and non-local so that simple image domain enhancement approaches would not suffice. Second, the MAR approaches which attempt to reduce metal artifacts in the X-ray projection (sinogram) domain inevitably lead to severe secondary artifact due to sinogram inconsistency. To overcome these difficulties, we propose an end-to-end trainable Dual Domain Network (DuDoNet) to simultaneously restore sinogram consistency and enhance CT images. The linkage between the sigogram and image domains is a novel Radon inversion layer that allows the gradients to back-propagate from the image domain to the sinogram domain during training. Extensive experiments show that our method achieves significant improvements over other single domain MAR approaches. To the best of our knowledge, it is the first end-to-end dual-domain network for MAR.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00273](http://arxiv.org/abs/1907.00273)

##### PDF
[http://arxiv.org/pdf/1907.00273](http://arxiv.org/pdf/1907.00273)


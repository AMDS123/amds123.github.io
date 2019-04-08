---
layout: post
title: "DeceptionNet: Network-Driven Domain Randomization"
date: 2019-04-04 19:01:42
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Pose_Estimation Optimization Classification Recognition
author: Sergey Zakharov, Wadim Kehl, Slobodan Ilic
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach to tackle domain adaptation between synthetic and real data. Instead of employing 'blind' domain randomization, i.e. augmenting synthetic renderings with random backgrounds or changing illumination and colorization, we leverage the task network as its own adversarial guide towards useful augmentations that maximize the uncertainty of the output. To this end, we design a min-max optimization scheme where a given task competes against a special deception network, with the goal of minimizing the task error subject to specific constraints enforced by the deceiver. The deception network samples from a family of differentiable pixel-level perturbations and exploits the task architecture to find the most destructive augmentations. Unlike GAN-based approaches that require unlabeled data from the target domain, our method achieves robust mappings that scale well to multiple target distributions from source data alone. We apply our framework to the tasks of digit recognition on enhanced MNIST variants as well as classification and object pose estimation on the Cropped LineMOD dataset and compare to a number of domain adaptation approaches, demonstrating similar results with superior generalization capabilities.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02750](https://arxiv.org/abs/1904.02750)

##### PDF
[https://arxiv.org/pdf/1904.02750](https://arxiv.org/pdf/1904.02750)


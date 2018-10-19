---
layout: post
title: "Unsupervised Domain Adaptation for Learning Eye Gaze from a Million Synthetic Images: An Adversarial Approach"
date: 2018-10-18 07:15:06
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Avisek Lahiri, Abhinav Agarwalla, Prabir Kumar Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
With contemporary advancements of graphics engines, recent trend in deep learning community is to train models on automatically annotated simulated examples and apply on real data during test time. This alleviates the burden of manual annotation. However, there is an inherent difference of distributions between images coming from graphics engine and real world. Such domain difference deteriorates test time performances of models trained on synthetic examples. In this paper we address this issue with unsupervised adversarial feature adaptation across synthetic and real domain for the special use case of eye gaze estimation which is an essential component for various downstream HCI tasks. We initially learn a gaze estimator on annotated synthetic samples rendered from a 3D game engine and then adapt the features of unannotated real samples via a zero-sum minmax adversarial game against a domain discriminator following the recent paradigm of generative adversarial networks. Such adversarial adaptation forces features of both domains to be indistinguishable which enables us to use regression models trained on synthetic domain to be used on real samples. On the challenging MPIIGaze real life dataset, we outperform recent fully supervised methods trained on manually annotated real samples by appreciable margins and also achieve 13\% more relative gain after adaptation compared to the current benchmark method of SimGAN

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.07926](https://arxiv.org/abs/1810.07926)

##### PDF
[https://arxiv.org/pdf/1810.07926](https://arxiv.org/pdf/1810.07926)


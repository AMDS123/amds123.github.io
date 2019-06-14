---
layout: post
title: "Deep Variational Networks with Exponential Weighting for Learning Computed Tomography"
date: 2019-06-13 07:54:51
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Inference Quantitative
author: Valery Vishnevskiy, Richard Rau, Orcun Goksel
mathjax: true
---

* content
{:toc}

##### Abstract
Tomographic image reconstruction is relevant for many medical imaging modalities including X-ray, ultrasound (US) computed tomography (CT) and photoacoustics, for which the access to full angular range tomographic projections might be not available in clinical practice due to physical or time constraints. Reconstruction from incomplete data in low signal-to-noise ratio regime is a challenging and ill-posed inverse problem that usually leads to unsatisfactory image quality. While informative image priors may be learned using generic deep neural network architectures, the artefacts caused by an ill-conditioned design matrix often have global spatial support and cannot be efficiently filtered out by means of convolutions. In this paper we propose to learn an inverse mapping in an end-to-end fashion via unrolling optimization iterations of a prototypical reconstruction algorithm. We herein introduce a network architecture that performs filtering jointly in both sinogram and spatial domains. To efficiently train such deep network we propose a novel regularization approach based on deep exponential weighting. Experiments on US and X-ray CT data show that our proposed method is qualitatively and quantitatively superior to conventional non-linear reconstruction methods as well as state-of-the-art deep networks for image reconstruction. Fast inference time of the proposed algorithm allows for sophisticated reconstructions in real-time critical settings, demonstrated with US SoS imaging of an ex vivo bovine phantom.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05528](https://arxiv.org/abs/1906.05528)

##### PDF
[https://arxiv.org/pdf/1906.05528](https://arxiv.org/pdf/1906.05528)


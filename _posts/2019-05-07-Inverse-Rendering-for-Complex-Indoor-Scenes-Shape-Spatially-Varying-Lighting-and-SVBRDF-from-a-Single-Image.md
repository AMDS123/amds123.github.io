---
layout: post
title: "Inverse Rendering for Complex Indoor Scenes: Shape, Spatially-Varying Lighting and SVBRDF from a Single Image"
date: 2019-05-07 17:47:40
categories: arXiv_CV
tags: arXiv_CV Face Prediction
author: Zhengqin Li, Mohammad Shafiei, Ravi Ramamoorthi, Kalyan Sunkavalli, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep inverse rendering framework for indoor scenes. From a single RGB image of an arbitrary indoor scene, we create a complete scene reconstruction, estimating shape, spatially-varying lighting, and spatially-varying, non-Lambertian surface reflectance. To train this network, we augment the SUNCG indoor scene dataset with real-world materials and render them with a fast, high-quality, physically-based GPU renderer to create a large-scale, photorealistic indoor dataset. Our inverse rendering network incorporates physical insights -- including a spatially-varying spherical Gaussian lighting representation, a differentiable rendering layer to model scene appearance, a cascade structure to iteratively refine the predictions and a bilateral solver for refinement -- allowing us to jointly reason about shape, lighting, and reflectance. Experiments show that our framework outperforms previous methods for estimating individual scene components, which also enables various novel applications for augmented reality, such as photorealistic object insertion and material editing. Code and data will be made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02722](http://arxiv.org/abs/1905.02722)

##### PDF
[http://arxiv.org/pdf/1905.02722](http://arxiv.org/pdf/1905.02722)


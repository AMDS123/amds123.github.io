---
layout: post
title: "Learned reconstructions for practical mask-based lensless imaging"
date: 2019-08-30 01:45:05
categories: arXiv_CV
tags: arXiv_CV Review Knowledge Optimization Deep_Learning
author: Kristina Monakhova, Joshua Yurtsever, Grace Kuo, Nick Antipa, Kyrollos Yanny, Laura Waller
mathjax: true
---

* content
{:toc}

##### Abstract
Mask-based lensless imagers are smaller and lighter than traditional lensed cameras. In these imagers, the sensor does not directly record an image of the scene; rather, a computational algorithm reconstructs it. Typically, mask-based lensless imagers use a model-based reconstruction approach that suffers from long compute times and a heavy reliance on both system calibration and heuristically chosen denoisers. In this work, we address these limitations using a bounded-compute, trainable neural network to reconstruct the image. We leverage our knowledge of the physical system by unrolling a traditional model-based optimization algorithm, whose parameters we optimize using experimentally gathered ground-truth data. Optionally, images produced by the unrolled network are then fed into a jointly-trained denoiser. As compared to traditional methods, our architecture achieves better perceptual image quality and runs 20x faster, enabling interactive previewing of the scene. We explore a spectrum between model-based and deep learning methods, showing the benefits of using an intermediate approach. Finally, we test our network on images taken in the wild with a prototype mask-based camera, demonstrating that our network generalizes to natural images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11502](http://arxiv.org/abs/1908.11502)

##### PDF
[http://arxiv.org/pdf/1908.11502](http://arxiv.org/pdf/1908.11502)


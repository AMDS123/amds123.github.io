---
layout: post
title: "Coordinate-based Texture Inpainting for Pose-Guided Image Generation"
date: 2018-11-28 09:33:00
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning
author: Artur Grigorev, Artem Sevastopolsky, Alexander Vakhitov, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new deep learning approach to pose-guided resynthesis of human photographs. At the heart of the new approach is the estimation of the complete body surface texture based on a single photograph. Since the input photograph always observes only a part of the surface, we suggest a new inpainting method that completes the texture of the human body. Rather than working directly with colors of texture elements, the inpainting network estimates an appropriate source location in the input image for each element of the body surface. This correspondence field between the input image and the texture is then further warped into the target image coordinate frame based on the desired pose, effectively establishing the correspondence between the source and the target view even when the pose change is drastic. The final convolutional network then uses the established correspondence and all other available information to synthesize the output image using a fully-convolutional architecture with deformable convolutions. We show the state-of-the-art result for pose-guided image synthesis. Additionally, we demonstrate the performance of our system for garment transfer and pose-guided face resynthesis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11459](http://arxiv.org/abs/1811.11459)

##### PDF
[http://arxiv.org/pdf/1811.11459](http://arxiv.org/pdf/1811.11459)


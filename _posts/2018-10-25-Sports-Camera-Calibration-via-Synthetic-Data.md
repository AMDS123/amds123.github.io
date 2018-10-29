---
layout: post
title: "Sports Camera Calibration via Synthetic Data"
date: 2018-10-25 00:10:57
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Jianhui Chen, James J. Little
mathjax: true
---

* content
{:toc}

##### Abstract
Calibrating sports cameras is important for autonomous broadcasting and sports analysis. Here we propose a highly automatic method for calibrating sports cameras from a single image using synthetic data. First, we develop a novel camera pose engine. The camera pose engine has only three significant free parameters so that it can effectively generate a lot of camera poses and corresponding edge (i.e, field marking) images. Then, we learn compact deep features via a siamese network from paired edge image and camera pose and build a feature-pose database. After that, we use a novel two-GAN (generative adversarial network) model to detect field markings in real images. Finally, we query an initial camera pose from the feature-pose database and refine camera poses using truncated distance images. We evaluate our method on both synthetic and real data. Our method not only demonstrates the robustness on the synthetic data but also achieves the state-of-the-art accuracy on a standard soccer dataset and very high performance on a volleyball dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10658](https://arxiv.org/abs/1810.10658)

##### PDF
[https://arxiv.org/pdf/1810.10658](https://arxiv.org/pdf/1810.10658)


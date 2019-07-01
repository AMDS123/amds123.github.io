---
layout: post
title: "PointCleanNet: Learning to Denoise and Remove Outliers from Dense Point Clouds"
date: 2019-06-28 15:22:52
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Marie-Julie Rakotosaona, Vittorio La Barbera, Paul Guerrero, Niloy J. Mitra, Maks Ovsjanikov
mathjax: true
---

* content
{:toc}

##### Abstract
Point clouds obtained with 3D scanners or by image-based reconstruction techniques are often corrupted with significant amount of noise and outliers. Traditional methods for point cloud denoising largely rely on local surface fitting (e.g., jets or MLS surfaces), local or non-local averaging, or on statistical assumptions about the underlying noise model. In contrast, we develop a simple data-driven method for removing outliers and reducing noise in unordered point clouds. We base our approach on a deep learning architecture adapted from PCPNet, which was recently proposed for estimating local 3D shape properties in point clouds. Our method first classifies and discards outlier samples, and then estimates correction vectors that project noisy points onto the original clean surfaces. The approach is efficient and robust to varying amounts of noise and outliers, while being able to handle large densely-sampled point clouds. In our extensive evaluation, both on synthesic and real data, we show an increased robustness to strong noise levels compared to various state-of-the-art methods, enabling accurate surface reconstruction from extremely noisy real data obtained by range scans. Finally, the simplicity and universality of our approach makes it very easy to integrate in any existing geometry processing pipeline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01060](http://arxiv.org/abs/1901.01060)

##### PDF
[http://arxiv.org/pdf/1901.01060](http://arxiv.org/pdf/1901.01060)


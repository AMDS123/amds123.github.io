---
layout: post
title: "Inverse Path Tracing for Joint Material and Lighting Estimation"
date: 2019-03-17 19:06:31
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Dejan Azinovi&#x107;, Tzu-Mao Li, Anton Kaplanyan, Matthias Nie&#xdf;ner
mathjax: true
---

* content
{:toc}

##### Abstract
Modern computer vision algorithms have brought significant advancement to 3D geometry reconstruction. However, illumination and material reconstruction remain less studied, with current approaches assuming very simplified models for materials and illumination. We introduce Inverse Path Tracing, a novel approach to jointly estimate the material properties of objects and light sources in indoor scenes by using an invertible light transport simulation. We assume a coarse geometry scan, along with corresponding images and camera poses. The key contribution of this work is an accurate and simultaneous retrieval of light sources and physically based material properties (e.g., diffuse reflectance, specular reflectance, roughness, etc.) for the purpose of editing and re-rendering the scene under new conditions. To this end, we introduce a novel optimization method using a differentiable Monte Carlo renderer that computes derivatives with respect to the estimated unknown illumination and material properties. This enables joint optimization for physically correct light transport and material models using a tailored stochastic gradient descent.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07145](http://arxiv.org/abs/1903.07145)

##### PDF
[http://arxiv.org/pdf/1903.07145](http://arxiv.org/pdf/1903.07145)


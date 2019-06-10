---
layout: post
title: "How to make a pizza: Learning a compositional layer-based GAN model"
date: 2019-06-06 23:22:31
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Dim P. Papadopoulos, Youssef Tamaazousti, Ferda Ofli, Ingmar Weber, Antonio Torralba
mathjax: true
---

* content
{:toc}

##### Abstract
A food recipe is an ordered set of instructions for preparing a particular dish. From a visual perspective, every instruction step can be seen as a way to change the visual appearance of the dish by adding extra objects (e.g., adding an ingredient) or changing the appearance of the existing ones (e.g., cooking the dish). In this paper, we aim to teach a machine how to make a pizza by building a generative model that mirrors this step-by-step procedure. To do so, we learn composable module operations which are able to either add or remove a particular ingredient. Each operator is designed as a Generative Adversarial Network (GAN). Given only weak image-level supervision, the operators are trained to generate a visual layer that needs to be added to or removed from the existing image. The proposed model is able to decompose an image into an ordered sequence of layers by applying sequentially in the right order the corresponding removing modules. Experimental results on synthetic and real pizza images demonstrate that our proposed model is able to: (1) segment pizza toppings in a weaklysupervised fashion, (2) remove them by revealing what is occluded underneath them (i.e., inpainting), and (3) infer the ordering of the toppings without any depth ordering supervision. Code, data, and models are available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02839](http://arxiv.org/abs/1906.02839)

##### PDF
[http://arxiv.org/pdf/1906.02839](http://arxiv.org/pdf/1906.02839)


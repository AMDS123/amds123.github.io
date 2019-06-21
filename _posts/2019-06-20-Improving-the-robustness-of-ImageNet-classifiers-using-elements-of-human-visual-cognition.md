---
layout: post
title: "Improving the robustness of ImageNet classifiers using elements of human visual cognition"
date: 2019-06-20 02:28:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Recognition
author: A. Emin Orhan, Brenden M. Lake
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the robustness properties of image recognition models equipped with two features inspired by human vision, an explicit episodic memory and a shape bias, at the ImageNet scale. As reported in previous work, we show that an explicit episodic memory improves the robustness of image recognition models against small-norm adversarial perturbations under some threat models. It does not, however, improve the robustness against more natural, and typically larger, perturbations. Learning more robust features during training appears to be necessary for robustness in this second sense. We show that features derived from a model that was encouraged to learn global, shape-based representations (Geirhos et al., 2019) do not only improve the robustness against natural perturbations, but when used in conjunction with an episodic memory, they also provide additional robustness against adversarial perturbations. Finally, we address three important design choices for the episodic memory: memory size, dimensionality of the memories and the retrieval method. We show that to make the episodic memory more compact, it is preferable to reduce the number of memories by clustering them, instead of reducing their dimensionality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08416](http://arxiv.org/abs/1906.08416)

##### PDF
[http://arxiv.org/pdf/1906.08416](http://arxiv.org/pdf/1906.08416)


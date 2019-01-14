---
layout: post
title: "Image Disentanglement and Uncooperative Re-Entanglement for High-Fidelity Image-to-Image Translation"
date: 2019-01-11 16:08:21
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Optimization
author: Adam W. Harley, Shih-En Wei, Jason Saragih, Katerina Fragkiadaki
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-domain image-to-image translation should satisfy two requirements: (1) preserve the information that is common to both domains, and (2) generate convincing images covering variations that appear in the target domain. This is challenging, especially when there are no example translations available as supervision. Adversarial cycle consistency was recently proposed as a solution, with beautiful and creative results, yielding much follow-up work. However, augmented reality applications cannot readily use such techniques to provide users with compelling translations of real scenes, because the translations do not have high-fidelity constraints. In other words, current models are liable to change details that should be preserved: while re-texturing a face, they may alter the face's expression in an unpredictable way. In this paper, we introduce the problem of high-fidelity image-to-image translation, and present a method for solving it. Our main insight is that low-fidelity translations typically escape a cycle-consistency penalty, because the back-translator learns to compensate for the forward-translator's errors. We therefore introduce an optimization technique that prevents the networks from cooperating: simply train each network only when its input data is real. Prior works, in comparison, train each network with a mix of real and generated data. Experimental results show that our method accurately disentangles the factors that separate the domains, and converges to semantics-preserving translations that prior methods miss.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03628](http://arxiv.org/abs/1901.03628)

##### PDF
[http://arxiv.org/pdf/1901.03628](http://arxiv.org/pdf/1901.03628)


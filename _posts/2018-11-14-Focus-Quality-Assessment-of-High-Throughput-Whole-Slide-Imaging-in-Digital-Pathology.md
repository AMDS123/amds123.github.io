---
layout: post
title: "Focus Quality Assessment of High-Throughput Whole Slide Imaging in Digital Pathology"
date: 2018-11-14 20:07:26
categories: arXiv_CV
tags: arXiv_CV
author: Mahdi S. Hosseini, Yueyang Zhang, Lyndon Chan, Konstantinos N. Plataniotis, Jasper A.Z. Brawley-Hayes, Savvas Damaskinos
mathjax: true
---

* content
{:toc}

##### Abstract
One of the challenges facing the adoption of digital pathology workflows for clinical use is the need for automated quality control. As the scanners sometimes determine focus inaccurately, the resultant image blur deteriorates the scanned slide to the point of being unusable. Also, the scanned slide images tend to be extremely large when scanned at greater or equal 20X image resolution. Hence, for digital pathology to be clinically useful, it is necessary to use computational tools to quickly and accurately quantify the image focus quality and determine whether an image needs to be re-scanned. We propose a no-reference focus quality assessment metric specifically for digital pathology images, that operates by using a sum of even-derivative filter bases to synthesize a human visual system-like kernel, which is modeled as the inverse of the lens' point spread function. This kernel is then applied to a digital pathology image to modify high-frequency image information deteriorated by the scanner's optics and quantify the focus quality at the patch level. We show in several experiments that our method correlates better with ground-truth $z$-level data than other methods, and is more computationally efficient. We also extend our method to generate a local slide-level focus quality heatmap, which can be used for automated slide quality control, and demonstrate the utility of our method for clinical scan quality control by comparison with subjective slide quality scores.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06038](http://arxiv.org/abs/1811.06038)

##### PDF
[http://arxiv.org/pdf/1811.06038](http://arxiv.org/pdf/1811.06038)


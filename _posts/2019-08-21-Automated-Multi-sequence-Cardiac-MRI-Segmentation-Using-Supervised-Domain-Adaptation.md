---
layout: post
title: "Automated Multi-sequence Cardiac MRI Segmentation Using Supervised Domain Adaptation"
date: 2019-08-21 07:16:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning
author: Sulaiman Vesal, Nishant Ravikumar, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Left ventricle segmentation and morphological assessment are essential for improving diagnosis and our understanding of cardiomyopathy, which in turn is imperative for reducing risk of myocardial infarctions in patients. Convolutional neural network (CNN) based methods for cardiac magnetic resonance (CMR) image segmentation rely on supervision with pixel-level annotations, and may not generalize well to images from a different domain. These methods are typically sensitive to variations in imaging protocols and data acquisition. Since annotating multi-sequence CMR images is tedious and subject to inter- and intra-observer variations, developing methods that can automatically adapt from one domain to the target domain is of great interest. In this paper, we propose an approach for domain adaptation in multi-sequence CMR segmentation task using transfer learning that combines multi-source image information. We first train an encoder-decoder CNN on T2-weighted and balanced-Steady State Free Precession (bSSFP) MR images with pixel-level annotation and fine-tune the same network with a limited number of Late Gadolinium Enhanced-MR (LGE-MR) subjects, to adapt the domain features. The domain-adapted network was trained with just four LGE-MR training samples and obtained an average Dice score of $\sim$85.0\% on the test set comprises of 40 LGE-MR subjects. The proposed method significantly outperformed a network without adaptation trained from scratch on the same set of LGE-MR training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07726](http://arxiv.org/abs/1908.07726)

##### PDF
[http://arxiv.org/pdf/1908.07726](http://arxiv.org/pdf/1908.07726)


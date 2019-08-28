---
layout: post
title: "A Weakly Supervised Method for Instance Segmentation of Biological Cells"
date: 2019-08-26 19:42:14
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Weakly_Supervised Deep_Learning Detection
author: Fidel A. Guerrero-Pe&#xf1;a, Pedro D. Marrero Fernandez, Tsang Ing Ren, Alexandre Cunha
mathjax: true
---

* content
{:toc}

##### Abstract
We present a weakly supervised deep learning method to perform instance segmentation of cells present in microscopy images. Annotation of biomedical images in the lab can be scarce, incomplete, and inaccurate. This is of concern when supervised learning is used for image analysis as the discriminative power of a learning model might be compromised in these situations. To overcome the curse of poor labeling, our method focuses on three aspects to improve learning: i) we propose a loss function operating in three classes to facilitate separating adjacent cells and to drive the optimizer to properly classify underrepresented regions; ii) a contour-aware weight map model is introduced to strengthen contour detection while improving the network generalization capacity; and iii) we augment data by carefully modulating local intensities on edges shared by adjoining regions and to account for possibly weak signals on these edges. Generated probability maps are segmented using different methods, with the watershed based one generally offering the best solutions, specially in those regions where the prevalence of a single class is not clear. The combination of these contributions allows segmenting individual cells on challenging images. We demonstrate our methods in sparse and crowded cell images, showing improvements in the learning process for a fixed network architecture.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09891](http://arxiv.org/abs/1908.09891)

##### PDF
[http://arxiv.org/pdf/1908.09891](http://arxiv.org/pdf/1908.09891)


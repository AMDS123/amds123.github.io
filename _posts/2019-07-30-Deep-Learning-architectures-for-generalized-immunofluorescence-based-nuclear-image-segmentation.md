---
layout: post
title: "Deep Learning architectures for generalized immunofluorescence based nuclear image segmentation"
date: 2019-07-30 14:23:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Deep_Learning Detection
author: Florian Kromp, Lukas Fischer, Eva Bozsaky, Inge Ambros, Wolfgang Doerr, Sabine Taschner-Mandl, Peter Ambros, Allan Hanbury
mathjax: true
---

* content
{:toc}

##### Abstract
Separating and labeling each instance of a nucleus (instance-aware segmentation) is the key challenge in segmenting single cell nuclei on fluorescence microscopy images. Deep Neural Networks can learn the implicit transformation of a nuclear image into a probability map indicating the class membership of each pixel (nucleus or background), but the use of post-processing steps to turn the probability map into a labeled object mask is error-prone. This especially accounts for nuclear images of tissue sections and nuclear images across varying tissue preparations. In this work, we aim to evaluate the performance of state-of-the-art deep learning architectures to segment nuclei in fluorescence images of various tissue origins and sample preparation types without post-processing. We compare architectures that operate on pixel to pixel translation and an architecture that operates on object detection and subsequent locally applied segmentation. In addition, we propose a novel strategy to create artificial images to extend the training set. We evaluate the influence of ground truth annotation quality, image scale and segmentation complexity on segmentation performance. Results show that three out of four deep learning architectures (U-Net, U-Net with ResNet34 backbone, Mask R-CNN) can segment fluorescent nuclear images on most of the sample preparation types and tissue origins with satisfactory segmentation performance. Mask R-CNN, an architecture designed to address instance aware segmentation tasks, outperforms other architectures. Equal nuclear mean size, consistent nuclear annotations and the use of artificially generated images result in overall acceptable precision and recall across different tissues and sample preparation types.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12975](http://arxiv.org/abs/1907.12975)

##### PDF
[http://arxiv.org/pdf/1907.12975](http://arxiv.org/pdf/1907.12975)


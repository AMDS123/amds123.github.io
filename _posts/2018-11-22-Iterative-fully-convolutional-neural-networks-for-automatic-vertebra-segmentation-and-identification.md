---
layout: post
title: "Iterative fully convolutional neural networks for automatic vertebra segmentation and identification"
date: 2018-11-22 14:11:32
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Detection
author: Nikolas Lessmann, Bram van Ginneken, Pim A. de Jong, Ivana I&#x161;gum
mathjax: true
---

* content
{:toc}

##### Abstract
Precise segmentation and anatomical identification of the vertebrae provides the basis for automatic analysis of the spine, such as detection of vertebral compression fractures or other abnormalities. Most dedicated spine CT and MR scans as well as scans of the chest, abdomen or neck cover only part of the spine. Segmentation and identification should therefore not rely on the visibility of certain vertebrae or a certain number of vertebrae. We propose an iterative instance segmentation approach that uses a fully convolutional neural network to segment and label vertebrae one after the other, independently of the number of visible vertebrae. This instance-by-instance segmentation is enabled by combining the network with a memory component that retains information about already segmented vertebrae. The network iteratively analyzes image patches, using information from both image and memory to search for the next vertebra. To efficiently traverse the image, we include the prior knowledge that the vertebrae are always located next to each other, which is used to follow the vertebral column. This method was evaluated with five diverse datasets, including multiple modalities (CT and MR), various fields of view and coverages of different sections of the spine, and a particularly challenging set of low-dose chest CT scans. The proposed iterative segmentation method compares favorably with state-of-the-art methods and is fast, flexible and generalizable.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.04383](http://arxiv.org/abs/1804.04383)

##### PDF
[http://arxiv.org/pdf/1804.04383](http://arxiv.org/pdf/1804.04383)


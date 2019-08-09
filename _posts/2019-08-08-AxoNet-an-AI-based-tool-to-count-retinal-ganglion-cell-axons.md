---
layout: post
title: "AxoNet: an AI-based tool to count retinal ganglion cell axons"
date: 2019-08-08 03:43:11
categories: arXiv_CV
tags: arXiv_CV GAN CNN Deep_Learning Recognition
author: Matthew D. Ritch, Bailey G. Hannon, A. Thomas Read, Andrew J. Feola, Grant A. Cull, Juan Reynaud, John C. Morrison, Claude F. Burgoyne, Machelle T. Pardue, C. Ross Ethier
mathjax: true
---

* content
{:toc}

##### Abstract
Goal: In this work, we develop a robust, extensible tool to automatically and accurately count retinal ganglion cell axons in images of optic nerve tissue from various animal models of glaucoma. Methods: The U-Net convolutional neural network architecture was adapted to learn pixelwise axon count density estimates, which were then integrated over the image area to determine axon counts. The tool, termed AxoNet, was trained and evaluated using a dataset containing images of optic nerve regions randomly selected from complete cross sections of intact rat optic nerves and manually annotated for axon count and location. Both control and damaged optic nerves were used. This rat-trained network was then applied to a separate dataset of non-human primate (NHP) optic nerve images. AxoNet was then compared to two existing automated axon counting tools, AxonMaster and AxonJ, using both datasets. Results: AxoNet outperformed the existing tools on both the rat and NHP optic nerve datasets as judged by mean absolute error, R2 values when regressing automated vs. manual counts, and Bland-Altman analysis. Conclusion: The proposed tool allows for accurate quantification of axon numbers as a measure of glaucomatous damage. AxoNet is robust to variations in optic nerve tissue damage extent, image quality, and species of mammal. Significance: The deep learning method does not rely on hand-crafted image features for axon recognition. Therefore, this approach is not species-specific and can be extended to quantify additional optic nerve features. It will aid evaluation of optic nerve changes in glaucoma and potentially other neurodegenerative diseases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02919](http://arxiv.org/abs/1908.02919)

##### PDF
[http://arxiv.org/pdf/1908.02919](http://arxiv.org/pdf/1908.02919)


---
layout: post
title: "Unsupervised brain lesion segmentation from MRI using a convolutional autoencoder"
date: 2018-11-23 19:53:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Hans E. Atlason, Askell Love, Sigurdur Sigurdsson, Vilmundur Gudnason, Lotta M. Ellingsen
mathjax: true
---

* content
{:toc}

##### Abstract
Lesions that appear hyperintense in both Fluid Attenuated Inversion Recovery (FLAIR) and T2-weighted magnetic resonance images (MRIs) of the human brain are common in the brains of the elderly population and may be caused by ischemia or demyelination. Lesions are biomarkers for various neurodegenerative diseases, making accurate quantification of them important for both disease diagnosis and progression. Automatic lesion detection using supervised learning requires manually annotated images, which can often be impractical to acquire. Unsupervised lesion detection, on the other hand, does not require any manual delineation; however, these methods can be challenging to construct due to the variability in lesion load, placement of lesions, and voxel intensities. Here we present a novel approach to address this problem using a convolutional autoencoder, which learns to segment brain lesions as well as the white matter, gray matter, and cerebrospinal fluid by reconstructing FLAIR images as conical combinations of softmax layer outputs generated from the corresponding T1, T2, and FLAIR images. Some of the advantages of this model are that it accurately learns to segment lesions regardless of lesion load, and it can be used to quickly and robustly segment new images that were not in the training set. Comparisons with state-of-the-art segmentation methods evaluated on ground truth manual labels indicate that the proposed method works well for generating accurate lesion segmentations without the need for manual annotations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09655](https://arxiv.org/abs/1811.09655)

##### PDF
[https://arxiv.org/pdf/1811.09655](https://arxiv.org/pdf/1811.09655)


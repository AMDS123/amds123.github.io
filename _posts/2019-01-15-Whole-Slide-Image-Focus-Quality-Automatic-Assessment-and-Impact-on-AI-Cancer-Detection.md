---
layout: post
title: "Whole-Slide Image Focus Quality: Automatic Assessment and Impact on AI Cancer Detection"
date: 2019-01-15 00:31:35
categories: arXiv_CV
tags: arXiv_CV Review Object_Detection CNN Prediction Quantitative Detection
author: Timo Kohlberger, Yun Liu, Melissa Moran, Po-Hsuan (Cameron)Chen, Trissia Brown, Craig H. Mermel, Jason D. Hipp, Martin C. Stumpe
mathjax: true
---

* content
{:toc}

##### Abstract
Digital pathology enables remote access or consults and powerful image analysis algorithms. However, the slide digitization process can create artifacts such as out-of-focus (OOF). OOF is often only detected upon careful review, potentially causing rescanning and workflow delays. Although scan-time operator screening for whole-slide OOF is feasible, manual screening for OOF affecting only parts of a slide is impractical. We developed a convolutional neural network (ConvFocus) to exhaustively localize and quantify the severity of OOF regions on digitized slides. ConvFocus was developed using our refined semi-synthetic OOF data generation process, and evaluated using real whole-slide images spanning 3 different tissue types and 3 different stain types that were digitized by two different scanners. ConvFocus's predictions were compared with pathologist-annotated focus quality grades across 514 distinct regions representing 37,700 35x35μm image patches, and 21 digitized "z-stack" whole-slide images that contain known OOF patterns. When compared to pathologist-graded focus quality, ConvFocus achieved Spearman rank coefficients of 0.81 and 0.94 on two scanners, and reproduced the expected OOF patterns from z-stack scanning. We also evaluated the impact of OOF on the accuracy of a state-of-the-art metastatic breast cancer detector and saw a consistent decrease in performance with increasing OOF. Comprehensive whole-slide OOF categorization could enable rescans prior to pathologist review, potentially reducing the impact of digitization focus issues on the clinical workflow. We show that the algorithm trained on our semi-synthetic OOF data generalizes well to real OOF regions across tissue types, stains, and scanners. Finally, quantitative OOF maps can flag regions that might otherwise be misclassified by image analysis algorithms, preventing OOF-induced errors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04619](https://arxiv.org/abs/1901.04619)

##### PDF
[https://arxiv.org/pdf/1901.04619](https://arxiv.org/pdf/1901.04619)


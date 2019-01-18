---
layout: post
title: "Foreground-aware Image Inpainting"
date: 2019-01-17 18:39:10
categories: arXiv_CV
tags: arXiv_CV Inference
author: Wei Xiong, Zhe Lin, Jimei Yang, Xin Lu, Connelly Barnes, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Existing image inpainting methods typically fill holes by borrowing information from surrounding image regions. They often produce unsatisfactory results when the holes overlap with or touch foreground objects due to lack of information about the actual extent of foreground and background regions within the holes. These scenarios, however, are very important in practice, especially for applications such as distracting object removal. To address the problem, we propose a foreground-aware image inpainting system that explicitly disentangles structure inference and content completion. Specifically, our model learns to predict the foreground contour first, and then inpaints the missing region using the predicted contour as guidance. We show that by this disentanglement, the contour completion model predicts reasonable contours of objects, and further substantially improves the performance of image inpainting. Experiments show that our method significantly outperforms existing methods and achieves superior inpainting results on challenging cases with complex compositions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05945](https://arxiv.org/abs/1901.05945)

##### PDF
[https://arxiv.org/pdf/1901.05945](https://arxiv.org/pdf/1901.05945)


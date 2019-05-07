---
layout: post
title: "Visual and Semantic Knowledge Transfer for Large Scale Semi-supervised Object Detection"
date: 2018-03-13 16:09:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Yuxing Tang, Josiah Wang, Xiaofang Wang, Boyang Gao, Emmanuel Dellandrea, Robert Gaizauskas, Liming Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep CNN-based object detection systems have achieved remarkable success on several large-scale object detection benchmarks. However, training such detectors requires a large number of labeled bounding boxes, which are more difficult to obtain than image-level annotations. Previous work addresses this issue by transforming image-level classifiers into object detectors. This is done by modeling the differences between the two on categories with both image-level and bounding box annotations, and transferring this information to convert classifiers to detectors for categories without bounding box annotations. We improve this previous work by incorporating knowledge about object similarities from visual and semantic domains during the transfer process. The intuition behind our proposed method is that visually and semantically similar categories should exhibit more common transferable properties than dissimilar categories, e.g. a better detector would result by transforming the differences between a dog classifier and a dog detector onto the cat class, than would by transforming from the violin class. Experimental results on the challenging ILSVRC2013 detection dataset demonstrate that each of our proposed object similarity based knowledge transfer methods outperforms the baseline methods. We found strong evidence that visual similarity and semantic relatedness are complementary for the task, and when combined notably improve detection, achieving state-of-the-art detection performance in a semi-supervised setting.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.03145](https://arxiv.org/abs/1801.03145)

##### PDF
[https://arxiv.org/pdf/1801.03145](https://arxiv.org/pdf/1801.03145)


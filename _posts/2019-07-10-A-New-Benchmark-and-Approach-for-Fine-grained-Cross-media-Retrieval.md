---
layout: post
title: "A New Benchmark and Approach for Fine-grained Cross-media Retrieval"
date: 2019-07-10 01:15:22
categories: arXiv_CV
tags: arXiv_CV Knowledge Represenation_Learning Classification
author: Xiangteng He, Yuxin Peng, Liu Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-media retrieval is to return the results of various media types corresponding to the query of any media type. Existing researches generally focus on coarse-grained cross-media retrieval. When users submit an image of "Slaty-backed Gull" as a query, coarse-grained cross-media retrieval treats it as "Bird", so that users can only get the results of "Bird", which may include other bird species with similar appearance (image and video), descriptions (text) or sounds (audio), such as "Herring Gull". Such coarse-grained cross-media retrieval is not consistent with human lifestyle, where we generally have the fine-grained requirement of returning the exactly relevant results of "Slaty-backed Gull" instead of "Herring Gull". However, few researches focus on fine-grained cross-media retrieval, which is a highly challenging and practical task. Therefore, in this paper, we first construct a new benchmark for fine-grained cross-media retrieval, which consists of 200 fine-grained subcategories of the "Bird", and contains 4 media types, including image, text, video and audio. To the best of our knowledge, it is the first benchmark with 4 media types for fine-grained cross-media retrieval. Then, we propose a uniform deep model, namely FGCrossNet, which simultaneously learns 4 types of media without discriminative treatments. We jointly consider three constraints for better common representation learning: classification constraint ensures the learning of discriminative features, center constraint ensures the compactness characteristic of the features of the same subcategory, and ranking constraint ensures the sparsity characteristic of the features of different subcategories. Extensive experiments verify the usefulness of the new benchmark and the effectiveness of our FGCrossNet. They will be made available at https://github.com/PKU-ICST-MIPL/FGCrossNet_ACMMM2019.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04476](http://arxiv.org/abs/1907.04476)

##### PDF
[http://arxiv.org/pdf/1907.04476](http://arxiv.org/pdf/1907.04476)


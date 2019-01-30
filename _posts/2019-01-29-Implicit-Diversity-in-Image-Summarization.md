---
layout: post
title: "Implicit Diversity in Image Summarization"
date: 2019-01-29 13:13:16
categories: arXiv_CV
tags: arXiv_CV Summarization CNN
author: L. Elisa Celis, Vijay Keswani
mathjax: true
---

* content
{:toc}

##### Abstract
Case studies, such as Kay et al., 2015 have shown that in image summarization, such as with Google Image Search, the people in the results presented for occupations are more imbalanced with respect to sensitive attributes such as gender and ethnicity than the ground truth. Most of the existing approaches to correct for this problem in image summarization assume that the images are labelled and use the labels for training the model and correcting for biases. However, these labels may not always be present. Furthermore, it is often not possible (nor even desirable) to automatically classify images by sensitive attributes such as gender or race. Moreover, balancing according to the labels does not guarantee that the diversity will be visibly apparent - arguably the only metric that matters when selecting diverse images. We develop a novel approach that takes as input a visibly diverse control set of images and uses this set to produce images in response to a query which is similarly visibly diverse. We implement this approach using pre-trained and modified Convolutional Neural Networks like VGG-16, and evaluate our approach empirically on the Image dataset compiled and used by Kay et al., 2015. We compare our results with the Google Image Search results from Kay et al., 2015 and natural baselines and observe that our algorithm produces images that are accurate with respect to their similarity to the query images (on par with that of the Google Image Search results), but significantly outperforms with respect to visible diversity as measured by their similarity to our diverse control set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10265](http://arxiv.org/abs/1901.10265)

##### PDF
[http://arxiv.org/pdf/1901.10265](http://arxiv.org/pdf/1901.10265)


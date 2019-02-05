---
layout: post
title: "Learning to segment with image-level supervision"
date: 2019-02-04 17:56:16
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Weakly_Supervised CNN
author: Gaurav Pandey, Ambedkar Dukkipati
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks have achieved the state-of-the-art for semantic image segmentation tasks. However, training these networks requires access to densely labeled images, which are known to be very expensive to obtain. On the other hand, the web provides an almost unlimited source of images annotated at the image level. How can one utilize this much larger weakly annotated set for tasks that require dense labeling? Prior work often relied on localization cues, such as saliency maps, objectness priors, bounding boxes etc., to address this challenging problem. In this paper, we propose a model that generates auxiliary labels for each image, while simultaneously forcing the output of the CNN to satisfy the mean-field constraints imposed by a conditional random field. We show that one can enforce the CRF constraints by forcing the distribution at each pixel to be close to the distribution of its neighbors. This is in stark contrast with methods that compute a recursive expansion of the mean-field distribution using a recurrent architecture and train the resultant distribution. Instead, the proposed model adds an extra loss term to the output of the CNN, and hence, is faster than recursive implementations. We achieve the state-of-the-art for weakly supervised semantic image segmentation on VOC 2012 dataset, assuming no manually labeled pixel level information is available. Furthermore, the incorporation of conditional random fields in CNN incurs little extra time during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.01262](http://arxiv.org/abs/1705.01262)

##### PDF
[http://arxiv.org/pdf/1705.01262](http://arxiv.org/pdf/1705.01262)


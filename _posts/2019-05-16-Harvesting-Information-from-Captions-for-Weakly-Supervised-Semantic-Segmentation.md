---
layout: post
title: "Harvesting Information from Captions for Weakly Supervised Semantic Segmentation"
date: 2019-05-16 14:35:09
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation Weakly_Supervised Caption Embedding CNN Semantic_Segmentation
author: Johann Sawatzky, Debayan Banerjee, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
Since acquiring pixel-wise annotations for training convolutional neural networks for semantic image segmentation is time-consuming, weakly supervised approaches that only require class tags have been proposed. In this work, we propose another form of supervision, namely image captions as they can be found on the Internet. These captions have two advantages. They do not require additional curation as it is the case for the clean class tags used by current weakly supervised approaches and they provide textual context for the classes present in an image. To leverage such textual context, we deploy a multi-modal network that learns a joint embedding of the visual representation of the image and the textual representation of the caption. The network estimates text activation maps (TAMs) for class names as well as compound concepts, i.e. combinations of nouns and their attributes. The TAMs of compound concepts describing classes of interest substantially improve the quality of the estimated class activation maps which are then used to train a network for semantic segmentation. We evaluate our method on the COCO dataset where it achieves state of the art results for weakly supervised image segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06784](http://arxiv.org/abs/1905.06784)

##### PDF
[http://arxiv.org/pdf/1905.06784](http://arxiv.org/pdf/1905.06784)


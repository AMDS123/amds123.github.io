---
layout: post
title: "Visual-Relation Conscious Image Generation from Structured-Text"
date: 2019-08-05 17:33:00
categories: arXiv_CV
tags: arXiv_CV GAN Image_Generation Relation
author: Duc Minh Vo, Akihiro Sugimoto
mathjax: true
---

* content
{:toc}

##### Abstract
Generating realistic images from text descriptions is a challenging problem and has many applications such as image editing or computer-aided design. In spite of recent progress on this text-to-image generation based on GANs, generating realistic images from complex descriptions with many entities in a general scene is not yet achieved in the literature. In the presence of multiple entities, the relationships between entities become important because they condition the location of each entity. We propose a GAN-based end-to-end network that learns the visual-relation layout between entities from given texts and conditions the layout in generating images. Our proposed network consists of the visual-relation layout module and the stacking-GANs. The visual-relation layout module predicts bounding-boxes for all the entities given in an input text so that each of them uniquely corresponds to each entity while keeping its involved relationships. The visual-relation layout is obtained by aggregating all the bounding-boxes, reflecting the scene structure given in text. The stacking-GANs is the stack of three GANs conditioned on the output of previous GAN and the visual-relation layout, consistently capturing the scene structure. Our network realistically renders entities' details in high resolution while keeping the scene structure. Experimental results on two public datasets show outperformances of our method against state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01741](http://arxiv.org/abs/1908.01741)

##### PDF
[http://arxiv.org/pdf/1908.01741](http://arxiv.org/pdf/1908.01741)


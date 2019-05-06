---
layout: post
title: "Attention-based Natural Language Person Retrieval"
date: 2017-05-24 18:36:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Caption CNN Image_Classification RNN Classification Deep_Learning
author: Tao Zhou, Muhao Chen, Jie Yu, Demetri Terzopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Following the recent progress in image classification and captioning using deep learning, we develop a novel natural language person retrieval system based on an attention mechanism. More specifically, given the description of a person, the goal is to localize the person in an image. To this end, we first construct a benchmark dataset for natural language person retrieval. To do so, we generate bounding boxes for persons in a public image dataset from the segmentation masks, which are then annotated with descriptions and attributes using the Amazon Mechanical Turk. We then adopt a region proposal network in Faster R-CNN as a candidate region generator. The cropped images based on the region proposals as well as the whole images with attention weights are fed into Convolutional Neural Networks for visual feature extraction, while the natural language expression and attributes are input to Bidirectional Long Short- Term Memory (BLSTM) models for text feature extraction. The visual and text features are integrated to score region proposals, and the one with the highest score is retrieved as the output of our system. The experimental results show significant improvement over the state-of-the-art method for generic object retrieval and this line of research promises to benefit search in surveillance video footage.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.08923](https://arxiv.org/abs/1705.08923)

##### PDF
[https://arxiv.org/pdf/1705.08923](https://arxiv.org/pdf/1705.08923)


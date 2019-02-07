---
layout: post
title: "Squared English Word: A Method of Generating Glyph to Use Super Characters for Sentiment Analysis"
date: 2019-01-24 17:10:02
categories: arXiv_CL
tags: arXiv_CL Sentiment Classification
author: Baohua Sun, Lin Yang, Catherine Chi, Wenhan Zhang, Michael Lin
mathjax: true
---

* content
{:toc}

##### Abstract
The Super Characters method addresses sentiment analysis problems by first converting the input text into images and then applying 2D-CNN models to classify the sentiment. It achieves state of the art performance on many benchmark datasets. However, it is not as straightforward to apply in Latin languages as in Asian languages. Because the 2D-CNN model is designed to recognize two-dimensional images, it is better if the inputs are in the form of glyphs. In this paper, we propose SEW (Squared English Word) method generating a squared glyph for each English word by drawing Super Characters images of each English word at the alphabet level, combining the squared glyph together into a whole Super Characters image at the sentence level, and then applying the CNN model to classify the sentiment within the sentence. We applied the SEW method to Wikipedia dataset and obtained a 2.1% accuracy gain compared to the original Super Characters method. In the CL-Aff shared task on the HappyDB dataset, we applied Super Characters with SEW method and obtained 86.9% accuracy for agency classification and 85.8% for social accuracy classification on the validation set based on 80%:20% random split on the given labeled dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02160](http://arxiv.org/abs/1902.02160)

##### PDF
[http://arxiv.org/pdf/1902.02160](http://arxiv.org/pdf/1902.02160)


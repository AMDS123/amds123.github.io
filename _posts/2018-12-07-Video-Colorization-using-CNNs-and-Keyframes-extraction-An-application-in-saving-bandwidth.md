---
layout: post
title: "Video Colorization using CNNs and Keyframes extraction: An application in saving bandwidth"
date: 2018-12-07 09:24:39
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ankur Singh, Anurag Chanani, Harish Karnick
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we tackle the problem of Colorization of Grayscale Videos given a few colored keyframes of the video. We propose a model that extracts keyframes from the video and trains a Convolutional Neural Network from scratch on these colored frames. Once the model has been trained we colorize the rest of the frames of the video given their grayscale versions. An application of this technique is in saving bandwidth while sending raw colored videos that haven't gone through any compression. A raw colored video takes upto three times more memory than it's grayscale version. We can exploit this fact and send a grayscale video along with our trained model instead of a colored one. This will reduce bandwidth usage to upto three times.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03858](http://arxiv.org/abs/1812.03858)

##### PDF
[http://arxiv.org/pdf/1812.03858](http://arxiv.org/pdf/1812.03858)


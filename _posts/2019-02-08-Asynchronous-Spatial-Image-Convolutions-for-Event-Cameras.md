---
layout: post
title: "Asynchronous Spatial Image Convolutions for Event Cameras"
date: 2019-02-08 16:37:57
categories: arXiv_CV
tags: arXiv_CV Image_Caption Tracking Detection
author: Cedric Scheerlinck, Nick Barnes, Robert Mahony
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial convolution is arguably the most fundamental of 2D image processing operations. Conventional spatial image convolution can only be applied to a conventional image, that is, an array of pixel values (or similar image representation) that are associated with a single instant in time. Event cameras have serial, asynchronous output with no natural notion of an image frame, and each event arrives with a different timestamp. In this paper, we propose a method to compute the convolution of a linear spatial kernel with the output of an event camera. The approach operates on the event stream output of the camera directly without synthesising pseudo-image frames as is common in the literature. The key idea is the introduction of an internal state that directly encodes the convolved image information, which is updated asynchronously as each event arrives from the camera. The state can be read-off as-often-as and whenever required for use in higher level vision algorithms for real-time robotic systems. We demonstrate the application of our method to corner detection, providing an implementation of a Harris corner-response "state" that can be used in real-time for feature detection and tracking on robotic systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00438](http://arxiv.org/abs/1812.00438)

##### PDF
[http://arxiv.org/pdf/1812.00438](http://arxiv.org/pdf/1812.00438)


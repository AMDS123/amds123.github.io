---
layout: post
title: "Extract and Merge: Merging extracted humans from different images utilizing Mask R-CNN"
date: 2019-08-01 13:50:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Asati Minkesh, Kraisittipong Worranitta, Miyachi Taizo
mathjax: true
---

* content
{:toc}

##### Abstract
Selecting human objects out of the various type of objects in images and merging them with other scenes is manual and day-to-day work for photo editors. Although recently Adobe photoshop released "select subject" tool which automatically selects the foreground object in an image, but still requires fine manual tweaking separately. In this work, we proposed an application utilizing Mask R-CNN (for object detection and mask segmentation) that can extract human instances from multiple images and merge them with a new background. This application does not add any overhead to Mask R-CNN, running at 5 frames per second. It can extract human instances from any number of images or videos from merging them together. We also structured the code to accept videos of different lengths as input and length of the output-video will be equal to the longest input-video. We wanted to create a simple yet effective application that can serve as a base for photo editing and do most time-consuming work automatically, so, editors can focus more on the design part. Other application could be to group people together in a single picture with a new background from different images which could not be physically together. We are showing single-person and multi-person extraction and placement in two different backgrounds. Also, we are showing a video example with single-person extraction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00398](http://arxiv.org/abs/1908.00398)

##### PDF
[http://arxiv.org/pdf/1908.00398](http://arxiv.org/pdf/1908.00398)


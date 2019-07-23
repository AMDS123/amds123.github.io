---
layout: post
title: "Human Extraction and Scene Transition utilizing Mask R-CNN"
date: 2019-07-20 23:57:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection Recognition
author: Asati Minkesh, Kraittipong Worranitta, Miyachi Taizo
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is a trendy branch of computer vision, especially on human recognition and pedestrian detection. Recognizing the complete body of a person has always been a difficult problem. Over the years, researchers proposed various methods, and recently, a breakthrough came into the light as Mask R-CNN. Based on Faster R-CNN, Mask R-CNN was able to generate a segmentation mask for each instance. We propose an application to extract multiple persons and put them into a new background image utilizing Mask R-CNN. Mask R-CNN detects all type of object mask from images. Then our algorithm considers only the target person and extracts a person only without obstacles, such as dogs in front of the person, and the user also can select multiple persons as their expectations. Our algorithm is effective for both an image and a video irrespective of the length of it. Also, extract those persons and place them into the new background. Our algorithm does not add any overhead to Mask R-CNN, running at 5 fps. We show examples of yoga-person in an image and a dancer in a dance-video frame. We hope our simple and effective approach would serve as a baseline for replacing the image background and help ease future research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08884](http://arxiv.org/abs/1907.08884)

##### PDF
[http://arxiv.org/pdf/1907.08884](http://arxiv.org/pdf/1907.08884)


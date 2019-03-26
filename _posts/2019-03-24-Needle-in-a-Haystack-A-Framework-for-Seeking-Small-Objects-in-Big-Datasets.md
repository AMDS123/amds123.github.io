---
layout: post
title: "Needle in a Haystack: A Framework for Seeking Small Objects in Big Datasets"
date: 2019-03-24 16:57:21
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Detection
author: Joel Brogan, Aparna Bharati, Daniel Moreira, Kevin Bowyer, Patrick Flynn, Anderson Rocha, Walter Scheirer
mathjax: true
---

* content
{:toc}

##### Abstract
Images from social media can reflect diverse viewpoints, heated arguments, and expressions of creativity --- adding new complexity to search tasks. Researchers working on Content-Based Image Retrieval (CBIR) have traditionally tuned their search algorithms to match filtered results with user search intent. However, we are now bombarded with composite images of unknown origin, authenticity, and even meaning. With such uncertainty, users may not have an initial idea of what the results of a search query should look like. For instance, hidden people, spliced objects, and subtly altered scenes can be difficult for a user to detect initially in a meme image, but may contribute significantly to its composition. We propose a new framework for image retrieval that models object-level regions using image keypoints retrieved from an image index, which are then used to accurately weight small contributing objects within the results, without the need for costly object detection steps. We call this method Needle-Haystack (NH) scoring, and it is optimized for fast matrix operations on CPUs. We show that this method not only performs comparably to state-of-the-art methods in classic CBIR problems, but also outperforms them in fine-grained object- and instance-level retrieval on the Oxford 5K, Paris 6K, Google-Landmarks, and NIST MFC2018 datasets, as well as meme-style imagery from Reddit.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10019](http://arxiv.org/abs/1903.10019)

##### PDF
[http://arxiv.org/pdf/1903.10019](http://arxiv.org/pdf/1903.10019)


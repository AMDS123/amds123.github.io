---
layout: post
title: "Night-to-Day Image Translation for Retrieval-based Localization"
date: 2019-03-04 11:09:08
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval GAN
author: Asha Anoosheh, Torsten Sattler, Radu Timofte, Marc Pollefeys, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Visual localization is a key step in many robotics pipelines, allowing the robot to (approximately) determine its position and orientation in the world. An efficient and scalable approach to visual localization is to use image retrieval techniques. These approaches identify the image most similar to a query photo in a database of geo-tagged images and approximate the query's pose via the pose of the retrieved database image. However, image retrieval across drastically different illumination conditions, e.g. day and night, is still a problem with unsatisfactory results, even in this age of powerful neural models. This is due to a lack of a suitably diverse dataset with true correspondences to perform end-to-end learning. A recent class of neural models allows for realistic translation of images among visual domains with relatively little training data and, most importantly, without ground-truth pairings. In this paper, we explore the task of accurately localizing images captured from two traversals of the same area in both day and night. We propose ToDayGAN - a modified image-translation model to alter nighttime driving images to a more useful daytime representation. We then compare the daytime and translated night images to obtain a pose estimate for the night image using the known 6-DOF position of the closest day image. Our approach improves localization performance by over 250% compared the current state-of-the-art, in the context of standard metrics in multiple categories.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.09767](http://arxiv.org/abs/1809.09767)

##### PDF
[http://arxiv.org/pdf/1809.09767](http://arxiv.org/pdf/1809.09767)


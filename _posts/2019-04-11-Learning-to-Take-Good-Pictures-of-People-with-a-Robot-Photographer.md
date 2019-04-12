---
layout: post
title: "Learning to Take Good Pictures of People with a Robot Photographer"
date: 2019-04-11 13:38:45
categories: arXiv_RO
tags: arXiv_RO Face CNN
author: Rhys Newbury, Akansel Cosgun, Mehmet Koseoglu, Tom Drummond
mathjax: true
---

* content
{:toc}

##### Abstract
We present a robotic system capable of navigating autonomously by following a line and taking good quality pictures of people. When a group of people are detected, the robot rotates towards them and then back to line while continuously taking pictures from different angles. Each picture is processed in the cloud where its quality is estimated in a two-stage algorithm. First, features such as the face orientation and likelihood of facial emotions are input to a fully connected neural network to assign a quality score to each face. Second, a representation is extracted by abstracting faces from the image and it is input to a to Convolutional Neural Network (CNN) to classify the quality of the overall picture. We collected a dataset in which a picture was labeled as good quality if subjects are well-positioned in the image and oriented towards the camera with a pleasant expression. Our approach detected the quality of pictures with 78.4% accuracy in this dataset and received a better mean user rating (3.71/5) than a heuristic method that uses photographic composition procedures in a study where 97 human judges rated each picture. A statistical analysis against the state-of-the-art verified the quality of the resulting pictures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05688](http://arxiv.org/abs/1904.05688)

##### PDF
[http://arxiv.org/pdf/1904.05688](http://arxiv.org/pdf/1904.05688)


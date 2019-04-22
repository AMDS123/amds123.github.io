---
layout: post
title: "Person Identification with Visual Summary for a Safe Access to a Smart Home"
date: 2019-04-18 23:24:00
categories: arXiv_CV
tags: arXiv_CV Face CNN Detection Recognition
author: Shahinur Alam, Mohammed Yeasin
mathjax: true
---

* content
{:toc}

##### Abstract
SafeAccess is an integrated system designed to provide easier and safer access to a smart home for people with or without disabilities. The system is designed to enhance safety and promote the independence of people with disability (i.e., visually impaired). The key functionality of the system includes the detection and identification of human and generating contextual visual summary from the real-time video streams obtained from the cameras placed in strategic locations around the house. In addition, the system classifies human into groups (i.e. friends/families/caregiver versus intruders/burglars/unknown). These features allow the user to grant/deny remote access to the premises or ability to call emergency services. In this paper, we focus on designing a prototype system for the smart home and building a robust recognition engine that meets the system criteria and addresses speed, accuracy, deployment and environmental challenges under a wide variety of practical and real-life situations. To interact with the system, we implemented a dialog enabled interface to create a personalized profile using face images or video of friend/families/caregiver. To improve computational efficiency, we apply change detection to filter out frames and use Faster-RCNN to detect the human presence and extract faces using Multitask Cascaded Convolutional Networks (MTCNN). Subsequently, we apply LBP/FaceNet to identify a person and groups by matching extracted faces with the profile. SafeAccess sends a visual summary to the users with an MMS containing a person's name if any match found or as "Unknown", scene image, facial description, and contextual information. SafeAccess identifies friends/families/caregiver versus intruders/unknown with an average F-score 0.97 and generates a visual summary from 10 classes with an average accuracy of 98.01%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01178](http://arxiv.org/abs/1904.01178)

##### PDF
[http://arxiv.org/pdf/1904.01178](http://arxiv.org/pdf/1904.01178)


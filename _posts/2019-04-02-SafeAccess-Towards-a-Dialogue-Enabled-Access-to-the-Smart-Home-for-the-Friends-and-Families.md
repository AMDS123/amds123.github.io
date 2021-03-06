---
layout: post
title: "SafeAccess: Towards a Dialogue Enabled Access to the Smart Home for the Friends and Families"
date: 2019-04-02 02:25:31
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Detection Recognition
author: Shahinur Alam, Mohammed Yeasin
mathjax: true
---

* content
{:toc}

##### Abstract
SafeAccess is an interactive assistive technology solution to enhance the safety and independence of people with disability (i.e., visually impaired and limited mobility). The system output is the classification and identification of a person in front of the door or around the house into groups such as friends/families/caregiver versus intruders/burglars/unknown. This will allow the user to grant/deny remote access to the premises or ability to call emergency services. In this paper, we focus on designing a prototype system and building a robust recognition engine that meets the system criteria and addresses speed, accuracy, deployment and environmental challenges under a wide variety of practical and real-life situations. The premise is assumed to be equipped with cameras placed at strategic locations to capture images and videos. To interact with the system, we implemented a dialog enabled interface to create a personalized profile using face images or video of friend/families/caregiver. To improve the computational efficiency, we apply change detection to filter out frames and use Faster-RCNN to detect the human presence and extract faces using Multitask Cascaded Convolutional Networks (MTCNN). Subsequently, we apply LBP/FaceNet to identify a person and groups by matching extracted faces with the profile. SafeAccess sends identification result to the users with an MMS containing persons name if any match found or as intruder, scene image and a confidence score between 1 to 10. In addition, the daily, weekly and monthly summarized report of the past incident can be queried from the system. Empirical analysis shows a robust performance with an F-score of 0.97 in identifying friends/families/caregiver versus intruders/unknown.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01178](http://arxiv.org/abs/1904.01178)

##### PDF
[http://arxiv.org/pdf/1904.01178](http://arxiv.org/pdf/1904.01178)


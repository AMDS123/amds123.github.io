---
layout: post
title: "Finding Rats in Cats: Detecting Stealthy Attacks using Group Anomaly Detection"
date: 2019-05-16 17:16:52
categories: arXiv_AI
tags: arXiv_AI Adversarial Embedding Deep_Learning Detection
author: Aditya Kuppa, Slawomir Grzonkowski, Muhammad Rizwan Asghar, Nhien-An Le-Khac
mathjax: true
---

* content
{:toc}

##### Abstract
Advanced attack campaigns span across multiple stages and stay stealthy for long time periods. There is a growing trend of attackers using off-the-shelf tools and pre-installed system applications (such as \emph{powershell} and \emph{wmic}) to evade the detection because the same tools are also used by system administrators and security analysts for legitimate purposes for their routine tasks. To start investigations, event logs can be collected from operational systems; however, these logs are generic enough and it often becomes impossible to attribute a potential attack to a specific attack group. Recent approaches in the literature have used anomaly detection techniques, which aim at distinguishing between malicious and normal behavior of computers or network systems. Unfortunately, anomaly detection systems based on point anomalies are too rigid in a sense that they could miss the malicious activity and classify the attack, not an outlier. Therefore, there is a research challenge to make better detection of malicious activities. To address this challenge, in this paper, we leverage Group Anomaly Detection (GAD), which detects anomalous collections of individual data points. 
 Our approach is to build a neural network model utilizing Adversarial Autoencoder (AAE-$\alpha$) in order to detect the activity of an attacker who leverages off-the-shelf tools and system applications. In addition, we also build \textit{Behavior2Vec} and \textit{Command2Vec} sentence embedding deep learning models specific for feature extraction tasks. We conduct extensive experiments to evaluate our models on real-world datasets collected for a period of two months. The empirical results demonstrate that our approach is effective and robust in discovering targeted attacks, pen-tests, and attack campaigns leveraging custom tools.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07273](http://arxiv.org/abs/1905.07273)

##### PDF
[http://arxiv.org/pdf/1905.07273](http://arxiv.org/pdf/1905.07273)


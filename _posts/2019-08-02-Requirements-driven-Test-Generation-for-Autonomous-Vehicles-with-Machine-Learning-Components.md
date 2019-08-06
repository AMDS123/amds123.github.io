---
layout: post
title: "Requirements-driven Test Generation for Autonomous Vehicles with Machine Learning Components"
date: 2019-08-02 23:59:26
categories: arXiv_RO
tags: arXiv_RO
author: Cumhur Erkan Tuncali, Georgios Fainekos, Danil Prokhorov, Hisahiro Ito, James Kapinski
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous vehicles are complex systems that are challenging to test and debug. A requirements-driven approach to the development process can decrease the resources required to design and test these systems, while simultaneously increasing the reliability. We present a testing framework that uses signal temporal logic (STL), which is a precise and unambiguous requirements language. Our framework evaluates test cases against the STL formulae and additionally uses the requirements to automatically identify test cases that fail to satisfy the requirements. One of the key features of our tool is the support for machine learning (ML) components in the system design, such as deep neural networks. The framework allows evaluation of the control algorithms, including the ML components, and it also includes models of CCD camera, lidar, and radar sensors, as well as the vehicle environment. We use multiple methods to generate test cases, including covering arrays, which is an efficient method to search discrete variable spaces. The resulting test cases can be used to debug the controller design by identifying controller behaviors that do not satisfy requirements. The test cases can also enhance the testing phase of development by identifying critical corner cases that correspond to the limits of the system's allowed behaviors. We present STL requirements for an autonomous vehicle system, which capture both component-level and system-level behaviors. Additionally, we present three driving scenarios and demonstrate how our requirements-driven testing framework can be used to identify critical system behaviors, which can be used to support the development process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01094](http://arxiv.org/abs/1908.01094)

##### PDF
[http://arxiv.org/pdf/1908.01094](http://arxiv.org/pdf/1908.01094)


---
layout: post
title: "Hearing your touch: A new acoustic side channel on smartphones"
date: 2019-03-26 20:06:26
categories: arXiv_AI
tags: arXiv_AI Face
author: Ilia Shumailov, Laurent Simon, Jeff Yan, Ross Anderson
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first acoustic side-channel attack that recovers what users type on the virtual keyboard of their touch-screen smartphone or tablet. When a user taps the screen with a finger, the tap generates a sound wave that propagates on the screen surface and in the air. We found the device's microphone(s) can recover this wave and "hear" the finger's touch, and the wave's distortions are characteristic of the tap's location on the screen. Hence, by recording audio through the built-in microphone(s), a malicious app can infer text as the user enters it on their device. We evaluate the effectiveness of the attack with 45 participants in a real-world environment on an Android tablet and an Android smartphone. For the tablet, we recover 61% of 200 4-digit PIN-codes within 20 attempts, even if the model is not trained with the victim's data. For the smartphone, we recover 9 words of size 7--13 letters with 50 attempts in a common side-channel attack benchmark. Our results suggest that it not always sufficient to rely on isolation mechanisms such as TrustZone to protect user input. We propose and discuss hardware, operating-system and application-level mechanisms to block this attack more effectively. Mobile devices may need a richer capability model, a more user-friendly notification system for sensor usage and a more thorough evaluation of the information leaked by the underlying hardware.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11137](http://arxiv.org/abs/1903.11137)

##### PDF
[http://arxiv.org/pdf/1903.11137](http://arxiv.org/pdf/1903.11137)


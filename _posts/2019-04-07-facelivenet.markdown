---
layout: post
title:  "FaceLiveNet: End-to-End Networks Combining Face Verification with Interactive Facial Expression-Based Liveness Detection"
date:   2019-04-07 02:21:59 +00:00
categories: project
image: 
video: /images/facelivenet_teaser.mp4
author: "Hao Gong"
authors: 
venue: "Landmark Vision Tech, co-op with L3i, Université of La Rochelle"
patent: 
paper: 
code: https://github.com/gonghao67/FaceLiveNet
slides: 
website: 
link: 
comment: 
---
We proposed a holistic end-to-end deep networks which can perform face veriﬁcation and liveness detection simultaneously. It is based on the Inception-ResNet structure, designed to have two main branches corresponding to face verification and facial expression recognition. Branch 1 extracts the embedded features for face verification, while Branch 2 calculates the probabilities of the facial expressions. The structures of them are almost same, which can be easier for transfer learning. The two branches were trained with different loss functions, class-wise triplet loss and softmax loss, respectively. Face detection was implemented by the Multi-Task CNN (MTCNN).

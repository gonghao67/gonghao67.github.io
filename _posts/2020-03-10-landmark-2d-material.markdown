---
layout: post
title:  "Automatic Search, Localization and Stacking of 2D Crystals"
date:   2020-03-10 02:21:59 +00:00
categories: project
video: /images/facelivenet.mp4
author: "Hao Gong"
authors: 
venue: "Landmark Vision Tech, co-op with Institute of Optoelectronics at Shanxi University"
patent: 
paper: 
code:
slides: 
website: 
link: 
comment: 
---
The project aimed to develop a robotic system for automatically searching and stacking exfoliated 2D crystals to build van der Waals (vdW) heterostructures. Our primary contribution lied in the computer vision (CV) part of the system, which significantly reduced repetitive manual tasks and served as backbone of automation. It is capable of recognizing 2D crystals, locating and delineating their boundaries, and telling the system when to pick up during the stamping process. The CV algorithms comprised five components: blur detection based auto-focusing, machine learning based detection of Newton's rings, MaskRCNN/transfer learning based 2D material classification and segmentation w.r.t identity (graphite/hBN) and layer thickness, dynamic matching of target material samples using edge features, and wavefront detection of Newton's rings through contour extraction and tracking. Thanks to these sophisticated algorithms, the system can autonomously detect graphene/hBN flakes across varying layer thicknesses with a low error rate (<5%) and assemble them into vdW superlattices requiring minimal human intervention.

---
layout: post
title:  "Semantic Visual Mapping and Localization (Semantic Visual SLAM) in Project AVP (Automated Valet Parking)"
date:   2022-09-30 02:21:59 +00:00
categories: project
image: 
video: /images/avp_hpp_teaser.mp4
author: "Hao Gong"
authors: 
venue: "Enjoy Move Tech"
patent: 
paper: 
code:
slides: 
website: 
link: 
comment: 
---
Led the development of a new SLAM technique to build semantic visual map for self-localization feature in AVP application, using inputs from semantic detection of road markings and IMU-wheel encoder coupled odometry. As vehicle maneuvers, the map evolves in form of a dynamic semantic graph comprising semantic attributes and odometry. Graph optimization then periodically minimizes pose errors of semantic objects and egomotion, updating both local and global mapping. Once complete, vehicle re-localization can be effectively achieved in familiar environments, providing accurate pose estimations that guide vehicle navigation, path planning and control towards designated parking spots.

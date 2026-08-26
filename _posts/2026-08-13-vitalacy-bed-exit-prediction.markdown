---
layout: post
title:  "LSTM-Based Bed Exit Prediction for Smart Virtual Care"
date:   2026-08-13 02:21:59 +00:00
categories: project
image:
video: /images/pred_overlay_tbptt_20260416_R1_B1_P1_E_left_T01.mp4
author: "Hao Gong"
authors:
venue: "Vitalacy"
patent:
paper:
code:
slides:
website:
link:
comment: "[Real-time patient-safety AI system for early bed-exit risk prediction using object detection, human pose estimation, multi-person tracking, and stateful LSTM sequence modeling on edge devices]"
---

Developed a real-time visual AI pipeline for smart virtual care and patient safety applications, with the goal of detecting early bed-exit risk from continuous in-room video streams. The system combines hospital-bed detection, person detection and tracking, human pose estimation, bed-normalized keypoint representation, and temporal sequence modeling to classify patient states into four classes: in-bed, early-risk, high-risk, and out-of-bed.

Designed and trained an LSTM-based temporal model using truncated backpropagation through time (TBPTT) for frame-wise bed-exit prediction. The model consumes pose keypoints normalized with respect to the detected bed region and maintains per-track hidden states during online inference, enabling stable and low-latency prediction without a sliding-window pipeline.

Contributed to the full model-development workflow, including dataset preparation, annotation review, detector and pose-model fine-tuning, model evaluation, ONNX export, ONNX Runtime / TensorRT integration, and edge-device validation. The demo shows the four-class prediction behavior under realistic hospital-room conditions, including pose changes, partial occlusion, and transitions from safe in-bed states to high-risk and out-of-bed events.

---
title: "[Ambient AI] Smoking Detection"
excerpt: "논문 정리"

categories:
  - projects
tags:
  - [tag1, tag2]

permalink: /projects/smokingdetection_0/

toc: true
toc_sticky: true

date: 2022-09-03
last_modified_at: 2022-09-16
---

# 정리해보기   

> ## 1. Introduction   

* 왜 smoke detection이 중요한가?   
Fire incidents.   
_Airports, high-speed trains, gas stations, flammable and explosive warehouses and other smoke-free areas._


* Smoke detection   
Pros of smoke detection by image processing technology is that smoke detection is possible __in a large range__ of detection and __a long distance__ than smoke sensor.   
Smoke detection method is roughly divided into **dectection for smoke** and **detection for cigarette**.   
-> 피는 행위를 하는가, 그게 담배인가)로 나눠서 detect.
   
빠르고 정확하게 탐지하기 위해서 single-stage detection을 사용함.  
YOLOV5 algorithm.   


> ## 2. Model Building   

* 2.1 Custom attention mechanism module   
CBAM module을 참조하여, lightweight하게 CBAM-Tiny를 정의한다.    
CBAM: Convolutional Block Attention Module    

Input -> global maximum pooling & global average pooling -> add F1 & F2 -> 1X1 Conv -> ReLu -> 1X1 Conv -> Sigmoid -> Output   

<p>
<img src = "/Users/ce/ChaiEunLee.github.io/assets/images/projects_smoke_detection_0.png">
</p>


> ## 3. Model Design   
yolov5, 2번의 detect

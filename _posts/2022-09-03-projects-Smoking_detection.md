---
title: "Ambient AI Smoking Detection using google coral"
excerpt: "object detection, google coral, yolov5"

categories:
  - projects
tags:
  - [tag1, tag2]

permalink: /projects/smokingdetection/

toc: true
toc_sticky: true

date: 2022-09-03
last_modified_at: 2022-09-20
---

# 정리해보기   

> ## 1. Motivation  

* **Why smoke detection is important?**   
2022년 8월 폭우로 인한 침수 원인의 일부는 하수구에 버려진 담배꽁초 때문이었다. 그리고 발전소 같이 화재에 민감한 장소에서 담뱃불은 큰 화재로 번질 수 있는 위험성을 가지고 있다. 따라서 흡연을 하기 전에 흡연감지를 통해서 이러한 문제를 예방할 수 있다.     


* **금연구역에서의 흡연 원인**   
1. Lack of Smoking Area    
서울시 기준 금연구역 287,200곳인 것에 비해 흡연구역은 7,089곳 밖에 지정되지 않았다. 따라서 흡연자들은 어쩔수 없이 금연구역에서 흡연을 하게 되는 경우가 발생한다.      

2. Lack of Public Awareness     
흡연구역이 부족하기 때문에 금연구역에서의 흡연이 심각한 사안이라고 생각하지 못하는 사회적 인식도 하나의 원인으로 꼽을 수 있다.     

이 2가지를 해결하기 위해서 흡연부스를 많이 설치하여 데이터를 수집하고 금연구역에서의 경고 시스템을 고도화 시키는데에 사용한다면,     
흡연자들은 흡연구역이 생겨서 만족하고 금연구역은 흡연자들이 많이 오지 않을 것이라고 선순환이 발생할 것이다.     
그리고 금연구역에서의 흡연 시도를 경고음으로 알려준다면 사회적 인식 또한 많이 상승할거라고 판단했다.    


**Egde Device를 통해서 실시간으로 흡연을 할거라고 Object Detection을 진행하여 경고를 주는 시스템을 만들었다.**

> ## 2. System Overview  
* Why vision?    
As micro hardware technologies has been developed, we are able to receive high quality images with smaller cameras. That would be great benefit to us.     

* Why Object Detection? What is better than smoke detector?     
It can detect specific movement/object fast and prevent before smoking starts.

* Why Edge Device?    
It can be used widely in various places with less social/technical entry barrier.   

## 3. Model Design
Step 1.     

![Alt text] /Users/ce/ChaiEunLee.github.io/assets/images/inposts/smokingdetection_modeldesign.png

## 4. Data Preperation

## 5. Challenges

## 6. Results

## 7. Conclusion

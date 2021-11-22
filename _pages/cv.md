---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng. in Automation, Tianjin University, 2018
* M.S. in Computer Engineering, New York University, 2020

Work experience
======
* July 2020 -- present: Data Scientist
  * Oracle Corporation
    * Worked on the project that helps marketers to predict the performance of different marketing strategies. Designed a model which extracts both word and topological information of the market strategies and gives the performance prediction of the new market strategy based on historical data.
    * Participated in designing and developing data science's machine learning platform. Building a machine learning continues integration service for data science team.

* Sep 2018 -- May 2020: Graduate Research Assistant
  * New York University University
  * Supervisor: [Professor Zhongping Jiang](https://engineering.nyu.edu/faculty/zhong-ping-jiang)
    * Worked on safety evaluation of Connected and Autonomous Vehicles(CAVs). Applied a reinforcement learning based optimal control strategy on autonomous vehicles, showing the safety improvement when adding the autonomous vehicle into platoon. 
    * Participated in the research of autonomous vehicles. Applied computer vision methods to help the vehicle recognize the center of the lane and perform a controller learned from experiences through Adaptive Dynamic Programming to keep the vehicle in the center of the lane. 
    * Researched on collision avoidance in unknown environment. Implemented a computer vision method to detect obstacles and help the automated vehicle avoid obstacles.

* Jun 2019 -- Sep 2019: Software Engineer Intern
  * Oracle Corporation
    * Worked on proof of concept of entity resolution. Designed a hierarchical clustering-based algorithm to identify the same users who accessed the website with different IP addresses

* Sep 2015 -- July 2018: Research Assistant
  * Tianjin University
    * Analyzed the EEG data collected from the patients with neurological diseases, obtained the characteristic of EEG signals characterizing the state of diseases.
    * Designed a neural adaptive control strategy for the chaotic synchronization of two electrically coupled FitzHugh-Nagumo (FHN) neurons in the external electrical stimulation. The control scheme integrates the sliding mode control, input-output linearization technique, and neural network approximation. It shows that using the proposed control approach, chaos synchronization between two coupled neurons can be obtained.
    * Designed a brain-computer interface based intelligent rehabilitation robot control system. The coupled FHN neuron model is used to model the plant. The controller adopts the neural network based sliding mode control algorithm, and the coupled neurons are synchronized by adaptively adjusting the control parameters. 
  
Skills
======
* Python
* Tensorflow
* Docker
* Kubernetes
* Java
* C/C++

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service
======
* Teaching assistant for NYU ECE-UY 3064, Feedback Control, Spring 2019

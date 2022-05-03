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
* Ph.D in Mechanical Engineering, Michigan State University, Aug. 2017 - Dec. 2022
* M.S. in Computer Science, Georgia Institute of Technology, Aug. 2019 - May 2022
* M.S. in Material Science and Engineering, Beijing Institute of Technology, Sep. 2010 - Mar. 2013
* B.S. in Material Forming and Control Engineering, Guangdong University of Technology, Sep. 2006 - Jul. 2010




Work experience
======
* **Intel Corporation**, AXG Graphics Research Organization, Santa Clara, CA, Jan. 2022 – Apr. 2022
  * GPU Deep Learning/Software Engineering Intern
    * Optimized inference server in Neural Radian Field (NeRF) Camera using DirectVoxelGO model
    * Generalized and refactored back-end to provide standardized inference APIs to adapt to three NeRF-like models and two front-end interfaces to perform       model inference in real-time
    * Cooperated with software engineers to file a patent of NeRF Camera and extended it to a paper
    * Tested infrastructure of Intel Tiny Neural Network library toward DPC++ kernel development

* **Michigan State University**, Center of Advanced Manufacturing, East Lansing, MI, Aug. 2017 – Dec. 2022 
  * Research Assistant
    * Developed a digital imaging correlation algorithm in Python to dynamically track metallic material flow
    * Automated threshold selection for surface roughness analysis, utilized supervised classification to validate the accuracy of the algorithm (95% mean         accuracy), which outperforms heuristic threshold selection

* **Guangzhou Automobile Corporation**, Automotive Engineering Institute, Guangzhou, China, Apr. 2013 – Jun. 2017
  * Car Door System Engineer
    * Developed and tested scripts in Python to visualize and process over 100GB of car body modeling data
    * Automated data parsing using Numpy and Pandas to improve delivery efficiency by over 40%
    * Developed car door system, performed car testing in extremely cold conditions, resolved 58 technical issues
    * Assisted software engineer in testing and adding new features to Product Data Management System

Project experience
======
* **Facebook Hateful Memes Detection Challenge**
  * Gatech Capstone Group Project
    * Designed a pipeline to classify hateful memes based on Hateful Memes Dataset provided by Facebook
    * Implemented image feature extraction by leveraging Detectron (Mask RCNN + ResNet152)  in Facebook Multimodal Framework
    * Fine-tuned a pre-trained multimodal model (VisualBERT) using hyperparameter search and majority voting
    * Improved prediction accuracy by 13% and AUC by 8.7% compared to baseline results by Facebook

* **Road Event Detection Challenge in Autonomous Driving**
  * Gatech Capstone Group Project
    * Created a pipeline to detect road event (agent, action, location) using Oxford Road Event Awareness Dataset
    * Optimized feature extractor by replacing backbone network (ResNet50 + FPN) with Swin Transformer
    * Enhanced long-tailed data training process by changing focal loss to class-balanced loss
    * Improved 7.1% mAP for road event detection compared to the baseline results
   
* **3D Object Detection in Autonomous Driving**
  * Individual Project
    * Established a pipeline to detect 3D objects in autonomous driving using KITTI dataset
    * Removed ground from lidar data by utilizing RANSAC; applied DBSCAN to cluster over processed data
    * Applied a deep learning model (PointNet) to the clusters to detect the 3D objects, which achieved average precision of  71.5%, 73.4%, and 72.3% for           vehicle, pedestrian, and cyclist in moderate difficulty 


Skills
======
* Programming Languages: C++, Python, Java, MATLAB, SQL, HTML, CSS
* Frameworks & Tools: OpenCV, Pytorch, Linux,  Git, GCP, Facebook Multimodal Framework (MMF)


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Courses
======
* Artificial Intelligence
* Artificial Intelligence for Robotics
* Computational Photography
* Computer Vision
* Computer Network
* Data Structure & Algorithm
* Database & Design
* Deep Learning
* Machine Learning
* Intro to Graduate Algorithm
* Machine Learning for Trade
* Software Architecture and Design
* Software Development Process


Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
 

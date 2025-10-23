---
layout: archive
title:
permalink: /
author_profile: false
redirect_from:
  - /resume
  - /cv
---

{% include base_path %}

<div style="display: flex; align-items: center; gap: 30px; margin-bottom: 30px; flex-wrap: wrap;">
  <div style="text-align: left; max-width: 400px;">
    <h2 style="margin-top: 0;"><strong>Olivier Lessard</strong></h2>
    <p>Ph.D. Candidate in Computer Engineering<br>
    Polytechnique Montreal, MILA<br>
    <i class="fa fa-envelope"></i> olivier-lessard@videotron.ca<br>
    <i class="fa fa-map-marker"></i> Montreal, QC, Canada</p>
    <p><strong>Research Interests:</strong><br>
    Computer Vision, Deep Learning, Robot Learning</p>
  </div>
  <div>
    <img src='/images/LinkedIn IMG_6997.JPG' width='200' style='border-radius: 10px;'>
  </div>
</div>

Education 
======

Ph.D    Computer Engineering,   2026-...<br>
M.A.Sc. Computer Engineering,   2022<br>
B.Eng.  Electrical Engineering, 2021<br>

<img src='/images/mila.jpg' width='70' height='70'>
<img src='/images/polymtl.png' width='200' height='50'><br>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

---

Work experiences
======
**Research Engineer**, Humanitas Solutions, 2025
  * Build AI agents using LLMs, NVIDIA DeepStream, sensor fusion, model optimization for autonomous robots
  * Integrate visual odometry and SLAM solutions into to a fleet of drone simulation (Gazebo)

**AI Product Manager**, IMDS Software, 2023 
  * Won a tender for a new business opportunity by training a large-scale face recognition model on 40M
images, develop a vehicle recognition system for mobile app
  * Use transformer foundation models to improve cursive handwriting recognition with 20% CER reduction
  * Manage a R&D team of 5 researchers and engineers on document analysis and facial recognition, define
research areas and experimental design (OCR/HWR, CRNN, Vit, LLM, few-shot learning)
  * Present as a speaker at the ICDAR 2024 conference a comprehensive document analysis system
  * Collaborate with research labs form Rennes, LaRochelle and Paris Universities

**Computer Vision Scientist**, Enphase Energy, 2022
  * Reconstruct 3D polygonal surfaces from depth images and LiDAR data
  * Develop APIs and 2D object detectors (YOLO, MaskDino) for tree detection

**Computer Vision Scientist** Intern, Hydro-Quebec, 2020
  * Segmenting images using ensemble methods (model averaging) for predictive maintenance
  * Develop an end-to-end training pipeline with MLflow to manage AI models on cloud

***

Skills
======
* Programming: Python (4 years), C++ (2 years), Go (1 year), Java (1 years), Javascript (1 years)
* Libraries: PyTorch, Lightning, TF, Sk-learn, OpenCV, Open3D, ONNX, TensorRT, React, MLflow
* Tools: Git, Docker, AWS, GCP, Jira, Slurm, agile, MS Project, MQTT, PostgreSQL, NVIDIA DeepStream
* Bilingual: French; English
* Autonomy further developed during a student exchange and ease of integration

---


Other social and leadership experiences
======
**AI Annotation Platform Project**  (Personal Initiative) 2025
  * Develop a comprehensive AI platform (https://github.com/OlivierLessard/Hii-Annotation), demonstrating cross-functional expertise in cloud storage, database architecture, frontend development, UX, and zero-shot object detection

**Student Committee Director** (Polyrad) – Polytechnique Montréal 2020-2021
  * Quickly adapting the committee's projects in the context of a pandemic
  * Maintain a long-term vision of the committee and build good relationships with partners
  * Nomination as Director of the Year, members of the committee from 2016 to 2021, testifying to my sustained commitment and leadership abilities.

**Student exchange in Belgium** – Université libre de Bruxelles (ULB) Winter 2018
  *  Integrate quickly into new contexts, adapting to new teaching methods and working with multicultural teams
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
* Ph.D in Computer Science, DePaul University, 2028 (expected)
* M.S. in Artificial Intelligence, DePaul University, 2025
* B.S. in Computer Science, DePaul University, 2023

Work experience
======
* September 2025 – Present: Graduate Research Assistant
  * DePaul University
  * Duties included: Develop and maintain operations of end-to-end agentic conversational speech system. Lead a sub-team optimizing speech-based cognitive biomarkers.
  * Supervisor: Dr. Casey Bennett

* July 2024 – September 2025: Research Assistant
  * DePaul University
  * Duties included: Integrated Arduino sensor array with Raspberry Pi to build real-time activity detection pipelines. Optimized and deployed deep learning models for on-device inference.
  * Supervisor: Dr. Casey Bennett

* Fall 2023: Data Science Intern
  * Vistex, Inc.
  * Duties included: Analyzed sales trends and evaluated the causal impact of price changes. Presented findings to company leadership.
  * Supervisor: Dr. Christopher West

Skills
======
* AI & Machine Learning
  * PyTorch, TensorFlow, Transformers (Hugging Face), NLP
  * Fine-tuning (LoRA/PEFT), quantization, inference optimization
  * Agentic AI, conversational systems, ASR/TTS

* MLOps & Cloud Infrastructure
  * Model serving, Docker
  * Google Cloud (Compute Engine, Storage, VPC/Firewall), AWS, Azure
  * PostgreSQL, REST APIs, Git

* Full-Stack Engineering
  * Python, Django, React.js
  * Nginx, Certbot (TLS/HTTPS), Linux/Bash scripting

* Embedded Systems, Wearables & Signal Processing
  * Raspberry Pi, Arduino, Android, IoT
  * C/C++, Java, Bluetooth/BLE
  * Digital signal processing, sensor fusion, edge AI


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

  
<!--

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

-->
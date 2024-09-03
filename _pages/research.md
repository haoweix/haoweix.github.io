---
layout: archive
title: "Research Experience"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

Education
======
* Ph.D in University of Michigan, Ann Arbor, 2024
  * GPA: 3.93/4.0
  * Some Coursework: Funtional Analysis, Nonlinear Programming, Convex optimization
* M.S. in University of Michigan, Ann Arbor, 2019
  * GPA: 3.95/4.0
  * Some Coursework: Probability and Random Process, Matrix Theory, Machine Learning, Computer Vision, Image Processing
* B.S. in Huazhong University of Science and Technology, 2017
  * GPA Ranking: Top 3 among over 200 students
  * Qiming Honor Program (top 10%)
  * Outstanding Graduates Award & Excellent Academic Performance Scholarship

Research experience
======
* Feb 2021 - Present: Research Assistant @ EECS, University of Michigan
  
  Advisor: Jeffrey A. Fessler and Douglas C. Noll. 
  
  RF pulse design, sampling trajectories optimization and image reconstruction for novel silent MRI pulse sequence
  
  * Programmed silent MRI pulse sequence for the research and clinical scanners from multi-vendors using TOPPE and Pulseq
  * Designed functional tasks, including visual, motor and auditory simulation and collected fMRI data from over 20 subjects
  * Reconstructed images using model-based methods and learning-based methods, including **Plug-and-Play, unrolled neural networks** to resolve image artifacts and improve image resolution
  * Optimized 3D non-Cartesian sampling trajectories using **learning-based methods** to optimize the gradients and trajectories under the constraints of gradient peak amplitude and slew rate
  * Computed the shaped RF pulse for silent MRI to create more uniform excitation profiles
  * Developed spatial-temporal reconstruction methods including **UNFOLD and Low-rank models** for in-vivo fMRI data to boost the functional analysis
  
* Jan 2019 - Nov 2019: Research Assistant @ Medical School, University of Michigan

  Advisor: Yuni K. Dewaraja, Jeffrey A. Fessler. 

  This project aims to build a deep Convolutional Neural Networks to fastly and accurately predict scatter distribution of 3D SPECT/CT imaging.

  * Designed **multi-input physics-informed neural network** architecture tailored to 3D SPECT/CT system
  * Predicted the distribution of scatter from SPECT/CT using **deep convolutional neural network** and the estimation shows good alignment to the gold standard method
  * Reduced the computational time for **over 100X** from multiple hours using **Monte-Carlo simulation** to one minute using GPU.

* Jan 2018 - Aug 2018: Research Assistant , University of Michigan

  Acceleration of Convolutional Dictionary Learning and Convolutional Analysis Operator Learning by applying sketching method. This project won the first place in the KLA-Tencor Image Processing Contest ([Award](https://ece.engin.umich.edu/stories/students-win-prizes-for-improving-image-processing-techniques-for-liver-cancer-detection-and-much-more)).
  
Skills
======
* Computer language
  * Python: Pytorch, Tensorflow, Numpy, Scipy, Pandas
  * C/C++
  * MATLAB
  * SQL
  * Julia
* Others: Cloud Computing, Linux, SLURM, Latex, Git

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

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Reviewer for NeuroImage, Computers in Biology and Medicine, and ISMRM

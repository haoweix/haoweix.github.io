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
* B.S. in Huazhong University of Science and Technology, 2017
* M.S. in University of Michigan, Ann Arbor, 2019
* Ph.D in University of Michigan, Ann Arbor, 2024 (expected)

Research experience
======
* Feb 2021 - Present: Research Assistant @ EECS, University of Michigan
Advisor: Jeffrey A. Fessler and Douglas C. Noll. Designed and built novel Silent MRI techniques to reduce the acoustic noise in MRI, resolve the discomfort and anxiety in patients, and improve image qualities.  

  * Optimized sampling trajectories using learning-based methods and improved peak signal-to-noise ratio by more than 3 dB
  * Reconstructed images using statistical models, resolved image artifacts, and improved image resolution by 2x
  * Programmed silent MRI pulse sequence for the research lab on multiple scanners

* Jan 2019 - Nov 2019: Research Assistant @ Medical School, University of Michigan
  
  Advisor: Yuni K. Dewaraja, Jeffrey A. Fessler. This project aims to build a deep convolutional neural networks to fastly and accurately predict scatter distribution
  of SPECT/CT imaging.
  
  * Predict the distribution of scatter from SPECT/CT using deep convolutional neural network within seconds
  * Predicted scatter effect using CNN yielded comparable results to traditional gold standard which took hours
  * Applied mathematical method to evaluating the deep learning model performance
  
Skills
======
* Python
  * Pytorch
  * Numpy
  * Scipy
  * Tensorflow
  * Pandas

* MATLAB
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* SQL

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams

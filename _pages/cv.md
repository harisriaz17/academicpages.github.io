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
* B.S. in Computer Science, National University of Sciences & Technology, 2021 (expected)
  * __CGPA 3.71/4__

Work experience
======
* __March 2020 - Present: Research Intern @ [TUKL-NUST](https://tukl.seecs.nust.edu.pk/) R&D Center__ 
  * Currently working on my bachelor’s thesis ”In-Air handwriting recognition for signature verification” in collaboration with German Center for Artificial Intelligence (DFKI).
  * Experimented with LSTM’s, GRU’s and Transformers for recognizing text written in-air using IMU signals from a Myo-armband sensor
  * Supervisor: [Dr. Imran Malik](https://scholar.google.com/citations?user=W0u4ORoAAAAJ&hl=en)

* __June 2019 - Present: Machine Learning Intern @ [CERN](https://home.cern/)__ 
  * Worked on binary classification of rare signal versus background in ultra-relativistic heavy-ion collisions, as part of an open source library used by the [ALICE](https://home.cern/science/experiments/alice) experiment.
  * Implemented and compared performances of XGBoost, Random Forest & Keras algorithms on large imbalanced datasets.
  * Worked on an automated hyperparameter tuning pipeline using Bayesian optmisation.
  * Trained different variants of UNet to predict & correct space charge distortions in the Time Projection Chamber (TPC).
  * Implemented residual dilated UNet and an effective validation strategy for comparing models.
  * Presented an Internal Report on Tensorboard Studies of UNet model to members of the collaboration.
  * Supervisor: [Dr. Gian Michele Innocenti](https://www.researchgate.net/scientific-contributions/Gian-Michele-Innocenti-54637500)
  
* __June 2018 - September 2018: Software Development Intern @ System Analysis & Verification ([SAVe](http://save.seecs.nust.edu.pk/)) Lab__
  * Led development of a C++ based white-box testing tool.
  * Worked on routines for automatic exception, assertion and dead code testing.
  * Developed a GUI using Qt.
  * Added support for parsing multiple datatypes with regex.
  * Reviewed literature on state of the art white-box testing and parsing techniques & wrote a general paper documenting our work. [Link.](https://www.dropbox.com/s/xiguib0grfk9dmn/ADE_testbot.pdf?dl=0)

Skills
======
* Python, C, C++, Java
* Deep learning frameworks: Tensorflow/Keras, PyTorch 
* Javascript: React, React Native, Express.js, Node.js
* Databases: SQL, NoSQL: MongoDB, Mongoose
* Windows & Linux/Unix
* Certified MS Office (Word, Excel & Powerpoint) expert.
  * [MS Word Specialist Certification](https://www.youracclaim.com/badges/3db4be19-cf8c-43ba-9434-1df612103b70/public_url)
  * [MS Excel Specialist Certification](https://www.youracclaim.com/badges/d803faa0-3b74-43fd-86db-2328d002442c/public_url)
  * [MS Powerpoint Specialist Certification](https://www.youracclaim.com/badges/7d485a7e-1f8b-4548-bed5-e9316b1ac067/public_url)

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
* NUST Community Services Club (NCSC): Organized multiple donation drives to fund primary education for orphaned/underprivileged children.
* SEECS Declamation Chapter: Member of Speakers Pool.

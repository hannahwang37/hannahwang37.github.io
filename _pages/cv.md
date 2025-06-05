---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV as PDF](/files/cv.pdf)

Education
======
* **Ph.D. in Computer Science**, Vanderbilt University, Nashville, U.S. (Aug. 2023 - Expected May 2028)
* **B.Eng. in Software Engineering**, Nanjing Normal University, Nanjing, PRC (Sep. 2019 - Jun. 2023)

Experience
======
* **Research Assistant** (Aug. 2023 - Present)
  * Vanderbilt University
  * Advisor: [Prof. Matthew Berger](https://engineering.vanderbilt.edu/bio/?pid=matthew-berger)
  * Working on visual analysis for neural fields, focusing on adapting machine learning techniques to improve visual data exploration and how visualization can be used to help various aspects of machine learning.

* **Research Intern** (Oct. 2022 - Apr. 2023)
  * The Hong Kong University of Science and Technology
  * Advisor: [Prof. Zeyu Wang](https://cislab.hkust-gz.edu.cn/members/zeyu-wang/)
  * Co-advisor: [Prof. Wei Zeng](https://zeng-wei.com/)
  * Contributed as a primary author to a research paper that was accepted and published in Visual Informatics.

* **Research Intern** (Jul. 2022 - Dec. 2022)
  * Shandong Future Network Research Institute
  * Independently developed and implemented a backend algorithm module for a computer vision project, which successfully passed the testing phase.

* **Elite Talent Program** (Nov. 2020 - Nov. 2022)
  * Nanjing Normal University
  * Selected as one of the Top 30 students across the university. Worked in a team of three under the guidance of [Prof. Richen Liu](https://dabigtou.github.io/richenliu/), where we completed research tasks and co-authored multiple papers. Our team was funded with $10,000 by the school.

Research Projects
======
* **Feature-driven parameter space exploration of simulation ensembles** (Apr. 2024 - Present)
  * **Inverse Mapping via Latent-Space Learning**: Developed a bidirectional latent space bridging simulation parameters and outputs, enabling real-time inverse design from user-specified features while maintaining low dimensionality proportional to parameter count.
  * **Flexible Feature Extraction with Implicit Neural Representations**: Leveraged INRs to achieve highly compressed yet accurate field representations, multi-scale feature support, and derivative-based feature computation.
  * **Interactive Interface**: Developed an interactive interface supporting multiple interactions with different large-scale simulation ensembles.

* **TopologyGuidance: Controlling the Outputs of Generative Models via Vector Field Topology** (Sep. 2023 - Mar. 2024)
  * **Topology Guidance for DDPM**: Innovated a method to control diffusion model outputs to align with specified topological features using a coordinate-based neural network.
  * **Enhanced Controllability**: Improved generative model precision by guiding the denoising process based on topological signals.
  * **Validation**: Proved method effectiveness on 2D vector fields in fluid flows, accurately maintaining critical points.

* **EmotionLens: Interactive Visual Exploration of the Circumplex Emotion Space** (Nov. 2022 - Mar. 2023)
  * Created a new emotion dataset including literary works from different time periods, genres, and languages.
  * Designed an interactive system enabling users to analyze literary emotions at different levels and perspectives.
  * Introduced an enhanced affective word cloud adjusting word weight, position, and color.

* **BallonVis: Hybrid Line-Based and Region-Based Interactive Set Data Visualization Tool** (Oct. 2020 – Feb. 2021)
  * Designed a Balloon Connection Method based on the item connection blob algorithm.
  * Combined control points to bypass obstacles while connecting data items by lines.
  * Designed energy optimization-based routing algorithm and spring force algorithm.

Fellowships, Honors, and Awards
======
* **2022**: Outstanding Student Scholarship - First Prize (Top 5%)
* **2021**: Outstanding Student Scholarship - First Prize (Top 5%)
* **2021**: Outstanding National Computer Design Competition (Software Development) - First Prize
* **2020**: Outstanding Student Scholarship - First Prize (Top 5%)

Skills
======
* **Programming Languages**: Python, C++, JavaScript, MATLAB
* **Machine Learning**: PyTorch, TensorFlow, Neural Networks, Diffusion Models
* **Data Visualization**: D3.js, VTK, Interactive Systems Design
* **Computer Vision**: OpenCV, Image Processing, RANSAC
* **Web Development**: HTML/CSS, React, Node.js

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
* Currently signed in to 43 different slack teams
